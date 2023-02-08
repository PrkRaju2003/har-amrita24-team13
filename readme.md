
## Poster

![alt text](https://github.com/PrkRaju2003/har-amrita24-team13/blob/main/Team13_Poster.png)



## Team Members
P Ramakrishna Raju - CSE20134
M Nitin Sai - CSE20092
N Ravi Kiran - CSE20010
N V Siva Sai - CSE20109
N V Shanmukhnathreddy - CSE20108





## Description

Using Smartphones sensors such as linear accelerometer(a), gyroscope(w),
g-Force(gF) in 3 axes x,y,z based on them we have captured 9 features.
These features were recorded using an app called Physics ToolboxSuite in an interval
of 0.011 seconds.
Feature extraction has been done based on characteristics like mean,median,mode.....
and finally we have arrived at 111 features at 2.56 second interval.
While testing k-NN classifier gave us the best accuracy of 89% for 6 activities.
There are 6 activities in our dataset they are LAYING,SITTING,STANDING,WALKING,WALKING_DOWNSTAIRS,WALKING_UPSTAIRS
While bi-classification we combine LAYING,SITTING,STANDING into STATIONARY and
WALKING,WALKING_DOWNSTAIRS,WALKING_UPSTAIRS into MOVING.
Doing so SVM gave us 100% accuracy.
We have been finally able to provide activity output of a person along with timestamp.

## Usage
Record sensor data in Physics Toolbox Suite App after stopping the recording. You obtain a file called sensor2.csv
Send this file to your PC and change the filepath in Project.ipynb and execute all code cells.


