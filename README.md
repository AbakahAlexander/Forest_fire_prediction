# Forest_fire_prediction 

# Introduction

Forest fire is the prevalent environmental issue not only to my community but the world at large. Over the past decade, my community has been faced with this issue especially during the harsh dry weather season. It causes various economic,ecological damages thereby jeopardizing the lives of the living. In today’s technology man-made major disasters are multiplying exponentially. In this work, detecting the forest fire area by comparing various regression models has been accomplished. It represents how regression works best for detection of forest fires. Here Detecting in order to take quick action before the fire damages and spreads over a vast region.

The forest fires dataset from UCI Machine Learning Repository is analyzed for burnt areas prediction. This machine learning project is aimed to determine the behaviors  of 41 regression models on the dataset and rank them according to the R-squared and RSME values as well as the time taken. 

# Dataset

The dataset used in this study is the UCI Forest Fires dataset, which contains meteorological data and fire occurrence records in the Montesinho natural park in Portugal. The features include temperature, humidity, wind, rain, and several spatial and temporal attributes. 
Some features in dataset include but not limited to:
* Fine Fuel Moisture Code (FFMC)
* Duff Moisture Code (DMC)
* Drought Code (DC)
* Outside temperature
* Day and month

[Link to dataset](https://archive.ics.uci.edu/dataset/162/forest+fires)

# Summary of methodology
* The initial data exploration involved loading the dataset and inspecting its structure. The dataset was further processed to introduce a new categorical variable fire_scale based on the area affected by the fire to classify fires into three categories: no fire, small fire, and large fire.
* Following pre-processing, the data is divided into training and testing sets according to the specifications. The information has indeed been divided into two sections in this stage. such as a data collection for training and validation. where test data is used to evaluate the model's efficacy and accuracy and train data is used to validate the algorithm.training set (20%) and testing set (80%).
* Scaled the numerical features using StandardScaler to standardize the dataset.
* The performance of 41 regressions models were obserced. Using the error, efficiency, and accuracy numbers that these models have produced. Depending on Rating, RMSE, and R2 SCORE values, calculations are performed. Bagging  Regressor provided the higher accuracy and lower errors rates based on the methods.
* On prediction, the bagging regressor gave mse, mae and r2 of 0.1881, 0.1174, and 0.8471 which is an ideal performance on the data and also better than many regressors used in literature.

# References 
* Pradeep Kumar G, Rahul R, Ravindharan N “Early Forest Fire Detection Using Machine Learning Algorithms” International Journal of New Technology and Research (IJNTR)ISSN: 2454-4116, Volume-7, Issue-4, April 2021. 
* Ahmed M. Elshewey, Amira. A. Elsonbaty “Forest Fires Detection Using Machine Learning Techniques” Journal of Xi'an University of Architecture & Technology ISSN No: 1006-7930 Volume XII, Issue IX, 03 October 2020. 
* David A. Wood “Prediction and data mining of burned areas of forest fires: Optimized data matching and mining algorithm provides valuable insight” Artificial Intelligence in Agriculture 5 (2021).
* Pragati, Sejal Shambhuwani, Piyusha Umbrajkar “Forest fire detection using machine learning” international journal advances scientific research and engineering trends Volume 4 || Special Issue 12 || ISSN (Online) 2456- 0774|| ICCEME 2019-2020. 





  

