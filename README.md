# feature_enginnering_titanic_dataset
Feature Engineering

1) Data Cleaning:

1.1) Addressing Missing Values:

Missing data is a common issue in real-world datasets, which can hinder the performance of machine learning models. To handle missing values effectively, various techniques can be employed:

Imputation Methods:

Impute missing values using statistical measures such as mean, median, or mode.
Advanced imputation techniques like KNN imputation, which fills missing values based on the values of neighboring data points.
Understanding the Presence of Missing Values:

Missing values can occur due to different reasons:

- Data Entry Errors: Errors during data collection or entry processes can lead to missing values.
- Non-Response: Participants might choose not to provide certain information, leading to gaps in the dataset.

Types of Missing Data:

(i) Missing Completely at Random (MCAR):
Missing values occur randomly throughout the dataset, unrelated to any observed or missing data. There's no discernible pattern to the missingness.

(ii) Missing Data Not At Random (MNAR):
The missingness is related to the missing values themselves, even after considering observed data. This implies systematic differences between missing and observed data.

(iii) Missing At Random (MAR):
The probability of missing values depends only on observed data, not on the missing data itself. Missingness can be explained by other variables in the dataset.

Strategies for Handling Missing Values:

Mean/Median/Mode Replacement
Random Sample Imputation
Creating a new feature to capture missing values
End of Distribution Imputation
Arbitrary Imputation
Imputing with frequent categories
1.2) Managing Outliers:

Outliers, which are data points significantly different from other observations, can distort analysis results and model performance. Techniques for handling outliers include:

Truncation: Replacing outliers with a specified threshold.
Winsorization: Replacing outliers with the nearest non-outlier value.
Removing outliers altogether if they are deemed erroneous.
