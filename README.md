# Project: CandyHierarchy2017 - Data Analysis

## Overview

This project involves an in-depth analysis of the **CandyHierarchy2017** dataset. The dataset provides survey responses on Halloween candy preferences, demographics, and related questions. The analysis will cover data cleaning, handling missing and inconsistent data, and visualizing key insights to understand candy preferences based on different attributes.

## Dataset Description

The **CandyHierarchy2017** dataset contains responses from participants to various survey questions. Here’s a breakdown of the fields:

- **Internal_ID**: A unique identifier for each entry in the dataset.
- **Q1 - Going Out?**: A binary field indicating if the participant is going trick-or-treating themselves. Options: **Yes**, **No**.
- **Q2 - Gender**: The gender of the participant. Options: **Female**, **Male**, **Other**, **I'd rather not say**.
- **Q3 - Age**: The age of the participant (numeric field).
- **Q4 - Country**: The country the participant is from, though some names may be written differently due to user input.
- **Q5 - State/Province**: The state or province the participant is from, with similar variability in name format.
- **Q6 - Joy Or Despair**: Participant's preference for different types of chocolate bars with three options: **Joy**, **Meh**, **Despair**.
- **Q7 - Joy Other**: A text field where participants can list other items that give them joy, not mentioned in the previous questions.
- **Q8 - Despair Other**: A text field where participants can list other items that give them despair.
- **Q9 - Other Comments**: A text field for any additional comments participants wish to provide.
- **Q10 - Dress**: A binary field indicating if the participant is dressing up for Halloween. Options: **Yes**, **No**.
- **Q11 - Day**: A binary field indicating if the participant has plans on the day of Halloween. Options: **Yes**, **No**.

## Data Preparation

In this project, we will go through various stages of data preparation, including:

### 1. Handling Missing Data
   - Identifying and handling missing values in the dataset.
   - Deciding whether to fill, drop, or leave missing values based on the context of each field.

### 2. Handling Inconsistent Data
   - Resolving inconsistencies in textual fields (e.g., **Country** and **State/Province** fields).
   - Standardizing values where participants may have written their responses in various formats or languages.

### 3. Data Visualization
   - Visualizing key trends and insights in the dataset, such as:
     - The relationship between **Age** and **Candy Preferences**.
     - Gender-based candy preferences.
     - Regional (Country/State) candy trends.
   - Using libraries like **Matplotlib**, **Seaborn**, and **Plotly** for effective visual representation.

## Tools and Libraries Used

- **Python**: The primary programming language for data analysis and visualization.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib** & **Seaborn**: For data visualization.
- **NumPy**: For numerical operations.
- **Jupyter Notebooks**: For code execution and documentation.

## How to Run the Project

1. **Download the Dataset**:  
   You can download the dataset from Google Drive here:  
   [CandyHierarchy2017 Dataset](https://drive.google.com/drive/u/0/folders/1THFVmmCrMP87eutjbIrSXJCTJLsR9-DS).

2. **Install Dependencies**:  
   Make sure to install the required libraries. You can install them using `pip`:

   ```bash
   pip install pandas matplotlib seaborn numpy jupyter
