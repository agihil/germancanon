# germancanon

Repository containing data and code for the publication  
*Eckardt, Jana, Agnes Hilger, and Merten Kröncke. “1000 Punkte für Goethe: Eine empirische Rekonstruktion des Kanons der neueren deutschsprachigen Literatur.” Zeitschrift für Germanistik, vol. 37:1, 2027 [forthcoming].*

---

## 🚀 Quick Access

The file `canonicity_scores.xlsx` in the folder `data/` lists more than 5,000 authors of German-language literature (from roughly 1600 onward) along with their corresponding canonicity scores.

- `GND` – GND identifier of the author  
- `author` – author name according to the GND
- `canonicity_score` – Score ranging from 1 to 1000, where higher values indicate a more canonical author  
- `canonicity_rank` – Rank of the author, where lower numbers correspond to higher canonical status


![pic_canonicity_score](https://github.com/user-attachments/assets/e1747f72-a948-46ba-b0b9-dc94365e1b95)


*Example*: Johann Wolfgang von Goethe (`GND: 118540238`) has a canonicity score of 1000 and holds rank 1, making him the most canonical author of newer German-language literature.

---

## 📂 Repository Structure

### `data/`
Includes `data.csv`, which aggregates and harmonizes the individual files from `raw_data/`, and `canonicity_scores.xlsx` (see above).

### `documentation/`
Provides detailed information on the data in `raw_data/`, e.g., on data collection methods, definitions and meanings of columns, and bibliographic and licensing information for all data sources.

### `notebooks/`
Contains Jupyter notebooks with Python code for merging and cleaning the raw data and computing and analyzing canonicity scores.

### `raw_data/`
Contains the original datasets used to reconstruct canonicity, e.g., mentions of authors in university reading lists, literary histories, etc. All data is reusable. Please cite the corresponding sources (see `documentation/`).

---

## 🧾 Changelog

*(Nothing yet — first version)*

---

## References

If using the data from this repository, please cite the following publication:
*Eckardt, Jana, Agnes Hilger, and Merten Kröncke. “1000 Punkte für Goethe: Eine empirische Rekonstruktion des Kanons der neueren deutschsprachigen Literatur.” Zeitschrift für Germanistik, vol. 37:1, 2027 [forthcoming].*
