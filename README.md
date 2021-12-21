# Automatic COVID map

## An example repo for using GitHub Actions and mapshaper to automatically update a choropleth hosted on a website

Every hour, this repo pulls county-level data from the [NYT COVID data repo](https://github.com/nytimes/covid-19-data), then uses [mapshaper](https://github.com/mbloch/mapshaper/) to update a simple choropleth map that lives at [https://jsoma.github.io/auto-covid-map/](https://jsoma.github.io/auto-covid-map/).