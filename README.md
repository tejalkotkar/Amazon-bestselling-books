# Project-2-Amazon-bestselling-books

In the project we have built intractive dashboard to analyze Amazon's Top bestselling books from 2009 to 2019.

This dataset have Amazon customer's ratings and review 550 books categorized into fiction and non-fiction.

#### Tools:

This project is achieved by using:
HTML, CSS, javascript combined with D3, Python Flask API, Jupyter Notebook

#### Additional Libraries used for amination:
Anime.js (https://cdn.jsdelivr.net/npm/animejs@3.0.1/lib/anime.min.js)
Animate.min.css (https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css)

### Dataset:

Datasets is in form on CSV file taken from Kaggle link:

[https://www.kaggle.com/sootersaalu/amazon-top-50-bestselling-books-2009-2019](https://www.kaggle.com/sootersaalu/amazon-top-50-bestselling-books-2009-2019) 

### Questions for this analysis:

1) Top 10 books by review for over the years and Comparison between : User Rating & Review , User Rating & Price
The first chart illustrates the top 10 books by review and second chart illustrates the comparison between user rating and Price/Reviews.
From both the charts we can not say that having higher reviews will have high user ratings as well.
However for almost all years, most of the top books falls under user rating of 4.5-4.8		
![Default_view](Images/Img1.png)
![Default_view](Images/Img2.png)

2) Relationship between : 
    Price & User rating
     The r-squared value for Price V/S User Rating: -0.13.
     This R value shows weak correlation between price and user rating which shows user rating doesn't depends on the book price.
     ![Relationship](Images/User_Rating.png)
    Price & Review	
     The r-squared value for Price V/S Review:-0.11. 
     This R value shows weak correlation between price and number of review which shows number of reviews doesn't depends on the book price.
     ![Relationship](Images/Reviews.png)			

4) Authors with highest reviews and total price of their books.
   Suzanne Collins top the chart with hightest reviews (278329) for Hunger Games Series.
   Don Miguel Ruiz is at the bottom of the chart with 139848 reviews for The Four Agreements: A Practical Guide To Personal Freedom.
   ![Top Authors](Images/Img3.png)

4) Bestseller books count by Genre over the years.
   Counts of Non-fiction books have been consistently increasing from 2010 to 2014.
   Counts of Fictin books is highest in year 2014.
   ![Counts](Images/Img4.png)			

