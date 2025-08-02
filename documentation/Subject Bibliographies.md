# Subject Bibliographies
<!-- Template for Documentation -->

## Description
Subject bibliographies compile scholarly literature on a given topic, usually within a specific time frame. They reveal which texts, authors, and other objects have been studied and how frequently.

## bdsl
The *Bibliographie der deutschen Sprach- und Literaturwissenschaft* (BDSL) is one of the most important subject bibliographies in German Studies. Its online version (https://www.bdsl-online.de/) provides comprehensive documentation of relevant scholarship since 1985, including approximately 545,000 titles from the period 1985 to 2004 alone.

As far as we can see, there is no direct way to access the bibliographic entries using the GND identifier itself, which is why we resorted to searching for the author’s name as listed in the GND.

In some cases, the number of hits is greatly inflated because the author is listed in the GND under a one-word name, such as “Heinrich” or “Albrecht,” or under a name with abbreviations like “O.F. Berg” or “E. Y. Meyer.” This usually results in a large number of irrelevant hits — that is, titles mentioning not the searched author, but other people whose names also happen to include “Heinrich,” “Albrecht,” and so on.

The BDSL offers various search options, including "Freitext", which retrieves titles containing the search phrase anywhere in the metadata, and "Behandelte Person", which returns titles that have been explicitly tagged as engaging with the searched person. In many cases, however, the “Behandelte Person” option fails to return all relevant hits, especially when searching for lesser-known authors, which is why we opted for the “Freitext” option instead.

Data collection from the BDSL took place in August 2025.

The file "bdsl.csv" contains the following columns:

- *GND*: GND identifier for the respective author.
- *searchphrase*: string used to search the BDSL — in this case, the author’s name as listed in the GND.
- *BDSL_hits_2000_all*: number of titles returned by the BDSL when searching for the searchphrase using the "Freitext" search option, displaying all results from 2000 onward.
