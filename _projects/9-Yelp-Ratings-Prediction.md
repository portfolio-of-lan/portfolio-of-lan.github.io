---
name: Yelp Rating Prediction using Sentiment Analysis
tools: [Python, Machine Learning]
image: 
description: A multi-task CNN model that performs both classification and regression tasks to predict Yelp ratings from review texts
# external_url: https://github.com/PuppyGummy/Yelp-Ratings-Prediction
---

# Yelp Rating Prediction using Sentiment Analysis

<p style="color:DarkGrey">
A course project for Artificial Intelligence
</p>


<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center"> 
Description
</h3>
<br>

On Yelp.com, customers can rate a business in a range of 1 to 5 stars, and they can also provide a review (in text format) explaining their experience. Other optional rating scores that the customers can provide include: useful, cool, funny. Each of these fields can also be rated on a scale of 1 to 5. 

This project aims to develop a sentiment analysis model that can predict any of the mentioned rating scores for a business on Yelp.com given the content of the review text. Specificly, star rating is considered as a classification task, while the other three rating scores are considered as regression tasks.

The data used in this project can be found [here](https://www.yelp.com/dataset). Please download the JSON file, and find `yelp_academic dataset_review.json`.

<br>

<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center">
About
</h3>
<br>

This is a course project for my Artificial Intelligence class. In this project, I:
- Processed 6,990,280 data entries, involving dataset splitting, handling of missing values, text preprocessing, as well as text tokenizing.
- Developed and trained a multi-task CNN text model, capable of classification and regression, to predict review scores from Yelp comments.
- Fine-tuned the model with random search and early-stopping.


<p class="text-center" style="color:DarkGrey">
---
</p>

<br>
<div class="text-center">
<a style="color:DarkGrey" href="https://github.com/PuppyGummy/Yelp-Ratings-Prediction">
view source code here
</a>
</div>