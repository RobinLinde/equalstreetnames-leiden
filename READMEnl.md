# EqualStreetNames-Leiden
For English see the English (main) [README](README.md).
Deze repository bevat de submodule met de data voor Leiden in het EqualStreetNames project.
Voor meer informatie bezoek de [hoofd-repository (engelstalig) ](https://github.com/EqualStreetNames/equalstreetnames).

## Data updates
De daa wordt elke donderdag door github Actions geupdate:
[![Update data](https://github.com/EqualStreetNames/equalstreetnames-leiden/actions/workflows/update-data.yml/badge.svg)](https://github.com/EqualStreetNames/equalstreetnames-leiden/actions/workflows/update-data.yml)

Daarna wordt een nieuwe versie naar de `gh-pages` branch gepushed:
[![Deploy](https://github.com/EqualStreetNames/equalstreetnames-leiden/actions/workflows/deploy.yml/badge.svg)](https://github.com/EqualStreetNames/equalstreetnames-leiden/actions/workflows/deploy.yml)

## Meedoen
Als je fouten vindt in deze submodule open een issue of pull-request.
Als je aan de data wilt toevoegen (graag!) Dit kan via  [OpenStreetMap (OSM)](https://osm.org/).
Gebruik de tag  `name:etymology:wikidata`  om wikidata entiteiten aan de straten te koppelen.[Wikidata](https://wikidata.org).


### voorbeeld data
Het lijkt erop dat heel veel straten van Leiden in het wikipedia project zijn gekoppeld aan etymologie,
zie  [Lijst_van_straten_in_Leiden](https://nl.wikipedia.org/wiki/Lijst_van_straten_in_Leiden).
Helaas zijn ze niet gekoppeld in Open OpenStreetMap (OSM).

* je hebt een open streetmap account nodig.
* Ga dus zelf naar OpenStreetMap, klik op edit en klik een straat vernoemt naar persoon aan
* vind op [wikidata](https://www.wikidata.org/) de persoon waarnaar deze straat is vernoemt
* kopieer de tag vanuit wikidata (zoiets als `Q4822730`)
* Ga op OpenStreetMap bij de straat die je net hebt aangeklikt naar 'tags'
* voeg een tag toe: `name:etymology:wikidata`  (wanneer je etym typt komt deze tag naar boven )
* en vul bij de waarde van de tag het Qnummer in van de persoon.
* klik op opslaan.
* Nu heb je voor een straat met deze tag aangegeven naar wie deze straat is vernoemt!

Ik heb bijvoorbeeld een heel aantal straten van de Stevenshof ![](added_streets.png) van etymologie voorzien.
Dat brengt het aantal (cis) vrouwen behoorlijk omhoog want er zijn vrijwel alleen maar vrouwennamen daar!
