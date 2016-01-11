# Faker
Faker is a C# library used to easily generate fake data for: names, address, and many more!

It is available via [NuGet Package](https://www.nuget.org/packages/Faker.Data/)


|CI Build | NuGet Package Deployment| NuGet |
| :------: | :----: | :---: | :----: | :-----: |
| ![CI Build Status](https://ferm.visualstudio.com/DefaultCollection/_apis/public/build/definitions/c55f9b7a-25b6-4f2e-8b7e-b1c8345d9344/10/badge) | ![Package Build Status](https://ferm.visualstudio.com/DefaultCollection/_apis/public/build/definitions/c55f9b7a-25b6-4f2e-8b7e-b1c8345d9344/11/badge) | [![NuGet Status](https://img.shields.io/nuget/v/Faker.Data.svg)](https://www.nuget.org/packages/Faker.Data/)

Install the NuGet package via the Package Manager or
```
PM> Install-Package Faker.Data
```
## Usage

#### Addresses
```
var state = Faker.Address.State();
var stateAbbr = Faker.Address.StateAbbreviation();
var provinceAbbr = Faker.Address.ProvinceAbbreviation();
var province = Faker.Address.Province();
var streetName = Faker.Address.StreetName();
var country = Faker.Address.Country();
var cityPrefix = Faker.Address.CityPrefix();
var citySuffix = Faker.Address.CitySuffix();
var secondaryAddress = Faker.Address.SecondaryAddress();
var usCity = Faker.Address.USCity();
var usCounty = Faker.Address.USCounty();
var canadianZip = Faker.Address.CanadianZip();
var usZip = Faker.Address.USZip();
```
#### Geo Location
```
var lat = Faker.GeoLocation.Latitude();
var lon = Faker.GeoLocation.Longitude();
```


