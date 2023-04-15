# Use-SVM-to-do-classification

This repository contains the code for both binary and multiclass classification tasks to identify different types of physical activities. The purpose of this project is to accurately classify various physical activities using machine learning algorithms.

Dataset
The dataset used in this project contains 7767 objects and 564 variables. It includes measurements related to different physical activities. The dataset is split into training and validation sets.

Dependencies
To run the code, you will need the following software and libraries installed on your machine:

R (version >= 4.0.0)
RStudio (optional, but recommended)
The following R packages:
caret
e1071
rpart
xgboost
lightgbm
keras (for the neural network model)
tensorflow (for the neural network model)
You can install the R packages using the following command in R:

R
Copy code
install.packages(c("caret", "e1071", "rpart", "xgboost", "lightgbm", "keras"))
For the keras and tensorflow installation, follow the instructions in the comments of the code.

Usage
Clone this repository or download it as a zip file.
Open the R script files binary_classification.R and multiclass_classification.R in RStudio or your preferred R environment.
Set your working directory to the location where you saved the script files.
Run each script. The scripts will preprocess the data, train the models, and evaluate their performance using F1 score and accuracy. The results will be printed in the R console.
Results
By running the scripts, you will be able to reproduce the results for both binary and multiclass classification tasks using various machine learning models such as Support Vector Machines (SVM), Gradient Boosting, and Neural Networks. The performance of each model will be evaluated, and the confusion matrices will be printed in the console.

For any issues or questions, please open an issue in this repository or contact the author.
