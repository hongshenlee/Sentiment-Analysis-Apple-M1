# Sentiment-Analysis-Apple-M1
A&A Project for Text Mining. 

This project comes from an idea should I buy the new MacBook with new cross-era chips. Apple has released its cross era product with **Apple Silicon M1**. I'm curious about whether this new product is popular and what its reputation is. I want to see people’s attitudes towards the new MacBook products. So, I collect the tweets about this topic and use a sentiment analysis model to predict their attitudes to support my decision. 

**The whole project should be divided by following steps:**

- **Step 1:** Pulling tweets about the products(Macbook with new M1 chips) from twitter

- **Step 2:** Building a model to do the sentiment analysis (with relevant dataset to train)

- **Step 3:** Combining the data and model to predict the sentiment of these tweets, and go to the conclusion.

  

**Dataset Description**

1. The dataset to train the model : [Apple_M1_Sentiment_Analysis: Model](https://moodle.umt.edu/mod/hsuforum/discuss.php?d=729836)

2. The dataset to do the analysis: [Apple_M1_Sentiment_Analysis: Tweets Data](https://moodle.umt.edu/mod/hsuforum/discuss.php?d=729837)



**Bad Results**

Once I think these two dataset both are reviews of the products. So, the model built by the first dataset can be transferred to predict the sentiment of the second dataset.

After I finished the whole processes, the result in [Step 3.3](https://github.com/hongshenlee/Sentiment-Analysis-Apple-M1/blob/main/Step_3_Predict_Sentiment.ipynb) turned out to prove that I was wrong. Their features, which are their words in the reviews or tweets don't match at all.

What should I do next step？
