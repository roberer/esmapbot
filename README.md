# Mapbot de España 

[![Project Status: Concept – Minimal or no implementation has been done
yet, or the repository is only intended to be a limited example, demo,
or
proof-of-concept.](https://www.repostatus.org/badges/latest/concept.svg)](https://www.repostatus.org/#concept)
[![](https://img.shields.io/badge/Twitter-@esmapbot-white?style=flat&labelColor=blue&logo=Twitter&logoColor=white)](https://twitter.com/esmapbot)

### 🤖🛰️🇪🇦

Código fuente del bot de Twitter [@esmapbot](https://www.twitter.com/esmapbot) que postea imágenes aéreas aleatorias de España junto a sus cordenadas.

Construido originalmente por [@mattdray](https://twitter.com/mattdray), este bot es una adaptación de su [@londonmapbot](https://twitter.com/londonmapbot) hecha por RoberJ ([@progra_mapa](https://www.twitter.com/progra_mapa)). 

## Librerías 

* [{rtweet}](https://docs.ropensci.org/rtweet/)
* [MapBox Static Images API](https://docs.mapbox.com/api/maps/static-images/)
* [GitHub Actions](https://docs.github.com/en/actions) 


## Nuevas características
Modificaciones respecto al código del [repositorio original](https://github.com/matt-dray/londonmapbot):

* Las coordenadas se obtienen a partir de un punto generado aleatoriamente dentro de las fronteras terrestres de España
* Se ha añadido aleatoriedad en el nivel de zoom con el que se realizan las peticiones de imágenes







