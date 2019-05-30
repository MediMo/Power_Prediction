# The Output Power Prediction

This is the code for "Power Prediction" using linear regression. The data set is available at:
https://archive.ics.uci.edu/ml/datasets/combined+cycle+power+plant 

## Overview

In this code, we use Keras Sequential model for output power prediction of a combined cycle power plant using linear regression method.

## Data Set Information

According to UC Irvine Machine Learning Repository:

"The dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (EP) of the plant.

A combined cycle power plant (CCPP) is composed of gas turbines (GT), steam turbines (ST) and heat recovery steam generators. In a CCPP, the electricity is generated by gas and steam turbines, which are combined in one cycle, and is transferred from one turbine to another. While the Vacuum is colected from and has effect on the Steam Turbine, he other three of the ambient variables effect the GT performance."

## Some references:

https://github.com/PacktPublishing/Hands-On-Artificial-Intelligence-for-IoT/blob/master/Chapter03/ElectricalPowerOutputPredictionUsingRegression.ipynb

https://github.com/tensorflow/docs/blob/master/site/en/r2/tutorials/keras/basic_regression.ipynb

https://github.com/PacktPublishing/Tensorflow-2.0-Quick-Start-Guide/blob/master/Chapter02/Chapter2_Keras_sequential_models_TF2_alpha.ipynb

https://github.com/tensorflow/docs/blob/master/site/en/r2/tutorials/quickstart/advanced.ipynb
