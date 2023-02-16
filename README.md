dotnet new globaljson --sdk-version 6.0 --force

dotnet new webapi -minimal -n AsyncProductAPI 

dotnet add package Microsoft.EntityFrameworkCore

dotnet ef migrations add initialmigration

dotnet ef database update
