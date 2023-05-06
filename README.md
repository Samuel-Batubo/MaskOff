# MaskOff
#Spot the Mask Challenge

The objective of this Project is to create an image classification machine learning model to accurately predict the likelihood that an image contains a person wearing a face mask, or not. The total dataset contains 1,800+ images of people either wearing masks or not.

##Table of Content
* [Instalations](#Installation)
* [Project Motivation and Description](#Motivation)
* [File Description](#Description)
* [Observations and Results](#Results)
* [Limitation](#Limitation)
* [Licensing, Author, Acknowledgement](#Licensing)

## Installation
The code requires Python versions of 3.*, torchvision, cv2, keras and general libraries available through the Anaconda package.

## Project Motivation and Description <a name="motivation"></a>
*Face masks have become a common public sight in the last few months. 
*The Centers for Disease Control (CDC) recently advised the use of simple cloth face coverings to slow the spread of the virus and help people who may have the virus and do not know it from transmitting it to others. 
*Wearing masks is broadly recognised as critical to reducing community transmission and limiting touching of the face.

*In a time of concern about slowing the transmission of COVID-19, increased surveillance combined with AI solutions can improve monitoring and reduce the human effort needed to limit the spread of this disease. 

*The objective of this challenge is to create an image classification machine learning model to accurately predict the likelihood that an image contains a person wearing a face mask, or not.

## File Description <a name="description"></a>
This project includes one Jupyter notebooks, one pickled files, two images file,  one csv file. The .ipynb file titled 'Computer_Vision_FaceMaskDetection.ipynb' contains the code that creates the c>


## Results
A summary of the main findings and lessons of this project can be found in this blog post on [Medium](https://xxxxxxxxxxxxxxxxxxxxxxxxxxxx>

*The train_label .csv file has over 1300 observations
*The image directory has over 1800 files, meaning some files are not available on the train_label csv file
*The names of the file as used as the records for the image column in the train_label csv file.
*Therefore the train_label csv file contains the train data path for the train data and the rest files in the image directory contains the test data


## Limitations
There are a number of limitations of this project and the chosen implementation:
* Experiment was only done on limited available data.
* Some images were found blury making it difficult for the model to classify.

## Licensing, Authors, Acknowledgements <a name="licensing"></a>
The data used for the analysis comes from:
* [Zindi](https://zindi.africa/competitions/spot-the-mask)

Feel free to use the code as you please and play around with it.

