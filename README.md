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

disable nullable

