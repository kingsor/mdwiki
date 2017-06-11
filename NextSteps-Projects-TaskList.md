# Task List

I'd like to create a todo list / task list app.


## Building an Android Todo App
* [Building the Todo Android App in Studio](http://goo.gl/8R7Mty) - Step by step slides to create a minimalistic Todo app.
* [Basic Todo App Tutorial](http://guides.codepath.com/android/Basic-Todo-App-Tutorial) - Todo App steps in guide format
* [TODO-MVP](https://github.com/googlesamples/android-architecture/tree/todo-mvp/) - This sample is the base for many of the variants. It showcases a simple implementation of the Model-View-Presenter pattern with no architectural frameworks. It uses manual dependency injection to provide a repository with local and remote data sources. Asynchronous tasks are handled with callbacks.
* [How We Used Micro-Transitions for Smooth Android To-Do List Animations](https://yalantis.com/blog/how-we-used-micro-transitions-for-smooth-android-to-do-list-animations/) (???) - Working on one of our recent projects at Yalantis we had a small task of creating a to-do list, and the challenging part was to create one that would stand out among similar features and be fun for the user. The idea was that we needed something that would make managing tasks fast and intuitive. The project is available on [GitHub](https://github.com/Yalantis/ToDoList).
* [How to create REST API for Android app using PHP, Slim and MySQL – Day 1/2](http://www.androidhive.info/2014/01/how-to-create-rest-api-for-android-app-using-php-slim-and-mysql-day-12-2/) ( Jan 19, 2014) - This tutorial gives enough knowledge about building a REST API for very beginners. As this tutorial seems lengthy, I had divided it into 2 parts. In the 1st part we learn fundamental concepts of REST and do the required setup. In the 2nd part building actual API (writing PHP & MySQL code) is covered.
* [Android Login and Registration with PHP, MySQL and SQLite](http://www.androidhive.info/2012/01/android-login-and-registration-with-php-mysql-and-sqlite/) (Jan 31, 2012) - In this tutorial I am going to explain how to build complete login and registration system in android using PHP, MySQL and SQLite. Also this tutorial covers how to build simple API using PHP and MySQL.


## Samples
* [Todo-Backend](http://www.todobackend.com/) - The Todo-Backend project helps showcase and compare different language and framework combinations for building web services. This website defines a simple web API in the form of a todo list and users can create their own identical APIs using various tech stacks. This website then provides a spec runner to verify that the user implementation is identical to the base implementation. The Todo-Backend project was inspired by the [TodoMVC project](http://todomvc.com/), and some code (specifically the todo client app) was borrowed directly from TodoMVC.
* [In Depth Guide on Building a REST API with Node.js, Restify & MongoDB](https://getstream.io/blog/depth-guide-building-rest-api-node-js-restify-mongodb/) - a todo list sample using Restify and MongoDB.
* [Creating a Cloud Backend for Your Android App Using Firebase](https://www.sitepoint.com/creating-a-cloud-backend-for-your-android-app-using-firebase/) (Sep 7, 2016) - In this article, you’ll create a **simple To Do app** that will show how to save and retrieve data from Firebase, how to authenticate users, set read/write permissions on the data and validate the data on the server.

### ToDo with NancyFx
From the [Todo-Backend](http://www.todobackend.com/) project, here is a list of links about NancyFx use.

* [C# with NancyFx](http://todobackend.apphb.com/todo-backend) - implementation with Nancy Framework and NDatabase, an inmemory object database.
* [sriv/todo-backend-nancy](https://github.com/sriv/todo-backend-nancy) - An implementation of todo-backend using NancyFX
* Here is the [Demo Client](http://www.todobackend.com/client/index.html?https://todobackend.apphb.com/todo-backend)
* [Creating a Nancy web api to store data in MongoDB](https://suttoncodefield.wordpress.com/2015/09/24/creating-a-nancy-web-api-to-store-data-in-mongodb/) 
(Sep 24, 2015) - Today I’m going to describe a quick example of a web api for storing and retrieving data in a MongoDB.

### Cheddar App
* [Cheddar App](https://cheddarapp.com/) - Tasks made simple. With Cheddar, your tasks are instantly everywhere. Everything you do with Cheddar pushes to all of your devices, so your world is always in sync. It's really magical to create a task on your iPhone and have it instantly be on your computer without thinking about syncing.
	* [Nothing Magical](http://nothingmagical.com/) - Nothing Magical is just a one man show. Sam designs and develops all of the Nothing Magical products.
	* [Sam Soffes](https://soff.es/) - I am a [Swift and Ruby engineer](https://github.com/soffes), musician, wanna be designer, overly passionate motorcyclist, and burger connoisseur. I live in San Francisco with my beautiful wife.
* [Cheddar API](https://cheddarapp.com/developer) - Tasks made simple. With Cheddar, your tasks are instantly everywhere. Everything you do with Cheddar pushes to all of your devices, so your world is always in sync. It's really magical to create a task on your iPhone and have it instantly be on your computer without thinking about syncing.
* [aliHafizji/Cheddar-Android](https://github.com/aliHafizji/Cheddar-Android) - This is a universal Android app for Cheddar, a simple task manager.


## Execution
I want to use NancyFx and to follow the nancy succintly guide for the topics I need to know in detail.
I want to use a more complex model insted of classic model similar to this:
[Task.cs](https://github.com/edtyl3r/NancyDemo/blob/master/NancyDemo/Task.cs)

```javascript
public class Task
{
	[BsonId]
	[BsonRepresentation(BsonType.ObjectId)]
	public string Id { get; set; }
	public string Text { get; set; }
}
```

I want something similar to [Todo.cs](https://github.com/sriv/todo-backend-nancy/blob/master/Todo.cs) on [todo-backend-nancy](https://github.com/sriv/todo-backend-nancy) project.

```javascript
public class Todo
{
	// wont need nullable types if we can find a better way to bind the form values.
	public int Id { get; set; }
	public int? Order { get; set; }
	public string Title { get; set; }
	public string Url {get; set;}
	public bool? Completed { get; set; }
}
```

I think that a right model may be that of [Cheddar Tasks](https://cheddarapp.com/developer/tasks). Cheddar App use List of Tasks and User authentication.

```json
{
  "archived_at": null,
  "completed_at": null,
  "created_at": "2012-07-07T00:46:31Z",
  "display_html": "Eat at a new place",
  "display_text": "Eat at a new place",
  "entities": [],
  "id": 122307,
  "list_id": 16834,
  "position": 6,
  "tags": [],
  "text": "Eat at a new place",
  "updated_at": "2012-07-07T00:46:45Z",
  "url": "https://api.cheddarapp.com/v1/tasks/122307"
}
```

I like this kind of structure for a task list application.


## NancyFx
* [About NancyFx by Phil Hack](http://www.philhack.com/nancyfx/)
* [Exploring the nancy module](https://github.com/NancyFx/Nancy/wiki/Exploring%20the%20Nancy%20module)
* [Nancy Documentation](https://github.com/NancyFx/Nancy/wiki/Documentation)
* [Nancy Blog](http://blog.nancyfx.org/)
	* [One Nancy blog to aggregate them all!](http://blog.nancyfx.org/one-nancy-blog-to-aggregate-them-all/)
* [#nancyfx on twitter](https://twitter.com/hashtag/nancyfx)
* [Use NancyFx in ASP.NET Core](http://www.talkingdotnet.com/use-nancyfx-in-asp-net-core/) (Sep 22, 2016) -  In this post, let’s find out how to use NancyFx in ASP.NET Core.
* [Microservices in .NET with C#, the Nancy framework, and OWIN middleware](https://manning.com/books/microservices-in-net) by [Christian Horsdal](http://www.horsdal-consult.dk/p/about.html) (Publication in Summer 2016 - estimated) - Microservices in .NET shows you how to build and deploy secure and operations-friendly microservices using Nancy. The book takes you through an introduction to the microservices architectural style. Next, you’ll learn important practical aspects of developing microservices from simple core concepts to more sophisticated. Throughout the book, you’ll see many code examples implementing it with lightweight .NET technologies—most prominently Nancy. By the end, you’ll be able to quickly and easily build reliable and operations-friendly microservices using Nancy, OWIN and other open technologies. 
* [ASP.NET 5 Series: NancyFX](http://codeopinion.com/asp-net-5-series-nancyfx/) (Jan 11, 2016) - Last week I decided to start migrating one of my existing ASP.NET application that uses NancyFX over to ASP.NET 5.  The process is actually pretty straight forward if you are familiar with OWIN.
* [NancyFX: .NET Web Framework](http://codeopinion.com/nancyfx-net-web-framework/) (Sep 22, 2015) - There has been a bigger wave of alternative and open source software awareness within .NET. NancyFX is a great alternative that is very mature, simple and has great documentation.
* [horsdal/ShortURL](https://github.com/horsdal/ShortURL) (Latest commit on May 28, 2015)
* [Nancy handler functions revisited](http://anthonysteele.co.uk/nancy-handler-functions-revisited) (Jun 6, 2014)
* [More patterns for web services in NancyFx](http://anthonysteele.co.uk/more-patterns-for-web-services-in-nancyfx) (Mar 1, 2014)
* [Patterns for web services in NancyFx](http://anthonysteele.co.uk/patterns-of-web-apis-in-nancy) (Feb 25, 2014)
* [From ASP.NET MVC to Nancy - Part 1](http://www.jhovgaard.com/from-aspnet-mvc-to-nancy-part-1/) (Feb 17, 2012) - Nancy is a Micro .NET framework inspired by Sinatra. If you ever felt that ASP.NET MVC is too heavy, too clumsy and stands in your way, Nancy is definitely made for you. I’m an average .NET developer. I work for a middle-sized company where we build a lot of applications in ASP.NET MVC 3 and because of that, this series of posts will be designed for exactly that purpose: moving from ASP.NET MVC 3 to Nancy.
* [Frictionless .NET Web App Development with Nancy ](http://www.horsdal-consult.dk/2011/10/frictionless-net-web-app-development.html) (Oct 10, 2011)
