# Project Description
In this project, exploratory data analysis is performed on supply chain data using Power BI software, with the aid of a created dashboard for easier data visualisation and analysis. There are a few key focuses for this project:
* To create *separate reports for three different categories (Sales, Delivery and Customer)*
* To identify *key data figures and/or trends independently from the three reports, before combining them for better understanding*
* To identify *opportunities to improve On-time Delivery (ie. ratio of non-late deliveries to all deliveries), a key performance indicator related to the supply chain industry*

The project involves the following steps:
* **Data Sourcing and Extraction**: A suitably large, free-to-use dataset containing multiple factors is located and downloaded
* **Data Cleaning and Modelling**: The dataset is cleaned using Power Query software and uploaded into Power BI, where further measures and calcuations are created for analysis
* **Data Visualisation**: The cleaned and trasnformed dataset is loaded into various data visualisations (graphs, charts etc.), culminating in the creation of an interactive dashboard
* **Exploratory Data Analysis**: The dashboard is interpreted to view data interactions between various categories, so as to draw valuable insights 
# Dataset Details
The dataset used in this project is from Kaggle and belongs to a fictious company named "DataCo Global". The dataset contains details pertaining to supply chain data, including customer demographics, product categories, order, shipment, and price details, with data covering a duration of four years (2015 to 2018). Additional information as well as the raw dataset can be found [here](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis).
# Insights
Through exploratory data analysis, the following insights have been gathered from the three reports:
*Note: Due to incomplete data resulting in skewing of results, only data up til Sep'17 has been used in exploratory data analysis*

1. **Sales**
Excluding cancelled deliveries, "Latin America" (~30.0%) and "Europe" (~27.6%) make up the majority of sales by region, with "Standard Class" (~59.8%) as a shipping mode accounting for the majority of shipments. With regards to product category type, "Fishing" (~$5.4 million in total sales) is a clear leader with the next highest category type "Cleats" bringing in ~$3.4 million.

Additionally, sales for the top 10 product category types are evenly distributed with regards to region and shipping mode.

With regards to total sales and profits by month, there are 3 main outlier areas (Feb'15, Feb'16, Aug-Sep'17). Both Feb'15 and Feb'16 show a drop followed by an immediate V-shaped recovery back into baseline, while Aug-Sep'17 show a sustained boost above baseline. There is no clear commonality between Feb'15 and Feb'16 based on the Sales report, while it is clear the boost in Aug-Sep'17 is attributed to the "Europe" region.

2. **Delivery**
The On-time Delivery rate has been calculated to be ~40.93%, which is far below expected [industry](https://xcelpros.com/on-time-delivery-in-operations-part-1/) [targets](https://elogii.com/blog/on-time-delivery/#:~:text=A%20good%20on%20time%20delivery,goals%20based%20on%20current%20performance.) of at least 90-95%.

Notably ~4.4% of deliveries have been cancelled (likely due to customer dissatisfaction or insufficient products to fulfil orders on the company's end). From the report, there are no clear indicators based on country, shipping mode or period.

4. **Customer**



