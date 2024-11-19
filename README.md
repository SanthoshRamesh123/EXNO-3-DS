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
     ![Screenshot 2024-11-18 194403](https://github.com/user-attachments/assets/994126cc-8a3b-4b5e-9cbf-a432bd931f52)

![Screenshot 2024-11-18 194403](https://github.com/user-attachments/assets/37438f7c-e2d6-4799-ae70-86e10c487df6)
![Screenshot 2024-11-18 194416](https://github.com/user-attachments/assets/b969387e-15be-41d4-8254-52eac93410fe)
![Screenshot 2024-11-18 194427](https://github.com/user-attachments/assets/08f9acb0-44a0-4ea5-811b-36170b4e1eb0)
4-93df-e21d965f2cdf)
![Screenshot 2024-11-18 194438](https://github.com/user-attachments/assets/fbca75f1-2bb9-44c2-8c30-8c685f20143f)
![Screenshot 2024-11-18 194449](https://github.com/user-attachments/assets/31b1f2c4-82f5-4565-b8a5-591f4a40f3b0)
![Screenshot 2024-11-18 194458](https://github.com/user-attachments/assets/4154f93c-a68b-4763-8a1f-5888ff0807be)
![Screenshot 2024-11-18 194512](https://github.com/user-attachments/assets/293a9921-7792-4c6d-b824-7ac3b4e0afc6)
![Screenshot 2024-11-18 194518](https://github.com/user-attachments/assets/e742cfa6-6913-46a2-8383-5b4aaf29d567)
![Screenshot 2024-11-18 194529](https://github.com/user-attachments/assets/eaef4372-c8c1-4b29-b20a-12530fe44849)

# RESULT:
      Thus the given data, Feature, Encoding,Transforming process and save the data to a file was performed sucessfully

       
