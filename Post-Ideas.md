
# Post ideas

## JavaScript: The World's Most Misunderstood Programming Language
[JavaScript: The World's Most Misunderstood Programming Language](http://javascript.crockford.com/javascript.html) by [Douglas Crockford](http://www.crockford.com/)

Is JavaScript object-oriented? It has objects which can contain data and methods that act upon that data. Objects can contain other objects. It does not have classes, but it does have constructors which do what classes do, including acting as containers for class variables and methods. **It does not have class-oriented inheritance, but it does have prototype-oriented inheritance**.

The two main ways of building up object systems are by inheritance (is-a) and by aggregation (has-a). JavaScript does both, but its dynamic nature allows it to excel at aggregation.

Some argue that JavaScript is not truly object oriented because it does not provide information hiding. That is, objects cannot have private variables and private methods: All members are public.

But it turns out that [JavaScript objects can have private variables and private methods](http://www.crockford.com/javascript/private.html). Of course, few understand this because JavaScript is the world's most misunderstood programming language.

Some argue that JavaScript is not truly object oriented because it does not provide inheritance. But it turns out that [JavaScript supports not only classical inheritance, but other code reuse patterns as well](http://javascript.crockford.com/inheritance.html).


## Prototype based vs. Class based inheritance
[Prototype based vs. Class based inheritance](http://stackoverflow.com/questions/816071/prototype-based-vs-class-based-inheritance)  

There are about a hundred terminology issues here, mostly built around someone (not you) trying to make their idea sound like The Best.

All object oriented languages need to be able to deal with several concepts:

* encapsulation of data along with associated operations on the data, variously known as data members and member functions, or as data and methods, among other things.
* inheritance, the ability to say that these objects are just like that other set of objects EXCEPT for these changes
* polymorphism ("many shapes") in which an object decides for itself what methods are to be run, so that you can depend on the language to route your requests correctly.
Now, as far as comparison:

First thing is the whole "class" vs "prototype" question. The idea originally began in Simula, where with a class-based method each class represented a set of objects that shared the same state space (read "possible values") and the same operations, thereby forming an equivalence class. If you look back at Smalltalk, since you can open a class and add methods, this is effectively the same as what you can do in Javascript.

Later OO languages wanted to be able to use static type checking, so we got the notion of a fixed class set at compile time. In the open-class version, you had more flexibility; in the newer version, you had the ability to check some kinds of correctness at the compiler that would otherwise have required testing.

In a "class-based" language, that copying happens at compile time. In a prototype language, the operations are stored in the prototype data structure, which is copied and modified at run time. Abstractly, though, a class is still the equivalence class of all objects that share the same state space and methods. When you add a method to the prototype, you're effectively making an element of a new equivalence class.

Now, why do that? primarily because it makes for a simple, logical, elegant mechanism at run time. now, to create a new object, or to create a new class, you simply have to perform a deep copy, copying all the data and the prototype data structure. You get inheritance and polymorphism more or less for free then: method lookup always consists of asking a dictionary for a method implementation by name.

The reason that ended up in Javascript/ECMA script is basically that when we were getting started with this 10 years ago, we were dealing with much less powerful computers and much less sophisticated browsers. Choosing the prototype-based method meant the interpreter could be very simple while preserving the desirable properties of object orientation.

> Written with [StackEdit](https://stackedit.io/).
