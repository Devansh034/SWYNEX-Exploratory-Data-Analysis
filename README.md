# SWYNEX — Exploratory Data Analysis

## Data Analytics Internship — Task 2

This project performs Exploratory Data Analysis (EDA) on the cleaned Titanic dataset from Task 1.

### Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn

### Analysis Performed

- Dataset overview and summary statistics
- Survival analysis by gender
- Survival analysis by passenger class
- Age distribution analysis
- Fare distribution by passenger class
- Family-size survival analysis
- Title-based survival analysis
- Correlation analysis
- Outlier and anomaly identification

### Key Insights

1. Female passengers had a substantially higher survival rate than male passengers.
2. Survival rate decreased across passenger classes from 1st to 3rd class.
3. First-class passengers generally paid higher and more variable fares.
4. Small and medium family groups showed different survival patterns compared with solo passengers and very large groups.
5. Passenger titles showed noticeable differences in survival rates, although some title categories had small sample sizes.

### Visualizations

The project includes six visualizations:

1. Survival by Class and Sex
2. Age Distribution
3. Fare Distribution by Class
4. Survival by Family Size
5. Correlation Heatmap
6. Survival by Title

### Project Structure

```text
SWYNEX-Exploratory-Data-Analysis/
│
├── eda_analysis.py
├── EDA_REPORT.md
├── titanic_cleaned.csv
├── README.md
│
└── charts/
    ├── 01_survival_by_class_sex.png
    ├── 02_age_distribution.png
    ├── 03_fare_by_class.png
    ├── 04_survival_by_family_size.png
    ├── 05_correlation_heatmap.png
    └── 06_survival_by_title.png
