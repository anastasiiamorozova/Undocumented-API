# Undocumented-API
Scraping geocooridnates using undocumented API to create geojson for visualization 

This work is part of the analysis for the investigation about land and assets reprivatization in one of the Polish cities:
https://frontstory.pl/szczawnica-andrzej-mankowski-hrabia-amt-rosja-sankcje/

Having a CSV with addresses, the challenge was to receive the shapes of the land plots from a state national georegistry: https://geoportal-krajowy.pl/na-mapie

Since their website doesn't have an open API, I used an undocumented API to scrape the JSON files with the boundaries of the land plots and then turned them into GeoJSON for further visualization: https://public.flourish.studio/visualisation/17691936/
