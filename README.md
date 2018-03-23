# Deploying Neural Networks to learn from r/news on Reddit

For this project I;

1. Web-scraped the title, author, and new source of the top 100 posts on the r/news thread (Scraped twice a day for a week)
2. Used scikit-learn's multi-layered classifier (MLC) (scikit-learn's basic neural network model)

I was trying to predict if the post would be in the top 50% or top 10% of most popular posts (bases on up-votes). Also, I wanted to compare the multi-layered classifier to logistic regression to see how powerful/useful the MLC model is.
