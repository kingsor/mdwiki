# URL shortener

## The project
* [on url shorteners](http://joshua.schachter.org/2009/04/on-url-shorteners) (Apr 2009) - pro and cons of url shortener services.

The idea started time ago but was awaked by this post [Frictionless .NET Web App Development with Nancy](http://www.horsdal-consult.dk/2011/10/frictionless-net-web-app-development.html) that I read looking for a sample for learning how to getting started with MongoDB and C#.

* [Developing a URL shortening service using Windows Azure SDK and C#](http://www.nakkala.net/2013/02/developing-url-shortening-service-using.html)
    * [Skewrl Reference application](https://github.com/anilnakkala/skewrl) - Skewrl implements an open source URL shortener using C#/.NET/Windows Azure.
    * [HomeController.cs](https://github.com/anilnakkala/skewrl/blob/master/Skewrl/Skewrl.Web.UI/Controllers/HomeController.cs) - generating short url
    * [FNVHash.cs](https://github.com/anilnakkala/skewrl/blob/master/Skewrl/Skewrl.Library/FNVHash.cs) - This is a partial C# implementation of hash algorithm by Fowler/Noll/Vo
* [How to code a URL shortener?](http://stackoverflow.com/questions/742013/how-to-code-a-url-shortener)
* [Naive bijective function in C#](https://gist.github.com/dgritsko/9554733)
* [manufacturing flic.kr style photo URLs](http://www.flickr.com/groups/api/discuss/72157616713786392/)
    * [Tiny Url’s in C#](http://www.faygate.net/post/133462295/tinyurlcode)

## Node.js + Heroku
* [kingsor/shortio-url-shortener](https://github.com/kingsor/shortio-url-shortener) - the repo of the project I created following the tutorial on CodeTuts.

### Resources
* [Let's build a URL Shortener with Node, MongoDB and Hapi.js](https://codetuts.tech/build-a-url-shortener-node-hapi-js/) (Aug 6, 2016) - tutorial about creating a url shortener web api with node.js, hapi.js and mongodb.
* [KishCom/shorten-node](https://github.com/KishCom/shorten-node) - A Node.js powered URL Shortener web app with Heroku deploy instructions. [http://kish.cm](http://kish.cm/)
* [KingPixil/snip](https://github.com/KingPixil/snip) - dead-simple URL shortener [http://snipit.ga](http://snipit.ga)
* [What is the “__v” field in MongoDB](http://stackoverflow.com/a/31872302/2768802) - if you don't need version_key ...

## NancyFx + AppHarbor
[kingsor/ShortURL](https://github.com/kingsor/ShortURL) - A simple url shortener project created with NancyFx and MongoDB

A small Nancy sample, showing a simplistic URL shortener done in Nancy, and hosted in a console app as well on ASP.NET.

Based on [ShortURL](https://github.com/horsdal/ShortURL) project by [Christian Horsdal](https://github.com/horsdal) following his tutorial [Frictionless .NET Web App Development with Nancy](http://www.horsdal-consult.dk/2011/11/frictionless-net-web-app-development.html)

Front-end based on [Shortio](https://github.com/luishendrix92/shortio) project by [Luis Lopez](https://github.com/luishendrix92) following his tutorial [Let's build a URL Shortener with Node, MongoDB and Hapi.js](https://www.codetuts.tech/build-a-url-shortener-node-hapi-js/)


### NancyFx
* [nerobianchi/visual_studio_gallery](https://github.com/nerobianchi/visual_studio_gallery) - nancy template for visual studio 2015
* [Nancy: Serving static content (e.g. index.html) from “/”](http://stackoverflow.com/a/21477824/2768802) - this way I can configure a folder (usually "Content" folder) in order to contain all files for SPA web app.
* [bojanv91/codecamp2013-speakersapp-demo](https://github.com/bojanv91/codecamp2013-speakersapp-demo) - The complete demo project from my CodeCamp's 2013 session "AngularJS + NancyFx + MongoDB = The best trio for ultimate SPA"
* [Creating a Nancy web api to store data in MongoDB](https://suttoncodefield.wordpress.com/2015/09/24/creating-a-nancy-web-api-to-store-data-in-mongodb/) (Sep 24, 2015) - Today I’m going to describe a quick example of a web api for storing and retrieving data in a MongoDB. All the code you need is described in the article but a working example is available in [github](https://github.com/edtyl3r/NancyDemo).


## Old links
* [Shrinkr](http://shrinkr.codeplex.com/) - Shrinkr is a Url Shortening Service which demonstrates some of the best practices in developing real life web applications. ASP.NET MVC 2, Entity Framework 4 (Code First).
	* [Shrinkr - Url Shrinking Service Developed with Entity Framework 4.0, Unity, ASP.NET MVC And jQuery](http://weblogs.asp.net/rashid/archive/2009/09/10/shrinkr-url-shrinking-service-developed-with-entity-framework-4-0-unity-asp-net-mvc-and-jquery-part-1.aspx)
	* [Part 2](http://weblogs.asp.net/rashid/archive/2009/09/13/shrinkr-url-shrinking-service-developed-with-entity-framework-4-0-unity-asp-net-mvc-and-jquery-part-2.aspx)
	* [Part 3](http://weblogs.asp.net/rashid/archive/2009/09/15/shrinkr-url-shrinking-service-developed-with-entity-framework-4-0-unity-asp-net-mvc-and-jquery-part-3.aspx)
* [miniurl](http://miniurl.codeplex.com/) - Sample ASP.NET MVC application to show how to create URL shrink/snippet/etc and handling of shorten URLs.
* [Rick URL Shortening Service – an ASP.net MVC learning project](http://www.stum.de/2008/12/14/rick-url-shortening-service-an-aspnet-mvc-learning-project/)
* [How to reverse engineer a shortened URL](http://blogs.msdn.com/b/amb/archive/2011/02/13/how-to-reverse-engineer-a-shortened-url.aspx)
* [SHOV.IN – AN(OTHER) ASP.NET MVC URL SHORTENER](http://dochoffiday.com/Professional/shov-in-an-other-asp-net-mvc-url-shortener)
* [TinyURL](http://tinyurl.com/) - Making over a billion long URLs usable! Serving billions of redirects per month.
* [Create your own branded url-shortener in under 10 minutes using ASP.NET MVC 2](http://anderly.com/2010/06/10/create-your-own-branded-url-shortener-in-under-10-minutes-using-asp-net-mv2/)
* [Logic Ideas - Building a URL Shortener Service with C# and WCF](http://stackoverflow.com/questions/5528429/logic-ideas-building-a-url-shortener-service-with-c-sharp-and-wcf)
* [Making a short URL similar to TinyURL.com](http://stackoverflow.com/questions/1671059/making-a-short-url-similar-to-tinyurl-com)
* [Twitter Crowns Bit.ly As The King of Short Links; Here's What It Means](http://www.readwriteweb.com/archives/twitter_crowns_bitly_as_the_king_of_short_links_he.php)
* [Hate The Bitly Update? Here Are 5 Alternative URL Shorteners For Twitter](http://www.mediabistro.com/alltwitter/5-url-shorteners-twitter_b23303)