# Overview
Editions serve to make literary works accessible and to provide commentary or additional context regarding their creation, content, and reception. In many cases, the number of editions can be seen as an indicator of canonicity.

## Reclams Universal-Bibliothek

The *Universal-Bibliothek* (UB) by Reclam is a long-standing series of editions of (primarily) literary works. It is widely used in school and university teaching.

We compiled a list of all titles published as part of the UB according to the online catalogue of the Deutsche Nationalbibliothek (DNB) by using this search: https://portal.dnb.de/opac/simpleSearch?query=partOf%3D010784632&cqlMode=true&sortOrderIndex=jhr_asc.

Data collection from the DNB took place in December 2024.

Each row in the file `reclam.csv` represents one title from the UB series. The file contains the following columns:

- *DNB_dataset*: DNB identifier for the respective *Universal-Bibliothek* title  
- *title*: Title of the work  
- *UB*: Serial number within the *Universal-Bibliothek* series  
- *GND_person*: GND identifier(s) for individuals listed by the DNB as "Person" associated with the publication  
- *person*: Name(s) of the individuals listed as "Person" by the DNB  
- *GND_author*: GND identifier(s) for individuals listed by the DNB  as "Autor" (author) of the work  
- *author*: Name(s) of the individuals listed as "Autor" (author) by the DNB  
- *sachgruppen*: Subject group(s) assigned to the publication by the DNB
