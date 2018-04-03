# LearningComputerScienceWithJava
Introduction to computer science and programming intended for people with little or no experience



# HelloWorldMaven

# Objetivos

- Integrar desde Eclipse Maven y GitHub.

# Git
Eclipse trae de serie una componente denominada Egit que proporciona una interfaz bastante completa de las operaciones con Git. Para acceder a ella, en el menú Window > Show view > Other…, despliega la opcion de "Git", selecciona "Git repositories" y por ultimo open, apareceran las diferentes operaciones de Git.


# Maven
Por defecto eclipse usará una versión de maven interna.

Desde el fichero pom.xml, clic derecho, elegimos la opción "Run as" y ahí tenemos los comandos básicos de maven para ejecutar, como "build", "clean", "install", "test", etc.
Si nos hace falta alguno, tenemos que crear una nueva configuración de "Run". Elegimos "Run as" -> "Maven build..." y se abre la ventana con todos los posibles tipos de ejecución de un proyecto. Aparece en el lado derecho una ventana con una serie de campos a rellenar.

- En "New name" ponemos un nombre que nos ayude a identificar esta ejecución que estamos creando.
- En "Base directory" ponemos el directorio donde queremos que se ejecute el comando maven que estamos creando, que habitualmente será el directorio donde está el fichero pom.xml. Para elegir esto, con el botón "Browse Workspace" nos bastará elegir el proyecto donde tenemos el fichero pom.xml.
- En "Goals" ponemos el comando maven que queremos ejecutar, sin el "mvn" delante.


# PRÁCTICA
Clonaremos el proyecto y en la clase principal "HelloWorld.java" utilizaremos las diferentes "Escape sequences" para conocer sus funciones. 

\n	newline <br /> 
\t	tab <br />
\"	double quote <br />
\	backslash 


Para aprender más sobre esto: https://books.trinket.io/thinkjava/chapter1.html 









