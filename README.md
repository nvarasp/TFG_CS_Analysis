# TFG_CS_Analysis
This repository contains the scripts of my thesis' project: 
### "Analysis and comparison of local, national and European citizen science platforms"
Citizen participation in science, known as citizen science, is emerging as support for formal science, so that citizens learn and contribute to the local policies that are carried out. This work aims to analyse and compare the current situation of citizen science in Barcelona, Spain and Europe through its web platforms, with special emphasis on its relation with education.

To do this, information has been extracted from the Barcelonian, Spanish and European citizen science platforms, analysing them through computational techniques that permit to compare them, draw conclusions and indicators.

In order to get and analyse the content of the platforms, six scripts have been generated. First of all, one called “scraping_data.ipynb” scraps the desired content from the Spanish and Barcelonian platforms using Selenium and saves the different files. The way to do so is explained later on. 

The three scripts called “European_anlaysis.ipynb”, “Spanish_analysis.ipynb” and “BCN_analysis.ipynb” analyse individually the content of the corresponding platform in a more extensive way, generating interesting plots to get insights.  The “functions_t.ipynb” script includes several created functions that will be used in the analysing scripts. 

Finally, the one called “comparing_platforms.ipynb” imports the project's and resources’ data frames from the three platforms (generated as .xlsx files after performing some analysis in the corresponding scripts). On the one hand, it checks if there are projects that appear on more than one website and displays the corresponding cases to compare the different ways in which platforms present the same initiative. On the other hand, it joins all projects from the three pages (taking the repeated ones just one time) to generate a global dashboard with all projects, and the same is done with the resources. This will assist to create a general overview of the citizen science current situation. 

The resulting data frames have been imported to Tableau as a means to generate dashboards visualizations that display the data in a more visual and interactive way. The created website https://nvarasp.wixsite.com/cs-analysis includes the most interesting ones together with some obtained conclusions so that anyone can get all the insights with one click. 

The report is also included here.

Núria Varas, student of Mathematical Engineering in Data Science
