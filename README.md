**🎬  Content-Based Movie Recommender System**

This project implements a content-based movie recommender system using a neural network model. It leverages feature vectors representing users and movies to predict personalized ratings, and recommends the highest-rated items accordingly.

**💡 How It Works**

- User and movie features are fed into the neural network to predict a rating.

- The system generates a predicted rating for every movie the user hasn’t rated.

- Movies are sorted by predicted score to recommend the most suitable ones.

- Existing and new users can be handled differently based on available data.

**📂 Files**

- Content_basedRecSys.ipynb — Main notebook containing data loading, preprocessing, model training, and predictions.

- resysNNutils.py — Utility functions for loading data, printing predictions, and handling feature matrices.

- ./data/ — Folder containing training data and metadata:

   - content_item_train.csv, content_user_train.csv, content_y_train.csv — Feature matrices.

   - content_movie_list.csv — Movie metadata.

   - content_item_vecs.csv — Processed item vectors.

   - content_user_to_genre.pickle — User rating history by genre.

**🚀 How to Run**

- Make sure all data files are placed in a folder named data/.

- Run the notebook Content-basedRecSys.ipynb.

- Adjust model parameters and layers as needed.

📊 Example Output

This code simulates a user profile by setting genre preferences and average behavior, feeds it into a trained neural network along with movie data, and outputs the top 10 personalized movie recommendations based on predicted ratings:

![image](https://github.com/user-attachments/assets/b8e40929-88e7-4a9b-a341-269bcc87c92a)


📚 Acknowledgments

This project is based on techniques taught in DeepLearning.AI and Stanford’s Machine Learning course and adapted for practical implementation.

- View top recommendations and analyze predictions.

