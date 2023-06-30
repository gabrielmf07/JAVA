# Repaso de Java

Este es un breve repaso sobre Java, un lenguaje de programación popular y versátil que se utiliza en una amplia gama de aplicaciones, desde desarrollo de software hasta desarrollo web y aplicaciones móviles.

## Tabla de contenidos

1. [¿Qué es Java?](#qué-es-java)
2. [Características principales](#características-principales)
3. [Sintaxis básica](#sintaxis-básica)
4. [Tipos de datos y variables](#tipos-de-datos-y-variables)
5. [Estructuras de control](#estructuras-de-control)
6. [Programación orientada a objetos](#programación-orientada-a-objetos)
7. [Excepciones](#excepciones)
8. [Recursos adicionales](#recursos-adicionales)

## ¿Qué es Java?

Java es un lenguaje de programación orientado a objetos y de propósito general. Fue desarrollado por Sun Microsystems (ahora propiedad de Oracle) y se lanzó por primera vez en 1995. Java se destaca por su portabilidad, lo que significa que los programas escritos en Java pueden ejecutarse en diferentes plataformas sin necesidad de modificaciones.

Java es utilizado en una amplia gama de aplicaciones, desde desarrollo de aplicaciones de escritorio hasta desarrollo web y aplicaciones móviles. Además, Java es conocido por su seguridad, rendimiento y amplia comunidad de desarrolladores.

## Características principales

Algunas de las características principales de Java incluyen:

- **Orientación a objetos**: Java es un lenguaje completamente orientado a objetos, lo que significa que todo en Java es un objeto. Esto permite una programación estructurada y modular, y promueve la reutilización de código a través de conceptos como encapsulamiento, herencia y polimorfismo.

- **Portabilidad**: Los programas escritos en Java son portables, lo que significa que pueden ejecutarse en diferentes plataformas sin necesidad de modificaciones. Esto se debe a la máquina virtual de Java (JVM), que interpreta y ejecuta el código Java en cualquier plataforma compatible con JVM.

- **Robustez**: Java está diseñado para ser un lenguaje robusto y resistente a errores. Proporciona características como verificación de tipos en tiempo de compilación, gestión automática de memoria (a través del recolector de basura) y control de excepciones, lo que ayuda a prevenir y manejar errores de manera efectiva.

- **Multihilo**: Java ofrece soporte incorporado para la programación multihilo, lo que permite la ejecución simultánea de múltiples hilos de ejecución. Esto facilita la implementación de aplicaciones concurrentes y paralelas.

- **Biblioteca estándar amplia**: Java viene con una biblioteca estándar rica que proporciona una amplia gama de clases y métodos predefinidos. Esta biblioteca facilita tareas comunes de programación, como manipulación de cadenas, operaciones de entrada/salida, manipulación de fechas y más.

## Sintaxis básica

La sintaxis de Java es similar a la de otros lenguajes de programación como C++ y C#. Aquí hay un ejemplo básico de un programa Java:

```java
public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("¡Hola, mundo!");
    }
}
``

`

En este ejemplo, se define una clase llamada `HolaMundo` que contiene un método principal `main()`. El método `main()` es el punto de entrada de cualquier programa Java y es donde comienza la ejecución.

## Tipos de datos y variables

Java tiene varios tipos de datos predefinidos, incluyendo enteros, números de coma flotante, caracteres, booleanos y más. Puedes declarar variables utilizando estos tipos de datos. Aquí hay un ejemplo:

```java
int edad = 25;
double altura = 1.75;
char inicial = 'J';
boolean esEstudiante = true;
```

En este ejemplo, se declaran variables para almacenar la edad (un número entero), la altura (un número de coma flotante), la inicial del nombre (un carácter) y un indicador de si la persona es estudiante (un valor booleano).

## Estructuras de control

Java proporciona varias estructuras de control para controlar el flujo de ejecución de un programa. Algunas de las estructuras de control más comunes incluyen:

- **Estructuras de selección**: Se utilizan para tomar decisiones basadas en condiciones. Las estructuras de selección más comunes son `if-else` y `switch`.

- **Bucles**: Se utilizan para repetir un bloque de código hasta que se cumpla una condición. Los bucles más comunes son `for`, `while` y `do-while`.

- **Estructuras de salto**: Se utilizan para cambiar el flujo de ejecución del programa. Algunas estructuras de salto incluyen `break`, `continue` y `return`.

## Programación orientada a objetos

Java es un lenguaje orientado a objetos, lo que significa que se basa en el concepto de clases y objetos. Las clases son plantillas que definen las propiedades y comportamientos de los objetos, mientras que los objetos son instancias individuales de una clase.

Aquí hay un ejemplo básico de una clase en Java:

```java
public class Persona {
    private String nombre;
    private int edad;
    
    public Persona(String nombre, int edad) {
        this.nombre = nombre;
        this.edad = edad;
    }
    
    public void saludar() {
        System.out.println("Hola, mi nombre es " + nombre + " y tengo " + edad + " años.");
    }
}
```

En este ejemplo, se define una clase `Persona` con propiedades privadas (`nombre` y `edad`) y un constructor que se utiliza para inicializar las propiedades. La clase también tiene un método `saludar()` que imprime un mensaje de saludo utilizando las propiedades de la clase.

## Excepciones

Java maneja los errores y excepciones mediante el uso de bloques `try-catch`. Esto permite capturar y manejar errores de manera controlada en lugar de que el programa se bloquee por completo. Aquí hay un ejemplo:

```java
try {
    // Código que puede lanzar una excepción
    int resultado = dividir(10, 0);
    System.out.println("El resultado es: " + resultado);
} catch (ArithmeticException e) {
    // Manejo de la excepción
    System.out.println("Error: División por cero");
}
```

En este ejemplo, el código dentro del bloque `try` puede lanzar una excepción si se intenta dividir un número por cero. Si ocurre una excepción, el control se transfiere al bloque `catch`, donde se maneja

 la excepción específica `ArithmeticException` e imprime un mensaje de error adecuado.

## Recursos adicionales

Aquí tienes algunos recursos adicionales que puedes consultar para aprender más sobre Java:

- [Documentación oficial de Java](https://docs.oracle.com/javase/): La documentación oficial de Java proporciona una referencia completa de las clases y métodos disponibles en el lenguaje Java.

- [Java Tutorials](https://docs.oracle.com/javase/tutorial/): Los tutoriales de Java ofrecidos por Oracle proporcionan una guía paso a paso para aprender Java desde cero.

- [Java API Documentation](https://docs.oracle.com/en/java/javase/): La documentación de la API de Java proporciona información detallada sobre las clases y métodos de la biblioteca estándar de Java.

- Libros sobre Java: Hay muchos libros excelentes disponibles sobre programación en Java que cubren tanto los conceptos básicos como los temas avanzados. Algunos títulos populares incluyen "Head First Java" de Kathy Sierra y Bert Bates, y "Effective Java" de Joshua Bloch.

Recuerda practicar y escribir código Java por tu cuenta para obtener experiencia y comprensión práctica del lenguaje. ¡Diviértete programando en Java!
