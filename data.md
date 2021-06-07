## Problem

Find pharmacies in Belém and have some insights for where it would be a good place to start a new business.

## Data

- Belém Neighborhood will be scrapped from wikipedia
  - https://pt.wikipedia.org/wiki/Lista_de_bairros_de_Bel%C3%A9m
- The location of the city will be get from a different page
  - https://pt.wikipedia.org/wiki/Bel%C3%A9m_(Par%C3%A1)
- Neighborhood location will be taken from geocorder python library
- We will search for pharmacies on each neighborhood, using Foursquare, taking care to not duplicate entries
