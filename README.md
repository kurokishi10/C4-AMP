# Week 1

Install matplotlib, numpy, csv, scipy and sklearn on your systems using 
```
pip install matplotlib, numpy, csv , scipy, sklearn
```

## NP.py

Go through the content of this file as most of the functions we'll be using in numpy are defined and the workings are explained.

**Remember you'll be using pip or pip3 depending on your python versions installed, just make sure you install it for python3 if you're running multiple versions of python on one system**

## Linear regression with one variable

Once you've installed, give yourself a moment and go through the test data 'ex1data.txt'.

You'll be using the above file for the first exercise, which is implementing linear regression with one variable.

The main components of the first part are given as below: 
* __singleVariableMain.py__
The main file for the program, which will be using the other files to run the program. Go through it once to see how we load in the data, visualize it, and preprocess it for training.

* __computeCost.py__
The main file for computing the cost between predicted and actual values. It's your job to complete this file to get the desired result, as mentioned in the comments whitin the file.

* __gradientDescent.py__
The main file for actually implementing the gradient descent algorithm. It's your job (Again) to complete this file to get the desired results as mentioned in the comments within the file.


## Linear regression with two variables

You'll be using the data in 'ex1data2.txt' for this exercise.
* __multiVariableMain.py__
The main file for this exercise which will use the other files to run the program. Go through it to see how multiple features are read in and accoomodated for by the program. 
* __featureNormalization.py__
This is the only file you'll need to edit for the program to work. The task you need to complete will be mentioned within the file itself in the form of comments.

## Logistic Regression

Take a moment to go through the file 'ex2data1.txt' as it'll be containing the text data we'll be using for this exercise
The first column represents the marks of students in Exam 1 and the second oclumn represents the marks of students in Exam 2. The third column is a 1 or 0 valued column, indicating whether the student was selected in the program or not.

The main components of  the file are given below:
* __logisticmain.py__
The main file for the program, which will be using the other files to run the program. Go through it once to see how we load in the data, visualize it, and preprocess it for training. This time we'll be using the _minimize_ function provided by **scipy** to help the computer determine the best parameters for our model by itself.

* __loadData.py__
The file that contains the function for loading the data into the program, it's been completed already so you can see how we load data here, no need to edit it.

* __plotData.py__
The file that contains the function for plotting the data. It's been separated so as to allow us to plot multiple times if we want to.

* __costFunction.py__
The file that contains the cost function and gradient descend algorithms that need to be completed by you

* __sigmoid.py__
The file that contains the function for applying sigmoid to a numpy array. **Make sure you complete this file first before proceeding to the costFunction file.**


In order to get the desire result, navigate the the directory containing the files i.e.:
```
cd your-path-to-the-folder/Week1
```
And run the file from there 
