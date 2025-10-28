# Punto 5 Generación de ejecutables a partir de código fuente en distintos lenguajes en un mismo IDE (CE 2.e)

## IDE utilizado:
Como Thonny y PyCharm (los IDEs que habia estado utilizando) no dan opción a otro lenguaje distinto a Python, he decidido utilizar Visual Studio Code, ya que me ofrece las herramientas necesarias para poder hacer ambos códigos.

## Descripción de la tarea
Escribir un programa que cuente de 10 a 0 y luego imprima "¡Despegue!" usando un único IDE para generar y ejecutar este programa en dos lenguajes diferentes. En mi caso, haré Java y Kotlin

# Respuesta a preguntas evaluables
### Pregunta 1: ¿Cuál fue el proceso para ejecutar el mismo programa en diferentes lenguajes dentro del mismo IDE?
Creé en Visual Studio Code dos archivos separados, uno en Java y otro en kotlin, pero para ello primero me tuve que instalar los plugins/extensiones correspondientes a cada uno de los lenguajes. El objetivo de ambos lenguajes es contar de 10 a 0 y mostrar "¡Despeque!".
Escribí el código de cada versión, lo compilé y ejecuté directamente desde la terminal integrada del IDE, usando los comandos específicos de cada lenguaje (*javac* y *java* para Java y *Kotlin* para Kotlin).
De esta forma, pude trabajar con ambos lenguajes en el mismo entorno sin cambiar de programa.

### Pregunta 2: ¿Qué diferencias encontraste en la generación del ejecutable entre los dos lenguajes?
En Java, el archivo fuente (.java) se compila con javac, generando un archivo .class con bytecode que luego se ejecuta con la JVM mediante el comando java.
En Kotlin, el compilador (kotlinc) también genera bytecode compatible con la JVM, pero el proceso puede producir directamente un .jar ejecutable o archivos .class de forma más automática.
En resumen, ambos lenguajes generan bytecode para la JVM, pero kotlin simplifica el proceso, mientras que Java requiere compilar y ejecutar en pasos separados.