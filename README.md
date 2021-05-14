# Mining_Of_Massive_Datasets

Synthetic Dataset Creation
------------------------------
1. Use a synthetic data set for the classiﬁcation task. Generate two classes with 20 features each. 
Each class is given by a multivariate Gaussian distribution, with both classes sharing the same covariance matrix.
Ensure that the covariance matrix is not spherical, i.e., that it is not a diagonal matrix, with all the diagonal entries being the same. 
Generate 2000 examples for each class. Choose the centroids for the classes close enough so that there is some overlap in the classes. 
Clearly specify the details of the parameters used for the data generation. 
Randomly pick 30% of each class (i.e., 600 data points per class) as a test set, and train the classiﬁers on the remaining 70% data When you report performance results, it should be on the left out 30%. 
Call this dataset as DS1.


Linear Classiﬁcation
-------------------------------
2. For DS1, learn a linear classiﬁer by using regression on indicator variable. 
Report the best ﬁt accuracy, precision, recall and F-measure achieved by the classiﬁer, along with the coeﬃcients learnt.


k-NN classiﬁer
-------------------------
3. For DS1, use k-NN to learn a classiﬁer. 
Repeat the experiment for diﬀerent values of k and report the performance for each value. 
Technically this is not a linear classiﬁer, but we want you to appreciate how powerful linear classiﬁers can be.
• Do you do better than regression on indicator variables or worse? • Are there particular values of k which perform better? 
• Report the best ﬁt accuracy, precision, recall and f-measure achieved by this classiﬁer.


Data Imputation
---------------------
4. For the regression tasks, you will use the Communities and Crime (CandC) Data Set from the UCI repository (http://archive.ics.uci.edu/ml/datasets/Communities+ and+Crime). 
This is a real-life data set and as such would not have the nice properties that we expect. 
Your ﬁrst job is to make this dataset usable, by ﬁlling in all the missing values. 
• Use the sample mean of the missing attribute. Is this is a good choice? 
• What else might you use? If you have a better method, describe it, and you may use it for ﬁlling in the missing data. Turn in the completed data set.


Linear Regression
---------------------
5. Fit the CandC data using linear regression. 
Report the residual error of the best ﬁt achieved on test data, averaged over 5 diﬀerent 80-20 splits, along with the coeﬃcients learnt.


All of these have been solved in Jupyter Notebook files added in this repository.
Also adding a report to describe the solutions for better understanding of users.
