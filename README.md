# Market Analytics: Google Playstore Preference 
Hi all, this is a Data Analytics Project ! - Market Analytics with Machine Learning methodologies.


### Project Objective

* The purpose of this project is to establish **Exploratory Data Analysis (EDA)** and apply **Machine Learning methodology** for Market Analytics. At the same time, I try to uncover the critical factors for user preferences of Google PlayStore.


### Methods Used

* Inferential Statistics
* Data Wrangling
* Data Visualization
* Sentiment Analysis
* Machine Learning
* Predictive Modeling


### Algorithm Used

- Machine Learning: 
  - Linear Regression (LR)
  - Support Vector Machines (SVM)
  - Random Forest Regression (RFR)
  - Random Forest Classification (RFC)


### Technologies and Packages Used

* Python, Jupyter Notebook, Tableau
* Numpy, Pandas, Statsmodels.api
* Sklearn, Matplotlib, Seaborn


### Project Description

* Motivation:

  - Since Google Playstore is becoming larger and more competitive, the number of applications available in the Google Playstore has increased dramatically. Therefore, in order to seize this great business opportunity, more and more developers are trying to figure out which factors are critical to the users.  
  
  
* Data and Scope:

  - The dataset is downloaded from kaggle and it is also an open competition for participants who are willing to work on this project. The data size is around 10000 with meaningless and missing values. Thus, data cleansing is the first and the most important step to overcome in order to truly understand the importance weights for each variable.  
  
  
* Methodology Approach:

  - Data Cleansing:
    1. Label each **Category** and **Genres** with their unique variables and make sure the results are representative. 
    2. Convert every letter **M** and **k** in Size column to numerical numbers and replace the originals with new values.
    3. Split the meaningless symbols for each variable in the column and that's pretty much for data cleansing!
  
  - Modeling Approach: 
    1. Set factor **Rating** to Y and the rest factors to X.
    2. Split the dataset into 80% training data and 20% testing data.
    3. Apply Linear Regression model to detect the relationships between **Rating** and each factor.
    4. Apply Support Vector Machines model to predict the new **Rating** values.
    5. Apply Random Forest Regression and Classification to measure the importance weights for each variable.

  
### Conclusion:

  - Based on the related marketing research, it presents that **UserReviews** is the most influential factor for users to install the apps from Google PlayStore. However, there are something interesting when visualizing with EDA. For instance, I find out that rating score grows higher when the size of the app becomes smaller. That is to say, even though the average app rating is around 4.2 which is quite high, developers can still work on the **SIZE** issue to get better rating scores. 
  
  - In addition, since the type of social entertainments and games are the most popular apps above all, developers can focus on those developments. According to the results of sentimental analysis, it is obvious that most users have positive attitudes toward **Game, Health & Fitness and Travle & Local apps**.   
  
  - Furthermore, I can distinguish that **Linear Regression** model is robust and persuasive because R-squared is around 85%. Also, **Category, Type and Content Rating** are the three top influential factors in this model and they all have positive relations toward **Rating** factor. 
  
  - Moreover, the accuracy of **Random Forest Classification** model is around 76% which is a little bit lower than the Linear Regression model, but the results still remain strong and convincing since **Reviews and Size** are the top two meaningful factors from the results. On the other hand, **Price and Type** are less important in this classification analysis. 
  
  - In general, it is hard and unfair to say which model has a better performance since their **accuracies are pretty high**. Therefore, developers should choose wisely depending on their own purposes when applying the data with different kinds of machine learning models. 
  
  
  
