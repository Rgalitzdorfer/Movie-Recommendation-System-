# Movie-Recommendation-System-
## Description
As a fervent Netflix enthusiast, I've consistently marveled at the precision of movie recommendation systems. This particular recommendation system employs techniques from content-based filtering, suggesting movies based on shared features. After thorough experimentation, I identified key relevant features, including genre, tagline, keywords, and the original language of the movie. To measure the accuracy of the recommendations, I chose cosine similarity as the primary metric for evaluation. This approach distinguishes itself from others that heavily rely on user ratings, creating tailored suggestions for other movie enthusiasts.

The following data science concepts are used in this project
1. Data Collection & Cleaning (Removing null values)
2. Model Training (Extracting useful features, Vectorizer)
3. Model Evaluation (Cosine similarity)

The following technology & libraries are used in this project
1. Google Colab
2. Python
3. Pandas & Numpy (Data reading & cleaning)
4. Scikit-Learn (TfidVectorizer, Cosine Similarity)

## Future Improvements
Foremost, incorporating historical user ratings into this project could have significantly enhanced accuracy by providing explicit feedback. These ratings would have allowed for model evaluation using additional metrics like Precision and F1 scores. Due to the absence of explicit feedback, the recommendation system solely relies on content-based filtering, foregoing collaborative filtering or a hybrid approach. Moreover, a richer dataset would offer insights into the system's overall success, evaluating factors such as coverage, recommendation diversity, and others to assess its real-world impact. In future projects, this step will be integrated into the data retrieval and collection process for a more comprehensive understanding and improved performance.
