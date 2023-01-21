<h2 align="center">Total Questions : 30 <br>           
Correct Answers : 26 <br>            
Incorrect Answers : 04 <br>                             
Marks : 56/66</h2>
<h1 align="center">Score : 85%</h1>
<br>

## Question 1 
<p align="right">Multiple Choice Question (2/2 Marks) </p>
Assuming everything else remains the same, which of the following is the right statement about the predictions from the decision tree in comparison with predictions from random forest?

- [ ] A. Lower Variance, Lower Bias
- [ ] B. Lower Variance, Higher Bias
- [ ] C. Higher Variance, Higher Bias
- [x] D. Lower Bias, Higher Variance

**Solution :-**   
Correct Answer : D  
Your Answer : D

**Explanation :-**  
The predicted values in decision trees have low Bias but high variance when compared to random forests. This is because random forest attempts to reduce variance by bootstrap aggregation.
<br>

## Question 2
<p align="right">Multiple Choice Question (1/1 Marks) </p>
Suppose list1 is [2, 33, 222, 14, 251]. What is list1[:-1]?

- [x] A. [2, 33, 222, 14]
- [ ] B. Error
- [ ] C. 25
- [ ] D. [25, 14, 222, 33, 21]

**Solution :-**   
Correct answer : A  
Your answer : A 

**Explanation :-**    
The index -1 represents the last element, as the stopping condition for any index is that "STOP -1" the last element is not included.
  
## Question 3     
<p align="right">Multiple choice question (4/4 Marks) </p>  
To reduce under fitting of a random forest model, which of the following methods can be used?   

- [ ] A. Increase minimum sample leat value   
- [x] B.Increase depth of trees     
- [ ] C. Increase the value of minimum samples to split   
- [ ] D. Increase the number of samples     

**Solution :-**   
Correct answer : B    
Your answer : B 

**Explanation :-**    
Only option B is correct, because Increasing the number of samples for a leaf will reduce the depth of a tree, indirectly increasing underfitting.  
B: Increasing depth will definitely decrease and help reduce underfitting.  
C: Increasing the number of samples considered to split will have no effect, as the same information will be given to the
model.  


## Question 4 
<p align="right">Multiple Choice Question (4/4 Marks)</p>   
In a random forest, which of the following is randomly selected?  

- [ ] A. Number of decision trees.      
- [x] B. Features to be taken into account when building a tree.    
- [x] C. Samples to be given to train individual tree in a forest.    

**Solution :-**   
Correct answer : B, C 
Your answer : B, C    

**Explanation :-**  
Option A is incorrect because, number of trees has to be decided when building a tree. It is not random.  

## Question 5<br>
<p align="right">Multiple Choice Question (2/2 Marks)</p>     
Which of the following are the disadvantages of the decision tree algorithm?      

- [ ] A. Decision tree is not easy to interpret   
- [x] B. Decision tree is not a very stable algorithm     
- [x] C. Decision tree will overfit the data easily if it perfectly memorizes it    
- [ ] D. Decision tree does not have any disadvantages    

**Solution :-**<br>
Correct answer : B, C<br>
Your answer : B, C<br>

**Explanation :-**<br>
Option A is false, as decision tree are very easy to interpret.<br>
Option B is true, as decision tree are high unstable models.<br>
Option C is true, as the decision tree also tries to memorize noise.<br>



## Question 6<br>
<p align="right">Multiple Choice Question (4/4 Marks)</p>     
Which of the following statement (s) is/are true for Gradient Descent (GD) and Stochastic Gradient Descent (SGD)?   

- [x] A. In GD and seD, you update a set of parameters in an iterative manner to minimize the error function.  
- [ ] B. In SGD, you have to run through all the samples in your training set for a single update of a parameter in each iteration.   
- [ ] C. In GD, you either use the entire data or a subset of training data to update a parameter in each iteration  

**Solution :-**     
Correct answer : A    
Our answer : A

**Explanation :-**      
In SGD for each iteration you cho0se the batch which generally contains the random sample of data But in case of GD each iteration contains all of the training observations. 



## Question 7<br>
<p align="right">Multiple Choice Question (1/1 Marks)</p>   
Which of the following is a decision boundary of the decision tree? 

![image](https://user-images.githubusercontent.com/74552274/213859741-77843f20-a1f8-4b44-81aa-dfb8e955e0e9.png)
- [ ] A. B      
- [ ] B. A      
- [x] C. D    
- [ ] D. C    

**Solution :-**     
Correct answer : C    
Your answer: C   

**Explanation :-**    
Decision boundaries of decision trees are always perpendicular to the X and Y axis.



## Question 8<br>
<p align="right">Multiple Choice Question (1/1 Marks)</p>     
Given 1000 observations, minimum observation required to split a node equals to 200 and minimum leaf size equals to 300 then what could be the maximum depth of a decision tree?        

- [ ] A. 1    
- [x] B. 2    
- [ ] C. 3    
- [ ] D. 4  

**Solution :-**   
Correct answer: B     
Your answer : B 

**Explanation :-**  
The leaf nodes will be as follows for minimum observation to split is 200 and minimum leaf size is 300.   
![image](https://user-images.githubusercontent.com/74552274/213860181-79a6eb8a-5f85-4d5f-b5f5-f1e26f0c5e8c.png)       
So only after 2 splits, the tree is created. Therefore, depth is 2.



## Question 9<br>
<p align="right">Multiple Choice Question (2/2 Marks)</p>
Consider a classification tree for whether a person watches 'Game of Thrones' based on features like age, gender, qualification, and salary. Is it possible to have the following leaf node?    

![image](https://user-images.githubusercontent.com/74552274/213860399-531624c8-281b-4f1c-a021-ae518bfe9bc7.png)     

- [x] A. Yes
- [ ] B. No
- [ ] C. Can't say
- [ ] D. Incomplete Data

**Solution :-**       
Correct answer : A    
Your answer : A     

**Explanation :-**  
A node can be split on a feature, as long as it gives information after the split. So even though the above split does not reduce the classification error, it improves the Gini index and the cross-entropy.


## Question 10
<p align="right">Arrange in order (2/2 Marks)</p>
What is the right sequence of steps while building a random forest?   

1. Create bootstrap samples.  
2. Build a decision tree on every sample.   
3. Use feature sampling for each split in the decision tree.  
4. Aggregate all decision trees.    

**Solution :-**
That's right!


## Question 11
<p align="right">Multiple Choice Question (2/2 Marks)</p>
Which of the following corresponds to the properties of clusters?

- [ ] A. Points within the same cluster should be as different from each other as possible.       
- [x] B. Points within the same cluster should be as similar to each other as possible.       
- [x] C. Points in different clusters should be as different from each other as possible.       
- [ ] D. Points in ditferent clusters should be as Similar to each other as possible.         

**Solution :-**     
Correct answer : B, C   
Your answer : B, C    


## Question 12
<p align="right">Multiple Choice Question (4/4 Marks)</p>
If two variables V1 and V2, are used for clustering. Which of the following are true for K means clustering with k=3?   

**Statement 1:** if v1 and v2 have a correlation of 1, the cluster centroids will be in a straight line.  
**Statement 2:** if v1 and v2 have a correlation of 0, the cluster centroids will be in a straight line.  

- [x] A. Statement 1
- [ ] B. Statement 2
- [ ] C. Both the statements are incorrect

**Solution :-**   
Correct answer : A    
Your answer : A   

**Explanation :-**  
If the correlation between the variables V1 and V2 is 1, then all the data points will be in a straight line. Hence, all the three cluster centroids will form a straight line as well. 


## Ouestion 13
<p align="right">Multiple Choice Question (1/1 Marks)</p>
Which of the following hyper parameter (s), when increased may cause random forest to over fit the data?  

- [ ] A. Number of trees
- [x] B. Depth of tree
- [ ] C. Learning rate

**Solution :-**     
Correct answer : B  
Your answer: B    

**Explanation :-**    
Usually, if we increase the depth of the tree it will cause overfitting. Learning rate is not a hyperparameter in random forest. Increase in the number of trees will cause under fitting.


## Question 14
<p align="right">Multiple Choice Question (4/4 Marks)</p>
Which of the following can be applied to get good results for the K-means algorithm corresponding to global minima? 

- [x] A. Try to run algorithm for different centroid initialization
- [x] B. Adjust number of iteration
- [x] C. Find out the optimal number of clusters

**Solution :-**       
Correct answer : A, B, C      
Your answer : A, B, C

**Explanation :-**  
All of these are standard practices that are used in order to obtain good clustering results.


## Question 15
<p align="right">Multiple Choice Question (0/4 Marks)</p>
In case of data points that are spread unevenly or have variable density what steps could be taken to form meaningful clusters?

- [x] A.Pertorm feature transtormation to change/even-out the density ot the points.
- [x] B.Form a higher number of clusters and then merge the clusters which are very close together to form a supercluster.
- [x] C. Remove the observations causing uneven density of data points.
- [x] D. Impute the values to torm unitorm density of data points.

**Solution :-**       
Correct answer : A, B     
Your answer : A, B, C, D  

**Explanation :-**      
When the data points are uneven in spread/density, feature transformation can be used to make them uniform in density to have meaningful clusters. Moreover, the smaller clusters too close to each other can be merged to form a supercluster, this method helps in clustering where the patch of data is sparse compared to other regions.


## Question 16
<p align="right">Multiple Choice Question (1/1 Marks)</p>
Imagine, you are working with XYZ and you want to develop a machine learning algorithm which predicts the number of views on the articles.        

Your analysis is based on features like author name, number of articles written by the same author on XYZ in the past and a few other features. Which of the following evaluation metrics would you choose in that case?

- [x] A. Mean Square Error
- [ ] B. Accuracy
- [ ] C. F1 Score
- [ ] D. Log loss

**Solution :-**     
Correct answer : A      
Your answer : A

**Explanation :-**    
You can think that the number of views of articles is the continuous target variable which falls under the regression problem. So, mean squared error will be used as an evaluation metrics.



## Question 17
<p align="right">Multiple Choice Question (4/4 Marks)</p>
Let's say, you are working with categorical feature(s) and you have not looked at the distribution of the categorical variable in the test data. You want to apply one hot encoding (OHE) on the categorical feature(s). What challenges you may face if you have applied OHE on a categorical variable of train dataset?

- [x] A. All categories of categorical variables are not present in the test dataset.
- [x] B. Frequency distribution of categories is different in the train as compared to the test dataset.
- [ ] C. Train and test always have the same distribution.

**Solution :-**     
Correct answer : A, B     
Your answer A, B    

**Explanation :-**    
The OHE will fail to encode the categories which are present in test but not in train, so it could be one of the main challenges while applying OHE. The challenge given in option B is also true as you need to be more careful while applying OHE if frequency distribution isn't the same in train and test.


## Question 18
<p align="right">Multiple Choice Question (1/1 Marks)</p>
Adding a non-important feature to a linear regression model may result in:

- [x] A. Increase in R-square
- [ ] B. Decrease in R-square

**Solution :-**     
Correct answer: A     
Your answer: A  

**Explanation :-**    
After adding a feature in feature space, whether that feature is important or unimportant features the R-squared always increases.


## Question 19
<p align="right">Multiple Choice Question (1/1 Marks)</p>
Which of the following techniques would perform better for reducing dimensions of a data set?

- [x] A. Removing columns which have too many missing values
- [ ] B. Removing columns which have high variance in data
- [ ] C. Removing columns with dissimilar data trends
- [ ] D. None of the above

**Solution :-**   
Correct answer: A     
Your answer : A     

**Explanation :-**    
If a column has too many missing values, (say 99%) then we can remove such columns.



## Question 20
<p align="right">Multiple Choice Question (0/1 Marks)</p>
Why do we perform exploratory data analysis?

- [x] A. To be able to draw valuable insights from the data.
- [ ] B. To interpret the ML model.
- [x] C. Sets stage for meaningful feature engineering
- [ ] D. Helps in advanced missing value imputation.

**Solution :-**     
Correct answer : A, C, D      
Your answer: A, C   


## Question 21
<p align="right">Multiple Choice Question (0/4 Marks)</p>
Which among the following would be the most preferred approach, considering that we have to minimize the number of features in a model while retaining as much model performance as possible. (compute power is restricted/limíted)?

- [x] A. Forward selection
- [ ] B. Backward elimination
- [ ] C. Randomly handpicking features
- [ ] D. All of above are equally preffered

**Solution :-**     
Correct answer : B    
Your answer: A    

**Explanation :-**      
Backward selection is most preferred as it will require least number of iterations to to converge to the optimum solution.


## Question 22
<p align="right">Multiple Choice Question (4/4 Marks)</p>
Suppose, you are given three variables X, Y and Z. The Pearson correlation coefficients for (X, Y), (Y, Z) and (X, Z) are C1, C2& C3 respectively.

Now, you have added 2 in all values of X (i.enew values become X+2), subtracted 2 from all values of Y (i.e. new values are Y-2) and Z remains the same. The new coefficients for (X,Y), (Y,Z) and (X,Z) are given by D1, D2 & D3 respectively.

How do the values of D1, D2 & D3 relate to C1, c2 & C3?

- [ ] A. D1= C1, D2 < C2, D3 > C3
- [ ] B. D1 C1, D2> c2, D3 > C3
- [ ] C. D1 = C1, D2 > C2, D3 < C3
- [x] D. D1- C1, D2 = C2, D3 = C3

**Solution :-**   
Correct answer : D    
Your answer : D     

**Explanation :-**      
Correlation between the features won't change if you add or subtract a value in the features.



## Question 23
<p align="right">Multiple Choice Question (1/1 Marks)</p>
Imagine, you are solving a classification problem with a highly imbalanced class. The majority class is observed 99% of times in the training data.

Your model has 99% accuracy after taking the predictions on test data. Which of the following is true in such a case?

- [x] A Accuracy metric is not a good idea for imbalanced class problems.
- [ ] B. Accuracy metric is a good idea tor imbalanced class problems.
- [x] C. Precision and recall metrics are good for imbalanced class problems.
- [ ] D. Precision and recall metrics arent good for imbalanced class problems.

**Solution :-**     
Correct answer : A, C    
Your answer : A, C    

**Explanation :-**
The data iS highly imbalanced, therefore accuracy is not a good metric. Moreover, we need to use precision, recall or F1-score which considers the skewness of the data.



## Question 24
<p align="right">Multiple Choice Question (0/1 Marks)</p>
With many groups in one categorical variable which is the preferred way to deal with it?

- [ ] A. Creating dummy
- [ ] B. Binning
- [x] C. One Hot encoding
- [ ] D. Dropping those variables

**Solution :-**   
Correct answer : B    
Your answer : C   

**Explanation :-**
The bin-counting scheme is a useful scheme for dealing with categorical variables having many categories.


## Question 25
<p align="right">Multiple Choice Question (1/1 Marks)</p>
Binning can be used only for:

- [x] A. Numerical variables
- [x] B.Categorical variables
- [ ] C. None of the abovee

**Solution :-**     
Correct answer : A, B   
Your answer: A, B     

**Explanation :-**
The bin-counting scheme can be implemented in case we have many categories for categorical variables because creating dummy can cause a curse of dimensionality. A numerical bin is preferred for getting insights at a broad level.


## Question 26
<p align="right">Multiple Choice Question (2/2 Marks)</p>
In the context of a merge function 'how' parameter selects the right choices?

- [x] A. left: use only keys from the left frame.
- [x] B. right: use only keys from the right frame
- [x] C. outer: use union of keys from both frames.
- [x] D. inner: use intersection of keys from both frames

**Solution :-**     
Correct answer : A, B, C, D   
Your answer : A, B, C, D    


## Question 27
<p align="right">Multiple Choice Question (2/2 Marks)</p>
A total predicted logit of O can be transformed to a probability of

- [ ] A. 0
- [x] B. 0.5
- [ ] C. 1
- [ ] D. 0.75

**Solution :-**   
Correct answer : B    
Your answer : B   

**Explanation :-**    
Putting the value of zero in logit function (1/(1+exp(-X) will give us the value 0.5 which can be confirmed from the figure as well.

![image](https://user-images.githubusercontent.com/74552274/213868087-70ce46dd-dc12-4d88-9142-3ec6a87d4e92.png)


## Question 28
<p align="right">Multiple Choice Question (1/1 Marks)</p>

