# Analyzing Mental Health and College Difficulty

This project concerns the relationship between anxiety, depression, and difficulty adjusting to college as reported by undergraduate students across the United States. Here we use interactive graphs in a Shiny application to uncover various relationships between these variables. More details, as well as our analyses, can be found in the Shiny executive summary. The Shiny application itself can be found at https://69a3lt-miranda-yang.shinyapps.io/Mental_Health_of_Undergrad_Students/.

The data comes from the Healthy Minds Study among Colleges and Universities, conducted by the Healthy Minds Network. The study asks students across the United States to self report their mental health symptoms and status, along with struggles they may be facing and other demographic factors.

Citation: Healthy Minds Network (2007-2025). Healthy Minds Study among Colleges and Universities, 2007-2025 datasets. Healthy Minds Network, University of Michigan, University of California Los Angeles, Boston University, and Wayne State University. https://healthymindsnetwork.org/research/data-for-researchers.

### Dependencies
R must be installed to run any code in this project. In addition, the following packages are required to run the given programs.

#### Shiny application
 - shiny
 - bslib
 - markdown
 - leaflet
 - sf
 - ggplot2
 - plotly
 - tidyverse
 - shinythemes

#### Data Wrangling
 - readxl
 - openxlsx
 - data.table
 - tidyverse
 - sf

### Notes on Organization of this Repository
The data files from the Healthy Minds study are too large to be stored in this GitHub repository. While not strictly necessary, if you wish to run all code blocks in data_wrangling.qmd, you must add them manually in the initial_data subfolder. You may find these files on Google Drive, linked here: https://drive.google.com/file/d/1HHy2IRv18xQVeYTIVuPmxtor8LV9sWwy/view?usp=drive_link

You may notice that the final_wrangled_data subfolder containing the wrangled data is itself located in the shiny_app subfolder. This was required to publish the Shiny application.
