# Description

We use the term _course description_ for two types of text here: the title and the content description of a university course. By _course_, we refer to both seminars and lectures.  
The course descriptions were scraped from online course catalogues in German Studies at three universities in Austria and Germany: Universität Wien, Universität Stuttgart, and Universität Mainz. All courses were held between the summer semester of 2019 and the winter semester of 2023/24.

Each file corresponds to one university. In each file, rows represent mentions of persons found in course descriptions. The columns represent the following information:

- **GND_ID**: GND identifier of the respective person as manually identified.
- **Mention**: Name of the respective person as it appears in the course description.
- **Mention_Ort**: Takes the value `"Inhalt"` if the mention was found in the course content description, or `"Titel"` if it was found in the course title.
- **Titel**: Original title of the course as scraped from the online catalogue.
- **Inhalt**: Original content description of the course as scraped from the online catalogue.
- **Semester**: Semester in which the respective course was held.
- **NER_Pers_Titel**: List of all automatically identified person mentions in the course title.
- **NER_Pers_Inhalt**: List of all automatically identified person mentions in the course content description.
- **wrong_mention**: Takes the value `"ja"` if, during manual entity linking, the mention was classified as erroneous.
- **Kommentar**: Free-text field where annotators could comment on their decision during manual entity linking (e.g., explaining why a mention was marked as wrong).
- **Art**: Type of course (e.g., Seminar, Lecture), if available in the scraped data.
- **Intervall_Start**: Standardized datetime format for semester start (September for winter, April for summer semester), used for timeline visualization.
- **Intervall_End**: Standardized datetime format for semester end (March for winter, August for summer semester), used for timeline visualization.
- **ID**: Internal course ID assigned by us.

When using the course description data, cite the following: Hilger, Agnes. „On Reconstructions of Academic Canonicity: Explorations of University Course Catalogs for German Literature“. _DH2024 Book of Abstracts_, 2024.

# Data Collection

The initial data collection was carried out by Hilger (2024; see reference above). For a more detailed description of the data acquisition process, see: [https://github.com/agihil/course-catalog-canonicity](https://github.com/agihil/course-catalog-canonicity)

In the first step, lists of programs in German Studies in Germany, Austria, and Switzerland were compiled. A random selection of six universities (three from Germany, two from Austria, one from Switzerland) was drawn, and their online course catalogues were scraped.  
Compared to the total number of universities offering German Studies programs, the sample is small and not representative; analyses of this data should therefore be considered exploratory.

Named Entity Recognition (NER) was carried out on the scraped course titles and content descriptions using the model `flair/ner-german-large`.  
In the original publication, entities were linked to GND authority data semi-automatically using OpenRefine. Since this process proved to be error-prone, we revised the data for this publication and performed entity linking manually.  
However, due to the high manual effort required, we used only a subset of the original data and ensured higher annotation quality. For this reason, the dataset includes data from only three universities and covers the period from 2019 to 2023/24.

Despite the increased data quality, some errors may still be present — for example, not all courses offered in a semester may have been identified, and both the automatic NER and the manual entity linking steps may contain mistakes.  
By publishing the full dataset here, we aim to ensure transparency.
# Description of the Secondary Indicators
## vv_wien
Contains **1037** rows, each representing a person mention identified in the course descriptions scraped from Universität Wien.
## vv_stuttgart
Contains **1621** rows, each representing a person mention identified in the course descriptions scraped from Universität Stuttgart.
## vv_mainz
Contains **538** rows, each representing a person mention identified in the course descriptions scraped from Universität Mainz.

## vv_wien_mainz_stuttgart_all
Contains the data of the three tables above.


