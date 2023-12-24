# Johns Hopkins Center for a Livable Future Climate Label Study

## **Phase 1:** Scraping ingredients from recipe cards

**Overview**

Phase 1 of the Climate Label Study extracts ingredients from recipe cards used in two dining halls at Johns Hopkins University. This phase supports subsequent analysis and research activities such as labeling the climate impact of food choices into cards in terms of greenhouse gas (GHG) emissions and presenting them to students.

**Objective**

Phase 1 aims to extract data that scrapes detailed information about ingredients from recipe cards. This information helps define the composition of meals served over four weeks at the university's dining sites to calculate the Greenhouse Gas Emissions (GHGE) of ingredients and meals.

**Methodology**

The process involves the following key steps:

- Using a Python script, the project automatically extracts data from a series of PDF files containing the recipe cards. These PDFs represent menus and recipes used over four weeks across two dining halls at Johns Hopkins University.
- The script scrapes various data fields from each PDF, including Site, Date, Station, Meal Type, Recipe Name, Yield, Portions, and detailed Ingredients along with their quantities and units.
- The script can handle multiple files stored in different directories, corresponding to the weekly menus of the two dining halls. It iterates over each PDF file within these directories, ensuring comprehensive data extraction.
- Robust error handling mechanisms are implemented to ensure the script manages any exceptions or anomalies encountered during the extraction process, such as unreadable files or pages without text.

**Deliverables**

Phase 1 produces an Excel sheet that tabulates the extracted data. As of December 24, 2023, this process has successfully extracted approximately 26,277 ingredients.

## Next Steps (Phases 2-5)

- **Phase 2:** Cleaning the extracted dataset and converting the various quantities and units into a standardized format.

- **Phase 3:** Calculating GHG emissions associated with each ingredient, providing a quantifiable measure of environmental impact.

- **Phase 4:** Defining the threshold for GHG emissions, which will evaluate and label the climate impact of different meals through stoplight colors.

- **Phase 5:** Future analyses for the study that use the data gathered and processed in the earlier phases to draw meaningful conclusions and insights relevant to the Climate Label Study.
