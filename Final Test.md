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
- [ ] D.[25, 14, 222, 33, 21]

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
Only option B is correct, because Increasing the number of samples for a leaf will reduce the depth of a tree, indirectly
increasing underfitting.  
B: Increasing depth will definitely decrease and help reduce underfitting.  
C: Increasing the number of samples considered to split will have no effect, as the same information will be given to the
model.  
