# Open-Asteroid
Dataset about the most updated asteroids along with their updated features

Goal: 
Getting the diameter of an asteroid from the other data given about that asteroid, in other words supervised regression with the target being  log(𝑑𝑖𝑎𝑚𝑒𝑡𝑒𝑟)
The metric used during testing will be the  𝑅2-score.

How:

Step 1: Cleaning and preparing the data

Step 2: Train-test splitting of the data, and then normalizing (standard) using the test dataframe.

Step 3: Trying different regression algorithms-  
        - Linear Regression 
        - Elastic Net 
        - Decision Tree 
        - Random Forest
        - XGBoost
        - SVM
        - Neural Network

Step 4: Selecting the best algorithm

Extra: Since NASA's own estimator uses  𝐻 and  𝑎𝑙𝑏𝑒𝑑𝑜 to calculate the diameter, I decided to drop those to add difficulty and have less linearity in problem to solve.
