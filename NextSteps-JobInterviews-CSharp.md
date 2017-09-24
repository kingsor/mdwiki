# Preparing a Job Interview - CSharp

## General
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

## Async/Await
* [Improving Your Asynchronous Code Using Tasks, Async and Await](http://www.infoq.com/articles/Tasks-Async-Await)
* [Async and Await](http://blog.stephencleary.com/2012/02/async-and-await.html)

## .NET Cronology
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

## Micro ORM
* [.NET Micro-ORMs - Dapper, PetaPoco, and more](http://www.nullskull.com/a/1659/net-microorms--dapper-petapoco-and-more.aspx)
* [Dapper vs Entity Framework vs ADO.NET Performance Benchmarking](https://www.exceptionnotfound.net/dapper-vs-entity-framework-vs-ado-net-performance-benchmarking/)
* [PetaPoco](http://www.toptensoftware.com/petapoco/) - A tiny ORM-ish thing for your POCOs
* [PetaPoco can cause high memory usage with certain queries](http://shazwazza.com/post/petapoco-can-cause-high-memory-usage-with-certain-queries/)
* [Dapper-dot-net](http://stackexchange.github.io/dapper-dot-net/) - a simple object mapper for .Net
* [StackExchange/StackExchange.Redis](https://github.com/StackExchange/StackExchange.Redis) - StackExchange.Redis is a high performance general purpose redis client for .NET languages (C# etc). It is the logical successor to [BookSleeve](https://code.google.com/p/booksleeve/), and is the client developed-by (and used-by) [Stack Exchange](http://stackexchange.com/) for busy sites like [Stack Overflow](http://stackoverflow.com/). For the full reasons why this library was created (i.e. "What about BookSleeve?") [please see here](http://marcgravell.blogspot.com/2014/03/so-i-went-and-wrote-another-redis-client.html).

## Misc
* [EntityFramework.SqlServerCompact](https://www.nuget.org/packages/EntityFramework.SqlServerCompact/)
* [Getting Started with Entity Framework 6 Code First using MVC 5](https://www.asp.net/mvc/overview/getting-started/getting-started-with-ef-using-mvc/creating-an-entity-framework-data-model-for-an-asp-net-mvc-application)
* [Nullable DateTime with SQLDataReader - DataReader Extension](http://stackoverflow.com/a/17490905)
* [What's better: DataSet or DataReader?](http://stackoverflow.com/a/1083203)
* [Generate class from database table](http://stackoverflow.com/a/5873231) - SQL script for POCO model generation
* [What does “where T : class, new()” mean?](http://stackoverflow.com/questions/4737970/what-does-where-t-class-new-mean)
* [Building C# objects dynamically](https://www.oreilly.com/learning/building-c-objects-dynamically) (July 29, 2015) - Use ExpandoObject to create objects that can be enhanced with properties, methods, and events.

