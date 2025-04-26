# Start Success Prediction

Introduction

A startup is described as an early-stage business focused on innovation, aiming to scale rapidly by solving unique market problems. Kecskes, A. and Coeurderoy, R., (2021).

Business question?

As a data scientist in a Venture Capital firm, my firm wants to invest only in startups with high chances of being successful.

ML Task

My task is to build a model that accurately predicts startup success. This model will help the firm to mitigate the risks of investing in startups that eventually fail, making the firm profitable and preventing losses.  Using Maching Learning models to predict startup success based on selected features.

In this pipeline, a startup is deemed as failed if it is closed or acquired and deemed as successful if its status is ‘operating’ or ‘ipo’ in the dataset. Most data analysts add ‘acquired’ to the ‘successful’, but this pipeline did otherwise because a startup being acquired could either mean it’s being absorbed into its bigger competition, underselling or any of the other negative ways the acquisition can go. Another reason for adding ‘acquired to the ‘failed’ classifications is because the dataset already has a disproportionate count of ‘operating’ therefore adding acquired to the same group will skew the dataset further.
