Preparación NLP

Bloque 1

Etiquetado Morfosintáctico (POS Tagging) y
Algoritmo de Viterbi

1. Calcular probabilidad de emisión o transición

2. Completar celdas vacías de la Matriz de Viterbi

3. Realizar backtracking

Etiquetado Morfosintáctico (POS Tagging) y
Algoritmo de Viterbi

Analiza la oración "El sueño trae paz".

El corpus ha contado:
-

1.000.000 palabras con etiqueta NOUN

-

12.500 veces la palabra SUEÑO

Etiquetado Morfosintáctico (POS Tagging) y
Algoritmo de Viterbi

Utilizamos la fórmula

probabilidad de 0,0125 de que la palabra concreta que emita sea SUEÑO

Etiquetado Morfosintáctico (POS Tagging) y
Algoritmo de Viterbi

Rellena la Matriz de Viterbi para la palabra sueño

Etiquetado Morfosintáctico (POS Tagging) y
Algoritmo de Viterbi

Sueño

1. Paso anterior (columna anterior) en Viterbi: DET = 0,003.

2. Etiqueta anterior (DET) a la actual (NOUN) en Transición: DET = 0,3.

3. Dado un NOUN (calculado antes): NOUN = 0,0125

0,003 x 0,3 x 0,0125 = 0,00001125

Etiquetado Morfosintáctico (POS Tagging) y
Algoritmo de Viterbi

Trae

1. Paso anterior en Viterbi: NOUN = 0,00001125.

2. Etiqueta anterior (NOUN) a la actual (VERB) en Transición: NOUN= 0,2.

3. Dado un VERB en Emisión: VERB = 0,01.

0,2 x 0,00001125 x 0,01 = 0,0000000225

Etiquetado Morfosintáctico (POS Tagging) y
Algoritmo de Viterbi

Backtracking – ADJ VERB NOUN DET

1. Buscamos el valor más alto en la última columna Viterbi: ADJ = 2,25 x 10-11.

2. ¿De dónde ha salido ese valor? Transición ADJ->VERB = 0,1 y Emisión VERB =

0,01

3. Buscamos el valor más alto en columna SUEÑO de Viterbi: NOUN = 1,12 x 10-

5.

4. Viene de Transición NOUN->VERB = 0,2 y Emisión VERB = 0,01.

5. Buscamos el valor más alto en columna EL de Viterbi: DET = 0,003.
6. Viene de Transición DET->INIT = 0,3 y Emisión DET = 0,01.

Etiquetado Morfosintáctico (POS Tagging) y
Algoritmo de Viterbi

¿Acertó sintácticamente?

Comprobamos si las etiquetas calculadas coinciden con la categoría real de la
palabra.

El (det) sueño (noun) trae (verb) paz (adj).

Puesto que paz es un noun y lo está etiquetando como adj, es erróneo.

Bloque 2

Análisis Sintáctico y el Algoritmo CKY.

1. Completar celdas de la matriz triangular de CKY

2. Determinar ambigüedad sintáctica

3. Dibujar árbol sintáctico

Análisis Sintáctico y el Algoritmo CKY.

El algoritmo CKY clásico solo puede trabajar si la gramática está en la
Forma Normal de Chomsky (CNF)

A->a o A->BC
Sí, requiere obligatoriamente CNF.

Análisis Sintáctico y el Algoritmo CKY.

Él pinta un gato con un pincel

1. O -> Pron SV (0,1)

2. SN -> D N (0,1)

3. N -> N SP (0,02)
4. SP -> P SN (0,1)

5. SV -> V SN (0,7)

6. SV -> SV SP (0,3)

a. Pron → el (1,0)
b. V → pinta (0,6)
c. D → un (1,0)
d. N → gato (1,0)
e. P → con (1,0)
f. N → pincel (0,8)

Análisis Sintáctico y el Algoritmo CKY.

Análisis Sintáctico y el Algoritmo CKY.

1. La diagonal se ha rellenado con los valores de la Norma.

2. De izquierda a derecha, vamos de arriba a abajo.

3. Finalizando, nos queda el último bloque:

P[4,5] (1.0) <- [4,7] -> SN[5,7] (0.8) = SP(0.1) = 0.1x0.1x0.8 = SP(0.8)

Análisis Sintáctico y el Algoritmo CKY.

1. Siguiendo en la última columna (tiene 2 posibilidades):
V[1,2](0.6) <- [1,7] -> SN[2,7](0.016) = SV(0.7) = 0.6x0.7x0.016 =
0,00672

Análisis Sintáctico y el Algoritmo CKY.

Solución:

SP[4,7](0.08), SV[1,7](0.01008), O[0,7](0.01008)

Análisis Sintáctico y el Algoritmo CKY.

¿Presenta la solución ambigüedad sintáctica?

Sí, puesto que para la celda [1,7] había 2 posibilidades que generan 2
posibles árboles sintácticos.

Análisis Sintáctico y el Algoritmo CKY.

Genera el árbol

Bloque 3

Semántica Léxica, Desambiguación y Similitud.

1. Aplicar algoritmo de Lesk original

2. Construir un gráfico de tesauro calculando la similitud

Semántica Léxica, Desambiguación y Similitud.

Desambigüa LUNA en: La luna llena iluminaba la noche
• luna1: Astro que gira alrededor de la Tierra y que refleja la luz del sol,

apareciendo como un disco luminoso en el cielo nocturno.

• luna2: Lámina de cristal, vidrio u otra materia transparente, que se

emplea en ventanas, escaparates o parabrisas.

• lleno1: Que tiene su capacidad total de contenido o que está

completamente ocupado.

• noche1: Periodo de tiempo que transcurre desde el atardecer hasta el

amanecer, durante el cual la luz del sol no está presente.

• iluminar1: Hacer que algo sea visible mediante la proyección de luz

sobre ello.

Semántica Léxica, Desambiguación y Similitud.

Construir firmas eliminando stopwords:
• Firma(luna1): {astro, girar, tierra, reflejar, luz, sol, aparecer, disco,

luminoso, cielo, nocturno}.

• Firma(luna2): {lámina, cristal, vidrio, materia, transparente, emplear,

ventana, escaparate, parabrisas}.

• Firma(lleno1): {tener, capacidad, total, contenido, completamente,

ocupado}.

• Firma(iluminar1): {hacer, visible, mediante, proyección, luz}.
• Firma(noche1): {periodo, tiempo, transcurrir, atardecer, amanecer, luz,

sol, presente}.

Semántica Léxica, Desambiguación y Similitud.

Calcular solapamientos:
Comparación con la firma de luna1:
• Con lleno: 0 coincidencias.
• Con iluminar: 1 coincidencia -> la palabra "luz".
• Con noche: 2 coincidencias -> las palabras "luz" y "sol".
Comparación con la firma de luna2:
• Con lleno: 0 coincidencias.
• Con iluminar: 0 coincidencias.
• Con noche: 0 coincidencias.

Semántica Léxica, Desambiguación y Similitud.

Se usa la base de datos WordNet y debes construir el gráfico del tesauro
desde FLUID hasta WATER, CIDER y COLA.

Semántica Léxica, Desambiguación y Similitud.

1. Se utiliza la siguiente fórmula

Semántica Léxica, Desambiguación y Similitud.

1. De COLA a SOFT DRINK = 1 salto.

2. De SOFT DRINK a BEVERAGE = 2 saltos.

3. De BEVERAGE a FOOD = 3 saltos.

4. De FOOD a FLUID = 4 saltos.
5. De FLUID a LIQUID = 5 saltos.

6. De LIQUID a WATER = 6 saltos.

Semántica Léxica, Desambiguación y Similitud.

1. Aplicamos fórmula:

Pathlen = saltos + 1 = 6 saltos + 1 = 7

Simpath(cola, water) = 1/7 = 0,1428

*El +1 es porque en vez de contar 'saltos' así contamos nodos.

*El 1 numerador de la fórmula es para evitar dividir entre 0 (0/0) y para que a medida que las palabras

se alejan se vayan acercando a 0 (1/pathlen)

Bloque 4

Cálculo de TF-IDF

En un corpus de 500 documentos, la palabra "regalo" aparece en un total
de 12 documentos. Si en un documento específico la palabra "regalo"
aparece exactamente 6 veces , ¿cuál es el valor del TF-IDF para "regalo"
en ese documento?

Cálculo de TF-IDF

1. Aplicamos la fórmula

Cálculo de TF-IDF

1. Identificar TF (Term Frecuency)

o TF = 6

2. Identificar IDF (Inverse Document Frecuency)

o IDF(t) = log10 (500/12) = log10(41,6667)
o = 1,6197

3. Multiplicar TF x IDF

o TF-IDF = 6 x 1,6197 = 9,72

Cálculo de TF-IDF

TF-IDF = 6 x 1,6197 = 9,72
• Un valor TF-IDF alto indica que la palabra es muy relevante y

es un factor diferencial.

• Si la palabra apareciera en los 500 documentos, la fracción
sería 500/500 = 1, y log10(1) = 0, anularía su importancia. Al
aparecer solo 12 veces el modelo la premia porque ayuda a
clasificar.

Bloque 5

Modelado Neuronal y Word Embeddings

¿Por qué dejamos de usar One-Hot Enconding o Bag of Words?
• Alta dimensionalidad y dispersión: En One-Hot cada palabra necesita

su dimensión. Con 500.000 palabras el tamaño del vector
sería 500.000 lleno de 0s y un solo 1.

• Ortogonalidad estricta: Todos los vectores de One-Hot son

ortogonales, es decir, matemáticamente la distancia o el producto es
exactamente la misma. Entonces, el vector no contiene ninguna
información sobre el significado.

Modelado Neuronal y Word Embeddings

¿Diferencia One-Hot Enconding y Bag Of Words?
• One-Hot: es a nivel de palabra individual, se crea un vector con tantos

componentes como palabras totales y todos valen 0 menos la posición
de la palabra.

• Bag Of Words: es a nivel de documento/oración, se genera un único

vector del tamaño de todo el vocabulario (mete todas las palabras), e
ignora el orden y la estructura, solo cuenta términos.

Gato negro duerme junto al gato
• One-Hot: 5 vectores, Gato[100000] Negro[010000]…
• Bag Of Words: 1 vector, [11211]

Modelado Neuronal y Word Embeddings

La solución es Word2Vec, que proyectan palabras en un espacio continuo
y denso de baja dimensionalidad (normalmente 300 dimensiones).

Las palabras similares apuntan a direcciones parecidas en el espacio
geométrico, esto permite calcular similudes semánticas reales con
operaciones como similud de coseno.

Modelado Neuronal y Word Embeddings

¿Diferencia entre CBOW y Skip-Gram?

CBOW

Skip-Gram

Objetivo

Ejemplo

Predice la palabra objetivo a partir
de las palabras de contexto que la
rodean

Predice las palabras de contexto a partir de
una única palabra objetivo

Entrada: [La, ___, llena, iluminaba]
Salida: luna

Entrada: luna
Salida [La, llena, iluminaba]

Comportamiento

Rápido de entrenar y funciona bien
con palabras frecuentes

Funciona bien con corpus pequeños y
representa mejor palabras poco comunes

Modelado Neuronal y Word Embeddings

Bert y Transformers
• Supera Word2Vec: la palabra BANCO siempre tiene el mismo vector de

300 dimensiones, en BERT se resuelve generando embeddings
contextuales (dinámicos), el vector de una palabra cambia
dependiendo de en qué frase aparezca.

• Pre-entrenamiento con MLM: BERT se entrena de forma no supervisada
tapando palabras aleatorias y obligando a la red a adivinar qué palabra
iba usando el contexto de la izquierda y derecha a la vez.

• Softmax en Self-Attention: La función Softmax convierte los productos
escalares en un vector de probabilidad, qué porcentaje de atención
debe prestarle a cada palabra para entender su significado.

Bloque 6

Extracción de Significado y la Hipótesis Rule-to-Rule

En el análisis semántico dirigido por la sintaxis, las anotaciones
semánticas son instrucciones que especifican cómo generar la
representación del significado a partir de sus constituyentes
• Verdadero, no se puede desligar la estructura de la frase de

su significado.

• El principio de composición establece que el significado de
una oración completa se contruye por su significado por
partes.

• Rule-to-Rule: A cada regla del análisis sintáctico le

corresponde una regla equivalente en el análisis semántico.

Extracción de Significado y la Hipótesis Rule-to-Rule

A. Léxicas

B. Gramatiales de un constituyente

A. Gramatiales de más constituyentes

Extracción de Significado y la Hipótesis Rule-to-Rule

Evalúa el sistema Matías abrió un restaurante
{ⱻx Restaurante(x) ^ ⱻe Abierto(e) ^ PersonaQueAbre(e, Matías) ^
CosaAbierta(e,x)}
• Ventajas: Descarta ramas sintácticas válidas gramaticalmente pero sin

sentido semántico (evita análisis absurdos) y unifica dos procesos
pesados en un único cálculo matemático.

• Inconvenientes: Altamente ineficiente computacionalmente y las

reglas de anotación lambda son extremadamente complejas y costosas
de diseñar a mano para un idioma entero.

Bloque 7

Componentes de un Agente Conversacional

1. Reconocimiento Automático del Habla (ASR)

o Interacción por voz, transforma señal acústica a texto plano legible.
o Debe ser robusto a diferentes hablantes, ruidos de fondo, acentos.

2. Comprensión del Lenguaje Natural (NLU)
o Toma texto y extrae su significado semántico.
o La Intención (qué quiere hacer el usuario) y Las Entidades (variables necesarias

para ejecutar acción, como fecha=mañana).
3. Gestión del Diálogo (Dialogue Manager)

o Es el cerebro o subsistema coordinador. Mantiene memoria.
o Identifica la acción a realizar en el siguiente turno de palabra y conecta APIs

externas

Componentes de un Agente Conversacional

1. Generación de Respuestas (NLG) y Síntesis de Voz (TTS)

o NLG: convierte la decisión abstracta del gestor de diálogo en una frase

estructurada en lenguaje humano

o TTS: si el canal es hablado, este módulo toma el texto generado y lo convierte en

ondas de sonido.

Bloque 8

Modelado de Lenguaje Neuronal Avanzado (Redes
Recurrentes y Transformers)

¿Cómo podemos procesar una secuencia de tamaño variable con una red
neuronal de forma efectiva?
•

Las RNN procesan texto palabra por palabra, cada vez que se recibe
un embedding la red actualiza su estado oculto (hidden state) que
actúa como memoria de lo leído hasta ahora.

•

Las RNN tradiciones sufren desvanecimiento del gradiente (memoria a
corto plazo).

• Al procesar de forma secuencial presentan dificultades del

procesamiento en paralelo.

Modelado de Lenguaje Neuronal Avanzado (Redes
Recurrentes y Transformers)

La solución definitiva será Transformer
• Para superar problemas de lentitud y memoria de las RNN surge

Transformer (basado en modelos BERT) procesando la frase al mismo
tiempo en paralelo.

• Self-attention y Softmax: producto escalar entre los vectores para

medir afinidad y Softmax genera un vector de probabilidades de cada
elemento de entrada, diciendo matemáticamente el porcentaje de
atención semántico que prestar a cada palabra.

• Al procesar todo a la vez no se sabe qué palabra va antes que otra, por
lo que se añaden embeddings posicionales a cada embedding de
palabra antes de entrar a la red.

Bloque 9

Sistemas de Búsqueda de Respuestas (Question
Answering - QA)

• Factoid Questions vs. Preguntas Abiertas: Las factoid

questions buscan una respuesta directa, corta y concreta (un dato, una
fecha o un nombre). Las preguntas abiertas requieren explicaciones
complejas o resúmenes redactados.

• Relación con Information Retrieval (IR): No redactan una respuesta;
contestan las dudas del usuario buscando y extrayendo fragmentos o
listados de una colección de documentos previa.

• Uso de Transformers: Modelos basados en arquitecturas de

Transformer como BERT se utilizan muchísimo y son muy eficientes para
resolver tareas de QA extractivo.

Traducción Automática (Machine Translation)

• Arquitectura Encoder-Decoder: Los sistemas más avanzados de

traducción ya no usan reglas fijas ni diccionarios palabra por palabra.
Utilizan redes neuronales profundas (como RNN o Transformers) con
una estructura de Codificador-Decodificador (Encoder-Decoder).
• Contexto Global: Un buen sistema de traducción automática nunca
traduce los términos de forma aislada, sino que analiza el contexto
general y completo de la frase para evitar errores de sentido.

• Divergencia Léxica: Las diferencias estructurales y de vocabulario

entre idiomas (divergencias léxicas) son uno de los retos más relevantes
y difíciles de resolver dentro del campo de la Traducción Automática.

Análisis de Sentimiento (Sentiment Analysis)

• Objetivo de la tarea: Consiste en determinar y clasificar de manera

automática la polaridad emocional asociada a un texto (identificar si es
positivo, negativo o neutro).

• Diferencia con el significado: No debes confundirlo con el análisis

semántico tradicional. El análisis de sentimiento busca la carga afectiva
o la opinión del emisor, mientras que el semántico tradicional compone
el sentido lógico y estricto de la oración usando el principio de
composicionalidad.

Bloque 10
Repaso

Repaso

• NLP: interacción entre computadoras y lenguaje humano.
• 3 niveles de aplicación NLP:

o Processing [POS tagging, Semantic Role labeling, NER]
o Understanding [Q&A, Text similarity]
o Generation [Summarization, Translation]
o ⭢ Sentimental Analysis, Conversational Agents

This    is     the     way
det    verb  det   noun
tema relación atributo

no hay NER

• Morfología: estudiar las palabras (raíz, prefijo, flexión).
• Sintáxis: relación entre palabras para formar frases y oraciones.
• Semántica: significado de las palabras, frases y oraciones.
• Pragmática: intención de las palabras.
• Discurso: estructuración de varias oraciones.

Repaso

• Historia:

o Métodos formales: lenguaje descrito con reglas gramaticales (oración = sujeto +

verbo).

▪ Muy preciso para casos simples
▪ No escala y el lenguaje real es más complejo

o Métodos probabilísticos: lenguaje incierto, uso de probabilidad (estadística,

frecuencia de palabras).

▪ Mejora con el lenguaje real
▪ Es limitado; no entiende significado profundo

o Machine Learning: la máquina aprende sola a partir de datos (RNN, Deep learning,

Transformers).

▪ Más potente, capta contexto y significado
▪ Necesita muchos datos y computación

Repaso

• Principio de composición: el significado de una oración es el

significado de las palabras que lo contiene. Y la de la palabra es la
información de sus morfemas.

• Aspecto secuencial: el orden de las palabras importa.
• Perspectiva distribucional: el significado de un texto depende de las

palabras que lo rodean.

Repaso

Palabra CANTÁBAIS, VINO, VINO

Lexema/morfema léxico: raíz ⭢ [Cant], [Vino], [Vin]

Morfema gramatical: género, número, tiempo ⭢ [ába, is], [0,0], [o,0]
Lema: unidad autónoma ⭢ [Cantar], [Vino], [Venir]

Repaso

La pipeline de Normalización

• Tokenización ⭢  ["Clark", "Kent", "está", "en", "la", "cabina"]
• Borrar StopWords ⭢  ["Clark", "Kent", "está", "cabina"]
• NER ⭢  ["Clark Kent", "está", "cabina"]
• Mayúsculas y minúsculas ⭢  ["clark_kent", "está", "cabina"]
• Lematización ⭢  ["clark_kent", "estar", "cabina"]

Repaso

• Diccionario:  recoge lemas y definiciones
• Tesauros: recoge lema y sus relaciones (sinónimos y antónimos).

Como Wordnet.

• Treebank: conjunto de etiquetas normalizadas. Como Penn Treebank o

Eagles en español.

Repaso

• Propiedad de Markov:  solo debo tener en cuenta n para predecir n+1.
• Proceso de Markov: secuencia de observaciones que cada una

cumple La Propiedad de Markov.

• Modelo oculto de Markov: modelo para predecir valores

desconocidos.

Entonces, la etiqueta depende de la etiqueta anterior y la palabra de su
propia etiqueta.

Repaso

• Valor IOB de token: valor de INSIDE, OUTSIDE y BEGINNING; en el

token LA_MANCHA los valores son:
o I: A_MANCH
o O: A
o B: L

Repaso

• Vocabulario terminal: palabras. Nodos hoja.
• Vocabulario no terminal: sintagmas (nombres de los grupos de

palabras). Nodos intermedios.

• Raíz: oración.
• Gramática Libre de Contexto: izquierda No Terminal y derecha >= 0

Terminal o No Terminal. A ⭢ a, A ⭢ BC

• Forma normal de Chomsky: sus reglas son un No Terminal se asocia

con un Terminal o 1 No Terminal se asocia con 2 No Terminales.
• Transformar en Chomsky: cualquier gramática libre de contexto se

puede transformar. Se usa el algoritmo CKY.

Repaso

• Lógica descriptiva: simplificación de la Lógica de Primer Orden.
• Axioma: frases que son verdad.
• Formalismos de Lógica descriptiva: ALC y derivados; OWL, Web

Semántica (DBpedia).

• Ontología: representación del conocimiento experto con formalismo

para tratarlo computacionalmente.
• Operaciones de Lógica descriptiva:

o Clasificación: un componente pertenece a una categoría.
o Subsunción: una categoría es subconjunto de otra categoría.

Repaso

• Rule-to-rule: cada regla POS Tagging tiene su implicación semántica.

Se construye sobre gramáticas Libres de Contexto.

• Se va sustituyendo según las reglas:

NO entra en el
examen hacerlo

Repaso

• Semántica léxica: estudio significado de palabras y sus relaciones.
• Colocación de una palabra: si n=3, significa que cogemos las 3

anteriores y 3 posteriores. Con o sin stopwords si se indica. Esto nos da
el contexto de la palabra (las palabras de alrededor).

Repaso

• Algoritmo de Lesk: suma frecuencias mediante descripciones de lemas. Se

necesita un diccionario.

• Schütze: hace un cluster para cada sentido. Usa k-means, k grupos óptimos.
Se deshace del diccionario y busca solapamientos con corpus. Por ejemplo:

o Tengo 5 libros con 300 ocurrencias de BANCO.
o Para esas 300 ocurrencias hago 300 colocaciones que representan BANCO.
o Lo hago con BOW y consigo sus 300  contextos (vectores).
o Divido en k-means grupos (k=3, por ejemplo).
o Calculo el centroide de cada grupo, obteniendo un vector concreto que representa

cada grupo.

o Si existiera una nueva palabra (debe tener contexto), se saca su colocación, BOW, y

se compara con los centroides, calculando su distancia/similitud.

Repaso

• Algoritmo de Lesk: basado en conocimiento.
• Schütze: basado en métodos vectoriales.
• Holónimo y merónimo: son relaciones encontradas en WordNet, un

holónimo es el todo y un merónimo es una parte.

o Un equipo contiene jugadores ⭢ equipo holónimo, jugador merónimo.

• Hipónimo e hiperónimo: son relaciones encontradas en WordNet, un

hiperónimo es general y un hipónimo es específico.

o Fruta y fresa ⭢ fruta hiperónimo, fresa hipónimo.
• Metonimia: uso de una palabra en lugar de otra.

Repaso

• Similitud entre sentidos de palabra: en one-hot-encoding los

vectores son ortogonales (misma distancia entre sí) y además no
guardan relación entre palabras (es aleatorio), entonces:

o Similitud va de entre 1 y –1, siendo 0 ninguna similitud.

• Métodos: para calcular similitudes se calcula igual, la diferencia radica

en como hacemos los vectores.

• Método mediante tesauro: sim path = 1 / pathlen(c1,c2).
• Método mediante estadística: similitud de coseno a centroides de

palabras.

Repaso

• N-grama: token es palabra suelta y n-grama es n tokens.

o "want" = o contar fila o columna (da diferente porque está truncada)
o "want to" = 608

Repaso

En este caso, no es posible saberlo, puesto que necesitas saber
apariciones. Si usas la regla de la cadena, tienes probabilidades.

Repaso

Pero la usamos para el principio: P(I) x P(want|I).

Y seguimos con la Hipótesis de Markov: la probabilidad de un suceso
depende el último elemento.

Repaso

• N-grama: el problema que surge con estos modelos es que si no existe
el n-grama, no existe la probabilidad, y eso no es cierto. Por lo que hay
que suavizarlos:
o Técnica de Laplace / add-k

▪ En todas las celdas se sumará +1 (Laplace) o k (add-k).
▪ A cambio en los valores pequeños se altera bastante el valor original.

o Backoff e Interpolación

▪ Backoff: utilizo el n-grama más pequeño que me dé distinto de 0, hasta llegar a la propia palabra

si hace falta.

▪ Interpolación: se combinan (suman) los n-gramas de menor orden.

Repaso

• Evaluación del modelo

o Extrínseca: en la aplicación final se mide precision, recall, etc.
o Intrínseca: se usa la métrica de perplejidad, cómo responde el modelo con n-

gramas nuevos. Cuanto menor perplejidad mejor es el modelo.

Repaso

De n-gramas pasamos a modelado de lenguaje vectorial; pasamos del
One-Hot-Enconding (por palabra) al BOW (todo el texto).
• BOW TF-iDF: es un tipo de BOW que no solo indica cuántas veces

aparece una palabra sino si es relevante. Esto lo hace viendo cómo de
común o rara es la palabra de entre todos los textos y las pondera.

Repaso

• Función de activación:

o Sigmoide: clasificador 0/1
o ReLU: capas ocultas
o Softmax: mulitclase 0/1

Repaso

• Entradas y salidas:

o 1 entrada neurona entrada
o 1 salida neurona entrada valor sigmoide
o 3 entradas/pesos neurona oculta
o 1 sesgo neurona oculta
o 4 pesos neurona salida
o 1 sesgo neurona salida
o 1 salida neurona salida
o 2 salidas red neuronal

Se pueden procesar vectores de 3 dimensiones
Se entrena 1 sesgo por neurona
Se calculan tantos pesos como entradas por neurona

Repaso

• Autoencoder: número de entradas igual que de salidas.
• Word2Vec: sistema que crea embeddings (se basa en la idea de

'compresión' de autoencoder).
o CBOW: entrada es la colocación de la palabra SIN la palabra y el sistema debe

adivinar el One-Hot-Encondig de la palabra que falta.

o La gracia no es adivinar la palabra, sino que la red comprende el lenguaje tras

mucho entrenamiento.

Repaso

• Word2Vec

o Vectores de dimensión 300
o Sin dispersión
o Posición del vector relacionado con el significado
o Se auto-etiqueta (quitas una palabra y es el resultado)

Repaso

• FastText: usa tokens menores ya que en redes sociales no se escribe

tan formal y puede reconstruir palabras

• SkipGram: modelo de Word2Vec que predice contexto a partir de una

palabra (lo contrario a CBOW).

Repaso

• Red recurrente: permite procesar secuencias. La red neuronal simple
produce un 0 o 1. Aquí producimos un vector con las dimensiones de la
entrada.

Repaso

• Sequence to Sequence: una red recurrente es la entrada a otra. Y esta

arquitectura genera a para una secuencia, otra.

Repaso

• Sequence to Sequence tiene el problema de que las primeras

palabras tienen poca influencia en las últimas, entonces se introducen
las redes LSTM.

• Redes LSTM: es una red recurrente que se realimenta con 2 valores: la
salida (como antes) y forget key (vector ponderado de importancia).
o LSTM bidireccional: procesan la secuencia de izquierda a derecha y viceversa.

Concatena ambos resultados (vector 600d). Así se entrenó ELMO.

• ELMO: basado en LSTM bidireccional usa embeddings para contexto
(más que significado). Por ejemplo, el embedding de la palabra VINO
en una oración concreta.

• Embedding contextual: convertir significados en vectores, una misma
palabra produce diferentes embeddings dependiendo quién las rodea.

Repaso

• Entrenar ELMO: en Word2Vec intentábamos adivinar una palabra de
una ventana, aquí se entró con BiLM; una red que van de izquierda a
derecha y otra al revés e intentan adivinar la palabra del final y la del
principio.

o Con esto, conseguimos construir embeddings.

Repaso

• Transformers

o Atención: compuesto por vector key (la palabra actual) y vector query (búsqueda
de palabras que encajan con la actual). Calculamos los pesos de atención en
paralelo, no necesitamos ir en orden.

o Embedding posicional: ubicación de la palabra dentro de la secuencia.

Repaso

• BERT: primer modelo pre-entrenado con Transformer.
o Nos genera embeddings contextuales (como ELMO)
o Es entrenable para múltiples tareas (como Sec2Sec)

• Entrenar BERT

o Masked LM (MLM): toma un vector de n palabras, elimina 2

aleatoriamente y trata de adivinar esas 2 (más ambicioso queWord2Vec).

o Next Sentence Prediction (NSP): toma dos oraciones, elimina la segunda y trata

de adivinar la segunda oración.

Repaso

• Pre entrenamiento
o Semi-supervisado
o General
o Grandes corpus

• Fine Tunning
o Supervisado
o Concreto
o Corpus específico

Repaso

• Entrenar GPT, Llama o DeepSeek

o CLM (Causal Language Modeling): adivinan la siguiente palabra.

Repaso

• Few/One/Zero shot learning: cuántos ejemplos necesita mi modelo. Es

prompting.

• Modelos Instruct: entienden la tarea y sus respuestas son sobre ella. La
diferencia es que no sólo rellena texto (adivina siguiente palabra). Es un
modelo hecho sobre uno base y fine-tunneado.

• Large Reasoning Models (LRM): modelo base/instruct + fine tunning. Su

tarea es desglosar los apartados y resolverlos paso por paso. Se entrenan por
aprendizaje por refuerzo.

• Fine-tunning vs prompting: fine-tunning cambia pesos y sería para long

term. Prompting da contexto y sería una solución temporal.

• RAG: usa contextos específicos de bases de datos vectoriales, utilizando un

búscador. Sobretodo utilizado en Q&A.