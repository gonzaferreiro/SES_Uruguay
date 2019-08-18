# SES_Uruguay

This repository was created as a playful project with the objective of analyzing the Socioeconomic Status in Uruguay, using data from a national survey. In frist instance I tried to replicate using machine learning the socioeconomic classification used by the national institute of statistics, to afterwards do my own clsutering and see if the model was capable of finding any kind of pattern within the data. 

Some of the tools used throughout the notebook:

* **Dataset cleaning**: binarizing several variables and removing some others after carefully reading the dictionary provided by the national institute of statistics of Uruguay

* **Classification models**: trying to replicate the institute socioeconomic levels

* **Model using new target**: created out of the household income percentiles with ad-hoc function

* **PCA to reduce the number of features + modelling**: comparing the results with the previous models created

* **Clustering**: which unfortunately did not result in a neat grouping of any kind
