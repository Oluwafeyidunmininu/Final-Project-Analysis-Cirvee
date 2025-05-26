# 📊 Data Analysis on the Sustainable Jobs and Skills Against Inflation in Nigeria (2024)

![main sustainable job](https://github.com/user-attachments/assets/6980c91c-0f7b-4da7-bd36-28d35ed3878a)

## 🔍 Introduction

Nigeria's inflation rate rose to **29.90% in January 2024**, up from **28.92% in December 2023**, raising significant economic concerns. In light of this, identifying **resilient jobs and skills** that can withstand economic shocks has become crucial.

This analysis aims to spotlight **inflation-resistant**, **high-growth**, and **well-paying jobs** in Nigeria, offering insights into career paths that can support a sustainable and secure standard of living.

---

## 🎯 Aim

To analyze and report on sustainable jobs and skillsets that resist inflation and offer economic resilience in Nigeria.

---

## 🛠 Tools Used

- **Excel** – Data Cleaning  
- **SQL** – Data Transformation & Joins  
- **Power BI** – Data Visualization  

---

## 📥 Data Collection

Uncleaned data was collected from reputable online sources and compiled into an Excel workbook with three sheets:

| Sheet | Name                          | Description |
|-------|-------------------------------|-------------|
| 1     | Nigeria Sustainable Jobs      | Job titles with salary, growth rate, inflation resistance, and skill requirements |
| 2     | Job and Skills Requirement    | Mapping of jobs to skills with importance ratings |
| 3     | Inflation Resistance Data     | Job titles and their resistance levels |

### 📚 Data Sources:

1. National Bureau of Statistics (NBS)
2. Nigerian Labour Market Report 2022
3. Jobberman Nigeria Salary Report 2022
4. PwC Nigeria Economic Outlook 2024
5. World Bank Nigeria Economic Update 2024

📂 **Dataset on Kaggle**:  
https://www.kaggle.com/datasets/dunmininuolugbade/sustainable-jobs-and-skills-resistant-to-inflation

---

## 🧹 Data Cleaning (Excel)

Key cleaning steps:

- Removed duplicates and handled missing values.
- Standardized column data types.
- Dropped unnecessary columns (e.g., "S/N").
- Renamed "Importance (1-5)" to "Ratings".
- Separated combined fields into distinct columns.

### ✅ Cleaned Tables:

#### Table 1 – Sustainable Jobs  
![Table 1](https://github.com/user-attachments/assets/35e79713-5a69-467a-bfcf-7e8324dbf7c4)

#### Table 2 – Job-Skill Mapping  
![Table 2](https://github.com/user-attachments/assets/6cec08cc-00b3-4a19-aaa3-dae8f530fafc)

#### Table 3 – Inflation Resistance  
![Table 3](https://github.com/user-attachments/assets/e9df04ad-1c82-45e0-9efa-e5f8e40c3c75)

---

## 🔗 Data Transformation (SQL)

SQL was used to merge the cleaned tables into a unified dataset for visualization.

📄 **SQL Query File**:  
[Joining Tables for Sustainable Jobs](https://github.com/Oluwafeyidunmininu/-DATA-ANALYSIS--ON-THE-SUSTAINABLE-JOBS-AND-SKILLS-AGAINST-INFLATION-IN-NIGERIA-2024-/blob/main/SQL%20Joining%20%20tables%20of%20the%20Sustainable%20Nigeria%20Jobs%20over%20inflation%20in%20%202024.sql)

![SQL Join](https://github.com/user-attachments/assets/5f43b783-a884-44e4-a3b5-59da719ca17b)

---

## 📈 Data Visualization (Power BI)

Key transformations before visualization:

- Averaged skill ratings per job title.
- Dropped the “Skills” column after aggregation.
- Standardized column names and checked data types.

### 📊 Dashboard Preview  
![Dashboard](https://github.com/user-attachments/assets/d8645cee-a08c-49bb-9259-1025d5074b63)

---

## 📌 Key Findings

### 1. Inflation Resistance  
![Job by Inflation Resistance](https://github.com/user-attachments/assets/f01f976f-7e77-41de-bca1-507d969b671b)

- **Top Jobs**: Cybersecurity Specialist, Data Scientist, Medical Specialist, Software Developer

### 2. Job Growth Rate  
![Job by Growth Rate](https://github.com/user-attachments/assets/f7debe2e-8817-4206-92eb-cedae402b645)

- **Top Growth**: Renewable Energy Engineer (20%), Cybersecurity Specialist (18%), Data Scientist (18%)  
- Note: Renewable Energy Engineer has high growth but lower inflation resistance.

### 3. Average Salary  
![Job by Salary](https://github.com/user-attachments/assets/f4e7e5eb-e34a-47d6-a4d7-25e15c3b4354)

- **Highest Paid**: Software Developer, Medical Specialist, Data Scientist  
- All three also show strong inflation resistance.

### 4. Ratings  
![Job by Rating](https://github.com/user-attachments/assets/4a16e201-c2a6-4cf1-b85f-6adc77b1bdc5)

- **Top Rating**: Medical Specialist with a perfect score of 5/5

---

## 🧾 Conclusion

With Nigeria’s inflation on the rise, jobs that are resilient to economic volatility offer the best path to financial stability. This study reveals that focusing on **high-demand, inflation-resistant, and well-paid jobs**—especially those requiring specialized skills—can help individuals maintain a strong standard of living.

---

## ✅ Recommendations

1. Prioritize skill development for inflation-resistant careers.
2. Launch awareness campaigns to highlight in-demand, resilient jobs.
3. Implement government and private-sector training programs.
4. Integrate monetary policies that support skill acquisition.

---

## ⚠️ Limitations

- Limited data sources and scope due to availability constraints.

---

## 🔮 Future Research Directions

1. Analyze individual skills within each job sector for deeper insights.
2. Explore cost-benefit analysis of acquiring different high-resistance skills.

---

> 👨🏽‍💻 *Developed by Emmanuel Dunmininu Olugbade*  
> 📫 Connect: [LinkedIn](https://www.linkedin.com/in/emmanuel-olugbade/) | [Kaggle](https://www.kaggle.com/dunmininuolugbade)

