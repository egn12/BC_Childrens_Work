# BC Children's Work

Work I'm doing as a Summer Data Scientist for the BC Children's Hospital Foundation Analytics Team. The goal of the Foundation is to enhance the resources provided to the hospital by the provincial government in order to deliver the best care available to children and youth throughout the province. 

The jupyter notebooks are organized as follows:

**1. Cleaning and Geocoding**
  - Cleaning & Aggregating data from different databases at the postal code level 
  - Adding a Lat/Long to each postal code through Google API 
  - Placing each BC postal code within a neighbourhood using shapefiles 
  
**2. EDA and Prediction (Manifold)** 
   - Exploring the dataset relationships (correlation matrix, plotting). 
   - Running prediction analysis on 2016 hospital donations: 
      * `Multivariate Regression` 
      * `Multivariate Regression with PCA regressors`
      * `Random Forest` 
      * `Boosting`

**3. Churn (Retention Rates) Analysis (2016/17)**
   - Exploring the dataset relationships (Recency, Frequency and Monetary Value). 
   <img src="https://github.com/elbagn/BC_Childrens_Work/blob/master/churn.png" width="500" height="300" title="Github Logo">
   <img src="https://github.com/elbagn/BC_Childrens_Work/blob/master/Rec_Freq.png" width="700" height="300" title="Github Logo">
    <img src="https://github.com/elbagn/BC_Childrens_Work/blob/master/2016don_Freq_1.png" width="700" height="300" title="Github Logo">  
   - Classifying individuals by rentention rates: 
      * `Logistic Regression` 
      * `Random Forest`
      * `Boosted Decision Trees`
   - Feature Importance    
   - Deployment of model to Microsoft Azure in order to predict rates for 2018

**3. Visualizations**
  - Heatmap and Chloropleth for donation + demographic data accross BC ; blueprint for dashboard created using javascript + D3
     <img src="https://github.com/elbagn/BC_Childrens_Work/blob/master/Vancouver_heatmap.PNG" width="500" height="300" title="Github Logo">
     <img src="https://github.com/elbagn/BC_Childrens_Work/blob/master/chloropleth_all_bc_1.PNG" width="500" height="300" title="Github Logo">
