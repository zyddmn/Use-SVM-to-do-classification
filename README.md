## Use-SVM-to-do-classification

This repository contains the code for both binary and multiclass classification tasks to identify different types of physical activities. The purpose of this project is to accurately classify various physical activities using machine learning algorithms.

# Dataset
The dataset used in this project contains 7767 objects and 561 variables. It includes measurements related to different physical activities. The dataset is split into training and validation sets.

# Feature Description 
The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low-pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low-pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also, the magnitude of these three-dimensional signals was calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

Finally, a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

These signals were used to estimate the variables of the feature vector for each pattern:  
'-XYZ' denotes 3-axial signals in the X, Y, and Z directions.

# Dependencies
To run the code, you will need the following software and libraries installed on your machine:

R (version >= 4.0.0)
RStudio (optional, but recommended)
The following R packages:
dplyr
glmnet
rpart
caret
e1071
You can install the R packages using the following command in R:

```{r}
install.packages(c("dplyr", "glmnet", "rpart", "caret", "e1071"))
```

# Usage
1. Clone this repository or download it as a zip file.
2. Open the R script files binary_classification.R and multiclass_classification.R in RStudio or your preferred R environment.
3. Set your working directory to the location where you saved the script files.
4. Run each script. The scripts will preprocess the data, train the models, and evaluate their performance using F1 score and accuracy. The results will be printed in the R console.

# Results
By running the scripts, you will be able to reproduce the results for both binary and multiclass classification tasks using two different machine learning models include Decision Tree and Support Vector Machines (SVM). The performance of each model will be evaluated, and the confusion matrices will be printed in the console.

For any issues or questions, please open an issue in this repository or contact the author.
