## Problem Background

Online reviews significantly influence consumer purchasing decisions, particularly in the food industry. Fine Food focuses on the key industry areas of bakery, confectionery, dairy, meat & seafood, and natural products.

Analyzing sentiments in these reviews helps businesses understand customer satisfaction, improve product offerings, and enhance customer experience.

High Review Volume: The Amazon Fine Food reviews dataset contains a large number of reviews, providing a robust sample for analysis.
Diverse Opinions: Reviews cover a wide range of products, reflecting diverse consumer opinions and sentiments.
Business Impact: Fine foods are a critical category where customer feedback directly impacts product development and marketing strategies.
Relevance: Sentiment analysis in the food sector helps identify trends, preferences, and areas needing improvement, directly benefiting producers and consumers.

## About Dataset

This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review.

1. Reviews from Oct 1999 - Oct 2012
2. 568,454 reviews
3. 256,059 users
4. 74,258 products
5. 260 users with > 50 reviews

##  Objective

1. To conduct data and text preprocessing on Amazon Fine Food Review.
2. To conduct sentiment analysis on consumer’s review toward Amazon Fine Food.
3. To perform model development on predict and classify customer reviews into 3 categories (Positive, Negative and Neutral)
4. To evaluate model performance on sentiment classification and analysis.

## Flow of Executive

1. Data and Libarary Import
2. Data Preprocessing
  - Data Type Conversion
  - Data cleaning
3. Feature Engineering
  - Data binning
  - Timestamp extraction
4. Text Preprocessing
  - Letter Case Standardization
  - Punctuation Removal
  - Whitespace Removal
  - Digit Number Removal
  - Tokenization
  - Word Lemmatizing
  - Stopword Removal
  - Removal of Unicode / Bicode Characters
  - Rejoin
5. EDA
6. Label Encoding
7. Stratified Data Splitting
8. Word2vec word embedding and vectorization
9. Model Development
10. Model Evaluation

## Result, Findings and Conclusion
**Overall Comparison:**\
Based on these results, Random Forest appears to be the best performing model overall. It has the highest accuracy on the single test set and the highest average accuracy across the folds.
  - However, it is important to consider the difference values as well. The fact that Random Forest's accuracy on the single test set is slightly higher than its average accuracy which suggests that its performance might be somewhat unstable where there is some variance in the model's performance when dealing with unseen data and less efficient in generalizing new data.
  - On the other hand, Logistic Regression shows more consistent performance across the folds, even though its overall accuracy is slightly lower than Random Forest.

\
**Conclusion :**\
By considering all evaluation and cross validated results,
  - Random Forest model is selected as the most suitable model in this case study.

**Recommendataion**

1. Customers exhibit a more positive sentiment towards the products in overall.
  - Beside Helpfulness Denominator, Seller is encourage to prepare a section or platform for interaction between customers  to share their users' experience with picture to show off and they are allow to help to answer if there any customer post any enquiry on the suitability of item.

2. ProductID B007JFMH8M is top reviewed products among all.
  - Develop marketing strategy to boost this item sales by emphasizing the satisfactory area on this products or increase the advertising budget on this items
  - Bundle this item with other items in the store to increase sales.

3. UserId A3OXHLG6DIBRW8 with most commented positive can be recognized or certified as a reward being supportive.
  - For example, like the fan badges (facebook) can be assigned to these category of customer.

4. UserId A3TVZM3ZIXG8YW commented 182 times of negative rating and reviews.
  - Customers expressed high dissatisfaction on this item, where this emphasizing the need for more prompt and proactive support.
  - The disappointed review will impacted the sales performance as it will act as a reference point to future potential customer, seller are recommended to reply on these reviews to understand and enhance reputation with a promise and initiative of improvement.
