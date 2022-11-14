CPSC501 - Assignment 2: TensorFlow Neural Network Machine Learning

Assignment Description: 

The goal of this assignment is to explore four machine learning problems. There will be one Main machine learning problem that runs the length of the assignment, and then three others that are inter-leaved through-out the longer one. Each of these 4 parts of assignment should be stored in its own folder in a Gitlab project (Main/Part1/Part2/Part3).

The Main machine learning problem is to find a dataset, load this dataset into Python, view this dataset using MatPlotLib/Seaborn, process this dataset using NumPy/Pandas, and then using TensorFlow in Python train a model to use a portion of this dataset’s columns as input variables and in attempt to predict another column as an output variable. Finally, you will view the performance of this trained model using MatPlotLib/Seaborn again. Feasibility of the dataset size, and time to train a model is important here. You should avoid large image datasets, or video, and limit yourself to tables of data that could be stored in .csv files.

The inter-leaved smaller three machine learning problems (Part1/Part2/Part3) are the following: Part 1 is to improve the logistic regression accuracy of a MNIST digit image recognition model. Part 2 is to replace the MNIST image data with a harder set of letter representation data and train a good model for it. Part 3 is to create and develop a model for data loaded from a CSV file about Coronary Heart Disease and associated risk factors. These three smaller problems are designed to give you a chance to explore different aspects of TensorFlow and then apply learned lessons to the Main larger problem.

Main Dataset:

11 clinical features for predicting heart disease events. This dataset was created by combining different datasets already available independently but not combined before. In this dataset, 5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes. 

    Attribute Information:
    1.Age: age of the patient [years]
    2.Sex: sex of the patient [M: Male, F: Female]
    3.ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
    4.RestingBP: resting blood pressure [mm Hg]
    5.Cholesterol: serum cholesterol [mm/dl]
    6.FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
    7.RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST     elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
    8.MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
    9.ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
    10Oldpeak: oldpeak = ST [Numeric value measured in depression]
    11.ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
    12.HeartDisease: output class [1: heart disease, 0: Normal]

Citation:
fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved [Date Retrieved] from https://www.kaggle.com/fedesoriano/heart-failure-prediction.

