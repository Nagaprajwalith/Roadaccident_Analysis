# 🚦 Road Traffic Accident Analysis (Mini Project)

This repository contains a data analysis mini project focused on understanding road traffic accident patterns by gender using Python, Pandas, and Plotly Express.

## 📁 Project Structure

- `aml_miniprj_cleaned.ipynb`: Cleaned Jupyter Notebook with the full analysis and interactive plots.
- `RTA Dataset.csv`: Dataset containing information about road traffic accident casualties.
- `README.md`: Project documentation and overview.

## 📊 Project Description

The aim of this project is to analyze road traffic accident (RTA) data, specifically looking at the number of casualties based on gender. Using data visualization techniques, we explore patterns and draw insights from the dataset.

### Key Objectives:
- Understand the gender distribution of casualties.
- Use interactive visualizations to highlight differences.
- Provide an easy-to-understand analysis using Python tools.
- 
## 🔧 Technologies Used

- Python 3.12
- Pandas (v2.x)
- Plotly (v5.x)
- Jupyter Notebook
 
## 📈 Visualization Example

A donut-style pie chart was created using Plotly to show the number of casualties by gender:

```python
fig = px.pie(
    filtered_data,
    names='Sex_of_casualty',
    values='Number_of_casualties',
    template='ggplot2',
    hole=0.5,
    title='Number of Casualties by Gender')
fig.show()
```
# Casualty Analysis

## Number of Casualties by Gender
![Casualties by Gender]("C:\Users\NAGA PRAJWALITH\Pictures\Screenshots\Screenshot 2025-04-19 160639.png")

## 🧠 Skills Demonstrated

- 📊 **Exploratory Data Analysis (EDA):** Identified patterns and trends in road traffic accident data.
- 🧹 **Data Cleaning & Preprocessing:** Filtered relevant data (e.g., by gender) using Pandas.
- 📈 **Data Visualization:** Created interactive charts (donut-style pie chart) using Plotly Express.
- 📂 **Working with CSV files:** Loaded and manipulated real-world datasets using `pandas.read_csv()`.
- 💡 **Insight Derivation:** Interpreted visual data to draw meaningful conclusions.
- 🐍 **Python Programming:** Used Python libraries efficiently in a notebook environment.




