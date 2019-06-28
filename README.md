
#### Machine Learning - Decision Trees

# CreditCard--Fraud-Dection

![fb](images/am9.png)


# Background

Dataset consists of 3000 Amazon customer reviews, star ratings, date of review, variant and feedback of various amazon Alexa products like Alexa Echo, Echo dots.

* Dataset: www.kaggle.com/sid321axn/amazon-alexa-reviews


# Goals

* Discover insights into consumer reviews and perfrom sentiment analysis on the data.
* Split the data in Train and Test
* Train and Test the model in the data set
* Visualize data
* Get best accuracy 



# How to run 

Open Google Colab https://colab.research.google.com/
* File
* Upload Notebook
* Run the Cells


# Proccess

Import the data set and visualize the data

* Data set
#  
![fb](images/am1.png)

* Visualizing data points
#  
![fb](images/am3.png)

* Histogram (bins=5)
#  
![fb](images/am4.png)

Transforming the data
* Drop collumns
* Apply Dumies at Variation Collumn
* Add the encoded column again
* Concatenate them together

#  
![fb](images/am5.png)
Training Train and Test

#  

![fb](images/am6.png)
Evaluating the model
#  
![fb](images/am7.png)

Improve the model
* Droping the variations and add review length as a feature
* Apply randomforest_classifier
#  
![fb](images/am8.png)

Final Model represented by Confunsion Matrix
#  
![fb](images/am9.png)
