💤 **Sleep Health and Lifestyle Analysis — Power BI Project**

📌 **Project Overview :**

This project explores the **Sleep Health and Lifestyle Dataset** from Kaggle using **Microsoft Power BI**. The dataset includes lifestyle and physiological factors such as sleep duration, sleep quality, stress level, physical activity, and more. The objective is to visualize patterns that might indicate potential causes of sleep disorders and explore relationships among variables like age, gender, heart rate, and stress levels.

---

**📁 Dataset Information**

- **Source**: [Kaggle - Sleep Health and Lifestyle Dataset](https://www.kaggle.com/datasets)
- **Format**: Excel (`.csv`)
- **Size**: 375 rows × 13 columns
- **Key Columns**:
  - `Gender`
  - `Age`
  - `Occupation`
  - `Sleep Duration`
  - `Sleep Quality`
  - `Physical Activity Level`
  - `Stress Level`
  - `BMI Category`
  - `Heart Rate`
  - `Sleep Disorder`


🧭 **Steps from Raw Data to Dashboard :**

1️⃣**Data Preparation (Excel)**
- Checked for:
  - Clear column headers
  - Consistent formatting
  - No merged or empty rows/columns
- Saved the dataset as `sleep_health_dataset.csv`.


2️⃣ **Load Data into Power BI**
- Selected and loaded the dataset from the Excel file
  

3️⃣ **Data Cleaning & Transformation (Power Query)**
- Renamed columns for readability
- Set correct data types:
  - Text: `Gender`, `Occupation`, `BMI Category`, `Sleep Disorder`
  - Numeric: `Age`, `Sleep Duration`, `Stress Level`, `Heart Rate`, `Daily Steps`
- Removed any empty or duplicate rows
- Added calculated columns

4️⃣ **Data Modeling**
- Dataset is single-table, so no relationships were needed

5️⃣ **Data Visualization in Power BI**
Created interactive visualizations to explore:
- **Sleep Duration by Age Group**
- **Sleep Quality by Occupation**
- **Stress vs Sleep Duration**
- **BMI Category Distribution**

🔍 Interactive Filters (Slicers)
- Gender
- Occupation
- Sleep Disorder
- BMI Category


📊 Dashboard Features
- Clean layout with responsive visuals
- Slicers for filtering
- KPI cards showing:
  - Average Sleep Duration
  - Average Stress Level
