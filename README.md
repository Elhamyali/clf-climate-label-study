# Johns Hopkins Center for a Livable Future Climate Label Study

## **Phase 1:** Scraping ingredients from recipe cards

**Overview**

Phase 1 of the Climate Label Study focuses on the meticulous task of extracting ingredients from recipe cards used in two dining halls at Johns Hopkins University. This phase is crucial as it lays the foundation for subsequent analysis and research activities aimed at assessing the environmental impact of food choices, specifically in terms of greenhouse gas (GHG) emissions.

**Objective**

The primary objective of Phase 1 is to develop and execute a data extraction strategy that efficiently scrapes detailed information about ingredients from recipe cards. This information helps define the composition of meals served over four weeks at the university's dining facilities, and serves as the foundation for calculating the Greenhouse Gas Emissions (GHGE) of ingredients and meals.

**Methodology**

The process involves the following key steps:

- Using a Python script, the project automatically extracts data from a series of PDF files containing the recipe cards. These PDFs represent menus and recipes used over four weeks across two dining halls at Johns Hopkins University.
- The script is designed to scrape various data fields from each PDF, including Site, Date, Station, Meal Type, Recipe Name, Yield, Portions, and detailed Ingredients along with their quantities and units.
- The script is capable of handling multiple files stored in different directories, corresponding to the weekly menus of the two dining halls. It iterates over each PDF file within these directories, ensuring comprehensive data extraction.
- Robust error handling mechanisms are implemented to ensure the script manages any exceptions or anomalies encountered during the extraction process, such as unreadable files or pages without text.

**Deliverables**

The deliverable from Phase 1 is an Excel sheet that tabulates the extracted data. As of December 24, 2023, this process has successfully extracted approximately 26,277 individual ingredients.

## Next Steps (Phases 2-5)

- **Phase 2:** Cleaning dataset and converting quantities with units
Focuses on cleaning the extracted dataset and converting the various quantities and units into a standardized format.

- **Phase 3:** Calculating GHG emissions
Involves calculating the GHG emissions associated with each ingredient, providing a quantifiable measure of environmental impact.

- **Phase 4:** Defining the threshold for GHG emissions
Defines a threshold for GHG emissions, which will evaluate and label the climate impact of different meals through stop light colors.

- **Phase 5:** Future analyses for the study
Encompasses future analyses that use the data gathered and processed in the earlier phases to draw meaningful conclusions and insights relevant to the Climate Label Study.
