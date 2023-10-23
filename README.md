# ML_UniLabs_Notebooks
## A repo all about the labs of Machine Learning Course at Ain shams University 

## NoteBook 1
### Multiple Linear Regression for Robot Calibration
In this lab, we will illustrate the use of multiple linear regression for calibrating robot control. In addition to reviewing the concepts in multiple linear regression , you will see how to use multiple linear regression for time series data -- an important concept in dynamical systems such as robotics.
The data is from a three link robot:

![TUDORBild](https://github.com/ElecSpartan/ML_UniLabs_Notebooks/assets/112751175/190700dd-e154-4044-84a0-ddea8784ac88)

We will focus on predicting the current draw into one of the joints as a function of the robot motion. Such models are essential in predicting the overall robot power consumption. Several other models could also be used.
The full MERIt dataset can be obtained from the MERIt site. But, this dataset is large. We include only two of the ten experiments. Each experiments corresonds to 80 seconds of recorded motion. We will use the following files:

- exp1.csv for training
- exp2.csv for test
