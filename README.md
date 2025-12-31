# Women in STEM Data Analysis

## Project Overview
This project analyzes women's representation in STEM fields across different countries from 2000 to 2023. 
We focus on **female enrollment**, **female graduation rates**, and the **gender gap index** in STEM disciplines such as Engineering, Computer Science, Mathematics, and Biology.

The goal is to visualize trends, compare countries, and identify areas where gender representation is improving or lagging.

---

## Dataset
The dataset includes the following columns:
- **Country**: Name of the country
- **Year**: Year of observation
- **STEM Fields**: STEM disciplines (Engineering, Computer Science, Biology, Mathematics, etc.)
- **Female Enrollment (%)**: Percentage of female students enrolled in each STEM field
- **Female Graduation Rate (%)**: Percentage of female graduates in each STEM field
- **Gender Gap Index**: A metric showing gender equality in STEM

**Source:** [Insert your dataset source or leave blank if it's self-created]

**Notes on the dataset:**
- Duplicates and inconsistent entries were cleaned.
- Data is sorted by year in descending order (latest years first).
- Countries are sorted alphabetically for clarity.
- Aggregated 5-year intervals are used for easier visualization.

---

## Data Cleaning and Preprocessing
- Remove duplicates and missing values.
- Sort data by **year descending** and **country alphabetically**.
- Aggregate enrollment and graduation percentages for 5-year intervals (2000-2004, 2005-2009, ..., 2020-2023).
- Assign consistent colors for countries across all charts.
- Prepare data for comparison charts between enrollment and graduation.

---

## Visualizations

### 1️⃣ Female Enrollment in STEM Fields
This chart shows female enrollment percentages in all STEM fields across all countries, aggregated in 5-year intervals.

![Female Enrollment] https://github.com/mozhdamohammadi58-lang/women_stem_data_analysis/blob/main/01_female_enrollment.png

---

### 2️⃣ Female Graduation Rate in STEM Fields
This chart shows female graduation percentages in all STEM fields across all countries, aggregated in 5-year intervals.

![Female Graduation]https://github.com/mozhdamohammadi58-lang/women_stem_data_analysis/blob/main/02_graduation_stem.png

---

### 3️⃣ Enrollment vs Graduation Comparison
This chart compares average female enrollment vs. graduation percentages for each country.

![Enrollment vs Graduation]![alt text](../plots/03_enrollment_vs_graduation.png)

---

### 4️⃣ Gender Gap Index by Country
This chart visualizes the gender gap index for each country, highlighting areas of inequality in STEM participation.

![Gender Gap Index]https://github.com/mozhdamohammadi58-lang/women_stem_data_analysis/blob/main/03_enrollment_vs_graduation.png

---

## How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/yourusername/women_data_analysis.git

Navigate to the project folder:
cd women_data_analysis
Install the required Python libraries:

bash
pip install -r requirements.txt
Open Jupyter Notebook:

bash
jupyter notebook
Run the notebook:

text

notebooks/analysis.ipynb
This will load the dataset, process the data, and generate all charts.

Libraries Used
Python 3.x

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Project Structure
graphql

women_data_analysis/
│
├── data/
│   └── women_stem.csv         # Dataset
│
├── notebooks/
│   └── analysis.ipynb         # Jupyter Notebook with all code
│
├── plots/
│   ├── 01_female_enrollment.png
│   ├── 02_female_graduation.png
│   ├── 03_enrollment_vs_graduation.png
│   └── 04_gender_gap_index.png
│
└── README.md
