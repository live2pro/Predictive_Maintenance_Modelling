# Predictive Maintenance Modelling Demo (Python)

This project is demonstration of a real-time predictive maintenance model application. The project is comprised of the following three parts:

+ A Python implementation of [this](https://gallery.azure.ai/Notebook/Predictive-Maintenance-Implementation-Guide-R-Notebook-2) popular R notebook that contains the steps of implementing a predictive maintenance model: [Link](https://github.com/transferlearnings/Predictive_Maintenance_Modelling/blob/master/notebooks/Predictive%20Maintenance%20Modelling%20Guide.ipynb)

+ A Python app to simulate a real time feed of simulated failure, maintainence and condition data. Specifically, this app will involve the following: (In Progress)

  + With the given time-series data, generate simulated data using the ["block bootstrap"](http://mapageweb.umontreal.ca/goncals/documents/Goncalves-Politis-2011.pdf) method.
  
  + Post simulated data to Google Cloud Function end points

+ A set of Google Cloud Function to do the following: (In Progress)

  + Perform feature engineering on the simulated data
  
  + Generate failure predictions for simulated data

+ A Google Datastudio dashboard to visualize the simulated data and predictions: (In Progress)


