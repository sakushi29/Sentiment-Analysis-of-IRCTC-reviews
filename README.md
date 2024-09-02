# Sentiment-Analysis-of-IRCTC-App-Reviews

- Developing a sentiment analysis model specifically for processing user reviews on the IRCTC app is a strategic approach to understanding customer feedback in a structured manner. By categorizing the reviews into positive or negative sentiments

- Implemented various classical models for this classification and generated best predictions via LSTM model.


----

 1. **Sentiment_ Different Models**
   - **Objective**: Implemented various classical models for sentiment classification (both binary and multiclass). Binary classification worked best.
   - **Binary Classification**: 
     - **Classes**: Score ≤ 2 → Class 0 (Negative); Score > 2 → Class 1 (Positive).
     - **Models**: Used models like Logistic Regression, Naive Bayes, SVM, etc. Binary classification showed better performance.
   - **Multiclass**: Less effective compared to binary due to challenges like class imbalance.
 2. **Sentiment_LIVE**
   - **Objective**: Live sentiment predictions using an LSTM model.
   - **LSTM Model**: Trained on text data for real-time sentiment analysis, ideal for applications like social media or feedback analysis.
