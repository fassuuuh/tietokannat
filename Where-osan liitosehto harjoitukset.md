# Where-osan liitosehto harjoitukset

### Tehtävä 1
select country.name as "country name", airport.name as "airport name"
from airport, country 
where airport.iso_country = country.iso_country and country.name = 'Iceland';

![kuva](./ruudunkappaukset/teht.2.1.png)

### Tehtävä 2
select airport.name as "airport name" 
from airport, country
where airport.iso_country = country.iso_country 
and country.name = "France" and type = "large_airport";

![kuva](./ruudunkappaukset/teht.2.2.png)

### Tehtävä 3
select country.name as "country_name", airport.name as "airport_name" 
from airport, country 
where airport.iso_country = country.iso_country 
and country.continent = "AN";

![kuva](./ruudunkappaukset/teht.2.3.png)
