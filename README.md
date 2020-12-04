![Code Count](https://img.shields.io/github/languages/count/bdcoelho/WeatherRAML)
![Main Code Base](https://img.shields.io/github/languages/top/bdcoelho/WeatherRAML)
![Last Commit](https://img.shields.io/github/last-commit/bdcoelho/WeatherRAML)
![Open Issues](https://img.shields.io/github/issues-raw/bdcoelho/WeatherRAML)
![Repo Size](https://img.shields.io/github/repo-size/bdcoelho/WeatherRAML)

# Weather API integration application

## Table of Contents

- [Usage](#Usage)
- [Setup](#Setup)
- [Application](#Application)

## Usage
Clone the repository to your local machine.

## Setup

The mock weather service requires some setup before it can be used. The user can set it up using an IDE such as Visual Studio Code. Once downloaded, navigate to the folder ./WeatherRAML/weatherExcerciseDockerFile/weatherExcerciseDockerFile in the integrated terminal and run npm install. This will install the required packages. Next run npm start to run the mock weather service.

### Application

• If you do not have Mule installed, you can download it with the Anypoint IDE from https://www.mulesoft.com

• You will require to have JDK 8 installed on your machine to use Mule runtime

• Open the application in Anypoint Studio and run the application from the Run menu

• Once deployed, the service will now be live for access through a browser or Postman

• You can make request to the GetWeather service using the URL
http://0.0.0.0:8081/get-weather?CityName=Melbourne&CountryName=Australia

• Replace Melbourne and Australia with a desired city and country for other locations when using the live weather service. However, Melbourne is the only location available in the mock weather service

• You can make request to the GetCitiesByCountry service using the URL
http://0.0.0.0:8081/GetCitiesByCountry?CountryName=Australia

• The mock service only has data for Australia while using the above mentioned method.
