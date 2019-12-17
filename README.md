# countries-js
A simple package with a list of countries and details about call and currecies of each country.

# Installation
```
npm i @amirsanni/countries
```

# How to use
```
const countries = require('countries');

countries.all();//returns an array of all countries and their details
countries.list();//returns an array of all country names
countries.get('Jamaica');//returns an object with details about the specified country
countries.currencies();//returns the ISO code of all currencies
```