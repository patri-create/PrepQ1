Tema 1:
Introducción al aprendizaje automático

1

Índice

Introducción y objetivos

•
• Conceptos clave del aprendizaje supervisado
• Aprendizaje supervisado: problemas de regresión
• Aprendizaje supervisado: problemas de clasificación
• Etapas en un proyecto de aprendizaje automático
• Datos de entrenamiento y  datos de test

– Sobreajuste
– Evaluación cruzada

2

Introducción y objetivos

3

Inteligencia Artificial

• La inteligencia artificial es una disciplina en la que se

pretende obtener sistemas capaces de realizar tareas que
normalmente requieren inteligencia humana:
– Aprender
– Razonar
– Tomar decisiones y resolver problemas
– Tareas cognitivas: lenguaje, comprensión visual, olfativa

Generalmente, se acepta como
inicio de la disciplina el artículo
de Alan Turing Computing
Machinery and Intelligence
(1950, test de Turing) y en 1956
la Conferencia de Dartmouth

4

Aprendizaje automático

• Algoritmos que se ejecutan en ordenadores para aprender
automáticamente de los datos y ejecutar ciertas tareas

Programación Tradicional

Aprendizaje Automático

Instrucciones
lógicas

Datos de
Entrada

Datos
históricos

Programa

Resultados

Datos de
Entrada

Programa

Resultados

Algoritmo

5

Sistemas de aprendizaje automático

• Su presencia es cada vez más ubicua
• EU Artificial Intelligence Act

– “Sistema de IA":

• Un sistema basado en máquinas que está diseñado para funcionar con

diversos niveles de autonomía y que puede mostrar capacidad de adaptación
tras su despliegue, y que, para objetivos explícitos o implícitos, infiere, a partir
de la entrada que recibe, cómo generar salidas tales como predicciones,
contenidos, recomendaciones o decisiones que pueden influir en entornos
físicos o virtuales

6

Lluvia de ideas

• ¿En qué aplicaciones se utiliza el aprendizaje automático?

–
–
–
–
–

7

¿Qué tareas ejecuta ?

• Clasificar todo tipo de imágenes
• Detectar usos fraudulentos de tarjetas de crédito a partir de

transacciones
Identificar temas en un conjunto de artículos de blog

•
• Recomendar productos ej. en Amazon

8

Aprendizaje Automático e Inteligencia Artificial

• Es un subcampo de la inteligencia artificial
• Engloba al aprendizaje profundo y a la inteligencia artificial

generativa

Inteligencia Artificial

Aprendizaje Automático

Aprendizaje Profundo

IA
Generativa

9

Clases de Aprendizaje Automático
• Clasificación dependiendo
– paradigmas de aprendizaje
– naturaleza de los datos

Aprendizaje Automático

Supervisado

No supervisado

Por refuerzo

Utiliza
ejemplos
conocidos

Sin ejemplos.
Agrega por
distintos
criterios

Obtiene los
datos a partir de
la respuesta del
entrono a las
acciones que
realiza el agente

10

Aprendizaje supervisado

• El algoritmo aprende de datos etiquetados a hacer predicciones

– para datos no vistos anteriormente

manzana

manzana

plátano

manzana

plátano

plátano

manzana

plátano

manzana

etiqueta ?

¿Que pasará con el limón ?

11

Aprendizaje no supervisado

• Se descubren patrones o regularidades en los datos

– De acuerdo con unos principios heurísticos

• Similitud o disimilitud
• Secuencias
• Asociaciones
• Reducción de dimensiones

– De acuerdo con una cierta definición de distancia

12

Detección de anomalias

• Un caso particular de especial importancia del aprendizaje no

supervisado
– Detección de Anomalias

• Anomalía

– Evento con valores que se salen de los esperados o considerados

“normales”

– Eventos relativamente raros

• de lo contrario son “otro estado”

13

Aprendizaje por refuerzo

• Un agente aprende a  tomar decisiones

– Ejecutando acciones en el medio
– Recibiendo premios o castigos

• Las decisiones pueden constituir una serie en el  tiempo

– Los premios tienen un factor de descuento

• Balance exploración / explotación resultados
• Los premios más lejanos valen menos

política

entorno

premio

estado

agente

14

Aprendizaje Supervisado

-

-

Problemas de regresión
Problemas de clasificación

15

Aprendizaje supervisado: conceptos clave

Datos históricos
etiquetados

Entrenamiento

APRENDIZAJE
SUPERVISADO

Predicción en
datos nuevos

Evaluación

16

Aprendizaje supervisado: conjuntos de datos etiquetados

• Conjunto de datos de ejemplo

– se utilizan como datos de entrada
– Indican la relación entre entrada y salida deseada

• Etiquetado

– ¿Sabrías darme un ejemplo?:__________________

• Datos etiquetados

– Obtener datos etiquetados de calidad es un elemento fundamental
– A menudo una de las partes más costosas  y difíciles

• Tiempo requerido
• Consenso en lo que son las etiquetas reales

Aprendizaje no supervisado: a menudo se recurre a el para en una etapa inicial
agrupar los datos. El éxito de los grandes modelos de lenguaje (ej. chatGPT) fue
entrenarse inicialmente de forma no supervisada en todos los textos de internet.

17

Aprendizaje supervisado: entrenamiento

• ¿Qué significa realmente aprender o entrenarse?

– Es un problema de optimización

• Dados

– Una clase de funciones ℱ

• con diversas funciones 𝑓 de ℱ
• que pueden depender de diferentes parámetros 𝑓(𝑥; 𝑎)

– Un conjunto de datos etiquetados 𝑥  → 𝑦
– Un coste o función de pérdida

• Generalmente la diferencia entre la predicción  ො𝑦  y la etiqueta real 𝑦

• Hallar:

– Escoger la función 𝑓 (es un hiper parámetro)
– Para esa función 𝑓 hallar los parámetros 𝑎 para los que en el conjunto de

datos etiquetados se minimiza la pérdida

– Con la esperanza de que 𝑓 funcione igual de bien para datos no vistos

anteriormente

Aprendizaje estadístico

18

Aprendizaje supervisado: Creación del modelo

► Entrenamiento y Predicción (inferencia)

19

Aprendizaje supervisado: predicción  en datos nuevos

• Dos tipos de predicciones:

– Regresión:

• predecir un valor continuo

– Clasificación:

• Predecir una etiqueta, clase o categoría

Un problema de regresión puede ser convertido en uno de
clasificación

20

Aprendizaje supervisado: ejemplos

• Regresión

• Clasificación

21

Datos de entrenamiento y test

Sobreajuste
-
Evaluación cruzada

-

22

Aprendizaje supervisado: ejemplos

• Regresión

– Precio vivienda

• #habitaciones, 𝑚2, barrio

– Predicción temperatura
– Predicción ventas
– Consumo de energía

• Clasificación

– Detección de spam

• spam / no spam

– Diagnóstico médico
– Clasificación de texto

• Comentario, artículo, …

– Reconocimiento facial

23

Aprendizaje supervisado: clasificación

• Clasificación:

– Aprende a partir de ejemplos conocidos asignar una etiqueta o clase

𝑥1
𝑥𝑛

  ⟶   ቐ

𝐶1
𝐶2
𝐶𝑛

• Puede haber de varios tipos

Binaria

Dos clases

Clasificación

Multiclase

Varias
clases

Multi-
etiqueta

24

Aprendizaje supervisado: evaluación

• Dados unos datos en la forma

– características / etiquetas o valor  𝑥, 𝑦

• Encontrar la función que genere valores/etiquetas predichos

– ො𝑦 = 𝑓(𝑥)

• De tal forma que se minimice el error

𝑥

𝑓(𝑥)

ො𝑦

– ( ෝ𝑦𝑖 − 𝑦𝑖)

25

Aprendizaje supervisado: evaluación

• Regresión

– Distintas métricas

• MAE (valor medio del error absoluto)
• MAPE (valor medio del error porcentual)
• MSE (valor medio del cuadrado del error)

26

Aprendizaje supervisado: evaluación

• Clasificación

– Clases balanceadas

• Exactitud

𝑒𝑥𝑎𝑐𝑡𝑖𝑡𝑢𝑑 =

𝑉𝑃 + 𝑉𝑁
𝑉𝑃 + 𝐹𝑃 + 𝐹𝑁 + 𝑉𝑁

– Clases no balanceadas

• Por clase: precisión y detección

𝑝𝑟𝑒𝑐𝑖𝑠𝑖ó𝑛 =

𝑑𝑒𝑡𝑒𝑐𝑐𝑖ó𝑛 =

𝑉𝑃
𝑉𝑃 + 𝐹𝑃

𝑉𝑃
𝑉𝑃 + 𝐹𝑁

27

Etapas en un proyecto de
aprendizaje automático

28

Etapas en la aplicación de machine learning

• Definición del problema

• Recogida de datos

• Tratamiento de datos

• Exploración de características

• Elección del modelo

• Entrenamiento del modelo

• Evaluación del modelo

• Ajuste de hiperparámetros y optimización

• Desplegar el modelo

1

2

3

4

5

6

7

8

9

29

Símil con el proceso de cocinar

Esta foto de Autor desconocido
está bajo licencia CC BY-NC-ND

• Definición del problema→¿Qué necesitan mis comensales, cuando: almuerzo, ¿cena ?

• Recogida de datos → ¿Qué ingredientes necesito?  ¿De dónde los consigo ? ¿cantidad?

• Tratamiento de datos → Preparar los ingredientes: limpiar, pelar, cortar

• Exploración de características→ combinaciones necesarias: sofrito, picado, molido, zumo

• Elección del modelo → Elegir el molde/recipiente que me interesa

• Entrenamiento del modelo → Cocinar

• Evaluación del modelo → ¿cómo sale del horno? ¿satisfacción de los comensales?

• Ajuste de hiperparámetros y optimización → Ajuste temperatura, poca sal,  mucha

• Desplegar el modelo → Lo probé en la cocina, ahora ¡ a la sala del restaurante !

1

2

3

4

5

6

7

8

9

30

Procesos Estandar iterativo

• Un standard es el CRISP-DM

– Cross-industry standard process for data mining
• Liderado por un consorcio de empresas líderes

– Es un de facto standard que puede usarse como referencia
– Contempla básicamente las mismas 6 fases

• Comprensión de la cuestión desde un punto de vista de negocio
• Comprensión de los datos
• Preparación de los datos
• Modelado
• Evaluación
• Despliegue

– Destaca la naturaleza iterativa del proceso

31

Datos de entrenamiento y datos de test:
overfitting y validación cruzada

32

Datos

• Los datos son el componente clave de cualquier proyecto de

aprendizaje automático
– Estructurados:

• Tablas de bases de datos

– No estructurados:

• Textos, imágenes, audio, vídeos

– Semi estructurados:

• Páginas web, formularios con etiquetas

33

Datos

• La preparación y la comprensión de los datos

– es una de las tareas más importantes

• garbage in → garbage out

– Es la actividad que más tiempo consume del ciclo de vida del proyecto de

aprendizaje automático

– En general, se estima que desarrolladores de inteligencia artificial (IA)

pasan casi el 70 % de su tiempo analizando conjuntos de datos.

34

Datos: principales problemas

DATOS
INSUFICIENTES

Falta de disponibilidad
de grandes muestras
con suficiente
diversidad de valores

SESGO Y ERROR
HUMANO

Cualquier herramienta
para la recopilación de
datos conlleva
inevitablemente sesgos
conscientes o
inconscientes

CALIDAD

En el mundo real los
datos están
desorganizados,
complejos, no
consistentes y con
errores

PRIVACIDAD Y
CUMPLIMIENTO

La mayoría de las
fuentes no comporten
datos
Necesidad de
anonimizar
Restricciones de
movimiento entre
jurisdicciones (EU,
US)

ANOTACIÓN

Generalmente las
anotaciones humanas
requieren etiquetado
manual
Complejo, costoso y
proclive a errores
operativos y de
definición

35

Datasets
• Conjunto de datos

– Datos de entrenamiento
– Datos de validación
– Datos de test

• Uno de los retos del aprendizaje automático

– Generalización de la información extraída de los datos de entrenamiento

• A cualquier situación nueva

– Separación estricta

• Evitar filtración de información al algoritmo que sesgue de resultados

demasiados optimistas

Datos
Entrenamiento

Resto Mundo

36

Datasets

ENTRENAMIENTO

VALIDACIÓN

TEST

Datos
históricos
observados

37

Datasets

ENTRENAMIENTO

Para aprender la
función f(𝒙)

VALIDACIÓN

TEST

Optimizar hiper
parámetros f 𝒙
(opcional)

Comprobar
generalización
Estimación
rendimiento

38

Validación cruzada
• Aumentar el tamaño del conjunto de test-validación

– Sin  disminuir los datos de entrenamiento

• Se dividen los datos en K-partes
– Se entrena en 𝒌 − 𝟏 se testea en 𝒌
– Se toma el mejor modelo de los 𝒌
– Se considera el rendimiento la media con su dispersión

39

Overfitting (Sobreajuste)
• Cuanto más complejo sea el modelo, mejor podrá predecir

sobre los datos de entrenamiento.

• Cuando el aprendizaje se ajusta demasiado a las

particularidades del conjunto de datos de entrenamiento y
obtiene un modelo que funciona bien en el conjunto de
entrenamiento, pero que no es capaz de generalizarse en
nuevos datos.

40

Sobreajuste (overfitting)

• Cuanta mayor capacidad tiene el modelo

– Puede ajustar datos más complejos
– Riesgo de memorizer

• “aprender” el ruido, las particularidades coyunturales, no las características

• Fenómeno

– Excelente rendimiento en el conjunto de entrenamiento
– Peor rendimiento en el conjunto de test

• Solución: regularización, penalizar que aprenda demasiado

41

Gracias por vuestra atención

42

Referencia cita imágenes

•

•

•

•

•

•

Diapositiva 4:

–

–

By Juan Alberto Sánchez Margallo - File:Test_de_Turing.jpg, CC BY 2.5,
https://commons.wikimedia.org/w/index.php?curid=57298943

Captura de pantalla: https://raysolomonoff.com/dartmouth/boxa/dart564props.pdf

Diapositiva 5:

–

–

By Adrian Rosebrock - http://www.pyimagesearch.com/2016/11/07/intersection-over-union-iou-for-object-detection/, CC BY-
SA 4.0, https://commons.wikimedia.org/w/index.php?curid=57718561

By Moshanin - Own work, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=24097346

Diapositiva 6:

–

https://artificialintelligenceact.eu/

Diapositiva 7:

–

Cluster free icon, Muhammad_Usman Flaticon

Diapositiva 24:

–

Adaptado de https://en.wikipedia.org/wiki/Precision_and_recall#/media/File:Precisionrecall.svg

Diapositiva 31:

–

https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining#/media/File:CRISP-DM_Process_Diagram.png

43

Tema 2. Análisis de datos. Descriptivo y exploratorio
Antoni Munar Ara

Presentación de la
asignatura

Índice

2.1 Introducción y objetivos
2.2 Tipos de variables
2.3 Caracterización de las distribuciones de variables
2.4 Medidas de dispersión
2.5 Detección de valores atípicos
2.6 Diagramas de dispersión
2.7 Correlación entre variables
2.8 Matriz de covarianza

2

2.1 Introducción y objetivos

3

2.1 Introducción y objetivos

• Principios básicos del análisis descriptivo de los datos:

– Recolección y Organización
– Presentación y Descripción

• Histogramas
• Medidas de dispersión
• Interpretación estadística: diagramas de caja

• Exploratory Data Analysis (análisis exploratorio)

– Relaciones entre variables

• Coeficiente de Pearson para pares de atributos
• Matriz de covarianza para un conjunto de atributos

4

2.2 Tipos de variables

5

Definición de variable

• Característica o atributo de un objeto (Dicovsky Riobóo, 2012)

– Puede ser observable y susceptible de variación

• Se puede medir

– Puede asumir diferentes valores

• Los diferentes valores que puede tomar una  característica

– Rustom J. (2012)

6

Tipos de variables

• Las variables pueden ser de distintos tipos

Variables

cualitativas

cuantitativas

Nominales

Ordinales

Discretas

Continuas

7

Tipos de variables

• Cualitativas

– expresan características de forma no numérica.
– Ejemplos: color, género, grupo sanguíneo, estado civil, etc.

NOMINAL

ORDINAL

• Los valores son códigos o

• Los valores definen un orden

denominaciones que no se
pueden ordenar.

• de mayor a menor
• de mejor a peor

• Ejemplos: nacionalidad, religión,

• Ejemplos:

color de piel, etc.

•

intensidad del dolor

• ausente, leve, moderado,

severo, muy severo

• Calificación

• excelente, bueno, regular,

malo

8

Tipos de variables

• Cuantitativas

– Se expresa mediante un número

DISCRETA

CONTINUA

• Admite únicamente tomar una

cantidad de valores numéricos
• usualmente son valores enteros

• Ejemplo: número de hijos por

hogar, número de computadores
en un aula.

• Entre cualesquiera dos valores
distintos, puede haber infinitos
valores posibles.

• Representan mediciones.

• Ejemplo: peso (KG), estatura, el
tiempo que demora un atleta en
recorrer 100 metros.

9

Tipos de variables

• Tipos de variables en Python

10

Práctica Notebook - 1

• Google colab notebook

– Puede funcionar igualmente en local

• Ficheros en el campus

– notebook: nb_tema02_v0.ipynb
– Datos:

• Anuncios clasificados de alquiler de apartamentos
• apartments_for_rent_classified_10K.csv (6 MB)

• Sección 1:

– Carga de datos
– Examinar el dataset
– Ver tipos de variables
– Examinar variables

11

2.3 Caracterización de las
distribuciones de variables

12

Histogramas (1/ 2)

• Generalmente usado para variables

cuantitativas continuas

• Representación gráfica de la

frecuencia de los valores agrupados
de los valores que toma cada
variable

• La agrupación se basa en los
distintos intervalos contiguos

13

Histogramas (2 / 2)

• Dados

– La lista de valores  𝑥1, 𝑥2, … , 𝑥𝑛
– Un rango ℎ𝑚𝑖𝑛 y ℎ𝑚𝑎𝑥  de los valores 𝑥
• Puede o no coincidir con 𝑥𝑚𝑖𝑛 o 𝑥𝑚𝑎𝑥

– Un número de intervalos 𝑛𝑏𝑖𝑛

• Se crea  una lista con 𝑛𝑏𝑖𝑛 intervalos

– Entre ℎ𝑚𝑖𝑛 y ℎ𝑚𝑎𝑥

• Se calcula el número de elementos de  𝑥1, 𝑥2, … , 𝑥𝑛
– Que caen dentro de cada uno de los 𝑛𝑏𝑖𝑛 intervalos

• Se representa gráficamente

La base
corresponde a
cada intervalo

La altura de cada
barra indica el
número de
elementos o su
frecuencia

14

Histogramas y distribución de las variables

• Al trabajar con histogramas

– Controlar los rangos:  𝑥𝑚𝑖𝑛, 𝑥𝑚𝑎𝑥
– El número de intervalos 𝑏𝑖𝑛
– La escala: linear o logarítmica

• Caracterización de la distribución
– Uniforme: barras de la misma altura
– De campana o gaussiana: cuerpo central

con forma de “campana”

– Simetría o con desviación a un cierto

valor

– Con largas “colas”: distribuciones con

valores extremos

– Con valores atípicos (anomalías o  no)

15

Práctica Notebook - 2

• Trabajar con histogramas
• Caracterización de la distribución

16

2.4. Medidas de dispersión

17

Dispersión de las variables

• Caracteriza la variabilidad de los valores

– Generalmente variabilidad está relacionada con la información

• En la mayoría de los fenómenos

– Un núcleo de valores con una cierta dispersión respecto a una media
– Una larga cola de valores muy grandes, pero con baja frecuencia
– Ciertos valores extremos

• Errores, anomalías, o casos de por si extremos (“celebridades”)

18

Medidas de dispersion (1/ )

• Rango

– Diferencia entre límite inferior y superior
– Limitada utilidad, se distorsiona con los valores extremos

19

Medidas de dispersion (2/ )

df[['bathrooms', 'bedrooms','price','square_feet']].describe()

20

Medidas de dispersion (3/ )

df[['bathrooms', 'bedrooms','price','square_feet']].describe()

𝑟𝑎𝑛𝑔𝑜 𝑏𝑒𝑑𝑟𝑜𝑜𝑚𝑠 = 0.0, 9.0 = 9.0

𝑟𝑎𝑛𝑔𝑜 𝑝𝑟𝑖𝑐𝑒 = 200, 52500 = 52300

21

Medidas dispersion (4/ )

• Eliminar la influencia de los extremos
• Rango intercuartílico (RIC)

– Diferencia entre el tercer quartil y el primer cuartil

• Tercer quartil Q3: el valor tal que el 75% de los valores son inferiores
• Primer quartil Q1: el valor tal que el 25% de los valores son inferiores

𝑟𝑎𝑛𝑔𝑜 𝑏𝑒𝑑𝑟𝑜𝑜𝑚𝑠 = 1.0, 2.0 = 1.0

𝑟𝑎𝑛𝑔𝑜 𝑝𝑟𝑖𝑐𝑒 = 949, 1695 = 746

22

Medidas de dispersion (5/ )

• Varianza

– La media de la suma de los cuadrados de la desviación de cada dato

con respect a la media aritmética

• Desviación típica

– Raiz cuadrada de la varianza
– Mismas unidades que la media → util para comparaciones

Varianza poblacional: la que tiene
hipotéticamente 𝑁

Varianza muestral: la calculada
sobre los datos que tenemos 𝑛 − 1

23

2.5 Detección de valores
atípicos

24

Detección de valores atípicos

• Valor atípico

– Observación numéricamente “distante” del resto de datos
– No “encaja” en lo que sería “probable”
• Distorsionan los análisis estadísticos

– Si yo gano 5.000 y tú 5.000.000

• No significa que de media ganemos 2.502.500

• Un valor atípico

– Error de medición

25

Diagramas de caja (boxplot)

• Diagramas de caja

– Representación gráfica de los datos

• Cuartiles: Q1, Q2, Q3
• Limites “esperables”: bigotes o wiskers

– Extiende en 1.5 veces el rango intercuartílico RIC

Li

Q1

Q2

Q3

Ls

𝐿𝑖 = 𝑄1  − 1.5 · (𝑄3 − 𝑄1)

𝐿𝑠 = 𝑄3 + 1.5 · (𝑄3 − 𝑄1)

26

Práctica Notebook - 3

• Diagramas de caja

27

2.6. Diagramas de dispersión

28

2.6. Diagramas de dispersión

• Diagramas de dispersión = Diagramas de puntos  = Scatter

plots

• Las representaciones gráficas más útiles para describir el

comportamiento de un conjunto de variables.

• Estas gráficas muestran la relación existente entre las

variables numéricas.

29

Diagramas de dispersión

• Diagramas de dispersion

– Diagramas de puntos, scatter plots

• Representan los valores de dos variables

– Una respecto a la otra
– Muestran como están relacionadas  y relativamente distribuidas

• Truco técnico

– En la representación gráfica usar “transparencia”

• Da una idea de la densidad

30

Práctica Notebook - 4

• Diagramas de dispersión

31

2.7. Correlación entre
variables

32

Correlación entre variables

• Correlación

– Medida estadística
– Cuantifica el grado de variación conjunta
– La medida más común evalúa la tendencia creciente o decreciente de

los datos

a) Correlación positiva
b) Correlación negativa
c) Nula o sin correlación
d) Lineal
e) Exponencial
f) No lineal

33

Coeficiente de correlación

• Coeficiente de correlación de Pearson

– Permite cuantificar el grado de correlación lineal entre variables
– Toma valores entre  −1, 1

• Valores cercanos a 1:

– Correlación positiva donde ambas variables crecen simultaneamente

• Valores cercanos a -1:

– Correlación negative donde una variable crece y la otra decrece

• Valores cercanos a 0:

– No existe correlación

34

2.8. Matriz de covarianza

35

Covarianza

• Concepto cercano a la regression
• No está normalizada por la desviación típica

• Covarianza positiva

– Correlación directa entre datos

• Covarianza negativa
– Correlación inversa

• Covarianza nula

– No existe correlación como tal

36

Matriz de covarianza

• Representación de las covarianzas de varias variables
• Matriz cuadrada

– Diagonal principal: las varianzas
– Elementos: las covarianzas

• Simétrica

37

Práctica Notebook - 5

• Covarianza y correlación

38

Limitaciones correlación

39

Referencias Imágenes

• Slide 39:

– https://en.wikipedia.org/wiki/Anscombe%27s_quartet
– https://www.research.autodesk.com/publications/same-stats-

different-graphs/

40

Tema 3. Datos Ausentes y Normalización
Antoni Munar Ara

Presentación de la
asignatura

Índice

3.1 Introducción y objetivos
3.2 Encontrando atributos redundantes
3.3 Detectando registros duplicados
3.4 Mecanismos para reemplazar datos ausentes
3.5 Otros métodos de imputación de valores ausentes
3.6 Normalización mínima-máxima
3.7 Normalización z-score
3.8 De nominal a binario

2

3.1 Introducción y objetivos

3

Objetivos

•

Identificar los conceptos básicos de valores ausentes

• Métodos de imputación de datos ausentes

• Técnica y métodos más utilizados en detección de datos

redundantes

• Normalización de datos numéricos

4

Selección de atributos

• Una de las principales etapas para la creación de modelos

• Variables con información no relevante que introducen ruido

– Innecesaria variedad y variación

• La maldición de las altas dimensiones

•

Información redundante

• Mejora

– Calidad del modelo
– Uso eficiente de recursos computacionales

• Almacenamiento y memoria

5

Transformación de datos

• Dependiendo del algoritmo

– Necesario para tener todos los datos en la misma escala numérica
– Eliminación de datos atípicos (ruido)
– Transformación de nominal a valores binarios

Ajuste por escalas

Normalización z-score

Nominal a binario

• Ajuste escala
• Transformación

monótona
• Eliminación colas

• Eliminación atípicos
• Media 0, desviación 1

• Etiquetas a números
• Reducción valores:
• Seleccionados 1,

resto 0

6

3.2 Encontrando atributos
redundantes

7

Identificación datos redundantes

• Minería de datos

– integración y preprocesamiento de los datos

• Selección de los datos que mejor representan los datos
• Eliminar datos redundantes

– El conjunto de datos que no se deriven de cualquier otro atributo

• Técnicas utilizadas

– Correlación y Covarianza
– Prueba de datos nominales 𝜒2

Esta foto de Autor desconocido está bajo licencia CC BY-SA

8

Correlación – variables continuas

• Coeficiente de Pearson

– Asociación lineal entre dos variables cuantitativas y continuas

• Utilizado para determinar redundancia atributos

• Dados dos atributos 𝑥1 y 𝑥2

– Cuanto mayor el coeficiente de correlación más fuerte correlación
– Es posible prescindir de uno de ellos

• Si conozco el valor de uno, conozco el del otro

9

Coocurrencia – variables categóricas
• El test 𝜒2

– Hipótesis independencia coocurrencia dos variables

• Definir hipótesis: las dos variables son independientes

• Nivel de significación (alfa): 0.05

• Creación de tablas de contingencia

• Cálculo de frecuencia esperada

• Cálculo de chi cuadrado

• Cálculo de los grados de libertad

• Valor de p

• Decidir si rechazar o mantener la hipótesis nula

1

2

3

4

5

6

7

8

10

Ejemplo Notebook - 3

• 3.1 Test chi-cuadrado

11

3.3 Detectando registros
duplicados

12

Detectando registros duplicados

• Datos duplicados:

– Valores que coinciden en todas las variables seleccionadas
– Si coinciden parcialmente, pero representan una misma entidad

• record linkage
• Se usan algoritmos que agrupan los registros duplicados

– Fusionándolos o eliminándolos

• Afectan a la calidad de los resultados

– Sobre representan casos  introduciendo sesgos

• ruido

– Computacionalmente ineficientes

13

Ejemplo python

df.duplicated()

df = df.drop_duplicates()

14

3.4. Mecanismos para
reemplazar datos ausentes

15

Datos ausentes

• Atributos que no figuran o con valor erróneo en los datos

– No se introdujeron
– Se perdieron en el proceso de registro
– Corruptos o fuera de escala (sensores)

• Dificultan la realización del análisis de datos

– Introducción de sesgos (si los datos ausentes siguen un patrón)
– Pueden limitar la generalización de los resultados

16

Tratamiento datos ausentes
• Detectar la presencia de datos ausentes

– No  tan trivial como pueda parecer

• Definir ausencia

– ‘nan’,
– valores iguales a 0 o valores centinela
– cadena de caracteres vacia “”
– infinitos

• Normalizar los datos

– Examinarlos
– Definir un único valor (valor centinela)
– Conocer el número total de valores ausentes
– Ser cuidadoso con los valores ‘nan’

df.describe()

df.isnull().sum()

• Generalmente (SQL, Python) se asimilan a negativo para mantener lógica

binaria (0 o 1)

• En realidad (SQL) son lógica ternaria: 0, 1, nan

df.replace(0, nan)

17

Reemplazamiento datos ausentes

18

Eliminación
• Eliminar por completo

– Los atributos (columnas)
– Las instancias (filas)

• Viable

– Cuando los datos faltantes es un número relativamente pequeño
– Se concluye que su distribución no conduce a sesgos graves

• Única alternativa

– Si la mayoría de los datos están ausentes

19

Imputación

• Uso de alguna técnica de interpolación

– Para estimar valores ausentes
– A partir de otras instancias del conjunto de datos

• Media, Mediana, Moda

20

3.5 Otros métodos de
imputación de valores
ausentes

21

Técnicas de imputación

• Depende de los datos y la distribución de los datos faltantes
• Simples

– Sustitución por un valor constante:

• media, mediana, moda

– Estratificado si hay variaciones dependiendo grupos

• Modelado

– Tratarlo como un problema de aprendizaje supervisado
– Predecir el valor faltante

• KNN, regresión, máquinas de vectores de soporte

• Avanzadas

– Algoritmo esperanza maximización
– Método de imputación múltiple

22

Ejemplo Notebook - 3

• 3.2 Imputación datos ausentes

23

3.6 Normalización mínimo-
máximo

24

Necesidad normalización

• Normalmente los atributos en los datos
– Varían altamente en magnitud, unidad y rango

• Esto es relevante en algoritmos que usan distancias
– Dimensiones más grandes numéricamente dominaran

• Transformar  los atributos originales

– Generar nuevos atributos con mejores propiedades

• En la misma escala

• Estos nuevos atributos

– Variables de modelado o variables analíticas

25

Normalización min-max

• Escalar todos los valores con atributo numérico 𝑥𝑖

– Rango específico  𝑥𝑚𝑖𝑛, 𝑥𝑚𝑎𝑥

• Caso particular la normalización

– Es un ajuste min-max donde el intervalo final es

• 0, 1  o  −1, 1

– Acelera el proceso de aprendizaje en las redes neuronales

• Los pesos convergen más rápido

• Python scikit-learn
– MinMaxScaler

26

Ejemplo Notebook - 3

• 3.3 Normalización min-max

27

3.7. Normalización z-score

28

Z-score

• Una de las normalizaciones mas empleadas
• Estandarización de un conjunto de datos

– Los transforma como si fuera una distribución normal unitaria 𝑁(0,1)

• Media igual a 0 y desviación estándar igual a 1

29

Fórmula Z-score

• Nueva variable 𝑍 a partir de la original 𝑋

• 𝑍 =

𝑋−𝜇
𝜎

– 𝑍: valor estandarizado
– 𝑋: valor original
– 𝜇: media de la muestra
– 𝜎: desviación estándar de la muestra

• En scikit-learn

– StandardScaler

30

Ejemplo Notebook - 3

• 3.4 Normalización z-score

31

3.8 De nominal a binario

32

Transformación variables categóricas

• Algunos algoritmos de aprendizaje automático

– No pueden procesar atributos nominales

• E.g. redes neuronales, máquinas de vector soporte

• Transformación directa

– Valor nominal → variable numérica

• Problemática

– Los números son ordenables
– Implícitamente se establece un orden que no tiene porque existir

33

Transformación one-hot encoder

• Mapear cada atributo nominal

– Vector

• 1 en la posición correspondiente a un valor del atributo
• 0 en el resto

• Si el atributo nominal toma 𝑵 valores diferentes

– Se reemplaza por 𝑁 atributos binarios

Id

color

1

2

3

4

red

blue

green

blue

• Python

Id

1

2

3

4

color_red

color_blue

color_green

1

0

0

0

0

1

0

1

0

0

1

0

– Scikit-learn: OneHotEncoder
– Pandas: get_dummies

34

3.8. De nominal a binario

• Los algoritmos de aprendizaje automático, como las máquinas
de vector de soporte y las redes neuronales artificiales, no
pueden lidiar correctamente con los atributos nominales (no
numéricos).
– La presencia de estas características en un conjunto de datos puede

resultar problemática.

• Transformación variable nominal → variable numérica
– Cada valor nominal se codifica como un número entero.

 Esta opción no es recomendable debido a que se asume un
orden de jerarquía que no existe en los valores del atributo.
 Establecimiento de relaciones desiguales entre pares de valores

nominales → no es correcto.

35

Referencias Imágenes

• Slide :

36

37

Ejemplo Notebook - 2

• Trabajar con histogramas
• Caracterización de la distribución

38

Tema 4. Regresión y evaluación de algoritmos de regresión

Antoni Munar Ara

Presentación de la
asignatura

Índice

4.1 Introducción y objetivos
4.2 Algoritmos de regresión
4.3 Medidas cuantitativas del desempeño
4.4 Equilibrio entre varianza y sesgo
4.5 Visualización de errores

2

4.1 Introducción y objetivos

3

Objetivos

•

Introducción a los algoritmos de regresión

• Utilizar y comprender las métricas de error más comunes

•

•

Identificar el sesgo y la varianza en los datos

Identificar y  gestionar el overfitting y el underfitting en los
modelos de regresión

• Validar la generalización con visualizaciones de la

efectividad de los modelos

4

4.2 Algoritmos de regresión

5

Aprendizaje supervisado

• Supervisado

– Se utilizan variables conocidas para

predecir un valor o etiqueta

• (𝑥1, … , 𝑥𝑛)𝑖⟶ 𝑦𝑖

• Problemas de regresión

– Predecir un valor continuo para una

variable

• Problemas de clasificación

Aprendizaje
Automático

Supervisado

No supervisado

Regresión

– Predecir una clase para un elemento

Clasificación

6

Terminología

• Variable respuesta o outcome

– Variable dependiente, variable objetivo, target, class
– Se suele denotar por 𝑦

• Vector 𝒑 mediciones predictoras, entradas o inputs

– También conocido como regressors, features, características, variables

independientes
– Se suele denotar  Ԧ𝑥

• Datos de entrenamiento o training data

– Observaciones, ejemplos o instancias de cada una  de las medidas de

entrada

– Compuesto por una tupla de inputs y outputs
– 𝑥1, 𝑦1 , … , (𝑥𝑁, 𝑦𝑁)

7

Ejemplo Notebook - 4

• 4.1 Ejemplo predicción precio coste autos

8

Objetivo

• Considera una única variable independiente

– Pretende explicar una variable dependiente o variable respuesta

9

Usos

• Permite contestar a las siguientes preguntas

– ¿Existe una relación entre 2 variables ?
– ¿Es lineal la relación?
– ¿Cómo de fuerte es la relación ?
– ¿Qué variable contribuye más ?
– ¿Con qué precisión podemos estimar el efecto de cada variable?
– ¿Con qué precisión podemos predecir el objetivo?

10

Ejemplos

• Predecir ingresos anuales de una persona en base

– Nivel educativo, ingresos, lugar de residencia

• Predecir rendimiento de una plantación

– Rendimiento años anteriores, trabajadores, etc ..

• Predecir coste seguro médico
– Edad, peso, género, hijos
• Evolución precio vivienda

11

Formulación

• Asumiendo una variable objetivo y una variable de entrada

– 𝑦 =   𝛽0 + 𝛽1 · 𝑥 + 𝜖

• 𝛽1 es la pendiente (da idea de lo fuerte que es la relación)
• 𝛽0 es la intersección con el eje de las y (es el sesgo o desplazamiento)
• 𝜖 es el error, lo que no es capturado por el modelo

– Idealmente es aleatorio

12

¿Cómo se calcula?

• Método de los mínimos cuadrados
• Hallar 𝛽0 y 𝛽1 tales que se minimice
2 done 𝑒𝑖 = (𝑦𝑖 − ෝ𝑦𝑖)

𝑛 𝑒𝑖
𝑥1, 𝑦1 . . (𝑥𝑛, 𝑦𝑛   y     ෝ𝑦𝑖 = 𝛽0 + 𝛽1 · 𝑥𝑖

– σ𝑖=1
–

𝛽1 =

σ 𝑥𝑖 − ҧ𝑥 𝑦𝑖 − ത𝑦
σ 𝑥𝑖 − ҧ𝑥 2

𝛽0 = ത𝑦 − 𝛽1 ҧ𝑥

13

Ejemplo Notebook - 4

• 4.2 Regresión sobre la predicción precio coste autos

14

4.3 Medidas cuantitativas del
desempeño

15

Enfoque

• Todas las métricas se obtienen
– A partir del cálculo de los residuos

• Diferencia entre el valor real y el estimado

• Se utilizan para decidir si el modelo está funcionando bien o no

– Los valores con errores pequeños indican una buena capacidad
– Valores grandes sugieren lo contrario

16

Error cuadrático medio

• MSE (Mean Square Error)

– se define como la media del cuadrado de la diferencia entre el valor

real y el predicho

𝑛
𝑀𝑆𝐸 = Τ1 𝑛 ·  ෍
𝑖=1

(𝑦𝑖 − ො𝑦𝑖)2

17

Raíz del Error cuadrático medio

• RMSE (Root Mean Square Error)

– se define como la raíz cuadrada de la media de la diferencia entre el

valor real y el predicho

𝑅𝑀𝑆𝐸 =

𝑛
Τ1 𝑛 ·  ෍
𝑖=1

(𝑦𝑖 − ො𝑦𝑖)2

18

Error absoluto medio

• MAE (Mean Absolute Error)

– se define como la diferencia en valor absoluto de la diferencia entre el

valor real y el predicho

𝑛
𝑀𝐴𝐸 = Τ1 𝑛 ·  ෍
𝑖=1

|𝑦𝑖 − ො𝑦𝑖 |

19

Error porcentual absoluto medio

• MAPE (Mean Absolute Percentage Error)
– Es el porcentaje equivalente del MAE

𝑛

𝑀𝐴𝐸 =

Τ

100 𝑛 ·  ෍
𝑖=1

𝑦𝑖 − ො𝑦𝑖
𝑦𝑖

20

Error porcentual medio

• MPE (Mean Porcentual Error)

– Igual al MAE pero sin valor absoluto

𝑛

𝑀𝑃𝐸 =

Τ

100 𝑛 ·  ෍
𝑖=1

𝑦𝑖 − ො𝑦𝑖
𝑦𝑖

21

Logaritmo de la raíz del error cuadrático medio

• RMLSE (Root Mean Logarithmic Square Error)

– se define como el logaritmo del error cuadrático medio
– Se usa

• cuando el objetivo varía en varios órdenes de magnitud
• Cuando las diferencias relativas son más importantes que las diferencias

absolutas

𝑅𝑀𝐿𝑆𝐸 =

𝑛
Τ1 𝑛 ·  ෍
𝑖=1

(log(𝑦𝑖+1) − log( ො𝑦𝑖 + 1))2

22

Coeficiente de determinación 𝑅2
• Este valor puede interpretarse

– Proporción de la variación de los datos

• Explicada por el modelo

• La formulación más simple

– Coeficiente de correlación entre

• Los valores observados
• Los valores predichos

• Ejemplo

– Un valor de 𝑅2de 0.75 implica que el modelo

• Puede explicar el 75% de la variación del resultado

23

Qué métrica utilizar

•

Importante tener en cuenta la naturaleza de los datos
– Los valores atípicos puede ser claves a la hora de tomar la decisión
• Dominios y variables con datos más propensos a datos atípicos

24

Ejemplo Notebook - 4

• 4.3 Medidas desempeño

25

4.4. Equilibrio entre varianza
y sesgo

26

Rendimiento vs eficacia

• Tareas de aprendizaje automático

Complejidad
del modelo

Exactitud de
predicciones
sobre datos no
utilizados para
entrenar al
modelo.

Precisión

27

Descomposición sesgo / varianza

El error de sesgo

• Debido a suposiciones erróneas en el algoritmo de aprendizaje.
• Un sesgo alto puede hacer que un algoritmo pierda las relaciones relevantes

entre las características y los resultados objetivo (DESAJUSTE).

La varianza

• Error por la sensibilidad a las pequeñas fluctuaciones en el conjunto de

entrenamiento.

• Una alta varianza puede resultar de un algoritmo que modela el ruido aleatorio

en los datos de entrenamiento (SOBREAJUSTE).

Descomposición sesgo-varianza

• Forma de analizar el error de generalización esperado de un algoritmo de

aprendizaje con respecto a un problema particular

• Suma de tres términos: el sesgo, la varianza y error irreducible.

28

4.5 Visualización de errores

29

Porque es importante

• La visualización de errores permite detectar estructura en el

error
– Correlación con la variable target u otras estructuras
– Idealmente si nuestro modelo ha logrado capturar todas las

dependencias funcionales

• El error es puramente aleatorio, gaussiano, con media 𝜇 = 0 y una cierta

dispersión que depende del ruido de la variable

30

Forma de visualización

• Diagrama de dispersión en dos dimensiones

– Variable predicha vs valor real

Predicción perfecta

sobreestimado

subestimado

31

Forma de visualización

• Histograma de los errores

– Permite ver estructuras o sesgos

32

Ejemplo Notebook - 5

• 4.4 Visualización de errores

33

Referencias Imágenes

•

Diapositiva 9:

–

Fuente: https://commons.wikimedia.org/wiki/File:Linear_regression.svg#/media/File:Linear_regression.svg

34

Tema 5. Evaluación de algoritmos de clasificación
Antoni Munar Ara

Presentación de la
asignatura

Índice

5.1 Introducción y objetivos
5.2 Algoritmos de clasificación
5.3 Predicciones de clase
5.4 Métricas de evaluación: matriz de confusión
5.5 Métricas de evaluación: curvas ROC y AUC

2

5.1 Introducción y objetivos

3

Objetivos

• Comprender los modelos de clasificación

– Diferentes tipos de clasificación

• Utilizar y comprender las métricas de evaluación del

rendimiento

•

Identificar los problemas de rendimiento
– Asociados al desbalanceo en los datos

• Validar el aprendizaje

– Visualización de las métricas de rendimiento

4

5.2 Algoritmos de
clasificación

5

Clasificación

• Supervisado

– Obtener la clase más probable para cada una

de las instancias

• (𝑥1, … , 𝑥𝑛)𝑖⟶ 𝐶𝑖

• Estimar probabilidad de pertenencia

– Binaria: una clase entre 2 posibles
– Multiclase: la probabilidad de una clase entre varias

Aprendizaje
Automático

posibles

Supervisado

No supervisado

Regresión

Clasificación

6

Ejemplos

• Clasificación de correo como spam

– Binario: spam no spam

• Diagnostico médico

– Multiclase

• Clasificación de documentos

– Binario o multiclase
Imágenes

•

7

5.3 Predicciones de clase

8

Dos tipos de predicciones

• Probabilidad de pertenencia

• Categoría discreta

Clasificación

Clasificación

Manzana

Plátano

Sandía

Fresa

Naranja

Suma

0,01

0,95

0,01

0,02

0,01

1

Manzana

0 / No

Plátano

Sandía

Fresa

Naranja

1 / Si

0 / No

0 / No

0 / No

9

Probabilidad de pertenencia

Clasificación

Manzana

Plátano

Sandía

Fresa

Naranja

Suma

0,01

0,95

0,01

0,02

0,01

1

• Útil para medir la confianza del modelo en la clasificación
• Ejemplo:

– Una fruta con una probabilidad de predicción de plátano de 0.55
– Se clasificaría de la misma forma que con una probabilidad de 0.99
– Aunque tenemos más confianza en que la segunda sea un plátano

10

Ejemplo Notebook - 5

• 5.1 Clasificación flores iris

– Características:

• Longitud del sépalo (cm)
• Anchura del sépalo (cm)
• Longitud del pétalo (cm)
• Anchura del pétalo (cm)

– Clases:

• Iris Setosa
• Iris Versicolor
• Iris Virginica

11

5.4 Métricas de Evaluación

12

Métricas de Evaluación

• Queremos saber

– El clasificador tiene éxito en su propósito

• Para evaluar un clasificador
– Valores de la clase predichos
– Valores de la clase reales

13

Clasificación binaria: matriz de confusión

• Clasificación binaria

– Casos positivos y negativos
• Generalmente la clase positive

– Es la clase de interés

• Matriz de confusión

Predicción
clase positiva

Predicción
clase negativa

Clase positiva
real

Clase negativa
real

TP

FP

FN

TN

14

Métricas de evaluación

clases reales

clase positiva

clase negativa

clase
positiva

TP
(positivos verdaderos)

FP
(falsos positivos)

clase
negativa

FN
(falsos negativos)

TN
(negativos verdaderos)

clases
predichas

precisión positivos
𝑇𝑃
𝑇𝑃 + 𝐹𝑃

precisión negativos
𝑇𝑁
𝑇𝑁 + 𝐹𝑁

sensibilidad
𝑇𝑃
𝑇𝑃 + 𝐹𝑁

especificidad
𝑇𝑁
𝑇𝑁 + 𝐹𝑃

exactitud
𝑇𝑃 + 𝑇𝑁
(𝑇𝑃 + 𝑇𝑁 + 𝐹𝑃 + 𝐹𝑁)

15

Métricas principales
• Exactitud (accuracy)

– El número total de predicciones correctas

• Tanto en la clase positiva como en la negativa

•

𝑇𝑃+𝑇𝑁
(𝑇𝑃+𝑇𝑁+𝐹𝑃+𝐹𝑁)

–  ¡No utilizar en caso de clases desbalanceadas!

• Precisión

– Ejemplos que son verdaderamente positivos
– Cuanto me puedo fiar: “si te digo que es un lobo, es realmente lobo o oveja”

•

𝑇𝑃
𝑇𝑃+𝐹𝑃
• Sensibilidad (recall)

– Ejemplos detectados del total
– “cuantos lobos he detectado de todos los que había”, “cuantos me he dejado

sin detectar”
𝑇𝑃
𝑇𝑃+𝐹𝑁

•

16

Otras métricas

• Utilizadas en otros campos
– Medicina, ensayos médicos
• Especificidad (specificity)

– Ratio de ejemplos negativos correctamente clasificados
– “Te puedo decir que no lo tienes”

•

𝑇𝑁
𝑇𝑁+𝐹𝑃
• Sensibilidad (recall)

– Ejemplos positivos detectados del total
– “cuantos lobos he detectado de todos los que había”, “cuantos me he

dejado sin detectar”

•

𝑇𝑃
𝑇𝑃+𝐹𝑁

17

Métricas sumario

• Expresar como un único numero

– Facilita comparaciones

• F-score

– Combina la precisión y la sensibilidad (recall)
– Es la media armónica

𝐹1 =

2 ∗ 𝑇𝑃
2 ∗ 𝑇𝑃 + 𝐹𝑃 + 𝐹𝑁

18

¿Qué métrica usar?
•
• Depende del

Todas las medidas aportan información importante

– comportamiento que queremos maximizar
– circunstancias

• Exactitud

– No es apta para datos desbalanceados
– Ejemplo

• Con 999 casos positivos y 1 negativo
• Clasificador trivial todos son positivos

• Precisión

999+0
999+0+1+0

= 99.9%

– Lo importante es ser fiable, aunque no detecte todo

• Contratar a un candidato que, seguro que es bueno, aunque rechace también a buenos

(Google que tiene muchos candidatos)

• Sensibilidad

– Lo  importante es detectarlo, aunque tenga falsas alarmas

• Diagnóstico médico, a veces se repiten los análisis

19

Ejemplo Notebook - 5

• 5.2 Métricas Clasificación flores iris

20

Datos desbalanceados: consideraciones

• En la realidad tener datos desbalanceados es lo más común

– La distribución de los datos no es uniforme
– Gran diferencia en el número de instancias de las distintas clases

• Los modelos de aprendizaje automático
– Tienden a sesgarse hacia la clase mayoritaria

• Las métricas globales

– No son representativas del rendimiento real del modelo
– Rendimiento deficiente para la clase minoritaria

• La métrica de exactitud

– No es apropiada

• Debemos utilizar métricas que tengan en cuenta el

desbalanceo entre clases
– La matriz de confusión entre otras

21

5.5 Métricas de evaluación:
curvas ROC y AUC

22

Curva ROC - definición

• ROC – Receiver Operating Characteristic

– Específico para clasificación binaria
– Representación gráfica de la sensibilidad frente a la especificidad
– Representa la ratio de verdaderos positivos frente a la ratio de falsos

positivos

• Dependiendo del umbral de discriminación
𝑇𝑃
𝑇𝑃+𝐹𝑁

• Ratio de verdaderos positivos 𝑇𝑃𝑅 =
𝐹𝑃
𝐹𝑃+𝑇𝑁

• Ratio de falsos positivos 𝐹𝑃𝑅 =

– Desarrollada en principio por los operadores de RADAR en la segunda

guerra mundial

23

Curva ROC – interpretación curva

• Determinar que umbral del modelo es major

– Compromiso entre verdaderos positivos y falsos positivos

• Modelo de correo basura:

– Quiero evitar perder correos importantes:

• Punto A, B, o C

24

Curva ROC – elección modelos

• Modelos con distintas curvas

– Indican distinto desempeño del modelo
– La diagonal

• Modelo aleatorio detección clase

• Cuanto más cercano a  1,1

– Más perfecto

• Criterio:

– AUC: área debajo de la curva

Desempeño perfecto

25

Ejemplo Notebook - 5

• 5.3 Ejemplo ROC

26

Referencias Imágenes

•

Diapositiva 25:

–

Fuente: By cmglee, MartinThoma - Roc-draft-xkcd-style.svg, CC BY-SA 4.0,
https://commons.wikimedia.org/w/index.php?curid=109730045

27

Tema 6. Aprendizaje supervisado. Regresión y clasificación
con árboles de decisión
Antoni Munar Ara

Presentación de la
asignatura

Índice

6.1 Introducción a los árboles de decisión
6.2 Best Split: entropía, índice de Gini, ganancia de información
6.3 Árboles para clasificación
6.4 Árboles vs modelos lineales

2

6.1 Introducción a los árboles
de decisión

3

Árboles de decisión (DT en inglés)

• Es un tipo de aprendizaje supervisado

• Una de las técnicas más populares en aprendizaje automático

– Permiten resolver problemas de regresión y clasificación

• Dividen o segmentan el espacio de las variables predictoras

– Serie de regiones

• Predicción

– Clasificación: la moda de las observaciones en cada región
– Regresión: la media de las observaciones en cada región

4

Estructura árbol de decisión (1/ 4)

• Predicción resultado elecciones US
– Condado Demócrata / Republicano

• Variables (*)

– Educación (categórica)
– Ingresos (numérica)
– Diversidad racial (categórica binaria)

(*) consideramos que son de este tipo para simplificar. En el ejemplo
veremos como las librerías transforman variables numéricas y
categóricas múltiples a categóricas binarias automáticamente

5

Estructura árbol de decisión (2 / 4)

• El modelo de aprende de los datos
• Construcción del árbol

– Construcción de la jerarquía del árbol invertido
– Selección de las variables  a diversos niveles
– Partición de los valores de los atributos y variables continuas
– Nodos decisión en cada nivel

Nivel educativo > mediana

Ingresos altos

Diverso racialmente

6

Estructura árbol de decisión (3 / 4)

• Flujo y nodos (bifurcaciones, decisiones)

– Nodo raíz
– Nodos internos
– Ramas
– Nodos terminales / hojas

• Nodo interno

– Prueba sobre un atributo

• Rama

– Resultado prueba
• Nodo terminal / hoja

– Etiqueta de clase / valor medio

• Nodo raíz

– Es el nodo superior del árbol

Nivel educativo > mediana

Ingresos altos

Diverso racialmente

7

Estructura árbol de decisión (4 /4 )

Nodo raíz

subárbol

Nodo
decisión

Nodo
decisión

Nodo
terminal

Nodo
decisión

Nodo
terminal

Nodo
terminal

Nodo
terminal

Nodo
terminal

8

Asunciones en árbol de decisión

Inicio: todo el conjunto de entrenamiento se considera raíz

•
• Los valores de los atributos deben ser categóricos

– Para valores continuos se discretizan antes de construir el modelo
– Por ejemplo, se toman los cuartiles, cada cuartil una categoría

Q1

Q2

Q3

Q4

• El orden para situar los atributos en la jerarquía del árbol

0%

25%

50%

75%

– Posición como raíz o en un nodo interno determinado
– Se realiza utilizando criterios estadísticos (siguiente sección)

100%

9

Asunciones entrenamiento árbol de decisión

• Al inicio

– Todo el conjunto de entrenamiento se considera raíz
• Los valores de los atributos deben ser categóricos

– Los valores continuos se discretizan durante el entrenamiento del modelo

• El orden para situar los atributos en la jerarquía del árbol

– Posición como raíz o en un nodo interno determinado

• Se realiza utilizando criterios estadísticos (siguiente sección)

10

Inferencia en los árboles de decisión

• Para todas las instancias se comienza con el nodo raíz
• Se van evaluando los distintos nodos

– Se avanza al nodo correspondiente según se cumpla la condición

• Este proceso continúa hasta que se alcanza un nodo hoja
•

La predicción se realiza en ese nodo hoja
– Clasificación: durante el entrenamiento se asigno una etiqueta

• Basada en la mayoría de las instancias en esa hoja durante el entrenamiento

– Regresión: durante el entrenamiento se asignó un valor

• Basado en la media del valor de las instancias que acabaron en esa hoja durante el

entrenamiento

11

Ejemplo Notebook – 6.1

• 6.1 Predicción resultado mayoría demócrata o republicano

elecciones US 2020 por condado

– Características:

• Nivel educación población
• Nivel ingresos
• Composición racial
• Ocupación población

– Clases:

• Porcentaje voto demócrata
• Porcentaje voto republicano

12

6.2 Best Split: entropía,
índice de Gini, ganancia de
información

13

Selección de atributos

• La tarea principal de los árboles de decisión

– Identificar los atributos
• Para el nodo raíz
• Para los nodos en cada nivel

• Dos criterios de selección de atributos

– Ganancia de información
– Índice de Gini

14

Ganancia de información - ejemplo

Nivel educativo > mediana

Ingresos altos (si/no)

Diverso racialmente
(si/no)

• El atributo que consigue separaciones más puras

– Es el que proporciona más información
– Reduce la entropía

15

Ganancia de información

• Trata de estimar la cantidad de información
– Que se contiene en cada partición de un atributo
• Sigue un método voraz  para decidir que decisión
– Da la mayor ganancia de información en cada paso
– Permita separar mejor las instancias respecto a la clasificación final
– Reduce la entropía

• Entropía

– Mide el grado de incertidumbre de la muestra

• Grado de impureza

– La ganancia de información es la reducción de entropía
– Shannon, C. E. (1948). A mathematical theory of communication. The

Bell system technical journal, 27(3), 379-423.

16

Entropía

• La entropía de una partición determinada

– 𝐸𝑛𝑡𝑟𝑜𝑝𝑦(𝑆) = σ𝑖=1

𝑐

  − 𝑝𝑖log2(𝑝𝑖)

• Donde:

– 𝑆 es la partición
– 𝐶 es el número de clases
– 𝑃 es la proporción de ejemplos para esa partición
• Para el caso particular de una clasificación binaria

– 𝐸 𝑆 = −𝑃log2 𝑃 − 𝑁log2(𝑁)
– 𝑆 es la partición
– 𝑃, 𝑁 son la proporción de ejemplos positivos y negativos

• La entropía de un nodo

– La entropía media de los nodos

17

Ejemplo cálculo entropía

𝑃  − 𝑠𝑒𝑟 𝑟𝑜𝑗𝑜
𝑁  − 𝑠𝑒𝑟 𝑎𝑧𝑢𝑙

Nodo: diverso racialmente
Partición izquierda:

𝐸 𝑆 = −𝑃log2 𝑃 − 𝑁log2 𝑁 = −

5
10

log2

5
10

−

5
10

log2

5
10

= 𝟏

Partición derecha:

𝐸 𝑆 = −𝑃log2 𝑃 − 𝑁log2 𝑁 = −

5
15

log2

5
15

−

10
15

log2

10
15

= 0.92

Entropía media nodo:

Nodo: ingresos altos
Partición izquierda:

=

10
25

· 1 +

15
25

· 0.92 = 0.952

𝐸 𝑆 = −𝑃log2 𝑃 − 𝑁log2 𝑁 = −

Partición derecha:

𝐸 𝑆 = −𝑃log2 𝑃 − 𝑁log2 𝑁 = −

Entropía media nodo:

8
12

1
13

log2

8
12

−

4
12

log2

log2

1
13

−

12
13

log2

4
12

12
13

= 0.92

= 0.32

=

12
25

· 0.92 +

13
25

· 0.32 = 0.68

Diverso racialmente
(si/no)

Ingresos altos (si/no)

18

Selección de atributos

• ¿Qué atributo crea las ramas más homogéneas?

– Proporciona una menor entropía
– Proporciona una ganancia de información mayor

• La ganancia de información

– La diferencia de entropía entre

• el nodo anterior
• la media de la entropía de los nodos hijos

𝐼𝑛𝑓𝑜𝐺𝑎𝑖𝑛(𝐹) =  𝐸𝑛𝑡𝑟𝑜𝑝𝑦(𝑝𝑎𝑑𝑟𝑒) − 𝐸𝑛𝑡𝑟𝑜𝑝𝑖𝑎(ℎ𝑖𝑗𝑜𝑠)

Nodo: diverso racialmente

𝐼𝑛𝑓𝑜𝐺𝑎𝑖𝑛 𝐹 = 𝐸𝑛𝑡𝑟𝑜𝑝𝑖𝑎 𝑃𝑎𝑑𝑟𝑒 −  0.952

Nodo: ingresos altos

𝐼𝑛𝑓𝑜𝐺𝑎𝑖𝑛 𝐹 = 𝐸𝑛𝑡𝑟𝑜𝑝𝑖𝑎 𝑃𝑎𝑑𝑟𝑒 −  0.68

19

Índice de Gini

• Calcula

– Probabilidad de que una característica especifica

• Se clasifique incorrectamente cuando se selecciona al azar
– El mayor valor de homogeneidad se da cuando es igual a 0
– Si todos los elementos están vinculados a una sola clase

• Entonces se puede llamar puro
– Solo para particiones binarias

𝐶

𝐺𝑖𝑛𝑖 = 1  −  ෍
𝑖=1

2

𝑝𝑖

20

Ejemplo cálculo Gini

𝑃  − 𝑠𝑒𝑟 𝑟𝑜𝑗𝑜
𝑁  − 𝑠𝑒𝑟 𝑎𝑧𝑢𝑙

Nodo: diverso racialmente
Partición izquierda:
2

𝐺𝑖𝑛𝑖 = 1 −

5
10

−

5
10

Partición derecha:
10
15

𝐺𝑖𝑛𝑖 = 1 −

2

−

5
15

2

2

= 0.50

= 0.44

Gini nodo:
10
25

=

· 0.5 +

15
25

· 0.44 = 0.47

Nodo: ingresos altos
Partición izquierda:
8
12

𝐺𝑖𝑛𝑖 = 1 −

2

−

4
12

Partición derecha:
1
13

𝐺𝑖𝑛𝑖 = 1 −

2

−

12
13

2

2

= 0.44

= 0.14

Diverso racialmente
(si/no)

Ingresos altos (si/no)

Gini nodo:
12
25

=

· 0.44 +

13
25

· 0.14 = 0.07

21

Information Gain vs Índice de Gini

• ¿Cuál elegir?

– El índice de Gini funciona major con grandes de distribuciones de datos
– La information gain funciona major con pequeñas distribuciones de datos

• El Índice de Gini

– Hace particiones de “éxito” o “fracaso”
– Realiza solo una división binaria

• La Information Gain

– Calcula la diferencia entre la entropía antes y después de la división
– Indica la impureza en las clases

Aning, S., & Przybyła-Kasperek, M. (2022). Comparative Study of Twoing and Entropy Criterion for Decision Tree
Classification of Dispersed Data. Procedia Computer Science, 207, 2434-2443.
https://doi.org/10.1016/j.procs.2022.09.301

22

Ejemplo Notebook – 6.2

• 6.2 Explicabilidad

– Una vez entrenado el modelo, los nodos permiten interpretar las

decisiones

23

6.3 Árboles para clasificación

24

Implementaciones

• La construcción de un árbol de decisión no es única

– Si aplicamos una estrategia u otra

• A la hora de decidir en qué orden se hacen las preguntas sobre los atributos

– Podemos encontrar árboles muy distintos

• Ejemplos

– ID3, Quinlan, J. R. 1986. Induction of Decision Trees. Mach. Learn. 1, 1

(Mar. 1986), 81–106

– C4.5, Quinlan, J. R. C4.5: Programs for Machine Learning. Morgan

Kaufmann Publishers, 1993.

– C5.0
– CART Breiman,Friedman,Olshen,Stone: Classification and Decision Trees,

Wadsworth, 1984

Hssina, B., Merbouha, A., Ezzikouri, H., & Erritali, M. (2014). A comparative study of decision tree ID3 and C4.
5. International Journal of Advanced Computer Science and Applications, 4(2), 13-19.

25

Características de los árboles de decisión

• Ventajas

– Son explicables, es fácil entender como se han llevado las

clasificaciones

– Los resultados pueden ser interpretados
• No requieren conocimiento técnico
• Se pueden analizar las consecuencias de llevar a cabo una alternativa

específica
• Desventajas

– Las reglas de clasificación

• son muy sensibles a pequeños cambios en los datos

– No es fácil elegir un árbol óptimo
– Suelen requerir de bastantes datos para obtener resultados

satisfactorios

– Tienden a la sobre parametrización (overfitting)

26

Sobreajuste

• Sobreajuste

– Funciona muy bien en el  entrenamiento
– No generaliza para ejemplos fuera del conjunto de entrenamiento
– Se detecta cuando

• Se reduce el error en el conjunto de entrenamiento
• Aumenta en el conjunto de prueba

27

Poda

• Prepoda

– Un árbol de decision tiende a crecer indefinidamente

• Idealmente hasta que en cada hoja se encuentre un único ejemplo
• Esto genera un sobreajuste

– Se trata de impedir el crecimiento del árbol

• Pospoda

– Se permite que el árbol crezca
– Posteriormente se realiza una poda
– Es una de las técnicas más utilizada

28

Ejemplo Notebook – 6.3

• 6.3 Poda y ajuste

– Efecto de no limitar el número máximo de niveles

29

6.4 Árboles vs modelos
lineales

30

¿Qué modelo es mejor ?

• Si existe un modelo estructural

– Entre las variables y la variable respuesta
– Una regresión lineal funciona mejor que un árbol de decisión

• Árbol de decisión mejores
– Problemas no lineales
– Relaciones complejas entre las variables

31

Ejemplo Notebook - 5

• 5.2 Métricas Clasificación flores iris

32

Referencias Imágenes

•

Diapositiva 26:

–

Fuente: By Gringer - Own workThis file was derived from: Overfitting.pngSVG version of original by Dake~commonswiki.
Created from scratch using Inkscape v0.45., CC BY 3.0, https://commons.wikimedia.org/w/index.php?curid=2959742

33

Tema 7. Máquinas de vectores de soporte (SVM)

Antoni Munar Ara

Presentación de la
asignatura

Índice

7.1 Introducción y conceptos básicos
7.2 Separación en hiperplanos
7.3 Clasificador de margen máximo
7.4 Soft margin
7.5 El truco del kernel
7.6 Aplicaciones de SVM

2

7.1 Introducción y conceptos
básicos

3

Máquinas de vector soporte

• Se basan en enfoques geométricos

• Objetivo del algoritmo

– Crear una frontera o línea de decisión

• Capaz de separar un conjunto de datos en diferentes clases

– Esta frontera o límite de decisión

• Es un hiperplano en el espacio de 𝒏 dimensiones de las características

•

Inicialmente pensados para problemas de clasificación binaria
– Se han extendido hasta abarcar problemas de regresión

4

Usos

• Se utilizan para resolver problemas de

– Reconocimiento de patrones
– Clasificación de imágenes
– Categorización de texto

• Son especialmente eficaces en

– Espacios de alto número de dimensiones
– Datos no separables linealmente

5

Objetivo fundamental de los SVM

• Hallar un plano

– Que separe las clases en el espacio de características

Vectores de soporte

Hiperplano de separación

6

SVM conceptos (1/2)

• Hiperplano

– Extensión del concepto de plano a un espacio de 𝑛 dimensiones

• Objeto matemático de dos dimensiones (en un espacio tridimensional)
• Contiene infinitos puntos y rectas

– Separa el espacio de 𝑛 dimensiones en dos mitades

• Margen

– Distancia

• entre el hiperplano de separación
• los puntos de cada clase más cercanos
– El objetivo del SVM es maximizar este margen
• Minimizando los errores de clasificación

Margen

7

SVM conceptos (2/2)

• Vector

– Segmento de recta

• Tomado a partir de un punto del espacio
• Su longitud representa a escala una magnitud
• Una dirección y un sentido

Ԧ𝑣

• Vectores de soporte

– Son los puntos de datos

• Que se encuentran más cerca del límite de decisión

– Hiperplano del SVM

– Determinan la posición y orientación del hiperplano

Vectores
de soporte

8

7.2 Separación en
hiperplanos

9

Objetivo: Separación en hiperplanos

• SVM es un modelo que representa los puntos de muestra

– En un espacio 𝑛 dimensional

• Las dimensiones corresponden a las características o features
– Separando las clases en dos espacios lo más amplio posible

• Separados mediante un hiperplano de separación

SVM tienen como objetivo
buscar un plano que separe
las clases

10

Función matemática

• Establecer la función matemática que separa los puntos

– En dos clases

𝑓 𝑋 = 𝛽0 + 𝛽1 · 𝑋1 + 𝛽2 · 𝑋2+ ··· +𝛽𝑝 · Xp

𝑆𝑖 𝑓 𝑋 > 0  → 𝑨𝒛𝒖𝒍
𝑆𝑖 𝑓 𝑋 < 0  → 𝑵𝒆𝒈𝒓𝒐

11

7.3 Clasificador de margen
máximo

12

Clasificador de margen máximo

• En el caso de un problema de clasificación binaria

• Es necesario buscar entre todos los hiperplanos posibles

– Aquel que nos proporcione la mayor diferencia entre las dos clases
– La mayor distancia entre los puntos que pertenecen a una y a otra clase

• Hipótesis subyacente

– Suponemos que este hiperplano será el que tendrá una mayor distancia

• En el conjunto de test y en las predicciones futuras

13

Margen máximo

• Hiperplano

– que proporcione la mayor diferencia entre las dos clases

14

7.4 Soft Margin

15

Problema: datos no linealmente separables

• Principal problema en casos reales

– Los datos no son en general separables por una línea recta

16

Dos tipos de márgenes

• Hard margin (margen duro)
– Todas las muestras

• Soft margin (margen duro)
– Algunas muestras:

• Encontrarse fuera del margen
• Han de estar correctamente

clasificadas

• Pueden encontrarse dentro del

margen

• Pueden estar incorrectamente
clasificadas (el otro lado del
hiperplano de separación)

17

Control del soft margin

• Se controla a través de un parámetro C (función de coste)
• Hace que el margen sea más grande o pequeño

– Un valor de C grande hace que el margen sea más pequeño
– Un valor de C pequeño hace que el margen sea más grande

18

Fronteras Lineales

• Problema de las fronteras lineales

– En ocasiones no es posible separar dos clases

• Opción:

– Incrementar la distancia entre variables

• Mediante transformaciones

19

Incremento distancia entre variables

•

 Transformaciones
– Pasar a un espacio de más dimensiones
– Ajustar un SVM en este nuevo espacio
– Resultan en fronteras de decisión

• No lineales con respecto al problema original

• Ejemplo: polinomios cúbicos

– Se puede pasar de dos a nueve variables

𝑓 𝑋 = 𝛽0 + 𝛽1 · 𝑋1 + 𝛽2 · 𝑋2 +𝛽3 · 𝑋1
+𝛽6 · 𝑋1

2 + 𝛽4 · 𝑋2
2
2· 𝑋2+ 𝛽9· 𝑋1 · 𝑋2

3 + 𝛽7 · 𝑋2

3 + 𝛽8 · 𝑋1

2 + 𝛽5 · 𝑋1· 𝑋2

20

Regresión con SVM

• Los SVM también pueden usarse para regresión
• Cambia el enfoque
– Clasificación:

• Encontrar un hiperplano, tal que la ecuación del hiperplano 𝑓 𝑥

clasifique correctamente los ejemplos

– Regresión:

• Encontrar un hiperplano, tal que la ecuación del hiperplano para todos los
ejemplos 𝑓 𝑥  se desvíe menos de 𝜀 del valor  𝑦 para dicho ejemplo 𝑥

21

7.5 El truco del kernel

22

Problema con los que se enfrenta un SVM

• Los datos que se encuentran en la práctica

– Son multidimensionales

• Mas de dos variables

– Curvas no lineales de separación
– Datos que no pueden ser completamente separables
– Clasificaciones en más de dos categorías

• Las expansiones de variables con polinomios

– Computacionalmente muy costosas
– Especialmente con gran número de dimensiones

𝑓 𝑋 = 𝛽0 + 𝛽1 · 𝑋1 + 𝛽2 · 𝑋2 +𝛽3 · 𝑋1
+𝛽6 · 𝑋1

2 + 𝛽4 · 𝑋2
2
2· 𝑋2+ 𝛽9· 𝑋1 · 𝑋2

3 + 𝛽7 · 𝑋2

3 + 𝛽8 · 𝑋1

2 + 𝛽5 · 𝑋1· 𝑋2

23

Kernels

• Construcción matemática

– Permite extender los vectores a un espacio de coordenadas superior
– Obteniendo fronteras de decisión no lineales
– Sin necesidad de hacer un mapeo completo

• Simplemente mediante el producto escalar de los vectores de soporte

– 𝐾 Ԧ𝑥 · Ԧ𝑦

• Evita tener que realizar las complejas transformaciones con polinomios

24

Tipos de kernel y parámetros

• Función que toma como entrada dos vectores de datos
• Funciones más utilizadas

– Lineal
– Radial Basis Function (RBF)
– Sigmoide
– Polinómica

25

Kernel hiperparametros

• Controlan el comportamiento del kernel

– 𝛾

• Valores pequeños: frontera lineal
• Valores grandes: flexibilidad modelo, no lineal

26

Aplicaciones de las SVM

• Clasificación de imágenes

– Previa reducción de las imágenes a vectores

• Clasificación de texto
• Bioinformática
• Detección de fraude y seguridad
• Otros

– Geociencias, marketing, visión por computador

27

Ejemplo Notebook - 7

• 7.1 Clasificación de especies de frijoles

28

Referencias Imágenes

•

•

Diapositiva 24:

–

Fuente: https://towardsdatascience.com/the-kernel-trick-c98cdbcaeb3f

Diapositiva 28:

–

Fuente: Shriya, Sakshi et al. “Dry Beans Classification using Ensemble Learning.” 2023 3rd International Conference on
Smart Data Intelligence (ICSMDI) (2023): 327-334.

29

Tema 8. Clasificación con Naïve Bayes

Antoni Munar Ara

Presentación de la
asignatura

Índice

8.1 Introducción
8.2 Teorema de Bayes
8.3 Tablas de probabilidad condicionada
8.4 Independencia condicional en el clasificador Naïve Bayes
8.5 Clasificador Naïve Bayes
8.6 Clasificador Naïve Bayes con variables numéricas

2

8.1 Introducción

3

Modelos Naïve Bayes

• Es un modelo de clasificación de los más simples

– Funciona sorprendentemente bien
– Se usa como referencia base en muchos casos

• Modelo probabilístico

– Se basa en el teorema de Bayes

• A partir de una estimación inicial
• Calcula una probabilidad posterior a partir de  la evidencia de los datos

– Asume que las variables predictoras son independientes

• De ahí la denominación de Naïve (ingenuo)

4

8.2 Teorema de Bayes

5

Concepto de probabilidad

• Regularidad observada en la realidad que nos rodea
• Dado un universo de todos los casos posibles Ω

– Partición de los diversos casos: 𝐴𝑖 tal que

• 𝐴𝑖 ∩ 𝐴𝑗 = ∅
𝑛 𝐴𝑖 = Ω
• ڂ𝑖=1

𝜴

𝑨𝒊

• La probabilidad (frecuentista) puede definirse como

– 𝑃𝑟𝑜𝑏 𝐴𝑖 =

lim
𝑜𝑏𝑠𝑒𝑟𝑣𝑎𝑐𝑖𝑜𝑛𝑒𝑠→∞

𝑛𝑖
𝑛𝑡𝑜𝑡𝑎𝑙𝑒𝑠

6

Ejemplo concepto de probabilidad

• Dado con todas las caras iguales
– “Equiprobables” (definición circular)

𝑃𝑟𝑜𝑏 𝑜𝑏𝑡𝑒𝑛𝑒𝑟 1 = 𝑃𝑟𝑜𝑏 𝑜𝑏𝑡𝑒𝑛𝑒𝑟 2 = ⋯ = 𝑃𝑟𝑜𝑏 𝑜𝑏𝑡𝑒𝑛𝑒𝑟 6 =

# 𝑐𝑎𝑠𝑜𝑠 𝑓𝑎𝑣𝑜𝑟𝑎𝑏𝑙𝑒𝑠
#𝑡𝑜𝑡𝑎𝑙 𝑐𝑎𝑠𝑜𝑠

𝑃𝑟𝑜𝑏 𝑝𝑎𝑟 =

#𝑑𝑜𝑠 + #𝑐𝑢𝑎𝑡𝑟𝑜 + #𝑠𝑒𝑖𝑠
# 𝑡𝑜𝑡𝑎𝑙𝑒𝑠

=

1 + 1 + 1
6

= 0.5

7

Teorema de Bayes

𝑃 𝐴 𝐵 =

𝑃 𝐵 𝐴 · 𝑃(𝐴)
𝑃(𝐵)

• 𝑃(𝐴): la probabilidad del suceso A
• 𝑃 𝐵 : la probabilidad del suceso B
• 𝑃(𝐵|𝐴): la probabilidad de que suceda 𝑩 sabiendo que 𝐴 ya ha sucedido

– Probabilidad de 𝐵 condicionada por 𝐴

• 𝑃(𝐴|𝐵): la probabilidad de que suceda 𝑨 sabiendo que 𝐵 ya ha sucedido

– Probabilidad de 𝐴 condicionada por 𝐵

8

Ejemplo: detección de spam

• Probabilidad de que un correo electrónico sea spam si contiene la palabra

viagra

A posteriori

𝑃 𝑠𝑝𝑎𝑚 𝑣𝑖𝑎𝑔𝑟𝑎 =

Verosimilitud

A priori

𝑃 𝑣𝑖𝑎𝑔𝑟𝑎 𝑠𝑝𝑎𝑚 · 𝑃(𝑠𝑝𝑎𝑚)
𝑃(𝑣𝑖𝑎𝑔𝑟𝑎)

• A priori:

– Cuanto de probable es que el mensaje sea spam
– Es la ocurrencia en general de los mensajes spam
– Si, por ejemplo, los mensajes spam son raros, será raro que este lo sea también

• Verosimilitud:

– Se aprende de los datos (entrenamiento)
– Que evidencia hay de que en los emails de spam se da la palabra viagra

• A posteriori

– Es la probabilidad que buscamos en un sistema real
– Si veo un email con la palabra viagra que probabilidad hay de que sea spam

• Verosimilitud marginal

Verosimilitud marginal

– Generalmente un factor de normalización para que la probabilidad a posteriori sea una probabilidad
– Probabilidad de que la palabra viagra aparezca en los emails – difícil de estimar

9

8.3 Tablas probabilidad
condicionada

10

Ejemplo spam

• Construyamos una tabla de frecuencias

– Indicar el número de veces que el evento aparece en cada una de las

situaciones

Ocurrencias

Viagra

No Viagra

Total

Spam

No Spam

Total

4

1

5

16

79

95

20

80

100

11

Tablas de verosimilitud

Ocurrencias

Viagra

No Viagra

Total

Spam

No Spam

Total

4

1

5

16

79

95

20

80

100

𝑃 𝑣𝑖𝑎𝑔𝑟𝑎 𝑠𝑝𝑎𝑚 =

4
20

12

Tablas a priori y verosimilitud marginal

Ocurrencias

Viagra

No Viagra

Total

Spam

No Spam

Total

4

1

5

16

79

95

20

80

100

𝑃 𝑠𝑝𝑎𝑚 =

4 + 16
100

=

20
100

𝑃 𝑣𝑖𝑎𝑔𝑟𝑎 =

4 + 1
100

=

5
100

13

Probabilidad a posteriori

Ocurrencias

Viagra

No Viagra

Total

Spam

No Spam

Total

4

1

5

16

79

95

20

80

100

𝑃 𝑠𝑝𝑎𝑚 𝑣𝑖𝑎𝑔𝑟𝑎 =

4
20

·

20
100
5
100

=

4
5

= 0.8 = 80%

14

7.4 Independencia
condicional

15

Predicción 𝑦 depende varias variables 𝑥𝑖

• En general clasificaremos un email, no solo dependiendo de la

presencia de una única palabra
– Sino de varias o varias características

• Ejemplo: muchos signos de exclamación “ !!! ”

• En este caso tenemos

– 𝑃(𝑠𝑝𝑎𝑚|𝑥𝑖) donde 𝑥1 = "𝑣𝑖𝑎𝑔𝑟𝑎“, 𝑥2 = "𝑜𝑓𝑒𝑟𝑡𝑎“, etc.

16

Independencia de factores 𝑥𝑖
• La fórmula general de la probabilidad condicionada es:

– 𝑃 𝑦 𝑥1, 𝑥2, ⋯ , 𝑥𝑛

• Si asumimos que 𝑥1, 𝑥2, ⋯ , 𝑥𝑛son independientes

– 𝑃 𝑥1, 𝑥2, ⋯ , 𝑥𝑛 = 𝑃 𝑥1 · 𝑃 𝑥2  ⋯ 𝑃 𝑥𝑛

• Y entonces podemos simplificar:

– 𝑃 𝑦 𝑥1, 𝑥2, ⋯ , 𝑥𝑛 = 𝑃 𝑦|𝑥1 · 𝑃 𝑦|𝑥2  ⋯ 𝑃 𝑦|𝑥𝑛

• Decimos entonces que

– El clasificador Naïve Bayes asume la independencia entre las

características

– En el ejemplo, que la aparición de la palabra “viagra” es independiente de

que haya muchos “ !!! ”

– Esta es la razón de que se denomine Naïve (ingenuo)
– Esta circunstancia no es cierta en general, pero sin embargo el método es

sorprendentemente efectivo

17

8.5 Clasificador Naïve Bayes

18

Pasos para realizar en un problema de clasificación

1. Para las distintas clases 𝐶𝑖 y sus correspondientes

características
– A partir de los datos de entrenamiento crear una tabla de frecuencias

2. Crear la correspondiente tabla de probabilidad

clase 𝑥1 𝑥2 𝑥𝑛

3. En inferencia

1. Usando Naïve Bayes calcular la probabilidad a posteriori para cada clase
𝑛 𝑝( 𝑥𝑗|𝐶𝑖)

𝑃(𝐶𝑖| 𝑥1, 𝑥2, ⋯ , 𝑥𝑛) = 𝑝(𝐶𝑖) · ς𝑗=1

2.

La clase predicha es la clase con la mayor probabilidad

19

8.6 Clasificador Naïve Bayes
con Variables Numéricas

20

Variables numéricas con Naïve Bayes

• En Naïve Bayes

– No se pueden utilizar directamente las variables numéricas

• Hay que transformarlas en categóricas

– Binning
– K-bins
– Transformación de discretización

• A cada valor se le asigna una etiqueta

21

Métodos para agrupar en k-valores discretos

• Uniforme

– Cada contenedor tiene la misma anchura e intervalo de valores
– Balance:

• Número de bins

– Pocos: se pierde mucha información
– Demasiados: procesamiento muy costoso, necesita más datos

• Cuartiles

– Cada contenedor tiene la misma cantidad de valores
– Divide en percentiles

• Clusters

– Se identifican los grupos según un cierto criterio
– Se les asignan las instancias

22

Sklearn KBinDiscretizer

•

•

•

Strategy:

– Hace referencia a la estrategia de división
• Uniforme, cuantiles o clustering k-medios

n-bins

– Cantidad de contenedores. Depende estrategia

• Uniforme: se puede escoger
• Cuartiles: menor que el número de

observaciones
K-means: especificar un valor

•
Encode

– Codificación ordinal.
–

A cada valor numérico, se le asigna un valor
ordinal

23

Ejemplo Notebook - 8

• 8.1 Clasificación de especies de frijoles

24

Referencias Imágenes

•

•

•

Diapositiva 7:

–

Fuente: http://lifelonglearningteachers.blogspot.com/2011/12/clil-lesson-for-sciencegeography.html

Diapositiva 23

–

Fuente: https://scikit-learn.org/stable/auto_examples/preprocessing/plot_discretization_strategies.html

Diapositiva 28

–

Fuente: Shriya, Sakshi et al. “Dry Beans Classification using Ensemble Learning.” 2023 3rd International Conference on
Smart Data Intelligence (ICSMDI) (2023): 327-334.

25

Tema 9. Combinación de clasificadores.
Bootstrapping, bagging y boosting
Antoni Munar Ara

Presentación de la
asignatura

Índice

9.1 Introducción
9.2 Técnica de muestreo bootstrap
9.3 Método bagging
9.4 Método boosting
9.5 Stacking
9.6 Comparación entre modelos de ensemble

2

9.1 Introducción

3

Introducción

• Ensembles / conjuntos de modelos

– Métodos que combinan múltiples modelos de machine learning
– El objetivo es que la combinación sea un modelo con mayor capacidad

de generalización que los modelos tomados individualmente

• Distintas aproximaciones

– Concatenación de modelos especializados en distintas etapas
– Concatenación de modelos iterando en distintos subconjuntos de datos
– Votación de distintos modelos más simples

4

Ejemplo: bagging y boosting
• Bagging (bolsa):

– Algoritmos más simples son usados en

paralelo

– Aprovechan la independencia entre

modelos simples
– El error se promedia
– Decisión final:

• Clasificación: votación
• Regresión: promedio

• Boosting:

– Modelos entrenados secuencialmente
– Sobre los errores de los anteriores
– Decisión final:

• Clasificación: votación
• Regresión: promedio

5

9.2 Técnica de muestreo
bootstrap

6

Muestreo Bootstrap
• Método basado en el muestreo aleatorio con reemplazamiento
• En vez de realizar una única muestra

– Realizar varias muestras
– Calcular el estadístico sobre las distintas muestras
– Las muestras se toman repetidas veces

• Con reemplazamiento

• Permite aumentar la información disponible sobre una

característica concreta
– En lugar de usar una única muestra
– Combate el error de muestreo

Efron, B. (1979). «Bootstrap methods: Another look
at the jackknife». The Annals of Statistics 7 (1): 1-
26.dddddddddd

7

Técnica muestreo (1/2)

• Fijar 𝑚 el número de muestras desadas
•

Iterando de 1 ⋯ 𝑚
– Seleccionar aleatoriamente un valor del dataset original
– Añadirlo a la muestra
– “devolverlo” al conjunto original

• Se usa como base para entrenar al modelo

8

Técnica muestreo (2/2)

• Tamaño muestra

– En ML es habitual tomar como tamaño de la muestra

• El tamaño del dataset original

– La toma de muestras es con reemplazo

– Si el dataset es demasiado grande
• Se toma como tamaño el 50-80%

• Número de repeticiones

– Lo suficientemente grande como para garantizar muestras significativas

• Media, desviación estándar y el error stándar en la muestra

9

9.3 Método bagging

10

Bagging

• Combinar el resultado de varias instancias de un modelo
– Sobre muestras aleatorias de los datos del conjunto original

• Obtenidas con bootstrap

– Agregar las predicciones individuales siguiendo cierto criterio

Datos originales

Bootstrap

Clasificador

Clasificador

Clasificador

Agregación

Clasificador ensemble

Bagging

11

Asunciones bagging

• Divide el conjunto de entrenamiento en distintos subconjuntos

– Muestra uniforme
– Muestra con reemplazo
– El tamaño de la muestra es igual al tamaño del conjunto de entrenamiento

• No exactamente igual
• No contiene a todos los individuos (repeticiones)

• Con cada subconjunto

– Se crea un modelo predictivo
• Se agregan las predicciones
– Generalmente el promedio

• Se consigue disminuir la varianza de las predicciones

– consenso

12

Out-of-bag error

• ¿ Cómo se estima el error en un modelo bagging ?

• Se usan midiendo el error promedio

– En los datos que no han formado parte de ninguna de las bolsas

• De esta forma no es necesaria usar

– Validación cruzada
– Retener muestras

13

9.4 Boosting

14

Método boosting (1/2)

• Método de combinación de modelos
– Aplicable para regresión y clasificación
– No involucra muestreo Bootstrap

• Los modelos

– Se generan de forma secuencial
– Cada modelo utiliza la información de los modelos anteriores

• En cada iteración

– Los datos son recalibrados
– Los ejemplos que estaban correctamente clasificados

• Pierden peso

– Los ejemplos incorrectamente clasificados

• Ganan peso

15

Método boosting (2 / 2)

•

Idea fundamental
– Elegir conjuntos de entrenamiento para el modelo base

• De tal forma que le obligue a inferior algo nuevo

– En cada invocación sobre cada subconjunto

– En la agregación

• Se otorga mayor peso al algoritmo con menores errores

Modelos 1,2, …,N son modelos individuales (ej. árboles de decision)

Modelo 1

Modelo 2

Modelo N

Fallos

Fallos

Selección 1

Selección 2

Selección N

Modelo ensemble (junto con todos los predecesores)

16

AdaBoost (1/2)

• Adaptive Boosting propuesto en 1995 (Freund & Schapire)
• Consiste en crear varios predictores sencillos secuenciales

– El siguiente ajusta bien lo que el anterior no ajustó

• Algoritmo:

Entrenar un clasificador inicial

1.
2. Obtener una clasificación
3.
4. Construir un nuevo clasificador con mejor desempeño en los casos anteriores

Identificar los casos mal clasificados

Los puntos donde el previo ha fallado tienen ahora más peso

1.
Repetir pasos 2-4

5.
6. Construir un ensemble con los clasificadores asignando pesos a las

decisiones de los diferentes clasificadores

• Vídeo: AdaBoost, Clearly Explained

17

Ejemplo AdaBoost

• Generalmente se usa con modelos de árboles de decisión

– Extremadamente simples, un nodo y dos hojas

• Se denominan stumps

•

•

Los stumps se van aplicando secuencialmente
– Ordenándolos por orden de efectividad separando los ejemplos
Los ejemplos tienen distintos “pesos” o “importancia”
– En una iteración dada los ejemplos clasificados mal por el stump anterior
• Tienen más peso, y si se clasifican bien dan más importancia al stump

• En inferencia

– La clasificación se realiza por mayoría, cada stump emitiendo un voto
– Los stumps que clasifican mejor tienen más peso en la decisión

18

Otros métodos de boosting

• Gradient Boosting

– En vez de ajustar los pesos de los datos
– Minimiza una función de pérdida

• Diferencia entre la predicción y el valor real

– Funciona tanto para la regression como para clasificación
– Gradient Boost Part 1 (of 4): Regression Main Ideas

• XGBoost (Extreme Gradient Boosting)
– Implementación de gradient boosting
– Mayor velocidad y rendimiento
– XGBoost Part 1 (of 4): Regression

• CatBoost

– Usa codificación de lo que hay clasificar
– CatBoost Part 1: Ordered Target Encoding

19

9.5 Stacking

20

Stacking

• Combina las predicciones de diferentes modelos base
• Dichas predicciones son la entrada para otro modelo

– El meta-modelo

• El meta-modelo realiza la predicción final

Datos de
Entrenamiento

Modelo 1

Modelo 2

Modelo n

Nuevo Conjunto
de datos de
entrenamiento

Meta-
modelo

Predicción
final

21

9.6 Comparación modelos de
ensemble

22

Tabla resumen

Algoritmo

Bagging

Boosting

Stacking

Propósito

Tiende a reducir
la varianza

Tiende a reducir el
sesgo

Mejora la exactitud

Aprendizaje base

Homogéneo

Homogéneo

Heterogéneo

Entrenamiento
base

Agregación

Paralelo

Secuencial

Secuencial

Voto mayoritario o
promedio

Peso promedio

Promedio ponderado

23

Ejemplo Notebook - 9

• 9.0 Stacking de modelos

24

Referencias Imágenes

•

•

•

Diapositiva 8:

–

Fuente: Kuhn, M., & Johnson, K. (2013). Applied predictive modeling (Vol. 26, p. 13). New York: Springer.

Diapositiva 23

–

Fuente: https://scikit-learn.org/stable/auto_examples/preprocessing/plot_discretization_strategies.html

Diapositiva 23

–

Fuente: https://scikit-learn.org/stable/auto_examples/preprocessing/plot_discretization_strategies.html

25

Tema 10. Aprendizaje supervisado. Random Forests

Antoni Munar Ara

Presentación de la
asignatura

Índice

10.1 Introducción
10.2 Descripción Random Forest
10.3 Ventajas y Desventajas
10.4 Interpretación del error out-of-bag
10.5 Evolución del número de árboles en función del número de
variables e importancia de variables

2

10.1 Introducción

3

Introducción

• Ensembles / conjuntos de modelos

– Métodos que combinan múltiples modelos de machine learning
– El objetivo es que la combinación sea un modelo más potente
– Generalmente se apoyan en la noción del weak learner

• Combinar modelos más sencillos que en conjunto resultan más potentes

• Dos técnicas

– Bagging: los modelos se combinan en paralelo
– Boosting: los modelos son usados secuencialmente

• Random Forest

– Combinación en paralelo de árboles de decisión más sencillos

4

Excursión – Sabiduría de las multitudes
• En 1906, observación de Francis Galton
– Feria de ganado en Plymouth, Inglaterra
– Concurso para estimar a ojo el peso de una cabeza

de ganado

– 800 personas participaron

• Granjeros, campesinos y personas no expertas

• Galton, científico y estadístico

– Escéptico por el nivel de conocimiento de las

personas presentes

• Resultados

– La media de las predicciones de todas las personas

fue de 1207 libras

• El peso del toro era de 1198 libras

– La media de la predicción colectiva tuvo una

precisión del 1%

• Este resultado

– Se ha confirmado en numerosos experimentos

posteriores

– La sabiduría de las multitudes

5

Deficiencias Árboles de Decisión

• Deficiencias de los árboles de decisión

– Tienden a sobreajustar los datos
– Tienden a ser inestables con mucho ruido

• Dependen de la muestra de datos tomadas para el entrenamiento

– Muestran una gran varianza

• Los Random Forest abordan estos problemas

– Combatir la varianza combinando el resultado de varios árboles
– En los problemas de clasificación

• La moda, o la predicción mayoritaria

– En los problemas de regresión
• La media de las predicciones

6

10.2 Descripción Random
Forest

7

Estructura Random Forest

1. Se muestrean N instancias de los datos originales
– Usando la técnica de Bootstrap: con reemplazo

2. Si los datos constan de P variables

–
–

Se especifica un número M < P
En cada sub-árbol en cada nodo
•

Se seleccionan aleatoriamente M variables de las P

–

sin reemplazamiento

–

El valor de M es igual para todos los árboles
3. Se entrenan T árboles con N instancias y escoge

M variables
– Cada árbol crece lo más que puede y no hay poda
–

El límite de lo que puede crecer lo da la capacidad de
tomar conjuntos distintos de M variables entre las P

•

En inferencia, resultado de cada árbol se combina
– Mediante el voto por mayoría para clasificación
– Mediante el promedio para la regresión

conjunto de datos X

𝑵 puntos
𝑴 variables

𝑵 puntos
𝑴 variables

Árbol #1

Árbol #2

Clase C

Clase A

…

…

…

…

𝑵 puntos
𝑴 variables

Árbol #T

Clase B

Voto mayoritario

CLASE FINAL

8

Random Forest

• Colección de árboles de decisión

– Cada uno de ellos difiere ligeramente de los otros
– Son más sencillos, usan menos variables

• Variables elegidas aleatoriamente

• Conjunto de árboles de decisión

– Permite que cada variable tenga la oportunidad de aparecer

• En distinto orden y en distintas combinaciones
• Combate la varianza intrínseca de los árboles de decisión

– Los distintos árboles son más sencillos y se pueden ejecutar en paralelo

• Velocidad de ejecución

– Promediar el resultado final de los árboles de decisión

• Permite controlar la varianza

9

10.3 Ventajas y desventajas

10

Ventajas y desventajas

Desventajas
• A diferencia de un árbol de decisión
– No es fácilmente interpretable
– Puede necesitar ajuste de

hiperparámetros

Ventajas
• Modelo de propósito general

– Funciona bien en la mayoría de los

problemas

– Puede gestionar datos

• Con ruido
• Faltantes
• Variables categóricas y contínuas

– Utilizable igualmente

• Gran número de instancias
• Gran número de variables

11

10.4 Interpretación error out-
of-bag

12

Error Out-of-bag

• En el método de bootstrapping

– Se seleccionan con reemplazamiento 𝑀 conjuntos de 𝑛 observaciones

de un total de datos de entrenamiento con 𝑁 ejemplos

• 𝑥3, 𝑥17, … , 𝑥𝑛  del conjunto de datos  1

𝑁 𝑥𝑖

• En la selección de los distintos 𝑴 conjuntos

– Al ser con reemplazamiento, generalmente no se seleccionan todos

los ejemplos disponibles

– Generalmente, y como regla, los árboles de decisión seleccionan sólo

2/3 de todos los datos disponibles

– El resto sin seleccionar es conocido como out-of-bag

datos escogidos
en el bootstrap

Conjunto total
de datos

Out-of-bag

13

Validación cruzada y out-of-bag

• No es necesario utilizar la validación cruzada

– Las muestras out-of-bag proporcionan una estimación similar

• Simplemente

– Observar la evolución del out-of-bag error
– Una vez que se haya estabilizado, se puede detener el entrenamiento

14

Otros métodos de boosting

• Gradient Boosting

– En vez de ajustar los pesos de los datos
– Minimiza una función de pérdida

• Diferencia entre la predicción y el valor real

– Funciona tanto para la regression como para clasificación
– Gradient Boost Part 1 (of 4): Regression Main Ideas

• XGBoost (Extreme Gradient Boosting)
– Implementación de gradient boosting
– Mayor velocidad y rendimiento
– XGBoost Part 1 (of 4): Regression

• CatBoost

– Usa codificación de lo que hay clasificar
– CatBoost Part 1: Ordered Target Encoding

15

10.5 Evolución del número de
árboles en función del
número de variables por
árbol e importancia de
variables

16

Hiper-parámetros Random Forest

• Los hiper-parámetros de Random Forest

– Número de árboles
– Número de variables

• Evaluadas en cada iteración
– Profundidad de los árboles

• En la práctica, no tiene gran influencia

17

Número de árboles

•

Intuición
– A mayor número de árboles: mejores resultados

• Práctica

– Existe un punto óptimo donde el error no se reduce

• A pesar de añadir más árboles

18

Importancia de variables
• Conectada con la explicabilidad
• En un Random Forest

– No tiene una interpretación tan directa
– Sin embargo, se puede estimar

• A medida que se construyen los árboles de decisión

– Se puede calcular la función de error para una determinada variable

• En cada punto de división

• Usando el índice de Gini

– Cada vez que se divide un nodo en un árbol de decisión

• Se mide la impureza del índice de Gini para todos los nodos descendientes
• Se suman las disminuciones de impureza

– En los nodos de todos los árboles donde participa esa variable

• La suma de la disminución de impureza de todas las variables

– Se normaliza igualándola a la unidad
– Se ordenan las variables según su disminución de impureza relativa
– Se obtiene una importancia relativa de las distintas variables

19

Ejemplo

rf_model = RandomForestClassifier(n_estimators=100, random_state=42)
rf_model.fit(X, y)

# Obtener importancias de las variables
importances = rf_model.feature_importances_

# Se representa las mportancias de las variables
(…)

20

Conclusión – Ventajas Random Forest
•
Funciona muy bien con grandes cantidades de datos.
• Puede manejar un gran número de variables de entrada

– Sin necesidad de eliminar ninguna.

• Puede estimar la importancia de las variables dentro de la clasificación
• Genera una estimación imparcial interna del error de generalización

•
•

•

•

–  A medida que avanza con la construcción del bosque.
Trabaja muy bien ante la existencia de datos faltantes.
Es capaz de equilibrar el error
– En un conjunto de datos desbalanceados
Es menos propenso al sobreajuste de un único árbol de decisión individual
– Gracias a la diversidad introducida.
Funciona muy bien para los problemas
– Tanto de clasificación y de regresión.

• No requiere de un ajuste fino de hiperparámetros complicados

– Es menos sensible a la elección de estos

21

Ejemplo Notebook - 10

• Predicción de abandono de un cliente de una compañía de

telecomunicaciones con Random Forests

22

Referencias Imágenes

•

•

•

Diapositiva 8:

–

Fuente: Kuhn, M., & Johnson, K. (2013). Applied predictive modeling (Vol. 26, p. 13). New York: Springer.

Diapositiva 23

–

Fuente: https://scikit-learn.org/stable/auto_examples/preprocessing/plot_discretization_strategies.html

Diapositiva 23

–

Fuente: https://scikit-learn.org/stable/auto_examples/preprocessing/plot_discretization_strategies.html

23