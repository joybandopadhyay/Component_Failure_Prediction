# Component_Failure_Prediction
#Brief Description dataset
"""
This dataset reflects real component failure prediction encountered in the
automobile and other industries with measurements from real equipment. The
features description: -
The six features are: -
Type: the quality of the product, consisting of a letter L, M, or H.
Meaning low, medium, and high, respectively.
Air temperature [K]: generated using a random walk process .
Process temperature [K]: generated using a random walk process .
Rotational speed [rpm]: calculated from power of 2860 W, overlaid with a
normally distributed noise.
Torque [Nm]: torque values are normally distributed around 40 Nm
Tool wear: The quality variants H/M/L of tool wear
in the process.
The targets are:
Target: failure or no failure (to perform binary classification).
Failure Type: type of failure (to perform multiclass classification).
