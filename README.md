# Statistical Analysis and Data Visualization for In-Depth Understanding of Multidimensional Cancer Data in Python

### Contributors
- **Abir Lassoued**
- **Eya Bendoudou**
- **Hamdi Belanez**
- **Wafa Jebali**

## Objective
This project utilizes advanced statistical analysis and visualization techniques to explore the characteristics of breast cancer using a multidimensional dataset. We developed a predictive model based on logistic regression and employed sophisticated visualizations to identify trends and risk factors associated with breast cancer. The primary goal is to contribute to prevention efforts and improve clinical interventions for breast cancer.

## Key Variables Analyzed
- **Diagnosis**: Indicates whether the tumor is benign (B) or malignant (M).
- **Texture Mean**: Measures the local variation in gray levels in a scanned medical image of breast tissue.
- **Radius Mean**: Represents the average distance from the center to a point on the perimeter of a detected tumor mass in the medical image.

## Project Structure
1. **Data Preprocessing**
   - DataFrame Dimensions and Information
   - Data Types of Each Column
   - Missing Values Check
   - Displaying First Few Rows
   - Dropping Unnecessary Columns
   - Identifying Duplicate Rows
   - Descriptive Statistics (All Columns)
   - Identifying Categorical and Numerical Variables

2. **Univariate Descriptive Analysis**
   - **Qualitative**: Chi-Square Test, Bar Plot, Pie Chart
   - **Quantitative**: Normality Assessment, Histogram, KDE, Boxplot

3. **Bivariate Descriptive Analysis**
   - **Quantitative-Quantitative**: Correlation Matrix, Pearson’s r, Kendall’s tau, Scatter Plot, Pair Plot
   - **Qualitative-Quantitative**: t-Test, ANOVA, Histograms, Boxplot

4. **Multivariate Descriptive Analysis: PCA**
   - Handling Missing Values and Initializing PCA
   - Eigenvalue Analysis and Cumulative Explained Variance
   - Bar Plot, Data Transformation, and Visualization
   - Scatter Plot (First Factorial Plane), Correlation Circle

5. **Visualization Techniques**
   - Scatter Plot, Line Plot, Histogram, Bar Plot
   - KDE Plot, Boxplot, Violin Plot
   - Facet Grid with Histplot, Pair Plots
   - Joint Plot: Scatter Plot with Marginal Distributions
   - Cluster Maps, Heatmaps, 3D Data Representation
   - Coloring by Numerical ('texture_mean') and Categorical ('species') Variables

6. **Cancer Prediction using Logistic Regression**
   - Data Standardization
   - Data Splitting
   - Logistic Regression
   - Confusion Matrix
