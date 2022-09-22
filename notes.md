# Learning dotnet with practicals - DOJ - Daddy Omar Jeng

# .gitignore file sample

- Sample can be found from [here](https://stackoverflow.com/questions/39289765/whats-the-common-practice-of-gitignore-for-aspnet-core-project) or [here](https://raw.githubusercontent.com/OmniSharp/generator-aspnet/master/templates/gitignore.txt)

# ASP.NET Core Web UI

- Asp.net is a complete UI framework.
- There are three different ways of building modern web Uis using ASP.NET Core:
  - Apps tha render UI from the server
  - Apps that render UI from the client(Web Browser)
  - Hybrid apps that take advantage of both client and server UI rendering approaches. Example: Most of the UI is rendered from the server, and the client rendered components are added as needed.

## Server Rendered UI

- A Web App UI that dynamically generates web pages(HTML, CSS) on the server and renders them on the client-side(Browser) based on the request sent from the client to the server.

## Client Rendered UI

- A client rendered app dynamically renderes web UI on the client, directly updating the DOM as necessary.

## Hybrid Rendered UI

- Makes use of both client and server UI rendering approaches.

### Choosing a Server Rendered ASP.NET Core UI Solution

- We can use the **ASP.NET Core Razor Pages** and **ASP.NET Core MVC** to render pages from the server.

### Choosing a Client Rendered ASP.NET Core UI Solution

- We can use the **Blazor** which is composed of **Razor Components**=> _segments of reusable web UI implemented using C#, HTML, and CSS._
- Both client and server code are written in C#, allowing shared code and libraries.
- Razor pages can be rendered or prerendered from _view_ and _pages_

#### ASP.NET Core SPA using Javascript Frameworks(React, etc)

- You can build client-side apps with ASP.NET Core using Javascript Frameworks like _React, Angular, etc_,.
- ASP.NET Core provides project templates for the frameworks that you can use when writing code.

### Choosing a Hybrid Rendered ASP.NET Core UI Solution(ASP.NET Core MVC or Razor Pages plus Blazor)

- You can use either ASP.NET Core MVC or Razor Pages with Blazor to create a hybrid rendering solution for your application.

# Razor Pages in ASP.NET Core

- Create a new project: **dotnet new webapp -o RazorPageContacts**
