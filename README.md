# Human-Activity-Recognition-Using-Smartphones
In this project, our prime focus was to predict human activity by using the smartphone’s sensors. 

The tasks associated with this project were the classification and clustering of humans on the basis of their activities.

Tools and Language: Python, Jupyter Notebooks

## Dataset Description
Dataset consists of signals from a smartphone carried by 30 individuals performing 6 different activities. Activities performed are listed below with their corresponding codes.

● WALKING
● CLIMBING UP THE STAIRS
● CLIMBING DOWN THE STAIRS
● SITTING
● STANDING
● LAYING

Signals were recorded with a sampling rate of 50Hz and were then stored as time series data for each dimension, so 6 different signals were obtained where 3 are from accelerometer and other 3 are from gyroscope. The noise was then filtered using median and 20Hz Butterworth[13] filters in order to get precise results. A second 3Hz Butterworth filter was applied to eliminate the effect of gravity in the accelerometer signals. Figure 2 depicts the graphs of high and low pass Butterworth filters. Values were then normalized to an interval of -1 to 1. Euclid magnitudes of the values of 3 dimensions were then calculated to merge 3 dimensional signal into one dataset.

Several steps were implemented to perform data preprocessing.

Feature Engineering was done using Principal Component Analysis(PCA) t-Distributed Stochastic Neighbor Embedding (tSNE)

## The methods used for classification:

● Support Vector Machines,

● K-nearest neighbors(KNN),

● Decision Tree,

● Random Forest,

● Logistic Regression,

● GaussianNB

