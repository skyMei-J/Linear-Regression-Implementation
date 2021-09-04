# Linear-Regression-Implementation with handcrafted inverse (using LU decompositino)

Implement Linear Regression and Logistic Regression algorithms.

find the best fitting line on the data with the matrix operations which are written by myself.
## Input Parameter
### (a) A set of data points(comma seperated :x,y):

### (b) The number of polynomial bases n:
For example, if the number of polynomial bases is 3, then we are going to find
the curve that fits the data points by ax2 + bx1 + cx0 = y


I implement the formula above with my handcrafted inverse function (used LU decomposition) to find the inverse matrix and plot the result including points and the fitting line.
### Inverse Matrix:
![image](https://github.com/skyMei-J/Image/blob/main/linear%20regression/截圖%202021-09-04%20下午5.27.07.png)
# Logistic Regression Implementation (handcrafted)
Both L2-norm and cross entropy will do gradient descent to find the optimal result
Below is the reference function
![image](https://github.com/skyMei-J/Image/blob/main/linear%20regression/截圖%202021-09-04%20下午5.27.34.png)

![image](https://github.com/skyMei-J/Image/blob/main/linear%20regression/截圖%202021-09-04%20下午5.27.42.png)
![image](https://github.com/skyMei-J/Image/blob/main/linear%20regression/截圖%202021-09-04%20下午5.28.24.png)

## The steps of logistic regression:
i. We have some (x,y) points, we might make it become a vector like [x,y,1]. 
The last one will be the bias.  

ii. Then it will do dot product with our w, which is a 3 by 1 vector here.  
Then put them into the sigmoid function, it will give you a
result between 0 and 1.  

iii. Now you have the target y and the predict result y’, just use two different error function doing the gradient descent, both two error
function’s result is given.  

iv. Until your loss smaller than your threshold, you get the w.  


![image](https://github.com/skyMei-J/Image/blob/main/linear%20regression/截圖%202021-09-04%20下午5.28.16.png)
![image](https://github.com/skyMei-J/Image/blob/main/linear%20regression/截圖%202021-09-04%20下午5.28.31.png)
