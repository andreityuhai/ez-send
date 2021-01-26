# ez-send
Landing Page

# .NET Core Tutorials
- [ASP.NET Core Crash Course - C# App in One Hour](https://www.youtube.com/watch?v=BfEjDD8mWYg)
- [Entity Framework Core 5.0](https://www.youtube.com/watch?v=7jcLliJvMcY)
- [ASP.NET Core Identity tutorial from scratch](https://www.youtube.com/watch?v=egITMrwMOPU)
- [ASP.NET Core tutorial for beginners](https://www.youtube.com/playlist?list=PL6n9fhu94yhVkdrusLaQsfERmL_Jh4XmU)

# .NET Core 5 Basics
Create a new project from the template *ASP.NET Core Web Application*

Install the following libraries by running the following command in *Package Manager Console*:
```
Install-Package Microsoft.EntityFrameworkCore
Install-Package Microsoft.EntityFrameworkCore.Tools
Install-Package Pomelo.EntityFrameworkCore.MySql -Version 5.0.0-alpha.2
Install-Package Microsoft.AspNetCore.Identity.EntityFrameworkCore
```

Add a database connection string into *appsettings.json* file, for example:
```json
{
  "ConnectionStrings": {
    "DefaultConnection": "server=localhost; port=3306; database=dotnet_core; user=root; password=root; Persist Security Info=False; Connect Timeout=300"
  }
}
```
