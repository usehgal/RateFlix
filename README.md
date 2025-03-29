RateFlix - Movie Rating Prediction System

RateFlix is a Movie Rating Prediction System built using an Autoencoder in PyTorch. It uses the MovieLens 100K dataset to predict user ratings for movies based on collaborative filtering techniques.

Features

Uses Autoencoder-based collaborative filtering.

Trained on MovieLens 100K dataset.

Predicts ratings for unseen movies.

Provides personalized movie recommendations.

How It Works

Data Preprocessing:

Downloaded and extracted the MovieLens 100K dataset.

Loaded and cleaned the ratings and movie title data.

Converted the data into a user-item matrix.

Normalized the ratings between 0 and 1.

Model Building:

Designed an Autoencoder with fully connected layers.

Used ReLU activations in the encoder and Sigmoid activation in the decoder.

Training:

Split the dataset into 80% training and 20% testing.

Trained the model using Mean Squared Error (MSE) loss and Adam optimizer.

Ran for 50 epochs to minimize reconstruction error.

Evaluation:

Computed MSE (Mean Squared Error) and MAE (Mean Absolute Error) to evaluate model performance.

Provided personalized Top-N movie recommendations for users.

Test Evaluation Metrics

After training, the model achieved the following evaluation scores:

Mean Squared Error (MSE): 0.0074

Mean Absolute Error (MAE): 0.0094

Created by Utkarsh Sehgal 🚀

