# INSAID2022-DL-CV-Skin-Cancer-Detection
INSAID 2022 Deep Learning CV Term Project
# Project Description
## Introduction
- Your client for this project is a Healthcare Company.
  - The incidence of both non-melanoma and melanoma skin cancers has been increasing over the past decades.
  - Currently, between 2 and 3 million non-melanoma skin cancers and 132,000 skin cancers occur globally each year.
  - One in every three cancers diagnosed is skin cancer and, according to Skin Cancer Foundation Statistics, one in every five Asians will develop skin cancer in their lifetime.
  - The researchers are building an app that can be used to identify what kind of skin cancer the person is diagnosed with.

## Current Scenario
- The detection of skin cancer in the early stage can be helpful to cure it.
- Analyzing the patient's current situation and identifying the type of skin cancer is not an easy task.
- Often, the human responsible for the task needs to take the opinion of the assigned doctor which is time-consuming.
- However, Designing a computer program to do this turns out to be a bit trickier.
- Currently, the organization is keeping track by manually identifying the status of skin cancer.

## Problem Statement
The current process suffers from the following problems:
- The treatment of patients is often delayed due to misdiagnosis of skin cancer type.
- It is tedious to hire an expert all the time if we want to inspect the patient’s condition.
- This process is slow and time-consuming.

## Project Task
* Project task is to automate the image analysis process.
* This model should return high accuracy.

## Project Deliverables
- Deliverable: **Type of Skin Cancer.**
- Machine Learning Task: **Image Classification**
- Target Variable: **Skin Cancer Type**
## Evaluation Metric
* The model evaluation will be based on the Accuracy score.
# Data Description
* The dataset contains images of all-important skin cancer diagnostic categories.
* There are 7 distinct type of skin cancer. This is the data that we have to predict for future images.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 3622 images and 7 label categories.

## Test Set:
* The test set contains 905 images.
* The test set doesn’t contain the label categories.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **AKIEC**   | Actinic keratoses and intraepithelial carcinoma / Bowen's disease (AKIEC)    |
|02| **BCC**   | Basal cell carcinoma (BCC)       |
|03| **BKL** | Benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratosis, BKL)   |
|04| **DF** | Dermatofibroma (DF)   |
|05| **MEL** | Melanoma (MEL)   |
|06| **NV** | Melanocytic nevi (NV)   |
|07| **VASC** | Vascular lesions (angiomas, angiokeratomas, pyogenic granulomas, and hemorrhage, VASC)   |
