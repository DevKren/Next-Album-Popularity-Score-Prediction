# Artists-Next-Album-Streams-Predictor-ML
Code Written by Anthony Krenek
Artists Popularirty Prediction Score on there next album
Need From Spotify:
Client ID 
Client Secert 

Libraries used: 
Spotipy 
Numpy 
Pandas
from spotipy.oauth2 import SpotifyClientCredentials
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import mean_absolute_error

Formulas Used: 
Mean Absoute Error
1 / n ∑ of y - y_hat 
n = total data points 
y = actual output value
y_hat = predicted output value 

Use this to get an accuracy number for testing and training on the model 
A python program using Random ForesT Regressions and Spotifys developer platforms and libraries to predict the amount of streams for an artists next album

Model Used: 
Random Forest Regreesion: 
I decided to use this model because this model works well on predicting continous numbers such as an albums popularity score.
I am comparing the performance of any artists previous albums popularity score and predicting for the next one.
Also, this model was very easy to use and implement

Problems: 
It was hard to learn the spotify developer program, but after a feel google searches it all made sense
Having data not get lost, I had to run it multiple times because data was being lost when the sessions would be restarted
Finding the data within the Spotipy library to actually be able to use (e.g: Can't get streams so had to use popularity score)
Takeaways: 
Taught myself another ML model that I haven't heard of before
Getting more comfortable with Pandas and Numpy and application with these libraries
Learned more Sklearn model libraries which I can then use on future projects

Future Ideas: 
Use Pytorch to implement features on the next album which could then influence the popularity score
Give a timeline of when they are dropping 
How popular the artist we have selected at that time is 
Making better predictions 

Thank You all for looking at my project and feel free to be able to use it! 
