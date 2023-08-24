# Project Description
In this project, exploratory data analysis is performed on supply chain data using Power BI software, with the aid of a created dashboard for easier data visualisation and analysis. There are a few key focuses for this project:
* To investigate *which sub-groups show a higher propensity to be hospitalised* over others
* To investigate *which factors show a strong correlation to discharge charges*

The project involves the following steps:
* **Data Sourcing and Extraction**: A suitably large, free-to-use dataset containing multiple factors is located and downloaded
* **Data Cleaning and Transformation**: The dataset is cleaned using Power Query software and uploaded into Power BI software, where further measures and calcuations are created for analysis
* **Data Visualisation**: The cleaned and trasnformed dataset is loaded into various data visualisations (graphs, charts etc.), culminating in the creation of an interactive dashboard
* **Exploratory Data Analysis**: The dashboard is interpreted to view data interactions between various categories, so as to draw valuable insights 
# Dataset Details
The dataset used in this project is from Kaggle and belongs to a fictious company named "DataCo Global". The dataset contains details pertaining to supply chain data, including. Additional information as well as the raw dataset can be found [here](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis).
# Insights
Through exploratory data analysis, the following insights have been gathered:
1. **Length of Stay**: There is a *positive correlation between average length of stay and charges incurred*, in line with real-world observations 
2. **Age Group**: There is a *positive correlation between average length of stay and age group* (and therefore charges incurred), with the oldest patients falling into the *"70 or Older" age group staying an average of 6.26 days compared to an average of 3.97 days by the youngest "0 to 17" age group*
3. **Payment Method**: *Approximately a quarter (~25.3%) of all patients* fall under the combination of *"MediCare" as a payment method and being in the "70 or Older" age group*, which is in line with expectations since elderly patients make up a significant proportion of all patients and "Medicare" is mainly used by those aged 65 and older
4. **Location**: The *3 locations with the highest costs belong to the "Hudson Valley", "New York City" and "Long Island" areas*, with "Nassau" as a county located within "Long Island" having the highest average charges per patient (~$66.330)
5. **Admissions**: *"Birth-related" admissions classified under the "Extreme" sub-group for severity level incur the highest average total charges per patient by far (~$561,804)*, more than twice the next highest combination of "Trauma-related" admissions classified under the same "Extreme" sub-group (~$230,643)
6. **Race**: Excluding childbirth and pregnancy-related conditions, the *top three medical conditions typically observed across all races are linked to "Diseases and Disorders of the 1) Circulatory, 2) Respiratory and 3) Digestive Systems"*. There is an exception for patients classified under "White" as their racial group, with "Diseases and Disorders of the Musculoskeletal System and Connective Tissue" ranking in the top three
7. **Newborns**: There is an inverse relationship between the number of newborns and the length of stay of newborns, with *~90.8% of newborns staying less than 10 days*. This is in line with real-world observations of the majority of newborns leaving in less than 5 days, which is also supported by [studies](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3336902/). It is interesting to note that the average birth weight also has an inverse relationship with the length of stay, which is likely due to health complications (assuming data is accurate even with a reduced sample size)

