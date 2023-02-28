# BreakThrough-Tech-AI

### Objective

Motion recognition is beneficial to the commercial, manufacturing, as well as medical sectors. With these techniques we can monitor patients remotely, or determine if a person’s gait is deteriorating because of a medical issue. In this project, we use IMU (Inertial Measurement Unites) data to simulate and detect different categories of human motion by using Machine Learning and Deep Learning approaches.


### Impact
Enable the next generation of wearable electronic devices with motion recognition


### Dataset
We have used openly available IMU dataset collected by a waist-mounted smartphone with embedded inertial sensors from UCI Machine Learning Repository. Our dataset includes:

-	Triaxial acceleration from the accelerometer and the estimated body acceleration

-	Triaxial Angular velocity from the gyroscope

-	561- feature vector with time and frequency domain variables

-	Activity label：
	Walking
	Walking_upstairs
	Walking_downstairs
	Sitting
	Standing
	Laying
-	An identifier of the subject who carried out the experiment


### Functional Approach and Steps
1.	Perform data cleaning if there is missing values.
2.	Use Statistics and Machine Learning Toolbox and/or Deep Learning Toolbox to classify categories of human motion in the data
3.	Train the classification algorithm with default parameters and evaluate the model performance for train, test, and validation data
4.	Improve model performance using Hyperparameters tuning and feature selection techniques
Technologies used
1.	MATLAB Classification Learner App
2.	MATLAB Deep Learning Toolbox


### Conclusion
We have reduced our dataset from 561 features to 300 features by using PCA. After detailed examination and evaluation, we decided to use KNN as our final model with 96.4% accuracy on validation set. For the further steps, we may train our model on human motion data captured by ourselves and run our AI classification algorithms on real hardware.

