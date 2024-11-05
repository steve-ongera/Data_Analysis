# Data Preprocessing Pipeline
## Overview
This Python script provides a comprehensive data preprocessing pipeline for two datasets: SubscribersData.csv and ActivityData.csv. The pipeline performs the following steps:

Load Data: The script loads the two CSV files into Pandas DataFrames.
Explore Data: The script prints the first 10 rows of each dataset, checks the shape of the datasets, and examines the null values in each dataset.
Compute Statistics: The script computes and displays the statistical measures (mean, median, standard deviation, etc.) for the numeric columns in each dataset.
Handle Null Values: The script fills the null values in the datasets using appropriate measures of central tendency (median for numeric columns, mode for categorical columns).
Detect Outliers: The script uses the Z-score method to detect outliers in the numeric columns and visualizes the outliers using boxplots.
Remove Outliers: The script removes the detected outliers from the datasets.
Remove Duplicates: The script identifies and removes any duplicate rows from the datasets.
Save Preprocessed Datasets: The script saves the cleaned and preprocessed datasets to new CSV files.
Print Preprocessing Summary: The script provides a summary of the preprocessing steps, including the original and final number of rows, the percentage of data retained, and the column-wise null values after cleaning.
Visualize Cleaned Data Distributions: The script creates histogram plots with kernel density estimation (KDE) to visualize the distributions of the numeric columns in the cleaned datasets.

## Prerequisites

Python 3.x
Required libraries: pandas, numpy, matplotlib, seaborn, scipy

## Installation

Ensure you have Python 3.x installed on your system.
Install the required libraries using pip:

pip install pandas numpy matplotlib seaborn scipy

## Usage

Ensure the CSV files (SubscribersData.csv and ActivityData.csv) are located in the correct directory specified in the script.
Run the script, and it will perform the data preprocessing pipeline and save the cleaned datasets.
The preprocessed datasets will be saved as preprocessed_subscriber_data.csv and preprocessed_activity_data.csv.
The script will also display various summary information and visualizations throughout the process.

## Key Features

- Comprehensive data exploration and preprocessing steps
- Handling of null values using appropriate measures of central tendency
- Outlier detection and removal using Z-score
- Duplicate row identification and removal
- Saving of preprocessed datasets
- Detailed summary of the preprocessing steps
- Visualization of the cleaned data distributions

## Customization
The script can be customized further by:

- Modifying the file paths for the input and output CSV files
- Adjusting the thresholds or parameters used in the outlier detection
- Adding or modifying the data preprocessing steps based on specific requirements
- Enhancing the visualization or adding more data analysis components

Feel free to explore and adapt the script to fit your data preprocessing needs.
Contribution
If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request on the project's GitHub repository.

## License
This project is licensed under the MIT License.
+254 112284093 