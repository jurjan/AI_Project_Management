# Management and documentation of data collection, preparation, feature engineering and selection

* Duomenų rinkimas / Data Collection
  * Duomenų šaltiniai / Sources of Data: Internal vs. External data, APIs, surveys, sensors, etc.
  * Duomenų tipai / Data Types: Structured, unstructured, time-series, categorical, continuous
  * Įrankiai ir technikos / Tools & Techniques: Data scraping, database querying, data ingestion from files (CSV, JSON, etc.)
  * Dokumentacija / Documentation Best Practices: Version control for datasets, data collection methodologies, metadata
  * Iššūkiai / Challenges: Missing data, data consistency, data quality

* Duomenų paruošimas / Data Preparation
  * Duomenų paruošimas / Data Cleaning: Handling missing values, removing duplicates, dealing with outliers
  * Duomenų transformavimas / Data Transformation: Normalization, scaling, encoding categorical variables
  * Duomenų rinkinio padalinimas / Splitting the Dataset: Training, validation, and test sets
  * Geriausios praktikos dokumentuojant / Documentation Best Practices: Tracking data cleaning methods, transformations applied, scripts used for preprocessing
  * Įrankiai / Tools: Pandas, NumPy, scikit-learn, etc.
* Feature Engineering
  * Feature Creation: Creating new features from raw data, aggregation, extraction, and transformation
  * Feature Encoding: Techniques for categorical features, such as one-hot encoding, label encoding
  * Dimensionality Reduction: Principal Component Analysis (PCA), t-SNE for feature visualization
  * Tools: Featuretools, scikit-learn, custom scripts
  * Documentation Best Practices: Documenting feature definitions, rationale for transformations, tools/scripts used
* Feature Selection
  * Pagalba: https://machinelearningmastery.com/feature-selection-with-real-and-categorical-data/
  * Methods:
    * Filter methods (Correlation-based Selection, Chi-Square Test, ANOVA F-test, Mutual Information, Variance Threshold)
    * Wrapper methods (Recursive Feature Elimination (RFE), Forward Selection, Backward Elimination, Stepwise Selection)
    * Embedded methods (Lasso Regression (L1 Regularization), Ridge Regression (L2 Regularization)
    * Decision Trees and Random Forests, Gradient Boosting (e.g., XGBoost), Elastic Net)
    * Dimensionality Reduction Methods (Principal Component Analysis (PCA)
    * Linear Discriminant Analysis (LDA), t-SNE)
    * Hybrid Methods (Genetic Algorithms, Simulated Annealing)
  * Evaluation Metrics: Performance with and without certain features (cross-validation, model accuracy)
  * Documentation Best Practices: Tracking selected features, feature importance, rationale for including/excluding features
