# sentiment-analysis
dataset used - amazon fine food reviews available on [Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews)

dataset details:
- reviews from Oct 1999 - Oct 2012
- 568,454 reviews
- 256,059 users
- 74,258 products
- 260 users with > 50 reviews

parameter in the dataset:
- Id - review number 
- ProductId - unique identifier for the product
- UserId - unique identifier for the user
- ProfileName - profile name of the user
- HelpfulnessNumerator - number of users who found the review helpful
- HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not 
- Score - rating between 1 and 5
- Time - timestamp
- Summary - summary of the review
- Text - text of the review

what each file does:
- read_data.ipynb reads the data and does the basic data cleaning 
