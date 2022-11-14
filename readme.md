# Blazor
- Flavors to Consider
  - [Blazor Server](#blazor-server)
  - [Blazor WebAssembly](#blazor-webassembly)
    - [Standalone](#blazor-webassembly-standalone) and [ASP.NET hosted](#blazor-webassembly-aspnet-core-hosted)
    - [Progressive web app](#blazor-webassembly-progressive-web-app)
---
# Blazor WebAssembly
  - .NET(C#) on the client
  - Browser loads the dotnet runtime
  - Download size (getting better)
  - Diminished debugging experience
---
# Blazor Server
  - All logic on the server
  - Improved security
  - Server resources for every connected client
  - Requires a good network
---
# Blazor WebAssembly: Standalone
  - Simplest Blazor application model
  - ASP.NET Core server isn't needed
  - Deploy a static folder of files
---
# Blazor WebAssembly: ASP.NET Core Hosted
  - ASP.NET Core serves the Blazor application
  - Client and server can share code
  - Client application packaged and deployed with the server
---
# Blazor WebAssembly: Progressive Web App
  - Progressive web apps can be opened like a native app
  - Loads quickly
  - Offline access
  - Self updating