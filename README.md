# CS211_Final_Project
CS211 Final Project Fall 2021

Our group consists of Preston Hunter and Alex Downs. The problem we are trying to solve is making a differentially private mechanism for returning the value which represents the x percentile value of a numerical dataset, in our case the height of basketball players in inches. We also seek to show disparity in heights from day-to-day vs a professional setting which selects for height. Our approach will consist of sample and aggregate, splitting the dataset into k chunks, and calculating percentile values on the chunks, and then returning the average value for the x percentile over all chunks. We will then analyze the accuracy of our approach, comparing it to the true values and assessing its over all usefulness. 

Dataset: https://www.kaggle.com/wyattowalsh/basketball
