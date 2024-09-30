# Melanoma-Detection
 To develop a CNN-based model capable of accurately detecting melanoma, a form of cancer that can be fatal if not identified early. Melanoma is responsible for 75% of skin cancer-related deaths. Implementing a solution that can analyze images and notify dermatologists about the presence of melanoma could significantly reduce the manual effort required for diagnosis.





## Table of Contents
* [Problem Statement](#problem-statement)
* [Dataset](#dataset)
* [Project Workflow](#project-workflow)
* [Technologies](#technologies)


<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
 To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



## Dataset
The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Project Workflow

- **Data Loading and Understanding:** Define the paths for the training and testing images.
- **Dataset Creation:** Generate training and validation datasets from the training directory with a batch size of 32. Ensure the images are resized to 180x180 pixels.
- **Dataset Visualization:** Implement code to display one example from each of the nine classes in the dataset.
- **Model Building and Training:**
  - Construct a CNN model to accurately classify the nine classes in the dataset. During model development, apply rescaling to normalize pixel values between 0 and 1.
  - Select an appropriate optimizer and loss function for training.
  - Train the model for approximately 20 epochs.
  - Document your observations after training, focusing on any signs of overfitting or underfitting.
- **Data Augmentation:** Apply an appropriate data augmentation technique to address overfitting or underfitting.
- **Model Building and Training on Augmented Data:**
  - Build a CNN model to accurately classify the nine classes, ensuring image rescaling to normalize pixel values between 0 and 1.
  - Choose a suitable optimizer and loss function for training.
  - Train the model for approximately 20 epochs.
  - Evaluate and document if the previous issues (overfitting/underfitting) have been resolved.
- **Class Distribution Analysis:** Analyze the class distribution in the training dataset.
  - Identify which class has the fewest samples.
  - Determine which classes dominate the dataset in terms of sample proportion.
- **Handling Class Imbalance:** Correct any class imbalances in the training dataset using the Augmentor library.
- **Model Building and Training on Balanced Data:**
  - Build a CNN model to accurately classify the nine classes, ensuring image rescaling to normalize pixel values between 0 and 1.
  - Select an appropriate optimizer and loss function for training.
  - Train the model for approximately 30 epochs.
  - Document your observations after training and check whether the previous issues have been addressed.



## Technologies
- tensorflow v2.17.0
- Augmentor-0.2.12
- matplotlib
- pandas
- numpy
- keras

