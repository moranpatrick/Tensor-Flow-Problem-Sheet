# Problem Set: Tensorflow
Patrick Moran  
g00179039@gmit.ie  
This repository contains the soloutions to a Problem [sheet](https://emerging-technologies.github.io/problems/tensorflow.html) for my Forth Year Emerging technologies Module.

## How To Use this Repository?
This problem sheet was completed using Jupyter Notebook. The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more. You can try out the notebook on their website or click [here](https://try.jupyter.org/).  

To install Jupyter click [here](http://jupyter.org/install.html) for full instructions. I reccomend downloading the latest version of anaconda which comes with python and jupyter.

You can view the notebook in this repository [here](https://github.com/moranpatrick/Tensor-Flow-Problem-Sheet/blob/master/TensorFlow-Iris-Problem-Sheet.ipynb) but you cannot interact with it. See "Running your own Notebook" below for more.

### Tensor Flow
Tensorflow, released by Google in 2015, is an open source software library which allows developers to build and train deep learning models. To see it in action [click here](http://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.06501&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false). Tensorflow is written in python and is used for machine learning using neural networks. More information including lots of tutorials can be found [here](https://www.tensorflow.org/get_started/).

## Running your own Notebook
Step 1. To run this notebook on your own machine make sure have tensor flow installed. Full instructions on how to install tensorflow can be found [here](https://www.tensorflow.org/install/).   
Step 2: Download the requirements.txt file from this repository.  
Step 3: Open the notebook in this repository.  
Step 4: Click Raw. (Its On the right)  
Step 5: Right Click somewhere over the text and click "Save as"  
Step 6: Remove the .txt extension from the end. Make sure the file is saved as .ipynb  
Step 7: Make sure you download the iris.csv file from the repository and save it to the same directory as the notebook. Make sure the requirements.txt file is saved here also.   
Step 8: Open a command prompt where the files you downloaded are saved.    
Step 9: Then Activate the virtual envoirnment   
>\> activate tensorflow   

Install the requirements inside.   
>(tensorflow)\> pip install -r requirements.txt 

Then Type 
>\> jupyter notebook  

Step 10: This will open the notebook at the directory level in your browser. Click on the notebook you saved. (TensorFlow-Iris-Problem-Sheet
.ipynb) and your good to go. 

# TensorFlow Problem Sheet
These problems relate to the Python package [Tensorflow](https://www.tensorflow.org/). We will again use the famous [iris data set](https://en.wikipedia.org/wiki/Iris_flower_data_set). Save your work as a single Jupyter notebook file in a GitHub repository. Include any required data files, a README, and a gitignore file in the repository.

## 1. Use Tensorflow to create model

Use Tensorflow to create a model to predict the species of Iris from a flower’s sepal width, sepal length, petal width, and petal length.

## 2. Split the data into training and testing

Split the data set into a training set and a testing set. You should investigate the best way to do this, and list any online references used in your notebook. If you wish to, you can write some code to randomly separate the data on the fly.

## 3. Train the model

Use the testing set to train your model.

## 4. Test the model

Use the testing set to test your model, clearly calculating and displaying the error rate.
