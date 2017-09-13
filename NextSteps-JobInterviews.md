# Preparing a Job Interview
Or what you need to know to be a good developer.

## General
* [Whiteboarding](https://writing.pupius.co.uk/whiteboarding-4df873dbba2e) (Nov 20, 2012) - If you are interviewing for a programming job it is almost inevitable that you will be asked to do some coding on a whiteboard. In this post I’m not commenting on the validity of this style of interview (though I do personally find whiteboard coding a useful way to see how candidates work through problems) but instead pointing out some common pitfalls that can be avoided, given that this is how tech companies interview.
* [97 Things Every Programmer Should Know](http://programmer.97things.oreilly.com/wiki/index.php/Contributions_Appearing_in_the_Book) - The collection is intended simply to contain multiple and varied perspectives on what it is that contributors to the project feel programmers should know. This can be anything from code-focused advice to culture, from algorithm usage to agile thinking, from implementation know-how to professionalism, from style to substance.
* [The Joel Test For Programmers (The Simple Programmer Test)](https://simpleprogrammer.com/2015/02/16/joel-test-programmers-simple-programmer-test/) (Feb 16, 2015) - The Joel Test is great for software development shops and for programmers that are interested in quickly evaluating a company's software development environment, but what about a Joel Test for actual programmers? Several people have asked me lately if I had an idea for a Joel Test to evaluate an actual programmer, rather than a software development organization, so I've decided to put together a list of what I think might be a good equivalent of the Joel Test for evaluating the skills of an actual software developer.
* [Interview Questions & Answers](https://biginterview.com/blog/interview-questions-answers) - Knowing how to put together a strong answer to the most common interview questions is obviously key to landing a job. The art and science of creating great answers involves being strategic in crafting your responses as well as practicing till you’re as strong a possible. The best job candidates are not lucky. They spend a ton of time both on preparation because they know how important that 30-60 minute interview can be to their entire career. If you’d prefer to get started with a free resource before paying for a coach or a program, this tutorial is designed to get you up and running with the basics for acing your next interview (in ten easy lessons).
* [HOW TO ANSWER: Tell Me About Yourself](https://biginterview.com/blog/2011/09/tell-me-about-yourself.html) (Sep, 2011) - There are some job interview questions that are guaranteed to come up in most (if not all) of your job interviews — regardless of your industry, your experience level, and job type. At the top of this list is the universal and much-dreaded classic: “Tell me about yourself.” This question (or a variation like “Walk me through your background”) comes up in just about every job interview and many job searchers hate it. This question is an opportunity — an opening for you to set the tone of the job interview and emphasize the points that you most want this potential employer to know about you.
* [Answering Behavioral Interview Questions: Your Greatest Accomplishments](https://biginterview.com/blog/2017/04/greatest-accomplishment-question.html) - If your interviewer asks you this question, consider yourself lucky. It’s the perfect opportunity to talk about your most impressive experience. Unfortunately, most candidates waste this wonderful opportunity because they aren’t prepared and/or don’t feel comfortable “bragging.”

## Object Oriented Design Principles
* [Object-oriented programming](https://en.wikipedia.org/wiki/Object-oriented_programming)
* [10 Object Oriented Design Principles Java Programmer should know](http://javarevisited.blogspot.de/2012/03/10-object-oriented-design-principles.html)
* [Introduction to Object Oriented Programming Concepts (OOP) and More](http://www.codeproject.com/Articles/22769/Introduction-to-Object-Oriented-Programming-Concep)
* [S.O.L.I.D: The First 5 Principles of Object Oriented Design](https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design)
* [JavaBeat Design Patterns Articles](http://www.javabeat.net/tag/design-patterns/)
* [Design Patterns Interview Questions](http://www.javabeat.net/design-patterns-interview-questions/)

### SOLID
S.O.L.I.D. is an acronym for the first five object-oriented design(OOD) principles by Robert C. Martin, popularly known as Uncle Bob.
These principles, when combined together, make it easy for a programmer to develop software that are easy to maintain and extend. They also make it easy for developers to avoid code smells, easily refactor code, and are also a part of the agile or adaptive software development.

#### Single-responsibility Principle (SRP)
> A class should have one and only one reason to change, meaning that a class should have only one job.

#### Open-closed Principle (OCP)
> Objects or entities should be open for extension, but closed for modification.

#### Liskov substitution principle (LSP)
> Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.

#### Interface segregation principle (ISP)
> A client should never be forced to implement an interface that it doesn’t use or clients shouldn’t be forced to depend on methods they do not use.

#### Dependency Inversion principle (DIP)
>Entities must depend on abstractions not on concretions. It states that the high level module must not depend on the low level module, but they should depend on abstractions.

* [S.O.L.I.D: The First 5 Principles of Object Oriented Design](https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design)
* [The SOLID Principles](http://code.tutsplus.com/series/the-solid-principles--cms-634) - Four posts about five agile principles that should guide you every time you write code.
* [SOLID (object-oriented design)](https://en.wikipedia.org/wiki/SOLID_%28object-oriented_design%29)



## Design Patterns

[Design patterns implemented in Java](http://java-design-patterns.com/) - usefull collection of 93 patterns ([source code on GitHub](https://github.com/iluwatar/java-design-patterns))

A design pattern is a solution to a general software problem within a particular context.

* Context : A recurring set of situations where the pattern applies.
* Problem : A system of forces (goals and constraints) that occur repeatedly in this context.
* Solution : A description of communicating objects and classes (collaboration) that can be applied to resolve those forces.

Design patterns capture solutions that have evolved over time as developers strive for greater flexibility in their software. Whereas class libraries are reusable source code, and components are reusable packaged objects, patterns are generic, reusable design descriptions that are customized to solve a specific problem. The study of design patterns provides a common vocabulary for communication and documentation, and it provides a framework for evolution and improvement of existing patterns.

* Creational patterns (5)
	* [Abstract factory](http://java-design-patterns.com/patterns/abstract-factory/)
	* [Builder](http://java-design-patterns.com/patterns/builder/)
	* [Factory Method](http://java-design-patterns.com/patterns/factory-method/)
	* [Prototype](http://java-design-patterns.com/patterns/prototype/)
	* [Singleton](http://java-design-patterns.com/patterns/singleton/)
		* [Avoid Singletons to Write Testable Code](https://codeahoy.com/2016/05/27/avoid-singletons-to-write-testable-code/) (May 27, 2016) - Often times there is a need to share a single object of a class throughout the code base. This is a valid and a very common requirement but is often equated and related to a design pattern called Singleton. While they provide a quick and easy solution, singletons are considered bad because they make unit testing and debugging difficult.
* Structural patterns (7)
	* Adapter pattern
	* Bridge pattern
	* Composite pattern
	* Decorator pattern
	* Facade pattern
	* Flyweight pattern
	* Proxy pattern
* Behavioral patterns (11)
	* Chain-of-responsibility pattern
	* Command pattern
	* Interpreter pattern
	* Iterator pattern
	* Mediator pattern
	* Memento pattern
	* Observer pattern
	* State pattern
	* Strategy pattern
	* Template method pattern
	* Visitor pattern



## Java
* [115 Java Interview Questions and Answers – The ULTIMATE List (PDF Download)](http://www.javacodegeeks.com/2014/04/java-interview-questions-and-answers.html) - In this tutorial we will discuss about different types of questions that can be used in a Java interview, in order for the employer to test your skills in Java and object-oriented programming in general. In the following sections we will discuss about object-oriented programming and its characteristics, general questions regarding Java and its functionality, collections in Java, garbage collectors, exception handling, Java applets, Swing, JDBC, Remote Method Invocation (RMI), Servlets and JSP.
* [Top 20 Core Java Interview Questions and Answers from Investment Banks](https://www.javacodegeeks.com/2015/11/top-20-core-java-interview-questions-and-answers-from-investment-banks.html) (Nov 7, 2015) by [Javin Paul](https://twitter.com/javinpaul) - This is a new series of sharing core Java interview questions and answers on the Finance domain and mostly on big Investment banks.
* [Top 10 Tricky Java interview questions and Answers](http://www.java67.com/2012/09/top-10-tricky-java-interview-questions-answers.html) (Sep, 2012) - What is a tricky question? Well, tricky Java interview questions are those questions which have some surprise element on it. If you try to answer a tricky question with common sense, you will most likely fail because they require some specific knowledge. Most of the tricky Java questions comes from confusing concepts like function overloading and overriding, Multi-threading which is really tricky to master, character encoding, checked vs unchecked exceptions and subtle Java programming details like Integer overflow. Most important thing to answer a tricky Java question is attitude and analytical thinking, which helps even if you don't know the answer. Anyway in this Java article we will see 10 Java questions which are real tricky and requires more than average knowledge of Java programming language to answer them correctly. As per my experience, there is always one or two tricky or tough Java interview question on any core Java or J2EE interviews, so it's good to prepare tricky questions from Java in advance.
* [Clean and SOLID Java EE code in practice](http://www.codebulb.ch/2015/06/clean-and-solid-java-ee-code-in-practice-part-1.html) (Jun 14, 2015) - Writing software to deliver functionality is not enough in the real world. Software has to be maintainable right after its initial programming, and typically for many years after its release. Luckily, there are some well-established design patterns and best practices which help us achieve high software quality. Rather than publishing another article about how things are done in the perfect world, I will here present some real-world examples of violated or misinterpreted design patterns I found throughout my career – and how to fix them.
* [The Vital Guide to Java Interviewing](https://www.toptal.com/java#hiring-guide) by [Toptal](https://www.toptal.com/) - Mastering Java is no small feat. Its extensive class libraries contain a wide array of capabilities and nuances, many of which are lost on the average developer. Those who have mastered the language can have a significant positive impact on your team's productivity and on your system's performance. Here are some targeted questions to help identify true masters of the language.
* [Essential Java Interview Questions](https://www.toptal.com/java/interview-questions) by [Toptal](https://www.toptal.com/) -  There is more to interviewing than tricky technical questions, so these are intended merely as a guide. Not every “A” candidate worth hiring will be able to answer them all, nor does answering them all guarantee an “A” candidate. At the end of the day, [hiring remains an art, a science — and a lot of work](https://www.toptal.com/freelance/in-search-of-the-elite-few-finding-and-hiring-the-best-developers-in-the-industry).
* [20 Things Every Experienced Java Developer Must Know](http://www.fromdev.com/2009/05/as-java-developer-what-should-i-be.html) (May 1st, 2009) -We have short listed some of the highly recommended concepts and components of Java language for beginners and senior programmers. These things to learn in java may help you get the best Java developer job you deserve.
* [How To Be Well Prepared For a Java Programmer Interview](http://www.itavalon.com/well-prepared-java-programmer-interview/) (Feb 19, 2015) - The resume worked, you got an interview set for a Java Programmer position. That’s the first step and clearly you are on the right path, now you need to wow them in person and that takes some time and preparation. Don’t wing it, you will fail and lose this opportunity. This is test time, just like school all over again. You know the material, however, you need to prepare to sell not only your knowledge, but you as a viable candidate. Here are some sites that have great tips on how to prepare and what you should be ready to answer.
* [133 Java Interview Questions Answers From Last 5 Years - The MEGA List](http://javarevisited.blogspot.sg/2015/10/133-java-interview-questions-answers-from-last-5-years.html) - Since I like to explore interview questions, I have got this huge list of questions with me, which contains lots and lots of questions from different topics. I have been preparing this MEGA list from quite sometime and now It's ready to share with you guys. It contains interview questions not only from classic topics like threads, collections, equals and hashcode, sockets, but also from NIO, array, string, java 8 and many more.
* [Top 10 Free Java Programming Books, EBooks and PDF download](http://javarevisited.blogspot.it/2017/05/top-10-free-java-programming-books-ebooks-pdf.html) (May 2017) - The search goes on and while browsing the net a couple of days back I hit the Jackpot when I found these free Java books from Oreilly. Unlike most of the books, these free Java books are good, up-to-date and cover latest technologies like Java 8, MicroServices, Docker, Java EE, Functional Programming and Core Java.
* [Java67](http://www.java67.com/) by [Javin Paul](https://twitter.com/javinpaul) - Java Programming tutorials and Interview Questions
* [CodeAhoy - Posts](https://codeahoy.com/posts/) by [Umer Mansoor]
* [Concurrent Programming posts](https://10kloc.wordpress.com/category/concurrent-programming/) at [10K-LOC](https://10kloc.wordpress.com/)

### Microservices
* [Microservices for Java Developers](http://www.oreilly.com/programming/free/microservices-for-java-developers.csp) (free book) - A Hands-On Introduction to Frameworks and Containers.
* [Microservices Architecture Guide](https://www.datawire.io/guide) - This Guide provides detailed background and an opinionated reference architecture built around Kubernetes, Docker, and Envoy. We hope you'll find everything you need to set up your infrastructure to support microservices.
* [Microservices Stories](https://www.datawire.io/microservices-stories/) - We’ve collected the stories of how companies have implemented microservices at scale. Posts can be filtered according to the different challenges of adopting microservices, and different company sizes.

### Topics
* [Java Threads in 60 Seconds](https://in60secondsblog.wordpress.com/2015/12/13/java-threads-in-60-seconds/) (Dec 13, 2015)
* [Microservices in 60 Seconds](https://in60secondsblog.wordpress.com/2015/12/12/microservices-in-60-seconds/) (Dec 12, 2015)
* [Buggy Java Code: The Top 10 Most Common Mistakes That Java Developers Make](https://www.toptal.com/java/top-10-most-common-java-development-mistakes)
* [Automated Tests Help Developers Sleep Better](https://codeahoy.com/2016/11/12/automated-tests-help-developers-sleep-better/) (Nov 12, 2016) - Most developers hate testing. They tend to test gently, subconsciously knowing where the code will break and avoiding the weak spots. Pragmatic Programmers are different. We are driven to find our bugs now, so we don’t have to endure the shame of others finding our bugs later.
* [Command Line Flags for the JVM](https://10kloc.wordpress.com/2013/05/10/command-line-options-in-java-virtual-machine/) (May 10, 2013) - This post attempts to demystify command-line options of the Java Virtual Machine (JVM). I’m talking about those strange characters you often have to type when starting Java to run a program. The options are often used to specify environment variables (class path), configure  performance characteristics of the JVM (garbage collection frequency), amongst many other things.
* [Things every Java developer must know about Exception handling](https://10kloc.wordpress.com/2013/03/09/runtimeexceptions-try-catch-or-not-to-catch/) (Mar 9, 2013) - Exceptions are one of the most misunderstood (and misused) features of the Java programming language. This article describes the absolute minimum every Java developer must know about exceptions. It assumes that the reader is somewhat familiar with Java.
* [Skeletal Implementations in Java Explained - Abstract Interfaces](https://10kloc.wordpress.com/2012/12/03/abstract-interfaces-the-mystery-revealed/) (Dec 3, 2012) - Using Interfaces, as a general contract, has many benefits over Inheritance. Inheritance, however has its own place in programming, and often times is a necessary evil. In this post, we explored Abstract Interfaces which combine the power of Interfaces with Inheritance. Abstract Interface is a term for Abstract Class, which implements all the functionality of an Interface. Abstract Interfaces always go with the Interfaces they are supporting.
* [Difference between Inheritance and Composition in Java OOP](http://javarevisited.blogspot.sg/2015/06/difference-between-inheritance-and-Composition-in-Java-OOP.html)
* [What is final in Java? Final variable, Method and Class Example](http://javarevisited.blogspot.it/2011/12/final-variable-method-class-java.html)

### Java versions cronology
* [The Java Programming Language](https://en.wikipedia.org/wiki/Java_\(programming_language\)) - Java is a general-purpose computer programming language that is concurrent, class-based, object-oriented,[14] and specifically designed to have as few implementation dependencies as possible. It is intended to let application developers "write once, run anywhere" (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation. Java applications are typically compiled to bytecode that can run on any Java virtual machine (JVM) regardless of computer architecture. As of 2016, Java is one of the most popular programming languages in use, particularly for client-server web applications, with a reported 9 million developers. Java was originally developed by James Gosling at Sun Microsystems (which has since been acquired by Oracle Corporation) and released in 1995 as a core component of Sun Microsystems' Java platform. The language derives much of its syntax from C and C++, but it has fewer low-level facilities than either of them.
* [Java Platform, Standard Edition](https://en.wikipedia.org/wiki/Java_Platform,_Standard_Edition) - Java Platform, Standard Edition or Java SE is a widely used computing platform for development and deployment of portable code for desktop and server environments. Java SE was formerly known as Java 2 Platform, Standard Edition or J2SE.
* [Java version history](https://en.wikipedia.org/wiki/Java_version_history) - The Java language has undergone several changes since JDK 1.0 as well as numerous additions of classes and packages to the standard library. In addition to the language changes, much more dramatic changes have been made to the Java Class Library over the years, which has grown from a few hundred classes in JDK 1.0 to over three thousand in J2SE 5. Entire new APIs, such as Swing and Java2D, have been introduced, and many of the original JDK 1.0 classes and methods have been deprecated. 
* [Java Platform, Enterprise Edition](https://en.wikipedia.org/wiki/Java_Platform,_Enterprise_Edition) - Java Platform, Enterprise Edition or Java EE is a widely used computing platform for development and deployment of enterprise software (network and web services).[1] Java EE was formerly known as Java 2 Platform, Enterprise Edition or J2EE. The platform uses the object-oriented Java programming language. It is part of the Java software-platform family. Java EE extends the Java Platform, Standard Edition (Java SE),[2] providing an API for object-relational mapping, distributed and multitier architectures, and web services. The platform incorporates a design based largely on modular components running on an application server. The platform emphasizes convention over configuration[3] and annotations for configuration. Optionally XML can be used to override annotations or to deviate from the platform defaults.
* [Java EE version history](https://en.wikipedia.org/wiki/Java_EE_version_history) - The Java Platform, Enterprise Edition or Java EE (formerly known as Java 2 Platform, Enterprise Edition or J2EE) has undergone several changes since 1.0 as well as numerous additions of new specifications.


## Android
* [Interviewing Android Developers](https://android.jlelse.eu/interviewing-android-developers-435ce69b06fa) (Apr 12, 2017)
* [Top traits of a great mobile developer](http://blog.duckma.com/2016/02/top-traits-of-great-mobile-developer.html)


## SQL
* [Fundamentals of Relational Database Design](http://r937.com/relational.html)
* [SQL Server T-SQL Recipes, 4th Edition](http://it-ebooks.info/book/6540/) (2015) - SQL Server T-SQL Recipes is an example-based guide to the Transact-SQL language that is at the core of SQL Server. This edition has been lightly updated for SQL Server 2014 and provides ready-to-implement solutions to common programming and database administration tasks. Learn to create databases, create in-memory tables and stored procedures, insert and update data, generate reports, secure your data, and more. Tasks and their solutions are broken down into a problem/solution format that is quick and easy to read so that you can get the job done fast when the pressure is on. Solutions in this book are divided into chapters by problem domain. Each chapter is a collection of solutions around a single facet of the language such as writing queries, managing indexes, error handling, and query performance. Each solution is presented code-first, giving you a working code example to copy from and implement immediately in your own environment. Following each example is an in-depth description of how and why the given solution works. Tradeoffs and alternative approaches are also discussed.
	* [AdventureWorks Databases – 2012, 2008R2 and 2008](http://msftdbprodsamples.codeplex.com/releases/view/93587) - This release consolidates AdventureWorks databases for SQL Server 2012, 2008R2 and 2008 versions to one page. Each zip file contains an mdf database file and ldf log file. This should make it easier to find and download AdventureWorks databases since all OLTP versions are on one page. There are no database schema changes.
* [SQL and Relational Theory, 3rd Edition](http://it-ebooks.info/book/6450/) (2015) - SQL is full of difficulties and traps for the unwary. You can avoid them if you understand relational theory, but only if you know how to put that theory into practice. In this book, Chris Date explains relational theory in depth, and demonstrates through numerous examples and exercises how you can apply it to your use of SQL. This third edition has been revised, extended, and improved throughout. Topics whose treatment has been expanded include data types and domains, table comparisons, image relations, aggregate operators and summarization, view updating, and subqueries. A special feature of this edition is a new appendix on NoSQL and relational theory.

#### SQL Exercises
* [Where are some useful SQL puzzles to teach SQL in a workplace?](http://dba.stackexchange.com/questions/29/where-are-some-useful-sql-puzzles-to-teach-sql-in-a-workplace) - I'm looking for beginner and intermediate level SQL puzzles, that I can point trainees at for practice. I'm aware of http://sqlzoo.net/ which is a great resource - is there anything else out there that you could suggest?
	* [SQLZOO](http://sqlzoo.net/) - SQLZoo includes tutorials and reference to support people learning SQL.
* [SQL exercises](http://www.sql-ex.ru/) - This site will help everyone to gain or improve skills in building SQL Data Manipulation Language statements. To train You will have to build yourself the SQL statements for retrieval or modification of specific data required in the exercises.


## About FinTech
* [The next FinTech Chapter - current observations on the FinTech market](https://www.linkedin.com/pulse/next-fintech-chapter-current-observations-market-matthias-lange) (Feb 19, 2017) by [Matthias Lange
](https://twitter.com/matthiaslange) - Many people think of FinTech as a new hip trend. The reality, however, is that FinTech is maturing. The times when FinTech was only a fancy app are over, making it much more than just a nice customer frontend. Consequently, business models in the FinTech industry are moving away from the (retail) consumer interface towards innovation that includes the backend and solutions that are focused on corporate customers.
* [Big Data in 2017: 10 Predictions Everyone Should Read](https://www.ciklum.com/blog/big-data-in-2017-10-predictions-everyone-should-read/) (Oct 19, 2016) - Big data has been an emerging trend in the business world for the last few years, and as more devices are getting connected to the web, big data will only continue to grow both in influence and in size. With that in mind, [Ciklum’s Big Data Engineering team](https://www.ciklum.com/our-expertise/big-data-analytics/) has made 10 predictions for big data over the next year.

## CSharp
* [CSharp Language Version History](https://github.com/dotnet/csharplang/blob/master/Language-Version-History.md) - Features Added in CSharp Language Versions
* [Essential C# Interview Questions](https://www.toptal.com/c-sharp/interview-questions) by [Toptal](https://www.toptal.com/)
* [The Vital Guide to C# Interviewing](https://www.toptal.com/c-sharp) by [Toptal](https://www.toptal.com/) - This article should help you identify a developer that understands C# in its core. Regardless on the application type, techniques and tips mentioned below should be universal to all C# developers and they should all be able to demonstrate extensive understanding of these topics.
* [Buggy C# Code: The 10 Most Common Mistakes That C# Developers Make](https://www.toptal.com/c-sharp/top-10-mistakes-that-c-sharp-programmers-make) by [Toptal](https://www.toptal.com/) - This tutorial describes 10 of the most common programming mistakes made, or problems to be avoided, by C# programmers and provide them with help.
* [ASP.NET Data Access Options](https://msdn.microsoft.com/en-us/library/ms178359.aspx#dbfmfcf) - ASP.NET provides many options for storing, retrieving, and displaying data. For developers who are new to ASP.NET, the appropriate options are not always obvious. This topic provides ecommendations and guidelines for choosing the options that best fit your scenario.
* [The Beginner's Guide to LINQ in .NET](https://www.exceptionnotfound.net/linq-for-beginners/) (Apr 24, 2015) - LINQ stands for Language INtegrated Query, a feature of .NET that was released as part of version 3.5 way back in 2007. It greatly improved the ability of C# and VB programmers to handle and parse data in business-level code. What LINQ does is provide a syntax that allows business-level programmers to query sets of data without needing to know any SQL.
* [Singleton in C# – Pattern or Anti-pattern](http://www.dotnetcurry.com/patterns-practices/1350/singleton-design-anti-pattern-csharp) - Singleton is one of the basic software design patterns from the Gang of four book. It is an appropriate choice for providing managed access to unique external resources, but can quickly be abused by storing global state in it. Even without that, it can introduce difficulties when writing unit tests or developing multi/threaded applications.  
As an alternative to singletons, we can pass the instance as an explicit dependency to class constructors that need it. To make this process easier, we can use a dependency injection library. Some application frameworks already have such a library built into them which can provide a complete replacement for the singleton pattern.
* [Getting started with ASP.NET Core MVC and Entity Framework Core using Visual Studio (1 of 10)](https://docs.microsoft.com/en-us/aspnet/core/data/ef-mvc/intro) - The Contoso University sample web application demonstrates how to create ASP.NET Core 1.1 MVC web applications using Entity Framework Core 1.1 and Visual Studio 2017.
* [Getting Started with Entity Framework 6 Code First using MVC 5](https://docs.microsoft.com/en-us/aspnet/mvc/overview/getting-started/getting-started-with-ef-using-mvc/creating-an-entity-framework-data-model-for-an-asp-net-mvc-application) - The Contoso University sample web application demonstrates how to create ASP.NET MVC 5 applications using the Entity Framework 6 and Visual Studio 2013. This tutorial uses the Code First workflow. For information about how to choose between Code First, Database First, and Model First, see [Entity Framework Development Workflows](https://msdn.microsoft.com/en-us/library/ms178359.aspx#dbfmfcf).
* [ASP.NET MVC interview questions with answers](http://www.codeproject.com/Articles/556995/ASP-NET-MVC-interview-questions-with-answers) (Dec 23, 2014) - The whole purpose of this article is to quickly brush up your MVC knowledge from ASP.NET MVC interview perspective.

### Async/Await
* [Improving Your Asynchronous Code Using Tasks, Async and Await](http://www.infoq.com/articles/Tasks-Async-Await)
* [Async and Await](http://blog.stephencleary.com/2012/02/async-and-await.html)

### .NET Cronology
* Visual Studio
	* [Microsoft Visual Studio History](https://en.wikipedia.org/wiki/Microsoft_Visual_Studio#History)
* .NET Framework
	* [.NET Framework version history](https://en.wikipedia.org/wiki/.NET_Framework_version_history)
* ASP.NET
	* [ASP.NET MVC](http://www.asp.net/mvc) - ASP.NET MVC gives you a powerful, patterns-based way to build dynamic websites that enables a clean separation of concerns and that gives you full control over markup for enjoyable, agile development. ASP.NET MVC includes many features that enable fast, TDD-friendly development for creating sophisticated applications that use the latest web standards.
		* [ASP.NET MVC on Wikipedia](https://en.wikipedia.org/wiki/ASP.NET_MVC)
	* [Web API](http://www.asp.net/web-api) - ASP.NET Web API is a framework that makes it easy to build HTTP services that reach a broad range of clients, including browsers and mobile devices. ASP.NET Web API is an ideal platform for building RESTful applications on the .NET Framework.
		* [Web API on Nuget](https://www.nuget.org/packages/Microsoft.AspNet.WebApi/)
		* [Web API Version History](http://stackoverflow.com/a/30347209)
* SQL Server
* Windows

### Micro ORM
* [.NET Micro-ORMs - Dapper, PetaPoco, and more](http://www.nullskull.com/a/1659/net-microorms--dapper-petapoco-and-more.aspx)
* [Dapper vs Entity Framework vs ADO.NET Performance Benchmarking](https://www.exceptionnotfound.net/dapper-vs-entity-framework-vs-ado-net-performance-benchmarking/)
* [PetaPoco](http://www.toptensoftware.com/petapoco/) - A tiny ORM-ish thing for your POCOs
* [PetaPoco can cause high memory usage with certain queries](http://shazwazza.com/post/petapoco-can-cause-high-memory-usage-with-certain-queries/)
* [Dapper-dot-net](http://stackexchange.github.io/dapper-dot-net/) - a simple object mapper for .Net
* [StackExchange/StackExchange.Redis](https://github.com/StackExchange/StackExchange.Redis) - StackExchange.Redis is a high performance general purpose redis client for .NET languages (C# etc). It is the logical successor to [BookSleeve](https://code.google.com/p/booksleeve/), and is the client developed-by (and used-by) [Stack Exchange](http://stackexchange.com/) for busy sites like [Stack Overflow](http://stackoverflow.com/). For the full reasons why this library was created (i.e. "What about BookSleeve?") [please see here](http://marcgravell.blogspot.com/2014/03/so-i-went-and-wrote-another-redis-client.html).

### Misc
* [EntityFramework.SqlServerCompact](https://www.nuget.org/packages/EntityFramework.SqlServerCompact/)
* [Getting Started with Entity Framework 6 Code First using MVC 5](https://www.asp.net/mvc/overview/getting-started/getting-started-with-ef-using-mvc/creating-an-entity-framework-data-model-for-an-asp-net-mvc-application)
* [Nullable DateTime with SQLDataReader - DataReader Extension](http://stackoverflow.com/a/17490905)
* [What's better: DataSet or DataReader?](http://stackoverflow.com/a/1083203)
* [Generate class from database table](http://stackoverflow.com/a/5873231) - SQL script for POCO model generation
* [What does “where T : class, new()” mean?](http://stackoverflow.com/questions/4737970/what-does-where-t-class-new-mean)
* [Building C# objects dynamically](https://www.oreilly.com/learning/building-c-objects-dynamically) (July 29, 2015) - Use ExpandoObject to create objects that can be enhanced with properties, methods, and events.



