<hr style="border-top: 1px solid #001a79;" />
<h1 style="color: #001a79;">ATU - Atlantic Technological University</h1>
<h1 style="color: #001a79;">Machine Learning and Statistics</h1>
<hr style="border-top: 1px solid #001a79;" />

<br>


<h2 style="color: #001a79;">1. Quickview</h2>
<hr style="border-top: 1px solid #001a79;" />

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/CiaranMoran27/machstat-assessment/blob/main/time_series_anomaly_detection.ipynb) 

<br>

<h2 style="color: #001a79;">2. Overview</h2>
<hr style="border-top: 1px solid #001a79;" />
This repository contains all the files relevant to my Machine Learning and Statistics Assessment. The Assessment <br>is broken into 2 parts:<br><br>

1. **Practical Exercies:** (located in the practicals folder).<br>
These exercies explore the following:<br><br>
    - Statistics: 
        - [The Lady Tasting Tea Problem](https://en.wikipedia.org/wiki/Lady_tasting_tea).
        - [T-tests](https://en.wikipedia.org/wiki/Student%27s_t-test).<br><br>
    - Modelling and Parameters:
        - [The Absolute Value Function](https://en.wikipedia.org/wiki/Absolute_value).
        - [Fitting Straight Lines](https://en.wikipedia.org/wiki/Linear_regression).
        - [Fitting Polynomials](https://en.wikipedia.org/wiki/Polynomial).
<br>
<br>

2. **Time Series Anomaly Detection with Keras**.<br>
This part of the assessment explores time-series anomaly detection using a type of artificial neural network<br>
called an autoencoder. The project levarages the [Keras documentation](https://keras.io/examples/timeseries/timeseries_anomaly_detection/), which describes the neural network<br>
model used as a reconstruction convolutional autoencoder model. The idea here is that our model can learn<br>
its own parameters in lower-dimensional space and re-construct itself to give us a metric on the "baseline"<br>
noise that is considered acceptable. When the model is tested against a datset with anomalies the "baseline"<br>
noise is exceeded and the data is labelled as anomalous. We will detail what role convolution plays in the<br>
project and we will explore:
    - How Neural Networks & Autoencoders work.
    - Data Standardization  & Transformation.
    - Activation Functions (ReLU and Sigmoid).
    - Optimisers (Adam and Gradient Descent).
    - Training our Model.
    - Evaluation of Model Performance.
    - Detecting the Anomaly.
    

<br>
<br>

<h2 style="color: #001a79;">3. Contents of repository</h2>
<h4 style="color: #001a79;">(Not including this README and the gitignore file.)</h4>
<hr style="border-top: 1px solid #001a79;" />

1. **Practicals Folder**: <br />  
    - This Folder contains 5 Jupyter notebooks that answer the Practical Exercises from Section 2.1.<br>
        - 01-statistics-part1-exercise.ipynb.
        - 01-statistics-part2-exercise.ipynb.
        - 02-models-part1-exercise.ipynb.
        - 02-models-part2-exercise.ipynb.
        - 03-parameters-part1-exercise.ipynb.      
        
<br>

2. **time_series_anomaly_detection.ipynb**:  
    - This notebook explores time series anomaly detection using an autoencoder.<br>
          
<br>

3. **Images Folder**: <br />  
    - This Folder contains images that help describe neural networks and autoencoders. These images<br>
    are used in the time_series_anomaly_detection.ipynb notebook.<br>

<br>

4. **requirements.txt file**: <br />  
    - This file contains the packages necessary to run the files in this repository (Note: Download Keras &<br>
    TensorFlow seperately as per section 4 below).
    
<br>
<br>
<br>


<h2 style="color: #001a79;">4. Running notebooks locally</h2>
<hr style="border-top: 1px solid #001a79;" />

1. Download [Anaconda](https://docs.anaconda.com/anaconda/install/index.html), this contains the python 
interpreter and libraries needed to run this notebook.
2. Download [Keras and Tensorflow](https://www.activestate.com/resources/quick-reads/how-to-install-keras-and-tensorflow/) for making a neural network.
2. Download [cmder](https://cmder.app/) if working on a Windows Operating System, alternatively use the basic *command<br>
line interface* if working on a Linux or Mac operating system.
3. Clone my [repository](https://github.com/CiaranMoran27/machstat-assessment) as laid out [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).
4. Run '*jupyter notebook*' command on:
    - *Cmder* if working on a Windows operation system.
    - *Command line interface* if working on a Linux or Mac operating system.
 
<br>
<b>Note:</b>
Although Anacondas contains some of the required packages to run all the notebooks in this repository,<br>
you can download the missing packages from the requirements.txt file by running the following command<br>
(adjust path accordingly). <br />

``` Python
pip install -r /path/requirements.txt
```