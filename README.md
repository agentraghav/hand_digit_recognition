# hand_digit_recognition
In this project we have with the help of knn machine learning classify the hand written digits from MNIST database.
To know about what is kNN go to [KNN machine learning](http://scikit-learn.org/stable/modules/neighbors.html)

# How to start:
1.   Download the MNIST datasets in your system from the given link [MNIST datasets](http://yann.lecun.com/exdb/mnist/). Download all four files and unzip them.
2.   After downloading and unzipping all files . Make sure that  Anaconda which is a free and open source distribution of the Python and R programming languages for data science and machine learning related applications is available on your system 
     and if not then download it from the given link [Anaconda](https://www.anaconda.com/download/#download)
3.   After Downloading Anaconda open Anaconda navigator on your system and then in that navigator launch jupyter notebook 
4.   In that juputer notebook open the given file in this repository and that is knn digit recognition.ipynb 

# How it works:

1.   In this it takes input of images from the MNIST dataset , that are hand written digits and predict the output of the given number .
     Through knn machine learning it shows 99% accuracy 
2.   Each image is a 28 by 28 pixel square (784 pixels total). A standard spit of the dataset is used to evaluate and compare models, where 60,000 images are used to train a model and a separate set of 10,000 images are used to test it.
     It is a digit recognition task. As such there are 10 digits (0 to 9) or 10 classes to predict. Results are reported using prediction error, which is nothing more than the inverted classification accuracy.
3.   The given result is shown in a form of confusion matrix . To know what a confusion matrix is and how to implement it [Confusion Matrix](http://scikit-learn.org/stable/auto_examples/model_selection/plot_confusion_matrix.html)
## your output is shown in given format where diagonals of matrix shows the accuracy
  ![screenshot_2018-09-11 knn digit recognition 2](https://user-images.githubusercontent.com/35917821/45347389-99e86b80-b5c9-11e8-9edb-b9c786ae8687.png)
  
4.   In this datasets we have checked for digit 2,3 and 8 and predicted their result
5.   This also shows the images that are miss readed as 3 instead they are 8

##  the given image shows the images that are miss predicted as 3 instead of 8 
  ![screenshot_2018-09-11 knn digit recognition 1](https://user-images.githubusercontent.com/35917821/45347796-8b4e8400-b5ca-11e8-95fd-c451525fc943.png)
