ROBERT M PROJECT 3

PROJECT 3 NLP BINARY CLASSIFICATION PROBLEM EXECUTIVE SUMMARY:

Using Pushshift's API two subreddit posts have been collected: r/49ers and r/NFL
Using a NLP, the goal is to train a classifier on which subreddit a given post came from. One way of measuring this is through accuracy.

If there is a noticable distinction between the r/49er fans and r/NFL fans on reddit, the marketing team for the 49ers organization should also make a marketing distinction: Focus ad promotions within the 49ers subreddit. When it comes to fans, people who make time to be part of a social media website and talk about their favorite team, it's not about convincing them to buy, its about simply finding where they are at.

Few of several classification models were chosen and trained to distinguish the subreddits based on language characteristics:

-Logistic Regression
-Naive Bayes
-KNN neighbors
-Random Forrest
-Support Vector Classifier

   Of course, not all models are the same but in this final case all models gave high variant results. I choose logistic regression due to ease of use and familiarity. Min/max document frequency, max_features, n_gram range, stop words ect.. were adjusted, piped and gridsearched. Very little distinction between sentiments from both reddits. Both were slightly positive with 80% neutrality. However, the value of sentiment may change during different seasons: pre, post and draft season. 
   
   Distribution of confusion matrix components show a large overlap between true positive and true negative probabilities. This shows room for necessary tuning of model and vectorizer parameters. Although, its important to keep in mind that both reddits are not anatagonistic in nature. This is not one reddit proponent for smoking against another reddit for non-smoking. This is about an American sport, football, in which there can understandably be a lot of similar linguistics dispersed in each reddit post. The reading are a good start because there is found to be a distinction between NFL and 49er reddit posts. 







# reddit_49ers_classification
