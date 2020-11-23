# Douban-Movie-Review-Sentiment-Analysis
The popularity of online movie reviews encourages many people to generate the comment and share their watching experiences. However, when I scraped all the movie reviews for 16 movies from Douban, a Chinese version of IMDB, I found that on average, each movie has about 65,000 reviews, and each review contains about 37 words. The large volume of movie reviews makes it quite hard for users to go through all of them. Under this circumstance, what should we pay attention to when writing movie reviews so our comment can stand out?

So this project aims to find the features that have positive relastionship with the popularity of movie reviews as well as build a prediction moddel to predict the sentiment of each review especially under the movie context.

In Douban community, users write their movie reviews, then everyone else has access to them and can click like button if they do like them. In this case, movie reviews receiving more likes can be defined as more popular ones.

The data scraped from Douban website contains:<br><br>
*Chinese name and English name of the movie*<br>
*The date when the data was crawled*<br>
*The username of people who wrote reviews*<br>
*The comment (Movie reviews) they generated*<br>
*The star they gave for the movie*<br>
*The date they wrote their reviews as well as the number of likes they received from other users*

