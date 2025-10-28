You are provided with a weather dataset in CSV format containing various meteorological measurements (e.g., temperature, humidity, wind speed, visibility, etc.) along with a categorical target column named Weather (e.g., Clear, Rain, Fog, Snow, etc.). Your task is to build a supervised classification pipeline to predict the weather condition based on the given features.

Your solution must include the following steps and deliverables:

Data Loading & Overview
    • Load the dataset using pandas
    • Display top records and briefly describe the structure
Exploratory Analysis
    • Show the distribution of the Weather classes (e.g., value_counts)
    • Identify any obvious data quality issues if present
Pre-processing
    • Separate features (X) and target (y)
    • Perform a train-test split
Modeling using Decision Trees
    • Train Decision Tree models with multiple max_depth values (e.g., 1–9 & None)
    • Evaluate and record train vs. test accuracy for each configuration
Analysis & Conclusion
    • Compare how model depth affects overfitting / generalization
    • State which depth performs best and why
Write the entire solution in a well-formatted notebook style, with code + markdown explanation for each step.
