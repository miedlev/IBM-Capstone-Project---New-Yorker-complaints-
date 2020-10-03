### IBM-Capstone-Project - 311 complaint dataset

### 1. My Conclusion Analysis Report - Jupyter Notebook & IBM Watson
* [311 complaint dataset](https://UnimportantCoolProfessional.saeyoonyoon.repl.co)
* [Data Visualization Image](https://github.com/miedlev/kaggle---San-Francisco-Crime-Classfication/tree/main/Image)


### 2. About Data : Using Dataset 
* This dataset is available at (https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9). You can download part of this data by using SODA API.

Download only the data that is related to the Department of Housing Preservation and Development. Also, restrict your data to the limited number of fields. Otherwise, your data size will be unnecessarily large, and it might not work in the Watson Studio environment. Too much data can also be very slow to process and analyze.


### 3. Process Introduction :
It is a task of 'IBM Data Science and Machine Learning Capstone Project' and conducts a Python-based analysis. 

**[My focusing was on]** 
1. EDA - Focusing on dependent variable
2. Column fix, revise
3. One - Hot - Encoding
4. Feature engineering(Address, Datetime)
5. stats / delete of data for accurancy
6. Hold-out Validation 
7. StandardScaler process
8. Ensemble Model Selection(GradientBoostingClassifier)
9. classification_report
10. 'log_loss' metrics
11. hyperparameter Tuning 
12. classification_report

**[Dependencies & Tech]:**
* [IPython](http://ipython.org/)
* [NumPy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [SciKit-Learn](http://scikit-learn.org/stable/)
* [SciPy](http://www.scipy.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Matplotlib](http://matplotlib.org/)
* [Folium](https://pypi.org/project/folium/)
* [StatsModels](http://statsmodels.sourceforge.net/)
* [LightGBM](https://lightgbm.readthedocs.io/en/latest/)


### 4. IBM Data Science and Machine Learning Capstone Project
The people of New Yorker use the 311 system to report complaints about the non-emergency problems to local authorities. Various agencies in New York are assigned these problems. The Department of Housing Preservation and Development of New York City is the agency that processes 311 complaints that are related to housing and buildings.

In the last few years, the number of 311 complaints coming to the Department of Housing Preservation and Development has increased significantly. Although these complaints are not necessarily urgent, the large volume of complaints and the sudden increase is impacting the overall efficiency of operations of the agency.

Therefore, the Department of Housing Preservation and Development has approached your organization to help them manage the large volume of 311 complaints they are receiving every year.

The agency needs answers to several questions. The answers to those questions must be supported by data and analytics. These are their questions:

1. Which type of complaint should the Department of Housing Preservation and Development of New York City focus on first?

2. Should the Department of Housing Preservation and Development of New York City focus on any particular set of boroughs, ZIP codes, or street (where the complaints are severe) for the specific type of complaints you identified in response to Question 1?

3. Does the Complaint Type that you identified in response to question 1 have an obvious relationship with any particular characteristic or characteristics of the houses or buildings? And can a predictive model be built for a future prediction of the possibility of complaints of the type that you have identified in response to question 1?
