# SENTIMENT-ANALYSIS
# COMPANY: CODTECH IT SOLUTIONS
# NAME: HRIDHYA ABHINA RAJEEVAN
# INTERN ID: CT04DH2665
# DOMAIN: DATA ANALYTICS
# DURATION: 1 MONTH
# description: 
In this project, the goal was to perform sentiment analysis on textual data to classify text snippets into sentiment categories—positive, negative, or neutral. Sentiment analysis is a crucial task in natural language processing that helps machines understand human emotions and opinions expressed in text. This capability is widely used in analyzing customer feedback, monitoring social media sentiment, and conducting market research.

Since a specific dataset was not provided, a small sample dataset containing ten sentences with labeled sentiments was created within the code for demonstration purposes. These text samples were short statements reflecting various opinions ranging from strong positivity to negativity and neutral stances.

The first key step involved preprocessing the raw text to prepare it for analysis. Text preprocessing included converting all characters to lowercase to ensure uniformity, removing extraneous content like URLs, user mentions, and hashtags which do not contribute to sentiment meaning, and stripping punctuation and numerical characters. Additionally, common stopwords—words such as “the”, “is”, and “and” that provide little value in sentiment classification—were removed. Stemming was applied to reduce words to their base or root form (e.g., “loved” to “love”) to consolidate word variants and improve model generalization.

Next, the cleaned text was transformed into a numerical representation using the Term Frequency-Inverse Document Frequency (TF-IDF) vectorizer. TF-IDF assigns weights to words based on how important they are within a document relative to the whole dataset, enabling the model to focus on meaningful words rather than frequent common words.

With the dataset vectorized, a Logistic Regression model was trained to learn patterns associating word usage with sentiment labels. The dataset was split into training and testing subsets (70% train, 30% test) to evaluate model performance on unseen data.

Model evaluation included measuring accuracy (percentage of correct predictions), precision, recall, and F1-score (harmonic mean of precision and recall) for each sentiment class, alongside a confusion matrix showing the distribution of predicted versus actual labels.

The model achieved moderate accuracy (~67%), showing reasonable ability to distinguish sentiments despite the small sample size. The confusion matrix indicated some misclassifications, which is expected in small datasets and a simple model.

In conclusion, this task highlighted the complete workflow of sentiment analysis—from data cleaning and feature extraction to modeling and evaluation—demonstrating how text data can be converted into actionable insights using NLP. This foundation prepares for more advanced projects using larger datasets and sophisticated models.

# output




