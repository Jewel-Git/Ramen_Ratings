# Ramen_Ratings_Analysis

## by Gladens Popoola


## Dataset Description

#### THE BIG LIST
The Big List is a list of reviews for ramen products across different brands and countries. The dataset can be found on THE RAMEN RATER([The Big List](https://www.theramenrater.com/resources-2/the-list/)). The dataset contains 4120 rows of reviewed Ramen products across 7 different properties(columns) which are Review #,Brand,Variety,Style,Country,Stars,T. 

Some background: these reviews are based on the personal preferences of the owner of The Ramen Rater, not on sales of popularity. Scores are in .25 increments – rounding is NOT recommended. Think of letter grading; a 3.5 score out of 5 stars – (3.5 * 2) * 10 = 70 = C. So, rounding a 3.5 to a 4.0 doesn’t reflect it correctly.


## Question(s) for Analysis

- What ramen Style is the most common?
- What Country has the most ramen products?
- Which brand is the most common?
- What is the average star ratings for each ramen style?
- What country has the highest rating for ramen products?
- What Ramen Brands have the highest average stars?
- Do ramen products with Spicy flavor have higher star ratings on average?
- Do ramen products with Chicken flavor have higher star ratings on average?
- Do ramen products with Seafood flavor have higher star ratings on average?
- What is the average star ratings by ramen flavor?


## Conclusions

1. The distributon of the Star ratings is skewed to the left.
2. The most common style used by ramen brands is Pack, followed by Bowl and then Cup. Bottle, Restaurant, Can and Bar are the least used styles by ramen brands.
3. Japan has the highest total number of ramen_brands. 
4. The most common brand is Nissan.
5. Ramen product with the style Bar has the highest star ratings on average but this is because only one ramen product record has the style Bar and it had a star rating of 5.0! Also Can and Bottle ramen styles both have a average star ratings of 3.5 and 4.0 respectively because there is only one ramen product record for each style. The ramen products with the style Box have the second highest star ratings on average of 4.262821. Ramen products with the Cup style have the lowest star ratings on average.
6. France has the highest average rating for ramen products while Ireland has the lowest average rating. We must note that some countries have only one recored ramen product. These countries are Portugal, New Zealand and Ghana.
7. 66 different Brands have average star ratings of 5.0. The next Brand with the closest average star rating to 5.0 is Prima Taste Brand with average star rating of 4.961538. The Brands US Canning, Yibin, Dr. McDougall's, Isoyama Shoji, Kim Ve Wong, Nanoblock, Simply Asia, Fairy Bridge, One Dish Asia, Tiger, Hikari Miso, Base Foods, Hsin Tung Yang, and Bowlfull all have the lowest average star ratings of 0.0. The next Brand with the closest average star rating to 0.0 is Roland Brand with average star rating of 0.125000.
8. The Percentage of Ramen products with Spicy Flavor is 16.3%(673 spicy ramen products 0f 4117 total ramen products).
9. The Percentage of Ramen products with Spicy Flavor is 11.8%(484 chicken ramen products 0f 4117 total ramen products).
10. The Percentage of Ramen products with Spicy Flavor is 3.7%(151 seafood ramen products 0f 4117 total ramen products).
11. Ramen products with spicy flavor have higher star ratings on average. The difference between the average star ratings of ramen products with spicy flavor and those without it is 0.018.
12. Ramen products with chicken flavor have lower average star ratings than those without chicken flavor. The average star ratings of ramen products without chicken flavor is greater than those with chicken flavor by 0.23.
13. Ramen products with seafood flavor have higher star ratings average. The difference between the average star ratings of ramen products with seafood flavor and those without it is 0.11.
14. Ramen products with Spicy,Seafood flavor have the highest average star ratings of 3.987179 followed by those with Seafood flavor with average star rating of 3.776786. Ramen products with Chicken flavor have the least average star ratings of 3.505583. Those with Spicy,Chicken flavor have average star ratings of 3.630208. It can be seen that products containing chicken flavor generally have lower star 
ratings.


##  Limitations & Recommendation
More feature engineering to get the flavors for the remaining ramen products will help to drive deeper analysis and get more insights.
