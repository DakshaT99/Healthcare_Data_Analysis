# Healthcare_Data_Analysis

This project focuses on analyzing healthcare data, such as patient health profiles, medical histories, and healthcare costs.

# Objective

The aim of this project is to analyze healthcare data to extract actionable insights that could help improve patient care and healthcare resource management. By working with multiple datasets, I utilized various Excel techniques to clean, transform, and analyze the data to uncover meaningful patterns.

# Dashboard

<img width="875" height="652" alt="healthcare analysis dashboard" src="https://github.com/user-attachments/assets/092aa982-85dd-4834-afa7-d542bb1b3902" />


This healthcare data dashboard provides a multi-dimensional look at patient demographics, medical history, and hospital billing trends.

# Data Exploration

1. Hospital Charges (Financial Statistics)
   
This section summarizes the cost distribution for all 2,335 customers:

- Mean (Average): $13,559.07 This is the "typical" charge per patient. Since the mean is significantly higher than the median, it suggests that a few very expensive cases (outliers) are pulling the average up.

* Median: $9,634.54 The middle value of the dataset. This indicates that 50% of your patients were charged less than roughly $9,635, which is a more realistic representation of a standard visit than the mean.

+ Mode: $38,711.00 The most frequently occurring charge value. In healthcare data, a high mode like this often points toward a standardized cost for a specific, common procedure or surgery.

- Range (Min/Max): Charges vary wildly, from a minimum of $563.84 to a maximum of $63,770.43.

* Standard Deviation: $11,920.11 This high value shows a large "spread" in the data, meaning hospital charges are not uniform and depend heavily on the patient's specific condition.

2. Patient Demographics (Age)

- Median Age: 39 Half of the patients in this dataset are 39 years old or younger.

* Mode Age: 18 The most common age group represented in this data is 18-year-olds. This explains why the "Age v/s Hospital Expenditures" chart in your dashboard starts right at the 18-year mark.

# Data Cleaning and Transformation

- Basic Data Cleaning: Learned and applied techniques such as using mean, median, and mode to clean the data.
Patient Segmentation:

* BMI (Body Mass Index): Segregated patients as Underweight, Healthy, Overweight, and Obese.

+ Blood Sugar Levels: Classified patients as Normal, Pre-Diabetic, and Diabetic.

# Data Analysis

1) Smoking and Cancer Risk:

Insight: Using a Donut Chart, I found that non-smokers have a higher cancer history compared to smokers, indicating that smoking might not be the only factor contributing to cancer risk.

* Obesity & Cancer Correlation: Through further analysis, I observed that obese and overweight patients were more prone to cancer than those with a normal weight.

+ Research Findings: Web research showed that being overweight can lead to insulin resistance, increasing the risk of colon cancer.

2) Blood Sugar and Surgeries:

- Diabetes Analysis: Investigated the blood sugar levels of obese and overweight patients and found that most were either diabetic or pre-diabetic.

* Surgeries & Blood Sugar: Using another Donut Chart, I found that patients with uncontrolled blood sugar levels underwent more than two surgeries.

3) Hospital Charges:

- Obesity & Costs: Obese patients were found to incur higher hospital charges compared to others, even if their blood sugar levels were normal.

* Valuable Insight: Maintaining a healthy weight through exercise and diet is critical to preventing diseases such as cancer and reducing healthcare costs.

4) Hospital Charge Trends:

- Tier 2 Hospitals: A Column Chart revealed that Tier 2 hospitals had the highest hospital charges. This may be due to the developing nature of these cities, which may lack proper sanitation and awareness about physical health.

* Charges by Age: With the help of a Line Chart, I observed that hospital charges increase with age, but after 60, these charges rise dramatically due to age-related factors.

5) Age, BMI, and Blood Sugar Trends:

- As age increases, both blood sugar and BMI levels rise.

* Beyond 60 years old, blood sugar levels increase sharply, while BMI levels decrease.

+ Young Patients (25-35): A surprising observation was the presence of obesity among younger patients, as indicated by peaks in the BMI trend.

# Key Excel Functions & Techniques Used:

- Data Cleaning: Mean, Median, Mode functions.

* Data Segmentation: Conditional formatting and formulas to categorize BMI and blood sugar levels.

# Charts:

- Donut Chart: Used to compare smokers vs. non-smokers and their health histories.

* Column Chart: Displayed hospital charges in different regions.

+ Line Chart: Showed trends in hospital charges by age.ly in region R1011, which is a significant cost outlier.

- Health Status & Hospital Charges: A grouped bar chart showing that Obesity is the primary driver of hospital costs, significantly higher than "Healthy Weight," "Overweight," or "Underweight" categories. Within these groups, "Normal" and "Diabetes" patients incur similar high costs.

* Age v/s Hospital Expenditures: A trend line showing a clear positive correlation between age and medical spending. Costs start near $6,000 at age 18 and climb to nearly $30,000 by age 64.

