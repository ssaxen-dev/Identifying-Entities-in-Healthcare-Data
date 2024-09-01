# Identifying Entities in Healthcare Data - Syntactic Processing Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.

we need to perform the following broad steps:

- You need to process and modify the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
- After that, you need to define the features to build the CRF model.
- Then, you need to apply these features in each sentence of the train and the test dataset to get the feature values.
- Once the features are computed, you need to define the target variable and then build the CRF model.
- Then, you need to perform the evaluation using a test data set.
- After that, you need to create a dictionary in which diseases are keys and treatments are values.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Based on the models created accuracy increased from 90.7 to 91.06 which helps in predicting the treatment for disease name 'hereditary retinoblastoma' is 'radiotherapy'

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Jupyter
- Spacy
- Sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- As part of upgrad's assignment for Identifying Entities in Healthcare Data - Syntactic Processing
- References if any - Upgrad's live classes & Tutorials
- Dataset provided by Upgrad
- Google


## Contact
Created by [@ssaxen-dev] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->