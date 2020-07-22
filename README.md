# Fashion Classification
A machine learning model that classifies clothing items.This is the basis of Amazon's echo look, a virtual assistant that provides the user with new fashion recommendations based on the user's physique, style preference and latest trend.  
This model can be also used to perform targeted marketing. 

Dataset not added in the repo but can be downloaded from the link: https://www.kaggle.com/zalando-research/fashionmnist 

## Table of contents
* [Technologies](#technologies)
* [Data](#data)
* [Model Details](#modeldetails)



## Technologies
  The following technologies were used for this part of the project:
  * Python 3
  * Jupyter notebook
  * Pandas: Python package for data analysis
  * Matplotlib and Seaborn: Python 2D plotting library
  * Sklearn: Python package for modeling creation
  
## Data   
The data set for this project consists of 70,000 images whihc is divided into 60,000 training sample and 10,000 testing sample. Each image is on 28x28 grayscale with 1 out of 10 label classes. The 10 classes are listed below: 0 - T-shirt/top 1 - Trouser 2 - Pullover 3 - Dress 4 - Coat 5 - Sandal 6 - Shirt 7 - Sneaker 8 - Bag 9 - Ankle Boot

The image has a width and height of 28 pixel which comes up to 784 pixels in total. Each pixel has a pixel value which translates to the grey shade. The values ranges from 0 to 255. The higher the value, the darker the pixel is.
  
  
  
 ## Model Details
 The image below shows the images in the training set with a width and height of 28 pixel which comes up to 784 pixels in total.  
 <img width="564" alt="image_in_grid" src="https://user-images.githubusercontent.com/39994111/86512488-16ef6f80-be46-11ea-8863-44b0506e40ff.png">
 
 The image below shows the model classification report
 
<img width="587" alt="model_classification_report" src="https://user-images.githubusercontent.com/39994111/86512599-d9d7ad00-be46-11ea-851e-45005507b76e.png">
 
 The following image shows the image classification done on the test set
<img width="831" alt="model_prediction" src="https://user-images.githubusercontent.com/39994111/86512612-efe56d80-be46-11ea-93aa-e6fa73742f77.png">

