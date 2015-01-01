Live ServiceStack Demos
=======================

Live Demos of ServiceStack Apps

## [TechStacks](https://github.com/ServiceStackApps/TechStacks)

> TechStacks is a [AngularJS App](https://github.com/ServiceStack/ServiceStackVS/blob/master/angular-spa.md) that lets you explore TechStacks of popular StartUps using your favorite technologies

[![TechStacks](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/techstacks/screenshots/techstacks.png)](http://techstacks.io)

#### Features 

TechStacks is based on a [Bootstrap template](http://getbootstrap.com) with client-side features:

 - HTML5 Routing to enable pretty urls, also supports full page reloads and back button support
 - Same Services supporting both human-readable Slugs or int primary keys
 - Responsive design supporting iPad Landscape and Portrait modes
 - Preloading and background data fetching to reduce flicker and maximize responsiveness
 - [Disqus](https://disqus.com/) commenting system
 - [Chosen](http://harvesthq.github.io/chosen/) for UX-friendly multi combo boxes

and some of TechStacks back-end features include: 

 - [Twitter and GitHub OAuth Providers](https://github.com/ServiceStack/ServiceStack/wiki/Authentication-and-authorization)
 - Substitutable [OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite) RDBMS [PostgreSQL and Sqlite](https://github.com/ServiceStackApps/TechStacks/blob/875e78910e43d2230f0925b71d5990497216511e/src/TechStacks/TechStacks/AppHost.cs#L49-L56) back-ends
 - [Auto Query](https://github.com/ServiceStack/ServiceStack/wiki/Auto-Query) for automatic services of RDBMS tables
 - [RDBMS Sessions and In Memory Caching](https://github.com/ServiceStack/ServiceStack/wiki/Caching)
 - [Smart Razor Views](http://razor.servicestack.net)
 - [Fluent Validation](https://github.com/ServiceStack/ServiceStack/wiki/Validation)

## [React Chat](https://github.com/ServiceStackApps/Chat-React)

> React.js port of ServerEvents Chat using React, Reflux and new **ReactJS App** VS.NET Template

[![React Chat](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/chat-react-multichannels.png)](http://react-chat.servicestack.net?channels=home,work,play)

#### Features 

 - [Modern ReactJS App Template](https://github.com/ServiceStackApps/Chat-React#modern-reactjs-apps-with-net)
   - [npm](https://www.npmjs.org/) to manage node.js dependencies (bower, grunt, gulp)
   - [Bower](http://bower.io/) for managing client dependencies (angular, jquery, bootstrap, etc)
   - [Grunt](http://gruntjs.com/) as the primary task runner for server, client packaging and deployments
   - [Gulp](http://gulpjs.com/) used by Grunt to do the heavy-lifting bundling and minification
 - [Intro guide into React.js](https://github.com/ServiceStackApps/Chat-React#introducing-reactjs)
 - [Designing a React App](https://github.com/ServiceStackApps/Chat-React#react-components)
 - [Flux vs Reflux](https://github.com/ServiceStackApps/Chat-React#flux-vs-reflux)
 - [ReactJS App Deployments with Grunt/Gulp and MS Deploy](https://github.com/ServiceStackApps/Chat-React#reactjs-app-deployments)

## [Chat](https://github.com/ServiceStackApps/Chat)

> Feature rich Single Page Chat App, showcasing Server Events support in 170 lines of JavaScript!

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/chat.png)](http://chat.servicestack.net)

#### Features 

  - [Server Events](https://github.com/ServiceStackApps/Chat#server-sent-events)
    - [Sending Events](https://github.com/ServiceStackApps/Chat#sending-server-events)
    - [Event Subscription](https://github.com/ServiceStackApps/Chat#event-subscription)
  - [Channels](https://github.com/ServiceStackApps/Chat#channels)
  - [Client Bindings - ss-utils.js](https://github.com/ServiceStackApps/Chat#client-bindings---ss-utilsjs)
  - [Remote Control](https://github.com/ServiceStackApps/Chat#remote-control)
    - [Selectors](https://github.com/ServiceStackApps/Chat#selectors)
    - [Global Event Handlers](https://github.com/ServiceStackApps/Chat#global-event-handlers)
    - [Postfix jQuery selector](https://github.com/ServiceStackApps/Chat#postfix-jquery-selector)
    - [Modifying CSS via jQuery](https://github.com/ServiceStackApps/Chat#modifying-css-via-jquery)
    - [jQuery Events](https://github.com/ServiceStackApps/Chat#jquery-events)
    - [Receivers](https://github.com/ServiceStackApps/Chat#receivers)
  - [Direct Messaging](https://github.com/ServiceStackApps/Chat#sending-a-message-to-a-specific-user)
  - [Server Event Services](https://github.com/ServiceStackApps/Chat#server-event-services)

## [Http Benchmarks](https://github.com/ServiceStackApps/HttpBenchmarks)

> Upload Apache HTTP Benchmarks to visualize, analyze and export their results. Includes Integration with Glimpe, DotNetOpenAuth, FineUploader, DotNetZip and Highcharts.js. 

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/httpbenchmarks-02.png)](https://httpbenchmarks.servicestack.net)

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/httpbenchmarks.png)](https://httpbenchmarks.servicestack.net/databases-in-asp-net?id=120)

#### Features 

  - [Interchangeable OrmLite PostgreSql and Sqlite](https://github.com/ServiceStackApps/HttpBenchmarks/blob/master/src/BenchmarksAnalyzer/Global.asax.cs#L40-L49)
  - Multiple Authentication, [Credentials and OAuth Providers](https://github.com/ServiceStackApps/HttpBenchmarks#authentication)
  - [Glimpse Integration](https://github.com/ServiceStackApps/HttpBenchmarks#setting-up-glimpse)
  - Minimal JS Deps with [Really Simple MV Pattern](https://github.com/ServiceStackApps/HttpBenchmarks#minimal-javascript-dependencies)
  - Multiple [File and Zip uploads](https://github.com/ServiceStackApps/HttpBenchmarks#integration-with-servicestack)
  - [Integration with HighCharts](https://github.com/ServiceStackApps/HttpBenchmarks#integration-with-highcharts)
  - [AutoGrid and multiple export options](https://github.com/ServiceStackApps/HttpBenchmarks#the-magic-autogrid-partial)
  - [Hosting on AWS](https://github.com/ServiceStackApps/HttpBenchmarks#hosting-on-aws)
   - [Deploying to AWS](https://github.com/ServiceStackApps/HttpBenchmarks#deploying-to-aws) 
  - [Configuring SSL](https://github.com/ServiceStackApps/HttpBenchmarks#configuring-ssl)


## [Email Contacts](https://github.com/ServiceStackApps/EmailContacts)

> Guidance on creating ServiceStack App from Scratch utilizing RabbitMQ support for Emails

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/emailcontacts.png)](http://emailcontacts.servicestack.net)

#### Features

  - [OrmLite](https://github.com/ServiceStackApps/EmailContacts#ormlite)
  - [Accessing AppSettings](https://github.com/ServiceStackApps/EmailContacts#accessing-appsettings)
  - [Registering Dependencies](https://github.com/ServiceStackApps/EmailContacts#registering-dependencies)
  - [Profiling](https://github.com/ServiceStackApps/EmailContacts#profiling)
  - [Razor Pages](https://github.com/ServiceStackApps/EmailContacts#razor-pages)
    - [No Ceremony option - Dynamic pages without Controllers](https://github.com/ServiceStackApps/EmailContacts#the-no-ceremony-option---dynamic-pages-without-controllers)
    - [Accessing Db Directly](https://github.com/ServiceStackApps/EmailContacts#accessing-db-directly)
    - [Accessing Services and Dependencies](https://github.com/ServiceStackApps/EmailContacts#accessing-services-and-dependencies)
    - [Embedded JSON](https://github.com/ServiceStackApps/EmailContacts#embedded-json)
    - [Loaded via Ajax](https://github.com/ServiceStackApps/EmailContacts#loaded-via-ajax)
    - [View Model](https://github.com/ServiceStackApps/EmailContacts#view-model)
  - [API-first development](https://github.com/ServiceStackApps/EmailContacts#api-first-development)
    - [Bootstrap Forms](https://github.com/ServiceStackApps/EmailContacts#bootstrap-forms)
    - [Binding HTML Forms](https://github.com/ServiceStackApps/EmailContacts#binding-html-forms)
    - [Fluent Validation](https://github.com/ServiceStackApps/EmailContacts#fluent-validation)
    - [Declarative Events](https://github.com/ServiceStackApps/EmailContacts#declarative-events)
    - [Data Binding](https://github.com/ServiceStackApps/EmailContacts#data-binding)
    - [Advanced bindForm usages](https://github.com/ServiceStackApps/EmailContacts#advanced-bindform-usages)
  - [Message Queues](https://github.com/ServiceStackApps/EmailContacts#message-queues)
    - [Rabbit MQ](https://github.com/ServiceStackApps/EmailContacts#rabbit-mq)
  - [Integration Tests](https://github.com/ServiceStackApps/EmailContacts#integration-tests)
  - [Unit Tests](https://github.com/ServiceStackApps/EmailContacts#unit-tests)

## [MVC](https://github.com/ServiceStack/ServiceStack/wiki/ServiceStack-Integration)

> Simple demo showcasing integration and authentication with ServiceStack from ASP.NET MVC

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/mvc.png)](http://mvc.servicestack.net)

#### Features

  - [ServiceStack Integration with MVC](https://github.com/ServiceStack/ServiceStack/wiki/ServiceStack-Integration)
  - [Authentication and Authorization](https://github.com/ServiceStack/ServiceStack/wiki/Authentication-and-authorization)
    - Twitter
    - Facebook
    - GitHub
    - Google+
    - Yahoo
    - LinkedIn
    - VK
    - Yandex
    - Windows Auth
  - [JS Utils and Forms AutoBinding](https://github.com/ServiceStack/ServiceStack/wiki/ss-utils.js-JavaScript-Client-Library)

> Demo for ServiceStack with ASP.NET WebForms available at [webforms.servicestack.net](http://webforms.servicestack.net/)

## [StackApis](https://github.com/ServiceStackApps/StackApis)

> AngularJS Single Page App leveraging AutoQuery in <50 lines of JavaScript + 1 AutoQuery DTO 

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/stackapis.png)](http://stackapis.servicestack.net)

#### Features

 - [AutoQuery](https://github.com/ServiceStack/ServiceStack/wiki/Auto-Query)
 - [StackApis AutoQuery Service](https://github.com/ServiceStackApps/StackApis#stackapis-autoquery-service)
 - [OrmLite Sqlite](https://github.com/ServiceStack.OrmLite)

## [Imgur](https://github.com/ServiceStackApps/Imgur)

> Imgur-like App to resize uploaded images in all iOS Resolutions in <30 lines of JavaScript + 1 ServiceStack ImageService

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/imgur.png)](http://imgur.servicestack.net)

#### Features

 - [1 default.html page](https://github.com/ServiceStackApps/Imgur/blob/master/src/Imgur/default.html)
 - [1 ServicStack back-end .cs file](https://github.com/ServiceStackApps/Imgur/blob/master/src/Imgur/Global.asax.cs)


## [Todos](https://github.com/ServiceStackApps/Todos)

> Backbone.js Todo App powered by a C# Redis Client back-end

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/todos.png)](http://todos.servicestack.net)

#### Features

 - [1 ServicStack back-end .cs file](https://github.com/ServiceStackApps/Todos/blob/master/src/Todos/Global.asax.cs)
 - [ServiceStack.Redis](https://github.com/ServiceStack/ServiceStack.Redis)


## [Razor Rockstars](https://github.com/ServiceStackApps/RazorRockstars)

> Showcase of ServiceStack's unified HTTP Stack with Razor support, embedded Markdown Razor Views, Controller-less Razor Pages, Cascading Layout templates, Smart View Pages, Flexible Layouts

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/razor.png)](http://razor.servicestack.net)

#### Features

 - [OrmLite Sqlite](https://github.com/ServiceStack.OrmLite)
 - [Runs Everywhere](http://razor.servicestack.net/#runs-everywhere)
   - [Any ASP.NET host](https://github.com/ServiceStackApps/RazorRockstars/tree/master/src/RazorRockstars.WebHost)
   - [A Stand-alone, self-hosted HttpListener](https://github.com/ServiceStackApps/RazorRockstars/tree/master/src/RazorRockstars.SelfHost)
   - [A Stand-alone Windows Service](https://github.com/ServiceStackApps/RazorRockstars/tree/master/src/RazorRockstars.WinService)
 - Self-hosted HttpListener with
   - [Entire App ILMerged into a single cross-platform App.exe](https://github.com/ServiceStack/ServiceStack.Gap#self-hosting-console-app)
   - [Hosted inside WinForms with Chromium Embedded Framework](https://github.com/ServiceStack/ServiceStack.Gap#winforms-with-chromium-embedded-framework)
   - [Hosted inside Mac OSX Cocoa App with Xmarain.Mac](https://github.com/ServiceStack/ServiceStack.Gap#mac-osx-cocoa-app-with-xmarainmac)
 - [One simple and unified HTTP stack](http://razor.servicestack.net/#unified-stack)
 - [No Ceremony Option](http://razor.servicestack.net/#no-ceremony)
 - [Smart View Pages](http://razor.servicestack.net/#smart-views)
 - [Built-in Markdown](http://razor.servicestack.net/#markdown)
 - [Optimized for developer productivity](http://razor.servicestack.net/#optimized-for-dev)

## [Social Bootstrap API](https://github.com/ServiceStackApps/SocialBootstrapApi)

> Backbone.js-based Single Page Twitter Client App built integrating with ASP.NET MVC and showcasing multiple Auth Providers enabled in a Single App

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/bootstrapapi.png)](http://bootstrapapi.servicestack.net)

#### Features

 - [MVC Integration](https://github.com/ServiceStack/ServiceStack/wiki/Mvc-integration)
 - [Multiple Auth Providers](https://github.com/ServiceStack/ServiceStack/wiki/Authentication-and-authorization)

## [Redis Admin UI](https://github.com/ServiceStackApps/RedisAdminUI)

> Google Closure Admin UI and typed backend services API for redis-server operations

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/redisadminui.png)](http://redisadminui.servicestack.net)

#### Features

 - [Over 100+ Web Services](redisadminui.servicestack.net/redis/metadata)
 - [ServiceStack.Redis C# Client](https://github.com/ServiceStack/ServiceStack.Redis)

## [Rest Files](https://github.com/ServiceStackApps/RestFiles)

> GitHub-like browser with complete remote file management over REST APIs in 1 page of jQuery and 1 FileService.cs

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/restfiles.png)](http://restfiles.servicestack.net)

#### Features

 - [1 Page jQuery](https://github.com/ServiceStackApps/RestFiles/blob/master/src/RestFiles/RestFiles/default.htm)
 - [1 ServiceStack FilesService](https://github.com/ServiceStackApps/RestFiles/blob/master/src/RestFiles/RestFiles.ServiceInterface/FilesService.cs)

## [Redis StackOverflow](https://github.com/ServiceStackApps/RedisStackOverflow)

> Mini StackOverflow Single Page App built using just ServiceStack + Redis

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/redisstackoverflow.png)](http://redisstackoverflow.servicestack.net)

#### Features

 - [1 Page jQuery](https://github.com/ServiceStackApps/RedisStackOverflow/blob/master/src/RedisStackOverflow/RedisStackOverflow/default.htm)
 - [1 Redis Repository](https://github.com/ServiceStackApps/RedisStackOverflow/blob/master/src/RedisStackOverflow/RedisStackOverflow.ServiceInterface/IRepository.cs)
 - [ServiceStack.Redis C# Client](https://github.com/ServiceStack/ServiceStack.Redis)


## [Northwind](https://github.com/ServiceStackApps/Northwind)

> Northwind database viewer, showing how to easily expose read and cached view services of an internal dataset with ServiceStack + OrmLite

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/northwind.png)](http://northwind.servicestack.net)

#### Features

 - [OrmLite Sqlite](https://github.com/ServiceStack.OrmLite)
 - [Multiple automatic built-in Content-Types](http://northwind.servicestack.net/default.htm)
 - [Custom Media Types - Adding vcard format](http://northwind.servicestack.net/vcard-format.htm)
 - [1 CachedService](https://github.com/ServiceStackApps/Northwind/blob/master/src/Northwind/Northwind.ServiceInterface/CachedServices.cs)



## [Docs](https://github.com/ServiceStackApps/Docs)

> A Content Heavy Ajax site using built just using Markdown Razor

[![](https://raw.githubusercontent.com/ServiceStack/Assets/master/img/livedemos/docs.png)](http://docs.servicestack.net)

#### Features

 - [Markdown Razor](https://github.com/ServiceStack/ServiceStack/wiki/Markdown-Razor)

----

## [ServiceStack.UseCases](https://github.com/ServiceStack/ServiceStack.UseCases)

We're also developing single-purpose applications showcasing single use-cases at: 

  - Custom Authentication and [Integration with ASP.NET](https://github.com/ServiceStack/ServiceStack.UseCases/tree/master/CustomAuthentication)
  - Custom Authentication and [Integration with ASP.NET MVC](https://github.com/ServiceStack/ServiceStack.UseCases/tree/master/CustomAuthenticationMvc)
  - [Multi Hello World](https://github.com/ServiceStack/ServiceStack.UseCases/blob/master/HelloWorld/Global.asax.cs)- Different ways to say Hello, with built-in Content-Types, text, html and generating a dynamic image
  - [Reusability](https://github.com/ServiceStack/ServiceStack.UseCases/tree/master/Reusability) - showcasing how you can re-use the same services inside MQ hosts to provide instant response times and transparent parallel execution
  - [Poco Power](https://github.com/ServiceStack/ServiceStack.UseCases/blob/master/PocoPower/Program.cs) - Showing how you can re-use the same POCOs in all ServiceStack client libraries. From maintaing complex types in Web.config to creating DB tables with OrmLite to calling 3rd Party twitter and GitHub REST APIs and storing and retrieving them in RDBMS and Redis
  - [NodeStackProxy](https://github.com/ServiceStack/ServiceStack.UseCases/tree/master/NodeStackProxy) - Use node.js as a front-end proxy to a backend ServiceStack instance on Windows and OSX/Linux
  - [Swagger Hello World](https://github.com/ServiceStack/ServiceStack.UseCases/tree/master/SwaggerHelloWorld) - Simple service with Swagger integration and features enabled
  - [WebApi Products Example](https://github.com/ServiceStack/ServiceStack.UseCases/tree/master/WebApi.ProductsExample) - Showcase the differences rewriting WebApi products into a ServiceStack service

## [Starter Templates](https://github.com/ServiceStack/ServiceStack.Examples/tree/master/src/StarterTemplates)

Different working starting templates for popular configurations of ServiceStack:

  - [At custom path, like  /api](https://github.com/ServiceStack/ServiceStack.Examples/tree/master/src/StarterTemplates/CustomPath40)
  - [At / root path](https://github.com/ServiceStack/ServiceStack.Examples/tree/master/src/StarterTemplates/RootPath40)
  - [A stand-alone HttpListener Console AppHost](https://github.com/ServiceStack/ServiceStack.Examples/tree/master/src/StarterTemplates/ConsoleAppHost)
  - [A Windows Service AppHost](https://github.com/ServiceStack/ServiceStack.Examples/tree/master/src/StarterTemplates/WinServiceAppHost)

Many of these Starter template are included in [ServiceStackVS VS.NET Extension](https://github.com/ServiceStack/ServiceStack/wiki/Creating-your-first-project).
