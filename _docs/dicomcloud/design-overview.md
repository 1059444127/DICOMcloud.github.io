---
title: Design Overview
navigation: dicomcloud
---

The DICOMcloud server is built with extensibility in mind. 
That means that you can virtually extend and customize any part of the framework to suit your needs and plug-it into the framework. 

This also means that there is an initial learning curve to understand how all the pieces fit together. The good news is, 
if you are already familiar with the standard Software Design Patterns, such as the below, you will find it easy to follow along:
1. [Builder](http://www.dofactory.com/net/builder-design-pattern)
2. [Factory](http://www.dofactory.com/net/factory-method-design-pattern)  
3. [Command](http://www.dofactory.com/net/command-design-pattern)
4. Constructor Injection ([Dependency Injection](http://www.dotnettricks.com/learn/dependencyinjection/implementation-of-dependency-injection-pattern-in-csharp))
5. ...

The best place to start with if you like to extend and customize the DICOMcloud server is to look at the [DICOMcloudBuilder](https://github.com/DICOMcloud/DICOMcloud/blob/development/DICOMcloud.Wado.WebApi/App_Start/DICOMcloudBuilder.cs) class.

This class is the entry point that constructs and build all the components necessary to run the server.
