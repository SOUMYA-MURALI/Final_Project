# Final Project

Airbnb is a prominent online hospitality marketplace and provides data for properties worldwide. 
We reviewed Airbnb publicly available data, focusing on listings and ratings for Dublin, Ireland. 

Source: Inside Airbnb http://insideairbnb.com/get-the-data.html

Listings: Analyzed how various features of properties influence the price of a listings.

Reviews: Performed sentiment analysis on total data set and created training models. 

Various models were employed to understand relationships and predict price.

Link to Tableau - Quick Overview of Data 
https://public.tableau.com/profile/soumya.murali#!/vizhome/final_project_send/SatelliteviewofAirbnblisting-DublinIreland


# Tools and Libraries Utilized
+ Tableau
+ Python/Jupyter Notebook
+ Senitment Intesity Analyzer Vader
+ Pandas, Matplotlib, SKLearn, Statmodels.API, Seaborn
+ Decision Tree, Random Forest, Multinomial Naive Bayes, Logistical Regression
+ IPython Kernel, Standard Scaler




# Jupyter Notebooks

+ *Stats and model analysis-clean* - Initial overview of listings datset to determine the important factors to dive deeper on. 
  Correlation Heatmap, Stats Libarary (STATMODELSAPI)
  
+ *Reviews-Copy1* - Initial review model (biased), using VADER and Multinomical Naive Bayes as test models
+ *Unbiased_Model_Reviews* - Final review model with working test models
+ *All Reviews* - Applied Vader to entire data set to create positive/negative classification

  Folder (AIR_BNB_GITHUB_1)
 + *air_bnb_price_affordability* - Finding the Average Price based on room type, neighbourhood, and listing id.
  Creating predictive model using Logistic Regression from the Average Price of listing id which predicts the lodging is Affordable 
  or Expensive.
 + *price affordability_check* - Saved model


