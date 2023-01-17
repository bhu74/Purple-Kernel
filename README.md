# Purple-Kernel Seeds Prediction

A set of images of normal seeds are provided. In 24 hours, some of these seeds start to 
develop purple coloration. Images of the seeds after 24 hours are also provided. 
About 173 pairs of Images of seeds taken on day 0 and 24 hours later are provided. The Day 
0 images are of normal seeds. The Day 1 images shows seeds after 24 hours. Some seeds 
are normal while some seeds have developed a purple tint. 
The purpose of this challenge is to use these images and propose solutions to predict the 
seeds that could turn purple.

## Solution
The proposed solution for this challenge involves using digital image analysis and machine 
learning techniques to develop the required algorithm.
Image analysis techniques are used to extract morphological (seed shape) information (such 
as length, width, area, etc) and truth values (turned purple or not). 
As the requirement is to predict if the seeds turn purple or not, it is a binary classification 
problem. Suitable binary classification algorithms are applied on the seeds data extracted and 
applied to unseen/test seeds images for prediction.

Steps to develop the prediction algorithm 
1. Seeds Data preparation 
    * Image Analysis and extraction of seeds information 
    * Feature Engineering
    * Data Preparation for modelling
2. Develop prediction model and train on training data 
3. Fit model to test data, make predictions and summarize results
