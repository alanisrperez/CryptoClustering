# Module 19 Challenge - Unsupervised Machine Learning

Background
------------------------------
In this challenge, you'll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Prepare the Data
------------------------------
- Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
- Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
-- The first five rows of the scaled DataFrame should appear as follows:

[image of scaled df]

Find the Best Value for k Using the Scaled DataFrame
------------------------------
Use the elbow method to find the best value for k using the following steps:
1. Create a list with the number of k values from 1 to 11.
2. Create an empty list to store the inertia values.
Create a for loop to compute the inertia with each possible value of k.
3. Create a dictionary with the data to plot the elbow curve.
4. Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
5. Answer the following question in your notebook: What is the best value for k?