# **_Classic Design Patterns_**
### Source : [refactoring guru](https://refactoring.guru/design-patterns/catalog) <br>
<br>

# 1) Creational patterns 
These patterns provide various object creation mechanisms which increase flexibility and reuse of existing code.

## <li> **Singleton***
When we want only one object of a class during our program.
> ## **_Structure_** 
> ![Singleton](https://refactoring.guru/images/patterns/diagrams/singleton/structure-en.png)

## <li> **Prototype***
When we want to create a new copy of an object.
> ## **_Structure_** 
> ![prototype](https://refactoring.guru/images/patterns/diagrams/prototype/structure.png)

## <li> **Builder**
When we want to construct complex objects step by step. This pattern allows us to produce different types and representations of an object using the same construction code.
> ## **_Structure_** 
> ![Builder](https://refactoring.guru/images/patterns/diagrams/builder/structure.png?id=fe9e23559923ea0657aa5fe75efef333)

## <li> **Abstract Factory**
When we want to produce families of related objects without specifying their concrete classes.
> ## **_Structure_** 
> ![Abstract Factory](https://refactoring.guru/images/patterns/diagrams/abstract-factory/structure.png)

> ## **_example_** 
> ![Abstract Factory](https://refactoring.guru/images/patterns/diagrams/abstract-factory/example.png)

## <li> **Factory Method***
When we want to create objects in a superclass, but allow subclasses to alter the type of objects that will be created.
> ## **_Structure_** 
> ![Factory Method](https://refactoring.guru/images/patterns/diagrams/factory-method/structure.png)

# 2) Structural patterns 
These patterns explain how to assemble objects and classes into larger structures while keeping these structures flexible and efficient

## <li> **Adapter***
When we want to allow objects with incompatible interfaces to collaborate
> ## **_Structure_** 
> ### Object Adapter
> ![object adapter](https://refactoring.guru/images/patterns/diagrams/adapter/structure-object-adapter.png)
> ### Class Adapter
> ![class adapter](https://refactoring.guru/images/patterns/diagrams/adapter/structure-class-adapter.png)

## <li> **Bridge***
When we want to split a large class or a set of closely related classes into two separate hierarchies—abstraction and implementation—which can be developed independently of each other
> ## **_Structure_** 
> ![Bridge](https://refactoring.guru/images/patterns/diagrams/bridge/structure-en.png)

## <li> **Composite***
When we want to compose objects into tree structures and then work with these structures as if they were individual objects
> ## **_Structure_** 
> ![Composite](https://refactoring.guru/images/patterns/diagrams/composite/structure-en.png)

## <li> **Decorator***
When we want to attach new behaviors to objects by placing these objects inside special wrapper objects that contain the behaviors
> ## **_Structure_** 
> ![Decorator](https://refactoring.guru/images/patterns/diagrams/decorator/structure.png)

## <li> **Facade**
When we want to create a simple interface with limited functions to work with a sophisticated functionalities in the background
> ## **_Structure_** 
> ![Facade](https://refactoring.guru/images/patterns/diagrams/facade/structure.png)

## <li> **Flyweight (Cache)**
When we want to fit more objects into the available amount of RAM by sharing common parts of state between multiple objects instead of keeping all of the data in each object.
> ## **_Structure_** 
> ![Flyweight](https://refactoring.guru/images/patterns/diagrams/flyweight/structure.png)

## <li> **Proxy**
When we want to provide a substitute or placeholder for another object. A proxy controls access to the original object, allowing you to perform something either before or after the request gets through to the original object.
> ## **_Structure_** 
> ![Proxy](https://refactoring.guru/images/patterns/diagrams/proxy/structure.png)

# 3) Behavioral patterns 
These patterns are concerned with algorithms and the assignment of responsibilities between objects.
