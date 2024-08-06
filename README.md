# STAT-4630-Project

## Overview

This report presents the findings of our analysis of NBA player statistics and their relationship to salaries and starting roles. We used various statistical methods including regression and classification techniques to identify key factors influencing player compensation and starting status. The analysis focused on NBA player statistics and their impact on salaries and starting roles, utilizing regression and classification methods to identify key factors. Data was obtained from Kaggle, combining salary information from Hoopshype and statistics from Basketball Reference.

## Business Problem

The main business problems addressed were identifying which player skills translate to higher salaries and determining what stats lead to players being overall starters. The goal was to provide insights for team managers, coaches, and players to make informed decisions. 

## Data Preprocessing and Methods Used

In data preprocessing and analysis, We created new variables like Starter and Position Group, addressed multicollinearity by removing redundant variables, log-transformed the Salary variable, and conducted exploratory data analysis (EDA) using correlation matrices, boxplots, and scatter plots.

The methods used included regression analysis (Lasso Regression, Recursive Binary Splitting, and Random Forests) and classification analysis (Logistic Regression, Pruned Classification Trees, and Random Forests). Key findings from the salary prediction analysis revealed that the most important factors were Age, Minutes Played per Game, Value Over Replacement, Steals per Game, and Field Goals per Game. For starter classification, key predictors were identified as Turnovers per Game, Free Throw Percentage, Steals per Game, and Blocks per Game. In terms of model performance, Random Forests performed best for regression (lowest test MSE), while Logistic Regression showed the best overall performance for classification.

## Recommendations

Based on these findings, we made several recommendations. For team managers, we suggested developing a comprehensive player valuation framework based on the key statistics identified and focusing scouting and analytics on these areas when evaluating prospects and current players. Players were advised to design training regimens focused on improving the key metrics identified and to track progress on these metrics, setting ambitious goals aligned with desired salary levels. For those aiming to be starters, the focus should be on reducing turnovers, increasing steals and blocks, and improving free throw percentage.
