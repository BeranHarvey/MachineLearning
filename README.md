Coursework 3

Submission format

Solve all the question directly in this notebook. Some tasks require writing and running code. Other times you are asked to write answers to questions within the 'Markdown' cells and the answers are propmted by Your answer:.

Submit the solved Jupyter notebooks with the code and answers to KEATS. Make sure that all your code is running and the results are displayed. We will not be re-running your notebook when marking. You do not need to submit the data files with your notebooks. Your submission should consists of a single solved Python notebook file named CW3.ipynb.

Marks obtained in this coursework will be converted to 30% of your final grade.

System requirements

Q1-3 can be run on your local machines on CPU. Q4 needs to be run on Google Colab, because it requires GPU. If you prefer, you can solve all questions on Colab, intructions for uploading the datasets on Colab are given.

Questions

Queries about the coursework should be sent to rachel.sparks@kcl.ac.uk and maria.deprez@kcl.ac.uk. Please note that we are not able to answer any queries about how you should answer the questions. Your queries should only be related to clarity of the instructions or practical difficulties with the submission.

Guidance on use of generative AI

We emphasise that it is important that you submit your own work. Your marks will be based on your ability to demonstrate understanding of the techniques and methods discussed in class. We can recognise AI generated text and code. If you would like to use generative AI, limit it to searching for ideas, learning about machine learning techniques and correcting grammar (though grammar has no influence on your marks). Submitting AI generated content may result in a disciplinary hearing.

Guidance on written comments

Write your answers concisely and stay below the word limit. The word limit is generous, do not try to write more words than necessary. Do not copy text from the lectures and tutorials, you will not be given marks for that. We are interested in specific insights into your implemented solutions. Generic comments will not result in marks.

Breast Cancer Wisconsin Prognostic Dataset

In tutorials we have been looking at the Breast Cancer Wisconsin Diagnostic Dataset, where the task is to distinguish benign and cancerous cells in fine needle aspiration, on method breast biopsies are performed, based on 30 features.

The dataset for this coursework is a litte bit different, but related. In this dataset all patients have cancer. Some patients go on to have a cancer recurrence, cancer returning after treatment (label 1), and some remain cancer-free after the end of treatment (label 0). For this dataset 32 features are extracted. The two new features are the size of the original tumour lesion and the number of lymph nodes involved, these are number of lymph node biopsies that contain cancer cells a well known early indication of cancer spread.

Both Question 1 and 2 use this dataset.

Question 4 - CNN Classification

Detecting cancer from histopatological images

In this question we will implement a CNN to classify histopatological images for presence of cancer. More details about the PatchCamelyon dataset can be found here https://github.com/basveeling/pcam.
