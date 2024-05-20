# Penguins_Unsupervised_Classification

This is a project of a graduated level machine learning course that aims to classify good/bad wine base on costum setting (by the user) on the wine quality. The project was originally finished in R (check it out!) but it was improved and written in python language (shown here).

The description and the datasets can be accessed here:

https://archive.ics.uci.edu/dataset/186/wine+quality

Please not that only **white** wine data is used here.

The project will be presented into two parts: 1. Binary classification. 2. Mulitclass Classification
In general, the structure follows:

**1. Data Access and threshold setting**

**2. Data Visualization**
   
**3. Data Preparation**
   
**4. Logistic Regression Approach**   

**5. Random Forest Approach**   

**6. Support Vector Classifier Approach**


# 1. Binary Classification

The feature of this project is returning "good/bad" label for each wine, and the "standard" is set by the user. The reason behind is simply: common people might not be able to quantify the quality for a bottle of wine (like a professonal wine taster!), this might help them to roughly know which wine might fit their need in the future.

One of the feature is "quality" (from 1 to 10, where 10 is perfect) of the wine, we simply set a threshold on this feature to distinguish the label of the wine.

First of all, we type in a number and set the threshold:
![alt text](images/a1.jpg)
![alt text](images/a2.jpg)
![alt text](images/boxplot.jpg)

![alt text](images/a3.jpg)
![alt text](images/a4.jpg)
![alt text](images/a5.jpg)
![alt text](images/a6.jpg)


![alt text](images/b1.jpg)
![alt text](images/gender.jpg)
![alt text](images/b2.jpg)
![alt text](images/culmen_length_mm.jpg)
![alt text](images/culmen_depth_mm.jpg)
![alt text](images/flipper_length_mm.jpg)
![alt text](images/body_mass_g.jpg)

![alt text](images/c1.jpg)
![alt text](images/c2.jpg)


![alt text](images/d1.jpg)
![alt text](images/Change_in_Inertia.jpg)
![alt text](images/Interia_Trend.jpg)
![alt text](images/d2.jpg)
![alt text](images/3d_kmean.jpg)
![alt text](images/d3.jpg)
![alt text](images/2_vs_3_PCproj.jpg)
![alt text](images/3_vs_1_PCproj.jpg)
![alt text](images/1_vs_2_PCproj.jpg)

![alt text](images/e1.jpg)
![alt text](images/den.jpg)
![alt text](images/e2.jpg)
![alt text](images/e3.jpg)
![alt text](images/hc.jpg)

![alt text](images/f1.jpg)
![alt text](images/f2.jpg)
![alt text](images/N_clusters_DBSCAN.jpg)
![alt text](images/Sil_score_DBSCAN.jpg)
![alt text](images/f3.jpg)
![alt text](images/f4.jpg)
![alt text](images/f5.jpg)
![alt text](images/f6.jpg)
![alt text](images/DBSCAN.jpg)
