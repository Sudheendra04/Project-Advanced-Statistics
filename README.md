# Project-Advanced-Statistics
Principal Component Analysis, hypothesis for conducting one-way ANOVA for both Education and Occupation individually.

## Course Description

Multivariate Statistical techniques are important tools for understanding Analysis of Dependence and Analysis of Interdependence. The techniques covered in this course would help you in testing for differences between groups, estimating and predicting the impact of an independent variable on a dependent variable, and characterizing the underlying factors, given a set of items, that best summarize the data using dimension reduction techniques.
This project gives the basic concepts of the most important multivariate techniques, with an overview of actual applications in various fields.

## Project Objectives

Select appropriate multivariate statistical techniques for answering the appropriate research questions derived from the problem statement.
Understand the various assumptions needed for the various methodologies and testing of assumptions.
Analyze and draw inferences from data using appropriate statistical methods and computer software.  
Be able to identify the merits and limitations of various statistical techniques

Basics of ANOVA, ANOVA with interaction effects
Exploratory Data Analysis (EDA)
Principal Component Analysis 

Problem 1A:
Salary is hypothesized to depend on educational qualification and occupation. To understand the dependency, the salaries of 40 individuals [SalaryData.csv] are collected and each person’s educational qualification and occupation are noted. Educational qualification is at three levels, High school graduate, Bachelor, and Doctorate. Occupation is at four levels, Administrative and clerical, Sales, Professional or specialty, and Executive or managerial. A different number of observations are in each level of education – occupation combination.

Problem 1B:

What is the interaction between two treatments? Analyze the effects of one variable on the other (Education and Occupation) with the help of an interaction plot.[hint: use the ‘pointplot’ function from the ‘seaborn’ function]
Perform a two-way ANOVA based on Salary with respect to both Education and Occupation (along with their interaction Education*Occupation). State the null and alternative hypotheses and state your results. How will you interpret this result?
Explain the business implications of performing ANOVA for this particular case study.

Problem 2:

The dataset Education - Post 12th Standard.csv contains information on various colleges. You are expected to do a Principal Component Analysis for this case study according to the instructions given. The data dictionary of the 'Education - Post 12th Standard.csv' can be found in the following file: Data Dictionary.xlsx.

Perform Exploratory Data Analysis [both univariate and multivariate analysis to be performed]. What insight do you draw from the EDA?
Is scaling necessary for PCA in this case? Give justification and perform scaling.
Comment on the comparison between the covariance and the correlation matrices from this data [on scaled data].
Check the dataset for outliers before and after scaling. What insight do you derive here? [Please do not treat Outliers unless specifically asked to do so]
Extract the eigenvalues and eigenvectors.[Using Sklearn PCA Print Both]
Perform PCA and export the data of the Principal Component (eigenvectors) into a data frame with the original features
Write down the explicit form of the first PC (in terms of the eigenvectors. Use values with two places of decimals only). [hint: write the linear equation of PC in terms of eigenvectors and corresponding features]
Consider the cumulative values of the eigenvalues. How does it help you to decide on the optimum number of principal components? What do the eigenvectors indicate?
Explain the business implication of using the Principal Component Analysis for this case study. How may PCs help in the further analysis? [Hint: Write Interpretations of the Principal Components Obtained]
