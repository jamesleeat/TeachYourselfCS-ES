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

Si la idea de aprender 9 temas a lo largo de varios años te parece abrumadora, te sugerimos enfocarte en dos libros: Computer Systems: A Programmer's Perspective y Designing Data-Intensive Applications. En nuestra experiencia, estos dos libros proveen la mayor utilidad por tiempo invertido, especialmente para aquellos ingenieros autodidactas y graduados de bootcamps que trabajan en aplicaciones en red. Tambien pueden servir como un "delicioso abrebocas" para otros temas y recursos listados.

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

Aos que acharem SICP muito dificil, recomendamos: _[How to Design Programs](http://www.htdp.org/)_. Para aqueles que acharam muito fácil: _[Concepts, Techniques, and Models of Computer Programming](https://smile.amazon.com/Concepts-Techniques-Models-Computer-Programming/dp/0262220695/)_.

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

_[Operating System Concepts](https://www.amazon.com/dp/1118063333/)_ e _[Modern Operating Systems](https://www.amazon.com/dp/013359162X/)_ são os livros “clássicos” quando se trata de sistemas operacionais. Os dois foram criticados pela sua escrita e estilo, e por ser o tipo de livro que tem 1000 páginas e tem suas edições revisadas depois de alguns anos para que você compre a nova edição.

_Operating Systems: Three Easy Pieces_ é uma boa alternativa que está disponível [online de graça](http://pages.cs.wisc.edu/~remzi/OSTEP/). Nós gostamos da estrutura do livro e achamos que os exercícios valem a pena.

Depois do OSTEP, encorajamos você a explorar as decisões de design de sistemas operacionais específicos, usando os livros do estilo “{nome do SO} internals”, como por exemplo _[Lion's commentary on Unix](https://www.amazon.com/Lions-Commentary-Unix-John/dp/1573980137/)_, _[The Design and Implementation of the FreeBSD Operating System](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972/)_, e _[Mac OS X Internals](https://www.amazon.com/Mac-OS-Internals-Systems-Approach/dp/0321278542/)_.

Uma ótima maneira de consolidar o seu entendimento é ler o código fonte de um kernel pequeno e adicionar novas funcionalidades. Uma ótima escolha é [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html), um porte do unix V6 para ANSI C e x86 mantido para um curso no MIT. OSTEP tem um apêndice de [xv6 labs](http://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf), cheio de ideias incríveis para possíveis projetos.

### Redes de Computadores

Já que a maioria da desenvolvimento de software acontece nos servidores e clientes, uma das áreas mais valiosas da ciência da computação são redes de computadores. Nossos alunos autodidatas que estudam redes metodicamente sentem que eles finalmente entendem conceitos, termos e protocolos que estavam ao redor deles por anos.

Nosso livro favorito do assunto é _[CRedes de Computadores e A Internet - Uma Abordagem Top-Down](https://www.saraiva.com.br/redes-de-computadores-e-a-internet-uma-abordagem-top-down-6-ed-2013-8223157/p)_. Os pequenos projetos e exercícios no livro valem muito a pena serem feitos, nós gostamos particularmente do “Wireshark labs”, que [eles deixam online](http://www-net.cs.umass.edu/wireshark-labs/).

Para os que preferem video aulas, sugerimos o curso [\_Introduction to Computer Networking ](https://lagunita.stanford.edu/courses/Engineering/Networking-SP/SelfPaced/about), disponível no MOOC lagunita.

O estudo de redes se beneficia mais através de grandes projetos do que através de pequenos exercícios. Alguns possíveis projetos são, por exemplo: um server HTTP, ou um chat baseado em UDP, uma [mini stack de TCP](http://jvns.ca/blog/2014/08/12/what-happens-if-you-write-a-tcp-stack-in-python/), um proxy, ou um balanceador de carga, e uma hash table distribuída.

> Você pode olhar para uma bola de cristal e ver o futuro. O que a internet vai ser no futuro vai ser definido pelo que a sociedade decidir.
>
> — Bob Kahn

[![Computer Networking: A Top-Down Approach](http://lojasaraiva.vteximg.com.br/arquivos/ids/12105154/1009651669.jpg?v=637142233019400000)](https://www.saraiva.com.br/redes-de-computadores-e-a-internet-uma-abordagem-top-down-6-ed-2013-8223157/p)

### Banco de Dados

Requer mais esforço aprender sobre sistemas de banco de dados do que a maioria dos outros tópicos. É uma área de estudo ainda muito imatura, com incentivos comerciais muito fortes para manter boas ideias em segredo. E ainda, muitos possíveis autores de livros didáticos preferem se juntar a uma ou criar uma empresa.

Dadas a ciscunstâncias nós sugerimos autodidatas ignorarem os livros e comecar com a [CS 186](https://archive.org/details/UCBerkeley_Course_Computer_Science_186), o curso de banco de dados da Berkeley e comecar a ler artigos logo após.

Um artigo em especial vale a pena ser mencionado a novos estudantes, o “[Architecture of a Database System](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf)” que unicamente dá uma visão abstrata de como sistemas de gerenciamento de banco de dados relacionais (SGBD) funcionam. Isso serve como esqueleto para futuros estudos.

_Readings in Database Systems_ mais conhecido como [“The Red Book”](http://www.redbook.io/) é uma colecao de artigos compilados e editados por Peter Bailis, Joe Hellerstein e Michael Stonebraker. para os que já progrediram além do nível da CS 186, o Red Book deve ser a sua próxima parada.

Se você insiste em usar um livro introdutório, sugerimos t _[Database Management Systems](https://smile.amazon.com/Database-Management-Systems-Raghu-Ramakrishnan/dp/0072465638/)_ por Ramakrishnan e Gehrke. Para estudantes mais avançados o clássico _[Transaction Processing: Concepts and Techniques](https://www.amazon.com/Transaction-Processing-Concepts-Techniques-Management/dp/1558601902)_ vale a pena, mas nós não incentivamos usá-lo como primeiro recurso.

É difícil consolidar os conceitos sem escrever uma quantidade considerável de código. Os alunos do CS 186 adicionaram recursos ao Spark, que é um projeto razoável, mas sugerimos escrever, do zero, um simples sistema de gerenciamento de banco de dados relacional. Não será cheio de recursos, mas será esclarecedor mesmo escrevendo a versão mais rudimentar de cada componente de um SGBD típico.

Por fim, a modelagem de dados é um aspecto negligenciado e mal ensinado sobre o trabalho com bancos de dados. Nosso livro sugerido é o _[Data and Reality: A Timeless Perspective on Perceiving and Managing Information in Our Imprecise World](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215)_.

### Linguagens e Compiladores

A maioria dos programadores aprende linguagens específicas, enquanto a maioria dos cientistas da computação aprendem _sobre_ linguagens. Isso dá ao cientista da computação uma vantagem distinta em relação ao programador, mesmo no domínio da programação! Seu conhecimento é generalizado; eles são capazes de entender o funcionamento de uma nova linguagem mais profunda e rapidamente do que os que aprendem linguagens específicas.

O texto introdutório padrão é o _[Compiladores: Princípios, Técnicas e Ferramentas](https://www.amazon.com.br/Compiladores-princ%C3%ADpios-ferramentas-Alfred-Aho/dp/8588639246)_, comumente chamado de "o Livro do Dragão" (Dragon Book). Infelizmente, ele não foi feito para auto-estudo, mas sim para que os professores escolham conteúdo suficiente para 1-2 semestres de curso. É essencial, então, que você escolha os tópicos a dedo, ou de preferência com a ajuda de um mentor.

Se você optar por usar o Dragon Book para seus estudos, recomendamos seguir alguma série de video aulas para ajudar com a estruturação do aprendizado, depois ir mergulhando mais profundamente no livro conforme necessário. Nossa reocmendação de curso online é [o do Alex Aiken, disponível na plataforma MOOC da Stanford Lagunita](https://lagunita.stanford.edu/courses/Engineering/Compilers/Fall2014/about).

Como possivel alternativa ao Dragon Book sugerimos _[Language Implementation Patterns](https://smile.amazon.com/Language-Implementation-Patterns-Domain-Specific-Programming/dp/193435645X/)_ por Terence Parr. Ele é escrito mais diretamente para o engenheiro de software praticante que pretende trabalhar em pequenos projetos de linguagem como como DSLs, o que pode torná-lo mais útil para você. É claro que, para isso, ele sacrifica bastante profundidade.

Para projetos, sugerimos escrever um compilador para uma linguagem didática simples como COOL, ou para um subconjunto de uma linguagem que lhe interesse. Quem achar esse projeto muito difícil pode começar com o [Make a Lisp](https://github.com/kanaka/mal), que te ajuda em cada etapa do projeto.

[![Compiladores: Princípios, Técnicas e Ferramentas](https://lojasaraiva.vteximg.com.br/arquivos/ids/7461119/522430.jpg?v=637087093968900000)](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811) [![Language Implementation Patterns](https://teachyourselfcs.com/parr.jpg)](https://smile.amazon.com/Language-Implementation-Patterns-Domain-Specific-Programming/dp/193435645X/)

> Não seja um programador padrão. Construa ferramentas para usuários e outros programadores. Tome nota histórica da indústria têxtil e siderúrgica: você quer construir máquinas e ferramentas, ou quer operar essas máquinas?
>
> — Ras Bodik no início de seu curso de compiladores

### Sistemas Distribuídos

Os computadores têm aumentado em número, e com isso eles também têm _se espalhado_. Enquanto que antigamente empresas adquiriam mainframes cada vez maiores, hoje em dia é típico que mesmo aplicações muito pequenas rodem em várias máquinas. Sistemas distribuídos é o estudo de como raciocinar os trade-offs envolvidos com a execução disso, uma habilidade cada vez mais importante.

Nosso livro sugerido é o _[Sistemas Distribuídos: Princípios e Paradigmas](https://www.amazon.com.br/Sistemas-distribu%C3%ADdos-princ%C3%ADpios-Andrew-Tanenbaum/dp/8576051427)_ de Maarten van Steen e Andrew Tanenbaum. A terceira edição está disponível online de graça, graças à generosidade de seus autores. Como sistemas distribuídos são um campo em constante mudança, nenhum livro didático servirá como guia definitivo, mas esse dá a melhor descrição dos assuntos mais fundamentais e consolidados que já vimos.

Um bom curso que tem alguns vídeos online é [6.824 do MIT](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB) (um curso de pós-graduação), mas infelizmente as gravações tem péssima qualidade de audio, e não está claro se as gravações foram autorizadas. _[Atualização @ Mar 2020: [os vídeos da palestra oficial do curso](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB) já foram publicados!]_

Não importa a escolha do livro ou de outros recursos, o estudo de sistemas distribuídos _exige_ a leitura de artigos. Uma boa lista pode ser achada aqui [aqui](http://dsrg.pdos.csail.mit.edu/papers/), e te incentivamos a participar do seu [Papers We Love](http://paperswelove.org/) local.

## Perguntas frequentes

### E quanto a IA/Computação Gráfica/etc?

Nós tentamos limitar nossa lista para tópicos que nós achamos essenciais para todos os engenheiros de software\_, independentemente da especialidade. Com essa fundação, você estará numa posição muito melhor para simplesmente usar livros e ler artigos sem precisar de algum tipo de guia. Aqui nossos pontos de partida para essas “eletivas”:

- Inteligencia artifical: faça [curso introdutório da Berkeley](http://ai.berkeley.edu/). Vendo os vídeos e completando os projetos excelentes de pacman. E use o livro _Artificial Intelligence: A Modern Approach_ por Russell e Norvig.

- Para machine learning: o curso do Andrew Ng na coursera. Seja paciente, e tenha certeza que você entende os fundamental antes de ir atrás de novos conhecimentos como deep learning.

- Para computação gráfica faça o [curso 184 de CC da Berkeley](http://inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html) e use [Computer Graphics: Principles and Practice](https://www.amazon.com/Computer-Graphics-Principles-Practice-3rd/dp/0321399528) como livro.

### Quão rígida é a sequência sugerida?

Realisticamente, todos os assuntos possui um nível significante de conhecimento compartilhado, e se auto referenciam. Por exemplo, a relação entre matemática discreta e algoritmos: Aprender matemática antes te ajudaria a analisar e entender seus algoritmos com mais profundidade, mas aprender os algoritmos servem de grande motivação e familiarização para a matemática discreta. Idealmente, você vai revisitar esses tópicos muitas vezes ao longo da sua carreira.

Sendo assim, nossa sequência sugerida está aí mais para te ajudar a _começar_… se você tiver razões convincentes para escolher outra sequência, só vai. Os pré-requisitos mais significativos, na nossa opinião, são: arquitetura de computadores antes de sistemas operacionais ou banco de dados, e redes de computadores e sistemas operacionais antes de sistemas distribuídos.

### Quem é o público alvo deste guia?

Nós temos em mente que você é um engenheiro de software, graduando de bootcamp ou um estudante de ensino médio precoce, ou um universitário procurando uma educação complementar. A decisão de quando embarcar nessa jornada é inteiramente pessoal, mas a maioria das pessoas tem algum beneficio por ter alguma experiência profissional antes de se aprofundar nos tópicos de ciência da computação. Por exemplo, nós percebemos que estudantes _amam_ aprender sobre banco de dados se eles já trabalharam profissionalmente na área, ou redes de computadores se eles já trabalharam num projeto web ou dois.

### Como isso se compara ao currículo da Open Source Society ou do freeCodeCamp?

O [OSS guide](https://github.com/open-source-society/computer-science) tem muitos assuntos, sugerem referências inferiores para grande parte, e nao dao nenhum raciocínio ou guia sobre o por quê e quais aspectos dos cursos em particular são valiosos. Nós nos esforçamos para limitar os cursos que você _realmente_ precisa saber e para te ajudar a entender o por quê de cada curso.

freeCodeCamp foca mais na programação e não na ciência da computação. O por quê de você querer aprender ciencia da computacao veja [acima](#why).

### E a linguagem X?

Aprender uma linguagem em particular, é uma coisa totalmente diferente de aprender sobre uma área da ciência da computação - uma linguagem é muito _mais fácil_, e _menos significativo_. Se você já é proficiente em algumas linguagens, nós sugerimos seguir o guia e ir colocar o aprendizado de novas linguagens no meio, ou simplesmente deixar para depois. Se você aprendeu programação bem, e especialmente se você aprendeu sobre compiladores, você vai levar não mais de uma semana para aprender os fundamentos de uma nova linguagem.

### E a tecnologia X que está na moda?

Nenhuma tecnologia é tão importante que aprender a usá-la deve ser parte dos fundamentos da sua educação. Por outro lado, é muito bom que você está animado para aprender essa coisa nova. O truque está em trabalhar de trás para frente da tecnologia em particular até os fundamentos e conceitos, e aprender aquilo bem antes de ver como a sua tecnologia se encaixa no panorama geral.

### Por que ainda estão recomendando “dragon book”?

O “Dragon book” ainda é um dos melhores recursos para compiladores. Tem uma má fama, especialmente por colocar muita ênfase em certos tópicos que não são tão importantes hoje em dia. Mas o livro nao foi idealizado para ser lido por completo, mas dar material suficiente para um instrutor conseguir montar um curso. Similarmente, um autodidata pode escolher sua própria aventura com o livro, ou melhor ainda seguir sugestões de professores em seus resumos/guias de leitura.

### Como posso conseguir livros baratos?

Graças a generosidade dos seus autores, muitos dos livros que sugerimos são achados de graça online. Para os que não são, nós sugerimos comprar edições usadas. Como regra geral, se existe varias edições de um livro, é muito provável que as edições mais antigas ainda sejam perfeitamente adequadas. É muito difícil que a nova versão seja 10x melhor que as mais velhas, mesmo que a diferença de preço seja.

### Quem fez isso?

Esse guia foi escrito por [Ozan Onay](https://twitter.com/oznova_) e [Myles Byrne](https://twitter.com/quackingduck), instrutores na [Bradfield School of Computer Science](https://bradfieldcs.com) em São Francisco. É baseado na nossa experiência ensinando os fundamentos da ciência da computação para centenas de engenheiros (muitos autodidatas) ou graduados de bootcamps. Muito obrigado a todos os estudantes pelo feedback contínuo sobre meios para o aprendizado autodidata. Obrigado também a Alek Sharma, Omar Rayward, Ammar Mian and Tyler Bettilyon, pelo feedback sobre o guia.

### Quem é o tradutor?

Iae galera, meu nome é Clemens Schrage, eu sou estudante de ciência de computação da UFAL (Universidade Federal de Alagoas). Se vocês tiverem alguma sugestão pra ajudar na tradução, eu acharia irado, só fazer um pull. Eu realmente não sei escrever direito e isso aqui tá uma bagunça. Espero que eu tenha ajudado quem quer que esteja lendo isso, porque o texto original me ajudou bastante. Abração ae galera.
