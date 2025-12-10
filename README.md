# Heart Disease Data Analysis

This project analyzes a **heart disease dataset** (from Kaggle) to uncover insights into **key health indicators and risk factors**. We apply data cleaning and exploratory analysis techniques to the patient data, then build interactive dashboards for visualization. Our goal is to reveal patterns that can aid in understanding heart disease prevalence and risk. Cardiovascular disease remains the leading cause of death worldwide
, so these insights are critical for **informing healthcare decisions and prevention strategies**.We aims to deliver actionable insights that could support healthcare decision-making and early risk identification.

### Key Objectives

- Identify Patterns: Uncover which patient features (e.g. **age, cholesterol, blood pressure**) are most associated with heart disease.

- Data Quality: Perform thorough data cleaning to **handle missing values, inconsistencies, and outliers.**

- Interactive Dashboards: Build dashboards in Power BI and Charts with Tableau to **present findings in a user-friendly way.**

- Insight Generation: Derive actionable insights to help **healthcare professionals and researchers.**

### Tools & Technologies

- **Python**– Used for data cleaning and Exploratory Data Analysis (EDA). We leverage libraries like pandas for data manipulation and analysis.
- 
- **Power Query** – Utilized for data transformation and shaping within Power BI.
. This enables efficient ETL operations on the dataset.
  
- **Power BI** – Employed for creating interactive dashboards and visualizations. Power BI helps “turn your data into visuals with advanced data-analysis tools, AI capabilities, and a user-friendly report-creation tool”.
  
- **Tableau** – Used to develop additional interactive visualizations. Tableau makes it easy to “organize and present information intuitively” through drag-and-drop charts.

### Workflow

1. **Data Cleaning & Preparation**: Load the raw Kaggle heart disease data into Python and clean it using pandas (handling missing values, correcting data types, encoding categorical fields, etc).
   
3. **Exploratory Data Analysis (EDA)**: Analyze distributions and correlations (using plots, summary statistics, and correlation matrices) to understand the data. Identify trends such as which age groups or symptoms correlate with heart disease incidence.

4. **Data Transformation (Power Query)**: Import the cleaned data into Power Query to perform any further ETL transformations. This includes merging tables if needed, filtering records, and creating calculated columns  risk scores.
  
6. **Visualization & Dashboard Building**: Develop interactive dashboards in Power BI and Tableau. Using Power BI’s advanced visuals and Tableau’s intuitive interface, we create charts and filters that allow users to explore the data. These tools turn the processed data into clear visual insights.

### Key Insights

- Elevated cholesterol and glucose levels show a **strong relationship with heart stroke cases.**

- **Age is a significant risk driver,** particularly above certain thresholds.

- Lifestyle indicators, including **smoking**, correlate with increased **cardiovascular risk.**

- Combined clinical features provide more reliable patterns than single metrics.

Here are the Limitations and Conclusion sections tailored to your specific analysis. You can add these to the bottom of your README.md file, just before the "Author" section.

### Limitations
-**Class Imbalance**: The target variable **(Heart_ stroke) is heavily imbalanced**, with significantly **more negative cases (3594) than positive cases (644)**. This may bias future machine learning models toward the majority class if not addressed ( SMOTE or undersampling).

-**Imputation Strategy**: Missing values for columns like **glucose and BMI** were filled using the **median**, and **education** using the **mode**. While effective for preserving distribution centers, this method does not account for correlations between features and may **slightly reduce data variance.**

-**Feature Generalization**: The engineered features **(BP_Cat, Glucose_Cat)** rely on general medical thresholds. Individual **patient history** or specific medical contexts were **not available for finer customization.**

### Conclusion
This project successfully transformed raw **heart disease data** into a clean, analytical dataset. By addressing **missing values, removing duplicates, and standardizing data types, the integrity of the dataset has been ensured**. Furthermore, the Feature Engineering phase added significant value by **translating raw clinical metrics (like blood pressure and BMI) into medically relevant categories.**
The findings reinforce widely recognized medical insights: **cardiovascular risk tends to increase with age, unhealthy lifestyle habits (such as smoking), and abnormal clinical indicators**. The dashboards offer a clear view of **patient distribution and risk characteristics,** enabling healthcare analysts and non-technical stakeholders to explore the data effectively.
