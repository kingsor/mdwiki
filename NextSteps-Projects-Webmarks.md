# Webmarks App

I want to create an app for android with the main feature to save a url of an article/post I'm interested in to read it later. This way I collect interesting stuff with bookmark purpose.

(Jan 9, 2016) The Webmarks App has a [repository](https://github.com/WebmarksApp) and a [site](http://webmarksapp.github.io/) provided by GitHub.

## The Project
[Webmarks App](https://github.com/WebmarksApp) on GitHub
	
* [webmarks.nancy](https://github.com/WebmarksApp/webmarks.nancy) - hosted on  [AppHarbor](https://appharbor.com/applications/webmarks) and available at this address: [http://webmarks.apphb.com/](http://webmarks.apphb.com/)
* [webmarks.node](https://github.com/WebmarksApp/webmarks.node) - hosted on [Heroku](https://dashboard.heroku.com/apps/webmarksapp) and available at this address: [https://webmarksapp.herokuapp.com/](https://webmarksapp.herokuapp.com/)
* [webmarksapp.github.io](https://github.com/WebmarksApp/webmarksapp.github.io) - hosted by [GitHub Pages](https://pages.github.com/) and available at this address: [http://webmarksapp.github.io/](http://webmarksapp.github.io/)
* [Webmarks-Android](https://github.com/kingsor/WebMarks-Android)


## Inspirational Apps / Samples
* [MarkSearch](https://darkle.github.io/MarkSearch/) - MarkSearch is a desktop bookmarking application. It allows you to save and search web pages. The desktop application runs in the background while you use your browser to access the main MarkSearch search page. MarkSearch is supposed to work kinda like google in that you don’t need to use tags or categories, you just do a full text search. You can save websites manually from the MarkSearch search page, or by using the browser extension to save a site. The browser extension also has the ability to show your MarkSearch bookmarks on google search pages, so you can see results for you search terms from Google and MarkSearch at the same time.
* [Building a Bookmarking App with Electron, VueJs, and Firebase](https://coligo.io/bookmarking-app-electron-vuejs-firebase/) (Apr 1st, 2016) - In this tutorial we will be building a cross-platform, real-time Bookmarking Application using [Electron](http://electron.atom.io/), [Firebase](https://www.firebase.com/), and [VueJs](http://vuejs.org/). We will be covering everything from setting up your project structure and configuring Webpack to creating the Electron app and building the Vue components.
* [shaarli/Shaarli](https://github.com/shaarli/Shaarli) - The personal, minimalist, super-fast, database free, bookmarking service - community repo
* [Shaarli](http://sebsauvage.net/wiki/doku.php?id=php:shaarli) - You want to share the links you discover ? Shaarli is a minimalist delicious clone you can install on your own website. It is designed to be personal (single-user), fast and handy.

### Libraries
* [ceee/ReadSharp](https://github.com/ceee/ReadSharp) - Extract meaningful website contents using a port of NReadability. ReadSharp was previously PocketSharp.Reader and is now hosted without the PocketSharp dependency.
* [wallabag/php-readability](https://libraries.io/github/wallabag/php-readability) - This is a PHP port of Arc90's original Javascript version of Readability.
* [feelinglucky/php-readability](https://github.com/feelinglucky/php-readability) - Back the fun of reading - PHP Port of Arc90′s Readability
* [andreskrey/readability.php](https://github.com/andreskrey/readability.php) - PHP port of Mozilla's Readability.js
* [marek-stoj/NReadability](https://github.com/marek-stoj/NReadability) - NReadability is a tool for removing clutter from HTML pages so that they are more enjoyable to read.
* [Nuget NReadability 1.4.9](https://www.nuget.org/packages/NReadability) - the nuget package.

## Ideas Backlog
* when I have a big list of bookmarks I'd like to be able to organize them. There are a few ways to do that.
	* Using tags - it's a way too flat if it is not possible to show articles for more than one tag a time - I'd like to use the delicious way (you can choose a tag and you can see the other tags associated with the resulting article) so you can create a hierarchy of tags
	* Using categories
	* Using titled lists - so you can create a path of content you are interested in
* there is [feedly](http://www.feedly.com/) and the following articles may be helpful for thinking new features for Webmarks.
	* [Seven ways to save articles that you read in feedly](http://blog.feedly.com/2015/08/31/seven-ways-to-save-articles-that-you-read-in-feedly/)
	* [Meet Shared Collections: Now you can choose to share what you read with others](http://blog.feedly.com/2015/09/01/launching-shared-collections/)
	* [Seven ways to share stories from feedly](http://blog.feedly.com/2015/09/08/seven-ways-to-share-stories-from-feedly/)
	* [The feedly Cloud API](http://developer.feedly.com/)
	* [liGhun/RSSharp](https://github.com/liGhun/RSSharp) - A .NET library giving access to various RSS feed aggregation services.


## Key Customers
I need to find at least five to ten key customers in order to sharpen the app.

* [Andrea Parodi "Paco"](https://twitter.com/vitarilassata) - he uses Pocket and he is available to try my app
* [Alessio Biancalana](https://twitter.com/dottorblaster) - he uses Pocket as I discovered by this [status](https://twitter.com/dottorblaster/status/642270131519942656)
* [AlessandraFarabegoli](https://twitter.com/alebegoli) - she uses Pocket for retrieving stuff for newsletter creation as described on slide 29 of [Email Marketing per chi non ha tempo di scrivere #BTO2015](http://www.slideshare.net/alebegoli/email-marketing-per-chi-non-ha-tempo-di-scrivere-bto2015).

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

## Mercury (the parser part of Readability)

Something about Mercury and who is working on it.

* [Mercury](https://mercury.postlight.com/) - Mercury is a toolkit that lets you transform web pages into clean text. Publishers and programmers use it to make the web make sense. For free. Mercury is a product of [Postlight Labs](https://postlight.com/labs). [Mercury Toolkit](https://twitter.com/MercuryToolkit) on twitter.
	* [Postlight](https://postlight.com/) - Postlight is a digital product studio in New York City. We build prototypes to prove out ideas—then build large, scalable digital platforms that support elegant consumer products.
	* [Mercury Case Study](https://postlight.com/work/mercury/) - a post about the project.
	* [Web Parser API](https://mercury.postlight.com/web-parser/) - With just one API request, Mercury takes any web article and returns only the relevant content — headline, author, body text, relevant images and more — free from any clutter. It’s reliable, easy-to-use and free.
	* [AMP Converter](https://mercury.postlight.com/amp-converter/) - With just one line of code, Mercury AMP gets your publication ready for Google AMP. Get lightning-fast load times and boosted search results on mobile.
		* [The Accelerated Mobile Pages (AMP) Project](https://www.ampproject.org/) - it is an open source initiative that embodies the vision that publishers can create mobile optimized content once and have it load instantly everywhere.
		* [Introducing the Accelerated Mobile Pages Project, for a faster, open mobile web](https://googleblog.blogspot.it/2015/10/introducing-accelerated-mobile-pages.html) (Oct 7, 2015) - Smartphones and tablets have revolutionized the way we access information, and today people consume a tremendous amount of news on their phones. Today, after discussions with publishers and technology companies around the world, we’re announcing a new open source initiative called Accelerated Mobile Pages, which aims to dramatically improve the performance of the mobile web. We want webpages with rich content like video, animations and graphics to work alongside smart ads, and to load instantaneously. We also want the same code to work across multiple platforms and devices so that content can appear everywhere in an instant—no matter what type of phone, tablet or mobile device you’re using.


## Libraries for Readability feature

### Java

* [boilerpipe](https://code.google.com/p/boilerpipe/) - Boilerplate Removal and Fulltext Extraction from HTML pages.  
From this [Instapaper-like algorithm](http://stackoverflow.com/questions/4283418/instapaper-like-algorithm) stackoverflow question, I landed to boilerpipe.
The boilerpipe library provides algorithms to detect and remove the surplus "clutter" (boilerplate, templates) around the main textual content of a web page.  
The library already provides specific strategies for common tasks (for example: news article extraction) and may also be easily extended for individual problem settings.  
Extracting content is very fast (milliseconds), just needs the input document (no global or site-level information required) and is usually quite accurate.  
Boilerpipe is a Java library written by Christian Kohlschütter. It is released under the Apache License 2.0.   
It is possible to test drive boilerpipe on the Web: [http://boilerpipe-web.appspot.com/](http://boilerpipe-web.appspot.com/)
* [wuman/JReadability](https://github.com/wuman/JReadability) - JReadability is a Java library that parses HTML as input and returns clean, easy-to-read text. JReadability is a Java port of arc90's original Javascript project Readability. (The original Readability.js project is now migrated to become a server-side platform which as far as I know is no longer open source.)
* [karussell/snacktory](https://github.com/karussell/snacktory) - This is a small helper utility for people who don't want to write yet another java clone of Readability. In most cases, this is applied to articles, although it should work for any website to find its major area, extract its text, keywords, its main picture and more. [Snacktory – Yet another Readability clone. This time in Java.](https://karussell.wordpress.com/2011/07/12/snacktory-yet-another-readability-clone-this-time-in-java/)

### C Sharp

* [ReadSharp](https://github.com/ceee/ReadSharp) - Extract meaningful website contents using a port of NReadability. Non si installa su VS2010 - sembra che il progetto sia per VS2013
* [NReadability](https://github.com/marek-stoj/NReadability) - NReadability cleans up hard-to-read articles on the Web. It's a tool for removing clutter from HTML pages so that they are more enjoyable to read. The NReadability package consists of the .NET class library and a simple console application. NReadability is a C# port of [Arc90's Readability bookmarklet](http://lab.arc90.com/2009/03/02/readability/).

### Scala
* [GravityLabs/goose](https://github.com/GravityLabs/goose) (Latest commit on Dec 1, 2015) - Html Content / Article Extractor in Scala - open sourced from [Gravity Labs](http://gravity.com) - a recommendation engine for content.


## Similar projects
Here are posts about read-it-later projects:

* [Wallabag to serve your open source read-it-later app needs](https://opensource.com/life/14/4/open-source-read-it-later-app-wallabag) (Apr 9, 2014)
* [PinBoard](https://pinboard.in/) - here is a [tour](https://pinboard.in/tour/) of Pinboard and [here](https://pinboard.in/api) the API (v1) documentation.
* [Building a self-hosted “Instapaper”](http://cataspanglish.com/blog/2012/05/20/building-a-self-hosted-instapaper/) (May 20, 2012) - about creating an opensource version of Instapaper.

More about Wallabag:

* [Wallabag Service](https://www.wallabag.it/en/features) - [wallabag](https://wallabag.org/) is an [open source](https://github.com/wallabag) application to save your web articles and allows you to read them later, on your smartphone, your tablet or your ereader. We propose to you a quality service to host your account: you'll get the latest version of the application and you'll get a professional support.
	* [Framabag](https://www.framabag.org/) - Framabag est un service libre et gratuit proposé par le réseau [Framasoft](http://framasoft.org/). Framabag est une instance de [wallabag](http://www.wallabag.org/).


## Competitors
These are post about read-it-later services:

* [The best read-it-later service - Instapaper](http://thesweetsetup.com/apps/best-read-it-later-service/) (Jul 7, 2015)
* [Readability: 5 Best Tools to Help Save Web Pages for Reading Later](http://www.technorms.com/41317/5-best-tools-to-help-save-web-pages-for-reading-later) (Nov 7, 2014)
* ["Read Later" Apps Compared: Pocket vs. Instapaper vs. Readability](http://lifehacker.com/5894995/bookmark-and-read-later-apps-compared-read-it-later-vs-instapaper-vs-readability) (Aug 27, 2013)
* [9 Tools To Save What You Read On The Web For Later](http://www.makeuseof.com/tag/9-tools-to-save-what-you-read-on-the-web-for-later/) (Feb 28, 2013)

.. and these are the main competitor apps that do it in a nice way:

* [Pocket](https://getpocket.com/) -  [Google Play](https://play.google.com/store/apps/details?id=com.ideashower.readitlater.pro)
* [Instapaper](https://www.instapaper.com/) - [Google Play](https://play.google.com/store/apps/details?id=com.instapaper.android)
* [Readability](https://www.readability.com/) - [Google Play](https://play.google.com/store/apps/details?id=com.readability) - shutdown on Sep 30, 2016 - here is the [announcement](https://medium.com/@readability/the-readability-bookmarking-service-will-shut-down-on-september-30-2016-1641cc18e02b)

