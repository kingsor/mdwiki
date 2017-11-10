# Preparing a Job Interview - Principles

## Object Oriented Design Principles
* [Object-oriented programming](https://en.wikipedia.org/wiki/Object-oriented_programming)
* [10 Object Oriented Design Principles Java Programmer should know](http://javarevisited.blogspot.de/2012/03/10-object-oriented-design-principles.html)
* [Introduction to Object Oriented Programming Concepts (OOP) and More](http://www.codeproject.com/Articles/22769/Introduction-to-Object-Oriented-Programming-Concep)


## SOLID
S.O.L.I.D. is an acronym for the first five object-oriented design(OOD) principles by Robert C. Martin, popularly known as Uncle Bob.
These principles, when combined together, make it easy for a programmer to develop software that are easy to maintain and extend. They also make it easy for developers to avoid code smells, easily refactor code, and are also a part of the agile or adaptive software development.

### Single-responsibility Principle (SRP)
> A class should have one and only one reason to change, meaning that a class should have only one job.

### Open-closed Principle (OCP)
> Objects or entities should be open for extension, but closed for modification.

### Liskov substitution principle (LSP)
> Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.

### Interface segregation principle (ISP)
> A client should never be forced to implement an interface that it doesn’t use or clients shouldn’t be forced to depend on methods they do not use.

### Dependency Inversion principle (DIP)
>Entities must depend on abstractions not on concretions. It states that the high level module must not depend on the low level module, but they should depend on abstractions.

* [S.O.L.I.D: The First 5 Principles of Object Oriented Design](https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design)
* [The SOLID Principles](http://code.tutsplus.com/series/the-solid-principles--cms-634) - Four posts about five agile principles that should guide you every time you write code.
* [SOLID (object-oriented design)](https://en.wikipedia.org/wiki/SOLID_%28object-oriented_design%29)


## Design Patterns

[Design patterns implemented in Java](http://java-design-patterns.com/) - usefull collection of 93 patterns ([source code on GitHub](https://github.com/iluwatar/java-design-patterns))

> A design pattern is a solution to a general software problem within a particular context.

> * Context : A recurring set of situations where the pattern applies.
* Problem : A system of forces (goals and constraints) that occur repeatedly in this context.
* Solution : A description of communicating objects and classes (collaboration) that can be applied to resolve those forces.

> Design patterns capture solutions that have evolved over time as developers strive for greater flexibility in their software.  

> Whereas class libraries are reusable source code, and components are reusable packaged objects, patterns are generic, reusable design descriptions that are customized to solve a specific problem.  

> The study of design patterns provides a common vocabulary for communication and documentation, and it provides a framework for evolution and improvement of existing patterns.


* Creational patterns (5)
	* [Abstract factory](http://java-design-patterns.com/patterns/abstract-factory/)
	* [Builder](http://java-design-patterns.com/patterns/builder/)
	* [Factory Method](http://java-design-patterns.com/patterns/factory-method/)
	* [Prototype](http://java-design-patterns.com/patterns/prototype/)
	* [Singleton](http://java-design-patterns.com/patterns/singleton/)
		* [Avoid Singletons to Write Testable Code](https://codeahoy.com/2016/05/27/avoid-singletons-to-write-testable-code/) (May 27, 2016) - Often times there is a need to share a single object of a class throughout the code base. This is a valid and a very common requirement but is often equated and related to a design pattern called Singleton. While they provide a quick and easy solution, singletons are considered bad because they make unit testing and debugging difficult.
* Structural patterns (7)
	* Adapter
	* Bridge
	* Composite
	* Decorator
	* Facade
	* Flyweight
	* Proxy
* Behavioral patterns (11)
	* Chain-of-responsibility
	* Command
	* Interpreter
	* Iterator
	* Mediator
	* Memento
	* Observer
	* State
	* Strategy
	* Template Method
	* Visitor
