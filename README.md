# E-M-algorithm
Code to manually calculate a random intercept model using the E-M algorithm.


E-step:

Set a priori values for parameters: intercep, residual variance and covariance matrix of a dependent variiable.

M-step:

Updating the parameter estimates (e.g., intercept, variance, covariance matrix) to maximize the likelihood function.
These new parameter estimates are then used in the next iteration of the E-step.



The pictures below show the convergence of the intercept value. The a priori value was set to zero. 
The x-axis shows the iteration step, and the y-axis shows the eta value after each M-step of the algorithm.
![image](https://github.com/user-attachments/assets/3fe551e8-baa7-4756-9e8a-e5a5225bc5d9)

