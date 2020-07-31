PROYECTO GLOSARIO DE FILOSOFÍA DE LA TÉCNICA
============================================

Entrada: Programa
-----------------

"Programa" tiene dos sentidos básicos en filosofía. Por un lado, se
habla de "programa" cuando se hace referencia a una serie de criterios y
valores que tienen por objetivo canalizar esfuerzos en una dirección
particular para explorar un campo de fenómenos o de posibilidades de
acción, mientras se articula una red de conceptos, teorías, modelos,
personas y sociedades para enfrentar la exploración y la explicación de
los fenómenos bajo investigación. Los trabajos de Imre Lakatos en
filosofía de la ciencia ---articulados bajo el rótulo de "metodología de
programas de investigación científica"--- constituyen uno de las
reflexiones más acabadas sobre esta forma de entender "programa", aunque
el término se suele emplear en distintas comunidades de manera mucho
menos específica, simplemente para refererise a los objetivos generales
que comparten distintas formas de abordar un problema. De esta manera se
habla de, e.g., "el programa formalista de Hilbert", "el programa
minimalista de Chomsky", "el programa de la naturaleza dual de los
artefactos técnicos", etc.

Por otro lado, lo que se entiende por "programa" es "programa de
computadora" y dado que es el sentido más usual en la reflexión sobre la
tecnología es la acepción sobre la que esta entrada del glosario se
enfoca. Entendido así, el término programa se refiere a un conjunto de
instrucciones que pueden ser interpretadas y llevadas a cabo por una
computadora para realizar una tarea. Así expuesta, la definción parece
sencilla. Cada una de sus partes, sin embargo, ha originado profundos
debates filosóficos que continuan en la actualidad; mientras que la
noción de programa ha permitido dar nueva luz sobre problemas
filosóficos que emergieron sin relación directa, como el problema
mente-cuerpo y la de la naturaleza de las entidades matemáticas.

Al hablar de computadora normalmente se hace una distinción tajante
entre el "software" o la "parte blanda" y el "hardware" o la parte
"física o dura". La primera está representada por un conjunto de
programas que ordenan el funcionamiento de los elementos físicos que
hacen al hardware, cumpliendo así distintas tareas o funciones, siendo
algunas de esas tareas la de simplemente permitir que otros programas se
ejecuten, esto es, que las instrucciones de dichos programas puedan ser
llevadas a cabo por otros programas o por el hardware "directamente" (el
ejemplo más claro es un sistema operativo). Aquí ya se puede observar
que la distinción entre hardware y software no es tan tajante y que
amerita una profunda revisión filosófica. Los programas se suelen ver
como software, en tanto son, por lo general, entidades abstractas ya que
en un sentido son independientes del medio físico que los soporta, lo
que les da cierta independencia, a su vez, del medio físico que los
puede implementar y ejecutar. Sin embargo, un programa también puede ser
"escrito" físicamente y ser solamente hardware, es decir, ser un
dispositivo físico que cumple exactamente la misma función que un
programa "abstracto" que puede ser implementado en cualquier otra
computadora. La virtud de la formulación de Turing sobre la computación
es precisamente la de hacer explícita esta intuición acerca de la
conexión entre el mundo matemático y el mundo físico, además de permitir
la existencia de la computadora programable gracias a su "máquina
universal", capaz de imitar cualquier otra máquina de computar (ver
máquina de Turing; computación). Así, en el reino de las entidades
matemáticas, los programas tienen un lugar muy particular debido a que
su conexión con el mundo físico debe ser explícita en ellos, en tanto es
eso lo que los vuelve un programa. Además, las instrucciones deben ser
factibles en la práctica, no solo en principio. Esto significa que en su
mismo diseño deben considerar el uso de los recursos computacionales
fundamentales: tiempo y espacio (memoria). Esto es precisamente lo que
deja ver a los programas como "instrucciones de diseño", en tanto
sugieren qué organización física particular tiene que tomar una máquina
si se desea que ésta produzca los resultados esperados en la
especificación del programa. Las especificaciones no necesariamente son
programas, en tanto no siempre consisten de instrucciones particulares a
seguir, sino más bien representan la dimensión normativa que define qué
es lo que se espera del programa, pero no la manera de lograr ese
resultado; de todas formas, un programa puede servir de especificación
para otro programa, aunque por lo general son sólo una definición de qué
*debe* cumplir un programa basado en tales especificaciones. Esto
también deja entrever cómo una arquitectura de computación particular
también funciona como una especificación, en tanto delimita la clase de
programas que pueden ejecutarse sobre ella. 
La arquitectura de von Neumann, introducida en 1945 en el *First draft of a report on the
EDVAC*, estandarizó el uso de una unidad de procesamiento central (CPU),
compuesta por una unidad de control y una unidad de lógica aritmética, y
es esta unidad la que interactúa con el "órgano" de memoria, en donde se
encuentran tanto los datos como las instrucciones del programa. Von
Neumann llega a este diseño implementando de una manera particular la
abstracción que habían propuesto Warren McCulloch y Walter Pitts en
1943, quienes demostraron que una red de neuronas idealizadas,
organizadas de manera particular, podían ser consideradas equivalentes a
una máquina universal de Turing, sin separación entre la memoria del
programa y la de las instrucciones. Las primeras computadoras, en
cambio, no se programaban, sino que se *diseñaban*, en tanto una
configuración particular del hardware la volvía una computadora
específica para realizar una tarea. Nuevamente, esto es una clara forma
de ver la conexión entre un programa y un diseño para una máquina. El
paso siguiente, y que es una condición necesaria para la idea actual de
programa y el avance tecnológico asociado, fue el de continuar el
proceso de abstracción y modularización que se encontraban implícitos
incluso en las formulaciones originales de la computación, pero que
cobraron nueva vida a medida que se podían implementar tecnológicamente.
Así es como una máquina se puede abstraer de su microconfiguración, en
tanto distintas microarquitecturas pueden cumplir con las
especificaciones de una máquina abstracta, definida como el conjunto de
instrucciones de las que puede ser capaz una CPU. Una serie particular
de esas instrucciones definidas en una secuencia correcta, en conjunto
con los datos sobre los que se aplican las instrucciones, constituyen un
programa. De aquí la famosa expresión "algoritmo + estructura de datos =
programa" (ver. algoritmo). La misma abstracción es la que permitió el
desarrollo de los lenguajes de programación, que facilitaron
inmensamente la tarea de transformar a los algoritmos en listas de
instrucciones para estas máquinas "abstractas" y luego permitieron
cerrar el ciclo: representar en el mismo lenguaje tanto datos como
algoritmos, efectivamente demostrando que una computadora puede verse
como una máquina que manipula símbolos que definen tipos de datos,
operaciones definidas sobre los tipos que actúa como intérprete (ver
código, computación).

Entonces un programa es esencialmente un "núcleo de funcionalidad" por
el que hay que entender la *causa* de un proceso dinámico que consiste
en las transformaciones de estados y la secuencia de operaciones que los
transforman. De acuerdo al nivel de abstracción en el que los estados se
expresen, estos podrán interpretarse *como* representaciones
particulares, en función de la tarea que se espera que el programa
efectivamente realice. Es importante notar aquí que la capacidad
representacional de un programa está determinada por el intérprete que
lo implementa efectivamente y que pueda reconocer un patrón de estados
como significativo para la tarea (ver patrón).

Las ciencias de la computación y la ingeniería de software tratan sobre
la creación de artefactos técnicos complejos basados en programas. Lo
que permite escalar en la complejidad es la manera en la que los
programas pueden interactuar entre sí, produciendo datos que son usados
por otros programas como valores de entrada o funcionando directamente
como submodulos dentro de un programa más grande. Esta modularización es
la que permite que haya "núcleos de funcionalidad" distribuidos, en
tanto los programas que interactúan por medio de una interfaz pueden
incluso no compartir la misma computadora. Aquí se puede pensar una
metáfora con un organismo biológico; de hecho, la analogía ha sido
epistémicamente fértil en ambas direcciones, tanto la biología como la
ciencia de la computación se han beneficiado del cambio de
representación que surge de entender a los organismos como sistemas
computacionales, y viceversa. Hoy en día el uso de la noción de
información es prácticamente ubicuo en biología y no sólo se limita al
programa genético (ver información). Antes del descubrimiento del
mecanismo de replicación del ADN, von Neumann demostró cómo era posible
pensar un programa cuya función fuera la de generar una copia de sí
mismo, efectivamente demostrando que no hay ninguna distinción en
principio entre las capacidades de una máquina y las de un organismo
vivo, simplemente se trata de distintas implementaciones de un mismo
principio. De hecho, la tesis de autoreplicación de autómatas de von
Neumann es el origen de una clase particular de programas de
computadoras cuyo objetivo es replicarse e infectar otros programas con
código propio: los virus.

La discusión filosófica alrededor de la noción de programa tiene dos
ejes principales. Uno es el de la naturaleza misma de los programas, en
tanto pueden ser vistos como análogos a entidades abstractas (como
matemáticas o lingüísticas) pero a su vez cercanas a la física o las
máquinas; junto con el problema de cuál es el rol que cumple la
semántica y las intenciones de los programadores para que un programa
sea, efectivamente un programa. El otro eje consiste en aplicar la
noción de programa para brindar nuevas aproximaciones a viejos problemas
filosóficos, desde cómo un cerebro puede dar lugar al comportamiento
inteligente y a la consciencia hasta sobre la naturaleza misma del
conocimiento, del azar, de la inferencia y de los objetos. En esta
última dirección, uno de los programas de investigación cuyas
consecuencias filosóficas y técnicas recién comienzan a ser exploradas
en profundidad es el de teoría algorítimica de la información, cuyas
bases fueron sentadas independientemente por Ray Salomonoff, Andrey
Kolmogorov y Gregori Chaitin en la década de 1960.

### Bibliografía sugerida

Colburn, T. 2000, *Philosophy and Computer Science*, Armonk, NY: M.E.
Sharp.

McCulloch, W. S., & Pitts, W. (1943). A logical calculus of the ideas
immanent in nervous activity. T*he bulletin of mathematical biophysics,
5*(4), 115--133.

Neumann, J. von. (1966). *Theory of self-reproducing automata* (A. W.
Burks, Ed.). University of Illinois Press.

Leeuwen, J. van (Ed.). (1990). *Handbook of theoretical computer
science*. Elsevier ; MIT Press.

Turner, R. (2018). *Computational Artifacts: Towards a Philosophy of
Computer Science*. Springer Berlin Heidelberg.

### Ver también

computación, información, algoritmo, recursividad, patrón, código,
datos, efectividad, objeto digital, máquina de Turing, inteligencia
artificial, interfaz.
