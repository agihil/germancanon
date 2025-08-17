
# Literary Histories

## Description

## Beutin et al. (2013)

We use the eighth edition: Beutin, Wolfgang et al., ed. *Deutsche Literaturgeschichte. Von den Anfängen bis zur Gegenwart*. 8th ed., updated and expanded, J.B. Metzler, 2013.

The file "litges_beutin.csv" contains the following columns:

- *ID*: Not relevant.
- *GND-Nummer*: GND identifier for the respective author.
- *Eintrag*: Name of the author as listed in the index of Beutin et al. (2013).
- *Seiten*: Pages as listed in the index of Beutin et al. (2013).
- *Eintragsart*: Not relevant.
- *Anzahl_Seiten*: Automatic addition of pages from the "Seiten" column.
- *Kommentar*: Not relevant.
- *Anzahl_Seiten_neu*: Manual correction of page numbers, based on the information in the "Seiten" column. Corrections were made for errors resulting from entries with "f." in the index and from page-range indications (e.g., 148–153).
- *ignore*: Not relevant.


## Brenner (2011)

We use the third edition: Brenner, Peter J., ed. *Neue deutsche Literaturgeschichte. Vom "Ackermann" zu Günter Grass*. 3rd ed., updated and expanded, De Gruyter, 2011

The file "litges_brenner.csv" contains the following columns:

- *GND-Nummer*: GND identifier for the respective author.
- *Eintrag*: Name of the author as listed in the index of Brenner (2011).
- *Seiten*: Pages as listed in the index of Brenner (2011).
- *Anzahl_Seiten_neu*: Number of pages. This column contains the pages that were manually corrected, based on the information in the "Seiten" column. Corrections were made for errors resulting from entries with "f." in the index and from page-range indications (e.g., 148–153).

The indexes of the literary histories were digitized using text recognition. Author names and the page numbers listed there were transferred into separate columns. 

The main challenges in the digitization process involve page references using "f." and page ranges. In many cases these were digitized correctly, but there are also instances where "f." was not recognized. It can therefore be assumed that, for a significant number of authors, the pages on which they are mentioned may appear one to two pages higher than in the original. 

In addition, the indexes themselves sometimes contain errors, that is, pages on which authors are mentioned are not included in the index. Obvious errors were corrected by cross-checking with the literary histories (for example, in Beutin et al. 2013, the entries for Peter Huchel, Wilhelm Lehmann, and Bertolt Brecht were corrected).
