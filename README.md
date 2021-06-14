# SpaceCovid
* DataExploration.ipynb : Exploration des images satelite de nuit, plus corrélation avec cas covid
* LightMeanCalculator.ipynb : Calcul de l'intensité moyenne de la lumière de 2014 à 2020 pour les villes les principales villes européen
* LightHyphotesis.ipynb : Graphique fill and between, calcul cranking ville et pays, clustering, definition d'un modèle pour donne un score en fonction de l'intensité lumineuse à une zone géographique, correlation entre intensité de la lumière et différentes varibales covid (fermeture lieu de travail, annulation evenement public, ...)
* DistrictPrediction.ipynb : Utilisation du modèle préccedement défini pour effectuer des prédictions des restriction covid sur différents pays d'europe.
* Data/ 
    * covid.json : Nombre de cas et mort du covid par pays dans le monde, source : https://github.com/owid/covid-19-data/tree/master/public/data
    * population.csv : Population pays européens, source : https://en.wikipedia.org/wiki/List_of_European_countries_by_population
    * covid-stringency-index.csv : Index de rigueur des restrictions Covid par pays, source : https://ourworldindata.org/covid-stringency-index
    * public-events-covid.csv : Index de restriction des evenements publique liés au covid, source : https://ourworldindata.org/covid-cancel-public-events
    * public-gathering-rules-covid.csv : Index des restrictions des rassemblements lié au covid, source : https://ourworldindata.org/covid-cancel-public-events
    * school-closures-covid.csv : Index de fermeture des écoles, source : https://ourworldindata.org/covid-school-workplace-closures
    * workplace-closures-covid.csv : Index de fermeture des lieu de travails, source : https://ourworldindata.org/covid-school-workplace-closures
    * stay-at-home-covid.csv : Index de réstriction des sorties lié au covid, source : https://ourworldindata.org/covid-stay-home-restrictions
    * swiss_district_light.csv : Prédiction du ranking via l'intensité lumineuse sur la carte de la Suisse
    * france_district_light.csv : Prédiction du ranking via l'intensité lumineuse sur la carte de la France
    * italy_district_light.csv : Prédiction du ranking via l'intensité lumineuse sur la carte de la Italy
    * swiss_district.geojson : Commune de suisse au format geojson, source : https://www.bfs.admin.ch/bfs/en/home/statistics/regional-statistics/base-maps/cartographic-bases.html
    * FRA_adm : dossier avec les différents fichiers permettant de dessiner la carte de la France, source : http://www.diva-gis.org/gdata
    * ITA_adm : dossier avec les différents fichiers permettant de dessiner la carte de la Italy, source : http://www.diva-gis.org/gdata
    * european_cities.csv : Coordonnées GPS des différentes villes européennes, source : https://simplemaps.com/resources/free-country-cities
    * european_cities_light.csv : Récupération de la moyenne de l'intensité lumineuse  pour les différentes villes d'Europe de 2014 à 2020


