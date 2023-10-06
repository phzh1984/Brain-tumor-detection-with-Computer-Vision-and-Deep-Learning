# Brain-tumor-detection-with-Computer-Vision-and-Deep-Learning

Introduction

A brain tumor is a medical condition in which abnormal cells form within the brain. These tumors can be categorized into two main types: cancerous (malignant) tumors and benign tumors. Primary tumors originate within the brain, while secondary tumors, known as brain metastasis tumors, spread from elsewhere in the body. Symptoms of brain tumors can vary, depending on the location within the brain, and may include headaches, seizures, vision problems, vomiting, and mental changes. Notably, morning headaches that improve with vomiting are a common symptom. As the disease progresses, more severe symptoms such as difficulty walking, speaking, or changes in sensations may develop, and unconsciousness may occur.

Project Overview and Objectives

The primary goal of this project was to develop a Convolutional Neural Network (CNN) model capable of classifying whether a subject has a brain tumor based on MRI scans. To accomplish this, the VGG-16 model architecture and pre-trained weights were employed to train the model for this binary classification task. Accuracy was used as the primary metric to assess the model's performance.

In machine learning, the training set is essential for model training, comprising input examples paired with their corresponding target outputs. This data enables the model to identify patterns and relationships, facilitating the generalization of the model's capabilities to make predictions on new, unseen data.

For the purposes of this project, the data was divided into the following sets:

Training Set: This set was used to train the model and consisted of a collection of labeled MRI scans.

Validation Set: The validation set was utilized during the training process to fine-tune hyperparameters and assess model performance.

Test Set: The test set was kept separate throughout the entire training process and served as the final evaluation dataset for model performance.

Data Set Description

The image data used for this project is sourced from "Brain MRI Images for Brain Tumor Detection." This dataset consists of MRI scans, which were categorized into two classes:

NO: Denoting the absence of a tumor, encoded as 0.

YES: Indicating the presence of a tumor, encoded as 1.

Conclusions

This project effectively addressed both a CNN model classification problem, aiming to predict the presence of brain tumors, and a Computer Vision problem, involving the automated extraction of brain images from MRI scans. The model achieved a final accuracy significantly higher than the 50% baseline. However, further improvements could be realized through an increase in the number of training images or by fine-tuning model hyperparameters.
