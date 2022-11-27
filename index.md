# Teoría de la Computación 2022

Este es un curso introductorio a la teoría de la computación, la cual se ocupa de determinar cuáles problemas pueden ser resueltos computacionalmente y con qué eficiencia, así como de entender el límite entre los problemas computables y los no-computables, y clasificarlos de acuerdo a su simpleza o dificultad.

El curso inicia con el estudio de distintos modelos de cómputo, como los autómatas finitos (que son los más sencillos), y sus diferentes tipos y aplicaciones;
las máquinas de Turing (que son las computadoras usuales de hoy en día) y las computadoras cuánticas (cuyo funcionamiento no es digital). Una vez formulado un modelo de computación, nos interesa conocer la cantidad de recursos computacionales que es necesario utilizar para resolver un problema. El primero de estos recursos es el tiempo: cuántos pasos o cuántas acciones debemos realizar para resolver el problema. También son importantes el espacio ocupado, la necesidad de utilizar una fuente de números aleatorios, la posibilidad de resolver subproblemas en paralelo, entre otros.

La formalización de un modelo computacional como objeto matemático permite expresar de manera precisa preguntas sobre problemas o algoritmos. En particular, si L es un problema. ¿Puede L ser resuelto por un algoritmo? ¿Puede ser L resuelto de manera eficiente? ¿Cómo podemos construir un algoritmo eficiente para L? ¿Es L un
problema para el cual no existe un algoritmo que lo resuelva? Contestaremos a algunas de estas preguntas, mientras que otras se verán en los cursos de Lógica Matemática y en Análisis de Algoritmos.


# Prerrequisitos

Se recomienda que los estudiantes antes del curso estén habituados con los siguientes temas:
* Álgebra lineal (matricial).
* Matemática discreta (conteo, permutaciones, divisibilidad, congruencias).
* Grafos  (representaciones, propiedades, algoritmos).
* Cálculo (funciones, límites, derivadas).
* Estructuras y algoritmos (pilas y colas, árboles, grafos).
* Programación en Python.

Bastará con haber cursado una materia de cálculo y una de mátemática discreta. En el caso de programación, conviene conocer muy bien los temas de estructuas de datos y algoritmos.

El curso tiene una carga fuerte en el tema de matemática y estructuras abstractas. Cuando sea conveniente, dedicaremos una parte del curso a cubrir algunos prerrequisitos necesarios en los temas.


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-tc2022.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Lunes de 19:50 a 21:25, y Miércoes de 19:00 a 21:25.

### Office Hours
<div id='id-office'/>

* Viernes, de 19:00 a 20:00.


# Material del curso
<div id='id-material'/>

  **No.**  | **Fecha**    | **Tópicos**                                                                    | **Recursos**
  -------- | ------------ | ------------------------------------------------------------------------------ |  -------------------------------------
  00       | 06.07.2022   | Introducción. Aspectos generales de la teoría de la computación. <br/>         |
  01       | 11.07.2022   | Alfabetos, palabras y lenguajes. Autómatas finitos deterministas (AFD). <br/> [Aula 01a](aulas/Aula01.pdf){:target="_blank"} [Aula 01b](aulas/Aula01b.pdf){:target="_blank"} | Secciones 1.5 y 2.1 Hopcroft.
  02       | 13.07.2022   | Expresiones regulares. Formalismo de los AFD. <br/> [Aula 02a](aulas/Aula02a.pdf){:target="_blank"} [Aula 02b](aulas/Aula02b.pdf){:target="_blank"} | Sección 2.1 Hopcroft.
  L1       | 13.07.2022   | Lab 01. <br/>                                                                  | [Lab 01](labs/Lab01.pdf){:target="_blank"}
  03       | 18.07.2022   | Función de transición extendida. Derivaciones. Simulación de un AFD. [Aula 03](aulas/Aula03.pdf){:target="_blank"} | Capítulo 2 Hopcroft.
  04       | 20.07.2022   | Autómatas finitos no-deterministas (AFN). Equivalencia entre AFD y AFN. [Aula 04](aulas/Aula04.pdf){:target="_blank"} | Capítulo 2 Hopcroft.
  L2       | 20.07.2022   | Lab 02. <br/>                                                                  | [Lab 02](labs/Lab02.pdf){:target="_blank"}
  05       | 25.07.2022   | epsilon-AFN. Conversión de *regexp* a AFN: Algoritmo de Thompson. [Aula 05a](aulas/Aula05a.pdf){:target="_blank"} [Aula 05b](aulas/Aula05b.pdf){:target="_blank"} | Capítulo 3 Hopcroft.
  06       | 27.07.2022   | Conversión de AFN a regexp: Algoritmo de reducción. Lema de Arden. <br/> [Aula 06](aulas/Aula06.pdf){:target="_blank"} [Aula 06_notas](aulas/Aula06_notas.pdf){:target="_blank"}  | Capítulo 3 Hopcroft.
  07       | 03.08.2022   | Repaso de algoritmos en autómatas. <br/>                                       | 
  L3       | 03.08.2022   | Lab 03. <br/>                                                                  | [Lab 03](labs/Lab03.pdf){:target="_blank"}
  08       | 08.08.2022   | Propiedades de lenguajes regulares. *Pumping Lemma*. <br/> [Aula 07a](aulas/Aula07a.pdf){:target="_blank"} | 
  09       | 10.08.2022   | Examen Corto 1.  | [Corto 01](cortos/Corto01.pdf){:target="_blank"}
  10       | 17.08.2022   | Equivalencia de lenguajes regulares. Propiedades de cerradura. <br/> [Aula 08](aulas/Aula08.pdf){:target="_blank"} | Capítulo 3 Hopcroft.
  L4       | 17.08.2022   | Lab 04. <br/>                                                                  | [Lab 04](labs/Lab04.pdf){:target="_blank"}
  11       | 22.08.2022   | Propiedades de Decisión. Algoritmo de minimización de AFD. <br/> [Aula 09](aulas/Aula09.pdf){:target="_blank"} | Capítulo 3 Hopcroft.
  12       | 24.08.2022   | Repaso de algoritmo de minimización. <br/> [Aula 10](aulas/Aula10.pdf){:target="_blank"} | Capítulo 3 Hopcroft.
  L5       | 24.08.2022   | Lab 05. <br/>                                                                  | [Lab 05](labs/Lab05.pdf){:target="_blank"}
  13       | 31.08.2022   | Gramáticas libres del contexto (*CFG*). <br/> [Aula 12](aulas/Aula12.pdf){:target="_blank"} | 
  14       | 05.09.2022   | Árboles sintácticos (*parse trees*). Ambigüedad. <br/> [Aula 13](aulas/Aula13.pdf){:target="_blank"} | 
  15       | 07.09.2022   | Remoción de Ambigüedad. <br/> [Aula 14](aulas/Aula14.pdf){:target="_blank"} | 
  L6       | 07.09.2022   | Lab 06. <br/>  | [Lab 06](labs/Lab06.pdf){:target="_blank"}
  16       | 21.09.2022   | Algoritmo de simplificación de gramáticas. <br/> [Aula 15](aulas/Aula15.pdf){:target="_blank"}  [Ejemplos](aulas/Aula15b.txt){:target="_blank"}|
  17       | 26.09.2022   | Autómatas de Pila. <br/> [Aula 16](aulas/Aula16.pdf){:target="_blank"} [Aula 17](aulas/Aula17.pdf){:target="_blank"} | 
  18       | 28.09.2022   | Presentación del primer proyecto. <br/> | 
  19       | 03.10.2022   | Análisis de algoritmos. Notaciones asintóticas. <br/> [Aula 18](aulas/Aula18.pdf){:target="_blank"} | 
  19       | 05.10.2022   | Ejemplos de notación asintótica. <br/>   | 
  L7       | 05.10.2022   | Lab 07. <br/>  | [Lab 07](labs/Lab07.pdf){:target="_blank"}
  20       | 12.10.2022   | Máquinas de Turing: motivación. <br/> [Aula 20](aulas/Aula20.pdf){:target="_blank"} | 
  21       | 17.10.2022   | Máquinas de Turing II: formalización, transiciones. <br/> [Aula 21](aulas/Aula21.pdf){:target="_blank"} | 
  22       | 19.10.2022   | Ejemplos de máquinas de Turing. <br/> [Aula 22](aulas/Aula22.pdf){:target="_blank"}  | 
  23       | 24.10.2022   | Más ejemplos de máquinas de Turing. <br/> [Aula 23](aulas/Aula23.pdf){:target="_blank"}  | 
  L8       | 26.10.2022   | Lab 08. <br/>  | [Lab 08](labs/Lab08.pdf){:target="_blank"}
  24       | 26.10.2022   | Examen Corto 2.  | [Corto 02](cortos/Corto02.pdf){:target="_blank"} <br/> **Fecha de Entrega: lunes 31 de octubre.**
  25       | 31.10.2022   | Máquinas de Turing III: Extensiones. <br/> [Aula 24](aulas/Aula24.pdf){:target="_blank"} | 
  26       | 07.11.2022   | Computabilidad, Decidibilidad. Modelos computacionales. <br/> [Aula 25](aulas/Aula25.pdf){:target="_blank"} | 
  27       | 09.11.2022   | Cálculo Lambda. <br/> [Aula 26](aulas/Aula26.pdf){:target="_blank"} | 
  28       | 09.11.2022   | Examen Corto 3.  | [Corto 03](cortos/Corto03.pdf){:target="_blank"} <br/> **Fecha de Entrega: domingo 13 de noviembre.**
  29       | 14.11.2022   | Resolución de dudas sobre el proyecto.  | 
  30       | 16.11.2022   | Clases de Complejidad. P vs NP. <br/>  Máquinas de turing universales. | 
  31       | 23.11.2022   | Presentación de proyectos finales. | 

  
# Lecturas complementarias
### (Autores: T. Gálvez, B. Pojoy, P. Mejía y A. Reyes-Figueroa).
<div id='id-notas'/>

  **No.**  | **Fecha**    | **Tópicos**                                                                | **Recursos**
  -------- | ------------ | -------------------------------------------------------------------------- |  -------------------------------------
  01       | 25.07.2022   | Lectura 1 - Expresiones regulares y AFNs.                                  | [Lectura 1](lectures/Lectura01.pdf){:target="_blank"}
  02       | 08.08.2022   | Lectura 2 - Conversión de AFNs a AFDs y construcción directa del AFD.      | [Lectura 2](lectures/Lectura02.pdf){:target="_blank"}
  03       | 22.08.2022   | Lectura 3 - Minimización de AFDs.                                          | [Lectura 3](lectures/Lectura03.pdf){:target="_blank"}
  04       | 05.10.2022   | Lectura 4 - Notación Asintótica.                                           | [Lectura 4](lectures/Lectura04.pdf){:target="_blank"}
  05       | 24.10.2022   | Lectura 5 - Máquinas de Turing.                                            | [Lectura 5](lectures/Lectura05.pdf){:target="_blank"}
  06       | 07.11.2022   | Lectura 6 - Complejidad.                                                   | [Lectura 6](lectures/Lectura06.pdf){:target="_blank"}


# Proyectos
<div id='id-projs'/>

  **No.**  | **Fecha**    | **Tópicos**                                                           | **Recursos**
  -------- | ------------ | --------------------------------------------------------------------- |  -------------------------------------
  1        | 22.08.2022   | Proyecto 1 - Algoritmos sobre AFDs, AFNs y *regexp*.                  | [Proyecto 1](projects/Proyecto_1_2022.pdf){:target="_blank"}
  .        | 28.09.2022   | Presentación y entrega de informe.                                    |

  
  **No.**  | **Fecha**    | **Tópicos**                                                           | **Recursos**
  -------- | ------------ | --------------------------------------------------------------------- |  -------------------------------------
  2        | 31.10.2022   | Proyecto 2 - Algoritmo CYK y Funciones Lambda.                        | [Proyecto 2](projects/Proyecto_2_2022.pdf){:target="_blank"} 
  .        | 23.11.2022   | Presentación.                                                         |
  .        | 26.11.2022   | Entrega de informe final.                                             |

Horarios para la presentación del segundo proyecto. **(23 de noviembre)**

  **No.**  | **Hora**           | **Grupo**         
  -------- | ------------------ | -----------------------
  1        | 7:00 pm - 7:15pm   | Equipo 9
  2        | 7:15 pm - 7:30pm   | Equipo 8
  3        | 7:30 pm - 7:45pm   | Equipo 1
  4        | 7:45 pm - 8:00pm   | Equipo 7
  5        | 8:00 pm - 8:15pm   | Equipo 4
  6        | 8:15 pm - 8:30pm   | Equipo 2
  7        | 8:30 pm - 8:45pm   | Equipo 5
  8        | 8:45 pm - 9:00pm   | Equipo 3
  9        | 9:00 pm - 9:15pm   | Equipo 10
  

  
# Referencias
<div id='id-ref'/> 

### Textos:

* [J. Hopcroft, R. Motwani, J. Ullman (2006). *Automata Theory, Languages and Computation*.](http://library.lol/main/CAC409C1878AC487AF3A39687C924FFC){:target="_blank"}

* [J. Hopcroft, R. Motwani, J. Ullman (2007). *Teoría de automatas, lenguajes y computación*.](libros/Hopcroft_Ullman.pdf){:target="_blank"}

* [H. Lewis, C. Papadimitriou (1998). *Elements of the Theory of Computation*.](http://library.lol/main/586BEB94A1648CF624F74496477E92DB){:target="_blank"}


### Referencias adicionales:

* [J. G. Brookshear (1988). *Theory of Computation: Formal Languages, Automata, and Complexity*.](http://library.lol/main/EE4EB25060E76527E13F904C99DE2D98){:target="_blank"}

* [J. G. Brookshear (1993). *Teoría de la Computación, Lenguajes Formales, Autómatas y Complejidad*.](libros/Brookshear.djvu){:target="_blank"}

* [R. de Castro Korgi (2004). *Teoría de la Computación, Lenguajes Autómatas, Gramáticas*.](http://library.lol/main/60501AE7549BF7B67BB11709240CE5B7){:target="_blank"}

* [E. Gaudioso Vásquez *et al.* (2017). *Introduccón a la Teoría de Autómatas, Gramáticas y Lenguajes*.](http://library.lol/main/7B969A8129A16B2F3679F4D4A20FFF5D){:target="_blank"}

* [H. Pedrycz (2022). *Automata Theory and Formal Languages*.](http://library.lol/main/AEC2FE8B00CE16488082B14183D31727){:target="_blank"}


### Referencias avanzadas:

* [C. Papadimitriou, K. Steiglitz (1994). *Computational Complexity*.](http://library.lol/main/2E57188472ACBBBB8B5860A1327FBA94){:target="_blank"}

---
