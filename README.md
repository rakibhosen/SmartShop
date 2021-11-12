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
1. Download the repository.
2. Open the `SmartShop.DataApi` project in the command prompt & write the below command.
3. Add  migration for SmartShopDbContext - `dotnet ef migrations add "SS_v0" --project ..\SmartShop.DataLib\SmartShop.DataLib.csproj --startup-project .\SmartShop.DataApi.csproj -c SmartShopDbContext`
4. Update migration for SmartShopDbContext - `dotnet ef database update "SS_v0" --project ..\SmartShop.DataLib\SmartShop.DataLib.csproj --startup-project .\SmartShop.DataApi.csproj -c SmartShopDbContext`
5. Update migration for AppDbContext - `dotnet ef database update -c AppDbContext `
6. Open `SmartShop.Web` project in the command prompt and run the server on 5001 port - `dotnet run --urls=http://localhost:5001`
6. Open the `SmartShop.DataApi` project in the command prompt and run - `dotnet run`
7. Open the `SmartShop.Web\ClientApp`  in the command prompt and run - `npm install` & then `ng serve -o`

### Some picture
#### Client
![screencapture-localhost-5001-2021-11-12-21_25_58](https://user-images.githubusercontent.com/18288587/141492536-17b0263a-873b-41e8-b2ed-1b8b2a4d4124.png)
![screencapture-localhost-5001-Product-ProductDetails-1-2021-11-12-21_28_22](https://user-images.githubusercontent.com/18288587/141507410-d1042d31-c6e0-4613-9b79-ccb30d2ff96d.png)
![screencapture-localhost-5001-Cart-2021-11-12-20_52_15](https://user-images.githubusercontent.com/18288587/141507528-103ebcf4-2475-4637-9079-71c367c9ae11.png)

![screencapture-localhost-5001-Checkout-2021-11-12-21_29_17](https://user-images.githubusercontent.com/18288587/141507573-d7b67581-849d-44dc-94a4-76ed733d510a.png)
![screencapture-localhost-5001-User-2021-11-12-21_31_35](https://user-images.githubusercontent.com/18288587/141507603-caad1d99-8c20-4026-8b0b-70a089b9ff33.png)

![screencapture-localhost-5001-User-2021-11-12-21_31_55](https://user-images.githubusercontent.com/18288587/141507624-ffa4a5fc-df13-47eb-8176-0e89b1f2bf06.png)

#### Admin

![WhatsApp Image 2021-11-05 at 7 33 28 PM (1)](https://user-images.githubusercontent.com/18288587/140632944-915ced62-0684-45ed-bdf9-272bc19558f4.jpeg)
![WhatsApp Image 2021-11-05 at 7 33 28 PM (2)](https://user-images.githubusercontent.com/18288587/140632952-4dde4a95-c1ca-4781-b2bd-7684141d2bb0.jpeg)
![WhatsApp Image 2021-11-06 at 12 09 48 PM](https://user-images.githubusercontent.com/18288587/140632956-a04dbfaa-5ffa-4357-8c9d-41e732fcd741.jpeg)


