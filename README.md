
# Cohort Characterisation and Clustering in Profound Hypotension

Authors: 

1. Abylaikhan Bexeit - 1445804
2. Ruotong Zhao - 1076714

This repository is for the MLH Final Project, which focuses on classifying and predicting medical information using various machine learning techniques. 
## Contents

 'MLH_Final_Project.ipynb': Jupyter notebook containing all code, outputs, and explanations.

 'requirements.txt': File with all dependencies and their versions. It is required to specify them to recreate the code environment.

## General Nature of the Solution

### **Data Retrieval**



### **Data Processing**

1. Finding Kidney-Related ICD-Codes：

   "Acute kidney failure": ["N179", "5849", "N170", "5845"],

   "Chronic kidney disease": ["5859", "N189", "N183", "5853", "N184"],

   "End stage renal disease": ["5856", "N186"]

2. Data Split: Training set - 80%, Test set - 20%

3. Apply SMOTE (Synthetic Minority Over-sampling Technique): Handling the Issue of Imbalanced Datasets

### **Model Used**

1. **Logistic Regression**（LR）

2. **Support Vector Classification**（SVC）

3. **Dense Neural Network**（DNN）

4. **Gradient Boosting Trees**（GBT）

5. **Stacking**

6. **Voting (Hard)** [LR, SVC, GBT]

7. **LSTM**（Long Short-Term Memory）

8. **RNN**（Recurrent Neural Network）

9. **Random Forest**（RF）

10. **Random Forest Improving Trials**（RF Improving Trials）

### **Tech Stack**

**Software:** Google Colab

**Type:** Jupyter Notebook

**Language:** Python

**Version:** Python 3.10.12

**Used libraries:** pandas, numpy, matplotlib, sklearn, seaborn, warnings

Python 3 server accelerator based on Google Compute Engine ().

## Environment Variables

To run this project, you will need to add the following environment variables using the provided **requirements.txt** file

Environment Setup:

Python:
```bash
pip install -r requirements.txt
```

## Execution

Jupyter notebook:

```bash
jupyter notebook
```

Steps for project execution:
- Start the Jupyter notebook
- Find the '**MLH_Final_Project.ipynb**' file and open it
- Execute the code cells to see all analyses and graphs

## Hardware requirements

Browser: Modern web browser like Safari, Google Chrome, etc. is desirable

RAM: 4 GB minimum (8 GB and higher is desirable)

GPU: Integrated intel GPU will be sufficient. Since the project does not heavily rely on GPU resources.  

Operating System: Any modern operating system such as Windows, MacOS, Linux, etc. 

CPU: Intel core i3 and higher is desirable but not mandatory

## Acknowledgements

## Support

For support, email 

1. abexeit@student.unimelb.edu.au
2. ruotzhao@student.unimelb.edu.au
