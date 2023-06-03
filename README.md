# World_Cup_Analysis
Summaries, analysis, and predictions for 2022 World Cup using this dataset: https://www.kaggle.com/datasets/brenda89/fifa-world-cup-2022.

Repository includes 3 files --

World_Cup_Presentation: .pdf file is a presentation that brings together summary figures and regression model. Was presented in my MGSC310: Statistical Models for Business Analytics (Introduction to Machine Learning) class, taken in Argyros School of Business and Economics at Chapman University.

World_Cup_Summary: RMarkdown file that includes summary statistics from a dataset that included interesting data that I wanted to show which was not included in my dataset. 

TO VIEW THIS KNITTED HTML FILE (INCLUDES GRAPHS AND OUTPUTS): https://htmlpreview.github.io/?https://github.com/c2bs/WorldCupAnalysis/blob/main/World_Cup_Summary.html 

World_Cup_Summary_and_Predictions: RMarkdown file that also includes summary statistics along with a classification (logistic regression) prediction model of the teams left in the Round of 16. This prediction model uses different variables to predict team_win (whether or not the team wins). After exponentiating coefficients, I found that the country did not have a large impact on team_win because countries play teams with varying levels of skill, and the amount of games won does not determine skill. I found that variables goalkeeper_score, defense_rating, midfield_rating, and offense_rating truly provides the best predictions to determine a win. Mutated a new variable, model_score, that multiplies each rating by the models exponentiated score for defense, offense, etc.. Model determined France, Brazil, and Spain took the top 3 spots in chances to win the 2022 World Cup. Finally, scored my model by area under the curve and found that results were not strong (0.66 - training, 0.73 - testing), likely due to not having enough data. My reasoning for not using the entire dataset for this model and just matches played in World Cup and World Cup Qualification was due to of my knowledge of soccer/football being that teams play most competitive in these types of matches.   

TO VIEW THIS KNITTED HTML FILE (INCLUDES GRAPHS AND OUTPUTS): https://htmlpreview.github.io/?https://github.com/c2bs/WorldCupAnalysis/blob/main/World_Cup_Summary_and_Predictions.html
