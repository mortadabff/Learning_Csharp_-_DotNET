# 1. What is Asp.Net Core?

ASP.NET Core is a free, open-source, and cross-platform framework for building cloud-based applications, such as web apps, IoT apps, and mobile backends. It is designed to run on the cloud as well as on-premises.

ASP.NET Core is not an upgraded version of ASP.NET. ASP.NET Core is completely rewriting that work with the .net Core framework. It is much faster, configurable, modular, scalable, extensible, and has cross-platform support. It is best suitable for developing cloud-based such as web applications, mobile applications, and IoT applications.



# 2. What are the features of Asp.Net Core?

Following are the core features that are provided by the ASP.NET Core

Built-in supports for Dependency Injection

Built-in supports for the logging framework and it can be extensible

Introduced a new, fast and cross-platform web server - Kestrel. So, a web application can run without IIS, Apache, and Nginx.

Multiple hosting platforms are supported

It supports modularity, so the developer needs to include the module required by the application.

Command-line supports to creating, building, and running of the application

There is no web .config file. We can store the custom configuration into an appsettings.json file

It has good support for asynchronous programming



# 3. What are the advantages of ASP.NET Core over ASP.NET (.NET Framework)?

There are the following advantages of ASP.NET Core over ASP.NET:

It offers faster performance due to its minimalistic design

It is cross-platform, so it can be run on Windows, Linux, and Mac.

It is open-source

There is no dependency on framework installation because all the required dependencies are shipped with our application to the production server

Multiple deployment platforms available with ASP.NET Core



# 4. What is Asp.Net Core meta package?

The ASP.NET Core shared framework (Microsoft.AspNetCore.App) contains assemblies that are developed and supported by Microsoft. Microsoft.AspNetCore.App is installed when the .NET Core 3.0 or later SDK is installed. The shared framework is the set of assemblies (.dll files) that are installed on the machine and includes a runtime component and a targeting pack.

<Project Sdk="Microsoft.NET.Sdk.Web">
  <PropertyGroup>
    <TargetFramework>net6.0</TargetFramework>
  </PropertyGroup>
    ...
</Project>


# 5. When do you choose classic ASP.NET MVC over ASP.NET Core?

Though Asp.Net Core is a better choice in almost all the aspects, you don’t have to switch to ASP.NET Core if you are maintaining a legacy ASP.NET application that you are happy with and that is no longer actively developed.



ASP.NET MVC is a better choice if you:

Don’t need cross-platform support for your Web app.

The existing team is already working on an existing app and extending its functionality.

The existing developers needs a learning curve to upgrade themselves to Asp.Net Core



# 6. What is a web application framework, and what are its benefits?

Learning to build a modern web application can be daunting. Most of the web applications have a standard set of functionality such as:



Build a dynamic response that corresponds to an HTTP request.

Allow users to log into the application and manage their data.

Store the data in the database.

Handle database connections and transactions.

Route URLs to appropriate methods.

Supporting sessions, cookies, and user authorization.

Format output (e.g. HTML, JSON, XML)

Improve security.

Frameworks help developers to write, maintain and scale applications. They provide tools and libraries that simplify the above recurring tasks, eliminating a lot of unnecessary complexity.




Course source code on udemy : https://github.com/Harsha-Global/AspNetCore-Harsha
