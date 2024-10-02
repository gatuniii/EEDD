# Lenguajes de Programacion

## **1.Que es un lenguaje de programacion**

> Un *lenguaje de programación* es un conjunto de reglas y sintaxis que permite a los programadores escribir instrucciones que una computadora puede entender y ejecutar. Estos lenguajes facilitan la creación de software, aplicaciones y sistemas, permitiendo a los desarrolladores expresar algoritmos y lógica de forma clara y estructurada. Ejemplos incluyen Python, Java y C++.


## **2.Clasificación de los lenguajes de programación según su nivel de abstracción**

> 1. Lenguajes de Bajo Nivel
*Descripción:* Muy cercanos al hardware, difíciles de entender para humanos.
*Ejemplos:*
-Lenguaje de máquina (código binario)
-Lenguaje ensamblador (Assembly)
2. Lenguajes de Medio Nivel
*Descripción:* Combinan características de bajo y alto nivel, ofreciendo control sobre el hardware.
*Ejemplos:*
-C
-C++
3. Lenguajes de Alto Nivel
*Descripción:* Muy abstractos y fáciles de usar, centrándose en la lógica del programa.
*Ejemplos*:
    -Python
    -Java
    -JavaScript

**Resumen**
    -Bajo Nivel: Lenguaje de máquina,       ensamblador
    -Medio Nivel: C, C++
    -Alto Nivel: Python, Java, JavaScript

## **3.Clasificación de los lenguajes de programación según su forma de ejecución**


1. Lenguajes Compilados
   
*Descripción*: 

>Se traducen completamente a código máquina antes de ser ejecutados. El compilador convierte el código fuente en un archivo ejecutable.
- **Ejemplos**: 
  - C
  - C++
  - Rust

2. Lenguajes Interpretados
*Descripción*: 

>Se ejecutan línea por línea a través de un intérprete, que traduce el código fuente en tiempo real durante la ejecución.

*Ejemplos*: 
  - Python
  - JavaScript
  - Ruby

3. Lenguajes Híbridos
*Descripción*:

>Combinan características de lenguajes compilados e interpretados. Parte del código se compila a un formato intermedio, que luego es interpretado.

*Ejemplos*: 
  - Java (compilado a bytecode y ejecutado por la JVM)
  - C# (compilado a bytecode y ejecutado por el CLR)

**Resumen**

- *Compilados*: C, C++, Rust
- *Interpretados*: Python, JavaScript, Ruby
- *Híbridos*: Java, C#


# **4.Ventajas e inconvenientes entre lenguajes interpretados, compilados y virtuales**

> **Lenguajes Compilados**
> 
**Ventajas**:

1. *Rápidos*: Se ejecutan rápidamente porque ya están en código máquina.
2. *Optimización*: Mejor rendimiento por optimizaciones en el proceso de compilación.

**Inconvenientes**:

1. *Tiempo de compilación*: Necesitan compilarse antes de ejecutarse.
2. *Poca portabilidad**: Deben recompilarse para diferentes sistemas.


> **Lenguajes Interpretados**


**Ventajas**:

1. *Flexibles*: Se pueden modificar y ejecutar sin recompilación.
2. *Portátiles*: Se ejecutan en cualquier sistema con un intérprete.


**Inconvenientes**:

1. *Más lentos*: Se traducen en tiempo de ejecución, lo que puede hacerlos más lentos.
2.  *Errores en ejecución*: Los errores aparecen mientras se ejecuta el programa.


> **Lenguajes Virtuales**
**Ventajas:**

1. *Portabilidad*: Se ejecutan en cualquier sistema con la máquina virtual adecuada.
2. Seguridad: Incluyen características de seguridad y manejo de errores.


**Inconvenientes:**

1. *Rendimiento*: Pueden ser más lentos que los compilados.
2. *Dependencia*: Requieren que la máquina virtual esté instalada.

# **5.Qué es el código fuente**

>El *código fuente* es el conjunto de instrucciones y declaraciones escritas en un lenguaje de programación que define el comportamiento y las funcionalidades de un programa. Es el texto original que los programadores crean y editan, y se debe compilar o interpretar para que una computadora lo ejecute.

# **6. qué es un compilador**

> Un *compilador* es un programa que traduce el código fuente de un lenguaje de alto nivel a código máquina o a un lenguaje intermedio. Convierte todo el código en un archivo ejecutable antes de la ejecución, optimizando el rendimiento del programa.


# **7.Qué es el código objeto**

> El *código objeto* es el resultado de la compilación del código fuente, que ha sido traducido a un lenguaje de bajo nivel, generalmente en forma de código máquina o lenguaje ensamblador. Este código aún no está completamente ejecutable, ya que puede requerir un enlazador para combinarlo con otros módulos o bibliotecas antes de generar un archivo ejecutable final.


# **8.Indica qué es un intérprete**

> Un *intérprete* es un programa que ejecuta directamente el código fuente de un lenguaje de programación, traduciéndolo línea por línea en tiempo real. A diferencia de un compilador, que convierte todo el código a un archivo ejecutable antes de la ejecución, el intérprete procesa el código a medida que se encuentra con cada instrucción. Esto permite una mayor flexibilidad y facilidad de modificación, pero generalmente resulta en un rendimiento más lento.

# **9.Qué es una máquina virtual**

> Una *máquina virtual* es un entorno de ejecución que emula un sistema informático completo, permitiendo que un software se ejecute como si estuviera en un hardware físico real. Proporciona una capa de abstracción entre el sistema operativo y el hardware, permitiendo la ejecución de aplicaciones de manera portátil y aislada. Esto facilita la ejecución de programas en diferentes sistemas operativos y proporciona características de seguridad y manejo de errores. Un ejemplo común es la Java Virtual Machine (JVM).


# **10.Qué son los bytecodes**

>Los *bytecodes* son un tipo de código intermedio que resulta de la compilación de un programa en lenguajes como Java. Este código no es directamente ejecutable por la máquina, sino que es diseñado para ser interpretado o ejecutado por una máquina virtual, como la Java Virtual Machine (JVM). Los bytecodes permiten la portabilidad del programa, ya que pueden ejecutarse en cualquier plataforma que tenga la máquina virtual correspondiente.


# **11.Qué es JDK y JRE**

> **JDK (Java Development Kit)**
*Descripción*: Es un conjunto completo de herramientas para desarrollar aplicaciones en Java. Incluye el compilador, herramientas de depuración, bibliotecas y otros recursos necesarios para crear y compilar programas Java.
*Uso*: Utilizado por desarrolladores para escribir y compilar código Java.

> **JRE (Java Runtime Environment)**
*Descripción*: Es un entorno que permite ejecutar aplicaciones Java. Incluye la JVM (Java Virtual Machine) y las bibliotecas necesarias para ejecutar programas Java, pero no contiene herramientas de desarrollo como el compilador.
*Uso*: Utilizado por usuarios finales para ejecutar aplicaciones Java.




