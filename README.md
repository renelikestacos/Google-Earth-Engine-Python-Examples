# Google Earth Engine Python API Examples
A collection of [Jupyter Notebooks](http://jupyter.org/) for [Google Earth Engine](https://earthengine.google.com/) Python API.

## Jupyter Notebook Tutorials for Google Earth Engine

#### 001 Landcover Classfication for Landsat 8 TOA imagery
Classification Example for Landsat 8 including several vegetation indices and object feature extraction. 
This example is based on the scientfic work "[MAD-MEX: Automatic Wall-to-Wall Land Cover Monitoring for the Mexican REDD-MRV Program Using All Landsat Data](https://www.mdpi.com/2072-4292/6/5/3923)" by S.Gebhardt et. al 2014. Eventually you can't access the training data. In case you are interested in the training data, feel free to contact me.<br><br>
![alt text](https://github.com/renelikestacos/Google-Earth-Engine-Python-Examples/blob/master/src/img/001_training.png "")<br><br>
#### 002 Tasseled Cap Transformation for Landsat 8 TOA imagery
Tasseled Cap Transformation for Landsat 8 TOA imagery based on the scientfic work "Derivation of a tasselled cap transformation based on Landsat 8 at-satellite reflectance" by M.Baigab, L.Zhang, T.Shuai & Q.Tong (2014).<br><br>
![alt text](https://github.com/renelikestacos/Google-Earth-Engine-Python-Examples/blob/master/src/img/002_brightness.png "")<br><br>
#### 003 Proba-V NDVI Comparison
Comparison on Proba-V NDVI (Normalized Difference Vegetation Index) Imagery. One NDVI is derived on the fly, the other one is the actual NDVI band provided by Proba-V.<br><br>
![alt text](https://github.com/renelikestacos/Google-Earth-Engine-Python-Examples/blob/master/src/img/003_ndvi.png "")<br><br>
#### 004 Retrieve Proba-V Time-Series
Display Proba-V NDVI (Normalized Difference Vegetation Index) Time-Series using Pandas and Matplotlib. Extracting Proba-V NDVI data from a randomly chosen point in Luxembourg.<br><br>
#### 005 Proba-V Time-Series Analysis
Basic Time-Series Analysis using Proba-V NDVI (Normalized Difference Vegetation Index) imagery.<br><br>
![alt text](https://github.com/renelikestacos/Google-Earth-Engine-Python-Examples/blob/master/src/img/005_timeseries.png "")<br><br>
#### 006 Linear Regression 
Linear regression on Proba-V, Landsat and Climate Hazards Group InfraRed Precipitation (CHRIPS) data. This tutorial demonstrates the comparison of one of the most common supervised machine learning methods, the linear regression. We are going to compare [scikit-learn](http://scikit-learn.org/stable/) and [Statsmodels](http://www.statsmodels.org/stable/index.html). For more information about types of Machine Learning, check this [link](https://towardsdatascience.com/types-of-machine-learning-algorithms-you-should-know-953a08248861).
<br><br>
#### 007 Time-Series Prediction and Forecast
Proba-V NDVI Time-Series Prediction, using Fourier extrapolation and ARIMA model. Multiple step Time-Series Forecast on Proba-V NDVI data using [Facebook Prophet](https://github.com/facebook/prophet). Landsat and Climate Hazards Group InfraRed Precipitation (CHRIPS) data were used as additional regressors. <br><br>
![alt text](https://github.com/renelikestacos/Google-Earth-Engine-Python-Examples/blob/master/src/img/007_timeseries_forecast.png "")<br><br>
#### 008 Google Earth Engine meets GeoPandas
Extracting Landsat 8 TOA and CHIRPS precipitation data from Google Earth Engine and use [Geopandas](http://geopandas.org/) capabilities to create time series analysis. Furthermore, data will be visualized through a time series viewer<br><br>
![alt text](https://github.com/renelikestacos/Google-Earth-Engine-Python-Examples/blob/master/src/img/008_geopandas.png "")
<br><br>

and also a precipitation heat map using [Folium](https://python-visualization.github.io/folium/).

![alt text](https://github.com/renelikestacos/Google-Earth-Engine-Python-Examples/blob/master/src/img/008_heatmap.png "")
<br><br><br><br>

