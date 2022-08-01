# SyriaTel Company Churn Analysis and Modelling
<img src=images/telecom2.png>

## Introduction
<p> Syrial is a telecommunicatioon company that aims at optimizing its operation by reducing the amount of money 
spend on customers who don't stick to the company for long by using machine learning and finding the predictable 
patterns for such customers</p>

## Business Understanding
<p>Our stakeholder will be the SyrialTel telecom Company. The purpose of this project is to provide the Syrial with valuable insight regarding the factors that most contribute to a customer churning , as well as use predictive model that can be used to make recommendations to the company in order to help reduce the amount of money spend wasted on customers who don't stick for long.</p>

##  Objectives
<li> To do analysis and find patterns between customers who churn and those who don't </li>
<li> To build a Machine Learning prediction model for classifing the churn of the Syrial Company </li>
<li> To use iterative modelling to find the best model with the highest classification accuracy </li>

## Data Understanding
<p> The data for this project comes from SyrialTelecom customer churn dataset </p>
<p> Data/bigml_59c28831336c6604c800002a.csv </p>

## Modelling 
<p> Different Modelling algorithms were used iteratively to find the best: </P>
<li> Logistic Regression </li>
<li> Decision tree </li>
<li> Random Forest </li>
<li> Gradient Boosting </li>
<li> Stacking </li><br>
<p> Here we created baseline model and progressed iteratively tuning the different hyperparameters for the different modelling algorithms and 
using GridSearch to find the best paramaters for each model</p>

## Conclusion
<p> The final model picked was the Random forest model 1 which had the highest metrics of :
 <li>Classification Accuracy  : 93% </li>
 <li>Classification recall    : 73% </li>
 <li>Classification F1 score  : 74% </li>
 <li>Classification precision : 75% </li>
</p>
<p> This model had a very high classification accuracy of 93% and also it had a balance in the other evaluating metrics above 70% for recall , 
F1 score and precision </p>
