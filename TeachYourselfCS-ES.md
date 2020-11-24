# Enseñate Ciencias de la Computación

> Este documento es una traduccion de [TeachYourselfCS](https://teachyourselfcs.com), escrito por [Ozan Onay](https://twitter.com/oznova_) y [Myles Byrne](https://twitter.com/quackingduck). Para mas informacion acerca de esta traduccion, ir al [final del documento](#quien-es-el-traductor).

> Esta version es una traduccion de la ultima version de la original hecha en Mayo 2020.

Si eres un ingeniero autodidacta o un graduado de un bootcamp, te debes a ti mismo aprender ciencias de la computación. Menos mal y te puedes otorgar una educacion en estas sin necesidad de muchos años y una fortuna en un titulo💸.

Hay muchos recursos por alli, pero unos son mejores que otros. No necesitas otra lista de "200+ Cursos Online Gratis!". Necesitas respuestas a estas preguntas:

- **Cuales temas** debes aprender, y por que?

- Cual es **el mejor libro o clase** para un tema?

Esta guia es nuestro intento para darle una respuesta definitiva a esas preguntas.

## TL;DR: (Resumelo por favor)

Estudia todos los siguientes temas, en mas o menos el orden presentado, usando el libro sugerido o la serie de videos, pero idealmente ambos. Trata de estudiar 100-200 horas en cada tema, luego repasa tus favoritos a lo largo de tu carrera 🚀.

| Tema                                                                                          | Por que estudiarlo ?                                                                                                                                      | Libro                                                       | Videos                          |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------- |
| **[Programacion](#Programacion)**                                                             | No seas la persona que nunca entendio algo como la recursion.                                                                                             | _Structure and Interpretation of Computer Programs_         | Brian Harvey Berkeley CS 61A    |
| **[Arquitetura de Computadores](#arquitetura-de-computadores)**                               | Si no tienes un modelo mental solido sobre como un computador funciona realmente, entonces todas tus abstracciones de alto nivel se quebraran facilmente. | _Computer Systems: A Programmer's Perspective_              | Berkeley CS 61C                 |
| **[Algoritmos y Estructura de Datos](#algoritmos-y-estructura-de-datos)**                     | Si no sabes como usar estructuras de datos ubicuas como las pilas, colas, arboles, y grafos, no seras capaz de resolver problemas desafiantes.            | _The Algorithm Design Manual_                               | Clases de Steven Skiena         |
| **[Matemática para Ciencias de la computación](#matemática-para-ciencias-de-la-computacion)** | Las ciencias de la computación son basicamente una rama de las maetmaticas aplicadas, asi que aprender matematicas te dara una ventaja competitiva.       | _Mathematics for Computer Science_                          | Tom Leighton MIT 6.042J         |
| **[Sistemas Operativos](#sistemas-operativos)**                                               | La mayor parte del codigo que escribes es ejecutado por un sistema operativo, asi que deberias saber como ambos interactuan.                              | _Operating Systems: Three Easy Pieces_                      | Berkeley CS 162                 |
| **[Redes de Computadores](#redes-de-computadores)**                                           | El internet resulto ser una gran cuestion. Entiende como funciona para desbloquear todo su potencial                                                      | _Computer Networking: A Top-Down Approach_                  | Stanford CS 144                 |
| **[Base de Datos](#base-de-datos)**                                                           | Los datos son el centro de los programas mas importantes, pero muy pocos entienden como funcionan realmente los sistemas de bases de datos.               | _Readings in Database Systems_                              | Joe Hellerstein Berkeley CS 186 |
| **[Lenguajes y Compiladores](#lenguajes-y-compiladores)**                                     | Si entiendes como funcionan los lenguajes y los compiladores, entonces seras capaz de escribir mejor codigo y aprender nuevos lenguajes mas facilmente.   | _Crafting Interpreters_                                     | Curso de Alex Aiken en edX      |
| **[Sistemas Distribuidos](#sistemas-distribuidos)**                                           | Hoy en dia, la mayoria de los sistemas son sistemas distribuidos.                                                                                         | _Designing Data-Intensive Applications by Martin Kleppmann_ | MIT 6.824                       |

## Te parece demasiado?

Si la idea de aprender 9 temas a lo largo de varios años te parece abrumadora, te sugerimos enfocarte en dos libros: _Computer Systems: A Programmer's Perspective_ y _Designing Data-Intensive Applications_. En nuestra experiencia, estos dos libros proveen la mayor utilidad por tiempo invertido, especialmente para aquellos ingenieros autodidactas y graduados de bootcamps que trabajan en aplicaciones en red. Tambien pueden servir como un "delicioso abrebocas" para otros temas y recursos listados.

## Por que aprender Ciencias de la computación?

Existen 2 tipos de ingenieros de software: Aquellos que entienden bien las ciencias de la computación para trabajar en cosas desafiantes e innovativas, y aquellos que se las arreglan solo porque conocen una que otra herramienta de alto nivel.

Ambos se autodenominan como ingenieros de software, y ambos tienden a ganar salarios similares cuando comienzan sus carreras. Pero los ingenieros de Tipo 1 progresan a trabajo satisfactorio y bien remunerado a travez del tiempo, ya sea en trabajo commercialmente valioso o en proyectos innovadores de codigo abierto, liderazgo tecnico o contribuciones individuales de alta calidad.

> El sistema global de SMS maneja 20 billones de mensajes al dia. WhatsApp maneja 42 billones. Con 57 ingenieros. [pic.twitter.com/zZrtSIzhlR](https://t.co/zZrtSIzhlR)

> — Benedict Evans (@BenedictEvans) [2 de Febrero, 2016](https://twitter.com/BenedictEvans/status/694342874729545729)

Los ingenieros de Tipo 1 encuentran formas de aprender ciencias de la computación a profundidad, ya sea mediante medios convencionales o aprendiendo implacablemente a lo largo de sus carreras. Los ingenieros de Tipo 2 tipicamente se quedan en la superficie, aprendiendo herramientas y tecnologias en vez de sus fundamentos subyacientes, adquiriendo nuevas habilidades solo cuando los vientos de la moda tecnologica cambian.

Actualmente, el numero de personas entrando en la industria esta creciendo rapidamente, mientras el numero de profesionales en las ciencias de la computación se ha mantenido estatico. La oferta excesiva de ingenieros de Tipo 2 esta empezando a reducir sus oportunidades de empleo y los mantiene fuera de los trabajos mas satisfactorios de la industria. Ya sea que te estes esforzando por ser un ingeniero de Tipo 1 o simplemente quieras mayor seguridad laboral, aprender ciencias de la computación es el unico camino confiable.

> Lol oh pero lo estaban….[pic.twitter.com/XVNYlXAHar](https://t.co/XVNYlXAHar)

>

> — Jenna Bilotta (@jenna) [4 de Marzo, 2017](https://twitter.com/jenna/status/838161631662092289)

## Guia de Temas

### Programacion

La mayoria de programas de ciencias de la computación comienzan con una "introduccion" a la programacion. Las mejores versiones de estos cursos no ser orientan exclusivamente a novatos, pero tambien a aquellos que se perdieron de conceptos beneficiales y modelos de programacion mientras aprendian a programmar por primera vez.

Nuestra recomendacion estandar para este tema es el clasico _Structure and Interpretation of Computer Programs_, el cual esta disponible gratuitamente como un [libro](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html) y un [conjunto de clases de MIT](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/). A pesar de que esas clases son buenas, nuestra recomendacion son las clases de [Brian Harvey de SICP](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter) (para o curso 61A na universidade Berkeley). Estas son mas refinadas y mejor orientadas a nuevos estudiantes que las de MIT.

Recomendamos estudiar por lo menos los tres primeros capitulos de SICP y hacer los ejercicios. Para practica adicional, hacer algunos ejercicios de problemas de programacion como aquellos que aparecen en [exercism](http://exercism.io)

Desde que esta guia fue publicada por primera vez en 2016, una de las preguntas que mas se han preguntado ha sido si recomendamos unas versiones actualizadas de el curso 61A enseñadas por John DeNero, y/o el libro correspondiente, [Composing Programs](https://composingprograms.com/), el cual "sigue la tradicion de SICP" pero usa Python. Consideramos que los recuros de DeNero tabien son buenos, y algunos estudiantes terminaran prefiriendolo, pero aun asi sugerimos SICP, Scheme, y las clases de Brian Harvey como el primer recurso para revisar.

¿Por que? Porque SICP es unico en su habilidad--Al menos potencialmente-- de alterar tus creencias fundamentales sobre los computadores y la programacion. No todos experimentaran esto. Algunos odiaran el libro, otros no pasaran de las primeras paginas. Pero la potencial recompensa hace que intentarlo valga la pena.

Si no disfrutas SICP,intenta _Composing Programs_. Si eso tampoco te sirve, intenta [How To Design Programs](http://www.htdp.org/). Si ninguno de estos parece recompensar tu esfuerzo, tal vez sea una señal de que debes enfocarte en otros temas por un tiempo, y revisitar la disciplina de la programacion en un año o dos.

Finalmente, un punto a clarificar: Esta guia NO esta diseñada para aquellos que son nuevos en la programacion. Asumimos que eres un programador competente sin estudios en ciencias de la computación, buscando llenar vacios. El hecho de que hemos incluido una seccion sobre "programacion" es simplemente un recordatorio de que tal vez existen mas cosas que aprender. Para aquellos que nunca han programado antes, pero que les gustaria hacerlo, podrian preferir [esta guia](https://www.reddit.com/r/learnprogramming/wiki/faq#wiki_getting_started).

### Arquitetura de Computadores

La Arquitectura de Computadores --a veces llamada "Systemas Computacionales" o "Organizacion Computacional"--es una mirada importante a la computacion debajo de la superficie de software. En nuestra experiencia, es el area mas ignorada entre los ingenieros de software autodidactas.

Nuestro libro introductorio favorito es [**Computer Systems: A Programmer's Perspective**](http://csapp.cs.cmu.edu/3e/home.html), y una introduccion tipica a la arquitectura de computadoras usando el libro [cubriria](http://csapp.cs.cmu.edu/3e/courses.html) la mayor parte de los capitulos 1 al 6.

Amamos este libro por el enfoque practico y orientado a programadores. Aunque hay mucho mas alla de lo que cubre el libro, este sirve como un gran punto de partida para aquellos que les gustaria entender los sistemas computacionales primeramente para escribir **software** mas rapido, mas eficiente, y mas confiable.

Para aquellos que prefieren una introduccion mas gentil y un balance de hardware y software, sugerimos **The Elements of Computing Systems**, tambien conocido como "Nand2Tetris". Este es un libro ambicioso que intenta dar un entendimiento cohesivo sobre como todo funciona dentro de un computador. Cada capitulo consiste en construir una pequeña parte de todo el sistema, desde escribir puertas de logica basicas usando HDL, una CPU, un asemblador hasta una aplicacion del tamaño de un juego de Tetris.

Recomendamos leer los primeros seis capitulos del libro y completar los proyectos incluidos. Esto desarrollara tu entendimiento de la relacion entre la arquitectura de la maquina y el software que corre alli.

La primera mitad del libro (y todos sus proyectos), estan disponibles gratuitamente desde el sitio web oficial de [Nand2Tetris](https://www.nand2tetris.org/). Tambien esta disponbile como curso de [Coursera](https://www.coursera.org/learn/build-a-computer).

Buscando la simplicidad y la cohesion, Nand2Tetris intercambia la profunidad. Particularmente, dos conceptos muy importantes en la arquitectura de computadores moderna, como la jerarquia de memoria y el pipelining, estan casi totalmente ausentes del texto.

Una vez que te sientas comodo con el contenido de Nand2Tetris, sugerimos intentar Computer Systems: A Programmer's Perspective, o considerar [**Computer Organization and Design**](https://smile.amazon.com/Computer-Organization-Design-MIPS-Architecture/dp/0124077269/ref=sr_1_1?dchild=1&keywords=Computer+Organization+and+Design+MIPS+Edition%3A+The+Hardware%2FSoftware+Interface+%28The+Morgan+Kaufmann+Series+in+Computer+Architecture+and+Design%29+5th+Edition&qid=1606225161&sr=8-1) de Patterson y Hennessy, un excelente y clasico libro. No todas las secciones del libro son esenciales; sugerimos seguir el curso de [Berkeley CS61C](http://inst.eecs.berkeley.edu/~cs61c/sp15/) "Great Ideas in Computer Architecture" para lecturas especificas. Las notas de clase y los laboratorios estan disponible en linea, y las clases anteriores estan [en el Internet Archive](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_)

### Algoritmos y Estructura de Datos

Concordamos con que con decadas de sabiduria comun que estar familiarizados con algoritmos y estructuras de datos comune es unno de los aspectos mas empoderantes de una educaion en ciencias de la computacion. Este tambien es un gran lugar para entrenar la capacidad para resolver problemas, lo cual sera de gran beneficio en las otras areas de estudio.

Hay cientos de libros disponibles, pero nuestro favorito es [__The Algorithm Design Manual__](The Algorithm Design Manual) por Steven Skiena. El claramente ama la resolucion algoritmica de problemas y tipicamente es exitoso enf omentar el mismo entusiasmo en sus estudiantes y lectores. En nuestra opinion, los dos textos comunmente sugeridos (CLRS y Sedgewick) tienden a ser un poco densos en pruebas para aquellos que estan aprendiendo el material principalmente para mejorar sus habilidades de resolucion de problemas.

Para aquellos que prefieren videos, [Skiena generosamente proporciona los suyos en linea](https://www.youtube.com/watch?v=A2bFN3MyNDA&list=PLOtl7M3yp-DX32N0fVIyvn7ipWKNGmwpp). Tambien nos gusta el curso de Tim Roughgarden, disponible [en Coursera](https://www.coursera.org/specializations/algorithms) y en [su pagina](http://timroughgarden.org/videos.html). El que prefieras el estilo de Skiena o Roughgarden sera una cuestion de preferencia personal. De hecho, hay una docena de buenas alternativas, asi que si te llegas a encontrar una que te guste, te motivamos a quedarte con ella!

Para practicar, nuestra forma preferida es que los estudiantes resuelvan problemas en [Leetcode](https://leetcode.com/). Estos tienden a ser problemas interesantes con soluciones y discusiones incluidas. Tambien te ayudaran a evaluar tu progreso con preguntas que son comunmente usadas en entrevistas tecnicas en compañias de software mas competitivas. Sugerimos resolver alrededor de 100 problemas de leetcode al azar como parte de tus estudios.

Finalmente, recomendamos mucho [**How to Solve It**](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/) como una guia excelente y unica a la resolucion general de problemas; es tan aplicable a las ciencias de la computacion como a las matematicas.

### Matematicas para las Ciencias de la Computacion

De cierta forma, las ciencias de la computacion son una rama madura de las matematicas aplicadas. Mientras que agunos ingenieros de software intenan--En variados grados de exito--ignorarla, te motivamos a que te tomes el trabajo de estudiarla directamente. Hacerlo exitosamente te dara una enorme ventaja competativa sobre aquellos que no lo hagan.

El area mas relevante de las matematicas para las ciencias de la computacion es ampliamente llamada "matematicas discretas", donde "discreto" es lo opuesto de "continuo" y es vagamente una coleccion de temas interesantes de la matematica aplicada fuera del calculo. Dada la definicion vaga, no es significativo tratar de cubrir la totalidad de las "matematicas discretas". Una meta mas realista es tener un entendimiento funcional de la logica, combinatoria y probabilidad, teoria de conjuntos, teoria de grafos, y un poco de teoria de numeros relacionado con la criptografia. Algebra lineal es una area adicional que vale la pena estudiar, dada su importancia en los graficos de computadora y en machine learning.

Nuestro punto de partida sugerido para las matematicas discretas es el [conjunto de notas de László Lovász](http://www.cs.elte.hu/~lovasz/dmbook.ps). El profesor Lovász hizo un buen trabajo en hacer el contenido accesible e intuitivo, asi que este sirve como un punto de partida mejor que otros textos mas formales.

Para un estudio mas avanzado, sugerimos [**Mathematics for Computer Science**](https://courses.csail.mit.edu/6.042/spring17/mcs.pdf), las notas del tamaño de un libro del curso de MIT del mismo nombre. Los videos de ese curso estan [gratuitamente disponibles](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/), y son nuestra recomendacion para videos de matematiacs discretas.

Para algebra lineal, sugerimos empezar con la serie de videos [Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab), seguida del [libro](https://www.amazon.com/Introduction-Linear-Algebra-Gilbert-Strang/dp/0980232775/) y clases por [Gilber Strang](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/).

### Sistemas Operativos

_[Operating System Concepts]_(https://www.amazon.com/dp/1118063333/) y _[Modern Operating Systems](https://www.amazon.com/dp/013359162X/)_ son los libros "clasicos" sobre sistemas operativos. Ambos han atraido critisismos por su falta de claridad y general dificultad para los estudiantes.

_Operating Systems: Three Easy Pieces_ es una buena alternativa que esta (gratuitamente disponible en linea)[http://pages.cs.wisc.edu/~remzi/OSTEP/]. Particularmente nos gusta la estructura y legibilidad del libro, y sentimos que los ejercicios valen la pena.

Luego, te recomendamos explorar lsa decisiones de diseño de diferentes sistemas operativos, a travez de libros del tipo "Partes Internas de {Sistem Operativo}" como _[Lion's commentary on Unix](https://www.amazon.com/Lions-Commentary-Unix-John/dp/1573980137/)_, _[The Design and Implementation of the FreeBSD Operating System](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972/)_, y _[Mac OS X Internals](https://www.amazon.com/Mac-OS-Internals-Systems-Approach/dp/0321278542/)_. Para Linux, recomendamos el fantastico libro de Robert Love, [Linux Kernel Development](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468)

Una gran forma de consolidar tu entendimiento de los sistemas operativos es leer el codigo de un kernel pequeño y añadir funcionalidades. Una opcion es [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html), un puerto de Unix V6 a ANSI C y x86 mantenido para un curso en MIT. OSTEP tiene un apendice de (laboratorios potenciales de xv6)[http://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf] llenos de grandes ideas para projectos potenciales.

### Redes de Computadores

Dado que gran parte de la ingenieria de software es en servidores y clientes web, una de las areas de inmediato valor de las ciencias de la computacion es la de redes. Nuestros estudiantes autodidactas que metodicamente estudian redes encuentran que finalmente entienden conceptos, terminos, y protocolos que los habian rodeado por años.

Nuestro libro favorito para este tema es _[Computer Networking: A Top Down Approach](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)_. Los pequeños proyectos y ejercicios en el libro valen mucho la pena hacer, y nos gusta particularmente los "Wireshark labs" los cuales estan [generosamente en linea](http://www-net.cs.umass.edu/wireshark-labs/).

Para aquellos que prefieran videos, sugerimos el curso de Stanford _[Introduction to Computer Networking](https://www.youtube.com/playlist?list=PLvFG2xYBrYAQCyz4Wx3NPoYJOFjvU7g2Z)_ disponible previamente en la plataforma de MOOC de Stanford Lagunita, pero tristemente ahora solo se encuentra como playlists no oficiales en Youtube.

### Bases de datos

Toma mucho mas trabajo aprender de forma autodidacta acerca de sistemas de bases de datos que la mayoria de otros temas. Es un campo de estudio (post 1970s) relativamente nuevo con incentivos fuertemente comerciales para que las ideas se queden en secreto. Adicionalmente, muchos posibles autores de textos han preferido unirse o empezar compañias.

Debido a estas circunstancias, motivamos a los estudiantes evitar libros y empezar con las grabaciones de la clase [CS 186](https://www.youtube.com/user/CS186Berkeley/videos), el curso de Joe Hellerstein de bases de datos en Berkeley, y luego leer articulos.

Un articulo particularmente util para nuevos estudiantes es "[Architecture of a Database System](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf)", el cual provee un vistazo de alto nivel de como funcionan los sistemas de base de datos relacional (RDBMS). Esto servira como una base util para profundizar mas adelante.

_Readings in Database Systems_, mejor conocido como el ["Libro Rojo" de las bases de datos](http://www.redbook.io/), es una coleccion de articulos compilados y editados por Peter Bailis, Je Hellerstein y Michael Stonebraker. Para aquellos que han progresado mas alla del nivel del contenido de CS 186, el Libro Rojo debe ser la proxima parada.

Si realmente quieres usar un libro introductorio, te recomendamos _[Database Management Systems](https://smile.amazon.com/Database-Management-Systems-Raghu-Ramakrishnan/dp/0072465638/)_ por Ramakrishnan y Gehrke. Para estudiantes mas avanzados, el clasico de Jim Gray _[Transaction Processing: Concepts and Techniques](https://www.amazon.com/Transaction-Processing-Concepts-Techniques-Management/dp/1558601902)_ vale la pena, pero no recomendamos usar este como primer recurso.

Finalmente, el modelado de datos es un aspecto descuidado y pobremente enseñado al trabajar con bases de datos. Nuestro libro recomendado en el tema es _[Data and Reality: A Timeless Perspective on Perceiving and Managing Information in Our Imprecise World](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215)_

### Lenguajes y Compiladores

La mayoria de los programadores aprenden lenguajes, mientras que la mayoria de los que cientificos computacionales aprenden _sobre_ lenguajes. Esto les otorga una ventaja distintiva sobre el programador, incluso en el dominio de la programacion! Su conocimiento generaliza; son capaces de entender de forma mas profunda y rapida el funcionamiento de un nuevo lenguaje que aquellos que simplemente han aprendido lenguajes especificos.

Nuestro text introductorio recomendado es el excelente _[Crafting Interpreters](https://craftinginterpreters.com/contents.html)_ por By Nystrom, disponible gratuitamente en linea. Esta bien organizado, es altamente entretenido, y muy adecuado para aquellos cuyo objetivo principal es simplemente tener un mejor entendimiento de los lenguajes que usan y sus herramientas. Sugerimos tomar el tiempo necesario para trabajar todo el libro, intentando cualquiera de los "desafios" para sostener tu interes.

Una recomendacion mas tradicional es _[Compilers: Principles, Techniques & Tools](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)_, comunmente conocido como "El Libro del Dragon". Desafortunadamente, no esta diseñado para un estudio autodidacta, pero para ser usado como material de temas par auno o dos semestres.

Si decides usar el Libro del Dragon, es casi esencial que seas muy selectivo con los temas, idealmente con la ayuda de un mentor. De hecho, la forma en que sugerimos usar el Libro del Dragon, si asi lo deseas, es como una referencia suplementaria a una serie de videos. Nuestra recomendacion es la de _[Alex Aiken en edX](https://www.edx.org/course/compilers)_

### Sistemas Distribuidos

A medida que los computadores han incrementado en cantidad, tambien se han _propagado_. Donde antes negocios compraban mainframes grandes y mas grandes, ahora es normal para incluso aplicaciones muy pequeñas ejecutarse a traves de multiples maquinas. Los sistemas distribuidos son el estudio de como razonar sobre los trade-offs de implementarlos.

Nuestro libro sugerido para estudiar es _[Designing Data-Intensive Applications](https://smile.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable-ebook/dp/B06XPJML5D/)_. De lejos mejor que un libro tradicional, DDIA es un libro altamente legible diseñado para practicantes, el cual de alguna forma evita sacrificar profundidad o rigor.

Para aquellos que busquen un texto mas tradicional, o que prefieran uno que este gratuitamente disponible en linea, sugerimos _[Distributed Systems, 3rd Edition](https://www.distributed-systems.net/index.php/books/ds3/)_

Para aquellos que prefieran videos, _[6.824 DE MIT](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB)_ es un excelente curso enseñado por Robert Morris con lecturas disponibles [aqui](https://pdos.csail.mit.edu/6.824/schedule.html).

No importa cual sea tu eleccion de libro o recursos secondarios, estudiar sistemas distribuidos requiere absolutamente leer articulos. [Esta](http://dsrg.pdos.csail.mit.edu/papers/) es una buena lista, y recomendamos mucho antender tu seccion local de [Papers We Love](http://paperswelove.org/).

## Preguntas Frecuentes

### Quien es la audiencia ideal de esta guia?

Tenemos en mente que eres un ingeniero de software autodidacta, un graduado de un bootcamp, un estudiante de secundaria precoz, o un estudiante universitario buscando suplementar tu educacion formal con estudios adicionales. La pregunta de cuando embarcarse en este viaje es enteramente personal, pero la mayoria tiende a beneficiarse mas cuando ya tienen algo de experiencia profesional antes de estudiar de fondo la teoria de las ciencias de la computacion. Por ejemplo, nos dimos cuentas de que los estudiantes _les encanta_ aprender sobre sistemas de base de datos si ya han trabajado con bases de datos profesionalmente, o sobre redes de computador si han trabajado en un proyecto web o dos.

### Que hay de la IA/graficos/tema-de-moda-x?

Hemos tratado de limitar nuestra lista a temas de las ciencias de la computacion que sentimos que _todo practicante de la ingenieria de software_ deberia saber, sin importar la especialidad o la industria, pero con un enfoque en los sistemas. En nuestra experiencia, estos temas tendran el mas alto ROI (Retorno de la Inversion) para la gran mayoria de ingenieros autodidactas y graduados de bootcamps, y proveeran una solida fundacion para estudios adicionales. Subsecuentemente, estaras en una mejor posicion para leer libros o articulos y aprender los conceptos centrales sin mucha ayuda. Los siguientes son algunos puntos de partida para algunas "electivas" comunes.

- Para inteligencia artificial: Has el [curso de introduccion a la AI de Berkeley](http://ai.berkeley.edu/) mirando los videos y completando los excelentes proyectos de Pacman. Usa el _Artificial Intelligence: A Modern Approach_ de Russell y Norvig.

- Para machine learning: Has el curso de Andrew Ng de cursera. Se paciente, y asegurate de que entiendas los fundamentos antes de correr a los temas nuevos demoda como el deep learning.

- Para graficos de computadoras: Estudia el material del curso [CS 184 de Berkeley](http://inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html), y usa [Computer Graphics: Principles and Practice](https://www.amazon.com/Computer-Graphics-Principles-Practice-3rd/dp/0321399528) como libro de referencia.

### Que tan estricto es el orden sugerido?

Realisticamente, todos estos temas tienen una cantidad significativa de superposicion, y hacen referencia entre ellos ciclicamente. Toma por ejemplo la relacion entre las matematicas discretas y los algoritmos: aprender matematicas primero te ayudara a analizar y entender tus algoritmos en mayor profundidad, pero aprender algoritmos primero te dara mayor motivacion y contexto para las matematicas discretas. Idealmente, volveras a estos temas muchas veces durante tu carrera.

Como tal, nuestro orden sugerido esta alli para ayudarte a _empezar_... si tienes una razon de fondo para preferir una sequencia diferente, entonces adelante. Los "prerrequisitos" mas esneciales, en nuestra opinion, son: arquitectura de computadores antes de sistemas operativos o bases de datos, y redes y sistemas operativos antes de sistemas distribuidos.

### Como se compara esto al curriculo del Open Source Society o freeCodeCamp?

Cuando esta guia fue escrita en 2016, la guia de OSS tenia demasiados temas, sugeria recursos inferiores para muchos de ellos, y no explicaba la razon o la guia de porque o que aspectos de un curso en particular son valiosos. Tratamos de limitar nuestra lista de cursos a aquellos que _realmente deberias saber_ como ingeniero de software, sin importar de tu especialidad, y de ayudarte a entender porque cada curso esta incluido. En los años siguientes, la guia de OSS ha mejorado, pero aun pensamos que esta es un camino mas claro y cohesivo.

freeCodeCamp esta enfocado principalmente a la programacion, no las ciencias de la computacion. Para saber porque deberias aprender ciencias de la computacion, mira arriba. Si eres totalmente nuevo en la programcion, te sugerimos priorizar su aprendizaje, y luego retornar a esta guia en un año o dos.

### Que hay del lenguaje X?

Aprender un lenguaje de programacion particular esta en un plano totalmente distinto a aprender acerca de un area de las ciencias de la computacion -- aprender un lenguaje es mucho _mas facil_ y _menos valioso_. Si ya sabes unos cuantos elnguajes, te sugerimos simplemente seguir nuestra guia y encajar la adquisicion de un lenguaje en los huecos o vacios, o dejarlo para despues. Si has aprendido a programar bien (Como con _Structure and Interpetation of Computer Programs_), y especialmente si has aprendido sobre compiladores, te deberia tomar poco mas que un fin de semana para aprender lo esencial de un nuevo lenguaje, para luego despues podras aprender las librerias/herramienta/ecosistema en el trabajo.

### Que hay de tecnologia de moda X?

No hay ninguna tecnologia individual que sea lo suficientemente importante que aprender a usarla deba ser una parte central de tu educacion. Por otro lado, es bueno que te apasiona aprender acerca de ella. El truco esta en trabajar desde la tecnologia particular hacia el concepto o campo que le subyace, y aprender eso en profundidad antes de ver como tu tecnologia de moda encaja en la imagen mas grande.

### Por que sigues recomendando SICP?

Mira, solo intentalo. Algunas personas encuentran SICP una experiencia alucinante, caracteristica compartida por muy pocos otros libros. Si no te gusta, puedes intentar alguna otra cosa y, tal vez, volver a SICP mas tarde.

### Por que sigues recomendando el libro del Dragon?

El libro del Dragon sigue siendo el recurso mas completo sobre compiladores. Tiene algo de mala fama, tipicamente por sobreenfatizar ciertos temas que son menos mundanos para cubrir en detalle recientemente, como el parseo. La cuestion es que el proposito del libro nunca fue ser estudiado de tapa a tapa. Su proposito es el de proporcionar el suficiente material a un instructor para poder preparar un curso. De forma similar, un autodidacta puede escoger su propia aventura a traves del libro, o mejor aun seguir las sugerencias que las clases de cursos publicos han hecho en su estructura.

### Como puedo conseguir los libros a buen precio?

Muchos de los textos sugeridos estan disponibles en linea gratuitamente, gracias a la generosidad de sus autores. Para aquellos que no lo estan, sugerimos comprar copias usadas de ediciones antiguas. Como regla general, si han habido mas de un par de ediciones de un libro, es muy probable que la edicion mas vieja sea perfectamente adecuada. Es ciertamente improbable que la nueva edicion sea 10x mejor que la anterior, incluso si la diferencia en su precio lo es!

### Quien hizo esto?

Esta guia fue originalmente escrita por [Oz Nova](https://twitter.com/oznova_) y [Myles Byrne](https://twitter.com/quackingduck), con actualizaciones en 2020 hechas por Oz. Esta basada en nuestra experiencia enseñando fundamentos de ciencias computacionales a mas de 1000 ingenieros mayormente auto educados y graduados de bootcamp en pequeños grupos en San Francisco y en linea. Gracias a todos nuestros estudiantes por su feedback continuo en recursos para el auto aprendizaje.

Estamos muy confiados en que te puedes enseñar todo lo que esta arriba, asumiendo que hay suficiente tiempo y motivacion. Pero si prefieres un programa mas intensivo, estructurado, y encabezado por un instructor, tal vez te interesen nuestro programa [Intensivo de Ciencias de la Computacion](https://bradfieldcs.com/csi/). [NO](https://ozwrites.com/masters/) sugerimos conseguir una maestria.

### Quien es el traductor?

Soy James Archbold, un desarrollador frontend Colombiano trabajando actualmente en Elemento 43. Esta es una guia que decidi traducir para que las personas que son mayormente autodidactas o que quieren aprender por su cuenta tengan una mejor idea y estructura sobre como aprender estos temas.

Todos los libros que referencie tienen links a su version gratuita online o su libro en amazon. Es posible que algunos de estos tengan traducciones oficiales o no oficiales. Mas adelante, incluire links a aquellos libros que tengan traducciones y esten disponibles en linea o en amazon.

Si quieres hacer alguna recomendacion, correccion, o aclaracion, sientete libre de comunicarte conmigo o hacer un pull request con los cambios que sean necesarios.

Feliz aprendizaje!
