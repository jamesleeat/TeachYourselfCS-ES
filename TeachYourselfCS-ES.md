# Enséñate Ciencias de la Computación

> Este documento es una traducción de [TeachYourselfCS](https://teachyourselfcs.com), escrito por [Ozan Onay](https://twitter.com/oznova_) y [Myles Byrne](https://twitter.com/quackingduck). Para más información acerca de esta traducción, ir al [final del documento](#quien-es-el-traductor).

> Esta versión es una traducción de la última versión de la original hecha en Mayo 2020.

Si eres un ingeniero autodidacta o un graduado de un bootcamp, te mereces aprender por ti mismo ciencias de la computación. Afortunadamente puedes obtener una educación de alta calidad sin necesidad de invertir muchos años ni una fortuna en un título de Pregrado 💸.

Existen muchos recursos en internet, pero unos definitivamente mejores que otros. No necesitas otra lista de "200+ Cursos Online Gratis!". Necesitas respuestas a las siguientes preguntas:

- ¿**Qué temas** debes aprender, y por qué?

- ¿Cuál es **el mejor libro o clase** para un tema?

Esta guía es nuestro intento para darle una respuesta definitiva a esas preguntas.

## TL;DR: (Resúmelo por favor)

Estudia todos los siguientes temas, en más o menos el orden presentado, usando el libro sugerido o la serie de videos, idealmente ambos. Trata de estudiar 100-200 horas en cada tema, luego repasa tus temas preferidos a lo largo de tu carrera 🚀.

| Tema                                                                                          | ¿Por qué estudiarlo ?                                                                                                                                      | Libro                                                       | Videos                          |
| --------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------- |
| **[Programación](#programación)**                                                             | No seas la persona que nunca entendió algo como la recursión.                                                                                             | _Structure and Interpretation of Computer Programs_         | Brian Harvey Berkeley CS 61A    |
| **[Arquitectura de Computadores](#arquitectura-de-computadores)**                               | Si no tienes un modelo mental sólido sobre cómo un computador funciona realmente, entonces todas tus abstracciones de alto nivel se quebrarán fácilmente. | _Computer Systems: A Programmer's Perspective_              | Berkeley CS 61C                 |
| **[Algoritmos y Estructura de Datos](#algoritmos-y-estructura-de-datos)**                     | Si no sabes como usar estructuras de datos ubicuas como las pilas, colas, árboles, y grafos, no serás capaz de resolver problemas desafiantes.            | _The Algorithm Design Manual_                               | Clases de Steven Skiena         |
| **[Matemáticas para Ciencias de la computación](#matemáticas-para-ciencias-de-la-computación)** | Las ciencias de la computación son básicamente una rama de las matemáticas aplicadas, así que aprender matemáticas te dará una ventaja competitiva.       | _Mathematics for Computer Science_                          | Tom Leighton MIT 6.042J         |
| **[Sistemas Operativos](#sistemas-operativos)**                                               | La mayor parte del código que escribes es ejecutado por un sistema operativo, así que deberías saber cómo ambos interactúan.                              | _Operating Systems: Three Easy Pieces_                      | Berkeley CS 162                 |
| **[Redes de Computadores](#redes-de-computadores)**                                           | El internet resultó ser una gran cuestión. Entiende cómo funciona para desbloquear todo su potencial                                                      | _Computer Networking: A Top-Down Approach_                  | Stanford CS 144                 |
| **[Base de Datos](#bases-de-datos)**                                                           | Los datos son el centro de los programas más importantes, pero muy pocos entienden cómo funcionan realmente los sistemas de bases de datos.               | _Readings in Database Systems_                              | Joe Hellerstein Berkeley CS 186 |
| **[Lenguajes y Compiladores](#lenguajes-y-compiladores)**                                     | Si entiendes cómo funcionan los lenguajes y los compiladores, entonces serás capaz de escribir mejor código y aprender nuevos lenguajes más fácilmente.   | _Crafting Interpreters_                                     | Curso de Alex Aiken en edX      |
| **[Sistemas Distribuidos](#sistemas-distribuidos)**                                           | Hoy en día, la mayoría de los sistemas son sistemas distribuidos.                                                                                         | _Designing Data-Intensive Applications by Martin Kleppmann_ | MIT 6.824                       |

## ¿Te parece demasiado?

Si la idea de aprender 9 temas a lo largo de varios años te parece abrumadora, te sugerimos enfocarte en dos libros: _Computer Systems: A Programmer 's Perspective_ y _Designing Data-Intensive Applications_. En nuestra experiencia, estos dos libros proveen la mayor utilidad por tiempo invertido, especialmente para aquellos ingenieros autodidactas y graduados de bootcamps que trabajan en aplicaciones en red. También pueden servir como un "delicioso abrebocas" para otros temas y recursos listados.

## ¿Por qué aprender Ciencias de la computación?

Existen 2 tipos de ingenieros de software: Aquellos que entienden bien las ciencias de la computación para trabajar en cosas desafiantes e innovativas, y aquellos que se las arreglan solo porque conocen una que otra herramienta de alto nivel.

Ambos se autodenominan como ingenieros de software, y ambos tienden a ganar salarios similares cuando comienzan sus carreras. Pero los ingenieros de Tipo 1 progresan a trabajo satisfactorio y bien remunerado a través del tiempo, ya sea en trabajo comercialmente valioso o en proyectos innovadores de código abierto, liderazgo técnico o contribuciones individuales de alta calidad.

> El sistema global de SMS maneja 20 billones de mensajes al día. WhatsApp maneja 42 billones. Con 57 ingenieros. [pic.twitter.com/zZrtSIzhlR](https://t.co/zZrtSIzhlR)

> — Benedict Evans (@BenedictEvans) [2 de Febrero, 2016](https://twitter.com/BenedictEvans/status/694342874729545729)

Los ingenieros de Tipo 1 encuentran formas de aprender ciencias de la computación a profundidad, ya sea mediante medios convencionales o aprendiendo implacablemente a lo largo de sus carreras. Los ingenieros de Tipo 2 típicamente se quedan en la superficie, aprendiendo herramientas y tecnologías en vez de sus fundamentos subyacentes, adquiriendo nuevas habilidades sólo cuando los vientos de la moda tecnológica cambian.

Actualmente, el número de personas entrando en la industria está creciendo rápidamente, mientras el número de profesionales en las ciencias de la computación se ha mantenido estático. La oferta excesiva de ingenieros de Tipo 2 está empezando a reducir sus oportunidades de empleo y los mantiene fuera de los trabajos más satisfactorios de la industria. Ya sea que te estés esforzando por ser un ingeniero de Tipo 1 o simplemente quieras mayor seguridad laboral, aprender ciencias de la computación es el único camino confiable.

> Lol oh pero lo estaban….[pic.twitter.com/XVNYlXAHar](https://t.co/XVNYlXAHar)

>

> — Jenna Bilotta (@jenna) [4 de Marzo, 2017](https://twitter.com/jenna/status/838161631662092289)

## Guía de Temas

### Programación

La mayoría de programas de ciencias de la computación comienzan con una "introducción" a la programación. Las mejores versiones de estos cursos no se orientan exclusivamente a novatos, sino también a aquellos que se perdieron de conceptos beneficiosos y modelos de programación mientras aprenden a programar por primera vez.

Nuestra recomendación estándar para este tema es el clásico _Structure and Interpretation of Computer Programs_, el cual está disponible gratuitamente como un [libro](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html) y un [conjunto de clases de MIT](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/). A pesar de que esas clases son buenas, nuestra recomendación son las clases de [Brian Harvey de SICP](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter). Estas son más refinadas y mejor orientadas a nuevos estudiantes que las de MIT.

Recomendamos estudiar por lo menos los tres primeros capítulos de SICP y hacer los ejercicios. Para práctica adicional, hacer algunos ejercicios de problemas de programación como aquellos que aparecen en [exercism](http://exercism.io)

Desde que esta guía fue publicada por primera vez en 2016, una de las preguntas que más se han preguntado ha sido si recomendamos unas versiones actualizadas de el curso 61A enseñadas por John DeNero, y/o el libro correspondiente, [Composing Programs](https://composingprograms.com/), el cual "sigue la tradición de SICP" pero usa Python. Consideramos que los recursos de DeNero también son buenos, y algunos estudiantes terminarán prefiriendo, pero aún así sugerimos SICP, Scheme, y las clases de Brian Harvey como el primer recurso para revisar.

¿Por qué? Porque SICP es único en su habilidad--Al menos potencialmente-- de alterar tus creencias fundamentales sobre los computadores y la programación. No todos experimentarán esto. Algunos odiarán el libro, otros no pasarán de las primeras páginas. Pero la potencial recompensa hace que intentarlo valga la pena.

Si no disfrutas SICP,intenta _Composing Programs_. Si eso tampoco te sirve, intenta [How To Design Programs](http://www.htdp.org/). Si ninguno de estos parece recompensar tu esfuerzo, tal vez sea una señal de que debes enfocarte en otros temas por un tiempo, y revisar la disciplina de la programación en un año o dos.

Finalmente, un punto a clarificar: Esta guía NO está diseñada para aquellos que son nuevos en la programación. Asumimos que eres un programador competente sin estudios en ciencias de la computación, buscando llenar vacíos. El hecho de que hemos incluido una sección sobre "programación" es simplemente un recordatorio de que tal vez existen más cosas que aprender. Para aquellos que nunca han programado antes, pero que les gustaría hacerlo, podrían preferir [esta guía](https://www.reddit.com/r/learnprogramming/wiki/faq#wiki_getting_started).

### Arquitectura de Computadores

La Arquitectura de Computadores --a veces llamada "Sistemas Computacionales" o "Organización Computacional"--es una mirada importante a la computación debajo de la superficie de software. En nuestra experiencia, es el área más ignorada entre los ingenieros de software autodidactas.

Nuestro libro introductorio favorito es [**Computer Systems: A Programmer's Perspective**](http://csapp.cs.cmu.edu/3e/home.html), y una introducción típica a la arquitectura de computadoras usando el libro [cubriria](http://csapp.cs.cmu.edu/3e/courses.html) la mayor parte de los capítulos 1 al 6.

Amamos este libro por el enfoque práctico y orientado a programadores. Aunque hay mucho más allá de lo que cubre el libro, éste sirve como un gran punto de partida para aquellos que les gustaría entender los sistemas computacionales primeramente para escribir **software** más rápido, más eficiente, y más confiable.

Para aquellos que prefieren una introducción más gentil y un balance de hardware y software, sugerimos **The Elements of Computing Systems**, también conocido como "Nand2Tetris". Este es un libro ambicioso que intenta dar un entendimiento cohesivo sobre cómo todo funciona dentro de un computador. Cada capítulo consiste en construir una pequeña parte de todo el sistema, desde escribir puertas de lógica básicas usando HDL, una CPU, un ensamblador hasta una aplicación del tamaño de un juego de Tetris.

Recomendamos leer los primeros seis capítulos del libro y completar los proyectos incluidos. Esto desarrolla tu entendimiento de la relación entre la arquitectura de la máquina y el software que corre allí.

La primera mitad del libro (y todos sus proyectos), están disponibles gratuitamente desde el sitio web oficial de [Nand2Tetris](https://www.nand2tetris.org/). También está disponible como curso de [Coursera](https://www.coursera.org/learn/build-a-computer).

Buscando la simplicidad y la cohesión, Nand2Tetris intercambia la profundidad. Particularmente, dos conceptos muy importantes en la arquitectura de computadores moderna, como la jerarquía de memoria y el pipelining, están casi totalmente ausentes del texto.

Una vez que te sientas cómodo con el contenido de Nand2Tetris, sugerimos intentar Computer Systems: A Programmer's Perspective, o considerar [**Computer Organization and Design**](https://smile.amazon.com/Computer-Organization-Design-MIPS-Architecture/dp/0124077269/ref=sr_1_1?dchild=1&keywords=Computer+Organization+and+Design+MIPS+Edition%3A+The+Hardware%2FSoftware+Interface+%28The+Morgan+Kaufmann+Series+in+Computer+Architecture+and+Design%29+5th+Edition&qid=1606225161&sr=8-1) de Patterson y Hennessy, un excelente y clásico libro. No todas las secciones del libro son esenciales; sugerimos seguir el curso de [Berkeley CS61C](http://inst.eecs.berkeley.edu/~cs61c/sp15/) "Great Ideas in Computer Architecture" para lecturas específicas. Las notas de clase y los laboratorios están disponible en linea, y las clases anteriores están [en el Internet Archive](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_)

### Algoritmos y Estructura de Datos

Concordamos con que con décadas de sabiduría común que estar familiarizados con algoritmos y estructuras de datos común es uno de los aspectos más empoderantes de una educación en ciencias de la computación. Este también es un gran lugar para entrenar la capacidad para resolver problemas, lo cual será de gran beneficio en las otras áreas de estudio.

Hay cientos de libros disponibles, pero nuestro favorito es [__The Algorithm Design Manual__](The Algorithm Design Manual) por Steven Skiena. El claramente ama la resolución algorítmica de problemas y típicamente es exitoso en fomentar el mismo entusiasmo en sus estudiantes y lectores. En nuestra opinión, los dos textos comúnmente sugeridos (CLRS y Sedgewick) tienden a ser un poco densos en pruebas para aquellos que están aprendiendo el material principalmente para mejorar sus habilidades de resolución de problemas.

Para aquellos que prefieren videos, [Skiena generosamente proporciona los suyos en linea](https://www.youtube.com/watch?v=A2bFN3MyNDA&list=PLOtl7M3yp-DX32N0fVIyvn7ipWKNGmwpp). También nos gusta el curso de Tim Roughgarden, disponible [en Coursera](https://www.coursera.org/specializations/algorithms) y en [su pagina](http://timroughgarden.org/videos.html). El que prefieras el estilo de Skiena o Roughgarden será una cuestión de preferencia personal. De hecho, hay una docena de buenas alternativas, así que si te llegas a encontrar una que te guste, ¡te motivamos a quedarte con ella!

Para practicar, nuestra forma preferida es que los estudiantes resuelvan problemas en [Leetcode](https://leetcode.com/). Estos tienden a ser problemas interesantes con soluciones y discusiones incluidas. También te ayudarán a evaluar tu progreso con preguntas que son comúnmente usadas en entrevistas técnicas en compañías de software más competitivas. Sugerimos resolver alrededor de 100 problemas de leetcode al azar como parte de tus estudios.

Finalmente, recomendamos mucho [**How to Solve It**](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/) como una guía excelente y única a la resolución general de problemas; es tan aplicable a las ciencias de la computación como a las matemáticas.

### Matemáticas para Ciencias de la Computación

De cierta forma, las ciencias de la computación son una rama madura de las matemáticas aplicadas. Mientras que algunos ingenieros de software intentan--En variados grados de éxito--ignorarla, te motivamos a que te tomes el trabajo de estudiarla directamente. Hacerlo exitosamente te dará una enorme ventaja competitiva sobre aquellos que no lo hagan.

El área más relevante de las matemáticas para las ciencias de la computación es ampliamente llamada "matemáticas discretas", donde "discreto" es lo opuesto de "continuo" y es vagamente una colección de temas interesantes de la matemática aplicada fuera del cálculo. Dada la definición vaga, no es significativo tratar de cubrir la totalidad de las "matemáticas discretas". Una meta más realista es tener un entendimiento funcional de la lógica, combinatoria y probabilidad, teoría de conjuntos, teoría de grafos, y un poco de teoría de números relacionado con la criptografía. Álgebra lineal es un área adicional que vale la pena estudiar, dada su importancia en los gráficos de computadora y en machine learning.

Nuestro punto de partida sugerido para las matemáticas discretas es el [conjunto de notas de László Lovász](http://www.cs.elte.hu/~lovasz/dmbook.ps). El profesor Lovász hizo un buen trabajo en hacer el contenido accesible e intuitivo, así que éste sirve como un punto de partida mejor que otros textos más formales.

Para un estudio más avanzado, sugerimos [**Mathematics for Computer Science**](https://courses.csail.mit.edu/6.042/spring18/mcs.pdf), las notas del tamaño de un libro del curso de MIT del mismo nombre. Los videos de ese curso estan [gratuitamente disponibles](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/), y son nuestra recomendacion para videos de matematiacs discretas.

Para álgebra lineal, sugerimos empezar con la serie de videos [Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab), seguida del [libro](https://www.amazon.com/Introduction-Linear-Algebra-Gilbert-Strang/dp/0980232775/) y clases por [Gilber Strang](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/).

### Sistemas Operativos

_[Operating System Concepts](https://www.amazon.com/dp/1118063333/)_ y _[Modern Operating Systems](https://www.amazon.com/dp/013359162X/)_ son los libros "clásicos" sobre sistemas operativos. Ambos han atraído criticismos por su falta de claridad y general dificultad para los estudiantes.

_Operating Systems: Three Easy Pieces_ es una buena alternativa que esta [gratuitamente disponible en linea](http://pages.cs.wisc.edu/~remzi/OSTEP/). Particularmente nos gusta la estructura y legibilidad del libro, y sentimos que los ejercicios valen la pena.

Luego, te recomendamos explorar las decisiones de diseño de diferentes sistemas operativos, a través de libros del tipo "Partes Internas de {Sistem Operativo}" como _[Lion's commentary on Unix](https://www.amazon.com/Lions-Commentary-Unix-John/dp/1573980137/)_, _[The Design and Implementation of the FreeBSD Operating System](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972/)_, y _[Mac OS X Internals](https://www.amazon.com/Mac-OS-Internals-Systems-Approach/dp/0321278542/)_. Para Linux, recomendamos el fantástico libro de Robert Love, [Linux Kernel Development](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468)

Una gran forma de consolidar tu entendimiento de los sistemas operativos es leer el código de un kernel pequeño y añadir funcionalidades. Una opciÓn es [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html), un puerto de Unix V6 a ANSI C y x86 mantenido para un curso en MIT. OSTEP tiene un apendice de [laboratorios potenciales de xv6](http://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf) llenos de grandes ideas para projectos potenciales.

### Redes de Computadores

Dado que gran parte de la ingeniería de software es en servidores y clientes web, una de las áreas de inmediato valor de las ciencias de la computación es la de redes. Nuestros estudiantes autodidactas que metódicamente estudian redes encuentran que finalmente entienden conceptos, términos, y protocolos que los habían rodeado por años.

Nuestro libro favorito para este tema es _[Computer Networking: A Top Down Approach](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)_. Los pequeños proyectos y ejercicios en el libro valen mucho la pena hacer, y nos gusta particularmente los "Wireshark labs" los cuales están [generosamente en línea](http://www-net.cs.umass.edu/wireshark-labs/).

Para aquellos que prefieran videos, sugerimos el curso de Stanford _[Introduction to Computer Networking](https://www.youtube.com/playlist?list=PLvFG2xYBrYAQCyz4Wx3NPoYJOFjvU7g2Z)_ disponible previamente en la plataforma de MOOC de Stanford Lagunita, pero tristemente ahora solo se encuentra como playlists no oficiales en Youtube.

### Bases de datos

Toma mucho más trabajo aprender de forma autodidacta acerca de sistemas de bases de datos que la mayoría de otros temas. Es un campo de estudio (post 1970s) relativamente nuevo con incentivos fuertemente comerciales para que las ideas se queden en secreto. Adicionalmente, muchos posibles autores de textos han preferido unirse o empezar compañías.

Debido a estas circunstancias, motivamos a los estudiantes evitar libros y empezar con las grabaciones de la clase [CS 186](https://www.youtube.com/user/CS186Berkeley/videos), el curso de Joe Hellerstein de bases de datos en Berkeley, y luego leer artículos.

Un artículo particularmente útil para nuevos estudiantes es "[Architecture of a Database System](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf)", el cual provee un vistazo de alto nivel de cómo funcionan los sistemas de base de datos relacional (RDBMS). Esto servirá como una base útil para profundizar más adelante.

_Readings in Database Systems_, mejor conocido como el ["Libro Rojo" de las bases de datos](http://www.redbook.io/), es una colección de artículos compilados y editados por Peter Bailis, Je Hellerstein y Michael Stonebraker. Para aquellos que han progresado más allá del nivel del contenido de CS 186, el Libro Rojo debe ser la próxima parada.

Si realmente quieres usar un libro introductorio, te recomendamos _[Database Management Systems](https://smile.amazon.com/Database-Management-Systems-Raghu-Ramakrishnan/dp/0072465638/)_ por Ramakrishnan y Gehrke. Para estudiantes más avanzados, el clásico de Jim Gray _[Transaction Processing: Concepts and Techniques](https://www.amazon.com/Transaction-Processing-Concepts-Techniques-Management/dp/1558601902)_ vale la pena, pero no recomendamos usar este como primer recurso.

Finalmente, el modelado de datos es un aspecto descuidado y pobremente enseñado al trabajar con bases de datos. Nuestro libro recomendado en el tema es _[Data and Reality: A Timeless Perspective on Perceiving and Managing Information in Our Imprecise World](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215)_

### Lenguajes y Compiladores

La mayoría de los programadores aprenden lenguajes, mientras que la mayoría de los que científicos computacionales aprenden _sobre_ lenguajes. Esto les otorga una ventaja distintiva sobre el programador, incluso en el dominio de la programación! Su conocimiento generaliza; son capaces de entender de forma más profunda y rápida el funcionamiento de un nuevo lenguaje que aquellos que simplemente han aprendido lenguajes específicos.

Nuestro texto introductorio recomendado es el excelente _[Crafting Interpreters](https://craftinginterpreters.com/contents.html)_ por By Nystrom, disponible gratuitamente en línea. Está bien organizado, es altamente entretenido, y muy adecuado para aquellos cuyo objetivo principal es simplemente tener un mejor entendimiento de los lenguajes que usan y sus herramientas. Sugerimos tomar el tiempo necesario para trabajar todo el libro, intentando cualquiera de los "desafíos" para sostener tu interés.

Una recomendación más tradicional es _[Compilers: Principles, Techniques & Tools](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)_, comúnmente conocido como "El Libro del Dragón". Desafortunadamente, no está diseñado para un estudio autodidacta, pero para ser usado como material de temas por uno o dos semestres.

Si decides usar el Libro del Dragón, es casi esencial que seas muy selectivo con los temas, idealmente con la ayuda de un mentor. De hecho, la forma en que sugerimos usar el Libro del Dragón, si así lo deseas, es como una referencia suplementaria a una serie de videos. Nuestra recomendación es la de _[Alex Aiken en edX](https://www.edx.org/course/compilers)_

### Sistemas Distribuidos

A medida que los computadores han incrementado en cantidad, también se han _propagado_. Donde antes los negocios compraban mainframes grandes y más grandes, ahora es normal para incluso aplicaciones muy pequeñas ejecutarse a través de múltiples máquinas. Los sistemas distribuidos son el estudio de cómo razonar sobre los trade-offs de implementarlos.

Nuestro libro sugerido para estudiar es _[Designing Data-Intensive Applications](https://smile.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable-ebook/dp/B06XPJML5D/)_. De lejos mejor que un libro tradicional, DDIA es un libro altamente legible diseñado para practicantes, el cual de alguna forma evita sacrificar profundidad o rigor.

Para aquellos que busquen un texto más tradicional, o que prefieran uno que esté gratuitamente disponible en línea, sugerimos _[Distributed Systems, 3rd Edition](https://www.distributed-systems.net/index.php/books/ds3/)_

Para aquellos que prefieran videos, _[6.824 DE MIT](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB)_ es un excelente curso enseñado por Robert Morris con lecturas disponibles [aquí](https://pdos.csail.mit.edu/6.824/schedule.html).

No importa cuál sea tu elección de libro o recursos secundarios, estudiar sistemas distribuidos requiere absolutamente leer artículos. [Esta](http://dsrg.pdos.csail.mit.edu/papers/) es una buena lista, y recomendamos mucho atender tu sección local de [Papers We Love](http://paperswelove.org/).

## Preguntas Frecuentes

### ¿Quién es la audiencia ideal de esta guía?

Tenemos en mente que eres un ingeniero de software autodidacta, un graduado de un bootcamp, un estudiante de secundaria precoz, o un estudiante universitario buscando suplementar tu educación formal con estudios adicionales. La pregunta de cuándo embarcarse en este viaje es enteramente personal, pero la mayoría tiende a beneficiarse más cuando ya tienen algo de experiencia profesional antes de estudiar de fondo la teoría de las ciencias de la computación. Por ejemplo, nos dimos cuenta de que a los estudiantes _les encanta_ aprender sobre sistemas de base de datos si ya han trabajado con bases de datos profesionalmente, o sobre redes de computador si han trabajado en un proyecto web o dos.

### ¿Qué hay de la IA/gráficos/tema-de-moda-x?

Hemos tratado de limitar nuestra lista a temas de las ciencias de la computación que sentimos que _todo practicante de la ingeniería de software_ debería saber, sin importar la especialidad o la industria, pero con un enfoque en los sistemas. En nuestra experiencia, estos temas tendrán el más alto ROI (Retorno de la Inversión) para la gran mayoría de ingenieros autodidactas y graduados de bootcamps, y proveerán una sólida fundación para estudios adicionales. Subsecuentemente, estarás en una mejor posición para leer libros o artículos y aprender los conceptos centrales sin mucha ayuda. Los siguientes son algunos puntos de partida para algunas "electivas" comunes.

- Para inteligencia artificial: Realiza el [curso de introducción a la AI de Berkeley](http://ai.berkeley.edu/) mirando los videos y completando los excelentes proyectos de Pacman. Usa el _Artificial Intelligence: A Modern Approach_ de Russell y Norvig.

- Para machine learning: Has el curso de Andrew Ng de coursera. Sé paciente, y asegúrate de que entiendas los fundamentos antes de correr a los temas nuevos de moda como el deep learning.

- Para gráficos de computadoras: Estudia el material del curso [CS 184 de Berkeley](http://inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html), y usa [Computer Graphics: Principles and Practice](https://www.amazon.com/Computer-Graphics-Principles-Practice-3rd/dp/0321399528) como libro de referencia.

### ¿Qué tan estricto es el orden sugerido?

Realísticamente, todos estos temas tienen una cantidad significativa de superposición, y hacen referencia entre ellos cíclicamente. Toma por ejemplo la relación entre las matemáticas discretas y los algoritmos: aprender matemáticas primero te ayudará a analizar y entender tus algoritmos en mayor profundidad, pero aprender algoritmos primero te dará mayor motivación y contexto para las matemáticas discretas. Idealmente, volverás a estos temas muchas veces durante tu carrera.

Como tal, nuestro orden sugerido está allí para ayudarte a _empezar_... si tienes una razón de fondo para preferir una secuencia diferente, entonces adelante. Los "prerrequisitos" más esenciales, en nuestra opinión, son: arquitectura de computadores antes de sistemas operativos o bases de datos, y redes y sistemas operativos antes de sistemas distribuidos.

### ¿Cómo se compara esto al currículo del Open Source Society o freeCodeCamp?

Cuando esta guía fue escrita en 2016, la guía de OSS tenía demasiados temas, sugería recursos inferiores para muchos de ellos, y no explicaba la razón o la guía de porqué o qué aspectos de un curso en particular son valiosos. Tratamos de limitar nuestra lista de cursos a aquellos que _realmente deberías saber_ como ingeniero de software, sin importar de tu especialidad, y de ayudarte a entender porqué cada curso está incluido. En los años siguientes, la guía de OSS ha mejorado, pero aún pensamos que este es un camino más claro y cohesivo.

freeCodeCamp está enfocado principalmente a la programación, no a las ciencias de la computación. Para saber por qué deberías aprender ciencias de la computación, mira arriba. Si eres totalmente nuevo en la programación, te sugerimos priorizar su aprendizaje, y luego retornar a esta guía en un año o dos.

### ¿Qué hay del lenguaje X?

Aprender un lenguaje de programación particular está en un plano totalmente distinto a aprender acerca de un área de las ciencias de la computación -- aprender un lenguaje es mucho _más fácil_ y _menos valioso_. Si ya sabes unos cuantos lenguajes, te sugerimos simplemente seguir nuestra guía y encajar la adquisición de un lenguaje en los huecos o vacíos, o dejarlo para después. Si has aprendido a programar bien (Como con _Structure and Interpretation of Computer Programs_), y especialmente si has aprendido sobre compiladores, te debería tomar poco más que un fin de semana para aprender lo esencial de un nuevo lenguaje, para luego después podrás aprender las librerías/herramienta/ecosistema en el trabajo.

### ¿Qué hay de tecnología de moda X?

No hay ninguna tecnología individual que sea lo suficientemente importante que aprender a usarla deba ser una parte central de tu educación. Por otro lado, es bueno que te apasiona aprender acerca de ella. El truco está en trabajar desde la tecnología particular hacia el concepto o campo que le subyace, y aprender eso en profundidad antes de ver como tu tecnología de moda encaja en la imagen más grande.

### ¿Por qué sigues recomendando SICP?

Mira, solo inténtalo. Algunas personas encuentran SICP una experiencia alucinante, característica compartida por muy pocos otros libros. Si no te gusta, puedes intentar alguna otra cosa y, tal vez, volver a SICP más tarde.

### ¿Por qué sigues recomendando el libro del Dragón?

El libro del Dragón sigue siendo el recurso más completo sobre compiladores. Tiene algo de mala fama, típicamente por sobreenfatizar ciertos temas que son menos mundanos para cubrir en detalle recientemente, como el parseo. La cuestión es que el propósito del libro nunca fue ser estudiado de tapa a tapa. Su propósito es el de proporcionar el suficiente material a un instructor para poder preparar un curso. De forma similar, un autodidacta puede escoger su propia aventura a través del libro, o mejor aún seguir las sugerencias que las clases de cursos públicos han hecho en su estructura.

### ¿Cómo puedo conseguir los libros a buen precio?

Muchos de los textos sugeridos están disponibles en línea gratuitamente, gracias a la generosidad de sus autores. Para aquellos que no lo están, sugerimos comprar copias usadas de ediciones antiguas. Como regla general, si han habido más de un par de ediciones de un libro, es muy probable que la edición más vieja sea perfectamente adecuada. Es ciertamente improbable que la nueva edición sea 10x mejor que la anterior, incluso si la diferencia en su precio lo es!

### ¿Quién hizo esto?

Esta guía fue originalmente escrita por [Oz Nova](https://twitter.com/oznova_) y [Myles Byrne](https://twitter.com/quackingduck), con actualizaciones en 2020 hechas por Oz. Está basada en nuestra experiencia enseñando fundamentos de ciencias computacionales a más de 1000 ingenieros mayormente auto educados y graduados de bootcamp en pequeños grupos en San Francisco y en línea. Gracias a todos nuestros estudiantes por su feedback continuo en recursos para el auto aprendizaje.

Estamos muy confiados en que te puedes enseñar todo lo que está arriba, asumiendo que hay suficiente tiempo y motivación. Pero si prefieres un programa más intensivo, estructurado, y encabezado por un instructor, tal vez te interese nuestro programa [Intensivo de Ciencias de la Computación](https://bradfieldcs.com/csi/). [NO](https://ozwrites.com/masters/) sugerimos conseguir una maestría.

### ¿Quién es el traductor?

Soy [James Archbold](https://www.linkedin.com/in/james-archbold-6470b6a2/), un desarrollador frontend Colombiano trabajando actualmente en Elemento 43. Esta es una guía que decidí traducir para que las personas que son mayormente autodidactas o que quieren aprender por su cuenta tengan una mejor idea y estructura sobre cómo aprender estos temas.

Todos los libros que referencie tienen links a su versión gratuita online o su libro en amazon. Es posible que algunos de estos tengan traducciones oficiales o no oficiales. Más adelante, incluiré links a aquellos libros que tengan traducciones y estén disponibles en línea o en amazon.

Si quieres hacer alguna recomendación, corrección, o aclaración, siéntete libre de comunicarte conmigo o hacer un pull request con los cambios que sean necesarios.

Feliz aprendizaje!
