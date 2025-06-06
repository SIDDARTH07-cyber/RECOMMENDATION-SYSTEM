# RECOMMENDATION-SYSTEM

COMPANY: CODTECH IT SOLUTIONS

NAME: P VISHNU SIDDARTH

INTERN ID: CT04DF2078

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

Project Overview
This project implements a collaborative filtering-based movie recommendation system leveraging the Singular Value Decomposition (SVD) algorithm provided by the Surprise Python library. The system is designed to predict user preferences for movies based on historical user ratings, enabling personalized movie recommendations. The dataset used is the classic MovieLens 100K dataset, which contains 100,000 ratings from 943 users on 1682 movies.

Recommendation systems have become an integral part of modern digital platforms, helping users discover relevant content amid overwhelming choices. This project showcases how to build a robust recommendation system using matrix factorization techniques, a state-of-the-art approach widely used in industry.

Key Features
Data Loading and Preprocessing: The project uses the built-in MovieLens 100K dataset available within the Surprise library, which is preprocessed into a format suitable for collaborative filtering algorithms.

Model Training: Implements the SVD algorithm to learn latent factors representing users and items. This allows the system to estimate unknown user ratings effectively by decomposing the user-item interaction matrix.

Evaluation: The model's performance is evaluated using key metrics such as RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error) on a held-out test set, ensuring reliable predictions.

Cross-Validation: Uses 5-fold cross-validation to verify the model’s consistency and generalization capability across different data splits.

Top-N Recommendations: After training, the system generates personalized top-N movie recommendations for each user by predicting the ratings for all unrated items and selecting the highest predicted ratings.

Extensibility: The modular code structure allows easy swapping of algorithms, dataset expansion, and integration with real-world applications or APIs.

Technical Details
Language: Python 3.x

Libraries: surprise (for collaborative filtering), collections (for data manipulation)

Dataset: MovieLens 100K, which includes explicit user ratings ranging from 1 to 5 stars.

The core of the recommendation system relies on matrix factorization, where the original user-item rating matrix is decomposed into the product of two lower-dimensional matrices — one representing users and the other representing items. This approach captures latent features that explain observed ratings, enabling the system to make predictions for missing entries (i.e., items a user has not rated yet).

The SVD algorithm in Surprise is an optimized and regularized version that prevents overfitting and enhances prediction accuracy. Model evaluation involves computing RMSE and MAE on a test set created via random train-test splitting, as well as performing 5-fold cross-validation to assess stability.

Usage Instructions
Installation:

Install Surprise via pip:

pip install scikit-surprise
Clone this repository:

git clone <repo-url>
Run the code:

Load the dataset, train the SVD model, and get predictions.

Generate top-N recommendations for users.

Evaluate model accuracy with RMSE and MAE.

Customize:

Modify the number of recommendations (N) per user.

Change the algorithm or dataset to experiment with other collaborative filtering techniques.

Applications
Personalized movie recommendations in streaming services.

Product recommendations in e-commerce platforms.

Any domain requiring prediction of user preferences based on past interaction data.

Future Work
Incorporate Metadata: Use movie genres, tags, or user demographics to improve recommendations.

Hybrid Models: Combine collaborative filtering with content-based filtering.

Scalability: Adapt the system for larger datasets and real-time recommendations.

User Interface: Build a frontend for users to interactively explore recommendations.

Conclusion
This project demonstrates the power and practicality of collaborative filtering for recommendation systems. By applying the SVD algorithm on a well-known benchmark dataset, it highlights key steps such as data preparation, model training, evaluation, and recommendation generation. It serves as a solid foundation for anyone interested in building personalized recommendation engines using Python.

#OUTPUT 

![Image](https://github.com/user-attachments/assets/8f03a481-430e-40f7-abb1-54481f02dc7f)


