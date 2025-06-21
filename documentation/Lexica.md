# Lexica
<!-- Template for Documentation -->

## Description
Lexica consist of multiple articles on a specific topic, such as German-language literature. They serve as reference works, often aiming to present established knowledge in a comprehensive and accessible manner.

## killy
The *Killy Literaturlexikon* is a 12-volume author lexicon covering German-language literature. Each entry provides information on an author's life and work, along with references to relevant scholarly literature. The lexicon is available online via the "Verfasser-Datenbank" (https://www.degruyterbrill.com/database/vdbo/html), which brings together several major reference works on German-language literature.

We use the second edition: Kühlmann, Wilhelm, ed. *Killy Literaturlexikon: Autoren und Werke des deutschsprachigen Kulturraumes*. 2nd ed., fully revised, De Gruyter, 2008–2012. 12 vols. and 1 index volume.

The file "killy.csv" contains the following columns:

- *GND*: GND identifier for the respective author.
- *VDBO_source*: source volume from the *Verfasser-Datenbank online* from which the article is drawn, e.g., 'Killy_5' (the 5th volume of the Killy Literaturlexikon).
- *author_full*: full name of the author as listed in the *Killy Literaturlexikon*, including name variants, pseudonyms, and other forms.
- *author_simple*: simplified version of the author's name according to the *Killy Literaturlexikon*, excluding name variants, pseudonyms, etc.
- *length*: length of the article, measured in tokens.
