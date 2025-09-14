# **Biodiversity in National Parks [Portfolio Project]**

## **Introduction:**
This project was performed for the machine learning speciality in CodeCademy. The data was provided by CodeCademy and contained
data collected on U.S. national parks. The data was contained in two csv files (observations.csv & species_info.csv). The data was 
cleaned, analyzed, and plotted using a jupyter notebook and focused on answering four questions provided by Codecademy:
- What is the disribution of conservation_status for animals?
- Are certain types of species more likely to be endangered?
- Are difference between species and their conservation status significant?
- Which species were spotted the most at each park?

## **Tools used:**
- jupyter notebook
- pandas
- scipy.stats
- matplotlib
- numpy

## **Key Findings:**
- The species sampled most oftern were vascular plants
- 96.72% of dataset did not have a conservaton status noted
- The observations that did contain a conservation status, most (83.2%) were categorized as species of concern.
- The animals species containing the most conservation status observations by proportion were: Mamals (17.7%) followed by Birds (15.1%) and Fish (9.4%)
- Sampling for each park was consistent with vascular plants representing most observations and reptiles representing the fewest.
- Species category showed a moderate relationship to conservation status (Cramers V: 0.33) w/ Mammals, Fish, Birds, and Amphibians contributing most toward the relationship. See [Cramers V](https://en.wikipedia.org/wiki/Cram%C3%A9r%27s_V) and [Cohen's Rules of Thumb](https://cebma.org/assets/Uploads/Overview-Effect-Sizes-v2.pdf) for further information.

