Preparación

Bloque 1

Evaluación Regresión

Métricas para medir el error
• MAE: Error en positivo.

o Cuánto te equivocas de media
o Trabaja en las mismas unidades que los datos
o (2+5+2)/3 = 3. Te equivocas de media 3 unidades.

• MSE: Error elevado al cuadrado.
o Penaliza mucho errores grandes
o (4+25+4)/3 = 11. Te equivocas de media 11 unidades al cuadrado.

• MAPE: Error en porcentaje.
o Te dice el error relativo
o Penaliza errores pequeños
o 10/100 = 0.1. Te equivocas de media 10%.

Evaluación Clasificación

Métricas para medir el acierto

• Exactitud: Acertados en total.
o Solo para datos balanceados

• Precisión: Si detecto positivo, ¿realmente lo es?

o Penaliza falsos positivos
o Si lo aumento detecto menos pero con menos errores
o Calidad de positivos

• Recall: De todos los positivos, ¿cuántos detecto?

o Penaliza falsos negativos
o Si lo aumento detecto más pero con más errores
o Cobertura de positivos

Tipos de datos

• Estructurados: tablas.

• No estructurados: texto, imágenes, audio, vídeo.

• Semi estructurados: páginas web, formulario con etiquetas.

Datasets

• Entrenamiento: aprende la función f(x).

• Validación: optimiza hiperparámetros de f(x).

• Test:  comprobar rendimiento.

Validación cruzada

• K-fold cross validation: dividimos los datos en varias partes aumentando test-validación.

o Si entrenas 5 folds al modelo A y modelo B, haces la media y ves cuál de los 2 es mejor.

• Stratified k-fold: mantiene la proporción de clases (para desbalanceadas)

Bloque 2

Histograma

• ¿Es simétrico o sesgado?

o Si cola hacia un lado, muchos valores pequeños/grandes

• ¿Hay outliers?

o Barras  separadas al resto, distorsionan entrenamiento

• ¿Está muy disperso?

o Si es ancho, mucha variabilidad, dificil de predecir

• ¿Tiene varios picos?

o Unimodal o multimodal (varios grupos/comportamientos)

• ¿Necesito transformar los datos?

o Si cola larga o muchos outliers ⭢ log(x) o sqrt(x)

Histograma

• ¿Cómo de disperso es mi gráfico?
o Rango Intercuartílico = Q3 – Q1
o Q1 = 2.5, Q3 = 6.5, RIC = 4
o El 50% de los datos se distribuye en un intervalo de 4 unidades
o Ignora los outliers

Medidas de dispersión

• Varianza: cuánto se alejan los datos de la media (juntos o dispersos)

o Se da en unidades al cuadrado

• Desviación típica: es la raíz cuadrada de la varianza

o Devolvemos a las unidades originales

Boxplot

• ¿Cuánta dispersión?

o Si es grande la caja, mucha.

• ¿Distribución simétrica o sesgada?

o Si la mediana está centrada, simétrica.

• Longitud de bigotes

o Si es más largo de un lado, hay sesgo hacia ese lado.

• Outliers

o Puntos fuera de los bigotes.

• Simetría

o Si mediana, forma caja, longitud de bigotes parecido, datos equilibrados.

Boxplot

• ¿Hay relación?

o positiva, negativa, ninguna

• ¿Es lineal o no lineal?

o Si es curva se necesita modelos más complejos (árboles, redes)

• ¿Está muy disperso o concentrado?
o Si puntos muy juntos relación fuerte

• ¿Hay outliers?

o Puntos lejos del resto que distorsionan

• ¿Hay grupos o patrones?

o Puede haber grupos/clusters indicando varios comportamientos

Cuándo usar un gráfico u otro

Gráfica

Nº de variables

¿Cuándo usarla?

Qué información da

Ejemplo sencillo

Histograma

1

Ver cómo se
distribuyen los
datos

Forma (simetría, sesgo),
concentración

Boxplot

1 (o varias para
comparar)

Resumir
distribución y
detectar outliers

Mediana, cuartiles,
dispersión, outliers

Dispersión
(Scatter)

2

Analizar relación
entre variables

Correlación, tendencia,
patrones

Ver cómo se
distribuyen las notas
de un examen
(cuántos sacan 5, 7,
9…)

Ver si hay alumnos
con notas muy altas o
muy bajas fuera de lo
normal

Ver si más horas de
estudio implican
mejores notas

Coeficiente de Pearson

Indica correlación lineal entre dos variables

• ¿Qué tipo de relación tiene?

o Si +1; una sube y la otra sube, si 0; no relación, si -1: una sube otra baja

• ¿Cuánta fuerza tiene la relación?
o Cuanto más cerca a ±1; más fuerte

• No detecta relaciones no lineales

• Sensible a outliers

Covarianza y su Matriz

Cómo varían dos variables juntas. Es como la correlación de Pearson pero sin normalizar.

• ¿Qué tipo de relación tiene?

o Si >0; positiva, si 0; no relación, si <1: negativa

Bloque 3

Transformación de datos

Datos en misma escala, eliminación de atípicos y de nominal a binario

• Importante en Regresión Lineal, Redes y SVM

o Evita que unas variables dominen a otras. En árboles da igual.

• Se convierten variables categóricas a numéricas
o Se utiliza One-Hot-Enconding cuando no tienen orden

Datos redundantes

Se eliminan para reducir tamaño, modelo más rápido y reducir multicolinealidad

• Detección

o Variables muy correlacionadas. Utilizamos Pearson y PCA (reducción de dimensiones)

• Se convierten variables categóricas a numéricas
o Se utiliza One-Hot-Enconding cuando no tienen orden

• Puede que no sean exactamente iguales...

o Pero representan la misma entidad, conocido como Record Linkage. O se fusiona o se elimina.

Datos ausentes

Limitan la generación y producen sesgos

• Identificación

o Nan, centinela, cadena vacía, infinito

• Tratamiento

o Eliminación: pierdes información
o Imputación: por media, mediana, moda, valor constante o interpolación a partir de otras variables. Pueden ser

estratificadas o no (tomando los valores del grupo)

Bloque 4

Errores Regresión Lineal

Se calculan con el método de mínimos cuadrados.

Evaluación Regresión

Otras métricas para medir el error

• RMSE: Error raiz de MSE

o Mismas unidades que los datos
o Penaliza mucho los errores grandes

• RMLSE: Error logarítmico RMSE

o Compara proporciones
o Penaliza más errores relativos que absolutos (errores con pocas muestras penalizan más que en muchas)

• Coeficiente R^2

o Porcentaje de los datos que explica el modelo
o R^2 = 0.8 → el modelo explica el 80% de la variabilidad

Descomposición sesgo / varianza

• Desajuste: si mucho sesgo (no capta las relaciones relevantes)

• Sobreajuste: si mucha varianza (captura ruido del entrenamiento)

• Descomposición sesgo / varianza: hay que encontrar un equilibrio

o Error = Sesgo^2 + Varianza + ruido

Bloque 5

Evaluación Clasificación

• Matriz de confusión: siendo los casos positivos los de interés.

• Especifidad: negativos correctamente clasificados.

• F-score: combina precisión y sensibilidad (recall).

Evaluación Clasificación

• ROC (Receiver Operating Characteristic): gráfica de cómo de bien detecta nuestro modelo

con el compromiso de detectar verdaderos positivos y cometer falsos positivos.

• AUC (Area Under Curve): resume ROC en un número

o Si 1; perfecto, si 0.5: aleatorio, si <0.5 azar.

Bloque 6

Árboles de decisión

• DT es un tipo de aprendizaje supervisado: permite

problemas de regresión y clasificación.

• Cómo funciona: divide/segmenta las variables

predictoras

o Estructura: Nodo raíz → primera decisión, Nodos internos →

preguntas, Hojas → resultado final

• Criterios de división

o Clasificación: Gini o Reducción Entropía/Ganancia Información
o Regresión: Error cuadrático MSE

• Concepto de pureza: un nodo es puro si todos los
datos pertenecen a la misma clase. Entonces, el
objetivo es maximizar la pureza.

• Decisión

o Clasificación: se decide etiqueta
o Regresión: se decide valor

Árboles de decisión

• Índice de Gini: mide lo mezclados que están los datos de un nodo. La pureza.

o Si Gini = 0; completamente puro
o Si Gini >0.5; muy mezclado

• Ganancia de información: calcula diferencia de entropías antes y después de la

división. Se busca reducir entropía y maximizar GI.

o Si GI = 0; no mejora
o Si GI alto; buena separación

Árboles de decisión

• Ventajas

o Preprocesamiento sencillo
o Explicabilidad
o Interpretable

• Desventajas
o Overfitting
o Inestabilidad (sensible a pequeños cambios de datos)
o Poca precisión en algunos casos (necesitan muchos datos)

Árboles de decisión

• Overfitting: para combatir este fenómeno se utilizan las siguientes técnicas

o Prepoda: impedir crecimiento del árbol
o Pospoda: permite que crezca y luego se poda

Qué modelo elegir

Por ahora, hemos visto Regresión Lineal y Árboles de decisión

• Relación lineal o simple: funciona mejor RL, ya que:

o Es simple
o Captura bien relaciones lineales
o Generaliza más (menos overfitting)

• Relación no lineal o compleja: funciona mejor DT, ya que:

o Captura bien relaciones no lineales
o Maneja interacciones entre variables
o Divide el problema en reglas

Cafés: 1 → productividad: 2
Cafés: 2 → productividad: 4
Cafés: 3 → productividad: 6

productividad = 2 × cafés

Cafés: 1 → productividad: 5
Cafés: 2 → productividad: 7
Cafés: 3 → productividad: 9

más café → más productividad
Y
demasiado café → baja productividad

Bloque 7

Máquina de Vectores de Soporte SVM

• SVM: busca la mejor frontera para separar las clases de la forma más segura.

• Concepto de margen: distancia entre la frontera y los puntos más cercanos. Se busca

maximizar el margen.

• Vectores de soporte: los puntos más cercanos a la frontera. Deciden donde está

frontera, son los más importantes.

• Hiperplano: línea que separa las clases

o 2D → línea
o 3D → plano
o ND → hiperplano

• Parámetro C: controla el equilibrio

o C alto → menos errores pero más overfitting
o C bajo → más margen pero más errores

Máquina de Vectores de Soporte SVM

• Tipos de SVM

• El truco del Kernel: SVM transforma los datos a más dimensiones para separarlos más

facilmente. Hay los siguientes tipos de Kernel:

o Lineal: separa en línea recta

o Polinómico: fronteras curvas

o RBF: frontera muy flexibles y complejas. Separa en forma de burbuja/región

o Sigmoide: tipo red neuronal

Máquina de Vectores de Soporte SVM

• Hard margin: el modelo busca una separación perfecta. Solución ideal.

• Soft margin: permite errores. Funciona con ruido y generaliza mejor.

o C alto castiga mucho los errores (se asemeja a hard margin)
o C bajo permite más errores

Qué modelo elegir

RL → relación simple y lineal

Árbol → decisiones, reglas, lógica tipo if-then

SVM → separación compleja

Regresión
Lineal (RL)

Árbol de
Decisión (DT)

SVM

 (Recom)

 (No)

 (Requisito)

 (one-hot)

 (one-hot)

 (one-hot)

Aspecto

Relación lineal

No linealidad

Interpretación

Overfitting

Necesita
normalización

Datos categóricos
(sklearn)

Sensible a outliers

Complejidad

Alta dimensión

Bloque 8

Clasificación con Naïve Bayes

• Naïve Bayes: calcula la probabilidad de que un dato pertenezca a una clase. Se llama
Naïve (ingenuo) porque parte de que todas las variables son independientes entre sí.

o Ejemplo: en un email la palabra oferta y la palabra gratis asume que no están relacionadas.

Tablas de probabilidad condicionada

¿Es un zorro o un Therian?

Dataset

Animal

Zorro

Zorro

Zorro

Therian

Therian

Therian

Cola
esponjosa

Aullido
mágico

Sí

Sí

Sí

No

Sí

No

No

No

Sí

Sí

Sí

Sí

Tablas de probabilidad condicionada

¿Es un zorro o un Therian?

Tabla a Priori

Dataset

Animal

Zorro

Zorro

Zorro

Therian

Therian

Therian

Cola
esponjosa

Aullido
mágico

Sí

Sí

Sí

No

Sí

No

No

No

Sí

Sí

Sí

Sí

• Zorro = 3 zorros / 6 total = 0.5

• Therian = 3 therians / 6 total = 0.5

Clase

P(clase)

Zorro

Therian

0.5

0.5

Tablas de probabilidad condicionada

¿Es un zorro o un Therian?

Tabla Verosimilud

Dataset

Animal

Zorro

Zorro

Zorro

Therian

Therian

Therian

Cola
esponjosa

Aullido
mágico

Sí

Sí

Sí

No

Sí

No

No

No

Sí

Sí

Sí

Sí

Zorro

Therian

• Cola sí = 3 / 3 = 1

• Cola sí = 1 / 3 = 0.33

• Cola no = 0 / 0 = 0

• Cola no = 2 / 3 = 0.66

• Aullido sí = 1 / 3 = 0,33

• Aullido sí = 3 / 3 = 1

• Aullido no = 2 / 3 = 0,66

• Aullido no = 0 / 0 = 0

Variable

Zorro

Therian

Cola sí

Cola no

Aullido sí

Aullido no

1

0

0.33

0.66

0.33

0.66

1

0

Tablas de probabilidad condicionada

¿Es un zorro o un Therian?

Tabla Verosimilud Conjunta

Dataset

Animal

Zorro

Zorro

Zorro

Therian

Therian

Therian

Cola
esponjosa

Aullido
mágico

Sí

Sí

Sí

No

Sí

No

No

No

Sí

Sí

Sí

Sí

Entra nuevo dato:
Cola sí y Aullido sí

¿Es zorro?

Verosimilitud: P = 1 x 0.33 = 0.33

Priori: P = 0.5 x 0.33 = 0.16

¿Es therian?

Verosimiltud: P = 0.33 x 1 = 0.33
Priori: P = 0.5 x 0.33 = 0.16

Tablas de probabilidad condicionada

¿Es un zorro o un Therian?

Tabla Verosimilud Marginal

P(datos): P = 0.16 + 0.16 = 0.33

Dataset

Animal

Zorro

Zorro

Zorro

Therian

Therian

Therian

Cola
esponjosa

Aullido
mágico

Sí

Sí

Sí

No

Sí

No

No

No

Sí

Sí

Sí

Sí

Tablas de probabilidad condicionada

¿Es un zorro o un Therian?

Dataset

Animal

Zorro

Zorro

Zorro

Therian

Therian

Therian

Cola
esponjosa

Aullido
mágico

Sí

Sí

Sí

No

Sí

No

No

No

Sí

Sí

Sí

Sí

Tabla a Posteriori
Zorro
0.16 / 0.33 = 0.5

Therian
0.16 / 0.33 = 0.5

Resultado: empate.

A priori → probabilidad inicial
Verosimilitud → probabilidad de características

Marginal → normaliza
A posteriori → decisión final

Clasificación con Naïve Bayes

• Naïve Bayes clásico no soporta variables numéricas: hay que tranformarlas a

categóricas

o Binning: números en categorías

▪

▪

▪

0 – 18: joven

18 – 65: adulto

65+: mayor

o K-Bins: dividir los datos en intervalos automáticos

▪

Salario:  [0-1000], [1000-3000], [3000-10000]

▪ Métodos: Uniforme, Cuartiles, Clusters

Qué modelo elegir

RL → relación simple y lineal

Árbol → decisiones, reglas, lógica tipo if-then

SVM → separación compleja

Naïve Bayes → muchas variables, texto,
probabilidades

Aspecto

Relación lineal

No linealidad

Interpretación

Overfitting

Necesita
normalización

Regresión
Lineal (RL)

Árbol de
Decisión
(DT)

SVM

Naïve
Bayes

️

 (Recom)

 (No)

 (No)

(Requisito)

 (one-

hot)

Datos categóricos
(sklearn)

 (one-hot)

 (one-hot)

Texto

Velocidad

Relaciones complejas

Bloque 9

Combinación de clasificadores

Se combinan varios modelos simples para conseguir uno mejor
• Técnica Bootstrapping: crea variabilidad entre modelos generando múltiples dataset a
partir de uno. Se hace muestreo con reemplazo. Algunos datos no aparecerán, otros se
repetirán.

• Bagging: Booststrapping + múltiples modelos en paralelo + combinación resultados.

o Se generan múltiples datasets, se entrena un modelo por cada uno y se combinan los resultados de

clasificación y regresión

• Boosting: combina modelos secuencialmente. Cada modelo aprende de los errores del

anterior.

o AdaBoost
o Gradient Boosting
o XGBoost

• Stacking: se entrenan varios modelos diferentes y un Meta Modelo toma como

entradas sus predicciones y las combina

Combinación de clasificadores

• Out of Bag Error: evaluar el modelo sin necesidad de utilizar un conjunto de test

separado.

o Se utiliza en modelos de Bootstrapping como Random Forest
o El árbol se entrena con una muestra del dataset reemplazo

• Cómo funciona el cálculo  de error de OOB

o Dataset <A, B, C, D>; Bootstrap <A, B, B, D>, OOB <C>
o Para cada dato se buscan los árboles donde no se han usado y en ellos se predecirá ese valor y se calcula

el error con la realidad

o Como cross-validation pero automático y sin dividir el test
o Bootstrapping solo puede usarse con algunos modelos (Bagging o Random Forest)

Bloque 10

Random Forest

Es un tipo de Ensembles (modelos combinados). Combian weak learners para formar un
modelo más complejo.

• Técnica Bagging:  se combinan en paralelo, utilizando bootstrapping. Usada por

Random Forest.

• Problemas de los DT: sobreajustan, inestables al ruido y gran varianza

• Random Forest: soluciona estos problemas cogiendo la moda en problemas de

clasificación y la media en regresión.

Random Forest Hiperparámetros

Hiperparámetro

Qué hace

Ejemplo sencillo

n_estimators

Nº de árboles en el modelo

max_depth

Profundidad máxima de cada árbol

Si pones 100 → el modelo crea 100 árboles y votan
entre ellos

max_depth=3 → el árbol solo tiene 3 niveles (menos
complejo)

min_samples_split

Nº mínimo de datos para dividir un
nodo

2 → divide fácilmente; 10 → necesita más datos para
dividir

min_samples_leaf

Nº mínimo de datos en una hoja

1 → hojas pequeñas; 5 → hojas más grandes (más
general)

max_features

Nº de variables usadas en cada
división

"sqrt" → usa solo algunas variables → más variedad
entre árboles

bootstrap

Si usa muestreo con reemplazo

True → cada árbol ve datos distintos; False → todos
ven lo mismo

oob_score

Usa datos fuera del bootstrap para
evaluar

True → calcula error sin usar test externo

criterion

Cómo decide dividir nodos

random_state

Controla la aleatoriedad

"gini" → busca pureza; "entropy" → reduce
incertidumbre

random_state=42 → siempre obtienes el mismo
modelo

n_jobs

Nº de CPUs usadas

n_jobs=-1 → usa todos los núcleos → más rápido

Random Forest Hiperparámetros

• n_estimators → “cuántos árboles tengo”

• max_depth → “qué tan profundos son” (en la práctica no tiene influencia)

• max_features → “qué variables miran”

Random Forest

• Ventajas

o Reduce overfitting
o Robusto frente a ruido y variabilidad
o Modelo de propósito general

• Desventajas

o Poca interpretabilidad
o Ajuste de hiperparámetros pero no mucho
o Pesado computacionalmente

Bloque 11

Parametrización automática

Los hiper parámetros son valores que configuran el modelo antes de entrenarlo. Los elige
el ingeniero.

• Parámetro o hiperparámetro: la diferencia es que los parámetros los elige el modelo

durante el entrenamiento, y los hiperparámetros tú antes del entrenamiento.

• Principales hiperparámetros:

o Regresión Lineal: λ (regularización), tipo de regularización (L1, L2)
o Árbol de decisión: max_depth, min_samples_split, min_samples_leaf
o Random Forest: n_estimators, max_depth, max_features
o SVM: C, kernel
o Naïve Bayes: tipo (Gaussian, Multinomial, Bernoulli), smoothing (α)

Parametrización automática

Buscamos la mejor combinación de hiperparámetros.

• Búsqueda por rejilla (Grid Search): prueba todas las combinaciones posibles en la

rejilla C y Gamma.

• Búsqueda aleatoria (Random Search): prueba combinaciones al azar pero no todas,

solo algunas representativas.

• Búsqueda Bayesiana: usa probabilidad para elegir los mejores valores posibles.

• Optimización por gradiente: optimiza matemáticamente (entrena los

hiperparámetros).

• Optimización evolutiva: selección, mutación y selección. Explora

soluciones complejas que van sobreviviendo.

Parametrización automática

Método

 Ventaja principal

Grid Search

Encuentra el mejor en el
rango

 Desventaja

principal

Muy lento

 Cuándo usar

Pocos parámetros

Random Search Rápido

No garantiza el mejor

Muchos parámetros

Bayesiano

Gradiente

Evolutivo

Muy eficiente

Muy rápido

Explora bien

Más complejo

Optimización seria

Difícil de aplicar

Casos específicos

Costoso

Problemas complejos