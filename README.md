<img src="https://github.com/axiom2018/Nltk-Imbalanced-Youtube-Dataset/blob/main/Handling_imbalanced_data.png"/>

<p align="left"> 
  A scikit-learn & nltk project with massive preprocessing steps and so many models used in different ways. This is my first scikit learn project and like all my others, it's incredibly detailed.
  Link to kaggle <a href="https://www.kaggle.com/code/omarmoodie/nltk-youtube-imbalanced-dataset-classification">here</a>. Hope someone out there can learn from it!


  1) Exploratory Data Analysis
  2) Preprocessing
     - Lowercasing
     - Removing urls
     - Removing newline characters
     - Removing spaces
     - Removing emails
     - Removing twitter handles
     - Removing hashtags (<b>and</b> explanation regarding why they almost weren't removed)
     - Removing special characters
     - Removing numbers
     - Removing subscribers (several phrases with the word "subscriber" were present in the dataset, all phrases removed)
     - Removing stopwords
  3) Label Encoding
  4) Addressing the imbalance
     = Tfidf Vectorizer used
  5) Smote
  6) Model & prediction
     - Reason <b>WHY</b> accuracy isn't a good metric for imbalanced data.
  7) Combine title and description (2 features/columns in the data that went through preprocessing steps)
  8) Multiple Models
  9) Cost Sensitive Learning (What is it & why it's beneficial for more important data like business and <b>ESPECIALLY</b> health)
     - Model predictions without cost sensitive learning
     - Mdoel predictions WITH cost sensitive learning (& why imbalanced data was used again and not smote data)
  10) Grid Search Cross Validation
  11) Final Notes
</p>

