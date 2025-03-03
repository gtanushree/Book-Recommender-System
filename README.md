# Book-Recommender-System

Overview:
The Book Recommender System is a machine learning-based recommendation engine that suggests books to users based on collaborative filtering and popularity-based methods. It leverages user interaction data to provide personalized recommendations.

Features:
1. Popularity-Based Recommendations: Recommends books based on their overall popularity (e.g., number of ratings and average rating score).
2. Collaborative Filtering: Uses user behavior to recommend books similar to what a user has previously liked.
3. Similarity Score Calculation: Computes similarity between books to enhance recommendation accuracy.

Files & Directories:
1. Popularity_Based.ipynb: Jupyter Notebook implementing the popularity-based recommendation approach.
2. Collaborative_Filtering_Based.ipynb: Jupyter Notebook implementing collaborative filtering-based recommendations.
3. Popular.pkl: Precomputed dataset for popularity-based recommendations.
4. pt.pkl: Preprocessed pivot table used for collaborative filtering.
5. similarity_scores.pkl: Precomputed similarity scores for books.

Requirements:

To run this project, install the required dependencies:
pip install pandas numpy scikit-learn scipy

How to Run:
1. Open Popularity_Based.ipynb or Collaborative_Filtering_Based.ipynb in Jupyter Notebook.
2. Run the notebook cells to generate recommendations.
3. Load the precomputed .pkl files to avoid reprocessing.

Future Enhancements:
1. Implement a hybrid recommender system combining multiple approaches.
2. Develop a web-based interface for user interaction.
3. Incorporate deep learning-based recommendation models.

Contributor: Tanu Shree Gupta

Feel free to contribute or suggest improvements!


