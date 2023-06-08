## Red Neuronal o Artificial Neural Network ANN

Es un modelo de computación cuya estructura de capas se asemeja a la estructura interconectada de las neuronas en el cerebro, con capas de nodos conectados. Una red neuronal puede aprender de los datos, de manera que se puede entrenar para que reconozca patrones, clasifique datos y pronostique eventos futuros.

Las redes neuronales descomponen las entradas en capas de abstracción. Se pueden entrenar con muchos ejemplos para que reconozcan patrones de voz o en imágenes, por ejemplo, igual que el cerebro humano. Su comportamiento está definido por la forma en que se conectan sus elementos individuales, así como por la importancia (o ponderación) de dichas conexiones. Estas ponderaciones se ajustan automáticamente durante el entrenamiento de acuerdo con una regla de aprendizaje especificada hasta que la red neuronal lleva a cabo la tarea deseada correctamente.


### Funcionamiento de una red neuronal

Una red neuronal combina diversas capas de procesamiento y utiliza elementos simples que operan en paralelo, y están inspiradas en los sistemas nerviosos biológicos. Consta de una capa de entrada, una o varias capas ocultas y una capa de salida. Las capas están interconectadas mediante nodos, o neuronas; cada capa utiliza la salida de la capa anterior como entrada.

![Image of Mathworks](https://la.mathworks.com/discovery/neural-network/_jcr_content/mainParsys3/discoverysubsection_1001794945/mainParsys3/image.adapt.full.medium.svg/1681892840122.svg)

Figura 1. Arquitectura típica de una red neuronal.

### Usos de una red neuronal

Esta tecnología sea ido implementando progresivamente en diferentes ámbitos, por ejemplo, en predicción de comportamiento del cliente, mercadotecnia dirigida, creación de contenidos, pronóstico de demanda de producción, pronóstico de venta de productos, fluctuación de valor de la moneda, detección de fraudes financieros, conducción autónoma de vehículos, seguridad por análisis de imagen, enrutamiento inteligente para entrega de mensajería, asistentes de voz tipo Siri o Alexa, entre otros. 

![Image of Tesla](https://i.ytimg.com/vi/Vn-H2VpXAhM/maxresdefault.jpg)

Figura 2. Sistema de conduccion atónomo de Tesla.


### Modelo de una red neuronal

Las redes neuronales son modelos matemáticos que intentan reproducir el comportamiento del cerebro humano. El principal objetivo de este modelo es la construcción de sistemas capaces de presentar un cierto comportamiento inteligente. Esto implica la capacidad de aprender a realizar una determinada tarea. 
Una red neuronal está compuesta de tres partes: Entrada, núcleo y salidas. 
La figura 3 muestra un esquema de una red neuronal artificial. 
Las entradas reciben los datos o parámetros que le permiten decidir a la neurona se estará activa o no, normalmente se presentan como 𝑥1, 𝑥2, … , 𝑥𝑛. 
Entre la entrada y el núcleo se tienen los pesos (𝑤1, 𝑤2, … , 𝑤𝑛), que representan la memoria de la red. 
En el núcleo se realizan todas las operaciones necesarias para determinar la salida de la neurona; el proceso que se realiza en el núcleo varía dependiendo de la red neuronal que se esté trabajando. 

![Image of Neurona](https://gjorge.files.wordpress.com/2007/08/nueva-imagen.png)

Figura 3. Elementos básicos de una red neuronal.

Las salidas devuelven la respuesta de la neurona, es decir se está activa o no, representadas comúnmente como 𝑦1, 𝑦2, … , 𝑦𝑛.

En el núcleo se realizan 3 tipos de operaciones para determinar la salida de la neurona que son: Regla de propagación, Función de activación y Función de salida. La regla de propagación, integra la información proveniente de las distintas neuronas artificiales y proporciona el valor del potencial postsináptico de la neurona i. La función de activación, provee el estado de activación actual de la neurona i. La función de salida, representa la salida actual de la neurona i.

Entrada y salida Las entradas y salidas de una neurona pueden ser clasificadas en dos grandes grupos, binarias o continuas. Las neuronas binarias, sólo admiten dos valores posibles. En general en este tipo de neurona se utilizan los siguientes dos alfabetos {0,1} o {-1,1}. Por su parte, las neuronas continuas admiten valores dentro de un determinado rango, que en general suele definirse como [-1, 1]. La selección del tipo de neurona a utilizar depende de la aplicación y del modelo a construir.


#### Estructura de una red neuronal

Las partes principales de una red neuronal son: neuronas de entradas, ocultas, salidas y las interconexiones entre las neuronas.

La siguiente figura muestra la estructura de una red neuronal artificial.

![Image of Estructura](https://www.scielo.cl/img/revistas/infotec/v31n1//0718-0764-infotec-31-01-273-gf1.png)

Figura 4. Estructura de una red neuronal.

Las neuronas de entrada son transparentes, es decir no realizan ningún proceso, sólo dejan pasar la información que se quiere manejar en la red.
Las neuronas ocultas reciben las entradas y tienen la función de proporcionar un mejor aprendizaje. Las neuronas ocultas pueden o no estar presentes en una red y su incorporación depende de dos factores: Primero la topología con la que se esté trabajando y segundo de la complejidad de los patrones que deben ser aprendidos por la red.
Cuando la red está formada por una única capa de neuronas, se le llama redes monocapa, y las neuronas que conforman dicha capa cumplen la función de neuronas de entrada y salida simultáneamente. Cuando la red está compuesta por dos o más capas hablamos de redes multicapa.

La siguiente figura muestra las regiones de decisión de una red neuronal de 1, 2 y 3 capas.

![Image of Multicapa](https://upload.wikimedia.org/wikipedia/commons/0/04/Perceptr%C3%B3nMulticapa.png)

Figura 5. Regiones de decisión.

Las neuronas de salida se encargan de proporcionar la salida del sistema indicado, según su aprendizaje, una respuesta correcta o incorrecta.
Las interconexiones son las sinapsis de la red, estas tienen asociadas un peso sináptico, y son direccionales.

Cuando la conexión se establece entre dos neuronas de una misma capa hablamos de conexiones laterales o conexiones intra-capa. Por el contrario, si la conexión se establece entre neuronas de distintas capas se la denomina conexión inter-capa. Si la conexión se produce en el sentido inverso al de entrada-salida la conexión se llama recurrente o realimentada.

Una vez definida el tipo de neurona que se utilizará en un modelo de redes neuronales artificiales es necesario definir la topología de la misma.

La organización y disposición de las neuronas dentro de una red neuronal se denomina topología, y viene dada por el número de capas, la cantidad de neuronas por capa, el grado de conectividad, y el tipo de conexión entre neuronas.
A su vez, hablamos de redes neuronales con conexión hacia delante (redes feedforward) cuando las interconexiones entre las distintas neuronas de la red siguen un único sentido, desde la entrada de la red hacia la salida de la misma. Cuando las interconexiones pueden ser tanto hacia delante como hacia atrás hablamos de redes recurrentes (redes feedback).

### Técnicas empleadas durante la fase de entrenamiento con redes neuronales

- Aprendizaje supervisado.
Las redes neuronales supervisadas se entrenan para producir las salidas deseadas como respuesta a entradas de muestra, por lo que resultan idóneas para modelar y controlar sistemas dinámicos, clasificar datos con ruido y predecir eventos futuros.
- Clasificación.
La clasificación es un tipo de machine learning supervisado en el que un algoritmo “aprende” a clasificar nuevas observaciones a partir de ejemplos de datos etiquetados.
- Regresión.
Los modelos de regresión describen la relación entre una variable de respuesta (salida) y una o varias variables de predicción (entrada).
- Reconocimiento de patrones.
Funciona mediante la clasificación de los datos de entrada en objetos o clases en función de características clave, ya sea mediante la clasificación supervisada o no supervisada.
- Aprendizaje no supervisado.
Las redes neuronales no supervisadas se entrenan permitiendo que la red neuronal se autoajuste continuamente a las nuevas entradas. Se emplean para inferir información a partir de conjuntos de datos que constan de datos de entrada sin respuestas etiquetadas. Se pueden utilizar para descubrir distribuciones naturales, categorías y relaciones entre categorías en los datos.
- Clustering.
El clustering es un enfoque de aprendizaje no supervisado en el cual se pueden emplear redes neuronales para el análisis de datos exploratorio a fin de localizar patrones ocultos o agrupaciones de datos. Este proceso implica la agrupación de datos por similitud. Entre las aplicaciones del análisis de clusters están el análisis de secuencias genéticas, la investigación de mercados y el reconocimiento de objetos.

## Problema elegido para implementar una red neuronal

Estimacion de aforo vehicular en la ciudad de Hermosillo para el año 2030, de acuerdo con datos de Hermosillo Como Vamos.


##### Fuentes consultadas

“¿Qué Es Una Red Neuronal?” ¿Qué Es Una Red Neuronal? - MATLAB Simulink, https://la.mathworks.com/discovery/neural-network.html. Accesado el 4 de junio 2023.

Toral-Barrera, Jamie Areli. Redes Neuronales. Universidad de Guadalajara (México). http://www.cucei.udg.mx/sites/default/files/pdf/toral_barrera_jamie_areli.pdf Accesado el 3 de junio 2023.

Orza, Patricia (2022). "Neural business applications of artificial neural networks". Levity AI GmbH, https://levity.ai/blog/business-applications-artificial-neural-networks. Accesadi el 4 de junio 2023.

