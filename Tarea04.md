		Tarea 04: Conceptos

-- ¿Qué es un Patron de Diseño? 

Son la base para la búsqueda de soluciones a problemas comunes en el 
desarrollo de software y otros ámbitos referentes al diseño de interacción 
o interfaces. Un patrón de diseño resulta ser una solución a un problema 
de diseño.


-- ¿En Que consiste el patron singleton?

Es un patrón de diseño para restringir la creación de objetos pertenecientes 
a una clase o el valor de un tipo a un único objeto.
Su intención consiste en garantizar que una clase sólo tenga una instancia 
y proporcionar un punto de acceso global a ella.
El patrón singleton se implementa creando en nuestra clase un método que crea 
una instancia del objeto sólo si todavía no existe alguna. Para asegurar que la 
clase no puede ser instanciada nuevamente se regula el alcance del constructor
(con modificadores de acceso como protegido o privado).


-- ¿En que consiste el patron Factory? 

Consiste en utilizar una clase constructora (al estilo del Abstract Factory) 
abstracta con unos cuantos métodos definidos y otro(s) abstracto(s): el dedicado 
a la construcción de objetos de un subtipo de un tipo determinado. Es una 
simplificación del Abstract Factory, en la que la clase abstracta tiene métodos 
concretos que usan algunos de los abstractos; según usemos una u otra hija de 
esta clase abstracta, tendremos uno u otro comportamiento.


-- ¿En que consiste el patron Builder?

Es usado para permitir la creación de una variedad de objetos complejos desde 
un objeto fuente (Producto), el objeto fuente se compone de una variedad de 
partes que contribuyen individualmente a la creación de cada objeto complejo a 
través de un conjunto de llamadas a interfaces comunes de la clase Abstract Builder.
El patrón builder es creacional.
A menudo, el patrón builder construye el patrón Composite, un patrón estructural.
Intención: Abstrae el proceso de creación de un objeto complejo, centralizando 
dicho proceso en un único punto, de tal forma que el mismo proceso de construcción 
pueda crear representaciones diferentes.


-- ¿Investigar que es la herramienta ADB de Android? 

ADB responde a Android Debug Bridge (puente de depuración de Android) está 
dirigido a desarrolladores para ayudarlos a encontrar y reparar errores en las 
aplicaciones de Android que estén construyendo (de ahí su nombre).
Es una utilidad de línea de comandos de Google que permite acceder y controlar un 
dispositivo Android desde un ordenador a través de una conexión USB.


-- ¿Para que sirve el operador "final" en JAVA? 

Indica que una variable, método o clase no se va a modificar, lo cuál puede ser 
útil para añadir más semántica, por cuestiones de rendimiento, y para detectar 
errores.

– Si una variable se marca como final, no se podrá asignar un nuevo valor a la variable.
– Si una clase se marca como final, no se podrá extender la clase.
– Si es un método el que se declara como final, no se podrá sobreescribir.

Algo muy a tener en cuenta a la hora de utilizar este modificador es que si es 
un objeto lo que hemos marcado como final, esto no nos impedirá modificar el 
objeto en sí, sino tan sólo usar el operador de asignación para cambiar la referencia.


-- ¿Que Lenguajes soportan Sobre Carga de operadores?

Es uno de los mecanismos que nos permite ampliar las capacidades de los lenguajes 
de programación orientados a objetos. En C++, la declaración y definición de una 
sobrecarga de operador es muy similar a la declaración y definición de una función 
cualquiera.
Algunos lenguajes que puede soportar sobrecarga de operadores son:
- JAVA
- C++
- POO
- C#
- PHYTON


-- ¿Para que sirve Gradle? 

Gradle es una herramienta para automatizar la construcción de nuestros proyectos, 
por ejemplo las tareas de compilación, testing, empaquetado y el despliegue de los 
mismos. Es muy flexible para la configuración, pero además ya tiene armadas las tareas 
para las mayoría de los proyectos por default. Esta herramienta es usado por grandes 
proyecto “Open Source” como “Spring”, “Hibernate”, y “Grails”. (También lo usan empresas 
como “LinkedIn” para sus proyectos).


--  ¿En que consiste la inyección de dependencias en desarrollo de software, y por qué 
es útil utilizarla?

consiste en hacer que nuestras piezas de software sean independientes comunicándose 
únicamente a través de un interface. Esto implica muchas modificaciones en el código 
fuente como el uso de implementaciones, la eliminación de la instanciación de objetos 
mediante la instrucción new o la necesidad de un modo de configuración que indique que 
clases se instanciarán en el caso de solicitarlo.
La inyección de dependencias (DI) es un patrón de diseño que deriva de un patrón más 
genérico llamado Inversión de Control. DI hace uso de la modularidad y la reutilización, 
las cuales siempre deberíamos tener en cuenta si nuestra aplicación va a estar dotada 
de mayor funcionalidad. Más adelante, veremos en que consiste la Inversión de Control, 
pero hoy vamos a centrarnos en la DI.
Pero aún usando DI, a la fuerza tendremos que instanciar los dos tipos de cerradura y 
pasar como parámetro al ObjetoPuerta la que nos convenga en el momento, tal y como hemos 
hecho con ObjetoCerraduraCodigo y ObjetoCerraduraLlave.

