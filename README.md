# nhanes_inferential_2023

## Objective

In this assignment, you will use NHANES data to perform basic inferential statistics using Python in Google Colab. You will explore relationships and differences in health metrics and demographic variables, utilizing the skills learned in class to answer key questions about the dataset. Your final analysis should be saved as a Google Colab notebook and uploaded to a GitHub repository.

## Data Preparation
To start, you’ll use the following NHANES variables for analysis:

Marital Status (DMDMARTZ) - categorical, needs recoding (married or not married).
Education Level (DMDEDUC2) - categorical, needs recoding (bachelor’s or higher vs. less than bachelor’s).
Age in Years (RIDAGEYR) - continuous.
Systolic Blood Pressure (BPXOSY3) - continuous.
Diastolic Blood Pressure (BPXODI3) - continuous.
Vitamin D Lab Interpretation (LBDVD2LC) - categorical, two levels.
Hepatitis B Lab Antibodies (LBXHBS) - categorical, needs recoding to two levels.
Weak/Failing Kidneys (KIQ022) - categorical, can be treated as two levels.
Minutes of Sedentary Behavior (PAD680) - continuous, needs cleaning (remove values 7777, 9999, and null).
Current Self-Reported Weight (WHD020) - continuous, needs cleaning (remove values 7777, 9999, and null).
Note: Ensure you clean the data before performing analyses. For categorical variables, check and document frequency counts to confirm data consistency. For continuous variables, be mindful of placeholder values (7777, 9999) and handle these as appropriate (e.g., by removing or imputing).

