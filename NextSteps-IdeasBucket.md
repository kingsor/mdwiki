
# Next steps - Ideas Bucket

## About .NET past and future
* [After all, it might not matter - A commentary on the status of .NET](https://byterot.blogspot.it/2016/06/after-all-it-might-not-matter-commentary-status-of-dotnet-dotnetcore-csharp-oss-fsharp-dnx.html?m=1) (Jun 14, 2016) - What is worse is that the data showing with the announcement of #vNext aka #DNX aka #dotnetcore there was a sharp decline in the new OSS C# projects - the community is in a limbo situation waiting for the release - people find it pointless to create OSS projects on the current platform and the future platform is so much in flux which is not stable enough for innovation. With the recent changes announced, practically it will take another 12-18 months for it to stabilise (some might argue 6-12 months, fair enough, take what you like). For me this is the most alarming of all.


## REST Api Architecture
* [The Importance of Serializing API Output](https://philsturgeon.uk/api/2015/05/30/serializing-api-output/) (May 30 2015)  
when I talk about serialization, which I refer to as "adding a presentation layer to your data".
* [Building a Decent API](https://philsturgeon.uk/api/2013/07/12/building-a-decent-api/) (Jul 12 2013)  
PHP developers are increasingly moving over to API development, as are a lot of server-side developers. It's a trend that's been happening for the last few years and it's getting to the point where everyone and their dog are putting articles showing off how to build "awesome" API's. Unfortunately most of these are either woefully inadequate or are promoting bad practices. I'm not going to link to any bad examples because that's just rude, but here are some golden rules that I stick to when building out API's.
* [HTTP API Design Guide](https://github.com/interagent/http-api-design) (Jul 5, 2016)  
HTTP API design guide extracted from work on the [Heroku Platform API](https://devcenter.heroku.com/articles/platform-api-reference).
* [The Web API checklist - 43 things to think about](https://mathieu.fenniak.net/the-api-checklist/) (Apr 15, 2014)  
When you’re designing, testing, or releasing a new Web API, you’re building a new system on top of an existing complex and sophisticated system. At a minimum, you’re building upon HTTP, which is built upon TCP/IP, which is built upon a series of tubes. You’re also building upon a web server, an application framework, and maybe an API framework.  
Most people, myself included, are not aware of all the intricacies and nuances of every component they’re building upon. Even if you deeply understand each component, it’s probably going to be too much information to hold in your head at one time.
* [Best Practices for Designing a Pragmatic RESTful API](http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api) (Last updated Aug 12, 2015) - Your data model has started to stabilize and you're in a position to create a public API for your web app. You realize it's hard to make significant changes to your API once it's released and want to get as much right as possible up front. Now, the internet has no shortage on opinions on API design. But, since there's no one widely adopted standard that works in all cases, you're left with a bunch of choices: What formats should you accept? How should you authenticate? Should your API be versioned? In designing an API for [Enchant](http://www.enchant.com/) (a [Zendesk Alternative](http://www.enchant.com/zendesk-alternative)), I've tried to come up with pragmatic answers to these questions. My goal is for the [Enchant API](http://dev.enchant.com/api/v1) to be easy to use, easy to adopt and flexible enough to [dogfood](http://en.wikipedia.org/wiki/Eating_your_own_dog_food) for our own user interfaces.
* [Swagger](http://swagger.io/) - Swagger is a simple yet powerful representation of your RESTful API. With the largest ecosystem of API tooling on the planet, thousands of developers are supporting Swagger in almost every modern programming language and deployment environment. With a Swagger-enabled API, you get interactive documentation, client SDK generation and discoverability. We created Swagger to help fulfill the promise of APIs. Swagger helps companies like Apigee, Getty Images, Intuit, LivingSocial, McKesson, Microsoft, Morningstar, and PayPal build the best possible services with RESTful APIs. Now in version 2.0, Swagger is more enabling than ever. And it's 100% open source software.
	* [Swagger Editor](http://editor.swagger.io/) - An editor for designing Swagger specifications from scratch, using a simple YAML structure. [Source](https://github.com/swagger-api/swagger-editor)
	* [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) - Turn an API spec into client SDKs or server-side code. You can also generate API client or server using the online generator (https://generator.swagger.io).
* [OAI/OpenAPI-Specification](https://github.com/OAI/OpenAPI-Specification) - The goal of The OpenAPI Specification is to define a standard, language-agnostic interface to REST APIs which allows both humans and computers to discover and understand the capabilities of the service without access to source code, documentation, or through network traffic inspection. When properly defined via OpenAPI, a consumer can understand and interact with the remote service with a minimal amount of implementation logic. Similar to what interfaces have done for lower-level programming, OpenAPI removes the guesswork in calling the service.


## Web APIs, Building
- [Build APIs You Won't Hate](https://leanpub.com/build-apis-you-wont-hate) by [Phil Sturgeon](https://leanpub.com/u/philsturgeon)
- [Matthias Biehl](https://twitter.com/mattbiehl) - API Integration Architect | Innovation Catalyst | Digital Transformer | Author and Advisor [@API_University](https://twitter.com/API_University) - Zürich, CH - Stockholm, SE
- Working with Vagrant
- Creating REST Web API
	- with Nancy (ASP.NET)
	- with Node (Javascript)
	- with Laravel (PHP)


## ToRead List
* [moq/moq4](https://github.com/moq/moq4) - Moq (pronounced "Mock-you" or just "Mock") is the only mocking library for .NET developed from scratch to take full advantage of .NET Linq expression trees and lambda expressions, which makes it the most productive, type-safe and refactoring-friendly mocking library available. And it supports mocking interfaces as well as classes. Its API is extremely simple and straightforward, and doesn't require any prior knowledge or experience with mocking concepts.
* [Using dependency injection in Java](http://www.vogella.com/tutorials/DependencyInjection/article.html) by [Lars Vogel](http://www.vogella.com/) - This article describes the concept of dependency injection from a Java perspective.
* [Java 8, Lambda e la programmazione funzionale](http://www.mokabyte.it/2015/09/java8lambda/) - Un “esperimento” con le funzioni di ordine superiore.
* [IV parte: Codebase e Continuous Integration](http://www.mokabyte.it/2016/04/rapiddevelopment-4/) - in questo articolo, ci riallacciamo a quanto raccontato nelle parti precedenti della serie e guardiamo ad alcune strategie che la Continuous Integration la fanno fuori per davvero. Il fatto è che tali strategie di gestione del processo di sviluppo sono molto più comuni di quanto si pensi e che, soprattutto, vengono impiegate in ambiti in cui, in buona fede, si ritiene di fare Continuous Integration, Continuous Delivery e Continuous Deployment.


## Focus On

* [Electron](http://electron.atom.io/) - Build cross platform desktop apps with JavaScript, HTML, and CSS. If you can build a website, you can build a desktop app. Electron is a framework for creating native applications with web technologies like JavaScript, HTML, and CSS. It takes care of the hard parts so you can focus on the core of your application.
	* [Electron: Desktop Apps with Web Languages - GitHub Universe 2016](https://www.youtube.com/watch?v=FNHBfN8c32U) - In this session, hosted by Zeke Sikelianos, an Electron Developer at GitHub, we'll look at some of the amazing things you can create using features and tools Electron inherits from the Chromium browser, Node.js, and the vast ecosystem of npm modules.
	* [Marp](https://yhatt.github.io/marp/) - Markdown Presentation Writer
	* [Pencil Project](http://pencil.evolus.vn/) - Pencil is built for the purpose of providing a free and open-source GUI prototyping tool that people can easily install and use to create mockups in popular desktop platforms.
* [Is this my interface or yours?](https://medium.com/@jsaito/is-this-my-interface-or-yours-b09a7a795256) (Aug 8, 2016) - Why do products sometimes label things as my stuff, and sometimes label things as your stuff? As you tap around from app to app, you’ll see that there’s no standard way to refer to the things that belong to you within an interface. Some say it’s my stuff. Some say it’s your stuff.
* [Hygieia](https://developer.capitalone.com/opensource-projects/hygieia) - One Dashboard for the Entire CI/CD Pipeline. A single, configurable, easy to use dashboard to visualize near real-time status of the entire software delivery pipeline.
	* [capitalone/Hygieia](https://github.com/capitalone/Hygieia) - Hygieia℠ is a single, configurable, easy to use dashboard to visualize near real-time status of the entire delivery pipeline.


## Slack Alternatives
* [Five Open-Source Slack Alternatives](https://blog.okturtles.com/2015/11/five-open-source-slack-alternatives/) (Nov 2, 2015)
* [Rocket.Chat](https://rocket.chat/) - [demo](https://demo.rocket.chat/)
	* [Deploying Rocket.Chat on Vagrant with Ubuntu](https://rocket.chat/docs/installation/automation-tools/vagrant/)
* [Gabriel Engel: Building Rocket.Chat in Meteor](https://www.youtube.com/watch?v=yzkId54vng8)


## Web Apps Samples (Open Source)

### App for Conferences and Events
* [Connfa!](http://connfa.com/) - Open Source iOS & Android App for Conferences and Events
* [Squanchy](https://github.com/rock3r/squanchy) - Squanchy is an open source schedule platform for conferences. It was born as a fork of Connfa, but later diverged to embrace different design decision and user needs.

### Issue Tracker
* [NullDesk/TicketDesk](https://github.com/NullDesk/TicketDesk) (ASP.NET MVC 5, Entity Framework 6, C#) - TicketDesk is an issue tracking system for IT Help Desks. TicketDesk is efficient and designed to do only one thing, facilitate communications between help desk staff and end users. The overriding design goal is to be as simple and frictionless for both users and help desk staff as is possible.
* [Build A Support Ticket Application With Laravel – Part 2](https://scotch.io/tutorials/build-a-support-ticket-application-with-laravel-part-2) (Aug 15, 2016) - Learn how to build a support ticket application with Laravel.


## Meteor
* [An introduction to Meteor](https://www.youtube.com/watch?v=dOCMpoeuwTI)
* [10 Tips to Get a Job Working with Meteor](https://themeteorchef.com/blog/10-tips-to-get-a-job-working-with-meteor/) (Mar 28, 2016) - [Nate Strauser](http://natestrauser.me/)'s recommendations for developers looking to get a job with Meteor.
* [We Work Meteor](https://www.weworkmeteor.com/) - The premier job board and developer community space specifically for Meteor. [Source code](https://github.com/nate-strauser/wework) on GitHub.
* [Building An App In 45 Minutes With Meteor](https://www.smashingmagazine.com/2013/06/build-app-45-minutes-meteor/) (Jun 13, 2013) - what if I built an app that lets the user add their Twitter account to a list in a single click?
* [I’ve been running Meteor at scale for a year now. Here’s what I’ve learned.](https://medium.freecodecamp.com/scaling-meteor-a-year-on-26ee37588e4b#.ike82ll3a) (Dec 11, 2016) - A year ago I wrote an article describing my first experiences scaling Meteor. In short, I created a popular fantasy football website using Meteor. At a certain point, my service started slowing down. The single server I had running the game could no longer handle the load. I was able to solve these early scaling issues by — among other things — adding additional servers. Well, when last summer’s new season of football arrived, I once again ran into scaling issues. Adding more servers alone wouldn’t solve these problems. But I did manage to overcome them. This article will explain things I learned this time around, broken down into six pieces of practical advice.
	* [First Experiences Scaling a Meteor App](https://medium.freecodecamp.com/first-experiences-scaling-a-meteor-app-14a48e62a4af#.xr3jtm1ol) (Nov 2, 2015) - I recently went through the challenge and ordeal of having to scale my Meteor app. It’s a project that had already been running in production for about a year. This summer the app became a lot more popular with thousands of preseason signups. My initial setup could no longer handle the load and I was faced with a scaling problem that had to be solved quickly. This article describes the process I went through and some of the things I learnt along the way and my hope is that it will help others that face similar challenges in the future. It will cover the basics, such as what scaling is, and how load balancing works. It will also walk you through some basic setups, and show you how to scale your Meteor app.
	* [Minimum Viable DevOps](https://medium.freecodecamp.com/minimum-viable-devops-919972dfd9e0#.kb8cfek3x) (Jul 6, 2016) - Startup Genome says premature scaling is the number one cause of startup death. You shouldn’t spend time optimizing a product when you don’t even know if users want it. Yet every time you launch a web app, you run the risk of actually succeeding, and your server should be ready to handle the load. In this article I’ll share a simple, free recipe to get your app launch-ready. An hour spent following these steps will save you countless hours of sleep over the course of your product’s lifetime.


## PHP
* [PHP 6: Pissing in the Wind](https://philsturgeon.uk/php/2013/01/26/php-6-pissing-in-the-wind/)
* [HOW GOOD IS PHP?](http://www.webiny.com/blog/2015/01/06/how-good-is-php/) (Jan 9, 2015) - PHP is still, mostly thanks to Wordpress, the most widely used server-side language on the Internet (source). It is used on more than 82% of all websites. But why, with all that “glory”, some developers say it's a really bad language? They often use terms like "spaghetti code”, slow or even evil. In order to understand the origin of these standings, I will briefly go over the history of PHP.
* [PHP Releases](https://secure.php.net/releases/) - We have collected all the official information and code available for past PHP releases.

### Laravel
* [Getting Started With Laravel](http://code.tutsplus.com/tutorials/getting-started-with-laravel--cms-25386)
* [Laravel Homestead](https://laravel.com/docs/5.1/homestead)
* [Getting Started with Laravel Homestead](https://scotch.io/tutorials/getting-started-with-laravel-homestead) by [Scotch.io](https://scotch.io/) (Jul 16, 2014)
* [Laravel Quick Start - Basic Task List](https://laravel.com/docs/5.1/quickstart)
* [Laravel EU YouTube Channel](https://www.youtube.com/channel/UCb9XEo_1SDNR8Ucpbktrg5A)
* [Build A Support Ticket Application With Laravel – Part 1](https://scotch.io/tutorials/build-a-support-ticket-application-with-laravel-part-1) (Jul 27, 2016)
* [Token-Based Authentication for AngularJS and Laravel Apps](https://scotch.io/tutorials/token-based-authentication-for-angularjs-and-laravel-apps) (Jun 30, 2015)
* [Build a Time Tracker with Laravel 5 and AngularJS – Part 1](https://scotch.io/tutorials/build-a-time-tracker-with-laravel-5-and-angularjs-part-1) (Mar 26, 2015)
* [Build a Time Tracker with Laravel 5 and AngularJS – Part 2](https://scotch.io/tutorials/build-a-time-tracker-with-laravel-5-and-angularjs-part-2) (Apr 20, 2015)



## .NET Core
* [.NET Core and Visual Studio Code](https://code.visualstudio.com/docs/runtimes/dotnet) - .NET Core gives you a blazing fast and modular platform for creating server applications that run on Windows, Linux and Mac. Use Visual Studio Code with the C# extension to get a powerful editing experience with full support for C# IntelliSense (smart code completion) and debugging.
* [Integrating ASP.NET Core Web API and Entity Framework Core](http://www.mithunvp.com/aspnet-core-web-api-entity-framework-core/) - ASP.NET Core Web API and Entity Framework Core (EF Core) are the two latest Microsoft’s offerings into Open Source world gaining momentum. We will learn to integrate them together, being cross platform technologies you are not bound to Windows for learning.
* [Creating ASP.NET Core Web API in Visual Studio 2015](http://www.mithunvp.com/create-aspnet-mvc-6-web-api-visual-studio-2015/) - This tutorial lets us create very basic ASP.NET Core Web API using Visual Studio 2015. We will be creating Contacts API which lets do popular CRUD operations.
	* [ASP.NET Core Middleware – Write a Custom Middleware in Web API](http://www.mithunvp.com/write-custom-asp-net-core-middleware-web-api/) - ASP.NET Core Middleware concept is one of powerful features introduced, it gives us complete control over HTTP pipeline using Request and response. They effectively replacement for HttpModules and HttpHandlers. The scenario is “A user registers in our system to generate a “user-key“; using this key all requests are sent. The Web API project will check if “user-key” exists or not in header. If exists move ahead to validate if key is part of our registered user, if not then respond back with 401 status code. If key not present in Header then it will be Bad Request.
	* [Integrating ASP.NET Core Web API and Entity Framework Core](http://www.mithunvp.com/aspnet-core-web-api-entity-framework-core/) - EF Core is an object-relational mapper (O/RM) that enables .NET developers to work with a database using .NET objects. It eliminates the need for most of the data-access code that developers usually need to write. EF Core supports many database engines.
	* [mithunvp/ContactsAPI](https://github.com/mithunvp/ContactsAPI) - Contacts API is creating using ASP.NET Core Web API and using EF Core
* [kriasoft/aspnet-starter-kit](https://github.com/kriasoft/aspnet-starter-kit) - Cross-platform web development with Visual Studio Code, C#, F#, JavaScript, ASP.NET Core, EF Core, React (ReactJS), Redux, Babel. Single-page application boilerplate. 
* [[How To] Deploy your ASP.NET Core app to Heroku](https://bolorundurowinnertimothy.wordpress.com/2016/10/04/how-to-deploy-your-asp-net-core-app-to-heroku/) (Oct 4, 2016) - using a custom buildpack.
* [heroku/dotnet-buildpack](https://github.com/heroku/dotnet-buildpack) - This is a Heroku buildpack for building ASP.NET 5 apps using project.json files and the kpm package manager. Please note: This buildpack is an experimental project and is not officially supported.
	* [Buildpacks](https://devcenter.heroku.com/articles/buildpacks) - Buildpacks are responsible for transforming deployed code into a slug, which can then be executed on a dyno. Buildpacks are composed of a set of scripts, and depending on the programming language, the scripts will retrieve dependencies, output generated assets or compiled code, and more. This output is assembled into a slug by the slug compiler.
	* [Third-Party Buildpacks](https://devcenter.heroku.com/articles/third-party-buildpacks) - Heroku maintains a collection of officially supported buildpacks but there are also third-party buildpacks that enable you to use languages and frameworks beyond those that are officially supported by Heroku.


## GoLang
* [Golang for the C# Developer – [1] Intro](https://shonnlyga.wordpress.com/2016/10/01/golang-for-the-csharp-developer-intro/)
* [astaxie/build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang/blob/master/en/preface.md)
* [IDEs and Plugins for Go](https://github.com/golang/go/wiki/IDEsAndTextEditorPlugins)
* [Go Courses](https://github.com/golang/go/wiki/Courses)
* [Getting Started on Heroku with Go](https://devcenter.heroku.com/articles/getting-started-with-go#set-up)





## Backend Architectures
* [Stack Overflow: The Architecture - 2016 Edition](http://nickcraver.com/blog/2016/02/17/stack-overflow-the-architecture-2016-edition/) (Feb 17, 2016) - To get an idea of what all of this stuff “does,” let me start off with an update on the average day at Stack Overflow.
* [Getting Started with AWS](https://aws.amazon.com/start-now/) - Start building with Amazon Web Services
* [Getting Started with Microsoft Azure](https://azure.microsoft.com/en-us/get-started/) - Sign up and deploy your first Azure solution in under 5 minutes.
* [Firebase](https://firebase.google.com/) - The tools and infrastructure you need to build better apps and grow successful businesses.
* [Heroku](https://www.heroku.com/) - Choose Heroku for the same reasons disruptive startups do: it’s the best platform for building with modern architectures, innovating quickly, and scaling precisely to meet demand. Languages supported: Node.js, Ruby, Java, Php, Python, Go, Scala, Clojure.
* [AppHarbor](https://appharbor.com) - AppHarbor is a fully hosted .NET Platform as a Service. AppHarbor can deploy and scale any standard .NET application to the cloud.
* [Stamplay](https://stamplay.com/) - Chain together APIs as if they are Lego blocks arranging them into service based apps




## Node.js
* [How Developers use Node.js - Survey Results](https://blog.risingstack.com/node-js-developer-survey-results-2016/) by [RisingStack](http://blog.risingstack.com/) - RisingStack conducted a survey during 2016 Summer to find out how developers use Node.js and what technologies they prefer with it. This article summarizes the results.
* [Node.js Examples - How Enterprises use Node in 2016](https://blog.risingstack.com/node-js-examples-how-enterprises-use-node-in-2016/) - Fortunately, the Node Foundation’s [“Enterprise conversations”](https://www.youtube.com/playlist?list=PLfMzBWSH11xYNeUJXap4NTMX3TFtH-_0z) project lets us peek into the life of the greatest enterprises and their use cases as well. This article summarizes how GoDaddy, Netflix, and Capital One uses Node.js in 2016.
* [Node Hero - Getting Started With Node.js Tutorial](https://blog.risingstack.com/node-hero-tutorial-getting-started-with-node-js/) - This is the first post of an upcoming Node.js tutorial series called Node Hero - in these chapters, you can learn how to get started with Node.js and deliver software products using it. We are going to start with the basics - no prior Node.js knowledge is needed. The goal of this series is to get you started with Node.js and make sure you understand how to write an application using it, so don't hesitate to ask us if anything is unclear!
* [CRUD application using AngularJs, NodeJs, MongoDB : Part 1 : introduction](http://www.codeproject.com/Articles/1070392/CRUD-application-using-AngularJs-NodeJs-MongoDB) (Jan 11, 2016) - This article explains how we can implement a Web application built using angularjs, node js to perform create, read, update and delete operations on MongoDB database.
* [NodeSchool Workshopper](http://nodeschool.io/#workshopper-list) - Workshopper is the name used for the open source lesson modules associated with NodeSchool. All are self guided (you don't need to attend a workshop to do one) and most work offline.
* [Must See JavaScript Dev Tools That Put Other Dev Tools to Shame](https://medium.com/javascript-scene/must-see-javascript-dev-tools-that-put-other-dev-tools-to-shame-aca6d3e3d925#.mctqif9hr) (Nov 27, 2015) by [Eric Elliott](https://medium.com/@_ericelliott) - They said JS was slow. Now it's fast. Said we had no dev tools. We have the best. Said it sucks for big apps. We rock them.
* [Creating a Simple RESTful Web App with Node.js, Express, and MongoDB](http://cwbuecheler.com/web/tutorials/2014/restful-web-app-node-express-mongodb/) (Jun 7, 2015) - Learn the basics of REST and use them to build an easy, fast, single-page web app. 
* [Authenticate a Node.js API with JSON Web Tokens](https://scotch.io/tutorials/authenticate-a-node-js-api-with-json-web-tokens) (Apr 22, 2015) - As a primer to this article, go ahead and get yourself familiar with token based authentication principles and the standard used for token based authentication, JSON Web Tokens. Now that we’ve got all the important information about token based authentication out of the way, let’s build a very simple Node API and use tokens to authenticate users that request access.
* [RESTful API Using Node and Express 4](https://codeforgeek.com/2015/03/restful-api-node-and-express-4/) (Mar 16, 2015) - In this tutorial we’ll learn how to create basic REST API’s using Node.js and Express which retrieve data from MySQL database and give response in JSON format.
* [Build a RESTful API Using Node and Express 4](https://scotch.io/tutorials/build-a-restful-api-using-node-and-express-4) (Apr 15, 2014) - Today we’ll be looking at creating a RESTful API using Node, Express 4 and its Router, and Mongoose to interact with a MongoDB instance. We will also be testing our API using Postman in Chrome.
* [JavaScript Weekly - Best of 2015](http://javascriptweekly.com/issues/264) - A special issue looking back at the best of 2015.


## ASP.NET MVC & Web API
* [Business Application using HTML5, ASP.NET MVC, Web API and Knockout.js - Part 1](http://www.dotnetcurry.com/aspnet-mvc/1199/business-app-html5-aspnet-mvc-webapi-knockoutjs) (10/12/2015) - This article is divided in two parts. In the first part, we will see the server-side bits including Database design, Model design, and MVC and WEB API controllers. In part 2 of this article we will implement the client-side logic using jQuery and Knockout library. **Case Study**: There are several property owners who want to Sell or Rent their properties to local residents as well as visitors or investors. But it is challenging for them to put an advertisement in the newspaper, because of limited local circulation and also due to the financials involved. So we will make it easier for them by creating a web portal where they can display properties details and make it available to internet users, all across the globe.


## Microservices
* [Microservices: Real Architectural Patterns](https://medium.com/@skamille/microservices-real-architectural-patterns-68bd83bbb6cd) by [Camille Fournier](https://medium.com/@skamille) - A dissection of our favorite folk architecture.


## NoSQL, Working with
* [NoSQL Databases: a Survey and Decision Guidance](https://medium.baqend.com/nosql-databases-a-survey-and-decision-guidance-ea7823a822d) - Together with our colleagues at the University of Hamburg, we — that is Felix Gessert, Wolfram Wingerath, Steffen Friedrich and Norbert Ritter — presented an overview over the NoSQL landscape at SummerSOC’16 last month. Here is the written gist. We give our best to convey the condensed NoSQL knowledge we gathered building Baqend.


## Swing
* [Filthy Rich Clients](http://filthyrichclients.org/) by [Chet Haase](http://graphics-geek.blogspot.it/) and [Romain Guy](http://www.curious-creature.com/) - Create stunning visual and animated effects with Swing and Java 2D. Learn graphics and animation fundamentals as well as advanced rendering techniques. The source code for all the examples and demos from the book is available on [GitHub](https://github.com/romainguy/filthy-rich-clients) under the BSD license.
* [SimpleNotepad-Swing](https://github.com/statickidz/SimpleNotepad-Swing) - Word processor made with Java and Swing with MVP pattern.


## Udacity Courses
* [Scalable Microservices with Kubernetes](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615) - This course is designed to teach you about managing application containers, using Kubernetes.
* [Product Design](https://www.udacity.com/course/product-design--ud509) - Product Design blends theory and practice to teach you product validation, UI/UX practices, Google’s Design Sprint and the process for setting and tracking actionable metrics.
* [Designing RESTful APIs](https://www.udacity.com/course/designing-restful-apis--ud388)
* [Linux Command Line Basics ](https://www.udacity.com/course/linux-command-line-basics--ud595)
* [How to Use Git and GitHub](https://www.udacity.com/course/how-to-use-git-and-github--ud775) - Effective use of version control is an important and useful skill for any developer working on long-lived (or even medium-lived) projects, especially if more than one developer is involved. 


## Udemy Courses
- [Learn Android App Development With Java Step By Step](https://www.udemy.com/android-marshmallow-java-app-development-course/)
- [Android App in 26 Minutes](https://www.youtube.com/playlist?list=PLxvooGgpi4NdH877FIpWHLX2vxNfKpFmN) by [GK Micro Studios](https://www.youtube.com/channel/UCmrqaIMRI3z2MxfwfeDudsw) - nice videos about creating a very simple android app. I watched it for understand how the teacher talks and explains the topic of the course that I found on [Udemy](https://www.udemy.com/courses/).
- [Android App Development: Create a Spotify Clone](https://www.udemy.com/android-app-development-create-a-spotify-clone/) (Udemy, Instructed by [Mr Grant Klimaytys](https://www.udemy.com/user/grant-klimaytys/)) - Stream your music collection and learn how to play and control music on Android.
- [Android: From Beginner to Paid Professional](https://www.udemy.com/learn-android/) - Learn to code the Devslopes way. At Devslopes we teach you the platform and the underlying coding principles. We believe in building engineers and not copy-and-paste students. You can get started with no experience or with lots of coding experience.


## Web Site Builders
* [Wordpress.com](https://wordpress.com/) - Everything you need to build a beautiful website. Powerful tools and features that grow with you.
* [Altervista](http://it.altervista.org/)
* [WIX](http://www.wix.com/) - Wix.com is a leading cloud-based development platform with millions of users worldwide. We make it easy for everyone to create a beautiful, professional web presence.
Promote your business, showcase your art, set up an online shop or just test out new ideas. The Wix website builder has everything you need to create a fully personalized, high-quality free website.
	* [Step-by-Step Guide: How to Create the Ultimate Professional Website](http://www.wix.com/blog/2016/06/how-to-create-website-step-by-step-guide/) (June 1st 2016) - In this post, we will provide a step-by-step guide to assist you as you create the professional website you deserve using Wix’s website builder. In addition to walking you through the technicalities and details of building your own site, we will also focus on key issues in branding and marketing, to guarantee that your site is effective as well as beautiful.
* [Odoo - Open Source ERP and CRM](https://www.odoo.com/) - All-in-one management software. Beautiful. Easy-to-use.
	* [Odoo - Free Web Site Builder](https://www.odoo.com/page/website-builder)




> Written with [StackEdit](https://stackedit.io/).