# irma-scraped-data

Data scraped by https://github.com/simonw/irma-scrapers

The most interesting output of this repo is its commit history, which
shows when the various scraping sources have been updated and what
changed: https://github.com/simonw/irma-scraped-data/commits/master

Some of these changes are published to the Irma response Slack, in
the #shelter_scraper_data channel. https://irma-response-slack.herokuapp.com/

## florida-shelters.json (published to Slack)

Data scraped from the table on http://www.floridadisaster.org/shelters/summary.aspx

## fema-open-shelters.json (published to Slack)

Data from https://gis.fema.gov/REST/services/NSS/OpenShelters/MapServer/0/query?f=json&returnGeometry=true&spatialRel=esriSpatialRelIntersects&geometry=%7B%22xmin%22%3A-10018754.171396945%2C%22ymin%22%3A2504688.5428529754%2C%22xmax%22%3A-7514065.628548954%2C%22ymax%22%3A5009377.085700965%2C%22spatialReference%22%3A%7B%22wkid%22%3A102100%7D%7D&geometryType=esriGeometryEnvelope&inSR=102100&outFields=*&outSR=102100

Documentation here: https://gis.fema.gov/REST/services/NSS/OpenShelters/MapServer

## fema-nss.json (published to Slack)

Data from https://gis.fema.gov/REST/services/NSS/FEMA_NSS/MapServer/0/query?f=json&returnGeometry=true&spatialRel=esriSpatialRelIntersects&geometry=%7B%22xmin%22%3A-10018754.171396945%2C%22ymin%22%3A2504688.5428529754%2C%22xmax%22%3A-7514065.628548954%2C%22ymax%22%3A5009377.085700965%2C%22spatialReference%22%3A%7B%22wkid%22%3A102100%7D%7D&geometryType=esriGeometryEnvelope&inSR=102100&outFields=*&outSR=102100

## zeemaps-2682928.json (not published to Slack)

Data pulled from https://zeemaps.com/map?group=2682928

## irma-shelters.json (not published to Slack)

Data from https://irma-api.herokuapp.com/api/v1/shelters
