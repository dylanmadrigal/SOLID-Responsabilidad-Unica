# SOLID-Responsabilidad-Unica
Ejemplo en C++ del principio de responsabilidad única (SRP).

El principio de responsabilidad unica se implementa con la separacion de responsabilidades entre las clases que hay en el programa. 
En los archivos de Libro y Guardar, la clase libro es la que administra la informacion del libro, por medio de sus atributos.
Por otra parte, los archivos de la clase guardar son los que tienen el metodo de GUardarLirbo(), el cual se usa para recibir un objeto Libro
y mostrar titulo y autor en consola. Esto permite que cada clase tenga una responsabilidad diferenciada.
