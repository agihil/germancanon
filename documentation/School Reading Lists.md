# School Reading Lists
## Description
School reading lists are official literature lists for German language teaching in secondary schools in all federal states of the Federal Republic of Germany [„offizielle[] Literaturlisten für den gymnasialen Deutschunterricht aller Bundesländer der Bundesrepublik Deutschland“] (Spitzer, Wortmann, and Wolfer, 2023).

Our study draws on data collected by Spitzer, Wortmann, and Wolfer (2023), available at [https://www.owid.de/plus/lektemp2022/](https://www.owid.de/plus/lektemp2022/) (last accessed November 13, 2025). The dataset provides additional information on author gender, literary works, literary awards, and children’s and young adult literature. Further details are available in the accompanying documentation: [https://www.owid.de/plus/lektemp2022/LektEmp_InformationZurDatenbasis.pdf](https://www.owid.de/plus/lektemp2022/LektEmp_InformationZurDatenbasis.pdf) (last accessed November 13, 2025).

For our analysis, we compiled the relevant information into multiple files—one for each German state represented in Spitzer, Wortmann, and Wolfer (2023)—for example, `schullist_bayern.csv` or `schullist_brandenburg.csv`.

Each row in a `schullist_STATE.csv` file represents a single title. The files contain the following columns:

-   *GND*: GND identifier of the respective author
-   *author*: Name(s) of the author(s) as listed in Spitzer, Wortmann, and Wolfer (2023)
-   *title*: Title of the work as listed in Spitzer, Wortmann, and Wolfer (2023)
-   *year*: Year of publication as listed in Spitzer, Wortmann, and Wolfer (2023)
-   *state*: German federal state responsible for the reading list
-   *ID_orig*: Identifier of the entry in the original dataset by Spitzer, Wortmann, and Wolfer (2023)
  
When using the school reading list data, please cite:  
Carolin Müller-Spitzer, Thomas Wortmann, Sascha Wolfer: Bildungsrelevante Lektüre war und ist vorwiegend von Männern verfasste Literatur. Eine qualitativ-quantitative Auswertung von offiziellen Lektüreempfehlungen für den gymnasialen Deutschunterricht. In: Mitteilungen des DGV 70:2, 2023, pp. 198–218.
