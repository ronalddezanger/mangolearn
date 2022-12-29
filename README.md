# Udemy Course

## Learn Microservices architecture with .NET Core MVC(.NET 6) and Identity Server Integration with Azure Service Bus

https://www.udemy.com/course/net-core-microservices-the-complete-guide-net-6-mvc/


## Getting Started 

```Batchfile
dotnet new sln -n MangoRestaurant
mkdir FrontEnd
cd FrontEnd
dotnet new mvc -n Mango.Web -f net7.0
cd Mango.Web
dotnet run
cd ..
cd ..
mkdir Services
cd Services
dotnet new webapi -n Mango.Services.ProductAPI -f net7.0
cd Mango.Services.ProductAPI
dotnet run
```

disable nullable in the project files

## Adding Nu-Get packages

```Batchfile
dotnet add package AutoMapper
dotnet add package AutoMapper.Extensions.Microsoft.DependencyInjection
dotnet add package Swashbuckle.AspNetCore.SwaggerUI
dotnet add package Swashbuckle.AspNetCore.Annotations
dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer
dotnet add package Microsoft.AspNetCore.Mvc.Formatters.Json
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools
```

## Start SQL Server in docker (change ww)
```Batchfile
docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=mssql@Test01" -p 1433:1433 -d mcr.microsoft.com/mssql/server:2022-latest
```
