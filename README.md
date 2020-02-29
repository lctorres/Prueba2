# Prueba2
Evaluación 2 

Prueba N°2 (ABP) - Individual
----------------

Tema
+ Programación Orientada a Objetos (POO)

Temario Tratado
* Programación básica en Java
* Programación orientada a objetos
* Herencia y polimorfismos
* UML Java
* Pruebas JUnit Java

Nombre Proyecto "Electrodomésticos"

Descripción del Trabajo

Utilizando el mecanismo de herencia , crear una superclase llamada Electrodomésticos la cual tiene dos clases hijas llamadas
Lavadora y Televisión. Heredaran cuatro atributos (Precio base, color, consumo energético y peso), y también tendrán atributos
propios (Lavadora: carga - Televisión: pulgadas y sintonizadorTDT).

Métodos:
Ademas de los Atributos heredados de Electrodomésticos, las clases hijas: Lavadora y Televisión se asignaran diferentes
métodos en cada clase:
- Métodos get para todos los Atributos
- comprobarConsumoEnergetico(char letra), comprueba que la letra es correcta, sino es correcta usara la letra por defecto.
  Se invocara al crear el objeto y no sera visible.
- comprobarColor(String color), comprueba que el color es correcto, sino lo es usara el color por defecto. Se invocara
  al crear el objeto y no sera visible.
- precioFinal(), según el consumo energético, aumentara su precio, y según su tamaño también.

Constructores:
- Un constructor por defecto
- Un constructor que reciba dos Atributos, y el resto por defecto
- Un constructor que reciba todos los Atributos

Operador
- instanceof(), sirve para conocer si un objeto es de una clase determinada, es decir; si el objeto pasaría el test para 
  esa clase, especificando a la derecha del operador.

Una vez finalizada la implementación de la superclase y las clases hijas, se creara un Ejecutable para probar su funcionamiento.
Este programa consistirá en la creación de un Array, al cual en cada posición se le asignara un objeto con los valores que se 
deseen, para luego mostrar por consola el precio de cada clase. Es decir: el precio de todos los Televisores por un lado, el de las
Lavadoras por otro y la suma de precio de los Electrodomésticos.
