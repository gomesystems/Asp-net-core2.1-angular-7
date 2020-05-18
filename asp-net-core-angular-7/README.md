# Web App - ASP.NET core 2.1 Web API - Angular 7 - SQL Server
Documentação rascunho
> ASP.NET Core SDK
> Visual Studio Code
> Node.js
> Angular 7
> SQL Server 2017 Express (Base de dados teste 'Northwind' - tem online gratuito)
> Postman
> Command prompt (CMD)

#criar novo app
dotnet new webapi –o AspNetAngular –n AspNetAngular 

#no terminal ou vs code instalar os seguntes pacotes:
dotnet add package Microsoft.EntityFrameworkCore.Tools -v 2.1.2 
dotnet add package Microsoft.EntityFrameworkCore.SqlServer -v 2.1.2 
dotnet add package Microsoft.EntityFrameworkCore.SqlServer.Design -v 1.1.6 
dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design -v 2.1.5 
dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Tools -v 2.0.4 
dotnet add package AutoMapper.Extensions.Microsoft.DependencyInjection -v 5.0.1 

#dotnet build


#repositórios para operações CRUD
#dotnet watch run , localhost: 5000 / api / Supplier pega o json retornado para teste no sweeger
