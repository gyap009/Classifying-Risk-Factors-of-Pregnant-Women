# Classifying Risk Factors of Pregnant Women

## Overview
This project utilizes data science techniques to identify distinct subgroups within a population of pregnant women and assess their associated risk factors. The goal is to help healthcare providers tailor personalized prenatal care interventions to improve maternal and fetal health outcomes. The project primarily employs Hierarchical Clustering to group women based on similarities in characteristics such as age, blood pressure, and other relevant factors, thereby identifying distinct risk profiles.

## Dataset
The dataset used in this project is the **"Maternal Health Risk Data Set,"** which includes the following columns:
- `Age`: Age of the pregnant woman
- `SystolicBP`: Systolic blood pressure
- `DiastolicBP`: Diastolic blood pressure
- `BS`: Blood sugar level
- `BodyTemp`: Body temperature
- `HeartRate`: Heart rate
- `RiskLevel`: Risk level classified as low, mid, or high

## Data Exploration and Cleaning
Initial data exploration and cleaning steps included:
- Loading the dataset
- Handling missing values
- Standardizing numerical features

## Data Visualization
Data visualization was conducted to gain insights into the dataset:
- Histograms and density plots for continuous variables
- Box plots to identify outliers
- Dendrograms for hierarchical clustering

## Data Preprocessing
The preprocessing steps involved:
- Standardizing numerical features using `StandardScaler`

## Clustering with Hierarchical Clustering
The Hierarchical Clustering algorithm was applied to identify distinct subgroups among the pregnant women based on their characteristics. Key steps included:
- Performing hierarchical clustering using the linkage method
- Visualizing the dendrogram to determine optimal clusters
- Analyzing and interpreting the resulting clusters
- Hypothesis Testing

## Conclusion
Key takeaways from this project:
- Distinct subgroups with differing risk profiles were identified among the pregnant women, aiding in personalized care.
- The use of hierarchical clustering was effective in identifying these subgroups, as shown by the dendrogram analysis.

### Summary for stakeholders:
- The clustering analysis enabled the identification of subgroups with varying risk levels, which can inform targeted healthcare interventions.
- The success of this clustering approach suggests its potential applicability in other healthcare-related projects.
