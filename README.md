# Airline-Customer-Segmentation-LRFMC-Model
Airline Customer Segmentation based on LRFMC Model using K-Means++ Clustering

Get the presentation PDF file here: https://drive.google.com/file/d/1Qhk5evv59NzLioIJnVu-bTfNb4UiVt2y/view?usp=sharing

Customer segmentation is defined as the process where customers of an enterprise are divided into groups based on their purchasing behavior and characteristics. The objective of this project is the categorization of customer records into several groups in the aviation Business-to-Customer (B2C) context, using clustering analysis. This is accomplished by first using the Length, Recency, Frequency, Monetary (LRFM) customer lifetime value model, which scores customers according to four attributes; the relationship length with the company (L), recency of latest transaction (R), purchasing frequency (F), monetary value of customer (M), and cabin or passenger space (C). Then, the poject implement clustering model using the k-means++ algorithm, where customer records are segmented based on their respective LRFMC values. Also, the proposed model is integrated with a hyperparameter tuning phase, where the selection of the number of clusters is performed by employing Elbow Method. Finally, the clustering results are visualized and discussed. Through the customer segmentation, high value customer could be distinguished from valueless customer.

The dataset used by the project is attached in the same folder with this file.

**Objective** :

* Categorize customers into several groups based on LRFMC customer lifetime value model.
* Create recommended actionable insight and approach to the customers.
* Learn about big data clustering.

## Project Workflow:

[1] Data Understanding and Data Clening, include missing value handling and duplicated value check.

[2] Exploratory Data Analysis, include central tendency measures, univariate and bivariate analysis via correlation plot.

[3] Data Preprocessing, include feature selection, feature engineering, and feature scaling via LRFMC scoring.

[4] Modelling, include hyperparameter tuning, clustering, cluster visualization, and clustering analysis

[5] Conclusion and Recommendation

## Conclusion

* 91.71% customers come from China, followed by their neighbourhood: Hong Kong, South Korea, and Japan.
* Most customers are Male, takes up 76.5%
* There are three tiers of FFP (Frequent Flyer Program) offered: 4 - 6 tier. 92.1% customers hold tier 4 FFP.
* The core customers aged 35-45 years old
* There are 5 customer segments (rank from left to right): Loyalist - High Prospect - Low Consumer - Hibernating VIP - Uncertain Lost.
* Based on the total customer proportion,
  * High value customer takes up around 55%
  * Loyal customer takes up 40%, in the contrary 60% are relatively new member.

## Marketing Strategy Recommendation

1. Loyalist/High Value Customer (Cluster 0): Most valuable and core customers. 

 We should maintain the relationship and reward these customers by giving extra discount or free ticket, chance to win prize of flight to popular destination, and special souvenirs. We can also give them early access for our newest product/service and approach them to affiliate our product to help our promotion.

2. Potential Loyalist/High Prospect Customer (Cluster 4): New member with very high consumption. 
 
 We should retend these customers as long as possible. We can offer extra discount or free ticket after some period or of membership or mileage. Offer them discount or extra points that could be redeemed to upgrade for higher class of cabin to give them experience.

3. Low Consumer (Cluster 1): Old customer but low consumption. 

 We should encourage them to purchase more by providing special offers such as discount for longer distance flight and reward them as a regular customer by giving free voucher for affiliated product/event after achieving some flight records in some period, for example 2 flights in a year.

4. Hibernating VIP/ Can't Lose Them (Cluster 3): Recently absent higher class passenger. 

 We should attract them to buy our product again. Assuming this type of customer comes from higher class, bring them back with flight promotions that is bundled with destination event vouchers or signatured souvenirs. Run surveys to find out what went wrong and avoid losing them to a competitor.

5. Uncertain Lost/Low Value Customer (Cluster 2): New member with very low consumption. 

 Send them personalized campaigns/promo to reconnect and notify discount and helpful products to encourage another purchase.

## Reference

[1] Tao, Y.: Analysis Method for Customer Value of Aviation Big Data Based on LFRMC Model. ICPCSEE 2020, CCIS 1257. 89-100(2020)

[2] Kandeil, D., Saad, A. and Youssef, S. M.: A Two-phase Clustering Analysis for B2B Customer Segmentation. INCoS 2014, IEEE. 221-228(2014)

[3] Wer, J. T., et. al: Applying Data Mining and RFM Model to Analyze Customers’ Values of A Veterinary Hospital. IS3C 2016, IEEE, 481-484(2016)
