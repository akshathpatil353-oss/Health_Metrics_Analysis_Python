📊 ANALYSIS OF BODY MEASUREMENTS USING NUMPY AND DATA VISUALIZATION
(NHANES DATASET)

🎓 Capstone Project – Data Science and Machine Learning


📌 PROJECT DESCRIPTION
This project performs exploratory data analysis on human body measurement
data from the NHANES dataset using Python. The goal is to understand body
composition, health indicators, and relationships between variables such as
weight, height, waist, hip, and BMI.


🎯 PROJECT OBJECTIVES
✔ Analyse male and female body measurements
✔ Visualise weight distributions using histograms and boxplots
✔ Compute statistical measures (mean, median, standard deviation, skewness)
✔ Calculate Body Mass Index (BMI)
✔ Standardise the dataset using z-scores
✔ Analyse relationships using pairplots and correlation matrices
✔ Compute waist-to-height and waist-to-hip ratios
✔ Compare body fat distribution between genders
✔ Interpret health indicators based on data


📁 DATASET INFORMATION
Dataset: NHANES (National Health and Nutrition Examination Survey)

Files used:
- nhanes_adult_male_bmx_2020.csv
- nhanes_adult_female_bmx_2020.csv

Each dataset contains the following attributes:
1. Weight (kg)
2. Height (cm)
3. Upper arm length (cm)
4. Upper leg length (cm)
5. Arm circumference (cm)
6. Hip circumference (cm)
7. Waist circumference (cm)


🛠️ TECHNOLOGIES USED
💻 Python  
📊 NumPy  
📈 Pandas  
📉 Matplotlib  
🎨 Seaborn  
📓 Jupyter Notebook  


📊 KEY ANALYSIS PERFORMED

🔹 DATA VISUALISATION
- Histograms for male and female weight distributions
- Boxplots for comparing weight variation
- Boxplots for waist-to-height and waist-to-hip ratios

🔹 STATISTICAL ANALYSIS
- Mean, Median, Standard Deviation
- Minimum and Maximum values
- Skewness of distributions

🔹 FEATURE ENGINEERING
- BMI calculation
- Waist-to-Height Ratio (WHtR)
- Waist-to-Hip Ratio (WHR)

🔹 STANDARDISATION
- Converted all variables into z-scores for fair comparison

🔹 CORRELATION ANALYSIS
- Pearson correlation
- Spearman rank correlation
- Pairplot visualisation


📈 KEY INSIGHTS

✔ Male participants generally have higher average weight and more variation than females  
✔ BMI is strongly related to body weight and waist circumference  
✔ Waist-to-height ratio is a strong indicator of central obesity  
✔ Waist-to-hip ratio shows body fat distribution patterns  
✔ Individuals with higher BMI have larger waist and hip measurements  


⚖️ COMPARISON OF HEALTH INDICATORS

📌 BMI
Advantages:
✔ Easy to calculate  
✔ Widely used for classification  

Disadvantages:
✖ Does not show fat distribution  
✖ Cannot distinguish muscle from fat  

📌 Waist-to-Height Ratio (WHtR)
Advantages:
✔ Better predictor of health risk  
✔ Indicates central obesity  

Disadvantages:
✖ Depends on accurate waist measurement  

📌 Waist-to-Hip Ratio (WHR)
Advantages:
✔ Shows body fat distribution pattern  
✔ Useful in health risk analysis  

Disadvantages:
✖ Requires two measurements  
✖ Can hide fat gain if both values increase  


📌 CONCLUSION

This project demonstrates how data analysis and visualisation can be used
to understand human body composition and health indicators. Waist-based
ratios provide better insight into fat distribution and health risk than BMI
alone. Statistical and visual methods together help in better interpretation
of body measurement data.


👨‍💻 AUTHOR

Akshath Patil  
📊 Data Science and Machine Learning Enthusiast  
💡 Skills: Python, NumPy, Pandas, Data Visualization  
