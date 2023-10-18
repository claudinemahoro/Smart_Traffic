# Smart_Traffic

Traffic congestion is a persistent problem affecting millions of people daily. Due to the negative effects of 
congestion, including significant delays, increased travel times, and the risk of accidents, it is crucial to 
understand and model traffic patterns accurately to predict congestion and take necessary measures to 
control it. This project aims to analyze traffic conditions in different regions and build predictive models 
for traffic congestion using the Chicago Traffic Tracker dataset. The approach involved exploratory data 
analysis by visualizing trends and patterns over time, as well as K Means clustering to identify clusters 
representing congestion levels. To predict traffic congestion, the data was augmented with a dependent 
variable, and feature selection was performed using Principal Component Analysis and correlation. 
Random Forest, Support Vector Machine (SVM), and K Nearest Neighbor (KNN) were the models used 
and evaluated using F1 score, precision, and recall. Random Forest had the highest metrics when trained 
with all features but performed less otherwise which suggested overfitting. SVM showed consistency across 
different features and performed best when trained on principal components
