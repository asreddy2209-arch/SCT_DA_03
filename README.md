# Interactive HR Employee Attrition Dashboard

## 📌 Project Overview

The **Interactive HR Employee Attrition Dashboard** is a data analysis and visualization project designed to analyze employee attrition patterns using the IBM HR Employee Attrition dataset.

The project processes employee data, performs basic data cleaning and analysis, and generates an interactive HTML dashboard with filters, KPI cards, charts, and insights.

## 🎯 Objectives

* Analyze employee attrition patterns.
* Calculate total employees, employees who left, employees who stayed, and attrition rate.
* Analyze attrition based on department, age group, job role, and overtime.
* Provide interactive filters for exploring the dataset.
* Generate an interactive HTML dashboard for easy visualization.

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data processing and analysis
* **NumPy** – Numerical operations
* **Plotly.js** – Interactive charts
* **HTML & CSS** – Dashboard interface
* **Google Colab** – Running the Python notebook
* **Jupyter Notebook (.ipynb)**

## 📦 Requirements

Install the required Python libraries using:

```bash
pip install -r requirements.txt
```

### requirements.txt

```txt
pandas
numpy
```

## 📊 Dashboard Features

### KPI Cards

The dashboard displays:

* Total Employees
* Employees Left
* Employees Stayed
* Attrition Rate

### Interactive Filters

Users can filter the dashboard based on:

* Department
* Age Group
* Job Role
* Overtime

### Visualizations

The dashboard contains charts for:

1. Attrition by Department
2. Attrition by Age Group
3. Attrition by Job Role
4. Attrition by Overtime

### Automated Insight

The dashboard also provides a simple insight related to overtime and employee attrition based on the selected filters.

## 📁 Project Structure

```text
HR-Employee-Attrition-Dashboard/
│
├── Task3.ipynb
├── requirements.txt
├── README.md
└── HR_Employee_Attrition_Dashboard.html
```

## ▶️ How to Run

### Option 1: Google Colab

1. Open `Task3.ipynb` in Google Colab.
2. Run the notebook cells.
3. Upload the IBM HR Attrition dataset in CSV or ZIP format when prompted.
4. The notebook processes the dataset.
5. An HTML dashboard named:

```text
HR_Employee_Attrition_Dashboard.html
```

will be generated.

6. Open the HTML file in Chrome or Microsoft Edge.

### Option 2: Local Python Environment

1. Clone the repository.

```bash
git clone <your-github-repository-url>
```

2. Install the requirements.

```bash
pip install -r requirements.txt
```

3. Run the notebook using Jupyter Notebook or JupyterLab.

```bash
jupyter notebook
```

4. Upload the IBM HR Attrition CSV/ZIP dataset when prompted.

## 📈 Dataset

The project is designed to work with the **IBM HR Employee Attrition dataset**.

The dataset should contain fields such as:

* Age
* Attrition
* Department
* JobRole
* OverTime
* MonthlyIncome
* YearsAtCompany
* JobSatisfaction
* EnvironmentSatisfaction
* WorkLifeBalance
* DistanceFromHome

## 🔍 Data Processing

The project performs the following processing steps:

1. Uploads the dataset.
2. Extracts the CSV file if a ZIP file is uploaded.
3. Loads the dataset using Pandas.
4. Removes duplicate records.
5. Converts selected columns to numeric values.
6. Creates an `Age Group` column.
7. Calculates employee attrition statistics.
8. Generates the interactive dashboard.

## 💡 Key Output

The final output is an interactive HTML dashboard that allows users to explore employee attrition according to different employee characteristics.

## 👨‍💻 Author

**Saaketh Reddy Annreddy**

B.Tech – Artificial Intelligence and Machine Learning

## 📄 License

This project is created for educational and learning purposes.

Connect With Me
GitHub
https://github.com/asreddy2209-arch

LinkedIn
https://www.linkedin.com/in/saaketh-reddy-annreddy-22434937b/

Replace the placeholder with your actual LinkedIn profile.

⭐ Support
If you find this project useful:

⭐ Give the repository a star 🍴 Fork the repository 📢 Share the project 💬 Provide feedback
