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
What is the right sequence of steps while building a random forest? <br>
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
