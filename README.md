# nlp-on-e-commerce-reviews
Dataset investigation and testing of multiple ML approaches from supervised to unsupervised learning on the versatile Women's E-Commerce Clothing Reviews dataset released from Kaggle. Main focus on NLP.

## Files in this repository:

* Notebooks

  * DataExploration.ipynb: Run this first to get an understanding about the data.

  * SupervisedLearning.ipynb: Check this out if you are interested in supervised learning and AutoML.

  * UnsupervisedLearning_NLP.ipynb: This notebook has an implementation for finding topics from review texts using Latent Dirichlet Allocation (LDA)

* Project summary.pptx is a powerpoint file collecting together all the results from the three notebooks.

## How to

Notebooks were run on Google Colab with Python version: 3.7.10
package versions:
pandas==1.2.5
numpy==1.21.0
spacy==2.2.4
en-core-web-sm==2.2.5
gensim==3.6.0
nltk==3.2.5
pyLDAvis==3.3.1
scikit-learn==0.22.2.post1 

The dataset can be downloaded from https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews

## The Kaggle description of the data:

Welcome. This is a Women’s Clothing E-Commerce dataset revolving around the reviews written by customers. Its nine supportive features offer a great environment to parse out the text through its multiple dimensions. Because this is real commercial data, it has been anonymized, and references to the company in the review text and body have been replaced with “retailer”.

Content

This dataset includes 23486 rows and 10 feature variables. Each row corresponds to a customer review, and includes the variables:

Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.
Age: Positive Integer variable of the reviewers age.
Title: String variable for the title of the review.
Review Text: String variable for the review body.
Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.
Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.
Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.
Division Name: Categorical name of the product high level division.
Department Name: Categorical name of the product department name.
Class Name: Categorical name of the product class name.

## Results

Check out the presentation https://github.com/annilea/nlp-on-e-commerce-reviews/blob/main/Project%20summary.pptx
Topics found:
<img width="446" alt="image" src="https://user-images.githubusercontent.com/84013721/125407097-38bcf400-e3c2-11eb-9bb9-97a4bb281f2f.png">

where topic_names ={0:'dresses and fabric', 1:'wearing and season', 2:'tops and tees', 3:'bottoms', 4:'love the style', 5:'size’}



