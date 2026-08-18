# Zomato Data Analysis 🍽️
## 📚 References

- GeeksforGeeks – Zomato Data Analysis tutorial, used as a learning reference for the analysis workflow and concepts.

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Zomato restaurant dataset using Python.

The analysis focuses on understanding restaurant characteristics such as **restaurant type, ratings, customer votes, online ordering, table booking, and approximate cost for two people**.

The project uses data cleaning, statistical exploration, and visualization techniques to identify patterns and trends in the restaurant data.

## 🎯 Objectives

* Analyze different types of restaurants.
* Understand restaurant rating distributions.
* Study the relationship between ratings and customer votes.
* Analyze the availability of online ordering.
* Analyze table booking availability.
* Explore the approximate cost for two people.
* Identify patterns and trends in restaurant data using visualizations.

## 🗂️ Dataset

The dataset contains **148 restaurant records** and **7 columns**:

| Column                        | Description                          |
| ----------------------------- | ------------------------------------ |
| `name`                        | Name of the restaurant               |
| `online_order`                | Whether online ordering is available |
| `book_table`                  | Whether table booking is available   |
| `rate`                        | Restaurant rating                    |
| `votes`                       | Number of customer votes             |
| `approx_cost(for two people)` | Approximate cost for two people      |
| `listed_in(type)`             | Type/category of restaurant          |

The dataset was loaded using Pandas from `Zomato-data-.csv`.

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization

The notebook imports these libraries at the beginning of the analysis.

## 🔍 Data Cleaning

The original `rate` values were stored in the form `4.1/5`. The project converts these values into numerical ratings such as `4.1` for easier analysis.

The dataset was also checked for missing values, with no null values found across the analyzed columns.

## 📊 Exploratory Data Analysis

The project explores:

### Restaurant Types

The distribution of restaurants across different restaurant types is visualized using a Seaborn count plot.

### Restaurant Ratings

Restaurant ratings are analyzed to understand the overall rating patterns within the dataset.

### Customer Votes

The number of votes received by restaurants is examined to understand customer engagement.

### Online Ordering

The project analyzes whether restaurants provide online ordering facilities.

### Table Booking

The availability of table booking is explored across the restaurants.

### Approximate Cost

The approximate cost for two people is analyzed to understand pricing patterns among restaurants.

## 📈 Key Analysis Areas

The analysis investigates relationships between:

* Restaurant type and number of restaurants
* Restaurant ratings and customer votes
* Online ordering and restaurant characteristics
* Table booking and restaurant characteristics
* Restaurant type and approximate cost

## 📁 Project Structure

```text
Zomato-data-analysis/
│
├── Zomato-data-.csv
├── zomato_data_analysis.ipynb
└── README.md
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/Gayatri-tech24/Zomato-data-analysis.git
```

2. Open the project in **Jupyter Notebook** or **VS Code**.

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

4. Open:

```text
zomato_data_analysis.ipynb
```

5. Run the notebook cells to reproduce the analysis.

## 💡 Skills Demonstrated

* Data loading and inspection
* Data cleaning
* Handling and converting data types
* Exploratory Data Analysis
* Statistical analysis
* Data visualization
* Python programming
* Pandas and NumPy
* Matplotlib and Seaborn

## 👩‍💻 Author

**Gayatri Arvind Gundad**

Computer Science Engineering Student
Machine Learning & Data Analytics Enthusiast

GitHub: **Gayatri-tech24**

