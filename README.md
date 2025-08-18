### Zomato Exploratory Data Analysis (EDA)

#### Project Overview
This project is an in-depth Exploratory Data Analysis (EDA) of a comprehensive Zomato restaurant dataset. The primary objective is to clean and prepare the raw data, uncover key insights, and visualize restaurant trends.

#### Core Functionality
* **Data Loading & Initial Inspection**: The notebook begins by loading the Zomato dataset using `pandas` and performing an initial check of its structure, columns, and data types.
* **Data Cleaning**: It addresses data quality issues by handling missing values and removing irrelevant columns such as `url`, `address`, `phone`, and `dish_liked` to streamline the dataset.
* **Column Renaming**: The columns are renamed for clarity and ease of use (e.g., `'rate'` to `'rating'`, `'approx_cost(for two people)'` to `'cost'`).
* **Data Visualization & Insights**: The project includes a dedicated analysis of restaurant types. It uses various plots to visualize the distribution of restaurants across different categories, and a thorough analysis of cuisine types and the relationship between rating and cost.

#### Technologies Used
* **Python**: The core programming language used for the analysis.
* **Pandas**: A powerful data manipulation and analysis library.
* **NumPy**: A fundamental package for scientific computing in Python.
* **Matplotlib**: A plotting library used for creating static, animated, and interactive visualizations.
* **Seaborn**: A statistical data visualization library based on Matplotlib, used to create informative and attractive statistical graphics.
