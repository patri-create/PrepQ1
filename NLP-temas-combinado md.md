Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Bloque I - Tema 1 - Introducción

Problema del día

► ¿Qué características concretas debe tener una IA para

considerarse Procesamiento de Lenguaje Natural?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

Encuesta previa

► Nombra una herramienta que conozcas que usa PLN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

Encuesta previa

► Nombra una tarea que conozcas que se realiza con PLN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

En el día de hoy

► Definición de Procesamiento de Lenguaje Natural

► Aplicaciones de PLN

► Lingüística y PLN

► Historia del Procesamiento de Lenguaje Natural

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

5

Definición de Procesamiento de Lenguaje Natural

Natural language processing strives to build machines that understand and
respond to text or voice data—and respond with text or speech of their own—in
much the same way humans do. (IBM).

El procesamiento de lenguaje natural es un campo de las ciencias de la
computación, de la inteligencia artificial y de la lingüística que estudia las
interacciones entre las computadoras y el lenguaje humano. (Wikipedia)

Campo de la Inteligencia Artificial que tiene como objetivo principal hacer que las
máquinas sean capaces de realizar tareas que involucren el lenguaje humano
(Apuntes de la asignatura)

El Procesamiento de Lenguaje Natural (PLN) es una rama de la inteligencia
artificial que se enfoca en la interacción entre las computadoras y el lenguaje
humano. Su objetivo es permitir que las máquinas comprendan, interpreten,
generen y respondan al lenguaje de manera similar a los humanos. (ChatGPT)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

6

Aplicaciones de PLN

► Language Modeling
► Named Entity Recognition
► Análisis Morfológico
► Análisis Morfosintáctico (POS Tag)
► Análisis Sintáctico
► Word Sense Disambiguation
► Information Retrieval
► Question Answering
► Resumen Automático
► Traducción Automática
► Generación de Textos
► Speech Recognition
► Speech Generation
► Sistemas de Diálogo

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

Aplicaciones de PLN

► Language Modeling
► Named Entity Recognition
► Análisis Morfológico
► Análisis Morfosintáctico (POS Tag)
► Análisis Sintáctico
► Word Sense Disambiguation
► Information Retrieval
► Question Answering
► Resumen Automático
► Traducción Automática
► Generación de Textos
► Speech Recognition
► Speech Generation
► Sistemas de Diálogo

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

8

Aplicaciones de PLN

Natural
Language
Processing

Natural
Language
Understanding

Natural
Language
Generation

Pos tagging

Semantic
Role labeling

Named Entity
Recognition

Question
Answering

Sumarization

Text similarity

Translation

Sentiment Analysis

Conversational Agents

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

9

Lingüística y PLN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

10

Historia del Procesamiento de Lenguaje Natural

1940

1950

1957

1970

1970

1983

1983

1993

1993

1999

2000

2016

2016…

Automatas
Modelos prob.

Simbólico
Estocástico

Estados finitos
Empirismo

Empirismo

Estocástico
Lógica
Comprensión
Discurso

Aprendizaje
automático

Redes
neuronales

Deep Learning

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

11

Historia del Procesamiento de Lenguaje Natural

1940

1950

1957

1970

1970

1983

1983

1993

1993

1999

2000

2016

2016…

Automatas
Modelos prob.

Simbólico
Estocástico

Estados finitos
Empirismo

Empirismo

Estocástico
Lógica
Comprensión
Discurso

Aprendizaje
automático

Redes
neuronales

Deep Learning

Métodos Formales

Métodos Probabilísticos

Machine Learning

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

12

Métodos formales

– Teoría de lenguajes formales:

• Un lenguaje L es un conjunto, finito o infinito de

secuencias s

• Un vocabulario V es el conjunto de símbolos disponibles

en el lenguaje

• Una secuencia s es una concatenación de símbolos de V
• Una gramática G es una definición formal de L: establece

qué combinaciones de V forman secuencias s válidas en L
y cuáles no

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

13

Métodos formales

– Teoría de autómatas:

• Definición de lenguajes formales equivalente

• Mediante máquinas abstractas

• Formadas por un conjunto de estados S y una función de

transición T que define transiciones de un estado a otro en
función de los símbolos de una cadena de entrada

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

14

Métodos formales

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

15

Métodos formales

– ¿Puede el lenguaje natural formalizarse como un lenguaje
formal L, mediante una gramática G, o como un autómata?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

16

Métodos probabilísticos

► N-gramas

► Cálculo de probabilidades

► Cadenas de Markov (Hidden Markov Models o HMM)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

17

Métodos probabilísticos

► N-gramas

“por favor, por favor, no olvidemos que por este camino ya hemos
pasado antes”

(por favor) 2

(favor ,) 2

(, por) 1

…

(por este) 1

(este camino) 1

…

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

18

Métodos probabilísticos

► Cálculo de probabilidades de N-gramas

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

19

Métodos probabilísticos

► #ocurrencias por favor en el corpus: 2

► #ocurrencias por este en el corpus: 1

► #ocurrencias por en el corpus: 3

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

20

Métodos probabilísticos

► Autómatas con probabilidades de transición

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

21

Métodos computacionales

► Machine Learning / Deep Learning

► Aprendizaje supervisado

► Proliferación de datos. Internet, redes sociales

► Soluciones de hardware: cloud, GPU, TPU

► Permiten modelar patrones demasiado complejos para

formalizarlos explícitamente

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

22

Historia del PLN: aprendizaje automático

► Deep Learning

► Redes recurrentes: RNN, LSTM

► También convolucionales: CNN

► Transformadores: BERT

► Transfer Learning

► GAN aplicado a PLN

► LLM

► RAG

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

23

En resumen

► Aplicaciones de PLN

– NLP (etiquetado),
– NLU (question answering)
– NLG (text generation)

► Lingüística y PLN

– Morfología, sintaxis, semántica, pragmática, discurso
– Fonética

► Historia del Procesamiento de Lenguaje Natural

– Modelos formales
– Modelos probabilísticos
– Modelos basados en Machine Learning

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

24

En la próxima sesión

► ¿Cómo convertir el texto en una entrada válida para técnicas de

IA?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

25

www.unir.net

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 2 – El texto como dato

Encuesta previa

► ¿Tienes instalado Jupyter? / ¿Sabes usar Google Colab?

► ¿Sabes qué es un corpus lingüístico?

► ¿Sabes la diferencia entre lema y lexema?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

Problema del día

► ¿Cómo convertir el texto en una entrada válida para

técnicas de IA computacionales?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

Índice

► Principios conceptuales

► Morfología

► El pipeline de normalización

► Recursos

► Herramientas y librerías

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

Principios conceptuales

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

5

Principios conceptuales

► Idea principal

– La estructura del lenguaje natural es demasiado compleja

► Solución

– Simplificar los textos de forma sistemática

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

6

Principios conceptuales

► Simplificamos en base a tres principios:

– Principio de composición

– Aspecto secuencial

– Perspectiva distribucional

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

Principio de composición

A nivel de oración:

El significado de una oración se construye como

composición del significado de las palabras que contiene

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

8

Principio de composición

A nivel de oración:

El significado de una oración se construye como

composición del significado de las palabras que contiene

A nivel de palabra:

La información de una palabra se construye como

composición de la información que aportan sus morfemas

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

9

Aspecto secuencial

El orden en el que aparecen las palabras importa en la

construcción del significado de una oración

“Un hombre pobre”

“Al campo no he ido, he ido a la playa”

Vs

Vs

“Un pobre hombre”

“A la playa no he ido, he ido al campo”

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

10

Perspectiva distribucional

El significado de una palabra en un texto depende de las

palabras que la rodean

► Resulta útil en la solución de ambigüedades

– … fue al banco a contratar una hipoteca.
– … en el mar pude ver un banco de peces rojos.
– … ellos se sentaron en un banco de madera.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

11

Morfología

Principio composicional aplicado a palabras

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

12

Morfología de las palabras

► Morfemas :

– Lexema / morfema léxico: raíz de la palabra con significado

léxico

– Morfema gramatical: significado gramatical - género, número,

tiempo, etc.
• Morfema cero: marca gramatical sin marca fonética (ej.

mujer)

– Lema: unidad autónoma con el significado léxico raíz de la

palabra

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

13

Morfología de las palabras

► Ejemplos

Palabra

Lexema

Morfema
gramatical

Morfema
gramatical

Cantábais

Cant

Casita

Cas

Perros

Vino

Vino

Perr

Vino

Vin

ába

Ita

O

Morfema
cero (M)

o

Is

Morfema
cero (SG)

S

Morfema
cero (SG)

Morfema
cero (SG)

Lema

Cantar

Casa

Perro

Vino

Venir

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

14

Morfología de las palabras

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

15

(Inciso)
Uso de Jupyter Notebooks
Y
Google Colab

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

16

El pipeline de normalización

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

17

Problema a resolver

► ¿Cómo construir una nube de palabras?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

18

Pipeline

► Tokenización

► Borrado de StopWords

► NER

► Mayúsculas y minúsculas

► Lematización

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

19

Pipeline (detalle)

► Tokenización

– “En un lugar de La Mancha, de cuyo nombre no quiero acordarme”

– [ “En”, “un”, “lugar”, “de”, “La”, “Mancha”, “, “, “de”, “cuyo”, “nombre”,

“no”, “quiero”, “acordarme” ]

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

20

Pipeline (detalle)

► Borrado de stopwords

– [ “En”, “un”, “lugar”, “de”, “La”, “Mancha”, “de”, “cuyo”, “nombre”, “no”, “quiero”,

“acordarme” ]

– [ “lugar”, “Mancha”, “,”, “cuyo”, “nombre” , “quiero”, “acordarme” ]

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

21

Pipeline (detalle)

► NER

– [ “En”, “un”, “lugar”, “de”, “La”, “Mancha”, “de”, “cuyo”,

“nombre”, “no”, “quiero”, “acordarme” ]

– [ “En”, “un”, “lugar”, “de”, “La_Mancha”, “de”, “cuyo”, “nombre”,

“no”, “quiero”, “acordarme” ]

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

22

Pipeline (detalle)

► Mayúsculas / minúsculas

– [ “lugar”, “Mancha”, “cuyo”, “nombre , “quiero”, “acordarme” ]

– [ “lugar”, “mancha”, “cuyo”, “nombre , “quiero”, “acordarme” ]

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

23

Pipeline (detalle)

► Lematización

– [ “lugar”, “mancha”, “cuyo”, “nombre , “quiero”, “acordarme” ]

– [ “lugar”, “mancha”, “cuyo”, “nombre , “querer”, “acordar yo” ]

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

24

Pregunta

► Sabes qué son:

– Lema

– Lexema

– Lemma

– Lexeme

– Stem

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

25

Problema a resolver

► Nube de palabras: ¿qué efectos tendría

añadir/quitar/cambiar el orden de estas etapas?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

26

Recursos

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

27

Recursos lingüísticos disponibles

► Diccionarios

► Tesauros

► Lexicones

► Bases de datos lingüísticas

► Corpus

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

28

Diccionarios, Tesauros, Lexicones

► Diccionarios

– RAE, Linguee, WordReference, TheFreeDictionary…

– https://pypi.org/project/pyrae/

– https://github.com/squat/drae

► Tesauros

– TheFreeDictionary

► Lexicones

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

29

Bases de datos lingüísticas

► WordNet (https://wordnet.princeton.edu/ )

► Spanish WordNet 3.0 (http://timm.ujaen.es/recursos/spanish-

wordnet-3-0/ )

► FrameNet (https://framenet.icsi.berkeley.edu/fndrupal/ )

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

30

Corpus

► Un corpus es un conjunto de textos, que puede estar o no

etiquetado, que se utiliza para tareas de procesamiento de leguaje

natural

► Corpus de NLTK (https://www.nltk.org/nltk_data/ )

► https://www.kaggle.com/datasets?tags=13204-NLP

► POS (https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1827 )

► NER-C (https://www.kaggle.com/datasets/nltkdata/conll-corpora )

► MLDoc (https://github.com/facebookresearch/MLDoc )

► PAWS-X (https://github.com/google-research-datasets/paws/tree/master/pawsx )

► XNLI (https://github.com/facebookresearch/XNLI )

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

31

Herramientas y librerías

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

32

Herramientas y librerías

► NLTK

– https://www.nltk.org

► Spacy

– https://spacy.io

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

33

Para cerrar

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

34

Conceptos principales de esta sesión

► Normalizar es necesario para poder procesar

► El pipeline de normalización

– Tokenizar -> quitar stopwords -> lematizar

► Recursos

– Importante que sea posible acceder programáticamente
– Corpus y Tesauros

► Herramientas y librerías

– Spacy

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

35

En la próxima sesión

► ¿Cómo identificar la función de una palabra en una oración con

técnicas estadísticas?

– Y más concretamente:

¿Cómo construir tablas de transición y emisión?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

36

www.unir.net

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 3 – Etiquetado Morfosintáctico
(POS Tagging)

Encuesta previa

► ¿Sabes qué es un corpus lingüístico?

► ¿Sabes qué es un Modelo de Markov?

► ¿Has abierto ya un notebook con algo de código para NLP?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

Problema del día

¿Cómo construir tablas de transición y emisión?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

En el día de hoy

► Definición de moforsintaxis

► Categorías morfosintácticas

► Hidden Markov Models para POS tagging

► Probabilidad de transición / Probabilidad de emisión

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

Morfosintaxis / POS Tagging

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

5

Morfosintaxis / POS Tagging

► La morfosintaxis es un subcampo de la gramática que tiene como
objetivo el estudio de la formación de las palabras y las relaciones
de éstas para conformar frases u oraciones coherentes, es decir,
con sentido lógico. (https://conceptodefinicion.de/morfosintaxis/ )

► Parte de la gramática que integra la morfología y la sintaxis para
identificar las partes de una oración (apuntes de la asignatura)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

6

Morfosintaxis / POS Tagging

► Part of Speech:

– In grammar, a part of speech or part-of-speech (abbreviated as

POS or PoS, also known as word class or grammatical
category) is a category of words (or, more generally, of lexical
items) that have similar grammatical properties. (Wikipedia)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

Categorías Morfosintácticas

Las categorías gramaticales variables

– Sustantivos
– Pronombres
– Determinantes
– Adjetivos
– Verbos

Las categorías gramaticales invariables

– Adverbios
– Preposiciones
– Conjunciones
– Interjecciones

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

8

Categorías Morfosintácticas

Sustantivos

– Poseen género y número (morfología)

– Forman sintagmas nominales (sintaxis)

– Designan entidades de diferente naturaleza (semántica)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

9

Categorías Morfosintácticas

Pronombres

– Sustituyen a los sustantivos y cumplen las mismas funciones

– Su significado concreto depende del contexto (p.ej. “ellos”)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

10

Categorías Morfosintácticas

Determinantes

– Acompañan al sustantivo para precisar su significado

• El coche
• Un coche
• Ningún coche
• Ese coche

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

11

Categorías Morfosintácticas

Verbos

– Expresa una acción

– Es el núcleo del predicado

– Debe concordar en género y número con el sujeto

– Tiene variación de persona, número, tiempo, modo y aspecto

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

12

Etiquetado moforsintáctico

Bebo un vaso del vino tinto

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

13

Etiquetado moforsintáctico

Bebo un vaso del vino tinto

POS tagging informal

Bebo(verbo) un(determinante) vaso(sustantivo) de(preposición) el(determinante)

vino(sustantivo) tinto(adjetivo)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

14

Etiquetado moforsintáctico

► Penn Treebank

– Conjunto de etiquetas

normalizadas

– Diseñado para idioma

inglés

– https://gist.github.com
/nlothian/9240750

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

15

Etiquetado moforsintáctico

Bebo un vaso del vino tinto

POS tagging informal

Bebo(verbo) un(determinante) vaso(sustantivo) de(preposición) el(determinante)

vino(sustantivo) tinto(adjetivo)

POS tagging con Penn Treebank

Bebo/VBP un/DT vaso/NN de/IN el/DT vino/NN tinto/JJ

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

16

Etiquetado moforsintáctico

► Alternativas al Penn Treebank

– EAGLES (https://www.cs.upc.edu/~nlp/tools/parole-sp.html )

Talamé, L., Cardoso, A., & Amor, M. (2019). Comparación de herramientas
de procesamiento de textos en español extraídos de una red social para
Python. In XX Simposio Argentino de Inteligencia Artificial (ASAI 2019)-
JAIIO 48 (Salta).

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

17

Etiquetado moforsintáctico

► Demo con Spacy y NLTK

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

18

Hidden Markov Models para POS Tagging

► Modelo oculto de Markov (HMM)

– Un modelo oculto de Markov es un modelo estadístico que se
puede representar como una máquina de estados finitos,
pero donde las transiciones entre estados son
probabilísticas y no determinísticas

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

19

Hidden Markov Models para POS Tagging

► Propiedad de Markov

– la distribución de probabilidad del valor futuro de una variable
aleatoria depende únicamente de su valor presente, siendo
independiente de la historia de dicha variable.

► Proceso de Markov

– Secuencia de observaciones en las que cada observación

cumple la propiedad de Markov

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

20

Hidden Markov Models para POS Tagging

► Propiedad de Markov

– la distribución de probabilidad del valor futuro de una variable
aleatoria depende únicamente de su valor presente, siendo
independiente de la historia de dicha variable.

► Proceso de Markov

– Secuencia de observaciones en las que cada observación

cumple la propiedad de Markov

¿Es una oración un proceso de Markov?
Es decir, ¿se cumple la propiedad de Markov?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

21

Hidden Markov Models para POS Tagging

► Modelo oculto de Markov

– Modelo estadístico para determinar valores desconocidos
(ocultos) a partir de valores observables en un proceso de
Markov

Bebo/VBP un/DT vaso/NN de/IN el/DT vino/NN tinto/JJ

Parte
Observable

Parte Oculta

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

22

Probabilidad de transición y de emisión

► Un HMM se compone de:

► Conjunto de estados (POS tags)

► Conjunto de observaciones (palabras | tags)

► Matriz de probabilidades de transición

► Matriz de probabilidades de emisión

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

23

Probabilidad de transición

► Las probabilidades de transición de etiqueta 𝑃(𝑡𝑖|𝑡𝑖−1) representan

la probabilidad de una etiqueta dada la etiqueta anterior.

► Matriz de probabilidades de transición

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

24

Probabilidad de transición

► Las probabilidades de transición de etiqueta 𝑃(𝑡𝑖|𝑡𝑖−1) representan

la probabilidad de una etiqueta dada la etiqueta anterior.

► Matriz de probabilidades de transición

Se calcula a partir de un corpus de trabajo, y por tanto los valores dependen de dicho corpus

En la matriz aparecen los posibles estados, y es completamente independiente de la oración observada

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

25

Probabilidad de emisión

► Es probabilidad de que, dada una etiqueta, esta se asocie con una

palabra concreta

► Matriz de probabilidades de emisión

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

26

Probabilidad de emisión

► Es probabilidad de que, dada una etiqueta, esta se asocie con una

palabra concreta

► Matriz de probabilidades de emisión

Se calcula a partir de un corpus de trabajo, y por tanto los valores dependen de dicho corpus

En la matriz aparecen los posibles estados y las palabras observadas.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

27

En resumen

► Etiquetado morfosintáctico o POS tagging

– Asignar a cada palabra su categoría gramatical, de acuerdo al

contexto concreto de la oración observada

► Hidden Markov Models para POS tagging

– Modelo probabilístico en el que vamos a basar los algoritmos POS

tagging

– Requiere asumir cosas que no son del todo ciertas

► Probabilidad de transición / Probabilidad de emisión

– Transición: dado un estado, probabilidad de cambiar a otro
– Emisión: dado un estado observado, probabilidad de una observación

concreta

– Se calculan para un corpus dado

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

28

En la próxima sesión

¿Cómo identificar la función de una palabra en una oración con

técnicas estadísticas?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

29

www.unir.net

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 3 – Etiquetado Morfosintáctico
(POS Tagging)

Problema del día

¿Cómo identificar la función de una palabra en una oración con

técnicas estadísticas?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

Encuesta previa

► ¿Sabes enunciar la definición de probabilidad de transición?

► ¿Sabes enunciar la definición de probabilidad de emisión?

► ¿En cuál de las dos influye el corpus lingüístico con el que se

trabaja?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

En el día de hoy

► Repaso de la sesión anterior

► Algoritmo de Viterbi

► Etiquetado basado en Machine Learning

► Named-Entity Recognition

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

Repaso

► Nuestro objetivo: POS tagging

► Nuestro modelo: Hidden Markov Models

► Nuestros ingredientes:

– Un conjunto de estados posibles (etiquetas)
– Una observación (oración a etiquetar)
– Matriz de probabilidades de transición
– Matriz de probabilidades de emisión

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

5

Repaso

► Cosas que hemos asumido como ciertas:

– La probabilidad de aparición de una palabra depende solo de
su propia etiqueta y es independiente de las palabras y
etiquetas vecinas.

– La probabilidad de una etiqueta solo depende de la etiqueta

anterior, en lugar de toda la secuencia de etiquetas

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Repaso

► Cosas que hemos asumido como ciertas:

– La probabilidad de aparición de una palabra depende solo de
su propia etiqueta y es independiente de las palabras y
etiquetas vecinas.

– La probabilidad de una etiqueta solo depende de la etiqueta

anterior, en lugar de toda la secuencia de etiquetas

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

Algoritmo de Viterbi: objetivo

► ¿Cuáles son las categorías gramaticales de cada palabra en la

siguiente oración?

El señor vino tarde

Otra formulación, más ajustada a la computación:

► ¿Cuál es la secuencia de etiquetas más probable para la

secuencia de palabras observada?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

8

Algoritmo de Viterbi: observación

► El

► Señor

► Vino

► Tarde

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

9

Algoritmo de Viterbi: conjunto de etiquetas

► El

– Artículo Determinado

► Señor

– Sustantivo común
– Sustantivo propio
– Adjetivo

► Vino

– Sustantivo común
– Verbo

► Tarde

– Sustantivo común
– Adverbio
– Verbo

– Artículo Determinado
– Sustantivo común
– Sustantivo propio
– Adjetivo
– Verbo
– Adverbio

– DT
– NN
– NNP
– JJ
– VBD
– RB

https://www.buscapalabra.com/categoria-gramatical-
tiempo-verbal.html

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

10

Algoritmo de Viterbi:
matriz de probabilidad de transición

Valores del WSJ Corpus

DT

NN

NNP

JJ

VBD

RB

DT

NN

0,0017

0,4744

0,1147

0,2157

0,0002

0,0102

0,0068

0,1216

0,0096

0,0086

0,0314

0,0177

NNP

0,0025

0,0584

0,3777

0,0084

0,0009

0,0090

JJ

0,0036

0,4509

0,0366

0,733

0,0001

0,0036

VBD

0,2231

0,0615

0,0322

0,0837

0,0050

0,0514

RB

0,0479

0,0120

0,0068

0,1012

0,1011

0,0728

<start>

0,2026

0,0449

0,2767

0,0453

0,0031

0,0510

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

11

Algoritmo de Viterbi:
matriz de probabilidad de emisión

(valores ficticios, en un caso real son mucho más pequeños)

El

0,5
0
0
0

0

0

Señor

Vino

Tarde

0
0,2
0,15
0,1

0

0

0
0,1
0
0

0,4

0

0
0,05
0
0

0,2

0,4

DT
NN
NNP
JJ

VBD

RB

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

12

Algoritmo de Viterbi: valores de viterbi

<start>

El

Señor

Vino

Tarde

<end>

<end>

DT

NN

NNP

JJ

VBD

RB

<start>

► Máximo de: valor de viterbi previo * p.transición * p.emisión

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

13

Algoritmo de Viterbi: valores de viterbi

<end>

<start>

<end>
DT
NN
NNP
JJ
VBD
RB
<start>

1

El
0
0,1013
0
0
0
0
0
0

Tarde
0
0

Señor
0
0

Vino
0
0
0,00961134 0,00011687 7,1059E-07
0
0,00174287
0
0,00218504
0
0
0

0,00012072 7,3397E-07
2,482E-06
0

0
0

0
0

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

14

Algoritmo de Viterbi: ruta de máxima probabilidad

<end>

<start>

<end>
DT
NN
NNP
JJ
VBD
RB
<start>

1

El
0
0,1013
0
0
0
0
0
0

Tarde
0
0

Señor
0
0

Vino
0
0
0,00961134 0,00011687 7,1059E-07
0
0,00174287
0
0,00218504
0
0
0

0,00012072 7,3397E-07
2,482E-06
0

0
0

0
0

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

15

Algoritmo de Viterbi: ruta de máxima probabilidad

<end>

<start>

<end>
DT
NN
NNP
JJ
VBD
RB
<start>

1

El
0
0,1013
0
0
0
0
0
0

Tarde
0
0

Señor
0
0

Vino
0
0
0,00961134 0,00011687 7,1059E-07
0
0,00174287
0
0,00218504
0
0
0

0,00012072 7,3397E-07
2,482E-06
0

0
0

0
0

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

16

Algoritmo de Viterbi: ruta de máxima probabilidad

<end>

<start>

<end>
DT
NN
NNP
JJ
VBD
RB
<start>

1

El
0
0,1013
0
0
0
0
0
0

Tarde
0
0

Señor
0
0

Vino
0
0
0,00961134 0,00011687 7,1059E-07
0
0,00174287
0
0,00218504
0
0
0

0,00012072 7,3397E-07
2,482E-06
0

0
0

0
0

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

17

Algoritmo de Viterbi: ruta de máxima probabilidad

<end>

<start>

<end>
DT
NN
NNP
JJ
VBD
RB
<start>

1

El
0
0,1013
0
0
0
0
0
0

Tarde
0
0

Señor
0
0

Vino
0
0
0,00961134 0,00011687 7,1059E-07
0
0,00174287
0
0,00218504
0
0
0

0,00012072 7,3397E-07
2,482E-06
0

0
0

0
0

El/DT señor/NN vino/VBD tarde/RB

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

18

Etiquetado basado en Machine Learning

► Diferencia con respecto a otros ámbitos (señal, imagen, datos, etc)

¿Cómo representamos el texto a la entrada?

Palabras  Vectores
El señor come pescado

Como categorías (one-hot)

Bag of Word

Word embeddings

El

0

0

0

1

señor

Come

Pescado

0

0

1

0

0

1

0

0

1

0

0

0

• Recuento
•

Frecuencia
relativa
TF-IDF

•

• Word2Vec
• Glove

Métodos pre-
entrenados que
producen vectores
de menor
dimensionalidad
(aprox. 300)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

19

Etiquetado basado en Machine Learning

► Diferencia con respecto a otros ámbitos (señal, imagen, datos, etc)

¿Cómo representamos la secuencialidad?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

20

Etiquetado basado en Machine Learning

Chiche, A., Yitagesu, B. Part of speech tagging: a systematic review of deep learning and
machine learning approaches. J Big Data 9, 10 (2022).
https://doi.org/10.1186/s40537-022-00561-y

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

21

Named Entity Recognition

► Definición

Reconocimiento de entidades con nombre (NER) es una de las características que ofrece Azure

Cognitive Service for Language, una colección de algoritmos de aprendizaje automático e

inteligencia artificial en la nube para el desarrollo de aplicaciones inteligentes en las que interviene

lenguaje escrito. La característica Reconocimiento de entidades con nombre puede identificar y

clasificar entidades en texto no estructurado. Por ejemplo: personas, lugares, organizaciones y

cantidades. (Microsoft)

Busca localizar y clasificar en categorías predefinidas, como personas, organizaciones, lugares,

expresiones de tiempo y cantidades, las entidades nombradas encontradas en un texto. (Wikipedia)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

22

Named Entity Recognition

► Categorías predefinidas

– PER: personas, como por ejemplo el nombre de alguien (ej.: Frodo Baggins)
– GPE: ubicaciones geopolíticas: países, ciudades o estados (ej.: Madrid).
– LOC: ubicaciones concretas no geo-políticas (ej.: Vesubio).
– ORG: organizaciones o empresas (ej.: Microsoft).
– MONEY: referencias a dinero (ej.: $ 5).
– DATE: fechas (ej.: 05/02/2021 o «jueves»).

► Categorías específicas

– P.ej: book-name; weapon; hardware;

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

23

Named Entity Recognition

► Ejemplo

– “En un lugar de La Mancha, de cuyo nombre no quiero acordarme…”

– “Yo he visto cosas que vosotros no creeríais. Atacar naves en llamas
más allá de Orión. He visto rayos-C brillar en la oscuridad cerca de la
Puerta de Tannhäuser. Todos esos momentos se perderán en el
tiempo, como lágrimas en la lluvia. Es hora de morir.”

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

24

Named Entity Recognition

► Técnicas

– Goyal, A., Gupta, V., & Kumar, M. (2018). Recent named entity recognition and
classification techniques: a systematic review. Computer Science Review, 29,
21-43.

– Li, J., Sun, A., Han, J., & Li, C. (2020). A survey on deep learning for named
entity recognition. IEEE Transactions on Knowledge and Data Engineering,
34(1), 50-70.

► Sistemas basados en reglas

► Aprendizaje automático

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

25

En resumen

► Algoritmo de Viterbi

– Cálculo de los valores de Viterbi, y luego vuelta atrás
– Depende del corpus que ha dado lugar a las prob. de transmisión y

emisión

– Se hacen suposiciones para simplificar

► POS Basado en machine learning

– Reto: representar adecuadamente el texto a la entrada de la red
– Apendizaje supervisado

► Named-Entity Recognition

– Identificar fragmentos de texto como categorías pre-establecidas

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

26

En la próxima sesión

¿Cómo construir el árbol sintáctico de una oración?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

27

www.unir.net

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 4 – Análisis Sintáctico

Problema del día

¿Cómo construir el árbol sintáctico de una oración?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

Encuesta previa

► ¿Sabes qué es el árbol sintáctico de una oración?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

En el día de hoy

► Sintaxis, análisis sintáctico

► Gramáticas de estructura sintagmática

► Métodos para el análisis sintáctico basado en programación dinámica

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

De donde venimos…

El señor vino tarde

► Análisis morfológico

– el Definite=Def|Gender=Masc|Number=Sing|PronType=Art
– señor Gender=Masc|Number=Sing
– venir Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin
– tarde

► Análisis morfosintáctico (POS)

– DET
– NOUN
– VERB
– ADV

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

5

A dónde vamos

https://nlp.lsi.upc.edu/freeling/demo/demo.php

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

6

O

SN

SV

DET

N

V

CC

El señor vino tarde

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

El análisis sintáctico

► En el análisis sintáctico se determinan las

relaciones estructurales entre palabras

(apuntes de la asignatura)

► El análisis sintáctico es, en el campo de la

lingüística, el análisis de las funciones

sintácticas o relaciones de concordancia y

jerarquía que guardan las palabras

agrupándose entre sí en sintagmas u

oraciones. (www.wikilengua.org)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

El árbol sintáctico

► Oración: conjunto de sintagmas

► Sintagma (o grupo): constituyente sintáctico

formado por dos o más constituyentes

sintácticos

► Nodos: constituyentes sintácticos

► Hojas: palabras de la oración

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Gramáticas de estructura sintagmática

► Formalizan, con el objetivo de llevar a cabo tratamiento computacional, el

conocimiento de la gramática.

– Vocabulario terminal T
– Vocabulario no terminal N

• V es la unión entre T y N

– Conjunto de reglas R
– Símbolo inicial I

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Gramáticas de estructura sintagmática

► Ejemplo:

► jajajaa

► T = {j,a}

► N = {J, A, E}

► R = {

– E JA
– J  j
– A  a
– A  Aa
– E  EE
}
► I = E

– jajajaa
– Jajajaa
– JAjajaa
– Ejajaa
– EJajaa
– EJAjaa
– EEjaa
– EEJaa
– EEJAa
– EEJA
– EEE
– EE
– E

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Relaciones estructurales

Son reglas para la formación de sintagmas, o de oraciones

► Ejemplos:

SN  Det N

Se lee: El sintagma nominal se puede formar con un determinante y
un nombre, en ese orden.

O  SN SV

Se lee: Una oración se puede formar con un sintagma nominal seguido
de un sintagma verbal, en ese orden.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

12

Gramáticas de estructura sintagmática

► una cultura  D N

► la literatura moderna  D N A  D N GA  D GN  SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Tipos de gramáticas

► De estados finitos

– En el lado izquierdo, símbolo NO TERMINAL
– En el lado derecho ≥ 1 , por lo menos uno debe ser terminal

► Libres de contexto

– En el lado izquierdo, símbolo NO TERMINAL
– En el lado derecho ≥ 0 , terminales o no terminales

► Sensibles al contexto

– Número de símbolos izda. ≤ Número de símbolos dcha.

► Enumerables recursivamente

– Sin restricciones

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Tipos de gramáticas

► Con categorías complejas

T ={el, la, los, las, un, uno, una, unas, unos, señor, señora, gato, gata, ciudad, vino, viajó, comió, tarde, pronto}

N = {SN, SV, DET, N, Vt, Vi, CC}

R =

•

•

•

•

•

•

•

•

•

•

•

DET  {el, la, los, las, un, uno, una, unas, unos}

N  {señor, señora, gato, gata, ciudad}

Vt  {comió}

Vi  {viajó, vino}

CC  {tarde, pronto}

O  SN SV

SN  N

SN  DET N

SV  Vi CC

SV  Vi

SV  Vt SN

La señor vino tarde

El señores vino tarde

El gata vino tarde

I = O

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Tipos de gramáticas

► Con categorías complejas

R =

T ={el, la, los, las, un, uno, una, unas,

unos, señor, señora, gato, gata,

ciudad, vino, viajó, comió, tarde,

pronto}

N = {SN, SV, DETms, DETmp,

DETfs, DETfp, Nms, Nfs, Vt, Vi, CC}

I = O

•

•

•

•

•

•

•

•

•

•

•

•

•

•

•

•

DETms  {el, un, uno}

DETfs  {la, una}

DETmp  {los, unos}

DETfp  {las,unas}

Nms  {señor, gato}

Nfs  {señora, gata, ciudad}

Vt  {comió}

Vi  {viajó, vino}

CC  {tarde, pronto}

O  SN SV

SN  N

SN  DETms Nms

SN  DETfs Nfs

SV  Vi CC

SV  Vi

SV  Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Tipos de gramáticas

► Con categorías complejas

R =

T ={el, la, los, las, un, uno, una, unas,

unos, señor, señora, gato, gata,

ciudad, vino, viajó, comió, tarde,

pronto}

N = {SN, SV, DETms, DETmp,

DETfs, DETfp, Nms, Nfs, Vt, Vi, CC}

I = O

•

•

•

•

•

•

•

•

•

•

•

•

•

•

•

•

DETms  {el, un, uno}

DETfs  {la, una}

DETmp  {los, unos}

DETfp  {las,unas}

Nms  {señor, gato}

Nfs  {señora, gata, ciudad}

Vt  {comió}

Vi  {viajó, vino}

CC  {tarde, pronto}

O  SN SV

SN  N

SN  DETms Nms

SN  DETfs Nfs

SV  Vi CC

SV  Vi

SV  Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Tipos de gramáticas

► Con categorías complejas

R =

•

•

•

O  SN [num= NUM, gen=GEN] SV [num= NUM, gen=GEN]

SN [num= NUM, gen=GEN]  N [num= NUM, gen=GEN]

SN [num= NUM, gen=GEN] 

DET [num= NUM, gen=GEN] N [num= NUM, gen=GEN]

• …

El = {DET, m, s}

La = {DET, f, s}

…

Señor = {N, m, s}

…

N = {SN, SV, DET, N, Vt, Vi, CC}

I = O

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Tipos de gramáticas

► Libres de contexto

– En el lado izquierdo, símbolo NO TERMINAL
– En el lado derecho ≥ 0 , terminales o no terminales

► Forma normal de Chomsky

– Una gramática formal está en Forma normal de Chomsky si

todas sus reglas de producción son de alguna de las
siguientes formas
• A  a
• A  BC

– Cualquier gramática libre de contexto se puede transformar en

su CNF

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Algoritmo Cocke-Kasami-Younger (CKY)

► Conceptos básicos

– Determina si una secuencia pertenece al lenguaje definido en una

GLC

– Requiere que la GLC esté en forma normal de Chomsky
• Toda GLC se puede escribir en forma normal

– Destaca por su eficiencia

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

20

Algoritmo Cocke-Kasami-Younger (CKY)

► Pasos

1. Transformar la gramática a su forma normal de Chomsky

2. Construir una matriz triangular a partir de la oración

3. Rellenar la matriz

4. Reconstruir el árbol sintáctico

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

21

Algoritmo Cocke-Kasami-Younger (CKY)

1. Transformar la gramática a su forma normal de Chomsky

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

22

Algoritmo Cocke-Kasami-Younger (CKY)

1. Transformar la gramática a su forma normal de Chomsky

Lexicón:

N = {gato, pescado, perro,
pez, ..}
Det = {el, la,una,…}
Vi = {salta, duerme, …}
Vt = { ve, ama, come,…}

Reglas:

1) O -> SN SV
2) SN -> N
3) SN -> Det N
4) SV -> Vi
5) SV -> Vt SN

Gramática en CNF
1) O -> SN SV

2) SN -> gato | pescado | perro | pez

3) Det -> el | la | una

4) SN -> Det N

5) N -> gato | pescado | perro | pez

9) SV -> salta | duerme

10) Vt -> ve | ama | come

11) SV -> Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

23

Algoritmo Cocke-Kasami-Younger (CKY)

2. Construir una matriz triangular a partir de la oración

El

(0,1)

gato

(0,2)

come

pescado

(0,3)

(0,4)

(1,2)

(1,3)

(1,4)

(2,3)

(2,4)

(3,4)

Gramática en CNF
1) O -> SN SV

2) SN -> gato | pescado | perro | pez

3) Det -> el | la | una

4) SN -> Det N

5) N -> gato | pescado | perro | pez

9) SV -> salta | duerme

10) Vt -> ve | ama | come

11) SV -> Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

24

Algoritmo Cocke-Kasami-Younger (CKY)

3. Rellenar la matriz

El

(0,1)

gato

(0,2)

come

pescado

(0,3)

(0,4)

(1,2)

(1,3)

(1,4)

(2,3)

(2,4)

(3,4)

Gramática en CNF
1) O -> SN SV

2) SN -> gato | pescado | perro | pez

3) Det -> el | la | una

4) SN -> Det N

5) N -> gato | pescado | perro | pez

9) SV -> salta | duerme

10) Vt -> ve | ama | come

11) SV -> Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

25

Algoritmo Cocke-Kasami-Younger (CKY)

3. Rellenar la matriz

El

(0,1)
Det

gato

(0,2)

come

pescado

(0,3)

(0,4)

(1,3)

(1,4)

(1,2)
SN
N

(2,3)
Vt

(2,4)

(3,4)
SN
N

Gramática en CNF
1) O -> SN SV

2) SN -> gato | pescado | perro | pez

3) Det -> el | la | una

4) SN -> Det N

5) N -> gato | pescado | perro | pez

9) SV -> salta | duerme

10) Vt -> ve | ama | come

11) SV -> Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

26

Algoritmo Cocke-Kasami-Younger (CKY)

3. Rellenar la matriz

El

(0,1)
Det

gato

(0,2)
SN

(1,2)
SN
N

come

pescado

(0,3)

(0,4)

(1,3)

(1,4)

(2,3)
Vt

(2,4)

(3,4)
SN
N

Gramática en CNF
1) O -> SN SV

2) SN -> gato | pescado | perro | pez

3) Det -> el | la | una

4) SN -> Det N

5) N -> gato | pescado | perro | pez

9) SV -> salta | duerme

10) Vt -> ve | ama | come

11) SV -> Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

27

Algoritmo Cocke-Kasami-Younger (CKY)

3. Rellenar la matriz

El

(0,1)
Det

gato

(0,2)
SN

(1,2)
SN
N

come

pescado

(0,3)

(0,4)

(1,3)

(1,4)

(2,3)
Vt

(2,4)

(3,4)
SN
N

Gramática en CNF
1) O -> SN SV

2) SN -> gato | pescado | perro | pez

3) Det -> el | la | una

4) SN -> Det N

5) N -> gato | pescado | perro | pez

9) SV -> salta | duerme

10) Vt -> ve | ama | come

11) SV -> Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

28

Algoritmo Cocke-Kasami-Younger (CKY)

3. Rellenar la matriz

El

(0,1)
Det

gato

(0,2)
SN

(1,2)
SN
N

come

pescado

(0,3)

(0,4)

(1,3)

(1,4)

(2,3)
Vt

(2,4)

(3,4)
SN
N

Gramática en CNF
1) O -> SN SV

2) SN -> gato | pescado | perro | pez

3) Det -> el | la | una

4) SN -> Det N

5) N -> gato | pescado | perro | pez

9) SV -> salta | duerme

10) Vt -> ve | ama | come

11) SV -> Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

29

Algoritmo Cocke-Kasami-Younger (CKY)

3. Rellenar la matriz

El

(0,1)
Det

gato

(0,2)
SN

(1,2)
SN
N

come

pescado

(0,3)

(0,4)

(1,3)

(1,4)

(2,3)
Vt

(2,4)
SV

(3,4)
SN
N

Gramática en CNF
1) O -> SN SV

2) SN -> gato | pescado | perro | pez

3) Det -> el | la | una

4) SN -> Det N

5) N -> gato | pescado | perro | pez

9) SV -> salta | duerme

10) Vt -> ve | ama | come

11) SV -> Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

30

Algoritmo Cocke-Kasami-Younger (CKY)

3. Rellenar la matriz

El

(0,1)
Det

gato

(0,2)
SN

(1,2)
SN
N

come

pescado

(0,3)

(0,4)

(1,3)

(2,3)
Vt

(1,4)
O

(2,4)
SV

(3,4)
SN
N

Gramática en CNF
1) O -> SN SV

2) SN -> gato | pescado | perro | pez

3) Det -> el | la | una

4) SN -> Det N

5) N -> gato | pescado | perro | pez

9) SV -> salta | duerme

10) Vt -> ve | ama | come

11) SV -> Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

31

Algoritmo Cocke-Kasami-Younger (CKY)

3. Rellenar la matriz

El

(0,1)
Det

gato

(0,2)
SN

(1,2)
SN
N

come

pescado

(0,3)

(1,3)

(2,3)
Vt

(0,4)
O

(1,4)
O

(2,4)
SV

(3,4)
SN
N

Gramática en CNF
1) O -> SN SV

2) SN -> gato | pescado | perro | pez

3) Det -> el | la | una

4) SN -> Det N

5) N -> gato | pescado | perro | pez

9) SV -> salta | duerme

10) Vt -> ve | ama | come

11) SV -> Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

32

Algoritmo Cocke-Kasami-Younger (CKY)

4. Reconstruir el árbol

El

(0,1)
Det

gato

(0,2)
SN

(1,2)
SN
N

come

pescado

(0,3)

(1,3)

(2,3)
Vt

(0,4)
O

(1,4)
O

(2,4)
SV

(3,4)
SN
N

Gramática en CNF
1) O -> SN SV

2) SN -> gato | pescado | perro | pez

3) Det -> el | la | una

4) SN -> Det N

5) N -> gato | pescado | perro | pez

9) SV -> salta | duerme

10) Vt -> ve | ama | come

11) SV -> Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

33

Algoritmo Cocke-Kasami-Younger (CKY)

Ambigüedad

“Book the flight through Houston”

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

34

Algoritmo CKY probabilístico

- Gramática con probabilidades
- El cálculo de las celdas arrastra la probabilidad

El

(0,1)
Det 0.55

gato

(0,2)
SN 0.077

0.7*0.55*0.2

(1,2)
N 0.2
SN 0.2

come

(0,3)

(1,3)

pescado

(0,4)
O 0.00111

(1,4)
O 0.00288

(2,3)
Vt 0.2

(2,4)
SV 0.013

(3,4)
SN 0.15
N 0.15

Gramática en CNF

O -> SN SV (0.8)

SN -> gato (0.2)

SN -> pescado (0.15)

Det -> el (0.55)

SN -> Det N (0.7)

N -> gato (0.2)

N -> pescado (0.15)

SV -> salta (0.35)

SV -> duerme (0.27)

Vt -> ve (0.7)

Vt -> ama (0.1)

Vt -> come (0.2)

SV -> Vt SN (0.6)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

35

En la próxima sesión

¿Cómo representar la semántica de las palabras y realizar

razonamientos?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

36

www.unir.net

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 5 – Análisis Semántico

La pregunta del día

¿Cómo representar la semántica de las palabras y realizar

razonamientos?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

Encuesta previa

► ¿Sabes qué es una Ontología?

► (P1) Si llueve, la calle se moja.

(P2) No llovió.

(C) La calle no está mojada.

– ¿Te suena?

► ¿Conoces DBPedia?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

En el día de hoy

► Utilidad del análisis semántico

► Representación formal del significado

– Representación formal con lógicas descriptivas
– Representación formal con lógicas de primer orden

► Gramáticas Libres de Contexto con anotaciones semánticas

– Análisis semántico dirigido por la sintaxis

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

Utilidad del análisis semántico

► Convertir el conocimiento contenido en un texto en un modelo

formal con el que poder realizar operaciones lógicas

Lorem ipsum dolor sit
amet, consectetur
adipiscing elit. Curabitur
ex felis, fermentum eu
cursus a, semper nec est.
Morbi porttitor.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

5

Representación del conocimiento

► Debe ser verificable, inequívoca, expresiva y permitir la inferencia

de nuevo conocimiento.

► Algunas representaciones

– Lógica de primer orden

• Lógicas descriptivas

– Redes Semánticas
– Frames

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

6

Lógicas descriptivas

► Subconjunto de la expresividad de la lógica de primer orden

► Mecanismos para:

– generar descripciones de conceptos
– introducir axiomas
– introducir propiedades de los individuos
– Inferir nuevos conocimientos a partir de los axiomas

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

Formalismo de las lógicas descriptivas

► No hay un formalismo único, el término lógica descriptiva denota a

una familia de formalismos.

► El más utilizado es ALC.

► De las lógicas descriptivas derivan OWL y la Web Semántica

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

8

Formalismo de tripletas

► Ibañez es Autor

► Ibañez escribió El sulfato atómico

► Los autores son personas

Cormenzana, Roberto & López-Borrull, Alexandre. (2018). ESTUDIO DE LA
ADAPTACIÓN A RDA Y BIBFRAME EN EL ÁMBITO DE LAS BIBLIOTECAS
ESPAÑOLAS: ESTUDIOS DE CASO Title: STUDY OF THE ADAPTATION TO RDA
AND BIBFRAME IN THE FIELD OF SPANISH LIBRARIES: CASE STUDIES. Anales
de Documentacion. 21. 10.6018/analesdoc.21.2.323441.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

9

Operaciones con lógicas descriptivas

► Subsunción

– Determinar si una categoría es un subconjunto de otra

► Clasificación

– Determinar si un individuo pertenece a una categoría

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

10

Operaciones con lógicas descriptivas

► Subsunción

– Determinar si una categoría es un subconjunto de otra

► Clasificación

– Determinar si un individuo pertenece a una categoría

"¿Qué toreros se casaron
con cantantes de copla?"

ABOX

X : esTorero
Y: esCantanteCopla

<X, Y>: Casados

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

11

Lógica de primer orden

► Es un sistema formal diseñado para estudiar la inferencia en los

lenguajes de primer orden. (Wikipedia)

► Recogemos el significado de una oración en lenguaje natural y lo

representamos de manera formal, para poder hacer operaciones

matemático/lógicas.

► El formalismo es fijo, las variables y funciones son arbitrarias.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

12

Ejemplos de la lógica de primer orden

► Luis es profesor

– Profesor(Luis)

► Luis es profesor de Jorge

– ProfesorDe(Luis, Jorge)
– ProfesorDe(Luis, Jorge) ^ ProfesorDe(Luis, Juan)

► Los alumnos son personas

– ∀ (x) Alumno(x) → Persona(x)

► Existe un profesor que es una persona

– ∃ (x) Profesor(x) → Persona(x)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

13

Formalismo de la lógica de primer orden

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

14

Bases para el análisis semántico

► Una forma para representar el conocimiento

– Lógicas descriptivas, lógica de primer orden

► Una forma para, a partir del lenguaje natural, saber qué

conocimiento representar

– Técnicas de extracción del conocimiento  análisis semántico

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

15

Bases para la extracción del conocimiento

► Principio de composición (y cómo aplicarlo)

► Hipótesis rule-to-rule (y cómo aplicarla)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

16

Principio de composición

El significado de una oración se construye a partir del significado de sus partes

¿

?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

17

Principio de composición

El significado de una oración se construye a partir del significado de sus partes

¿

Ejemplos:

?

- Análisis de sentimiento con búsqueda de palabras relevantes

- Métodos basados en BoW

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

18

Principio de composición

El significado de una oración se construye a partir del significado de sus partes

¿

?

María ama a Pedro ≠ Pedro ama a María ≠ Pedro María

ama a

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

19

Principio de composición

El significado de una oración se

construye a partir del significado de

sus partes

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

20

Principio de composición

El significado de una oración se construye a

partir del significado de sus partes

Pedro ama a María

∃𝑒 𝐴𝑚𝑎𝑟 𝑒 ∧ 𝐴𝑚𝑎𝑛𝑡𝑒 𝑒,𝑃𝑒𝑑𝑟𝑜 ∧ 𝐴𝑚𝑎𝑑𝑎(𝑒, 𝑀𝑎𝑟𝑖𝑎)

María ama a Pedro

∃𝑒 𝐴𝑚𝑎𝑟 𝑒 ∧ 𝐴𝑚𝑎𝑛𝑡𝑒 𝑒,𝑀𝑎𝑟í𝑎 ∧ 𝐴𝑚𝑎𝑑𝑜(𝑒, 𝑃𝑒𝑑𝑟𝑜)

Pedro María ama a

𝑆𝑖𝑛 𝑠𝑖𝑔𝑛𝑖𝑓𝑖𝑐𝑎𝑑𝑜 𝑣á𝑙𝑖𝑑𝑜

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

21

Hipótesis rule-to-rule

► Cada regla aplicada para constituir el análisis sintáctico tiene un

significado equivalente en el análisis semántico

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

22

Gramáticas Libres de Contexto anotadas

Se construyen con la hipótesis rule-to-rule

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

23

Rule-to-rule en anotaciones semánticas

► Asociar expresiones del cálculo lambda complejas, similares a una

función, a las reglas léxicas.

► Copiar el valor semántico del único constituyente a la construcción cuando la

regla gramatical solo tiene un constituyente.

► Aplicar la semántica de uno de los constituyentes de una regla gramatical a la

semántica de otro de los constituyentes de la regla como si fuera una función.

► Foreach regla en GLC:

– If (regla tiene símbolo terminal a la derecha)

•

Lo rellenas directamente

– Else if (regla tiene un único símbolo no terminal a la derecha)

• Copias el símbolo terminal que va debajo

– Else if (regla tiene dos o más símbolos no terminales a la derecha)

• Haces una relación de subordinación

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

24

Rule-to-rule en anotaciones semánticas

Asociar expresiones del cálculo lambda complejas, similares a una función, a

las reglas léxicas.

o NP  Matías

{ λm.m (Matías) }

o N  restaurante

{ λr.Restaurante(r) }

o Det  un

o Vt  abrió

{ λP. λQ.ⱻx P(x) ^ Q(x) }

{ λw. λz.w (λx.ⱻe Abierto(e)

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) }

o O  SN SV

o SN  NP

o SN  Det N

o SV  Vt SN

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

25

Rule-to-rule en anotaciones semánticas

Copiar el valor semántico del único constituyente a la construcción cuando la regla

gramatical solo tiene un constituyente.

o NP  Matías

{ λm.m (Matías) }

o N  restaurante

{ λr.Restaurante(r) }

o Det  un

o Vt  abrió

{ λP. λQ.ⱻx P(x) ^ Q(x) }

{ λw. λz.w (λx.ⱻe Abierto(e)

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) }

o O  SN SV

o SN  NP

o SN  Det N

o SV  Vt SN

{NP.sem}

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

26

Rule-to-rule en anotaciones semánticas

► Aplicar la semántica de uno de los constituyentes de una regla gramatical a la

semántica de otro de los constituyentes de la regla como si fuera una función

o NP  Matías

{ λm.m (Matías) }

o N  restaurante

{ λr.Restaurante(r) }

o Det  un

o Vt  abrió

{ λP. λQ.ⱻx P(x) ^ Q(x) }

{ λw. λz.w (λx.ⱻe Abierto(e)

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) }

o O  SN SV

{ SN.sem(SV.sem) }

o SN  NP

{ NP.sem }

o SN  Det N

{ Det.sem(N.sem) }

o SV  Vt SN

{ Vt.sem(SN.sem) }

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

27

Análisis Semántico en paralelo con el Sintáctico

o NP  Matías

{ λm.m (Matías) }

o N  restaurante

{ λr.Restaurante(r) }

o Det  un

o

Vt  abrió

{ λP. λQ.ⱻx P(x) ^ Q(x) }

{ λw. λz.w (λx.ⱻe Abierto(e)

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) }

o O  SN SV

{ SN.sem(SV.sem) }

o

o

o

SN  NP

{ NP.sem }

SN  Det N

{ Det.sem(N.sem) }

SV  Vt SN

{ Vt.sem(SN.sem) }

Matías abrió

un restaurante

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

28

Análisis Semántico en paralelo con el Sintáctico

o NP  Matías

{ λm.m (Matías) }

o N  restaurante

{ λr.Restaurante(r) }

o Det  un

o

Vt  abrió

{ λP. λQ.ⱻx P(x) ^ Q(x) }

{ λw. λz.w (λx.ⱻe Abierto(e)

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) }

o O  SN SV

{ SN.sem(SV.sem) }

o

o

o

SN  NP

{ NP.sem }

SN  Det N

{ Det.sem(N.sem) }

SV  Vt SN

{ Vt.sem(SN.sem) }

{ λm.m
(Matías) }

NP

Matías abrió

un restaurante

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

29

Análisis Semántico en paralelo con el Sintáctico

o NP  Matías

{ λm.m (Matías) }

o N  restaurante

{ λr.Restaurante(r) }

o Det  un

o

Vt  abrió

{ λP. λQ.ⱻx P(x) ^ Q(x) }

{ λw. λz.w (λx.ⱻe Abierto(e)

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) }

o O  SN SV

{ SN.sem(SV.sem) }

o

o

o

SN  NP

{ NP.sem }

SN  Det N

{ Det.sem(N.sem) }

SV  Vt SN

{ Vt.sem(SN.sem) }

{ λm.m
(Matías) }

SN

NP

Matías abrió

un restaurante

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

30

Análisis Semántico en paralelo con el Sintáctico

o NP  Matías

{ λm.m (Matías) }

o N  restaurante

{ λr.Restaurante(r) }

o Det  un

o

Vt  abrió

{ λP. λQ.ⱻx P(x) ^ Q(x) }

{ λw. λz.w (λx.ⱻe Abierto(e)

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) }

o O  SN SV

{ SN.sem(SV.sem) }

o

o

o

SN  NP

{ NP.sem }

SN  Det N

{ Det.sem(N.sem) }

SV  Vt SN

{ Vt.sem(SN.sem) }

{ λw. λz.w (λx.ⱻe Abierto(e) ^PersonaQueAbre(e,z) ^
CosaAbierta(e,x)) }

SN

NP

V

Matías abrió

un restaurante

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

31

Análisis Semántico en paralelo con el Sintáctico

o NP  Matías

{ λm.m (Matías) }

o N  restaurante

{ λr.Restaurante(r) }

o Det  un

o

Vt  abrió

{ λP. λQ.ⱻx P(x) ^ Q(x) }

{ λw. λz.w (λx.ⱻe Abierto(e)

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) }

o O  SN SV

{ SN.sem(SV.sem) }

o

o

o

SN  NP

{ NP.sem }

SN  Det N

{ Det.sem(N.sem) }

SV  Vt SN

{ Vt.sem(SN.sem) }

{ λP. λQ.ⱻx P(x) ^
Q(x) }

SN

NP

V

DET

Matías abrió

un restaurante

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

32

Análisis Semántico en paralelo con el Sintáctico

o NP  Matías

{ λm.m (Matías) }

o N  restaurante

{ λr.Restaurante(r) }

o Det  un

o

Vt  abrió

{ λP. λQ.ⱻx P(x) ^ Q(x) }

{ λw. λz.w (λx.ⱻe Abierto(e)

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) }

o O  SN SV

{ SN.sem(SV.sem) }

o

o

o

SN  NP

{ NP.sem }

SN  Det N

{ Det.sem(N.sem) }

SV  Vt SN

{ Vt.sem(SN.sem) }

{ λr.Restaurante(r)
}

SN

NP

V

DET

N

Matías abrió

un restaurante

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

33

Análisis Semántico en paralelo con el Sintáctico

o NP  Matías

{ λm.m (Matías) }

o N  restaurante

{ λr.Restaurante(r) }

o Det  un

o

Vt  abrió

{ λP. λQ.ⱻx P(x) ^ Q(x) }

{ λw. λz.w (λx.ⱻe Abierto(e)

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) }

o O  SN SV

{ SN.sem(SV.sem) }

o

o

o

SN  NP

{ NP.sem }

SN  Det N

{ Det.sem(N.sem) }

SV  Vt SN

{ Vt.sem(SN.sem) }

{ Det.sem (N.sem) }

{ λP. λQ.ⱻx P(x) ^ Q(x) ( λr.Restaurante(r) ) }

{ λQ.ⱻx λr.Restaurante(r)(x) ^ Q(x) }

{ λQ.ⱻx Restaurante(x) ^ Q(x) }

SN

NP

V

SN

DET

N

Matías abrió

un restaurante

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

34

Análisis Semántico en paralelo con el Sintáctico

o NP  Matías

{ λm.m (Matías) }

o N  restaurante

{ λr.Restaurante(r) }

o Det  un

o

Vt  abrió

{ λP. λQ.ⱻx P(x) ^ Q(x) }

{ λw. λz.w (λx.ⱻe Abierto(e)

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) }

o O  SN SV

{ SN.sem(SV.sem) }

o

o

o

SN  NP

{ NP.sem }

SN  Det N

{ Det.sem(N.sem) }

SV  Vt SN

{ Vt.sem(SN.sem) }

{ Vt.sem( SN.sem ) }

{λw. λz.w (λx.ⱻe Abierto(e)

SN

SV

NP

V

SN

DET

N

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) ( λQ.ⱻx Restaurante((x) ^

Q(x) )}
{λz.ⱻx Restaurante(x) ^ λx.ⱻe Abierto(e)

^PersonaQueAbre(e,z)^CosaAbierta(e,x) (x) }

Matías abrió

un restaurante

{ λz.ⱻx Restaurante(x) ^ⱻe Abierto(e) ^ PersonaQueAbre(e,z) ^
CosaAbierta(e,x) }

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

35

Análisis Semántico en paralelo con el Sintáctico

o NP  Matías

{ λm.m (Matías) }

o N  restaurante

{ λr.Restaurante(r) }

o Det  un

o

Vt  abrió

{ λP. λQ.ⱻx P(x) ^ Q(x) }

{ λw. λz.w (λx.ⱻe Abierto(e)

O

^PersonaQueAbre(e,z)^CosaAbierta(e,x)) }

o O  SN SV

{ SN.sem(SV.sem) }

o

o

o

SN  NP

{ NP.sem }

SN  Det N

{ Det.sem(N.sem) }

SV  Vt SN

{ Vt.sem(SN.sem) }

SN

SV

{ SN.sem( SV.sem )
}
{ λm.m (Matías) (
λz.ⱻx Restaurante(x) ^ⱻe Abierto(e) ^ PersonaQueAbre(e,z) ^
CosaAbierta(e,x) ) }

NP

V

SN

DET

N

{λz.ⱻx Restaurante(x) ^ⱻe Abierto(e) ^ PersonaQueAbre(e,z) ^ CosaAbierta(e,x)
Matías abrió
(Matías)}

un restaurante

{ⱻx Restaurante(x) ^ⱻe Abierto(e) ^ PersonaQueAbre(e, Matías) ^
CosaAbierta(e,x)}

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

36

Análisis Semántico en paralelo con el Sintáctico

► Ventajas

► Inconvenientes

– Descarta ramas inválidas

– Ineficiente

semánticamente hablando

computacionalmente

– Dos análisis en un único

– Complejo de construir

cálculo

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

37

En resumen

► El análisis semántico busca formalizar el conocimiento

► Los modelos basados en tripletas

– son más sencillos
– permiten la aplicación de reglas lógicas.

► Los modelos basados en lógicas de primer orden

– Son más complejos
– Permiten paralelizar análisis sintáctico y semántico
– Permiten una representación completa de la oración

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

38

En la próxima semana

¿Cómo aplicar técnicas de desambiguación del significado?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

39

www.unir.net

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 6 – Semántica Léxica

La pregunta del día

¿Cómo aplicar técnicas de desambiguación del significado?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

En el día de hoy

► Semántica Léxica:

– Significado de las palabras

– Relaciones formales entre sentidos de las palabras

– Recursos para la catalogación de significados, WordNet

– Desambiguación del sentido de las palabras

• LESK
• Schütze

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

Significado de las palabras

► Semántica Léxica:

– Campo de la lingüística que estudia el significado de las

palabras y las relaciones de sentido que establecen entre ellas

– Funciones:

• Caracterizar el significado

• Estudiar las relaciones entre palabras

• Estudiar la variación contextual del significado
– https://www.youtube.com/watch?v=Xyp7xt-ygy0

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

Relaciones formales entre palabras

► Homonimia: homografía, homofonía

► Polisemia

► Sinónimos/antónimos

► Hipónimos/hiperónimos

► Merónimos/holónimos

► Metonimia

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Relaciones formales entre palabras

► Homonimia: homografía, homofonía

Requiere desambiguación

Genera dificultades al reconocer el lenguaje hablado

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Relaciones formales entre palabras

► Polisemia

– Una palabra es polisémica cuando tiene varios significados

• Hoja
• Mesa
• Ratón

– La polisemia se aplica a los lemas (p.ej. marcha vs marcha)

Requiere desambiguación

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Relaciones formales entre palabras

► Sinónimos

► Antónimos

Son relaciones binarias

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Relaciones formales entre palabras

► Hipónimos/hiperónimos

► A es más general que B (El hiperónimo es más general que el hipónimo)

– Animal es más general que perro
– Perro es más general que dálmata

► Se dice que:

– B es hipónimo de A

• Perro es hipónimo de animal

– A es hiperónimo de B

• Perro es hiperónimo de dálmata

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Relaciones formales entre palabras

► Merónimos/holónimos

► A es parte de B (el merónimo es parte del holónimo)

– La nariz forma parte de la cabeza
– La fosa nasal forma parte de la nariz

► Se dice que:

– A es merónimo de B

• Nariz es merónimo de cabeza

– B es holónimo A

• Nariz es holónimo de fosa nasal

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Relaciones formales entre palabras

► Metonimia

– Uso de una palabra en lugar de otra, valiéndose de una

relación existente

► Causa por su efecto

► Contenedor por el contenido

► Símbolo por la cosa simbolizada

► Lugar por lo que en él se produce

► Marca comercial por objeto de la marca

► Obra por el nombre de su autor

► La parte por el todo

► El todo por la parte

► (…)

Genera sinonimia no catalogada

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Recursos para la catalogación de significados

► Diccionarios

– Recogen los significados de un lema

► Tesauros

– Recogen las relaciones entre significados de un lema

► https://wordnet.princeton.edu/

► https://www.nltk.org/howto/wordnet.html

► https://www.nltk.org/api/nltk.corpus.reader.wordnet.html

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Conceptos clave de WordNet

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

WordNet con Python

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

WordNet en español con Python

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Antes de seguir, dos conceptos

► Colocación de una palabra

► Vectorización básica de palabras

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

16

Colocación de una palabra

► Dada una palabra cualquiera, en un texto cualquiera, la colocación

de dicha palabra es la secuencia de N palabras previas, y N

palabras posteriores, a la palabra que genera la colocación.

– Texto ejemplo:
“Muchos años después, frente al pelotón de fusilamiento, el coronel Aureliano Buendía había
de recordar aquella tarde remota en que su padre lo llevó a conocer el hielo. Macondo era
entonces una aldea de veinte casas de barro y cañabrava construida a la orilla de un río de
aguas diáfanas que se precipitaban por un lecho de piedras pulidas, blancas y enormes como
huevos prehistóricos. El mundo era tan reciente, que muchas cosas carecían de nombre, y
para mencionarlas había que señalarlas con el dedo”

Colocación de N=3 para la palabra ‘barro’

Con stopwords: [‘veinte’, ‘casas’, ‘de’, ‘barro’, ‘y’, ‘cañabrava’, ‘construida’]
Sin stopwords: ['aldea', 'veinte', 'casas', 'barro', 'cañabrava', 'construida', 'orilla’”]

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

17

Vectorizar texto: Empezamos con one-hot-encoding

Cada categoría se representa por un vector único

Y cada palabra es una categoría

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

18

Vectorizar texto: Empezamos con one-hot-encoding

En un lugar de la Mancha, de

cuyo nombre no quiero

acordarme, no ha mucho

tiempo que vivía un hidalgo de

los de lanza en astillero,

adarga antigua, rocín flaco y

galgo corredor.

Hay 27 palabras diferentes 

Se representan con vectores

de dimensión 27

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

19

Vectorizar texto: Bag of Words

► Recuento de palabras

– “antiguo, de un astillero antiguo”

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

20

Desambiguación semántica basada en
conocimiento
► Lesk

Leemos el significado en el diccionario

► Lesk simplificado

– Se lematiza cada uno de los sentidos de una palabra
– Se lematiza la colocación
– Se comparan ambas lematizaciones

► Lesk original

– Se lematiza cada uno de los sentidos de una palabra
– Se lematiza cada uno de los sentidos de las palabras colocadas
– Se comparan las lematizaciones

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

21

Lesk simplificado

► Compara la firma de la palabra ambigua (signature), que se corresponde

con su definición en el diccionario, con las palabras de contexto

(context), es decir, con las palabras vecinas a la palabra ambigua

El banco le prestó dinero

banco1:
Empresa dedicada a realizar operaciones financieras con el dinero procedente
de sus accionistas y de los depósitos de sus clientes.

(empresa, dedicar, realizar, operación,
financiera, dinero, accionista, depósito, cliente)

banco2:
Asiento, con respaldo o sin él, en que pueden sentarse dos o más personas.

(asiento, respaldo, poder, sentarse, persona)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

22

Lesk simplificado

► Compara la firma de la palabra ambigua (signature), que se corresponde

con su definición en el diccionario, con las palabras de contexto

(context), es decir, con las palabras vecinas a la palabra ambigua

El banco le prestó dinero

banco1:

banco2:

(empresa, dedicar, realizar, operación,
financiera, dinero, accionista, depósito, cliente)

(asiento, respaldo, poder, sentarse, persona)

Contexto:

(prestar, dinero)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

23

Lesk simplificado

► Compara la firma de la palabra ambigua (signature), que se corresponde

con su definición en el diccionario, con las palabras de contexto

(context), es decir, con las palabras vecinas a la palabra ambigua

El banco le prestó dinero

banco1:

banco2:

(empresa, dedicar, realizar, operación,
financiera, dinero, accionista, depósito, cliente)

(asiento, respaldo, poder, sentarse, persona)

Contexto:

(prestar, dinero)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

24

Lesk simplificado

► Compara la firma de la palabra ambigua (signature), que se corresponde

con su definición en el diccionario, con las palabras de contexto

(context), es decir, con las palabras vecinas a la palabra ambigua

El banco le prestó dinero

banco1:

banco2:

(empresa, dedicar, realizar, operación,
financiera, dinero, accionista, depósito, cliente)

1 solapamiento

(asiento, respaldo, poder, sentarse, persona)

0 solapamientos

Contexto:

(prestar, dinero)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

25

Lesk original

► Compara la firma de la palabra ambigua (signature), que se corresponde

con su definición en el diccionario, con las firmas de las palabras de

contexto (context), es decir, con las palabras vecinas a la palabra ambigua

Me senté en un banco del parque

banco1:

(empresa, dedicar, realizar, operación,
financiera, dinero, accionista, depósito, cliente)

0 solapamiento

banco2:

(asiento, respaldo, poder, sentarse, persona)

2 solapamientos

Contexto:

sentar: poner a una persona en un asiento apoyado sobre sus nalgas

(poner, persona, asiento, apoyar, nalgas)

parque: Espacio que se dedica a jardines

(espacio,dedicar, jardin)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

26

Acerca de los métodos basados en conocimiento

► Ventajas

– Muy explicables
– Basta con disponer de un recurso básico (diccionario)

► Inconvenientes

– No trabaja bien con entradas de diccionario muy cortas

• Ampliar con sinónimos

– Todas las palabras tienen el mismo peso

• Aplicar un peso por colocación, POS Tag.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

27

Desambiguación semántica basada en
aprendizaje no supervisado
► Schütze

Hacemos clústers para cada uno de los sentidos

► Clusterización

– Calcular el vector de contexto
– Clusterizar
– Calcular el centroide

► Desambiguación

– Menor distancia entre vectores

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

28

Schütze

► Clusterización

– Se calcula un vector de contexto c para cada aparición wi de la

palabra w en el corpus

(con un bag of words de la colocación)

– Se aplica un algoritmo de agrupamiento sobre los vectores de

contexto c en un número predefinido de grupos, que definirán cada
uno de los sentidos de la palabra w

(con k-means)

– Se calcula el centroide de cada grupo. Cada vector de un centroide

será el vector representación de un sentido de la palabra w

(promedio de cada dimensión)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

29

Clusterizar vectores

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

30

Schütze

► Desambiguación

– Se calcula un vector de contexto c para la aparición de la palabra w

que queremos desambiguar

(con un bag of words de la colocación)

– Se calcula la distancia desde el vector c hasta cada uno de los

centroides

– Se selecciona el centroide más cercano con el sentido correcto

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

31

Schütze

► Ventajas

– No hace falta un corpus etiquetado
– Conceptualmente sencillo

► Inconvenientes

– Mucho preprocesamiento para cada palabra
– Baja explicabilidad, aunque explicable en última instancia

(podríamos asignar palabras clave, con peso, a cada corpus)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

32

En resumen

► La semántica léxica estudia los significados de las palabras
► La semántica léxica trabaja con los lemas

► Los significados se recogen en Diccionarios

► Las relaciones entre palabras se recogen en Tesauros

► Desambiguación como tarea relevante en semántica léxica

– Métodos basados en conocimiento
– Métodos basados en vectores

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

33

www.unir.net

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 6 – Semántica Léxica

La pregunta del día

¿Cómo calcular la similitud entre palabras?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

En el día de hoy

► Semántica Léxica:

– Recordatorio:

• Relaciones entre palabras: holónimos y merónimos
• WordNet
• Colocaciones y BoW

– Similitud entre sentidos de las palabras

• Basadas en tesauro
• Basadas en tesauro + corpus
• Medidas stadísticas

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

Recordatorio: relaciones formales entre palabras

► Hipónimos/hiperónimos

► A es más general que B (El hiperónimo es más general que el hipónimo)

– Animal es más general que perro
– Perro es más general que dálmata

► Se dice que:

– B es hipónimo de A

• Perro es hipónimo de animal

– A es hiperónimo de B

• Perro es hiperónimo de dálmata

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Recordatorio: relaciones formales entre palabras

► Merónimos/holónimos

► A es parte de B (el merónimo es parte del holónimo)

– La nariz forma parte de la cabeza
– La fosa nasal forma parte de la nariz

► Se dice que:

– A es merónimo de B

• Nariz es merónimo de cabeza

– B es holónimo A

• Nariz es holónimo de fosa nasal

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Recordatorio: Relaciones formales entre palabras

► Metonimia

– Uso de una palabra en lugar de otra, valiéndose de una

relación existente

► Causa por su efecto

► Contenedor por el contenido

► Símbolo por la cosa simbolizada

► Lugar por lo que en él se produce

► Marca comercial por objeto de la marca

► Obra por el nombre de su autor

► La parte por el todo

► El todo por la parte

► (…)

Genera sinonimia no catalogada

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Recordatorio: colocación de una palabra

► Dada una palabra cualquiera, en un texto cualquiera, la colocación

de dicha palabra es la secuencia de N palabras previas, y N

palabras posteriores, a la palabra que genera la colocación.

– Texto ejemplo:
“Muchos años después, frente al pelotón de fusilamiento, el coronel Aureliano Buendía había
de recordar aquella tarde remota en que su padre lo llevó a conocer el hielo. Macondo era
entonces una aldea de veinte casas de barro y cañabrava construida a la orilla de un río de
aguas diáfanas que se precipitaban por un lecho de piedras pulidas, blancas y enormes como
huevos prehistóricos. El mundo era tan reciente, que muchas cosas carecían de nombre, y
para mencionarlas había que señalarlas con el dedo”

Colocación de N=3 para la palabra ‘barro’

Con stopwords: [‘veinte’, ‘casas’, ‘de’, ‘barro’, ‘y’, ‘cañabrava’, ‘construida’]
Sin stopwords: ['aldea', 'veinte', 'casas', 'barro', 'cañabrava', 'construida', 'orilla’”]

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

Recordatorio: Vectorizar texto

En un lugar de la Mancha, de

cuyo nombre no quiero

acordarme, no ha mucho

tiempo que vivía un hidalgo de

los de lanza en astillero,

adarga antigua, rocín flaco y

galgo corredor.

Hay 27 palabras diferentes 

Se representan con vectores

de dimensión 27

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

8

Recordatorio: Bag of Words

► Recuento de palabras

– “antiguo, de un astillero antiguo”

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

9

Similitud desde el punto de vista matemático

► Una similitud es un valor en el intervalo [-1, 1]

► Representa la semejanza entre dos vectores

– El valor 1 indica que son idénticos
– El valor 0 indica que no tienen ninguna característica común
– El valor -1 indica que son vectores opuestos entre sí

– No confundir similitud con distancia

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

10

Similitud entre palabras

► Métodos

– Basadas en tesauro

– Medidas estadísticas

– Basados en vectores calculados con métodos neuronales

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Similitud mediante tesauro

► Dos palabras son más similares si están cerca en el árbol del

tesauro. Es decir, si hay pocos saltos entre ellas

► En la práctica, se utilizan relaciones de hiponimia e hiperonimia

► Entre sentidos:

► Entre palabras:

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Similitud mediante tesauro: ejemplo

► Similitud entre silla y mesa (chair and table)

furniture

table

seat

chair

furniture

chair

table

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

path(silla, mesa) = 3+1 = 4
sim_path(silla, mesa) = 1/4 =
0.25

Similitud mediante tesauro: código NLTK

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Similitud mediante tesauro: problemas

► Subjetividad inherente al tesauro

► Valores discretos

► Se asume igual valor para todos los saltos

– Alternativas:

• Normalizar las distancias según la

profundidad del árbol

• Asociar distancias diferentes
• Métodos basados en la teoría de la

información

furniture

table

seat

chair

furniture

chair

table

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Similitud mediante tesauro: alternativas

► Leacock Chodorow Similarity:

– -log(sortest_path/2*max_distance2root)

► Wu-Palmer Similarity

– (2.0 * max_subsumer_depth) / (len2lcs1 + len2lcs2)

► Resnik Similarity:

– Information Content(least common subsumer)

► Jiang-Conrath Similarity:

– 1 / (IC(s1) + IC(s2) - 2 * IC(lcs))

► Lin Similarity:

– 2 * IC(lcs) / (IC(s1) + IC(s2))

https://www.nltk.org/api/nltk.corpus.reader.wordnet.html

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Similitud con métodos estadísticos

► Conseguir colocaciones de una palabra en un corpus

► Vectorizar las colocaciones de dicha palabra

► Calcular el/los centroide(s)

► El centroide será su vector representativo

► La similitud entre palabras se calcula como similitud entre

vectores.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Similitud mediante vectores

► Métricas matemáticas bien conocidas

– Distancia euclídea
– Similitud de coseno
– Pearson
– Jaccard
– Levensthein
– 17 types of similarity and dissimilarity measures used in data

science

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

En resumen

► Similitud como métrica importante en el PLN

– Métodos basados en tesauro
– Métodos basados en vectores

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

19

www.unir.net

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 7 – Modelado estadístico del lenguaje

La pregunta del día

¿Cómo podemos predecir siguiente texto, dado el comienzo de una

oración?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

En el día de hoy

► Introducción al Modelado del Lenguaje Estadístico

► Modelado de Lenguaje con N-Gramas

– Cómo crearlos
– Cómo medirlos
– Técnicas de suavizado

► Introducción al Modelado del Lenguaje Vectorial

► Modelado de Lenguaje con Vectores

– BoW
– TF
– TF-iDF

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

Introducción al modelado del lenguaje estadístico

► Qué es

– Un método para darle forma computacional al texto

► Para qué sirve

– Teclados predictivos
– Traducción automática
– Speech to text
– Generación de textos

► Cómo se hace?

– Estadístico

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

Modelado de Lenguaje con N-Gramas

► Tokens (palabras)

– [“En”, “un”, “lugar”, “de”, “La_Mancha”]

► Bigramas

– [ [“En”, “un”], [“un”,”lugar”],[“lugar”, “de”], [“de”, “La_Mancha”] ]

► Trigramas

– [ [“En”, “un”, “lugar”], [“un”,”lugar”, “de”], [“lugar”, “de”, “La_Mancha”] ]

► N-gramas

– [ … ]

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

5

Modelado de Lenguaje con N-Gramas

► ¿Cuál es la probabilidad de que, dada una palabra, aparezca otra

palabra concreta?

► Para un texto de referencia dado, ¿Cuál es la probabilidad de

que, dada una palabra, aparezca otra palabra concreta?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

6

Modelado de Lenguaje con N-Gramas

► ¿Cuál es la probabilidad de que tras la palabra “want” aparezca la

palabra to?

𝑃  𝑡𝑜 𝑤𝑎𝑛𝑡 =

𝐴𝑝𝑎𝑟𝑖𝑐𝑖𝑜𝑛𝑒𝑠 𝑑𝑒 "𝑤𝑎𝑛𝑡 𝑡𝑜"
𝐴𝑝𝑎𝑟𝑖𝑐𝑖𝑜𝑛𝑒𝑠 𝑑𝑒 "𝑤𝑎𝑛𝑡"

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

Modelado de Lenguaje con N-Gramas

Las filas y las
columnas no
suman lo mismo,
► ¿Cuál es la probabilidad de que tras la palabra “want” aparezca la
pero porque es un
ejemplo recortado

palabra to?

𝑃  𝑡𝑜 𝑤𝑎𝑛𝑡 =

𝐴𝑝𝑎𝑟𝑖𝑐𝑖𝑜𝑛𝑒𝑠 𝑑𝑒 "𝑤𝑎𝑛𝑡 𝑡𝑜"
𝐴𝑝𝑎𝑟𝑖𝑐𝑖𝑜𝑛𝑒𝑠 𝑑𝑒 "𝑤𝑎𝑛𝑡"

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

8

Modelado de Lenguaje con N-Gramas

► La probabilidad en un bigrama es fácil, ¿y en un

trigrama?

𝑃  𝑡𝑜 𝐼 𝑤𝑎𝑛𝑡 =

𝐴𝑝𝑎𝑟𝑖𝑐𝑖𝑜𝑛𝑒𝑠 𝑑𝑒 "𝐼 𝑤𝑎𝑛𝑡 𝑡𝑜"
𝐴𝑝𝑎𝑟𝑖𝑐𝑖𝑜𝑛𝑒𝑠 𝑑𝑒 "𝐼 𝑤𝑎𝑛𝑡"

= ??
827

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

9

Modelado de Lenguaje con N-Gramas

► ¿Y en un N-Grama?

𝑃  𝑒𝑎𝑡 𝐼 𝑤𝑎𝑛𝑡 𝑡𝑜 =

𝐴𝑝𝑎𝑟𝑖𝑐𝑖𝑜𝑛𝑒𝑠 𝑑𝑒 "𝐼 𝑤𝑎𝑛𝑡 𝑡𝑜 𝑒𝑎𝑡"
𝐴𝑝𝑎𝑟𝑖𝑐𝑖𝑜𝑛𝑒𝑠 𝑑𝑒 "𝐼 𝑤𝑎𝑛𝑡 𝑡𝑜"

= ¿?
¿?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

10

Modelado de Lenguaje con N-Gramas

► ¿Y en un N-Grama?

► Aplicamos la regla de la cadena

𝑃  𝐼 𝑤𝑎𝑛𝑡 𝑡𝑜 𝑒𝑎𝑡 =
𝑃 𝐼 ×
𝑃 𝑤𝑎𝑛𝑡 𝐼 ×
𝑃 𝑡𝑜 𝐼 𝑤𝑎𝑛𝑡 ×
𝑃 𝑒𝑎𝑡 𝐼 𝑤𝑎𝑛𝑡 𝑡𝑜

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

11

Modelado de Lenguaje con N-Gramas

► ¿Y en un N-Grama?

► Aplicamos la regla de la cadena

► Y la hipótesis de Markov

𝑃  𝐼 𝑤𝑎𝑛𝑡 𝑡𝑜 𝑒𝑎𝑡 =
𝑃 𝐼 ×
𝑃 𝑤𝑎𝑛𝑡 𝐼 ×
𝑃 𝑡𝑜 𝑤𝑎𝑛𝑡 ×
𝑃 𝑒𝑎𝑡 𝑡𝑜

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

12

Modelado de Lenguaje con N-Gramas

► Ya somos capaces de:

– Dada una secuencia, calcular la probabilidad de una

siguiente palabra dada

– Calcular la probabilidad de una secuencia dada

Siempre, en un corpus de referencia

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

13

Modelado de Lenguaje con N-Gramas

► Problemas del modelo

– Hay palabras que no aparecen en el corpus

– Hay bigramas que no aparecen en el corpus ( y

todas sus secuencias serán cero )

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

14

Técnicas de suavizado

► ¿Por qué el suavizado de modelos?

► Técnica de Laplace y técnica add-k

► Backoff e interpolación

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

15

¿Por qué el suavizado de modelos?

“no lo he visto” ≠ “no puede existir”

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

16

Técnica de Laplace y técnica add-k

+1

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

17

Técnica de Laplace y técnica add-k

2/5
3/6
6/9

608/827
609/828
612/831

=
=
=

=
=
=

0,4
0,5
0,66666667

0,73518742
0,73550725
0,73646209

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

18

Técnica de Laplace y técnica add-k

+k

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

19

Backoff e interpolación

► Backoff

– Se utilizan N gramas cada vez más pequeños, hasta encontrar

uno que sea distinto de cero

𝑃 𝑒𝑎𝑡 𝐼 𝑤𝑎𝑛𝑡 𝑡𝑜 ≈ 𝑃 𝑡𝑜 𝐼 𝑤𝑎𝑛𝑡 ≈ 𝑃 𝑤𝑎𝑛𝑡 𝐼 ≈ 𝑃(𝐼)

► Interpolación

– Se calcula como combinación lineal de n-gramas de menor

orden

𝑃 𝑒𝑎𝑡 𝐼 𝑤𝑎𝑛𝑡 𝑡𝑜 ≈ 𝜆1𝑃 𝑡𝑜 𝐼 𝑤𝑎𝑛𝑡 + 𝜆2𝑃 𝑤𝑎𝑛𝑡 𝐼 + 𝜆3𝑃(𝐼)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

20

Evaluación

► Nos dice en qué medida funciona un modelo

► Extrínseca

– Se prueba en la aplicación final

(p.ej. Precission y recall en la predicción de un teclado móvil)

► Intrínseca

– Perplejidad

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

21

Perplejidad

► Cuanto menor sea el valor, mejor es el modelo

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

22

Introducción al modelado del lenguaje vectorial

► Qué es

– Un método para darle forma computacional al texto

► Para qué sirve

– Uso de redes neuronales

► Cómo se hace?

– Vectorial

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

23

Nuestro texto de referencia

En un lugar de La Mancha, de cuyo nombre no quiero acordarme, no

ha mucho tiempo que vivía un hidalgo de los de lanza en astillero,

adarga antigua, rocín flaco y galgo corredor.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

24

Empezamos con one-hot-encoding

Hay 27 palabras diferentes  Se representan con vectores de

dimensión 27

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

25

Características de one-hot-enconding

► Es fácil de generar y manejar

► Todos los vectores son ortogonales entre sí

► En redes neuronales, cada palabra activaría una neurona de

entrada diferente

► Dimensión del vector potencialmente muy elevada

► El vector no contiene información sobre la palabra, es sólo una

asignación arbitraria

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

26

Modelos de lenguaje con Vectores

► Bag of Words (BoW), es una técnica que genera un único vector

que contiene todas las palabras de un texto.

► BoW binario

► BoW TF

► BoW WTF

► BoW TF-iDF

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

27

BoW binario

► 1 si la palabra aparece. 0 si la palabra no aparece.

– “antiguo, de un astillero antiguo”

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

28

BoW TF

► Recuento de palabras

– “antiguo, de un astillero antiguo”

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

29

BoW WTF

► Frecuencia de aparición de las palabras

– “antiguo, de un astillero antiguo”

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

30

BoW TF-iDF (representación global)

► Se pondera TF con respecto a las apariciones del mismo término

en otros documentos

– Nos dice si la palabra es un factor diferencial de este texto con

respecto a otros

► Ejemplo (no estricto, pero muy ilustrativo)

https://flowingdata.com/2018/09/18/cuisine-ingredients/

– En el ejemplo,

•
•

“most used” sería TF
“cuisine-specific” sería TF-iDF

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

31

Una vez que tengo el texto como vector

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

32

Una vez que tengo el texto como vector

► Problemas

– Vectores de entrada potencialmente muy grandes

– Vectores de entrada que NO tienen relación con el significado

– Modelo incapaz de entender la secuencialidad del texto

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

33

En resumen

► Modelos estadísticos

– Modelo que nos permite conocer la probabilidad de aparición de un N-Grama
– Aplicaciones

•
•
•

Teclados móviles
Traducción
Text-to-speech

► Modelado con vectores

– Modelo que nos permite construir un vector que representa a un texto

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

34

En la próxima semana

¿Cómo podemos representar una palabra en forma vectorial?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

35

www.unir.net

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 8 – Modelado neuronal del lenguaje

La pregunta del día

¿Cómo podemos representar una palabra en forma vectorial?

¿Cómo podemos superar las limitaciones de one-hot-encoding?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

Encuesta previa

► ¿Qué tal dominas el concepto de red neuronal?

► ¿Qué tal dominas el concepto de aprendizaje supervisado?

► ¿Qué tal dominas el concepto de aprendizaje no supervisado?

► ¿Conoces autoencoders?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

En el día de hoy

► La neurona artificial: fundamentos

► Introducción a embedings

► Word2Vec

– CBOW
– SkimGram
– Ejemplo de Word2Vec con código

► Otros Modelos

– FastText
– Glove

► Uso de los Embedings

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

La neurona artificial: fundamentos

𝑣 = θ +∑𝑁

𝑖=1 𝑥𝑖∗𝑤 𝑖

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

5

La neurona artificial: fundamentos

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

6

La neurona artificial: fundamentos

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

Funcionamiento básico de redes neuronales

1 capa oculta de 3 neuronas, y 1 único valor de salida

¿Cuántas entradas tiene la red?
¿Cuántos parámetros (pesos y sesgos) deben ser entrenados?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

8

Funcionamiento básico de redes neuronales

Red con 3 entradas, una capa oculta de 5 neuronas, y 1 único valor de salida

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

9

Funcionamiento básico de redes neuronales

Red con 3 entradas, una capa oculta de 5 neuronas, y 2 valores de salida

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

10

Funcionamiento básico de redes neuronales

Red con 3 entradas, 2 capas ocultas de 5 neuronas cada una, y 2 valores de
salida

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

11

Funcionamiento básico de redes neuronales

Red con 3 entradas, 2 capas ocultas de 5 y 7 neuronas, y 3 valores de salida

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

12

Funcionamiento básico de redes neuronales

Red con 7 entradas, 3 capas ocultas de 5-3-5 neuronas, y 7 valores de salida

https://playground.tensorflow.org

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

13

Funcionamiento básico de redes neuronales

Red con 5 entradas, 5 capas ocultas de 3 neuronas, y 5 de salida

¿Cuántos parámetros (pesos y sesgos) deben ser entrenados?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

14

Funcionamiento básico de redes neuronales

Red con 2*5 entradas, 5 capas ocultas de 3 neuronas, y 5 de salida

¿Cuántos parámetros (pesos y sesgos) deben ser entrenados?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

15

Funcionamiento básico de redes neuronales

Red con 4*5 entradas, 5 capas ocultas de 3 neuronas, y 5 de salida

¿Cuántos parámetros (pesos y sesgos) deben ser entrenados?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

16

Introducción a embedings

► Problemas de Bag of Words

– Alta dimensionalidad

• Una dimensión por cada palabra representada
• El modelo en_core_web_lg tiene 514K palabras

– Dispersión

• En un modelo de 1000 palabras, una frase de 10 palabras tendrá

990 ceros y 10 unos.

– Falta de relación con el significado de la palabra

• Todos los vectores ortogonales entre sí, por lo que:

– su producto escalar es cero
– Su distancia euclídea es siempre la misma

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

17

Introducción a embedings. Idea de partida

► Idea inicial:

– Reducir dimensionalidad y dispersión
– Utilizar conceptos derivados de autoencoders

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

18

Word2Vec

Mikolov, T., Sutskever, I., Chen, K., Corrado, G. S., & Dean, J.
(2013). Distributed representations of words and phrases and their
compositionality. Advances in neural information processing
systems, 26.

https://arxiv.org/abs/1310.4546

Propuesto por Google en 2013

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

19

Word2Vec. CBOW (Continuous Bag of Words)

► Cómo entrenar la red

► “En un lugar de La Mancha, de

cuyo nombre no quiero acordarme”

– “En un lugar de La”
– “un lugar de La Mancha”
– “lugar de La Mancha de”
– “de La Mancha de cuyo”
– “La Mancha de cuyo nombre”

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

20

Word2Vec. Skip-Gram.

► Cómo entrenar la red

► “En un lugar de La Mancha, de

cuyo nombre no quiero acordarme”

– “En un lugar de La”
– “un lugar de La Mancha”
– “lugar de La Mancha de”
– “de La Mancha de cuyo”
– “La Mancha de cuyo nombre”

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

21

Word2Vec. Cómo obtener el embeding

W * wonehot.palabra= wemb.palabra

X

0

0

1

0

0

=

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2222

Word2Vec

► Resultados

– Vectores de dimensión 300

– No hay dispersión

– Posición del vector relacionada con el significado

• https://projector.tensorflow.org/

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

23

Posición del vector relacionada con el significado

► Permite establecer similitud entre palabras

– Campos semánticos de detección automática
– Mucha ayuda en topic detection

► Permite procesar palabras que previamente no habían aparecido

– Vectores similares a la entrada darán clasificaciones similares

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

24

Representación con vectores de palabras

► Cómo entrenar un modelo con Word2Vec

https://github.com/kavgan/nlp-in-practice/tree/master/word2vec

► Representación tridimensional de Word2Vec

https://projector.tensorflow.org/

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

25

Otros Modelos. FastText

► Problema de Word2Vec.

– Palabras mal escritas
– Palabras nuevas

► Solución propuesta por FastText

– Hacer que los tokens sean n-gramas de palabras

<wh, whe, her, ere, re>

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

26

Word2Vec vs FastText

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

27

Otros Modelos. Glove

► Se afronta el problema con herramientas matriciales

– Reducción de la dimensionalidad con matriz característica

► Word2Vec vs Glove

– Resultados similares
– Glove es paralelizable

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

28

Uso de Word embedings

► Similitud semántica entre palabras / entre oraciones

► Input para redes neuronales

https://towardsdatascience.com

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

29

Uso de Word embedings

► Similitud semántica entre palabras / entre oraciones

► Input para redes neuronales

0,83

0,99

0,30

0,40

0,04

300 positions

https://towardsdatascience.com

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

30

En la próxima semana

¿Cómo podemos procesar una secuencia de tamaño variable con

una red neuronal?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

31

www.unir.net

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 8 – Modelado de lenguaje neuronal

En el día de hoy

¿Cómo podemos procesar una secuencia de tamaño variable con

una red neuronal?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

Encuesta previa

► ¿Cómo funciona una red neuronal?

► ¿Qué es un Word embedding?

► ¿Qué técnica introduce la idea de partir las palabras en tokens

menores?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

En el día de hoy

► Funcionamiento básico de redes neuronales

► Embedings (recordatorio)

► Redes recurrentes y LSTM

– ELMO

► Transformers

– BERT
– BETO

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

Funcionamiento básico de redes neuronales

𝑣 = θ +∑𝑁

𝑖=1 𝑥𝑖∗𝑤 𝑖

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

5

Funcionamiento básico de redes neuronales

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

6

Funcionamiento básico de redes neuronales

Red con 3 entradas, 1 capa oculta de 3 neuronas, y 1 único valor de salida

¿Cuántos parámetros (pesos y sesgos) deben ser entrenados?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

Funcionamiento básico de redes neuronales

Red con 3 entradas, una capa oculta de 5 neuronas, y 1 único valor de salida

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

8

Funcionamiento básico de redes neuronales

Red con 3 entradas, una capa oculta de 5 neuronas, y 2 valores de salida

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

9

Funcionamiento básico de redes neuronales

Red con 3 entradas, 2 capas ocultas de 5 neuronas cada una, y 2 valores de
salida

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

10

Funcionamiento básico de redes neuronales

Red con 3 entradas, 2 capas ocultas de 5 y 7 neuronas, y 3 valores de salida

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

11

Funcionamiento básico de redes neuronales

Red con 7 entradas, 3 capas ocultas de 5-3-5 neuronas, y 7 valores de salida

https://playground.tensorflow.org

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

12

Funcionamiento básico de redes neuronales

Red con 5 entradas, 5 capas ocultas de 3 neuronas, y 5 de salida

¿Cuántos parámetros (pesos y sesgos) deben ser entrenados?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

13

Funcionamiento básico de redes neuronales

Red con 2*5 entradas, 5 capas ocultas de 3 neuronas, y 5 de salida

¿Cuántos parámetros (pesos y sesgos) deben ser entrenados?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

14

Funcionamiento básico de redes neuronales

Red con 4*5 entradas, 5 capas ocultas de 3 neuronas, y 5 de salida

¿Cuántos parámetros (pesos y sesgos) deben ser entrenados?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

15

Embeddings (recordatorio)

Red con 4*50K entradas, 50K capas ocultas de 300 neuronas, y 50K de salida

► Word2Vec

W * wonehot.palabra= wemb.palabra

X

0

1

0

0

0

=

• Vectores que representan palabras, y guardan relación con su

significado

• Generados con entrenamiento no supervisado

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

16

Procesamiento con redes clásicas

W * wonehot.palabra= wemb.palabra

…

Yo
Soy
Tu
Padre

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

17

Procesamiento con redes clásicas

W * wonehot.palabra= wemb.palabra

…

Yo
Soy
Tu
Padre

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

18

Procesamiento con redes clásicas

W * wonehot.palabra= wemb.palabra

…

Yo
Soy
Tu
Padre

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

19

Procesamiento con redes clásicas

W * wonehot.palabra= wemb.palabra

…

Yo
Soy
Tu
Padre

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

20

Procesamiento con redes clásicas

W * wonehot.palabra= wemb.palabra

…

Yo
Soy
Tu
Padre

…

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

21

Redes recurrentes

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

22

Redes recurrentes

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

23

Redes recurrentes.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

24

Redes recurrentes.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

25

Redes recurrentes.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

26

Redes recurrentes. Sequence to Sequence

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

27

Redes recurrentes. Influencia decreciente

Yo

Soy

Tu

Padre

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

28

Redes LSTM

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

29

Redes LSTM

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

30

Redes LSTM bidireccionales

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

31

ELMO

► Utiliza redes LSTM bidireccionales para extraer el embedding

– El embedding hace mejor uso del contexto

► Una palabra no tiene representación única

– Un embedding diferente para una misma palabra en

oraciones diferentes

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

32

ELMO demo

► Ejemplo extraído de https://www.geeksforgeeks.org

/overview-of-word-embedding-using-embeddings-

from-language-models-elmo/

https://colab.research.google.com/drive/1ivu0eVa6ua

cmjS_gq8P4SDGJR-8bbHhm?usp=sharing

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

33

Transformers

Waswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A.

N., ... & Polosukhin, I. (2017). Attention is all you need. Advances in neural

information processing systems, 30.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

34

Vector key, vector query

► Vector key

► Vector query

– Representa a la palabra

– Representa las partes de
la frase a las que esta
palabra presta atención

Yo

Voy

A

[-0.33 -0.44 ... 0.11]

[-0.76 -0.59 ... -0.40]

[ 0.14 -0.15 ... 0.43]

[0,33

Yo

-0.87

Voy

0,56

A

Aprobar

[-0.08 0.01 ... 0.48]

0,01]

Aprobar

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

35

BERT

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

36

BERT demo

► Ejemplo extraído de https://mccormickml.com/2019/

05/14/BERT-word-embeddings-tutorial/

https://colab.research.google.com/drive/1ZQvuAVwA3I

jybezQOXnrXMGAnMyZRuPU

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

37

BETO: Spanish BERT

► BETO is a BERT model trained on a big Spanish corpus.

Canete, J., Chaperon, G., Fuentes, R., Ho, J. H., Kang, H., & Pérez,

J. (2020). Spanish pre-trained bert model and evaluation data.

Pml4dc at iclr, 2020, 1-10.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

38

BETO: Spanish BERT

► Spanish Wikis: Wich include Wikipedia, Wikinews, Wikiquotes and more.

► ParaCrawl: Spanish portion of ParaCrawl (http://opus.nlpl.eu/ParaCrawl.php)

► EUBookshop: Spanish portion of EUBookshop (http://opus.nlpl.eu/EUbookshop.php)

► MultiUN: Spanish portion of MultiUN (http://opus.nlpl.eu/MultiUN.php)

► OpenSubtitles: Spanish portion of OpenSubtitles2018 (http://opus.nlpl.eu/OpenSubtitles-v2018.php)

► DGC: Spanish portion of DGT (http://opus.nlpl.eu/DGT.php)

► DOGC: Spanish portion of DOGC (http://opus.nlpl.eu/DOGC.php)

► ECB: Spanish portion of ECB (http://opus.nlpl.eu/ECB.php)

► EMEA: Spanish portion of EMEA (http://opus.nlpl.eu/EMEA.php)

► Europarl: Spanish portion of Europarl (http://opus.nlpl.eu/Europarl.php)

► GlobalVoices: Spanish portion of GlobalVoices (http://opus.nlpl.eu/GlobalVoices.php)

► JRC: Spanish portion of JRC (http://opus.nlpl.eu/JRC-Acquis.php)

► News-Commentary11: Spanish portion of NCv11 (http://opus.nlpl.eu/News-Commentary-v11.php)

► TED: Spanish portion of TED (http://opus.nlpl.eu/TED2013.php)

► UN: Spanish portion of UN (http://opus.nlpl.eu/UN.php)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

39

En resumen

► Los embeddings generan vectores que representan palabras.

► Las redes secuenciales generan embeddings que tienen en cuenta

el contexto.

► Una palabra tiene diferentes representaciones según el

contexto.

► Los Transformers añaden el concepto de atención, que amplía

aún más el contexto que se puede tener en cuenta.

– Bert, modelo original, en inglés
– BETO, modelo pre-entrenado en español

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

40

En la próxima semana

¿Cómo podemos procesar un texto de gran tamaño con una red

neuronal?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

41

www.unir.net

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 8 – Modelado de lenguaje neuronal

En el día de hoy

¿Cómo podemos procesar un texto de gran tamaño con una red

neuronal?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

Encuesta previa

► ¿Qué es relevante en una red recurrente?

► ¿Qué diferencia una RNN de una LSTM?

► ¿Cuál es la arquitectura de Sequence2Sequence?

► ¿Qué es un embedding contextual?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

En el día de hoy

► embeddings, RNN, LSTM (recordatorio)

► Transformers

– Atención
– Posicionamiento

► Modelos preentrenados

– BERT
– BETO
– HuggingFace

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

Embeddings (recordatorio)

► Word2Vec

W * wonehot.palabra= wemb.palabra

X

0

1

0

0

0

=

• Vectores que representan palabras, y guardan relación con su

significado

• Generados con entrenamiento no supervisado

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

5

RNN y LSTM (recordatorio)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

6

Seq2Seq (recordatorio)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

ELMO

► Utiliza redes LSTM bidireccionales para extraer el embedding

– El embedding hace mejor uso del contexto

► Una palabra no tiene representación única

– Un embedding diferente para una misma palabra en

oraciones diferentes

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

8

Entrenamiento de ELMO

► BiLM

– Bidirectional Language Modeling

En un lugar de La Mancha de cuyo nombre no quiero acordarme

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

9

Cómo utilizar ELMO

https://www.geeksforgeeks.org/overview-of-word-embedding-using-

embeddings-from-language-models-elmo/

https://colab.research.google.com/drive/1ivu0eVa6uacmjS_gq8P4SDGJR-

8bbHhm?usp=sharing

texto

ELMO

embeddings

CLASIFICADOR

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

10

Transformers

Waswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A.

N., ... & Polosukhin, I. (2017). Attention is all you need. Advances in neural

information processing systems, 30.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

11

Transformers

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

12

Transformers. Dos conceptos clave

► Atención

► embeddings posicionales

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

13

Atención: Vector key, vector query

► Vector key

► Vector query

– Representa a la palabra

– Representa una búsqueda

actual

de palabras que
encajarían con la actual

Yo

Voy

A

Aprobar

K

Q

YoK

[-0.33 -0.44 ... 0.11]

YoQ

[-0.66 -0.55 ... -0.22]

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

14

Vector key, vector query. Vector de atención

► Vector key

► Vector query

– Representa a la palabra

– Representa las partes de
la frase a las que esta
palabra presta atención

YoK

VoyK

AK

[-0.33 -0.44 ... 0.11]

[-0.76 -0.59 ... -0.40]

[ 0.14 -0.15 ... 0.43]

[0,13

YoQ * YoK

0.87

0,06

YoQ * VoyK

YoQ * AK

AprobarK

[-0.08 0.01 ... 0.48]

0,52]

YoQ * AprobarK

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

15

embeddings posicionales

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

16

embeddings posicionales

Yop

Voyp

Ap

[ 1 1 … 1]

[ 2 2 … 2]

[ 3 3 … 3]

Aprovarp

[ 4 4 … 4]

Yo

Voy

A

[-0.33 -0.44 ... 0.11]

[-0.76 -0.59 ... -0.40]

[ 0.14 -0.15 ... 0.43]

Aprobar

[-0.08 0.01 ... 0.48]

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

17

embeddings posicionales

Yop

Voyp

Ap

Aprobarp

[ 0 0 0 …0 0
0 ]

[ 0 0 0 …0 0
1 ]

[ 0 0 0 …0 1
0 ]

[ 0 0 0 …0 1
1 ]

Yo

Voy

A

[ -0.33 -0.44 ... 0.11 ]

[ -0.76 -0.59 ... -0.40 ]

[ 0.14 -0.15 ... 0.43 ]

Aprobar

[ -0.08 0.01 ... 0.48 ]

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

18

embeddings posicionales

Yop

Voyp

Ap

Aprobarp

Yo

Voy

A

[ -0.33 -0.44 ... 0.11 ]

[ -0.76 -0.59 ... -0.40 ]

[ 0.14 -0.15 ... 0.43 ]

Aprobar

[ -0.08 0.01 ... 0.48 ]

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

19

embeddings posicionales. Proceso paralelizable

► Los textos se dejan de tratar como secuencias

► Las palabras se procesan en paralelo

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

20

BERT

Devlin, J., Chang, M. W., Lee, K., & Toutanova, K. (2018). Bert: Pre-

training of deep bidirectional transformers for language

understanding. arXiv preprint arXiv:1810.04805.

Modelo de Lenguaje basado en Transformers

❑ Pre-entrenado con BooksCorpus (800M words) y Wikipedia en

inglés (2,500M words)

❑ Genera embeddings contextuales

❑ Entrenable para multiples tareas

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

21

BERT. Preentrenamiento

❑ Pre-entrenado con BooksCorpus (800M words) y Wikipedia en

inglés (2,500M words)

❑ Masked LM (MLM)

❑ Next Sentence Prediction (NSP)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

22

BERT demo

► Ejemplo extraído de https://mccormickml.com/2019/

05/14/BERT-word-embeddings-tutorial/

https://colab.research.google.com/drive/1ZQvuAVwA3I

jybezQOXnrXMGAnMyZRuPU

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

23

Más modelos en HuggingFace

https://huggingface.co/models

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

24

BETO: Spanish BERT

► BETO is a BERT model trained on a big Spanish corpus.

Canete, J., Chaperon, G., Fuentes, R., Ho, J. H., Kang, H., & Pérez,

J. (2020). Spanish pre-trained bert model and evaluation data.

Pml4dc at iclr, 2020, 1-10.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

25

BETO: Spanish BERT

► Spanish Wikis: Wich include Wikipedia, Wikinews, Wikiquotes and more.

► ParaCrawl: Spanish portion of ParaCrawl (http://opus.nlpl.eu/ParaCrawl.php)

► EUBookshop: Spanish portion of EUBookshop (http://opus.nlpl.eu/EUbookshop.php)

► MultiUN: Spanish portion of MultiUN (http://opus.nlpl.eu/MultiUN.php)

► OpenSubtitles: Spanish portion of OpenSubtitles2018 (http://opus.nlpl.eu/OpenSubtitles-v2018.php)

► DGC: Spanish portion of DGT (http://opus.nlpl.eu/DGT.php)

► DOGC: Spanish portion of DOGC (http://opus.nlpl.eu/DOGC.php)

► ECB: Spanish portion of ECB (http://opus.nlpl.eu/ECB.php)

► EMEA: Spanish portion of EMEA (http://opus.nlpl.eu/EMEA.php)

► Europarl: Spanish portion of Europarl (http://opus.nlpl.eu/Europarl.php)

► GlobalVoices: Spanish portion of GlobalVoices (http://opus.nlpl.eu/GlobalVoices.php)

► JRC: Spanish portion of JRC (http://opus.nlpl.eu/JRC-Acquis.php)

► News-Commentary11: Spanish portion of NCv11 (http://opus.nlpl.eu/News-Commentary-v11.php)

► TED: Spanish portion of TED (http://opus.nlpl.eu/TED2013.php)

► UN: Spanish portion of UN (http://opus.nlpl.eu/UN.php)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

26

HuggingFace

Librería Transformers

https://huggingface.co/docs/transformers/index

Destaca el PIPELINE

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

27

En resumen

► Los Transformers evolucionan sobre LSTM y RNN con:

– Atención

– Encoding posicional

► Diferentes configuraciones de Transformers dan lugar a modelos

de lenguaje neuronales preentrenados.

► HuggingFace es una comunidad que contiene múltiples modelos.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

28

En la próxima semana

¿Cómo utilizar grandes modelos de lenguaje para pre-entrenamiento

y fine-tuning?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

29

www.unir.net

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 8 – Modelado de lenguaje neuronal

En el día de hoy

¿Cómo configuramos un LLM para una aplicación?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

Encuesta previa

► ¿Qué dos conceptos introducen los Transformers?

► ¿Qué es un LLM?

► ¿Qué significa que un modelo está preentrenado?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

En el día de hoy

► Recorrido del procesado de lenguaje neuronal (recordatorio)

► Uso práctico de LLMs: pipeline en HuggingFace

► Pre-entrenamiento y Fine-Tuning.

– Trainer en HuggingFace
– Tareas comunes

► Sistemas RAG

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

Recorrido del procesado de lenguaje Neuronal
(recordatorio)

1986-RNN

1997-LSTM

2013-
Word2Vec

2017-
Transformers

2018-ELMO

2018-BERT

2020-GPT-3

2022-
ChatGPT

2023-Llama

2025-
DeepSeek

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

5

Pipeline en HuggingFace

https://huggingface.co/docs/transformers/en/index

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

6

Pipeline en HuggingFace

https://huggingface.co/docs/transformers/en/index

Ojo, algunos modelos requieren permiso para acceder:

https://huggingface.co/docs/hub/models-gated

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

Pre entrenamiento y fine tunning

► Pre entrenamiento:

– Aprendizaje semi-supervisado
– Tareas no específicas
– Grandes corpus de texto

► Fine Tunning

– Tareas concretas
– Corpus específicos de cada tarea
– Aprendizaje supervisado

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

8

Pre entrenamiento

► Word2Vec

– CBOW y SkipGram

► BERT

– Masked Language Model y Next Sentence Prediction

► GPT

► Llama

► DeepSeek

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

9

Pre entrenamiento

► Word2Vec

– CBOW y SkipGram

► BERT

– Masked Language Model y Next Sentence Prediction

► GPT

– CLM (Causal Language Modeling)

► Llama

– CLM
► DeepSeek

– CLM

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

10

Fine Tunning

https://huggingface.co/docs/transformers/v4.19.0/es/training

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

11

Tareas de FineTunning

► https://huggingface.co/docs/transformers/v5.1.0/en/main_classes/pi

pelines#transformers.TextGenerationPipeline

– "document-question-answering"
– "fill-mask"
– "question-answering"
– "text-classification" (alias "sentiment-analysis" available)
– "text-generation"

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

12

Modelos INSTRUCT

► Entrenamiento FINE-TUNNING basado en instrucciones:

► Ejemplo:

– INPUT:
•

“Give three tips for staying healthy”

– EXPECTED-OUTPUT:

•

“1.Eat a balanced diet and make sure to include plenty of
fruits and vegetables. 2. Exercise regularly to keep your
body active and strong. 3. Get enough sleep and maintain
a consistent sleep schedule.”

https://huggingface.co/datasets/tatsu-lab/alpaca/

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

13

Modelos disponibles en Hugging Face

► Ejercicio: localizar

– ELMO
– BERT
– GPT
– Llama
– DeepSeek

En Hugging Face https://huggingface.co/models

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

14

Sistemas RAG

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

15

Ejemplo de sistema RAG.

1. Una consulta del usuario

entrando al sistema.

2. Un módulo de recuperación

que busca en una base de

datos de conocimientos.

3. Un módulo de generación de

lenguaje (LLM) que recibe la

consulta y la información

recuperada.

4. Una respuesta generada que

sale del sistema, combinando

la información recuperada y el

conocimiento del LLM.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

16

En resumen

► Hay que saber distinguir entre un modelo pre-entrenado y un

modelo que ha pasado por fine-tunning

► En HuggingFace hay multitud de recursos tanto de pre-entrenados

como de fine-tunning

► Los sistemas RAG combinan el uso de LLM con técnicas de

búsqueda en bases de datos confiables, normalmente vectoriales

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

17

www.unir.net

Procesamiento del Lenguaje Natural
Luis de la Fuente Valentín

Tema 9 –Aplicaciones del PLN

En el día de hoy

¿Cómo construir una aplicación de PLN?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

2

En el día de hoy…

► Recordatorio de tecnologías clave

► Modelos Base, Modelos Instruct, modelos de Razonamiento

► Prompting: Zero, one, few-shot learning

► Sistemas RAG

► Bases de datos vectoriales

► Construir aplicaciones

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

3

Tecnologías clave

► Representación vectorial:

– One-hot-enconding -> Bag of Words -> Embeddings

► Procesamiento con redes neuronales:

– Sequence to Sequence (encoder-decoder)
– RNN -> LSTM -> Transformers

► Grandes modelos de lenguaje

– Pre-entrenamiento
– Fine-tunning

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

4

Zero, one, few-shot learning

► Few-shot learning

► One-shot learning

► Zero-shot learning

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

5

Modelos INSTRUCT

► Parten de un modelo BASEs

► Entrenamiento FINE-TUNNING basado en instrucciones:

► Ejemplo:

– INPUT:
•

“Give three tips for staying healthy”

– EXPECTED-OUTPUT:

•

“1.Eat a balanced diet and make sure to include plenty of
fruits and vegetables. 2. Exercise regularly to keep your
body active and strong. 3. Get enough sleep and maintain
a consistent sleep schedule.”

https://huggingface.co/datasets/tatsu-lab/alpaca/

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

6

Large Reasoning Models (LRM)

► Xu, F., Hao, Q., Zong, Z., Wang, J., Zhang, Y., Wang, J., ... & Li, Y. (2025).

Towards Large Reasoning Models: A Survey of Reinforced Reasoning with
Large Language Models. arXiv preprint arXiv:2501.09686.

The success of these methods demonstrates that while LLMs possess inherent
reasoning abilities, their full potential can be unlocked through careful guidance and
structure in the prompting process.

► Shojaee, P., Mirzadeh, I., Alizadeh, K., Horton, M., Bengio, S., & Farajtabar, M.

(2025). The illusion of thinking: Understanding the strengths and limitations of
reasoning models via the lens of problem complexity. arXiv preprint
arXiv:2506.06941.

(1) Low complexity tasks where standard models surprisingly outperform LRMs, (2)
medium-complexity tasks where additional thinking in LRMs demonstrates advantage,
and (3) high-complexity tasks where both models experience complete collapse. We
found that LRMs have limitations in exact computation: they fail to use explicit
algorithms and reason inconsistently across puzzles

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

7

Fine tunning vs prompting

► ¿Cuándo usar cada estrategia?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

8

Sistemas RAG

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

9

Ejemplo de sistema RAG.

1. Una consulta del usuario

entrando al sistema.

2. Un módulo de recuperación

que busca en una base de

datos de conocimientos.

3. Un módulo de generación de

lenguaje (LLM) que recibe la

consulta y la información

recuperada.

4. Una respuesta generada que

sale del sistema, combinando

la información recuperada y el

conocimiento del LLM.

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

10

Bases de Datos Vectoriales

► Motores de BBDD dedicados como MILVUS

(https://milvus.io/docs/es/quickstart.md)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

11

Bases de Datos Vectoriales

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

12

Bases de Datos Vectoriales

► Sentence Transformers para Sentence Embeddings

(https://huggingface.co/models?pipeline_tag=sentence-similarity)

► Motores de BBDD dedicados como MILVUS

(https://milvus.io/docs/es/quickstart.md)

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

13

Creación de Aplicaciones con PLN

► Estudio de temáticas en podcast, y red de relaciones entre ellos

– ¿qué necesitamos?
– ¿cuál sería la arquitectura del programa?

► Predicción de tasa de conversión en call-center

– ¿qué necesitamos?
– ¿cuál sería la arquitectura del programa?

► Análisis del discurso de odio en noticias de prensa

– ¿qué necesitamos?
– ¿cuál sería la arquitectura del programa?

► Caracterización del uso del lenguaje según grupos de alumnos

– ¿qué necesitamos?
– ¿cuál sería la arquitectura del programa?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

14

En resumen

► Debemos dedicir si queremos una APP basada en prompting o en fine-tunning

► La arquitectura RAG aporta contexto a la construcción de la salida

► Las bases de datos vectoriales permiten mayor rapidez y precisión a la hora de

buscar el contexto en los sistemas RAG

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

15

Referencia bibliográfica clave

► Speech and Language Processing (3rd ed. draft)

Dan Jurafsky and James H. Martin

► https://web.stanford.edu/~jurafsky/slp3/

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

16

En la próxima semana

¿Cómo se construye un agente conversacional?

Procesamiento del Lenguaje Natural – Luis de la Fuente Valentín

17

www.unir.net

Caso práctico ejemplo de examen, se debe describir el sistema, analizar dataset, caracterizar dataset, validar sistema, dibujar diagrama de arquitectura y propuesta de mejora. Se valorará que la solución tenga sentido técnicos y esté respaldada por justificaciones. No existe una respuesta correcta, se quiere evaluar que el alumno comprende el temario y que sabe decidir.

-   ﻿﻿Estudio de temáticas en podcast, y red de relaciones entre ellos ¿qué necesitamos? ¿cuál sería la arquitectura del programa?
-   ﻿﻿Predicción de tasa de conversión en call-center ¿qué necesitamos? ¿cuál sería la arquitectura del programa?
-   ﻿﻿Análisis del discurso de odio en noticias de prensa ¿qué necesitamos? ¿cuál sería la arquitectura del programa?
-   ﻿﻿Caracterización del uso del lenguaje según grupos de alumnos ¿qué necesitamos? ¿cuál sería la arquitectura del programa?