# Aurora_Prediction_LSTM
Using TensorFlow Libraries to build an LSTM that uses Kp Value history to predict future Kp values.

I wanted to do a little bit of practice to remember some topics covered in my BioRobotics/Cybernetics class. Specifically here I am making an LSTM to attempt to predict the strength of the Aurora Borealis! I decided upon this idea because I find the Aurora super fascinating, the data I needed was super easy to gather as well!
The NOAA (National Oceanic and Atmosphere Administration) points towards the GFZ German Research Centre for Geosciences, they post an updated dataset of Geomagnetic Activity data every 3 hours since 1932! Granted there are very few data points that far back but even just using the Kp values they have, this gives us over 250,000 data points to train and test with.
Because of the time series nature of this data, using an LSTM(long-short-term-memory) is an ideal choice for learning.

My initial results from just getting the machine to work are below <committing real quick to get the code up and then doing some analysis on what I've got so far>
