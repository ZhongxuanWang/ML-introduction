# MLintro-HW-Notes-Projects

> **Special Notes**
> * This doc contains the illustrations for the notebooks (notes of mine), but it's still RECOMMENDED to read teacher's OFFICIAL NOTES as it contains more detailed and explained information
> * Most of the materials are come from <a href='https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/'>Udemy python for DS and ML bootcamp</a>. Please refer to its term of service and course behavior rule when you want to use anything from this repo.

<hr>

### s15


### s16-Bias Variance Trade-off-Notes
- bias variance trade-off definition & significance
- varaince & bias definition, and their relationships
- overfit & underfit
- causes of high bias / variance
- how to reduce variance in a model


### s17-Logistic-Regression-theory-Notes
- logistic regression
- pandas.DataFrame.isnull and seaborn.heatmap to clean the data with missing values
- use get_dummies to clean the data 
- use classification_report/confusion matrix to evaluate the model (first)
- how to increase precision / recall / accuracy?


### s18-K-Nearest-Neighbors-Notes
- KNN Classification definition, pros/cons, how it works
- use of StandardScaler to standarlize the data 
- use of elbow method to determine the optimal k value for KNN classification
- train, evaluate the model


### s19-Decision-Trees-and-Random-Forests-Notes
- Decision Tree / Random Forest Classifier definition, when to use, how they work
- Decision Tree concepts. 
- Random Forest: Pros/Cons, when to use...
- specify parameter n_estimator to specify number of trees
- POST: <a href='https://medium.com/@josemarcialportilla/enchanted-random-forest-b08d418cb411#.hh7n1co54'>random forest / decision tree explained by Jose</a >


### s20-Support-Vector-Machines-Notes
- Support Vector Machine definition, when to use, how they work, concepts(regression analysis, support vectors, hyperplane)
- Kernal Trick
- Breast_cacer dataset from sklearn
- **Grid Search method**: takes a dictionary object and searches the best combination of parameters values by inspecting the cross-validation.
- PROJECT: using Iris dataset from sklearn to classify flowers.


### s21-K-Means-Clustering-Notes
- KMeans definition (*kw. Unsupervised, cluster, centroid, elbow method*) when to use, how works, how to use
- make_blobs method from sklearn.datasets (generate data in clusters with 'labels')
- plt.subplot to compare results from dataset and kmeans results
- PROJECT: using Real college dataset (generate clusters and) to predict whether is private. (kw. sns.FacetGrid)


### s22-Principal-Component-Analysis-Notes
- PCA's definition, (*kw. Unsupervised, data analysis technique, interrelationships of vairables, factor analysis, dimension reduction*) how to use, when to use
- Get PCA's components
- REAPPEAR: StandardScaler method and breast_cancer dataset
- NO PROJECT, reading teacher's notes is recommended 


### s23-Recommender-Systems-Notes
- Recommender System's catogories, definitions (*kw. Content-Based, Collaboritive-Filtering, complex*), how to use, when to use
- pandas.DataFrame.pivot_table: to organize the data from DataFrame
- pandas.DataFrame.corrwith: get the correlation(0-1) between two DataFrames
- REAPPEAR: pandas merge, groupby, sort_values, jointplot...
- NO PROJECT, also reading teacher's notes is recommended (advanced RS)




