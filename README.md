# Project-2
HT Motor Project
   [1] Mount Google Drive: I mounted my Google Drive in the Colab environment to access files stored in my drive

    [2] Import Libraries: I imported necessary libraries, including pandas, numpy, seaborn, statsmodels, and matplotlib.

    [3] Read CSV Data: I read a CSV file from my Google Drive using pandas and displayed basic information about the dataset.

    [4]  Data Cleaning:
        I observed a DtypeWarning for mixed types in column 7.
        Checked for missing values and found missing values in 'V-phase' and 'W-phase'.
        Dropped rows with missing values.
        Dropped the 'Fault_Rate' column.

    [5] Label Encoding: I used LabelEncoder from scikit-learn to encode the 'Fault_Type' column, converting categorical labels into numerical values.

    [6]  Exploratory Data Analysis (EDA):
        I plotted a rolling mean line graph for selected features.
        Visualized Fault_Type distribution using a count plot and a pie chart.
        Created a scatterplot for 'Temperature_housing_A' vs 'Temperature_housing_B' with colors indicating 'Fault_Type'.
        Generated a heatmap to visualize the correlation matrix between features.

   [7] Data Visualization:
        Box plot and histograms for numerical columns in my dataset.

  [8]  Modeling:
        Split the data into training and testing sets.
        Applied a logistic regression model with a multinomial setting to predict 'Fault_Type'.
        Evaluated the model using accuracy, confusion matrix, and classification report.

