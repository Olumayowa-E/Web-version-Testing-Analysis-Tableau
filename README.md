# WEB VERSION TESTING ANALYSIS WITH TABLEAU

![image](https://github.com/user-attachments/assets/4ef60a6f-7dfc-46ed-ba0d-5a0eefbf73c0)

## Project Overview
This analysis was aimed at identifying which webpage version performs better across various user engagement metrics for a digital company. A detailed dataset capturing user interactions, behaviors, and responses to each webpage version was compiled and analyzed to determine the effectiveness of each design, inform future design iterations, and ultimately enhance user experience based on data-driven insights.

## My Analytical Approach
The dataset I worked with primarily consisted of Boolean values. I employed calculated fields to convert the true/false values into numerical data suitable for aggregation and analysis. This transformation was important to make the data appropriate for analysis. 


To provide a quick snapshot of each web version's performance, I identified and displayed key metrics at the top of the dashboard(image above), including the total number of users for the test, average pages viewed, and the overall conversion rate. 


The most intriguing and challenging aspect of this analysis was constructing a sales funnel to visualize the user journey from product view to final purchase. Using calculated fields in Tableau, I computed the conversion rates at each stage of the customer journey: from product view to add-to-cart, to add-to-cart to checkout, to checkout to purchase, and overall conversion rate.This granular approach revealed where potential customers were dropping off in the sales funnel.


During the sales funnel preparation, I uncovered an issue with the dataset. The checkout-to-purchase rate was initially above 100%, which was logically impossible. To tackle this challenge, I employed calculated fields. This process revealed potential issues in the data collection process which could be later addressed.
To address the data inconsistency, I implemented a series of calculated fields to adjust the values, ensuring logical consistency in the user journey. 

Please see attcahed PDF for details on insights and recommendations.

