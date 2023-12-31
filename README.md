# Project Description
In this project, exploratory data analysis is performed on supply chain data using Power BI software, with the aid of a created dashboard for easier data visualisation and analysis. There are a few key focuses for this project:
* To create *separate reports visualising data from three different angles (Sales, Delivery and Customer)*
* To glean *insightful data figures and/or trends independently from the three reports, before combining them for a more complete understanding*
* To identify *opportunities to improve On-time Delivery (ie. ratio of non-late deliveries to all deliveries), a key performance indicator related to the supply chain industry*

The project involves the following steps:
* **Data Sourcing and Extraction**: A suitably large, free-to-use dataset containing multiple factors is located and downloaded
* **Data Cleaning and Modelling**: The dataset is cleaned using Power Query software and uploaded into Power BI, where further measures and calculations are created for analysis
* **Data Visualisation**: The cleaned and transformed dataset is loaded into various data visualisations (graphs, charts etc.), culminating in the creation of an interactive dashboard
* **Exploratory Data Analysis**: The dashboard is interpreted to view data interactions between various categories, so as to draw valuable insights 
# Dataset Details
The dataset used in this project is from Kaggle and belongs to a fictious company named "DataCo Global". The dataset contains details pertaining to supply chain data, including customer demographics, product categories, order, shipment, and price details, with data covering a duration of four years (2015 to 2018). Additional information as well as the raw dataset can be found [here](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis).
# Insights
Through exploratory data analysis, the following insights have been gathered from the three reports:

*Note: Due to incomplete data resulting in skewing of results, only data up to Sep'17 has been used in exploratory data analysis*

**1. Sales** (excluding cancelled deliveries):

![](https://github.com/vikashperiasamy/Power_Bi_Dashboard_for_Supply_Chain_Data/blob/main/Images/Sales%20Report.png)

a) "Latin America" (~30.0%) and "Europe" (~28.0%) make up the majority of sales by delivery region, with "Standard Class" (~59.8%) as a shipping mode accounting for the majority of shipments by sales. 

b) With regards to product category type, "Fishing" (~$5.4 million in total sales) is a clear leader with the next highest category type "Cleats" bringing in ~$3.4 million.

c) Individual sales for the top 10 product category types are mostly evenly distributed with regards to both delivery region and shipping mode, with no outliers from total sales distributions.

d) Looking at monthly performance over time, it is clear sales and profits are closely correlated as per expectations. However, there are *three main outlier areas (Feb'15, Feb'16, Aug-Sep'17)* which can be analysed in two groups as follows:

   * i) *Both Feb'15 and Feb'16 show a sharp drop followed by a sharp V-shaped recovery* back into baseline, with a *decrease in order quantity being the most likely contributing factor*. However, it should be noted that Jun'17 also had a slightly smaller but comparable drop in order quantity, yet sales remained within baseline, though in the lower region. This can be attributed to the order mix in each time period, since the sales price and discounts offered would be different.

   * ii) *Aug-Sep'17 shows a sustained boost above baseline*, which can be attributed to a *change in order mix and demand from "Europe" delivery region*. There is increased sales in existing product category types ("Fishing", "Golf Gloves" etc.), while there also appears to be *newly available product category types since Q2'17*, some of which ("Strength Training", "Basketball" etc.) rank amongst the highest in terms of sales price, thereby naturally boosting sales.

**2. Delivery**: 

![](https://github.com/vikashperiasamy/Power_Bi_Dashboard_for_Supply_Chain_Data/blob/main/Images/Delivery%20Report.png)

a) The *On-time Delivery rate has been calculated to be ~40.93%*, which is far below expected [industry](https://xcelpros.com/on-time-delivery-in-operations-part-1/) [targets](https://elogii.com/blog/on-time-delivery/#:~:text=A%20good%20on%20time%20delivery,goals%20based%20on%20current%20performance.) of at least 90-95%. 

b) Notably *~4.4% of deliveries have been cancelled* (likely due to customer dissatisfaction or insufficient products to fulfil orders on the company's end), while *~54.7% deliveries are late*. These two groups will be analysed as follows:

   * i) Cancelled Deliveries: At first glance, there are no clear indicators based on delivery country, shipping mode or time period. However, it is interesting to see *payment methods falling under "Others" being used for 100% of cancelled deliveries* (although it should be noted that such payment methods are also used for deliveries falling under the On-time Delivery data group). A more detailed investigation into this factor and its accompanying details should yield some insight to lessen or completely eliminate cancelled deliveries.

   * ii) Late Deliveries: At first glance, there are no clear indicators based on delivery country, product category type, or time period. However, it is interesting to note that *"First Class" as a shipping mode is only present in late or cancelled deliveries*. Further investigation and, if deemed necessary, exclusion of this shipping mode will likely help reduce the quantity of late deliveries.

**3. Customer**: 

![](https://github.com/vikashperiasamy/Power_Bi_Dashboard_for_Supply_Chain_Data/blob/main/Images/Customer%20Report.png)

a) Looking at payment method, there are no changes in preference from 2015 to 2017 with "Debit" being the preferred choice. 

b) With regards to customer segment, "Consumer" is observed to be the highest contributing customer segment consistently across all five delivery regions.

c) With regards to *quantity of customers aggregated by product category type, "Fishing" is ranked only fifth with "Cleats" ranking as first*, although it should be noted the distribution is more even compared to the sales data. This contrast between sales and customer quantity data can be attributed to *differences in sales price* ("Fishing" products costing $399.98 compared to "Cleats" products costing $59.99 per item) and/or possible greater customer loyalty for "Fishing" products. 
