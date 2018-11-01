---
layout: page
title: About
permalink: /about/
---
##### Overview

- Architect for Bud an Apprenticeship Management System ([www.bud.co.uk](https://www.bud.co.uk)) which was designed and implemented using a MicroService Event Driven approach on Microsoft Azure
- Architected and delivered several projects such as Portfolio Manager a Modular KnockoutJS Application helping consumers manage their investment portfolios. Data API a ASP Web API Application exposing investment security data via the OData Standard. Lastly, FundsLibrary Components a modular components framework allowing security data and analysis to be embedded into any HTML page.
- Helped transition a team and business to an Agile way of working in as a way of delivering value, managing project risk/expectation and engage stakeholders
- Setup Continuous Integration/Deployment using VSTS, Cake.NET, Azure Classic Cloud and Azure App Services using GitFlow and the VSTS Pull Request System to manage the process of feature work coming into the service repositories
- Knowledge of several front and backend technologies such as HTML, CSS, jQuery, Knockout JS, Angular 2+, TypeScript, Castle Monorail, ASP.NET MVC, WebForms, ASP.NET Web API, Razor, nVelocity, nUnit, Rhino Mocks, Fake it Easy, Specflow, and nServiceBus.
- Use of Redux design pattern in conjunction with Angular 2+
- Exposure to SOA, CQRS, Event Sourcing and Messaging patterns specifically using nServiceBus, MSMQ and Azure Service Bus.
- Understanding and practice of Dependency Injection and TDD with specific use of Castle Windsor, nUnit, Rhino Mocks, Fake it Easy and Moq.
- Confident with several traditional database technologies including SQL Server, nHibernate, LINQ, Entity Framework and SQL.
- Exposure to Elasticsearch and Cosmos DB as NoSQL databases. 
- Involved in Business Strategy meetings in order to advise the business on how Development and the Product Roadmap can be organised to help meet their business objectives

##### Bud - Technical Architect 

###### Aug 2016/Dec 2018

###### Bristol

- Architected a distributed microservice solution using Web API 2, nServiceBus, Identity Server 3, Fluent Validation, Cosmos DB, Entity Framework with SQL Server using Angular 2+ with Redux as a Frontend Framework. Initially using Angular Seed but the moving to Angular CLI when it matured.
- Used nServiceBus in conjunction with Azure Service Bus as a Transport Layer and Azure Storage as Persistence for Saga Data.
- Setup a Continuous Integration & Deployment pipeline via Visual Studio Team Services to deploy backend & frontend services to the Azure Cloud. Initially via the Classic Cloud model but eventually moving to App Services when migrating to a true microservice deployment model. Using App Services, I deployed our Web API & Angular 2+ projects as Web Apps and our nServiceBus endpoints as WebJobs.
- Used Cake.NET to create an independent Build, Package and Deployment process which could be used on any CI/CD services as well as run locally. This process also automatically managed the publishing of internal NuGet packages for our internal teams to consume via MyGet.
- Implemented Azure Key Vault as a technology to keep configuration values secret and secure.
- Setup ELK (ElasticSearch, Logstash, Kibana) as an approach for Logging using Log4Net throughout the application.
- Used Identify Server 3 as a federated identity provider for our Microservices and our SPA (Single Page Application).
- Involved in Product Strategy meetings, advising and debating with the business the order and difficulty of features and epics to try and ensure the most business value could be delivered by the development team in-line with the business strategy.
- Skills: ASP.NET Web API, nServiceBus, Azure Service Bus, Azure Storage, Identity Server 3, Cosmos DB, SQL Server, Entity Framework, Angular 2+, VSTS, Azure Classic Cloud, Azure App Services, Azure Key Vault, Cake.NET, MyGet, ELK

##### FundsLibrary - Senior Developer 

###### Jun 2014/Aug 2016

###### Bristol

- Lead role architecting, developing and delegating work for a new web service. Built on top of elasticsearch and populated via a process which maps data from our legacy SQL Server schema to documents. This data is then exposed using Microsoft ODATA framework in conjunction with ASP.NET Web API. Using ElasticLINQ to execute the expression trees the ODATA framework builds.
  - [https://fundslibrary.uk/products/fund-data-hub/galaxia-data-api/](https://fundslibrary.uk/products/fund-data-hub/galaxia-data-api/)
  - [https://www.fundslibrary.co.uk/FundsLibrary.DataApi.Web/](https://www.fundslibrary.co.uk/FundsLibrary.DataApi.Web/)
- Contributed to ElasticLINQ creating an abstraction around the underlying connection. Allowing us to use a richer underlying framework elasticsearch-net which supported connection pooling.
  - [https://github.com/ElasticLINQ/ElasticLINQ](https://github.com/ElasticLINQ/ElasticLINQ)
- Collaboratively Architected and developed components a product built on the new web service. Using Knockout, SystemJS and TypeScript we have developed several suites of autonomous Knockout Components. Components deals with individual securities, exposing data as small text components, D3 charts, or more complex components which make calculations based on a portfolio of securities combined with user input. These components can then be composed together and embedded in client solutions to create applications.
- Developed and Maintained features for several client solutions which have been built using ASP.NET MVC, Web Forms, XSL and other C# based applications.
- Skills: ASP.NET Web API, ODATA, Elasticsearch, Typescript, Knockout JS, SystemJS

##### Brightside - Developer

###### Jun 2013/Jun 2014

###### Bristol

- Maintained Brightside brokering system which has been built using PHP, COM, C#, Visual Basic with a MySql database.
- Worked within an Agile development team.
- Policy Search feature. Identifying policies which could fit up to 25 different search criteria, used a batched singular query per criteria approach, whilst then using LINQ to filter datasets by each individual criteria and finally intersect to find policies which matched all specified criteria. This was exposed via a fluent API.
- Policy and Contract State Calculator. Designed and developed a rules engine to determine the explicit state of a Brightside insurance policies. The business rules surrounding policies are implicitly applied throughout the layers of technology in the system. This allowed the explicit state of Policies and its contracts to be calculated.
- Devised a proof of concept of running PHP and ASP.NET MVC/Web Api side by side as a way of migrating away from PHP. This involved creating shared sessions and authentication between the two process whilst also wrapping the COM service layer through the use of dynamic objects.
- Skills: Agile, C#, PHP, Visual Basic

##### ILLY Systems - Analyst/Programmer

###### Aug 2011/Jun 2013

###### London

- Developed and maintained Illy CarePath our flagship healthcare software which has been built using Castle Monorail an open source MVC framework along with Castle Windsor for Dependency Injection.
  - [https://www.illycorp.com/featured/carepath/](https://www.illycorp.com/featured/carepath/)
- Implemented new CarePath features using Specflow, SOA, nServiceBus, MSMQ, CQRS and nHibernate. Such features have been dashboard plug-ins for example, which involves adding Command messages in the legacy parts of the system, writing message handlers in order to handle event messages and maintain a de-normalised data store, nHibernate to query the data and AJAX, jQuery and Knockout JS in order to develop the front end for the feature.
- Created cutting edge time based reporting solution using event sourcing. Keeping a serialised store of events in a database and then loading events up to a specified time period, building up the state of object to that date and evaluating whether or not they meet the reporting criteria.
- Profiled and Tuned queries. Upon finishing a feature nhProf and SQL Profile Manager is used to profile and analyse queries, with indexes and batching implemented in order to improve performance.
- Developed an internal CSV to XML tool using nUnit and Rhino Mocks with TDD practices.
- Presented upcoming features to around 50 people at the annual user group.
- Skills: Castle Monorail, Castle Windsor, nHibernate, Knockout JS, Specflow, nUnit, nServiceBus, Presenting

##### Fantasy League Ltd - Developer 

###### Jun 2010/Aug 2011

###### London

- Developed internal tools using ASP.NET MVC along with Dependency Injection frameworks such as Ninject and Microsoft Unity to assist the management of prediction, world cup cricket and finance games.
- Implemented and maintained functionality on Fantasy Finance and Football games using ASP.NET WebForms.
- Created front end applications and jQuery plugins such as a widget to display betting markets and odds for William Hill and an AJAX team selection screen. Using various javascript frameworks.
- Implemented new web service functionality using WCF allowing clients to consume for mobile applications.
- Studied Software Patterns such as the Generic Repository and Repository patterns using technologies such as Entity Framework Code First and Fluent nHibernate in order to improve the quality of my applications.
- Researched new technologies such as Continuous Integration and Entity Framework Code First.
- Produce in house statistical reports on several aspects of the Finance games using SQL.
- Skills: ASP.NET MVC, ASP.NET WebForms, WCF, Ninject, Microsoft Unity, C#, LINQ, Entity Framework Code First, WatiN, Selenium, AJAX, Javascript, jQuery, Software Patterns, SQL

##### Oracle - Fusion Human Capital Management Development

###### Jul 2008/Jul 2009

###### Reading

- Developed Oracle Fusion front end and back end functionality using JSP with Oracle JDeveloper.
- Produced technical components by working to Functional and Technical Design Documents, and consulting with product managers.
- Learnt cutting edge development technologies in a short space of time, through intensive training.
- Documented technical work produced in the forms of function design documents, technical design documents, and developer test cases.
- Created appropriate test data SQL scripts for use after database refreshes.
- Maintained the internal Corporate Social Responsibility (CSR) website, successfully introducing a new user interface and updating content, by conferring with CSR board members.
- Worked in a global development team, communicating effectively with colleagues in India, and America.
- Completed work successfully to a deadline.
- Skills: JSP Development, Communication, Meeting Deadlines, Professional Documentation

##### Education

###### Bournemouth University

1st Class, BSc(Hons) Computing

2006 - 2010

##### Interests and Other Information

I enjoy exercising, either in a small group of people like cycling or larger team sports such as football. I mountain bike and go out road cycling and this has turned into a real passion of mine as it's nice to ditch the city and discover some quaint cafes and pubs out in the countryside. I also enjoy night riding as it’s a lot more fun than going to a gym throughout winter. You can find me on Strava!

My main passion is technology. I have taught myself various technologies such as C#, ASP.NET MVC and WebForms, Entity Framework Code First, Dependency Injection, AJAX, jQuery and CSS. Whilst also achieving 87% in an online Mongo DB course for developers ([certificate](https://education.10gen.com/downloads/certificates/e5fd9db668db423ebf23944f1f6f5705/Certificate.pdf)). 

As I get older I have switched from pet projects and reading blogs to reading books around architecture, a favourite of mine being Domain Driven Design by Eric Evans. I have found reading has enabled me to think differently around of solving problems in order to create simpler more elegant solutions, with Udi Dahan, Greg Young and Jonathan Oliver’s thinking being of particular interest to me for backend solutions and Rob Eisenburg for a front-end approach.