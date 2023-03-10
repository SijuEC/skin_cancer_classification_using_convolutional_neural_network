# Skin Cancer Classification using a Convolution Neural Network
Classification of skin cancer type using a custom convolutional neural network in TensorFlow

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#Contact)
* [License](#License)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. 

In this project a solution in the form of a convolutional neural network is being explored.

This neural network is being trained on 2357 images from International Skin Imaging Collaboration (ISIC) of 9 skin cancer types. A part of this data will be used to train the dataset and the rest of the dataset will be used to validate how accurate the model is to correctly identify the type of cancer in the images.


## Conclusions
- The first neural network was overfitting. This meant that reularization methods for the model parameters and image augmentation methods for the training images is required while training the model.
- Upon implementation of dropout and image augmentation, it was seen that the model was not overfitting, but it started underfitting.
- An analysis of the number of images in each of the categories, showed that the data was imbalanced between the different skin cancer types.
- Once rebalancing of the data was performed along with normalization of the parameters of the model, it was seen that the model performed admirably on the data with an accuracy of about 80% on the validation data.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pathlib - version 1.0.1
- tensorflow - version 2.11.0
- tensorflow.keras - version 2.11.0
- matplotlib - version 3.5.3
- numpy - version 1.22.4
- pandas - version 1.3.5
- PIL - version 22.0.4
- google.colab - version 1.0.0
- Augmentor - version 0.2.10

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
<!-- This project was inspired by... -->
- References
  - Images from International Skin Imaging Collaboration (ISIC) [https://challenge.isic-archive.com/data/](https://challenge.isic-archive.com/data/)
  - Downloading datasets into Google Drive via Google Colab (link: https://towardsdatascience.com/downloading-datasets-into-google-drive-via-google-colab-bcb1b30b0166)
<!-- This project was based on [this tutorial](https://www.example.com). -->


## Contact
Created by [@SijuEC] - feel free to contact me!


<!-- Optional -->
## License
This project is open source and available under the [MIT License]().

<!-- You don't have to include all sections - just the one's relevant to your project -->
