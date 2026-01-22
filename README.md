title: ".NET Developer Portfolio"

description: >
  Portfolio profesional desarrollado con .NET, diseñado con una arquitectura
  limpia, modular y escalable. El proyecto demuestra conocimientos reales en
  desarrollo backend y frontend, buenas prácticas de arquitectura, reutilización
  de código y organización de soluciones complejas.

architecture:
  overview: >
    La solución sigue una arquitectura desacoplada basada en una API central,
    varias aplicaciones Blazor independientes y proyectos compartidos
    reutilizables.
  structure:
    - name: DotNetPortfolio.Api
      description: API REST desarrollada con ASP.NET Core
    - name: DotNetPortfolio.Shared
      description: Modelos, DTOs, contratos e interfaces compartidas
    - name: DotNetPortfolio.Components
      description: Razor Class Library con componentes UI reutilizables
    - name: DotNetPortfolio.Web.Home
      description: Aplicación Blazor WebAssembly para la presentación principal
    - name: DotNetPortfolio.Web.Business
      description: Aplicación Blazor WebAssembly para gestión empresarial
    - name: DotNetPortfolio.Web.Maps
      description: Aplicación Blazor WebAssembly para gestión y visualización de mapas

principles:
  - Separación clara de responsabilidades
  - Reutilización de código mediante proyectos compartidos
  - API única consumida por múltiples aplicaciones
  - Escalabilidad para añadir nuevas aplicaciones sin afectar a las existentes

technologies:
  - ".NET 9"
  - "ASP.NET Core Web API"
  - "Blazor WebAssembly"
  - "Razor Class Library (RCL)"
  - "HTTP / JSON"
  - "Git"

execution:
  requirements:
    - Visual Studio 2022
    - .NET SDK 9
  steps:
    - Clonar el repositorio desde GitHub
    - Abrir la solución en Visual Studio 2022
    - Restaurar paquetes NuGet
    - Establecer como proyecto de inicio la API y una app Blazor
    - Ejecutar la solución

features:
  - API REST centralizada
  - Aplicaciones Blazor independientes
  - Modelos y contratos compartidos
  - Componentes UI reutilizables
  - Navegación SPA fluida
  - Arquitectura preparada para crecimiento

status: "En desarrollo activo"

author:
  name: Mohamed Ahdadouche
  role: Desarrollador .NET
  github: https://github.com/ahdadouche-dev

license: MIT
