---
title: Programación orientada a objetos con Java
date: 2021-05-07 20:00:00
categories: [JAVA, OOP]
tags: [java, oop]
---

## Intro

En este, mi primer post, comenzare hablando sobre los conceptos básicos de la programación orientada a objetos.
La POO\(Programación orientada a objetos\) es un paradigma surgido en los años 1970, que utiliza objetos como elementos fundamentales en la construcción de la solución. 


## Definiciones y conceptos básicos

- Definición de objeto:
    Un objeto es una entidad, una cosa, una representación de algo \(puede ser una idea o concepto \) en el mundo. Se aloja en memoria, tiene una identidad propia, guarda valores y brinda una forma de acceder y modificar esos valores \(aunque pueden ser valores de solo lectura \).

- Definición de Clase:
    Una clase describe un conjunto de objetos. Es lo que describe como es el objeto y su comportamiento. En Java por ejemplo, por convención, los nombres de las clases comienzan siempre en mayúsculas.

- Relación entre Clase y Objeto:
    Un objeto es un caso concreto de una clase, una instancia. La clase es lo que codificamos en un lenguaje de programación, mientras que los objetos se crean en memoria mientras se ejecuta el programa, tomando como \"plantilla \" o \" plano " a su clase.

- Definición de Identidad:
    La identidad es una caracteristica de todos los objetos, todos los objetos son capaces de diferenciarse entre sí gracias a esa identidad.
    La identidad de un objeto esta dada automáticamente, no hay que hacer ni programar nada. Mas abajo en este post, encontraras un link a un repo donde explico estos conceptos en código.

- Definición de Atributo: 
    Un atributo es una variable que se declara dentro de una clase. Por ejemplo, si creamos una clase Persona y queremos que cada Persona tenga un nombre, declaramos el atributo nombre, de tipo string dentro de la clase Persona.
    De esa forma todos los objetos instancia de la clase Person, tendrán su propio nombre.

- Definición de Operación:
    Una operación es una **especificación** de una función que se le pedira al objeto que ejecute.
    Se resalta especificación ya que la operación dice que es o que tiene que hacer el objeto, pero no indica el como. Entonces una operación, no es más que el encabezado de una función, que dice el nombre, lo que devuelve y una lista de parámetros.

- Definición de Método: 
    Es la implementación de una operación. Es el cuerpo de la función, el código útil que dice como vamos a llevar a cabo la operación. Es el método que hay que seguir para llevar adelante la operación.

- Definición de Estado:
    El estado de un objeto es el conjunto de los valores de los atributos en un instante en el tiempo. Se implementa a través de los atributos de su clase, y es algo dinámico, que puede cambiar con el tiempo.

- Definición de Comportamiento:
    El comportamiento de un objeto es el conjunto de operaciones que el objeto puede ejecutar. Esta dado entonces por las operaciones definidas en su clase.

Bueno, esto ha sido una pequeña y breve introducción al paradigma orientado a objetos. Cualquier duda me puedes escribir. Espero que esto pueda ser de utilidad, y con el correr de los días seguiré agregando contenido. Dejo un [repo](https://github.com/leoperez0782/oop-java) con ejemplos de los temas aquí tratados.


