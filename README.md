# Patrones de Diseño
En el diseño de software se busca dar soluciones a problemas comunes. Estas soluciones se pueden personalizar a traves de un patrón para resolver un problema particular.

## ¿Qué es un patrón de diseño? :bulb:
Los patrones son similares a un plano que se puede analizar en detalle para implementar la solución que mejor se adpate a dar solución a una necesidad particular en el diseño orientado a objetos.

## Historia de los patrones :hourglass_flowing_sand:
El concepto de los patrones fue introducido por Christopher Alexander en libro "El lenguaje de patrones" para el diseño de entornos urbanos. Mas tarde, en 1995,Erich Gamma, John Vlissides, Ralph Johnson y Richard Helm, llamados la "Banda de los cuatro" publicaron el libro "Patrones de Diseño", en el que aplicaron el concepto de los patrones de diseño a la programación. El libro presenta unos 23 patrones y se convirtió en un exito que llegó a ser conocido como  *“el libro GoF”*. Desde entoces se han creado nuevos patrones de diseño relacionados con la programación orientada a ojetos.

## Ventajas de los patrones:
- Utlizan principios de la programación orientada a objetos con soluciones ya probadas para resover casos habituales
- Definen un leguaje común en el equipo de trabajo para realizar las tareas de forma eficiente.

## Crítica de los patrones :broken_heart:

Algunas críticas estan orientadas a evitar su necesidad de uso. Por otro lado, es visto como un dogma carente de flexibilidad 

## Clasificación :
Es de esperar que los patrones de diseño varien en complejidad , escalabilidad y nevels de detalle. Esto no ndebe verse como una desventaja, sino practica que da status al diseño que puede ser da bajo nivel o llamarse **idioms** y de más alto nivel como son los **patrones de arquitectura**. Estos se clasifican según su proposito y estan agrupados así:

- **Patrones creacionales** : para la creación de objetos, son flexibles y reutilizables en el código existente:
  - Factory Method: Es un tipo de patron que permite crear objetos en una superclasey al a vez modificar o alterar estos ojetos en una subclase.
  - Abstract Factory : Permite crear familas de objetos o productos relacionados :family_man_woman_girl_boy:
  - Builder : es funcional cuando se requiera construir un arbol de objetos.
  - Prototype: permite utilizar como prototipos un grupo de objetos.
  - Singleton : facilita el contro estricto de variables globales.
- *Patrones estructurales* : se utilizan para ensamblar objetos y clases en estructuras más grandes sin afectar la flexiblidad y eficiencia de la estructura:
  - Adapter: facilita la colaboración entre objetos con interfaces incopatibles
  - Bridge : se utiliza cuando se requiere organizar y dividir una clse monolítica o extendrla en varias dimensiones.
  - Decorator : añade nuevas funcionalidades a objetos encasublados.
  - Facade : es útil cuando se requiera una estructura de capas o subsistemas.
  - Flyweight : es aplicable solamente cuando el programa requiera soportar una cantidad de objetos soportables en la RAM.
  - Proxy : controla el acceso al objeto original 
- *Patrones de comportamiento* : Se encargan de la comunicacion y asignacion de responsabilidad entre objetos:
  - Chain of Responsibility
  - Command
  - Memento
  - Template Method
  - Visitor
  - Iterator
  - State
  - Mediator
  - Strategy
  
