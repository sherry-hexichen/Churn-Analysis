# Churn-Analysis
This project is the practicum project that was required by my Master's Degree. The industrial host was Dealer-FX Group Inc. located in Markham, Ontario.

Throughout the last three years, Dealer-FX's customers have been experiencing around 46% customer churn in their service departments. They are losing on high potential revenue opportunities since service departments in car dealerships have higher profit margins than their retail vehicle sales. Thus, Dealer-FX is interested in developing a solution that both: caters to their customer's needs and compliments their existing branches of business.

The managerial problem at hand is to: tailor a solution for car dealerships to reduce customer churn in their service department. Our team developed a predictive model to predict the likelihood of a customer churning in the next year, and evaluating the reasons for customer attrition in order to provide car dealerships with individualized insight into why their service department customers are leaving.

The data that was used for analysis entailed customer level transactional data for 9 different car dealerships ranging from November 2016 – November 2019, the overall size of the data was around 200,000 observations and covered four main subsets: Dealer, customer, service and vehicle information. Overall, a CatBoost Decision Tree was used to predict the probability of a customer-vehicle pair from leaving the service department in the next year, customers were then grouped into deciles based on their probability of churn. 

The model yielded **very accurate results** via the high agreement between predicted and actual churn, in addition the top risk decile was predicted to churn at **2x** the average rate (91% vs. 46% respectively) and the second risk decile was predicted at **1.5x** times the average rate (63% vs. 46% respectively).

Each dealership may have a different strategy in terms of selecting the target group. For instance, some dealerships may think that the highest risky customer would decide to leave anyway, so they may want to target the customers who are on the edge, for instance, decile 3 to 6 who may have 40% to 50% probability to lost, to make them become more loyal customers. Alternatively, some dealerships may consider conducting special events for loyal customers, such as the ones in decile 9 or 10, to retain their loyalty. In either case, the model can help the marketing team to **identify the right subset** of the customers to contact.

Except for the probability of churn, the model also reported the features that contribute the most when predicting the likelihood. As these features may provide us with hints on why customers ended up deciding to leave the dealership, we conducted some preliminary analysis on the features and the predicted probability. 

Two main recommendations were proposed to complement the Marketing Services branch: a customer score card for segmentation based on risk characteristics and a customer contact list for targeted campaigns of top risky customers. Future work entailed expanding the analysis to all Dealer-FX clients as well as further investigating churn via voluntary vs. involuntary churners where data was currently not available to pursue.

**Great appreciation to my teammates, *Rachel Zhou* and *Khalid Askar***, who completed the project together with me. It was my pleasure to work with them.

