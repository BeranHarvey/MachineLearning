# Coursework 3.

## System requirements

Q1-3 can be run on your local machines on CPU. Q4 needs to be run on Google Colab, because it requires GPU. If you prefer, you can solve all questions on Colab, intructions for uploading the datasets on Colab are given.

## Breast Cancer Wisconsin Prognostic Dataset

In tutorials we have been looking at the Breast Cancer Wisconsin Diagnostic Dataset, where the task is to distinguish benign and cancerous cells in fine needle aspiration, on method breast biopsies are performed, based on 30 features.

The dataset for this coursework is a litte bit different, but related. In this dataset all patients have cancer. Some patients go on to have a cancer recurrence, cancer returning after treatment (label 1), and some remain cancer-free after the end of treatment (label 0). For this dataset 32 features are extracted. The two new features are the size of the original tumour lesion and the number of lymph nodes involved, these are number of lymph node biopsies that contain cancer cells a well known early indication of cancer spread.

Both Question 1 and 2 use this dataset.

## Question 3 - GMM segmentation

### SWI for visualisation of brain vessels

Susceptibility weighted imaging (SWI) is a MRI modality that gives good contrast for visualisation of blood vessels in the brain. You are given one slice of SWI image of a newborn baby acquired at 7T scanner at St Thomas Hospital. The file is named 'brainSWI.npy'. Your task is to segmenent the vessels in this image using Gaussian Mixture Model. Note that the vessels apprear dark on SWI, and the brain has been masked and padded by zeros.

## Question 4 - CNN Classification

### Detecting cancer from histopatological images

In this question we will implement a CNN to classify histopatological images for presence of cancer. More details about the PatchCamelyon dataset can be found here https://github.com/basveeling/pcam.
