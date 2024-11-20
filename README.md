# Project Name
CNN:Melanoma Detection Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Seborrheic Keratosis has least number of samples
With the base CNN model, the model is suffering from over-fitting
Training Accuracy: 79%
Validation Accuracy: 49%
To control the overfitting problem, we applied Data Augmentation Strategy. With this we can able to control the accuracy
Training Accuracy: 28%
Validation Accuracy: 20%
To improve the accuracy, we used the Augmentor package and handled the class imbalancce with 30 epochs
Training Accuracy:90%
Validation Accuracy:70%

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
IDE: Google Colaboratory, Google Drive
Language: Python
Libraries: Pandas, Numpy, Seaborn, Matplotlib, Sklearn, Keras, Tensorflow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by B.Ramu - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->