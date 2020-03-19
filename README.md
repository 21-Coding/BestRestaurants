# _Best Restaurants_

#### _MySql, Entity, C# practice lesson_

#### By _Matt, Jose, Dom_

## Description

_Application project to create, organize, and display a database. Tracks Cuisine and Restaurant tables._

## Behavior Driven Development
| Behavior | Input | Output |
|----|----|-----|
|  |  |  |


## Setup/Installation Requirements

* Open Terminal
* Type ``$ git clone https://github.com/.{url path}``
* Navigate into the directory 
* Type ``mysql`` and create the database below
* Type ``$ dotnet run``
* Open your browser and enter the address ``localhost:5000``


## SQL

CREATE DATABASE `best_restaurants`;

USE `best_restaurants`;

CREATE TABLE `cuisines` (  
  `CuisineId` int(11) NOT NULL AUTO_INCREMENT,  
  `CuisineName` varchar(255) DEFAULT NULL,  
  PRIMARY KEY (`CuisineId`)  
)

CREATE TABLE `restaurants` (  
  `RestaurantId` int(11) NOT NULL AUTO_INCREMENT,  
  `Name` varchar(255) DEFAULT NULL,  
  `Location` varchar(255) DEFAULT NULL,  
  `Rating` int(11) DEFAULT NULL,  
  `Review` varchar(255) DEFAULT NULL,  
  `CuisineId` int(11) DEFAULT '0',  
  PRIMARY KEY (`RestaurantId`)  
)

## Technologies Used

* Git
* C#
* .NET Core
* ASP.NET Razor
* MySQL
* Entity Framework Core

### License

*Licensed under the MIT License*

Copyright (c) 2020