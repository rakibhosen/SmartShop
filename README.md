# SmartShop
A ecommerce site  Made with Asp .Net Core , Asp .NET Web API & Angular


## Installation guide
1. Download the repositories.
2. Open the `SmartShop.DataApi` project in the command prompt & write the below command.
3. Add  migration for SmartShopDbContext - `dotnet ef migrations add "SS_v0" --project ..\SmartShop.DataLib\SmartShop.DataLib.csproj --startup-project .\SmartShop.DataApi.csproj -c SmartShopDbContext`
4. Update migration for SmartShopDbContext - `dotnet ef database update "SS_v0" --project ..\SmartShop.DataLib\SmartShop.DataLib.csproj --startup-project .\SmartShop.DataApi.csproj -c SmartShopDbContext`
5. Update migration for AppDbContext - `dotnet ef database update -c AppDbContext `
6. Open `SmartShop.Web` project in the command prompt and run the server on 5001 port - `dotnet run --urls=http://localhost:5001`
6. Open the `SmartShop.DataApi` project in the command prompt and run - `dotnet run`
7. Open the `SmartShop.Web\ClientApp`  in the command prompt and run - `npm install` & then `ng serve -o`
