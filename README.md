# Statistical Data Analysis Course Labs

This repository serves as a directory to all the laboratory works I've completed for the Statistical Data Analysis course at [University Name]. Each lab focuses on different aspects of statistical analysis using the R programming language.

## Course Information

- **Institution**: [University of Warsaw]
- **Course**: Statistical Data Analysis
- **Term**: [Spring 2024]
- **Instructors**: [Błażej Miasojedow, Barbara Domżał, Szymon Nowakowski]

## Labs Overview

Below is a list of laboratory works, each contained within its own repository, along with a brief description of the topics covered and the main objectives.

### Lab 1: First Statistical Report

- **Repository**: [Click to see](https://github.com/dimanaumow/Lab1-First-Statistical-Report)

- **Description**: This lab serves as an introduction to creating comprehensive statistical reports. It focuses on the fundamental 
skills required to process, analyze, and present data in a clear and informative manner using R. 
The objective is to guide students through the complete process of statistical analysis — from data collection to the final presentation of results.

- **Topics Covered**:
  - **Data Collection and Preparation**: Introduction to data collection methods, data cleaning, and preparation techniques.
  - **Descriptive Statistics**: Computing and interpreting measures of central tendency (mean, median, mode) and dispersion (variance, standard deviation, range).
  - **Data Visualization**: Creating effective visual representations of data, including histograms, box plots, and scatter plots.
  - **Report Writing**: Structuring and writing a statistical report. Emphasis on how to present statistical findings clearly and effectively.
  - **R Markdown**: Introduction to R Markdown for creating dynamic analysis reports that combine code, output, and narrative text.

- **Key R Packages**: `dplyr` for data manipulation, `ggplot2` for data visualization, `knitr` and `rmarkdown` for report generation.

- **Learning Outcomes**:
  - Acquire the skills to clean and prepare data for analysis.
  - Understand and apply basic descriptive statistics and data visualization techniques.
  - Develop the ability to communicate statistical findings through comprehensive reports.
  - Learn to use R Markdown to create reproducible statistical reports that integrate R code, results, and analysis narrative.
- **Challenges Encountered**: Discussion of any challenges encountered during the data analysis and report writing process, and how they were addressed.

### Lab 2: Parameter Estimation

- **Repository**: [https://github.com/dimanaumow/Lab-2-Parameter-Estimation]

- **Description**: This laboratory work focuses on the fundamental concepts and techniques of parameter estimation in statistical analysis. 
The main objectives include understanding the principles of point estimation and interval estimation, 
implementing various estimation methods using the R programming language, 
and applying these methods to real-world datasets to estimate population parameters based on sample data.

- **Topics Covered**:
  - Introduction to parameter estimation: Understanding the difference between point estimates and interval estimates.
  - Methods of estimation: Exploring different estimation methods, including Maximum Likelihood Estimation (MLE), Method of Moments, and Bayesian Estimation.
  - Confidence intervals: Calculating confidence intervals for population means, proportions, and variances.
  - Application to real-world data: Using R to apply estimation methods to datasets to infer about population parameters.

- **Key R Packages**: `stats`, `MASS`, `bayesplot`

- **Learning Outcomes**:
  - Gain a solid understanding of the theoretical foundations of parameter estimation.
  - Develop practical skills in applying estimation techniques to analyze data using R.
  - Learn how to interpret the results of parameter estimation in the context of data analysis.
- **Challenges Encountered**: Discuss any particular challenges you faced during the lab and how you addressed them.
- **Repository**: [Link to Lab 2]
- **Description**: Techniques for visualizing data using ggplot2 and other R packages.


### Lab 3: Loading Data and Confidence Intervals

- **Repository**: [https://github.com/dimanaumow/Lab1-First-Statistical-Report]

- **Description**: This lab introduces the essential skills required for loading and manipulating data in R, followed 
by the construction and interpretation of confidence intervals for statistical analysis. The focus is on practical data handling techniques 
and the fundamental concepts of inferential statistics.

- **Topics Covered**:
  - **Data Loading**: Techniques for importing data from various sources into R. Exploring R functions for reading data files (CSV, Excel, etc.).
  - **Data Manipulation**: Basic data manipulation operations in R including data cleaning, filtering, and transformations using dplyr and tidyr.
  - **Confidence Intervals**: Understanding the concept of confidence intervals and their importance in inferential statistics. Learning how to calculate 
and interpret confidence intervals for means, proportions, and variances in R.

  - **Practical Application**: Applying these concepts to a real-world dataset to perform exploratory data analysis and draw conclusions from sample data.

- **Key R Packages**: `readr`, `dplyr`, `tidyr`, `ggplot2` for data visualization, and `stats` for statistical functions.

- **Learning Outcomes**:
  - Master the ability to load and manipulate datasets in R.
  - Understand the theoretical basis and practical calculation of confidence intervals.
  - Apply data analysis techniques to derive insights from real-world data.
- **Challenges Encountered**: Reflecting on any challenges faced during the lab, such as difficulties in data 
manipulation or understanding the statistical concepts, and how these were overcome.


### Lab 4: Hypothesis Testing

- **Repository**: [https://github.com/dimanaumow/Lab1-First-Statistical-Report]

- **Description**: This lab focuses on the fundamental concepts of hypothesis testing within the realm of statistical analysis. 
The aim is to provide a hands-on experience in formulating and testing statistical hypotheses using R, covering various types of tests to analyze different data sets.

- **Topics Covered**:
  - **Basics of Hypothesis Testing**: Introduction to null and alternative hypotheses, significance levels, and p-values.
  - **Types of Tests**: Detailed exploration of one-sample t-tests, two-sample t-tests, paired tests, and chi-squared tests for categorical data.
  - **Decision Making**: How to interpret the results of statistical tests and make data-driven decisions.
  - **Practical Applications**: Applying hypothesis testing to real-world data to understand its practical implications.

- **Key R Packages**: `stats`, `dplyr`, `ggplot2` for visualization of test results.

- **Learning Outcomes**:
  - Understand the theory and application of hypothesis testing in statistical analysis.
  - Develop proficiency in performing different types of hypothesis tests using R.
  - Learn to make informed conclusions from statistical analysis of data.


### Lab 5: Testing Multiple Hypotheses

- **Repository**: [https://github.com/dimanaumow/Lab1-First-Statistical-Report]

- **Description**: Building on the foundational concepts of hypothesis testing, this lab delves into the challenges 
and methodologies associated with testing multiple hypotheses simultaneously. Emphasis is placed on understanding the 
problem of multiple comparisons and implementing techniques to control for false discovery rates.

- **Topics Covered**:
  - **Multiple Comparison Problem**: Introduction to the issues arising from multiple hypothesis testing, including the increased risk of Type I errors.
  - **Correction Methods**: Overview of Bonferroni correction, Holm-Bonferroni method, and Benjamini-Hochberg procedure.
  - **Case Studies**: Application of multiple hypothesis testing methods on datasets to illustrate the impact of corrections on p-values and statistical conclusions.
  - **Best Practices**: Guidelines for conducting multiple hypothesis tests responsibly and interpreting the results accurately.

- **Key R Packages**: `stats`, `p.adjust`, `ggplot2` for enhanced visualization of multiple testing results.

- **Learning Outcomes**:
  - Gain insight into the complexities of multiple hypothesis testing and the importance of error control.
  - Acquire skills in applying appropriate correction methods for multiple comparisons in R.
  - Develop the ability to critically evaluate the results of multiple hypothesis tests and their implications for statistical inference.


### Lab 6: Linear Regression

- **Repository**: [https://github.com/dimanaumow/Lab1-First-Statistical-Report]

- **Description**: This laboratory work is dedicated to exploring linear regression, one of the most fundamental techniques 
in statistical analysis and machine learning. It aims to provide practical experience in modeling relationships 
between dependent and independent variables using R. The lab focuses on fitting, evaluating, and interpreting linear regression models to analyze and predict data.

- **Topics Covered**:
  - **Introduction to Linear Regression**: Basics of regression analysis, assumptions behind linear regression models.
  - **Model Fitting**: Using R to fit linear regression models to datasets. Understanding the output provided by R's regression functions.
  - **Model Evaluation**: Techniques for evaluating the performance and validity of regression models, including R-squared, Adjusted R-squared, and residual analysis.
  - **Multiple Linear Regression**: Extending beyond simple linear regression to include multiple predictors. Addressing multicollinearity and interactions between variables.
  - **Predictive Modeling**: Applying linear regression models for prediction. Use of training and test datasets to assess model predictive performance.

- **Key R Packages**: `stats`, `ggplot2` for data visualization, `car` for advanced regression diagnostics.

- **Learning Outcomes**:
  - Understand the theory and assumptions underlying linear regression analysis.
  - Gain proficiency in fitting and evaluating linear regression models using R.
  - Develop the ability to interpret the results of regression analysis in the context of data.
  - Acquire skills in using regression models for predictive purposes and decision-making.
- **Challenges Encountered**: Any difficulties faced during the analysis, such as dealing with non-linearity, heteroscedasticity, 
or outliers, and strategies employed to overcome these issues.


## Tools and Technologies

Throughout these labs, the following tools and technologies were used:

- **Programming Language**: R
- **IDE**: [RStudio]
- **Key R Packages**: ggplot2

## Acknowledgements

I'd like to thank [Błażej Miasojedow, Barbara Domżał, Szymon Nowakowski] for guiding us through this course and providing insightful feedback on our work.




Feel free to explore each lab's repository for detailed explanations, code, and results. 
If you have any questions or feedback, please open an issue in the respective lab's repository.