## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Encoding for the feature in the data set.
STEP 4:Apply Feature Transformation for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:
![Screenshot 2024-11-18 194403](https://github.com/user-attachments/assets/a05567e1-fbf1-4d76-a61a-2659937f3fc2)
![Screenshot 2024-11-18 194416](https://github.com/user-attachments/assets/1fc814e4-8643-45d7-b763-56869d772085)
![Screenshot 2024-11-18 194427](https://github.com/user-attachments/assets/444c3d72-b88f-48e8-a9e8-dad711d59ceb)
![Screenshot 2024-11-18 194438](https://github.com/user-attachments/assets/7729c82c-643d-4e8c-9bb8-6f350c865c53)
![Screenshot 2024-11-18 194449](https://github.com/user-attachments/assets/37394223-b8d0-4fe8-bb57-8341dc1025e3)
![Screenshot 2024-11-18 194458](https://github.com/user-attachments/assets/00e078d7-4cfe-424c-9758-10f26e28de01)
![Screenshot 2024-11-18 194512](https://github.com/user-attachments/assets/09ad87fa-dcb8-40ca-8c9c-2293fbc57646)
![Screenshot 2024-11-18 194518](https://github.com/user-attachments/assets/6dfb5bd1-b17e-4368-88f0-4026730f33cc)
![Screenshot 2024-11-18 194529](https://github.com/user-attachments/assets/eb5b701a-b43a-4f7c-8913-ee885534cafa)

# RESULT:
Thus the given data, Feature Encoding, Transforming process and save the data to a file was performed sucessfully.
