# Getting started with Node.js

## Official site

* The first presentation on Node.js from Ryan Dahl at JSConf 2009
  [](https://www.youtube.com/watch?v=ztspvPYybIY)
* [node.js](http://nodejs.org/)  
  Node.js is a platform built on [Chrome's JavaScript runtime](http://code.google.com/p/v8/) for easily building fast, scalable network applications. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.
* [node project on github](https://github.com/joyent/node)  
  Repository on GitHub
* [Node.js community wiki](https://github.com/joyent/node/wiki)  
  Documentation and resources about node.js
* [Projects, Applications, and Companies Using Node](https://github.com/joyent/node/wiki/Projects,-Applications,-and-Companies-Using-Node)  
  An always updated list.

## The event loop

* [Understanding the node.js event loop](http://blog.mixu.net/2011/02/01/understanding-the-node-js-event-loop/)  
  The first basic thesis of node.js is that I/O is expensive.
* [Philip Roberts: Help, I'm stuck in an event-loop](http://vimeo.com/96425312)  
  Us JavaScript programmers like to use words like, "event-loop", "non-blocking", "callback", "asynchronous", "single-threaded" and "concurrency".
  We say things like "don't block the event loop", "make sure your code runs at 60 frames-per-second", "well of course, it won't work, that function is an asynchronous callback!"
  If you're anything like me, you nod and agree, as if it's all obvious, even though you don't actually know what the words mean; and yet, finding good explanations of how JavaScript actually _works_ isn't all that easy, so let's learn!
  With some handy visualisations, and fun hacks, let's get an intuitive understanding of what happens when JavaScript runs. Beginner or veteran, I'm sure you'll learn something!
  
  <iframe src="http://player.vimeo.com/video/96425312" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> <p><a href="http://vimeo.com/96425312">Philip Roberts: Help, I'm stuck in an event-loop.</a> from <a href="http://vimeo.com/edgecaseuk">Neo (UK)</a> on <a href="https://vimeo.com">Vimeo</a>.</p>
  
  [](http://vimeo.com/96425312)


## Starting from Javascript

* [It is time to learn Javascript](http://wildermuth.com/2014/6/22/It_Is_Time_to_Learn_JavaScript) (June 22, 2014)  
  JavaScript is having a great year. With the continuation of web development, Node.js, and even Apple adding JavaScript as a replacement for their AppleScript.  
  You may be waiting until you have to learn JavaScript, but maybe you should learn JavaScript to make you a better developer.
* [How to Learn JavaScript Properly](http://javascriptissexy.com/how-to-learn-javascript-properly/)  
  This course outline gives you a structured and instructive roadmap on how to learn JavaScript properly and thoroughly, from absolute beginner to attainment.
* [Don’t Be Scared Of Functional Programming](http://www.smashingmagazine.com/2014/07/02/dont-be-scared-of-functional-programming/) (July 2, 2014)  
  Functional programming is the mustachioed hipster of programming paradigms. Originally relegated to the annals of computer science academia, functional programming has had a recent renaissance that is due largely to its utility in distributed systems (and probably also because “pure” functional languages like Haskell are difficult to grasp, which gives them a certain cachet).
* [10 Most Common JavaScript Mistakes](http://www.toptal.com/javascript/10-most-common-javascript-mistakes) (July 7, 2014)  
  At first blush, JavaScript may seem quite simple. And indeed, to build basic JavaScript functionality into a web page is a fairly straightforward task for any experienced software developer, even if they’re new to JavaScript. Yet the language is significantly more nuanced, powerful, and complex than one would initially be lead to believe. Indeed, many of JavaScript’s subtleties lead to a number of common mistakes – 10 of which we discuss here – that are important to be aware of and avoid in one’s quest to become a master JavaScript developer.
* [Top 10 JavaScript traps for a C# developer](http://www.codetails.com/2014/05/27/top-10-javascript-traps-for-a-c-developer/) (May 27, 2014)  
  If you are an experienced C# developer, coming into JavaScript world for application development, you will end up making few common mistakes. However some of the mistakes you would make are due to the basic differences between any strongly typed language [C#, Java etc.] and a dynamically typed language [JavaScript, Python etc].
* [Understand JavaScript Closures With Ease](http://javascriptissexy.com/understand-javascript-closures-with-ease/) (Feb 2, 2013)  
  Closures are lovely and reliably serviceable: They allow programmers to program creatively, expressively, and concisely. They are used frequently in JavaScript and, no matter your JavaScript skill level, you will no doubt encounter them. Sure, closures might appear complex and beyond your scope, but after reading this article, closures will be much more easily understood and more appealing for usage in your everyday JavaScript programming.
* [Understand JavaScript Callback Functions and Use Them](http://javascriptissexy.com/understand-javascript-callback-functions-and-use-them/) (March 4, 2013)  
  In JavaScript, functions are first-class objects, which means functions can be used in a first-class manner like objects, since they are in fact objects themselves: They can be “stored in variables, passed as arguments to functions, created within functions, and returned from functions” [First Class](http://c2.com/cgi/wiki?FirstClass) definition.  
  Because functions are first-class objects, we can use callback functions in JavaScript. In the rest of this article we will learn everything about callback functions. Callback functions are probably the most widely used functional programming technique in JavaScript, and they are literally in just about every piece of JavaScript and jQuery code, yet they are a mystery to many JavaScript developers. You will know how to use them after reading this article.
* [Understanding JavaScript Callbacks](http://cwbuecheler.com/web/tutorials/2013/javascript-callbacks/) (2013)  
  When I got started working with Node.js and Express, one of the first things I had to really wrap my head around was JavaScript callbacks. This is a powerful functionality built into the language that allows you to defer action until a desired event occurs, while proceeding on with other activities. 
* [Learning JavaScript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/)  
  Design patterns also provide us a common vocabulary to describe solutions. This can be significantly simpler than describing syntax and semantics when we're attempting to convey a way of structuring a solution in code form to others.  
  In this book we will explore applying both classical and modern design patterns to the JavaScript programming language.

## Learning Node.js

* [The Node Beginner Book](http://www.nodebeginner.org/) - A Node.js tutorial by [Manuel Kiessling](http://twitter.com/manuelkiessling)  
  The aim of this document is to get you started with developing applications with Node.js, teaching you everything you need to know about "advanced" JavaScript along the way. It goes way beyond your typical "Hello World" tutorial.  
  This document will probably fit best for readers that have a background similar to my own: experienced with at least one object-oriented language like Ruby, Python, PHP or Java, only little experience with JavaScript, and completely new to Node.js.  
Aiming at developers that already have experience with other programming languages means that this document won't cover really basic stuff like data types, variables, control structures and the likes. You already need to know about these to understand this document.  
However, because functions and objects in JavaScript are different from their counterparts in most other languages, these will be explained in more detail.
* [Learn Node.js Completely and with Confidence](http://javascriptissexy.com/learn-node-js-completely-and-with-confidence)  
  I provide you with a detailed roadmap for learning Node.js that has worked for me, and I am confident it will work for you. You will learn Node.js completely and you should approach this course with confidence, because you are only 2 to 3 weeks away from building amazingly fast, real-time, modern web applications in short time.
* [Want To Learn Node.js? Here Are Some Useful Tutorials](http://www.designyourway.net/blog/resources/want-to-learn-node-js-here-are-some-useful-tutorials/)  
  Node.js is a technology that is increasing in popularity with web developers. Not too many people know what this new technology is. Node.js is a server-side JavaScript environment that uses an asynchronous event-driven model. 
* [Node.js Production Practices](http://www.joyent.com/developers/node)  
  As part of our stewardship of Node.js®, this resource is dedicated to sharing tools and techniques we use at Joyent to operate Node.js in production. From coding styles and design considerations through debugging large distributed systems, we intend to document our Node.js development and production practices.

## Tools

* [Building with Node.js Tools for Visual Studio](http://kowsheek.com/2014/05/21/building-with-node-js-tools-visual-studio/) (May 21, 2014)  
  [Node.js Tools for Visual Studio (NTVS)](https://nodejstools.codeplex.com/) is a free, open source plugin that turns Visual Studio into a Node.js IDE. NTVS supports Editing, Intellisense, Profiling, npm, TypeScript, Debugging locally and remotely (Windows/MacOS/Linux), as well Azure Web Sites and Cloud Service.

## Configuring a project

* [package.json](http://browsenpm.org/package.json)  
  This is an interactive guide for exploring various important properties of the package.json packaging format for node.js applications.
* [package.json](https://www.npmjs.org/doc/json.html)  
  This document is all you need to know about what's required in your package.json file. It must be actual JSON, not just a JavaScript object literal.
* [Package.json dependencies done right](http://blog.nodejitsu.com/package-dependencies-done-right/)  
  Dependency management. Need I say more? Entire developer ecosystems live and die by how dependency management works.

## Samples

* [Getting started with Node.js, Express, MongoDB](http://cwbuecheler.com/web/tutorials/2013/node-express-mongo/)  
  The Dead-Simple Step-by-Step Guide for Front-End Developers to Getting Up and Running with Node.JS, Express, Jade, and MongoDB.
* **Nodecellar Sample** by [Christophe Coenraets](http://coenraets.org/blog/)
    * [Creating a REST API using Node.js, Express, and MongoDB](http://coenraets.org/blog/2012/10/creating-a-rest-api-using-node-js-express-and-mongodb/)
    * [NodeCellar: Sample Application with Backbone.js, Twitter Bootstrap, Node.js, Express, and MongoDB](http://coenraets.org/blog/2012/10/nodecellar-sample-application-with-backbone-js-twitter-bootstrap-node-js-express-and-mongodb/)
    * [Real Time Web Analytics with Node.js and Socket.IO](http://coenraets.org/blog/2012/10/real-time-web-analytics-with-node-js-and-socket-io/)
* [The MEAN Stack: MongoDB, ExpressJS, AngularJS and Node.js](http://thecodebarbarian.wordpress.com/2013/04/29/easy-web-prototyping-with-mongodb-and-nodejs/) (Apr 29, 2013)
* **Introduction to the MEAN Stack**
    * [Introduction to the MEAN Stack, Part One: Setting Up Your Tools](http://thecodebarbarian.wordpress.com/2013/07/22/introduction-to-the-mean-stack-part-one-setting-up-your-tools/) (Jul 22, 2013)
    * [Introduction to the MEAN Stack, Part Two: Building and Testing a To-do List](http://thecodebarbarian.wordpress.com/2013/07/29/introduction-to-the-mean-stack-part-two-building-and-testing-a-to-do-list/) (Jul 29, 2013)
* **Node.js development with WebMatrix 2 and Express** by [Steven Sanderson](https://twitter.com/StevenSanderson)
    * [Getting started with Node and Express using WebMatrix 2](http://blog.stevensanderson.com/2012/07/09/node-js-development-with-webmatrix-2-and-express/)
    * [Building a web app with static UI / dynamic API architecture](http://blog.stevensanderson.com/2012/07/10/node-js-development-with-webmatrix-2-express-part-2/)
    * [Hints and tricks for optimising for mobiles](http://blog.stevensanderson.com/2012/07/11/node-js-development-with-webmatrix-2-express-part-3/)
* [Let's Make a Web App](http://dailyjs.com/web-app.html)  
  This tutorial series demonstrates how to build a web application with Node and Express.
* [Build a real-time polls application with Node.js, Express, AngularJS, and MongoDB](http://www.ibm.com/developerworks/library/wa-nodejs-polling-app/) (Jun 3, 2014)  
  Recently while lecturing on HTML5 to a large group of students, I wanted to poll them and display their voting results, updating in real-time. I decided to quickly build a polling app for this purpose. I wanted a simple architecture and not too many different languages and frameworks. So I decided to use JavaScript for everything — Node.js and Express for the server-side, MongoDB for the database, and AngularJS for the front-end user interface.
* [Build a RESTful API Using Node and Express 4](http://scotch.io/tutorials/javascript/build-a-restful-api-using-node-and-express-4) (Apr 15, 2014)  
  Today we’ll be looking at creating a RESTful API using Node, Express 4 and its Router, and Mongoose to interact with a MongoDB instance.
* [Build a simple notification service with Node.js and MongoDB](http://www.ibm.com/developerworks/library/wa-notify-app/) (Feb 4, 2014)  
  Do you ever find yourself trying to orchestrate the behavior of a growing set of disparate tools to create some larger system? In my case, our development team needs to assemble a continuous delivery pipeline and sequence their operation. One option is to employ a notification service that supports creating, signaling, and subscribing to events.
* [Building Web APIs with Node.js and MongoDB](http://www.codemag.com/Article/1210041) (Jan 5, 2014)  
  In this article, I’ll illustrate what it takes to build a simple Web API using Node.js and the Express.js web framework with MongoDB as the persistence mechanism. Under the hood I’ll use MongoDB and Mongoose to persist the data.
* [Creating a Single Page Todo App with Node and Angular](http://scotch.io/tutorials/javascript/creating-a-single-page-todo-app-with-node-and-angular) (November 7, 2013)  
  Today we will be creating a very simple Todo application using the MEAN (Mongo, Express, Angular, Node) stack.
* [Build a sentiment analysis application with Node.js, Express, sentiment, and ntwitter](http://www.ibm.com/developerworks/library/wa-nodejs-app/) (Jun 27, 2013)  
  As a software app developer, I've been trying to solve the following problem: how to get immediate feedback from users, specifically online users. Getting an instant read on the Twitterverse's reactions to an app, product launch, campaign, or current event, for example, would be enormously helpful. Are the reactions positive, negative, neutral?
* [Blog rolling with mongoDB, express and Node.js](http://howtonode.org/express-mongodb) (July 24, 2011)

## Interesting projects

* [Chorus.js](http://www.chorusjs.com/)  
  Chorus.js offers a very simple way to orchestrate asynchronous and synchronous APIs in Node applications.  
  Our focus is on making chorus.js super easy to learn and use everywhere, from an entry-level Raspberry Pi to the most scalable PaaS, and anything in between.

### Resources

### Newsletters

* [DailyJS](http://dailyjs.com/)  
  Incredible source of articles about javascript. Very inspirational.
* [Node Weekly Issues](http://nodeweekly.com/issues)
  A free, once–weekly e-mail round-up of Node.js news and articles
* [Mobile Web Weekly Issues](http://mobilewebweekly.co/issues)
  A weekly round-up of the releases, articles, and links that affect Web developers working on the mobile-facing Web

### Sites


