# Visualization-of-SVM-with-PIMA-Indian-Dataset

#### With the help of SVM(Support Vector Machine) I have trained the SVC(Support Vector Classifier) on PIMA Indians Diabetes Dataset

#### About the Dataset: The given dataset is a collection of SVM's measurements for 768 women of the PIMA Indian Heritage and their diagonosis of diabeetes. There are 8 clinical measurements or features out of which I have focused on 2 features i.e. Blood Glucose and BMI(Body Mass Index) where:
                          Blood Glucose: min = 0, max = 199, mean = 120.89
                          BMI: min = 0.0, max = 67.1, mean = 31.99  
                 
#### Filtering the data out of 0-valued instances:
                          Blood Glucose: min = 44, max = 199, mean = 121.94
                          BMI: min = 18.2, max = 67.1, mean = 32.45

#### Impementation of SVM on Linear Kernel:
                          Mean Accuracy on Train Data: 0.760
                          Mean Accuracy on Test Data: 0.770
                          
#### Implementation of SVM on RBF Kernel
                          Mean Accuracy on Train Data: 0.764
                          Mean Accuracy on Test Data: 0.765
                          
#### Producing even more non-linear solution by increasing the value of  𝛾 and putting it to 10:
                          Mean Accuracy on Train Data: 0.816
                          Mean Accuracy on Test Data: 0.757

#### Implementation of SVM on Polynomial Kernel
                          Mean Accuracy on Train Data: 0.726
                          Mean Accuracy on Test Data: 0.761
