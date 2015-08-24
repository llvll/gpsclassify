# GPSclassify
### Classification and visualization of OpenStreetMap GPS traces using GeoDjango, PostGIS and TinyLearn

*[Under development]*

Web application for labeling, visualizing and searching GPS traces from the bulk GPX dataset of OpenStreetMap: http://planet.openstreetmap.org/gps 

The processing pipeline applies machine learning algorithms for labeling the spatial data and further indexing into ElasticSearch.

The following frameworks and technologies are involved:

* GeoDjango
* OpenLayers
* PostGIS
* Haystack
* ElasticSearch
* TinyLearn
* Scikit-Learn
* GeoPandas
* Shapely

This module is partially based on another GitHub project for motion pattern recognition using KNN-DTW and sequence labeling: https://github.com/llvll/motionml

IPython Notebook (.ipynb file) is included for step-by-step execution of the demo application with extra comments.

This code is using TinyLearn framework, which simplifies the classification tasks with Python and the following modules: 

* Scikit-Learn
* Pandas
* OpenCV
* Other libraries, like FastDTW

TinyLearn framework is still at an early development stage. Please use with caution and feel free to ask any questions: oleg.v.puzanov@gmail.com
