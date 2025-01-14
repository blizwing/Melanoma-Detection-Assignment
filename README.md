# Skin Cancer Classification with Convolutional Neural Networks

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project implements a multiclass classification model using a custom CNN in TensorFlow to detect melanoma, a deadly form of skin cancer. Early detection is crucial, and this model aims to assist dermatologists by evaluating images and alerting them to the potential presence of melanoma.

- Dataset
The dataset consists of 2357 images of malignant and benign skin lesions from the International Skin Imaging Collaboration (ISIC). It includes nine classes:

  1. Actinic keratosis
  2. Basal cell carcinoma
  3. Dermatofibroma
  4. Melanoma
  5. Nevus
  6. Pigmented benign keratosis
  7. Seborrheic keratosis
  8. Squamous cell carcinoma
  9. Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
#### Model Evolution:

Initial model showed significant overfitting
Second iteration improved with data augmentation
Final model achieved balanced performance after class rebalancing

#### Improvements Made:

Implemented data augmentation techniques
Applied class rebalancing using Augmentor
Added dropout layers and batch normalization
Introduced callbacks for early stopping and learning rate adjustment

#### Final Model Performance:

Achieved approximately 65% accuracy
Showed good generalization between training and validation sets
Maintained consistent performance across different classes
Successfully addressed the initial overfitting problem


#### Challenges Addressed

Resolved class imbalance by augmenting underrepresented classes
Mitigated overfitting through regularization techniques
Improved model generalization while maintaining accuracy

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- TensorFlow
- Keras
- Augmentor
- Matplotlib
- NumPy
- Pandas

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@blizwing] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
