# Analyzing Mental Health of Undergrads

This project concerns the relationship between anxiety, depression, and difficulty adjusting to college as reported by undergraduate students across the United States. Here we use interactive graphs in a Shiny application to uncover various relationships between these variables. More details, as well as our analyses, can be found in the Shiny executive summary. The Shiny application itself can be found at https://69a3lt-miranda-yang.shinyapps.io/Mental_Health_of_Undergrad_Students/.

The data comes from the Healthy Minds Study among Colleges and Universities, conducted by the Healthy Minds Network. The study asks students across the United States to self-report their mental health symptoms and status, along with struggles they may be facing and other demographic factors.

Citation: Healthy Minds Network (2007-2025). Healthy Minds Study among Colleges and Universities, 2007-2025 datasets. Healthy Minds Network, University of Michigan, University of California Los Angeles, Boston University, and Wayne State University. https://healthymindsnetwork.org/research/data-for-researchers.

This was a collaborative project by Henry Sun, Maxine Dobbs, and Miranda Yang. Credit is given for each section of code as to who wrote it.

## Dependencies
R must be installed to run any code in this project. RStudio is recommended for opening and running code. In addition, the following packages are required to run the given programs.

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

## Notes on Organization of this Repository
The data files from the Healthy Minds study are too large to be stored in this GitHub repository. While unnecessary, running all code blocks in data_wrangling.qmd means adding them manually into the initial_data subfolder. If you wish to do so, you can either reach out to Maxine (maxdobbs32@gmail.com) for access to these files or make a request to the Healthy Minds Network here: https://forms.gle/g2BfiQyKXVguGNQAA.

You may notice that the final_wrangled_data subfolder containing the wrangled data is itself located in the shiny_app subfolder. This was required to publish the Shiny application.
