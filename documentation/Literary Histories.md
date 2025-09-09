
# Literary Histories

## Description

In this context, 'literary histories' are understood as monographic studies of German-language literature, constituting a textual form that is both literary-critical and historiographical. They are often organized according to literary periods or time periods.

## Beutin et al. (2013)

The *Deutsche Literaturgeschichte* is a German-language literary history written by Wolfgang Beutin, Matthias Beilein, Klaus Ehlert, Wolfgang Emmerich, Christine Kanz, Bernd Lutz, Volker Meid, Michael Opitz, Carola Opitz-Wiemers, Ralf Schnell, Peter Stein and Inge Stephan. It was first published in 1979 and comprises a total of 781 pages. This single-volume work covers literature from the Medieval Period to Contemporary Literature.

We use the eighth edition: Beutin, Wolfgang et al., ed. *Deutsche Literaturgeschichte. Von den Anfängen bis zur Gegenwart*. 8th ed., updated and expanded, J.B. Metzler, 2013.

The literary history by Beutin et al. exists in nine editions (1st edition 1979, 2nd edition 1984, 3rd edition 1989, 4th edition 1992, 5th edition 1994, 6th edition 2001, 7th edition 2008, 8th edition 2013, 9th edition 2019). Up to the 5th edition, fundamental revisions were carried out; in the 6th edition, substantial conceptual innovations and shifts of emphasis were also introduced, as well as the addition of two new chapters („Die literarische Moderne von 1890 bis 1920“ and „Tendenzen der deutschsprachigen Gegenwartsliteratur seit 1989“); but since the 7th edition, only minor corrections, revisions, and additions have apparently been made.


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

The *Neue deutsche Literaturgeschichte* is a German-language literary history written by Peter J. Brenner. It was first published in 1996 and comprises a total of 439 pages. It is a single-volume work covering literature from the Early Modern period to the Berlin Republic.

We use the third edition: Brenner, Peter J., ed. *Neue deutsche Literaturgeschichte. Vom "Ackermann" zu Günter Grass*. 3rd ed., updated and expanded, De Gruyter, 2011.

The literary history by Brenner exists in three editions (1st edition 1996, 2nd edition 2004, 3rd edition 2011). It is difficult to assess how fundamental the respective revisions are: for the 2nd edition, the literary history was „durchgesehen und bis zur Gegenwart weitergeführt“ (Brenner 2004), and for the 3rd edition, among other things, „Abschlusskapitel neu geschrieben und die literarhistorische Darstellung der letzten 40 Jahre insgesamt neu organisiert.“ In addition, the text was „durchgehend ergänzt und erweitert; dadurch wurde häufiger eine Neuorganisation der Darstellung erforderlich.“

The file "litges_brenner.csv" contains the following columns:

- *GND-Nummer*: GND identifier for the respective author.
- *Eintrag*: Name of the author as listed in the index of Brenner (2011).
- *Seiten*: Pages as listed in the index of Brenner (2011).
- *Anzahl_Seiten_neu*: Number of pages. This column contains the pages that were manually corrected, based on the information in the "Seiten" column. Corrections were made for errors resulting from entries with "f." in the index and from page-range indications (e.g., 148–153).
  

## Data Collection

The indexes of the literary histories were digitized using text recognition. Author names and the page numbers listed there were transferred into separate columns. 

The main challenges in the digitization process involve page references using "f." and page ranges. In many cases these were digitized correctly, but there are also instances where "f." was not recognized. It can therefore be assumed that, for a significant number of authors, the pages on which they are mentioned may appear one to two pages higher than in the original. 

In addition, the indexes themselves sometimes contain errors, that is, pages on which authors are mentioned are not included in the index. Obvious errors were corrected by cross-checking with the literary histories (for example, in Beutin et al. 2013, the entries for Peter Huchel, Wilhelm Lehmann, and Bertolt Brecht were corrected).
