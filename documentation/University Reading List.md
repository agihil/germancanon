# University Reading Lists
## Description
A university reading list is a compilation of literary works assembled by German studies departments or individual instructors. The aim is to have students read these texts over the course of their academic training. These lists serve as didactic tools, providing orientation in literary history. The present analysis is based on 42 reading lists from German studies departments in German-speaking countries: Germany (34), Austria (5), Switzerland (2), and Luxembourg (1). At the time of data collection (2021 to 2023), the reading lists were publicly accessible online. According to information provided either on the lists themselves or on the associated websites, the lists were created between 2003/04 and 2023; however, the year of origin could be determined for only 17 of the lists.

There is one file for each of the 42 reading lists. Example: The file "unilist_aachen_201718.csv" contains the following columns:
<ul>
<li>GND: GND identifier for the respective author.</li>
<li>author: Author names are given in the format Last Name, First Name. This does not necessarily have to match the spelling used in the GND. The spelling of authors’ names and titles was adopted directly from the reading lists. In cases of inconsistent spelling across a list, the version used in the first entry was retained.</li>
<li>title: Titles listed on the reading lists. These are generally literary texts. Occasionally, non-literary texts, generic genre designations such as “drama,” or titles of anthologies are also included. For further information, see below.</li>
<li>year: The year indicated generally refers to the year of publication of the title or, in the case of plays, the year of their premiere. In some instances, the year of composition of the play was recorded instead.</li>
<li>prob_to_read: For each title, the probability that a student will have read the text if they follow the reading list’s guidelines is indicated. The values range from 0 to 1. A value of 0 means the title is not mentioned on the list. A value of 1 means the text is listed as a required reading, not part of a selection. Values between 0 and 1 indicate that the title is listed as part of a selection. For further information, see below.</li> 
</ul>

When using the reading list data, cite the following: Jana Eckardt/Frederik Eicks/Sören Kleist/Julia Wagner/Simone Winko (2025). Leselisten als Textsorte und universitäre Kanonisierungsinstanz. Daten und Code [Data set]. IASL/Georg-August-Universität Göttingen. https://doi.org/10.5281/zenodo.15102618.


## Data Collection
The titles and authors listed on the reading lists were manually entered into a table. The following guidelines were observed during data entry:
<ul>
<li>Not all titles appearing on a given reading list were included. The following categories were not recorded consistently: literature published before 1600, non-German-language literature, and works from the field of literary studies (e.g., literary histories, encyclopedias, etc.).</li>
<li>Anthologies were marked with a ‘$’ at the beginning of the entry. Editors are listed in the author column and marked with '(Hg.)'.</li>
<li>There are instances in which only the author’s name and a literary genre are listed (e.g., Karoline von Günderrode: Lyrik). In such cases, the genre is recorded as the title, and the year is typically the average of the author’s birth and death years.</li>
<li>Some of the reading lists offer students a choice of titles either at specific points or as a guiding principle for the entire list. For example, students may be asked to select between two Brecht works, choose 5 out of 20 listed novels, or read 50 of the 100 titles provided. This optionality is reflected in the data. For each title, the probability that a student will have read the text if they follow the reading list’s guidelines is indicated (e.g., 0.5, 0.25, 0.5). When interpreting the data, it should be taken into account that such choices can only be represented when an exact number is specified. Although some reading lists indicate that students are not required to read all texts, they do not quantify this. This cannot be reflected in the data.</li>
<li>If both a general work and a specific title from that work are given, both are recorded separately. For example: “Heine: Reisebilder (at least: Harzreise).” A value of 1 is recorded for both "Reisebilder" and "Harzreise".</li>
</ul>

## Description of the Secondary Indicators
### University Reading List Aachen 2017/18
The University of Aachen has two reading lists. One list is for the teacher education program in German as a teaching subject, and the other reading list is for literary and linguistic studies. This reading list is intended for literary and linguistic studies. 

### University Reading List Augsburg 2020

### University Reading List Bochum

### University Reading List Bochum

### University Reading List Braunschweig

### University Reading List Dortmund

### University Reading List Eichstätt-Ingolstadt 2007

### University Reading List Frankfurt am Main

### University Reading List FU Berlin

### University Reading List Gießen

### University Reading List Göttingen

### University Reading List Graz 2021

### University Reading List Heidelberg 2017

### University Reading List Hildesheim

### University Reading List Innsbruck 2023

### University Reading List Innsbruck

### University Reading List Jena 2018

### University Reading List Karlsruhe

### University Reading List Koblenz

### University Reading List Köln

### University Reading List LA Aachen 2018
The University of Aachen has two reading lists. One list is for the teacher education program in German as a teaching subject, and the other reading list is for literary and linguistic studies. This reading list is intended for the teacher education program.

### University Reading List Lausanne

### University Reading List Leipzig

### University Reading List Lüneburg

### University Reading List Luxemburg

### University Reading List Magdeburg 2020

### University Reading List Mannheim

### University Reading List München

### University Reading List Oldenburg 2020

### University Reading List Osnabrück

### University Reading List Passau

### University Reading List Potsdam 2022

### University Reading List Saarland 2007

### University Reading List Salzburg

### University Reading List Stuttgart 2022

### University Reading List Stuttgart

### University Reading List Trier

### University Reading List Tübingen

### University Reading List Wien

### University Reading List Würzburg 2019

### University Reading List Würzburg 2003/04

### University Reading List Wuppertal 2015

### University Reading List Zürich 2013
