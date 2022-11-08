# Practical-Application-3

The business objective is to market bank products to the targeted customers instead of running generic campaigns.The business success metric is customer accepting banking products. 

## Data 
Our dataset comes from the UCI Machine Learning repository link. The data is from a Portugese banking institution and is a collection of the results of multiple marketing campaigns. The data is clean without null values.


<center>
    <img src = data_columns.png width = 40%/>
</center>


## Data Preparation

These steps followed to visualize the data to gain deeper understanding:
1. Checked the distribution of data
2. Removed the outliers
3. Checked correlations 
4. Standardized the data


<center>
    <img src = distribution.png width = 60%/>
</center>

### Distribution after removing the outliers
<center>
    <img src = data_without_outliers.png width = 60%/>
</center>

### Correlation

<center>
    <img src = corr.png width = 60%/>
</center>


### Standardized the data
<center>
    <img src = standardized.png width = 60%/>
</center>

compare the performance of the classifiers we encountered in this section, namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. We will utilize a dataset related to marketing bank products over the telephone.



## Classifications Models

The following Classification Models used in the application:
1. DummyClassifier
2. LogisticRegression
3. KNeighborClassifier
4. RandomForestClassifier
5. SVC

### Models performance
<center>
    <img src = modeling.png width = 60%/>
</center>

## Conclusion
 Based on preliminary model analysis Logistics Regression outperformed.To optimize further we used the GridSearchCV along with LogisticsRegression. 