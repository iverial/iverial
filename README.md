<h1 align="left">Hi 👋, I'm Ivan Caggiano</h1>
<h3 align="left">.NET Backend Developer</h3>

<h3 align="left">
I’m a .NET Backend Developer based in Buenos Aires, Argentina, with over 2 years of professional experience building scalable and high-performance backend systems.

Currently working at Grupo Penna, I design and maintain RESTful APIs, optimize SQL Server databases, and contribute to process automation and digital transformation initiatives across multiple business units.

My focus is on Clean Architecture, microservices, and building maintainable, production-ready backend solutions using ASP.NET Core and C#.

I’m passionate about writing clean code, designing scalable systems, and continuously improving both technical and business processes.
</h3>

<br>

```csharp
public class AboutMe
{
    public string Name => "Ivan Caggiano";
    public string Role => ".NET Backend Developer";
    public string Location => "Buenos Aires, Argentina";

    public string[] Languages => { "C#", "TypeScript" };

    public object Backend => new
    {
        Frameworks = new[] { "ASP.NET Core", "Entity Framework Core" },
        Architecture = new[] { "Clean Architecture", "Microservices", "REST APIs", "SOLID Principles" }
    };

    public object Database => new
    {
        Engine = "SQL Server",
        Skills = new[] { "Schema Design", "Stored Procedures", "T-SQL", "Query Optimization" }
    };

    public object DevOps => new
    {
        Cloud = new[] { "AWS (EC2, S3)" },
        Containers = new[] { "Docker" },
        CI_CD = new[] { "GitHub Actions" },
        WebServer = "Nginx"
    };

    public string CurrentPosition => "Backend Developer at Grupo Penna";
}
