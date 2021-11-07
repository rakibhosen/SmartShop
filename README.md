# SmartShop
A Ecommerce site  Made with ASP .NET Core , ASP .NET Web API & Angular

### Technologies at glance
#### Frontend Technologies
- JavaScript
- Angular
- TypeScript
- SignalR

#### Backend / API Technologies
- ASP .NET Core Web API
- ASP .NET Core
- EntityFrameworkCore
- SignalR


## Requirement
1. node js
2. Visual Studio Code 2019
3. `dotnet ef global tool` if you don't have, using this command to install `dotnet tool install --global dotnet-ef`

## Installation guide
1. Download the repositories.
2. Open the `SmartShop.DataApi` project in the command prompt & write the below command.
3. Add  migration for SmartShopDbContext - `dotnet ef migrations add "SS_v0" --project ..\SmartShop.DataLib\SmartShop.DataLib.csproj --startup-project .\SmartShop.DataApi.csproj -c SmartShopDbContext`
4. Update migration for SmartShopDbContext - `dotnet ef database update "SS_v0" --project ..\SmartShop.DataLib\SmartShop.DataLib.csproj --startup-project .\SmartShop.DataApi.csproj -c SmartShopDbContext`
5. Update migration for AppDbContext - `dotnet ef database update -c AppDbContext `
6. Open `SmartShop.Web` project in the command prompt and run the server on 5001 port - `dotnet run --urls=http://localhost:5001`
6. Open the `SmartShop.DataApi` project in the command prompt and run - `dotnet run`
7. Open the `SmartShop.Web\ClientApp`  in the command prompt and run - `npm install` & then `ng serve -o`

### Some picture
#### Client
![WhatsApp Image 2021-11-05 at 7 33 28 PM](https://user-images.githubusercontent.com/18288587/140632840-89bc186a-973a-4753-b74e-6c29d25bd9f2.jpeg)
![WhatsApp Image 2021-11-06 at 12 16 58 PM](https://user-images.githubusercontent.com/18288587/140632912-fab4e04e-b5d8-422e-8429-73b18cda828a.jpeg)
![WhatsApp Image 2021-11-05 at 7 33 28 PM (4)](https://user-images.githubusercontent.com/18288587/140632919-bd7a1998-ce22-43c5-bf7a-062ce8265b98.jpeg)
![WhatsApp Image 2021-11-06 at 12 16 59 PM](https://user-images.githubusercontent.com/18288587/140632926-c7eec859-a67d-4ed0-b8dc-f764717be5d7.jpeg)

#### Admin

![WhatsApp Image 2021-11-05 at 7 33 28 PM (1)](https://user-images.githubusercontent.com/18288587/140632944-915ced62-0684-45ed-bdf9-272bc19558f4.jpeg)
![WhatsApp Image 2021-11-05 at 7 33 28 PM (2)](https://user-images.githubusercontent.com/18288587/140632952-4dde4a95-c1ca-4781-b2bd-7684141d2bb0.jpeg)
![WhatsApp Image 2021-11-06 at 12 09 48 PM](https://user-images.githubusercontent.com/18288587/140632956-a04dbfaa-5ffa-4357-8c9d-41e732fcd741.jpeg)


