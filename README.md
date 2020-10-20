# Diabates Detector
 A web app that predicts if you have diabetes based on the report inputs using machine learning
 ![Home](https://github.com/kamaravichow/diabates-detector-app/raw/main/docs/home.png)
 
 ## Requirements 
 Pandas - ``` pip install pandas ```
 - pandas is a Python package that provides fast, flexible, and expressive data structures designed to make working with structured (tabular, multidimensional, potentially heterogeneous) and time series data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real world data analysis in Python.

 Scikit-learn - ```pip install -U scikit-learn```
 - Simple and efficient tools for predictive data analysis Accessible to everybody, and reusable in various contexts Built on NumPy, SciPy, and matplotlib
 
 Pillow - ```pip install Pillow```
 - Pillow is the friendly PIL fork by Alex Clark and Contributors. PIL is the Python Imaging Library by Fredrik Lundh and Contributors.
 
 StreamLit - ```pip install streamlit```
 - Streamlit’s open-source app framework is the easiest way for data scientists and machine learning engineers to create beautiful, performant apps in only a few hours!
 
 or just use ```pip install requirements.txt``` to install all the above packages.
 
 ## Dataset 
 
- This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.
 
The dataset was taken from kaggle at : https://www.kaggle.com/uciml/pima-indians-diabetes-database

|![Stats](https://github.com/kamaravichow/diabates-detector-app/raw/main/docs/stats.png)| ![Prediction](https://github.com/kamaravichow/diabates-detector-app/raw/main/docs/predictions.png)|
|---|---|

## Run
Use the following command to run it on your local machine 

```bash 
streamlit run "C:\PATH_TO_FOLDER\diabates-detector\app.py"
```
This should open up a browser window automatically to a locally hosted website.

## Liked it ?
If you liked it feel free to star the repo or fork it to start contributing. If you find something wrong or have an idea to improve this, just open an issue or tag me in a tweet on [twitter](https://www.twitter.com/kamaravichow)
