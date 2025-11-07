# Predicting Exoplanet Detection Methods Using Stellar and Planetary Characteristics

## Summary

This project explores whether the detection method of an exoplanet can be inferred from its stellar and planetary parameters using data-driven modeling. As thousands of exoplanets have been discovered through different techniques such as transit photometry and radial velocity each method introduces unique observational biases that affect which planets are detected. By analyzing physical parameters from the [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PS), this project seeks to understand how these biases shape current discoveries and to model the relationship between detection methods and system characteristics.

The problem addressed is the lack of quantitative understanding of how detection methods depend on measurable physical properties. Current analyses in exoplanet science often describe biases qualitatively; this project aims to formalize that understanding through machine learning–based classification and feature analysis.

## Question, Objectives, and Contribution

### Research Question

Can the detection method of an exoplanet be inferred from its stellar and planetary parameters, and which factors most strongly influence this detectability?

### Objectives

1. Develop a predictive model that classifies exoplanet detection methods using key stellar and planetary parameters.
2. Identify the most influential features that contribute to each detection technique to reveal underlying observational tendencies.
3. Quantify and interpret observational biases in current exoplanet datasets to improve understanding of detection limitations.
4. Provide insights for future detection planning, such as which types of planets or systems are more likely to be observed by specific methods.

### Contribution

This project contributes to the field of exoplanet science by providing:

* A **data-driven analysis** of detection biases across thousands of known exoplanets.
* **Interpretable results** that connect physical system properties with detection likelihood.
* **Insights for more efficient observation strategies**, helping future missions target planetary systems that are more likely to be detectable by specific techniques.

## Suggested Methodology

### 1. Data Collection

Data will be obtained from the [**NASA Exoplanet Archive**](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PS), containing physical and orbital parameters of confirmed exoplanets along with their detection methods.

### 2. Feature Selection

Around nine key stellar and planetary features will be selected based on completeness and relevance to detection likelihood.

### 3. Data Preprocessing

The dataset will be cleaned, missing values handled, categorical variables encoded, and numerical features standardized for consistency.

### 4. Modeling

Supervised classification models will be trained to predict detection methods, and their performance will be evaluated using standard metrics.

### 5. Feature Analysis and Interpretability

Feature importance analysis will reveal which planetary and stellar characteristics most influence the predicted detection method.

### 6. Evaluation

Model accuracy and generalization will be validated through data partitioning and cross-validation to ensure robust results.
