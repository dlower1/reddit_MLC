# Deploying Neural Networks to learn from r/news on Reddit

For this project I;

1. Web-scraped the title, author, and new source of the top 100 posts on the r/news thread (Scraped twice a day for a week)
2. Used scikit-learn's multi-layered classifier (MLC) (scikit-learn's basic neural network model)

I was analyzing the predictive power of the MLC, as compared to basic Logistic Regression. I used both models to predict if the post would be in the top 50% or top 10% of most popular posts (bases on up-votes).
