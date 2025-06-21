# Subject Bibliographies
<!-- Template for Documentation -->

## Description
Subject bibliographies compile scholarly literature on a given topic, usually within a specific time frame. They reveal which texts, authors, and other objects have been studied and how frequently.

## bdsl
The *Bibliographie der deutschen Sprach- und Literaturwissenschaft* (BDSL) is one of the most important subject bibliographies in German Studies. Its online version (https://www.bdsl-online.de/) provides comprehensive documentation of relevant scholarship since 1985, including approximately 545,000 titles from the period 1985 to 2004 alone. The bibliography offers various search options, including "Freitext", which retrieves titles containing the search phrase anywhere in the metadata, and "Behandelte Person", which returns titles that have been explicitly tagged as engaging with the searched person.

The file "bdsl.csv" contains the following columns:

- *GND*: GND identifier for the respective author.
- *hits_person_since1985*: number of titles returned by the BDSL when searching for the author's name (as listed in the GND) using the "Behandelte Person" search option, displaying all results from 1985 onward.
- *hits_all_since1985*: number of titles returned by the BDSL when searching for the author's name (as listed in the GND) using the "Freitext" search option, displaying all results from 1985 onward.
- *hits_person_since2000*: number of titles returned by the BDSL when searching for the author's name (as listed in the GND) using the "Behandelte Person" search option, displaying all results from 2000 onward.
- *hits_all_since2000*: number of titles returned by the BDSL when searching for the author's name (as listed in the GND) using the "Freitext" search option, displaying all results from 2000 onward.
