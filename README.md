# 🔥 Forest Fire Prediction

# 🌲 Introduction
Forest fire is a prevalent environmental issue not only in my community but the world at large. Over the past decade, my community has been faced with this issue, especially during the harsh dry weather season. It causes various economic and ecological damages, jeopardizing the lives of the living. In today’s technology, man-made major disasters are multiplying exponentially. This work aims to detect forest fire areas by comparing various regression models. It represents how regression works best for detecting forest fires to take quick action before the fire damages and spreads over a vast region.

The forest fires dataset from the UCI Machine Learning Repository is analyzed for burnt areas prediction. This machine learning project aims to determine the behaviors of 41 regression models on the dataset and rank them according to the R-squared and RMSE values as well as the time taken.

# 📊 Dataset
The dataset used in this study is the UCI Forest Fires dataset, which contains meteorological data and fire occurrence records in the Montesinho natural park in Portugal. The features include temperature, humidity, wind, rain, and several spatial and temporal attributes. Some features in the dataset include but are not limited to:
* Fine Fuel Moisture Code (FFMC)
* Duff Moisture Code (DMC)
* Drought Code (DC)
* Outside temperature
* Day and month

[Link to dataset](https://archive.ics.uci.edu/dataset/162/forest+fires)

# 🔍 Summary of Methodology
* Initial data exploration involved loading the dataset and inspecting its structure. A new categorical variable, fire_scale, was introduced based on the area affected by the fire to classify fires into three categories: no fire, small fire, and large fire.
* Following pre-processing, the data was divided into training and testing sets according to the specifications. The data was split into two sections: a training set (20%) and a testing set (80%). The training set is used to validate the algorithm, and the test set is used to evaluate the model's efficacy and accuracy.
* Scaled the numerical features using StandardScaler to standardize the dataset.
* The performance of 41 regression models was observed, considering error, efficiency, and accuracy metrics. Calculations were based on Rating, RMSE, and R2 SCORE values. The Bagging Regressor provided the highest accuracy and lowest error rates.
* On prediction, the bagging regressor gave mse, mae, and r2 of 0.1881, 0.1174, and 0.8471, respectively, which is an ideal performance on the data and also better than many regressors used in the literature.

# 📚 References 
* Pradeep Kumar G, Rahul R, Ravindharan N “Early Forest Fire Detection Using Machine Learning Algorithms” International Journal of New Technology and Research (IJNTR) ISSN: 2454-4116, Volume-7, Issue-4, April 2021.
* Ahmed M. Elshewey, Amira. A. Elsonbaty “Forest Fires Detection Using Machine Learning Techniques” Journal of Xi'an University of Architecture & Technology ISSN No: 1006-7930 Volume XII, Issue IX, 03 October 2020.
* David A. Wood “Prediction and data mining of burned areas of forest fires: Optimized data matching and mining algorithm provides valuable insight” Artificial Intelligence in Agriculture 5 (2021).
* Pragati, Sejal Shambhuwani, Piyusha Umbrajkar “Forest fire detection using machine learning” International Journal of Advances Scientific Research and Engineering Trends Volume 4 || Special Issue 12 || ISSN (Online) 2456-0774|| ICCEME 2019-2020.
