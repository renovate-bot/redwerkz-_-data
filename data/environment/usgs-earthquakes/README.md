USGS Ergbeben / USGS Earthquakes
================================

Erdbebenaufzeichnungen vom USGS. Die GeoJSON-Datei earthquakes.geojson enthält
alle Einträge, die die Suchfunktion des USGS für den Zeitraum 1980 bis heute 
für das Gebiet von 5 bis 8 grad östliche Länge und 50 bis 52 Grad nördliche Breite
ausgibt.

Quelle: http://earthquake.usgs.gov/earthquakes/search/

## Tools

### Download script `download.sh`

Downloads all earthquakes since 1980 and generates the GeoJSON file `earthquakes.geojson`.
No parameters required. Simply call it like this:

   sh download.sh
