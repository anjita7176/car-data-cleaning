 <div align="center">

# 🚗 Car Data Cleaning & Preprocessing

### Python | Pandas | NumPy | Data Preprocessing

*A data cleaning project focused on transforming a raw used-car dataset into a cleaner, structured, and analysis-ready dataset.*

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Project-Completed-success?style=flat-square)

</div>

---

## 🎯 Project Overview

Real-world datasets often contain missing values, duplicate records, inconsistent text, and incorrect data types. These issues can affect the quality and reliability of data analysis.

This project uses **Python and Pandas** to clean and preprocess a used-car dataset. It demonstrates practical data preparation techniques and exports the cleaned data into a CSV file for further analysis.

The project focuses on building a clear, beginner-friendly data cleaning workflow that can serve as the foundation for future Exploratory Data Analysis (EDA) and Machine Learning projects.

## 🎯 Project Objectives

- Understand the structure and quality of a raw dataset.
- Standardize column names and remove unnecessary whitespace.
- Identify and remove duplicate records.
- Clean inconsistent car names and text values.
- Convert relevant columns into appropriate numeric data types.
- Handle missing values using suitable strategies.
- Export the cleaned dataset for future use.
- Develop practical skills in data preprocessing with Pandas.

## 📁 Dataset Information

The project uses a used-car dataset containing information about cars listed for sale.

**Input dataset:** `quikr_car.csv`

The dataset includes information such as car names, year, selling price, kilometres driven, fuel type, and other vehicle-related attributes, depending on the source file.

### Data Preparation Summary

| Data Quality Issue | Cleaning Approach |
|---|---|
| Inconsistent column names | Converted column names to lowercase |
| Extra spaces in text | Removed unnecessary leading and trailing spaces |
| Duplicate records | Identified and removed duplicate rows |
| Inconsistent car names | Retained the first two words of car names |
| Price stored as text | Handled `Ask For Price`, removed commas, and converted values to numeric |
| Year and kilometres driven | Converted relevant values into numeric format |
| Missing numerical values | Filled missing values using the median |
| Missing categorical values | Replaced missing values with `Unknown` |

*Note: The exact results depend on the original dataset and the cleaning operations performed in the notebook.*

## 🧹 Data Cleaning Workflow

The notebook follows a step-by-step data preprocessing workflow.

1. **Import Libraries** — Load Pandas and other required Python libraries.
2. **Load Dataset** — Read the raw CSV file into a Pandas DataFrame.
3. **Inspect Data** — Examine rows, columns, data types, and missing values.
4. **Standardize Columns** — Convert column names to lowercase and clean whitespace.
5. **Remove Duplicates** — Eliminate duplicate records.
6. **Clean Text Data** — Standardize text fields and simplify car names.
7. **Convert Data Types** — Convert year, price, and kilometres driven into numeric formats.
8. **Handle Missing Values** — Apply median imputation to numeric columns and `Unknown` to categorical columns.
9. **Export Cleaned Data** — Save the processed dataset as a new CSV file.

## ⚙️ Key Data Cleaning Techniques

### 1. Text Cleaning

Unnecessary spaces are removed to make text values more consistent.

### 2. Duplicate Removal

Duplicate rows are removed to reduce repeated records in the dataset.

### 3. Data Type Conversion

Values stored as text are converted into appropriate numeric formats wherever applicable.

### 4. Missing Value Imputation

- **Numerical columns:** Missing values are filled using the median.
- **Categorical columns:** Missing values are filled with `Unknown`.

### 5. CSV Export

The cleaned DataFrame is exported without the Pandas index, making the output easier to reuse in other tools and projects.

## 📊 Project Files

| File | Description |
|---|---|
| `Data_Cleaning.ipynb` | Jupyter Notebook containing the data cleaning workflow |
| `quikr_car_cleaned.csv` | Exported cleaned dataset |
| `README.md` | Project documentation |

## 🛠️ Technologies Used

- **Python** — Core programming language.
- **Pandas** — Data manipulation, cleaning, and preprocessing.
- **NumPy** — Numerical computing support.
- **Google Colab** — Cloud-based notebook environment.
- **Jupyter Notebook** — Interactive Python development.

## 🚀 Getting Started

Follow these steps to run the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/anjita7176/car-data-cleaning.git
```

### 2. Open the Project Directory

```bash
cd car-data-cleaning
```

### 3. Install the Required Libraries

```bash
pip install pandas numpy jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Data_Cleaning.ipynb` and execute the cells in order.

**Important:** To reproduce the cleaning process, place the original `quikr_car.csv` file in the expected location and update the notebook's input path if required. The repository's cleaned CSV is already available as an output file.

## 🔮 Future Improvements

- Perform Exploratory Data Analysis (EDA).
- Visualize price distributions and other numerical features.
- Analyze the relationship between car age, kilometres driven, and price.
- Detect unusual values and potential outliers.
- Compare different missing-value handling techniques.
- Build a used-car price prediction model using Machine Learning.
- Create an interactive dashboard using Power BI.

## 👩‍💻 Author

**Anjita Kumari**

Aspiring Data Scientist | Python | Data Analysis | Machine Learning | Generative AI

- **GitHub:** [@anjita7176](https://github.com/anjita7176)
- **LinkedIn:** [Connect with me](https://www.linkedin.com/in/anjita-kumari-48975624b/)

---

<div align="center">

*Learning by building. Improving through data.*

⭐ If you find this project useful, consider giving the repository a star!

</div>
