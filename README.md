# frtproject
                                                           Handwritten Digit Recignition
OBJECTIVE:

        Designing a project from the MNIST dataset to identify digit classification using the SVM algorithm.

PROBLEM STATEMENT:

            To develop a model using Support Vector Machine which would correctly classify the handwritten digits from 0-9 based on the pixel values given as features. 
            Given MNIST dataset, which is a large database of hand written digits. The 'pixel values' of each digit (image) comprise the features, and the actual 
            number between 0-9 is the label. Since each image is of 28 x 28 pixels, and each pixel forms a feature, there are 784 features.

PLATFORM USED: 

          Used Google Colaboratory to make the .ipynb file.

ALGORITHM USED: 

         SVM (Support Vector Machine) Algorithm. 
         “Support Vector Machine” (SVM) is a supervised machine learning algorithm which can be used for both classification and regression challenges. 
         However, it is mostly used in classification problems.

STEPS FOLLOWED IN BUILDING THE MODEL:

• Given data set contains the pixel values of an image which has a handwritten number in it. Our goal is to find that handwritten number.

• Each image has 784 pixels.

• Necessary libraries like pandas, numpy, matplotlib.pyplot,seaborn are imported.

• Read the given data and analyzed it (it has 26391 rows and 785 columns).

• The data has unique entries of digits 0,1,2,3,4,5,6,7,8,9.

• Some digits are visualized by plotting them using mayplotlib.pyplot taking the pixel values as inputs.

• Divided the input and output data (the column ‘label’ is the output and remaining all other columns are inputs).

• Input has been scaled importing scale from sklearn.

• Divided the given data into training and testing data.

• Used SVC from sklearn.svm as classifier.

• Started first trial as linear model taking kernel as ‘linear’.

• Data is fit into the model and output is predicted. An accuracy of 91.05% is achieved using linear model.

• Tried a non-linear model taking kernel as ‘poly’ kernel.

• Data is fit into the model and output is predicted. An accuracy of 93.11% is achieved using non-linear model taking ‘poly’ kernel.

• Tried another non-linear model taking RBF kernel.

• Data is fit into the model and output is predicted. An accuracy of 95.92% is achieved using non-linear model taking ‘rbf’ kernel.

• So, maximum accuracy of 95.92% is achieved using non-linear ‘rbf’ kernel.

• Some pictures have been made visualizing the final model.The model gave an accuracy of 95.92%

CONCLUSION:

          A Machine learning model was built which predicts the digit  given in an image taking the pixel values of each image. It is achieved using 
          Support Vector Machine algorithm which works by creating a line or hyperplane that separates the data into classes. SVM is implemented using different kernels.
          An accuracy score of 95.92% is achieved using RBF kernel.
