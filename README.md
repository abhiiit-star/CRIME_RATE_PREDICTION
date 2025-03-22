Overview

This project analyzes the socio-economic and demographic factors influencing crime rates across 136 countries using a data-driven approach. 
The study leverages Ordinary Least Squares (OLS) regression modeling to explore relationships between variables such as GDP per capita, unemployment rate, 
population density, firearm ownership, internet usage, and global peace index, aiming to uncover insights into crime trends on a global scale.

Objective
The primary goal is to identify key socio-economic determinants of crime rates and assess their impact using statistical and machine learning techniques. 
The study also tests various economic and criminological theories, including:

✔ Becker's Economic Theory of Crime – Individuals commit crimes when perceived benefits outweigh risks.
✔ Social Disorganization Theory – Crime flourishes in disorganized communities.
✔ Routine Activity Theory – Crime depends on available opportunities.

Methodology
✔ Data Collection & Preprocessing: Cross-sectional data for 136 countries (2022), handling missing values, outlier detection, and log transformations.
✔ Exploratory Data Analysis (EDA): Visualizations (box plots, scatter plots, correlation matrices) to identify trends.
✔ Feature Selection & Model Fitting: Iterative variable elimination based on significance (p-values, VIF).
✔ Final Model (OLS Regression):

CR = 287.30 + (-5.73) × GDP + (-1.67) × PD + (-179.16) × SR + (5.76) × GPI

where CR = Crime Rate, PD = Population Density, SR = Sex Ratio, GPI = Global Peace Index.

Key Findings
📉 Higher GDP is significantly associated with lower crime rates.
📉 Higher population density has a mild negative effect on crime.
📉 Lower sex ratio (more males) correlates with higher crime rates.
📈 Higher Global Peace Index (less peaceful countries) is linked to higher crime rates.

Conclusion
Economic stability, better opportunities, and social stability play a crucial role in reducing crime rates. Policymakers should focus on economic development, gender balance, and conflict resolution strategies to curb crime.
