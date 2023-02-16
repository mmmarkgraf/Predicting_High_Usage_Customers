# Predicting_High_Usage_Customers
The purpose of this script is to predict if a user will be a 'adopted user' of a software program developed by Relax Inc., who "makes productivity and project management software that's popular with both individuals and teams".

Adopted User = "a user who has logged into the product on three separate days in at least one seven day period"

The resulting models generated a predictive accuracy of ~98% or ~86% depending on what variables was included in the input dataset. If the total number of times a user logged into the program was included, then the model had a predictive accuracy of ~98%. However, if the that variable was not included, then the model had a accuracy of ~86%. See PDF write-up for conclusions.

The methods used in this are Data Manipulation, Data Wrangling, and Machine Learning with Random Forest using Scikit-Learn/Sklearn. Because of the high performance of the random forest models, no other models were created.

Required Files Before Running:
- takehome_users.csv
- takehome_user_engagement.csv

These must be in the same folder as this script to run correctly. Else, change the filepaths to direct to these files.
