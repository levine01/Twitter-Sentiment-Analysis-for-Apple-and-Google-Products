# Twitter Sentiment Analysis for Apple and Google Products

![photo](https://images.pexels.com/photos/40185/mac-freelancer-macintosh-macbook-40185.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)

## Overview
This project aims to analyze Twitter sentiment regarding Apple and Google products using Natural Language Processing (NLP) techniques. The goal is to develop a model that can classify tweets as positive, negative, or neutral based on their content, helping to understand public sentiment towards these technology giants.

## Business understanding
In the realm of technology giants, Apple and Google, public sentiment plays a pivotal role in shaping their strategies and brand perception. This analysis focuses on understanding the dynamics of sentiment expressed on Twitter concerning these companies. Apple and Google have a significant global presence and are influenced by various factors, including product launches and developments. Last year, Apple's revenue exceeded $300 billion, while Google's parent company, Alphabet, reported revenues of over $181 billion. Monitoring and leveraging public sentiment can provide valuable insights for both companies in guiding marketing strategies and product development decisions.

The real-world problem we aim to address is the need for Apple and Google to gain actionable insights from the vast amount of public sentiment expressed on Twitter. Understanding customer sentiment is crucial for these companies as it directly impacts their product development, marketing strategies, and overall brand reputation. Negative sentiment can indicate areas that need improvement, while positive sentiment can inform successful strategies.

The stakeholders in this project include Apple and Google themselves, as well as their marketing and product development teams. Additionally, shareholders, investors, and the broader consumer base interested in these companies' performance can benefit from this analysis.

Our project provides clear value to these stakeholders. By analyzing Twitter sentiment, we offer a means for Apple and Google to gauge public perception accurately. This, in turn, can help them make data-driven decisions, identify potential issues, and refine their products and marketing strategies. For instance, if negative sentiment is detected around a specific product feature, this information can guide improvements and mitigate potential PR crises.

## Data Understanding

The dataset originates from CrowdFlower, accessed via data.world. The choice of this dataset is highly suitable for our project's objectives. It contains over 9,000 tweets that have been manually rated for sentiment (positive, negative, or neither). These tweets serve as a valuable resource for training and testing our sentiment analysis models. Since Twitter is a prominent platform for users to express their opinions and sentiments publicly, this data represents real-world sentiment effectively.

The dataset is sufficiently large, comprising over 9,000 tweets, which ensures an ample amount of data for model training and validation.The features used in our analysis have been carefully selected based on their properties and relevance to the project's objectives. Features such as tweet_text and emotion toward a brand or product are integral to understanding sentiment and determining the factors influencing it.

While the dataset is valuable, it does have limitations that could impact our analysis. For instance, tweet sentiment is not always straightforward to discern, as it may depend on context, sarcasm, or language nuances. Additionally, the dataset may not be fully representative of all sentiments expressed on Twitter.

## Modelling
We employ various machine learning techniques to build a robust sentiment analysis model for Twitter discussions about Apple and Google products. We begin with a baseline Naive Bayes classifier to establish a performance benchmark. After evaluating its accuracy and performance metrics, we explore Support Vector Classification (SVC) and assess its effectiveness in handling imbalanced sentiment classes. To enhance sentiment analysis, we explore Random Forest and assess its effectiveness in handling imbalanced sentiment classes. Furthermore, we expand our analysis to multiclass classification, including positive, negative, and neutral sentiments. We also investigate Naive bayes with hyperparameter tuning using GridSearchCV, Logistic Regression and Random Forest models to improve accuracy. Our ultimate goal is to develop a reliable model that accurately categorizes public sentiment toward these tech giants' products, offering valuable insights for stakeholders and decision-makers.

## Evaluation

For binary sentiment analysis, the Random Forest model emerged as the top performer, achieving an accuracy of 88.84% with balanced precision and recall for both positive and negative sentiments. In multiclass sentiment analysis, the Logistic Regression model outshone others with an accuracy of 69.1%, demonstrating balanced performance across sentiments.

Our sentiment analysis of Apple products on Twitter revealed key influencing factors, such as the frequency of positive and negative terms, specific keywords, and the volume of mentions. Stakeholders, including Apple, market analysts, and investors, can leverage these insights to assess marketing effectiveness, predict stock performance, and make informed investment decisions.

Consumers can also benefit by gauging public opinion to make informed purchasing choices. Overall, our sentiment analysis empowers a wide range of stakeholders to make data-driven decisions in the context of Apple's products and public sentiment.

## Recommendation

- Implement real-time sentiment monitoring for Twitter and other platforms to detect shifts in public sentiment.
- Utilize sentiment analysis insights to inform product development strategies, focusing on positively received features and addressing negative sentiment.
- Establish crisis management protocols triggered by significant negative sentiment spikes to protect brand reputation.
- Tailor marketing campaigns based on sentiment trends, capitalizing on positive sentiment and addressing negative feedback.
- Engage with users on social media, responding to both positive and negative comments to enhance customer satisfaction and convert negative sentiment into positive experiences.

## Presentention

Presentation slides found [here](https://www.canva.com/design/DAFurhpNMtg/MpLGL8vOt2wIw05D6SulaA/edit?utm_content=DAFurhpNMtg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)