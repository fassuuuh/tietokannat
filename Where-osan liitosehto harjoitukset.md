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

### Tehtävä 4
select elevation_ft
from game, airport
where game.location = airport.ident
and screen_name = "Heini";

![kuva](./ruudunkappaukset/teht.2.4.png)

### Tehtävä 5
select (elevation_ft * 0.3048) as "elevation_m"
from game, airport
where game.location = airport.ident
and screen_name = "Heini";

![kuva](./ruudunkappaukset/teht.2.5.png)

### Tehtävä 6
select name
from airport, game
where game.location = airport.ident
and game.screen_name = "Ilkka";

![kuva](./ruudunkappaukset/teht.2.6.png)

