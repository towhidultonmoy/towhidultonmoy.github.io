---
title: "Sentiment Analysis of Covid-19 related tweets"
excerpt: "<img src='/images/sentiment.jpg'>"
collection: portfolio
---

<html>
<head>
    <style>
        .cover {
            text-align: center;
            margin-bottom: 20px;
        }

        .cover img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <div class="cover">
        <img src="/images/sentiment.jpg" alt="Cover Image">
    </div>


</body>
</html>


##  The Problem

The Covid-19 pandemic has had a profound impact on global societies, resulting in significant economic losses, job disruptions, and confinement of a large portion of the global population. Understanding people's sentiments and emotions surrounding the pandemic is crucial for promoting mental health and keeping individuals informed about Covid-19 developments. This sentiment analysis competition focuses on analyzing Tweets related to the pandemic, presenting a multi-label text classification challenge. The training data comprises 5000 labeled tweets, while the validation data consists of 2500 unlabeled tweets. The training data contains three columns: Tweet ID, Tweet text, and corresponding labels. The labels are categorized as Optimistic (0), Thankful (1), Empathetic (2), Pessimistic (3), Anxious (4), Sad (5), Annoyed (6), Denial (7), Surprise (8), Official report (9), and Joking (10). For instance, if a tweet is labeled with 3 and 6, it signifies that the sentiment expressed in the tweet is Pessimistic and Annoyed.

## The Solution

In response to this problem, I employed the "XLNet" model in PyTorch to predict the sentiments expressed in tweets associated with the Covid-19 pandemic. Leveraging this powerful model, I successfully classified tweets from a dataset that contained multiple sentiment labels for each text. Through this approach, I aimed to gain insights into the diverse sentiments and emotions expressed by individuals during the pandemic.

## Benefits and Impact

By accurately predicting the sentiments of Covid-19-related tweets, this solution offers several benefits. Firstly, it provides valuable insights into people's emotional states, contributing to the overall understanding of mental health during the pandemic. This knowledge can inform mental health support initiatives and help individuals navigate the challenging circumstances brought about by the Covid-19 crisis. This analysis can also aid in monitoring public sentiment towards government policies and interventions, allowing for timely adjustments and improved public communication. Overall, leveraging sentiment analysis in this context has the potential to enhance mental health support, promote informed decision-making, and improve overall well-being during the Covid-19 pandemic.