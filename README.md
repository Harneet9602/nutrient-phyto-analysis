 🌱 Nutrient and Phytoplankton Biomass Analysis

This Jupyter Notebook contains data exploration and visualization of two environmental datasets:
 Nutrient concentrations (e.g., NH4N, NO2N, NO3N, TN)
 Phytoplankton biomass across groups like Cyanophyceans, Chlorophyceae, and others

 📂 Datasets Used
 `NutAverage.xlsx`: Nutrient concentration data
 `PhytoBiomass.xlsx`: Phytoplankton biomass data
 Data sources are provided via public URLs in the notebook

 📊 What’s Covered

 ✅ Nutrient Dataset
 Handling missing values
 Creating new features: DIN (Dissolved Inorganic Nitrogen), DON (Dissolved Organic Nitrogen)
 Adding an "Averages" row
 Descriptive statistics
 Visualization:
   Area plot
   Line plot
   Box plot
   Scatter plot of NH4N vs DIN

 ✅ Phytoplankton Biomass Dataset
 Filling null values
 Deriving "Others" biomass
 Summary statistics
 Visualizations:
   Barh plot
   KDE plot

 📚 Libraries Used
 `pandas`
 `numpy`
 `matplotlib`
 `seaborn`

This project is part of my Data Science learning journey. It helped me practice:

 Data cleaning and feature engineering
 Pandas DataFrame operations
 Plotting multiple types of visualizations
 Interpreting scientific environmental data

