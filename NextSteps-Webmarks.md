# Webmarks App

## Web Parser
Creating an app similar to [Mercury Web Parser](https://mercury.postlight.com/web-parser/).
Mercury Web Parser is created by Readability crew. They use a name with no meaning (for me, at least) about article extraction. Here is [Mercury](https://en.wikipedia.org/wiki/Mercury) in Wikipedia.
Readability is a name that focus on the readability feature and secondly on the bookmark feature.
Read it Later (now Pocket) has a focus on the bookmark feature and the readability feature is described as a plus.
Instapaper has a focus on the paper feature (kind of bookmark) and the readability feature is a plus.
Mercury is a Web Parser API (readability feature from the developer point of view) and after a while they created Mercury Reader (chrome extension) for the end user.
So I think I can use a name with no direct meaning on the main feature or a name that recall the meaning.
For the second type I was thinking to [sharpener](http://www.wordreference.com/enit/sharpener), or something that recall the extraction, clearing or similar of a web article. It is even interesting something that recall [web scraping](https://en.wikipedia.org/wiki/Web_scraping). 
For the first type I was looking for deities names from greek mytology - [Artemis](https://en.wikipedia.org/wiki/Artemis_(disambiguation)), [Aletheia](https://en.wikipedia.org/wiki/Aletheia_(disambiguation)), [Thalia](https://en.wikipedia.org/wiki/Thalia), [Cleo](https://en.wikipedia.org/wiki/Cleo_of_Alpha_Chi) from [Muses in popular culture](https://en.wikipedia.org/wiki/Muses_in_popular_culture).

I found very nice "Cleo, web articles scraping". But the day after it does not seem so nice :-D
On Friday 20th of Jan it became "Cleo, web content scraping" or "web content gathering" or "web article trimmer".
This may be the endpoint: GET -> /api/content/{url} with a header containing an API key about the user that is calling it.

A basic structure may be this:
 
 * a main page, describing what the service do and how to use it
 * api key creation, through a form that require an email, send the email with a link to activate the api key
 * parser api entry point

This app may be the base for Webmarks server. I'd like to publish on neetpiq domain. Something like webmarks.neetpiq.com or webmarksapp.neetpiq.com but I'm not sure it should be a right solution.

I'd like to use asp.net + nancyfx (it may be interesting to investigate about asp.net core) for this project.

* [StackExchange/dapper-dot-net](https://github.com/StackExchange/dapper-dot-net) - Dapper - a simple object mapper for .Net
* [Token-Based Authentication for Web Service APIs in C# MVC .NET](http://www.primaryobjects.com/2015/05/08/token-based-authentication-for-web-service-apis-in-c-mvc-net/) (May 8, 2015) - In this tutorial, we’ll walk through how to create a simple, but effective token-based authentication framework to secure a .NET REST API.
* [scottksmith95/CSharp.Readability](https://github.com/scottksmith95/CSharp.Readability) - Readability API binding and OAuth connect support for the readability.com API.
* [marek-stoj/NReadability](https://github.com/marek-stoj/NReadability) (Latest commit on Jun 29, 2014) - NReadability is a tool for removing clutter from HTML pages so that they are more enjoyable to read. 
* [ceee/ReadSharp](https://github.com/ceee/ReadSharp) (Latest commit on Dec 13, 2015) - Extract meaningful website contents using a port of NReadability.
* [Deserializing JSON resources with C# and Json.NET](http://www.codetrench.com/deserializing-json-resources-with-c-sharp-and-json-net/) (Apr 22, 2015)
* [Json.NET](http://www.newtonsoft.com/json) - Popular high-performance JSON framework for .NET)

Something about Mercury and who is working on it.

* [Mercury](https://mercury.postlight.com/) - Mercury is a toolkit that lets you transform web pages into clean text. Publishers and programmers use it to make the web make sense. For free. Mercury is a product of [Postlight Labs](https://postlight.com/labs). [Mercury Toolkit](https://twitter.com/MercuryToolkit) on twitter.
	* [Postlight](https://postlight.com/) - Postlight is a digital product studio in New York City. We build prototypes to prove out ideas—then build large, scalable digital platforms that support elegant consumer products.
	* [Mercury Case Study](https://postlight.com/work/mercury/) - a post about the project.
	* [Web Parser API](https://mercury.postlight.com/web-parser/) - With just one API request, Mercury takes any web article and returns only the relevant content — headline, author, body text, relevant images and more — free from any clutter. It’s reliable, easy-to-use and free.


## WebMarks
* [Wallabag Service](https://www.wallabag.it/en/features) - [wallabag](https://wallabag.org/) is an [open source](https://github.com/wallabag) application to save your web articles and allows you to read them later, on your smartphone, your tablet or your ereader. We propose to you a quality service to host your account: you'll get the latest version of the application and you'll get a professional support.
	* [Framabag](https://www.framabag.org/) - Framabag est un service libre et gratuit proposé par le réseau [Framasoft](http://framasoft.org/). Framabag est une instance de [wallabag](http://www.wallabag.org/).

