# Determinants of Moscow Public Catering Establishments Consumer Evaluations

Here we publish files for analysis of Determinants of Moscow Public Catering Establishments' Consumer Evaluations. It includes the analysis of reviews, geoanalysis, and building of the model.
The reviews were get from publicly available the largest Russian-language dataset of reviews of organizations published on Yandex Maps  (dataset was published by Yandex in https://github.com/yandex/geo-reviews-dataset-2023).

We analyzed reviews only of public catering establishments and only in the old borders of Moscow city. We also collected data from the TripAdvisor and municipal data from Rosstat.

The analysis of reviews is in the file _Review_Analysis.ipynb_. The main topics, sentiments, sentiments of topics were identified.

The geo analysis is in the file _Geo_part.ipynb_. The data about amenities and other characteristics of cities were downloaded from OSM. The Moscow were divided into hexagons, the competitiveness and nearby facilities were calculated based on the neighbored hexagons.

The creation of models is in the file _Models.ipynb_. 

**_Made by Saveleva Maria, Novozhilova Varvara, Kempi Elena._**
