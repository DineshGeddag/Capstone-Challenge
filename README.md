# Capstone-Challenge

# Starbucks Capstone Challenge: Using Starbucks app user data to predict effective offers

# Blogpost
[Please click here to refer my blog post](https://dineshgedda.medium.com/star-bucks-capstone-8e695f4ad250)

# Installation
This repository was written Python , and requires the following Python packages: 
pandas, numpy,  sklearn, matplotlib,DecisionTreeClassifier,RandomForestClassifier,f1_score, GridserachCV.

# Project Motivation
  In this model development I have used two business problem statements
    * What are the main factors that defines the usage of offers by customers
    * Probablity that the user will open and use the offer 
# Dataset Overview
  The data is contained in three files:

      portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
      profile.json - demographic data for each customer
      transcript.json - records for transactions, offers received, offers viewed, and offers completed
      
 # Summary
    Among all tenure of member is the higest predictor of the effectiveness of an offer.
    
     # Question 1:
              Among all tenure of member is the higest predictor of the effectiveness of an offer.

              One good common point while in 3 model preperation tenure of member, income and age are top 3 factors on prediction.

              BOGO and discount are quiet un balanced compared to information with top 3 features.
              
     # Question 2:
              By the end of 3 model preperations I could say that Bogo and discount are performed better than 80% which is quiet and acceptable business criteria.
              BOGO (82.87%)
              Discount (87.38%)

Meanwhile, for BOGO and discount models, I am quite happy with the 80% and above accuracy, as in a business setting that would be acceptable to show offers to people, even if the model misclassifies a few, the overall revenue increase might justify the few mistakes.
