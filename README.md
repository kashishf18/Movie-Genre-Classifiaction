# Movie-Genre-Classifiaction
A machine learning project that classifies movies into their respective genres based on plot summaries. This project uses TF-IDF vectorization for text preprocessing and Logistic Regression as the classifier.

📌 Table of Contents
Overview
Dataset
Models & Performance
Results

📝 Overview
This project focuses on classifying movies into multiple genres using text-based features such as plot descriptions. The key steps include:

1.Data Preprocessing: Cleaning and tokenizing text, removing stopwords, and vectorizing using TF-IDF.
2.Feature Engineering: Extracting useful information for classification.
3.Model Training: Implementing classification algorithms including Naive Bayes, Logistic Regression, Random Forest, and SVM.
4.Evaluation: Analyzing accuracy, F1-score, and AUC-ROC to determine the best model.

📂 Dataset

Source: Kaggle / IMDB / TMDB / Custom Dataset  (https://www.kaggle.com/code/imgowthamg/movie-genre-classification)
Description: Contains movie titles, descriptions, and corresponding genres.

📊Model & Performance
Classifier: Logistic Regression
Text Preprocessing: TF-IDF Vectorizer
Example Test Set Accuracy: 0.9351 (93.51%)

Classification Report:

               precision    recall  f1-score   support

      comedy        1.00      0.35      0.52        66
 documentary        0.93      0.92      0.92      4392
       drama        0.94      0.95      0.95      6378
       short        0.00      0.00      0.00         4

     accuracy                           0.94     10840
    macro avg       0.72      0.55      0.60     10840
 weighted avg       0.93      0.94      0.93     10840


📈Results
High Accuracy: The Logistic Regression model achieves approximately 93.51% test set accuracy.
Genre-Specific Performance:
Strong performance for genres with ample data (e.g., Documentary and Drama).
Lower recall for genres like Comedy and Short, indicating the need for more data or feature refinement.
