# Aurora_Prediction_LSTM
Using TensorFlow Libraries to build an LSTM that uses Kp Value history to predict future Kp values.

I wanted to do a little bit of practice to remember some topics covered in my BioRobotics/Cybernetics class. Specifically here I am making an LSTM to attempt to predict the strength of the Aurora Borealis! I decided upon this idea because I find the Aurora super fascinating and the data I needed was super easy to gather as well!
The NOAA (National Oceanic and Atmosphere Administration) points towards the GFZ German Research Centre for Geosciences(https://www.gfz-potsdam.de/en/section/geomagnetism/data-products-services/geomagnetic-kp-index). They post an updated dataset of Geomagnetic Activity data every 3 hours since 1932! This gives us over 250,000 data points to train and test with.
Because of the time series nature of this data, using an LSTM(long-short-term-memory) is an ideal choice for learning.

For now most of my analysis will be contained within the Jupyter notebook since basically at this point I just have the model working and have not really done any tuning at all. I'm also debating looking at adding more datasets to train on rather than just Kp values, Some other Geomagnetic activity data given is ap, C9, cp. 
If this can be tuned well, I'm interested in expanding this project to the source: solar activity, storms, & flares.
