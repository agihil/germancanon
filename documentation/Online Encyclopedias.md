# Online Encyclopedias
## Description

We consider online encyclopedias – in this case, _Wikipedia_ – as another potential indicator of canonicity.

Our dataset includes Wikipedia data for all authors mentioned in at least one of the other indicators (e.g., university reading lists, school exams). Wikipedia entries were identified via the authors’ GND identifiers. Data collection took place in the summer of 2025.

In our paper, we use article length as the metric, in order to maintain consistency with our treatment of (offline) encyclopedias. However, the dataset also provides several additional metrics.

Each row in the file `wiki.csv` represents one author. The file contains the following columns:

-   *GND*: GND identifier of the respective author
-   *page_found*: Boolean indicating whether a Wikipedia page exists for the respective author
-   *page_url*: URL of the Wikipedia article for the respective author
-   *page_title*: Title of the Wikipedia article for the respective author
-   *Item_id*: Wikidata identifier of the respective author
-   *length_in_words*: Length of the Wikipedia article in words
-   *number_of_sitelinks*: Number of sitelinks associated with the article
-   *number_of_pageviews_last_5_years*: Number of pageviews the article received over the past five years
-   *number_of_in_links*: Number of in-links pointing to the article
