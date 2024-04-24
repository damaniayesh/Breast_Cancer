# Breast_Cancer
The project provides information about breast cancer to help doctors predict if a person has it.

<img width="212" alt="B_C" src="https://github.com/damaniayesh/Breast_Cancer/assets/136892684/ee2733d5-4541-4bf7-a3bb-3ef900db827b">

# Introduction
- Breast cancer is a disease in which abnormal breast cells grow out of control and form tumours. If left unchecked, the tumours can spread throughout the body and become fatal.
- Breast cancer cells begin inside the milk ducts and/or the milk-producing lobules of the breast. The earliest form (in situ) is not life-threatening. Cancer cells can spread into nearby breast tissue (invasion). This creates tumours that cause lumps or thickening.
- Invasive cancers can spread to nearby lymph nodes or other organs (metastasize). Metastasis can be fatal.
- Treatment is based on the person, the type of cancer and its spread. Treatment combines surgery, radiation therapy and medications.

# Consider the data present in the Breast Cancer Dataset file
Following the attribute related information.
This data set includes 201 instances of one class and 85 instances of another class. The instances are described by 9 attributes, some of which are linear and some are nominal.

1. Age
2. Menopause
3. inv-nodes
4. node-caps
5. deg-malig
6. breast
7. breast-quad
8. irradiat
9. Outcome (no-recurrence-events, recurrence-events)

# Problem Statement
To diagnostically predict whether or not a patient has Breast Cancer, based on certain diagnostic measurements included in the dataset.

# Steps Followed for the Project
1. Importing Necessary Libraries
2. Performing Exploratory Data Analysis
3. Data Preprocessing
4. Converting Categorical data to numerical. (Label Encoder)
5. Creating X and Y
6. Split the data into test and train
7. Performed various model such as Logistic Regression, Decision Tree, Random Forest, Extra_Tree_Classifier, SVC, KNeighbors.
8. Tuned the above model
9. Smote Implementation and again running all above models for better accuracy and low recall value

# Conclusion
Performed multiple models such as Logistic Regression, Decision Tree, Random Forest, Extra_Tree_Classifier, SVC, KNeighbors amongst them the tuned logistic regression model exhibits promising performance with an accuracy of 75.86%, indicating robust overall prediction. The low Type II error rate of 8 underscores its effectiveness in minimizing instances of false negatives, making it a strong choice for applications where identifying positive cases is crucial.
