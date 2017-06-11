# Preparing a Job Interview
Or what you need to know to be a good developer.

## General
* [Whiteboarding](https://writing.pupius.co.uk/whiteboarding-4df873dbba2e) (Nov 20, 2012) - If you are interviewing for a programming job it is almost inevitable that you will be asked to do some coding on a whiteboard. In this post I’m not commenting on the validity of this style of interview (though I do personally find whiteboard coding a useful way to see how candidates work through problems) but instead pointing out some common pitfalls that can be avoided, given that this is how tech companies interview.
* [97 Things Every Programmer Should Know](http://programmer.97things.oreilly.com/wiki/index.php/Contributions_Appearing_in_the_Book)

## Android
* [Interviewing Android Developers](https://android.jlelse.eu/interviewing-android-developers-435ce69b06fa) (Apr 12, 2017)
* [Top traits of a great mobile developer](http://blog.duckma.com/2016/02/top-traits-of-great-mobile-developer.html)

## CSharp
* [CSharp Language Version History](https://github.com/dotnet/csharplang/blob/master/Language-Version-History.md) - Features Added in CSharp Language Versions
* [6 Essential C# Interview Questions](https://www.toptal.com/c-sharp/interview-questions)
* [The Vital Guide to C# Interviewing](https://www.toptal.com/c-sharp)
* [Test Your C# Basics](http://www.dotnetcurry.com/csharp/1280/test-your-csharp-basics)
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

### SQL
* [Fundamentals of Relational Database Design](http://r937.com/relational.html)
* [SQL Server T-SQL Recipes, 4th Edition](http://it-ebooks.info/book/6540/) (2015) - SQL Server T-SQL Recipes is an example-based guide to the Transact-SQL language that is at the core of SQL Server. This edition has been lightly updated for SQL Server 2014 and provides ready-to-implement solutions to common programming and database administration tasks. Learn to create databases, create in-memory tables and stored procedures, insert and update data, generate reports, secure your data, and more. Tasks and their solutions are broken down into a problem/solution format that is quick and easy to read so that you can get the job done fast when the pressure is on. Solutions in this book are divided into chapters by problem domain. Each chapter is a collection of solutions around a single facet of the language such as writing queries, managing indexes, error handling, and query performance. Each solution is presented code-first, giving you a working code example to copy from and implement immediately in your own environment. Following each example is an in-depth description of how and why the given solution works. Tradeoffs and alternative approaches are also discussed.
	* [AdventureWorks Databases – 2012, 2008R2 and 2008](http://msftdbprodsamples.codeplex.com/releases/view/93587) - This release consolidates AdventureWorks databases for SQL Server 2012, 2008R2 and 2008 versions to one page. Each zip file contains an mdf database file and ldf log file. This should make it easier to find and download AdventureWorks databases since all OLTP versions are on one page. There are no database schema changes.
* [SQL and Relational Theory, 3rd Edition](http://it-ebooks.info/book/6450/) (2015) - SQL is full of difficulties and traps for the unwary. You can avoid them if you understand relational theory, but only if you know how to put that theory into practice. In this book, Chris Date explains relational theory in depth, and demonstrates through numerous examples and exercises how you can apply it to your use of SQL. This third edition has been revised, extended, and improved throughout. Topics whose treatment has been expanded include data types and domains, table comparisons, image relations, aggregate operators and summarization, view updating, and subqueries. A special feature of this edition is a new appendix on NoSQL and relational theory.

#### SQL Exercises
* [Where are some useful SQL puzzles to teach SQL in a workplace?](http://dba.stackexchange.com/questions/29/where-are-some-useful-sql-puzzles-to-teach-sql-in-a-workplace) - I'm looking for beginner and intermediate level SQL puzzles, that I can point trainees at for practice. I'm aware of http://sqlzoo.net/ which is a great resource - is there anything else out there that you could suggest?
	* [SQLZOO](http://sqlzoo.net/) - SQLZoo includes tutorials and reference to support people learning SQL.
* [SQL exercises](http://www.sql-ex.ru/) - This site will help everyone to gain or improve skills in building SQL Data Manipulation Language statements. To train You will have to build yourself the SQL statements for retrieval or modification of specific data required in the exercises.

## Java
* [Java Platform, Enterprise Edition](https://en.wikipedia.org/wiki/Java_Platform,_Enterprise_Edition) - Version History, APIs, Certified Applicantion Servers.
* [Java EE version history](https://en.wikipedia.org/wiki/Java_EE_version_history)
* [20 Java Interview Questions from Investment Banks (Answered)](http://www.codeproject.com/Tips/1061616/Java-Interview-Questions-from-Investment-Banks-Ans) - Some core Java questions from Interviews from Investment banks, good for technical round.
* [Java Questions and Answers](http://bit.ly/JavaInterviewApp) - This FREE app has core java interview questions for experienced developers as well as beginners. The questions and answers are based on 15+ years of java programming experience. Many questions are compiled from various sources including practical interviews, java websites and communities. 
* [Buggy Java Code: The Top 10 Most Common Mistakes That Java Developers Make](https://www.toptal.com/java/top-10-most-common-java-development-mistakes)
* [Java Interview Questions](https://www.toptal.com/java/interview-questions)
* [Skeletal Implementations in Java Explained - Abstract Interfaces](https://10kloc.wordpress.com/2012/12/03/abstract-interfaces-the-mystery-revealed/) (Dec 3, 2012) - Using Interfaces, as a general contract, has many benefits over Inheritance. Inheritance, however has its own place in programming, and often times is a necessary evil. In this post, we explored Abstract Interfaces which combine the power of Interfaces with Inheritance. Abstract Interface is a term for Abstract Class, which implements all the functionality of an Interface. Abstract Interfaces always go with the Interfaces they are supporting.