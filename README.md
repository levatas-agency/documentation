# Documentation repository

## Table of contents

- [Git](#git)
- [Test-Driven Development](#test-driven-development)
- [Refactoring](#refactoring)
- [Google App Engine](#google-app-engine)
- [App Engine Pipelines](#app-engine-pipelines)
- [Angularjs](#angularjs)
- [Secure Sockets Layer - SSL](#secure-sockets-layer---ssl)

## Git

Git is a distributed revision control system with an emphasis on speed, data integrity, and support for distributed, non-linear workflows. Git was initially designed and developed by Linus Torvalds for Linux kernel development in 2005, and has since become the most widely adopted version control system for software development.

* [The Official Git Site](Git homepage) - Offers documentation for all Git commands as well as binary downloads of Git for all supported platforms.

* [Git Tutorial](https://www.atlassian.com/git/tutorials/) - A step by step Git tutorial covering from the very beginning to more advanced concepts.

* [Git Interactive Tutorial](https://try.github.io/) - This is an amazing interactive tutorial where you'll learn Git by actually using it in a simulated web terminal window.

* [Pro Git](http://git-scm.com/book/en/v2) - This is a book, free and online. It's great whenever you want to use it as a reference or as a starting guide to learn Git. 

* [Comparing Workflows](https://www.atlassian.com/git/tutorials/comparing-workflows/) - You can use different workflows to collaborate with your team using Git. This page covers some of the most popular workflows: [Centralized](https://www.atlassian.com/git/tutorials/comparing-workflows/centralized-workflow), [Feature Branch](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow), [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow), and [Forking Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow).

### GitHub

GitHub is a web-based Git repository hosting service, which offers all of the distributed revision control and source code management functionality of Git as well as adding its own features. Unlike Git, which is strictly a command-line tool, GitHub provides a web-based graphical interface and desktop as well as mobile integration. It also provides access control and several collaboration features such as wikis, task management, and bug tracking and feature requests for every project.

* [GitHub Guides](https://guides.github.com/) - Several guides on how to use GitHub and all its tools.

* [GitHub CheatSheet in English](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf) - Quick reference for common used Git commands and general GitHub usage.

* [Hoja de Referencia de GitHub en Español](https://training.github.com/kit/downloads/es/github-git-cheat-sheet.pdf) - Referencia para los comandos de Git más utilizados y detalles generales para el uso de GitHub.

## Test-Driven Development

* [Test Driven Development: By Example](http://www.amazon.com/Test-Driven-Development-Kent-Beck/dp/0321146530/ref=sr_1_1?ie=UTF8&qid=1430398587&sr=8-1&keywords=TDD) - This is an amazing book where Kent Beck illustrates how TDD should be done throughout an example. Must read to understand everything related to TDD.

* [Introduction to Test-Driven Development](http://agiledata.org/essays/tdd.html) - A quick tutorial about TDD.

* [TDD is not dead](https://blog.svpino.com/2014/05/15/tdd-is-not-dead) - A series of 5 hangout videos featuring Kent Beck, Martin Fowler, and  David H. Hansson where they discuss about TDD.

* [TDD Debate](https://www.youtube.com/watch?v=KtHQGs3zFAM) - A video where Jim Coplien and Bob Martin debate TDD. 

## Refactoring

Refactoring is the process of changing a software system in such a way that it does not alter the external behavior of the code yet improves its internal structure. 

* [Refactoring: Improving the Design of Existing Code](http://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672/ref=sr_1_1?ie=UTF8&qid=1429640710&sr=8-1&keywords=refactoring) - This is the one stop book for Refactoring. If you read this book, you probably don't need anything else listed below. It is that good.

* [What is Refactoring](http://c2.com/cgi/wiki?WhatIsRefactoring) - Take some time to discover what Refactoring is and isn't. (I know this web page looks very old and unpolished, but the content is amazing.)

* [Refactoring on the Web](https://sourcemaking.com/refactoring) - If you don't have the book mentioned above, and you are more of a web person, then you'll love this site. It contains a lot of material about Refactoring, including the links listed below for each technique.

* [Code Smells](https://sourcemaking.com/refactoring/bad-smells-in-code) - You can't learn about Refactoring without first knowing what _code smells_ are. Every refactoring technique was created to help mitigate one or several code smells.

* [Code Smells to Refactoring Cheat Sheet](http://www.industriallogic.com/wp-content/uploads/2005/09/smellstorefactorings.pdf) - Here is a list of code smells, each one with a corresponding list of refactoring techniques to solve the problem.  

### Dealing with duplicated code
As an example, here you have some refactoring techniques that will help you deal with duplicated code:

* [Extract Method](https://sourcemaking.com/refactoring/extract-method) - Extract Method is one of the most common refactoring techniques. Look at methods that are too long or look at code that needs a comment to understand its purpose. Then turn that fragment of code into its own method.

* [Extract Class](https://sourcemaking.com/refactoring/extract-class) - A class should be a crisp abstraction and handle a few clear responsibilities. As your class grows and becomes too complicated, you want to make sure to extract the functionality into a separate class to keep a well balanced design.

* [Pull Up Field](https://sourcemaking.com/refactoring/pull-up-field) - When subclasses are developed independently, or combined through refactoring, certain fields can end up being duplicated. As soon as you find out, you can generalize them up in the class herarchy.

## Google App Engine

Google App Engine is a Platform as a Service (PaaS) offering that lets you build and run applications on Google’s infrastructure. App Engine applications are easy to build, easy to maintain, and easy to scale as your traffic and data storage needs change. With App Engine, there are no servers for you to maintain. You simply upload your application and it's ready to go. 

These tutorials will guide you to implement a simple guest book that lets users post messages to a public message board.

* [Python](https://cloud.google.com/appengine/docs/python/gettingstartedpython27/introduction)

* [Java](https://cloud.google.com/appengine/docs/java/gettingstarted/introduction)

* [PHP](https://cloud.google.com/appengine/docs/php/gettingstarted/introduction)

##### Udacity Free Courses

You will learn how to harness the power of App Engine - Platform as a Service, run by Google, so you can focus on your application's features, not on managing infrastructure that runs your app.

* [Developing Scalable Apps in Python with Google App Engine](https://www.udacity.com/course/developing-scalable-apps-in-python--ud858)

* [Developing Scalable Apps in Java with Google App Engine](https://www.udacity.com/course/developing-scalable-apps-in-java--ud859)

## App Engine Pipelines

The Google App Engine Pipeline API connects together complex, time-consuming workflows, including human tasks. 

* [GitHub Repository](https://github.com/GoogleCloudPlatform/appengine-pipelines) - Java and Python libraries plus source code for both.

* [Pipelines Overview and Getting Started Guide](https://github.com/GoogleCloudPlatform/appengine-pipelines/wiki) - This is an introduction to App Engine Pipelines from the GitHub's Project Wiki. From here you can get access to specific documentation and examples for [Java](https://github.com/GoogleCloudPlatform/appengine-pipelines/wiki/Java) and [Python](https://github.com/GoogleCloudPlatform/appengine-pipelines/wiki/Python).

* [Google I/O 2011: Large-scale Data Analysis Using the App Engine Pipeline API](https://www.youtube.com/watch?v=Rsfy_TYA2ZY) - This video introduces the App Engine Pipeline API, how it works, and several scenarios where it's useful.

* [Java Examples](https://github.com/GoogleCloudPlatform/appengine-pipelines/tree/master/java/example/src/com/google/appengine/tools/pipeline/demo) - Example code using the App Engine Pipelines API in Java.

* [Python Examples](https://github.com/GoogleCloudPlatform/appengine-pipelines/tree/master/python/demo) - Example code using the App Engine Pipelines API in Python.


## Angularjs

AngularJS is a structural framework for dynamic web apps. It lets you use HTML as your template language and lets you extend HTML's syntax to express your application's components clearly. Angular's data binding and dependency injection eliminate much of the code you would otherwise have to write. And it all happens within the browser, making it an ideal partner with any server technology.

* [AngularJS Fundamentals in 60-ish Minutes](http://weblogs.asp.net/dwahlin/video-tutorial-angularjs-fundamentals-in-60-ish-minutes) - 60-ish Minutes to help break down the Angularjs learning curve. Learn how to get started with the AngularJS framework and some of the key features it provides that simplify SPA development.

* [Angular Basics](http://www.angularjsbook.com/) - A free interactive book, covering directives, modules, services, controllers, routing, and more.

* [Creating Custom AngularJS Directives Part I – The Fundamentals](http://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-i-the-fundamentals) - AngularJS directives can be a bit intimidating the first time you see them. Learn how pieces fit together and you'll find that they're not that bad.

* [Angular Style Guide by John Papa](https://github.com/johnpapa/angular-styleguide) - If you are looking for an opinionated style guide for syntax, conventions, and structuring Angular applications, then step right in.

## Secure Sockets Layer - SSL

SSL (Secure Sockets Layer) is the standard security technology for establishing an encrypted link between a web server and a browser. This link ensures that all data passed between the web server and browsers remain private and integral.

* [Configuring SSL in IIS Manager - Video](http://www.iis.net/learn/manage/configuring-security/configuring-ssl-in-iis-manager) - Enabling powerful SSL security to protect your Web applications is simpler to setup with IIS Manager and easier to deploy with self-signed certificates in IIS 7.0 and above.

* [How to Set Up SSL on IIS 7](http://www.iis.net/learn/manage/configuring-security/how-to-set-up-ssl-on-iis) - Steps for configuring Secure Sockets Layer (SSL) for a site.



