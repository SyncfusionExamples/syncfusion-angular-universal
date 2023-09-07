# Angular Universal: Server-side Rendering in Angular Frameworks

Angular is a widely-used client-side web development framework. However, by default, it operates exclusively on the client-side. Many web development tools are tailored for server-side frameworks like Asp.Net WebForms and Asp.Net MVC. To bridge this gap, Angular offers a feature known as Angular Universal, which facilitates server-side rendering (SSR) of Angular applications.

## Introduction

Angular Universal allows for server-side rendering of Angular applications. It is a technique that involves rendering Angular components on the server and sending the pre-rendered HTML to the client. Once on the client-side, JavaScript takes over to enhance interactivity. This approach brings several advantages, including improved SEO, faster loading times, and enhanced accessibility.

## What is Angular Universal?

Angular Universal is a technology that enables you to run Angular applications on the server side. This means that the application's code is executed on the server, and the resulting HTML is sent to the client's browser. Subsequently, JavaScript takes over to add interactivity to the application.

For more information, refer to the [Angular Universal](https://github.com/angular/universal) repository.

## Syncfusion Angular UI Components in Angular Universal

Syncfusion Angular UI Components also supports the Angular Universal. For a sample project that includes the Syncfusion Angular components, refer to the [syncfusion-angular-universal](https://github.com/SyncfusionExamples/syncfusion-angular-universal) GitHub repository.

To use Syncfusion Angular UI components in an Angular Universal application, follow these steps:

* Download or clone the starter project from the syncfusion-angular-universal repository
* Run `npm install` command to install all required dependencies.
* Follow the [Getting Started](https://ej2.syncfusion.com/angular/documentation/getting-started/angular-cli) to add required component and its code changes.
* Run `npm run build:ssr` && `npm run serve:ssr` command to build and serve the application in both prerender and rerender(ssr) mode of the universal.

## See also

* [Angular Universal](https://github.com/angular/universal)
* [Getting Started ASP .NET Core with Angular](../getting-started/aspnet-core.md)
* [Getting Started ASP .NET MVC with Angular](../getting-started/aspnet-mvc.md)