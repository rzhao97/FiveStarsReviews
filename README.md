<p align="right">
<img src="img/yelp-logo.png">
</p>

# FiveStarsReviews
**Ray Zhao**

### Table of Contents

* [Project Description](#description)
* [Data](#data)
* [Analysis](#analysis)
* [Processing of Reviews' Text](#NLP)
* [Model Comparison](#models)
* [Final Model Performance](#final)
* [Conclusion](#conclusion)

<a name="description"></a>
## Project Description

Yelp is a popular online directory of businesses that allows users to leave reviews and ratings ranging from 1 to 5 stars. The businesses can be filtered through many methods, such as restricting the type of business, location or price. The objective of this project is to look at the reviews for restaurants in Las Vegas, Nevada and predict if a review was given 5 stars.


<a name="data"></a>
## Data

#### Source:
* Original JSON datasets obtained from [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset). 
* The reviews dataset consists of 8 million reviews for businesses spread across 11 metropolitan cities.
* There are 1.5 million English reviews for restaurants in Las Vegas, Nevada.

#### Pipeline:
* .
* .
* .
* .

#### Cleaned Data:
* Dataset contains 1.5 million rows and ... features

| Features Name    | Description      | Datatype |
|:-----------------|:-----------------|----------|
| Business ID      |                  | str      |
| Review ID        |                  | str      |
| User ID          |                  | str      |
| Review Text      |                  | str      |
| Stars            |                  | int      |
| Funny            |                  | int      |
| Useful           |                  | int      |

| Word Count       |                  | int      |
| Language         |                  | str      |


<a name="analysis"></a>
## Analysis

### Exploratory Data Analysis

For the 7310 restaurants in Las Vegas, there are 1.5 million English reviews.

#### The class balance is as shown below:
<p align="center">
<img src="img/stars_ratio.png">
</p>
5 stars: 44.4%
Non 5 stars: 55.6%
* 4 stars: 22.8%
* 3 stars: 11.9%
* 2 stars: 8.4%
* 1 star: 12.4%

#### The Difference in Word Count
<p align="center">
<img src="img/word_count_plot.png">
</p>



<a name="NLP"></a>
## Processing of Reviews' Text

#### Example of Review:
<p align='center'>
<img src="images/five.png"> 
</p>
…
Example of Non-English Review:
…
Example of tokens:
...



<a name="models"></a>
## Model Comparison

**MODEL CHART HERE**
...
...
...

<p align='center'>
<img src="img/roc_curve.png">
</p>

<a name="final"></a>
## Final Model Performance

<p align="center">
<img src="img/roc_curve_final.png">
</p>

<a name="conclusion"></a>
## Conclusion

This is my conclusion

**To continue with this topic:**

This was in hope to build a recommender in the future. 
