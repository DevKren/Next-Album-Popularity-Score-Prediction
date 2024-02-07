# Artists-Next-Album-Streams-Predictor-ML
Code Written by Anthony Krenek
Artists Popularirty Prediction Score on there next album
Libraries used: 
Spotipy 
Numpy 
Pandas
from spotipy.oauth2 import SpotifyClientCredentials
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import mean_absolute_error

Formulas Used: 
Mean Absoute Error (https://github.com/DevKren/Artists-Next-Album-Streams-Predictor-ML/assets/115112111/8f2c81c4-7cbf-4130-890b-6c180926a80d)


A python program using Random ForesT Regressions and Spotifys developer platforms and libraries to predict the amount of streams for an artists next album.
