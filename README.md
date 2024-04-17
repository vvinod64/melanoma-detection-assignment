# Project Name
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

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


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- We aim to develop a Convolutional Neural Network (CNN) based model with the capability to accurately identify cases of melanoma. Melanoma, a form of skin cancer, can pose a severe threat if not detected at an early stage, constituting a significant portion of skin cancer-related fatalities (about 75%). The implementation of a solution capable of analyzing images and promptly notifying dermatologists about the presence of melanoma holds the potential to mitigate substantial manual effort currently involved in the diagnostic process.
- Our project focuses on leveraging machine learning techniques, specifically a CNN architecture, to address the critical problem of melanoma detection. The background of our endeavor is rooted in the urgency to enhance early diagnosis capabilities, thereby potentially saving lives and improving patient outcomes. By building an efficient model, we intend to streamline the diagnostic workflow for dermatologists and facilitate quicker interventions.
- Business Problem :
The core business problem we are addressing is the timely and accurate identification of melanoma cases. Detecting melanoma is pivotal due to its life-threatening implications, and automating this process can drastically reduce the time and effort required for manual evaluation. Our model aims to assist dermatologists by providing prompt alerts about potential melanoma occurrences, leading to improved patient care and efficient resource allocation.
- What is the dataset that is being used?
For this project, we are utilizing a comprehensive dataset of skin images that includes various types of skin lesions, including melanoma. This dataset enables our model to learn and recognize distinct features associated with melanoma. By training on diverse examples, we seek to develop a robust model capable of making accurate predictions when presented with new, unseen images. The availability of this dataset is pivotal for achieving our project's objective of creating an effective melanoma detection tool.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. **Model Training Progress**:
   - The model is trained for 20 epoch.
   - The training loss decreased progressively over the epochs, indicating the model's learning and convergence.
   - Training accuracy improved with each epoch, reaching approximately 91.18% by the end.

2. **Validation Performance**:
   - The validation accuracy improved consistently with each epoch, peaking at around 92.28%.
   - Validation loss decreased as the model learned, highlighting its ability to generalize well on unseen data.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python: The programming language used for writing the entire code.
- TensorFlow: An open-source machine learning framework used for building and training neural network models.
- Matplotlib: A plotting library used for creating visualizations, such as training curves and images.
- NumPy: A library for numerical computations in Python, used for working with arrays and mathematical operations.
- PIL (Pillow): Python Imaging Library, used for loading and manipulating images.
- Augmentor: A library for data augmentation, used for generating augmented images.
- Seaborn: A statistical data visualization library based on Matplotlib, used for creating bar plots.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements


## Contact
Created by [@vvinod64] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->