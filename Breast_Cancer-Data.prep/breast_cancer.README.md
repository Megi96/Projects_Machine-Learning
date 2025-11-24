🔬 Breast Cancer Data Analysis Project
🎯 Project Goal

Analyze tumor features to identify factors predicting malignancy using visualizations and statistics.

📊 Dataset Overview

Samples: 569 tumors

Malignant: 212 🔴

Benign: 357 🟦

Features:

Size: radius, perimeter, area

Shape/Irregularity: concavity, concave points

Texture: texture_mean, texture_worst

Target: 0 = Malignant 🔴, 1 = Benign 🟦

🔍 Analysis Steps

Data Exploration: distributions, class balance, outliers

Correlation Analysis: heatmaps to find highly correlated features

Feature Grouping:

Size: average of radius, perimeter, area

Shape/Irregularity: average of concave points, concavity

Texture: average of texture features

Visualizations:

KDE, histograms, violin plots, scatterplots, pairplots

Preprocessing:

Remove unnecessary features (target_num)

Scale numeric features if required

Train/test split

💡 Key Insights

Most impactful features: Size & boundary irregularity

Malignant tumors: larger 🔴, more irregular edges

Benign tumors: smaller 🟦, smoother edges

Texture features: subtle differences

Feature grouping: simplifies visualization & highlights patterns

📈 Visualizations

Distribution plots (KDE, histogram, violin)

Scatterplots & pairplots for top features

Heatmaps showing feature correlations and clusters

Grouped feature plots for size, shape, texture

🛠 Technologies

Python 3.x

pandas, numpy, matplotlib, seaborn

scikit-learn (preprocessing & modeling)

✅ Conclusion

Tumor size and edge irregularity are the primary drivers of malignancy detection, while texture features provide additional support. Grouping features enhances interpretability and informs predictive modeling.
