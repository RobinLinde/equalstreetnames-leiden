# EqualStreetNames-Assen

This repo contains the submodule containing the data for Leiden in the EqualStreetNames project. For more information about the project, visit the [main repo](https://github.com/EqualStreetNames/equalstreetnames).

## Data updates

The data is updated every thursday by Github Actions:
[![Update data](https://github.com/EqualStreetNames/equalstreetnames-leiden/actions/workflows/update-data.yml/badge.svg)](https://github.com/EqualStreetNames/equalstreetnames-leiden/actions/workflows/update-data.yml)

Afterwards the new version of the site is pushed to the `gh-pages` branch:
[![Deploy](https://github.com/EqualStreetNames/equalstreetnames-leiden/actions/workflows/deploy.yml/badge.svg)](https://github.com/EqualStreetNames/equalstreetnames-leiden/actions/workflows/deploy.yml)

## Contributing

If you notice any errors specifically in the submodule, feel free to open an issue, or submit a pull request.

If you want to add to the data itself, you can map it on [OpenStreetMap (OSM)](https://osm.org/). You can use the tag `name:etymology:wikidata` for adding the information to a street using a [Wikidata](https://wikidata.org) entity.



## Underlying data
At the start of the project only 4 streets in Leiden had been mapped to wikidata!
![](sad_state_2021-05-02.png)

The data is mostly mapped, but not in OSM, the Dutch wikipedia page [Lijst_van_straten_in_Leiden](https://nl.wikipedia.org/wiki/Lijst_van_straten_in_Leiden) has
has loads of etymology, but it is not yet added to OSM.

If you want to add to this project, you can map it on OpenStreetMap.
You can use the tag name:etymology:wikidata for adding the information to a street using a Wikidata entity.

I've added a few etymology notes to Stevenshof ![](added_streets.png) like here. 
