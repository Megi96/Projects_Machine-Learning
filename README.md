# Penguins Dataset Analysis

## Overview
This project analyzes the **Palmer Penguins dataset** using **Pandas, Seaborn, and Matplotlib**. The goal is to explore, clean, transform, and visualize morphological measurements for three penguin species across different islands. The analysis highlights key patterns in **body size, bill shape, and flipper length** while demonstrating feature engineering and data visualization techniques.

---

## Dataset
The **Penguins dataset** is a well-known dataset for data exploration and machine learning exercises. It contains measurements of:

- `species`: Penguin species (Adelie, Chinstrap, Gentoo)  
- `island`: Island of study (Biscoe, Dream, Torgersen)  
- `bill_length_mm` & `bill_depth_mm`: Bill dimensions  
- `flipper_length_mm`: Flipper length  
- `body_mass_g`: Body mass  
- `sex`: Male/Female  

Source: Seaborn built-in dataset (`sns.load_dataset("penguins")`)

---

## Project Goals
1. **Exploratory Data Analysis (EDA):**  
   - Understand dataset structure, missing values, and distributions.  
   - Summarize species-specific measurements.

2. **Data Cleaning:**  
   - Handle missing values for numeric and categorical columns.  
   - Convert categorical variables to proper types.  

3. **Feature Engineering:**  
   - Create derived metrics like:
     - `bill_ratio = bill_length_mm / bill_depth_mm`
     - `flipper_mass_ratio = flipper_length_mm / body_mass_g`

4. **Data Visualization:**  
   - Explore distributions, comparisons, and relationships using:
     - Histograms
     - Boxplots
     - Violin plots
     - Scatter plots
     - Heatmaps

5. **Insights:**  
   - Gentoo penguins are the largest in body mass and flipper length.  
   - Bill ratios differ significantly across species, indicating distinct shapes.  
   - Island location affects flipper size, revealing ecological variation.  

---

## Usage
1. Clone the repository:
```bash
git clone https://github.com/Megi96/penguins-analysis.git
