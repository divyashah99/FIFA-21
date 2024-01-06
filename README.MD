# FIFA 21 Data Cleaning and Transformation Project

This project focuses on cleaning and transforming FIFA 2021 player data to make it more suitable for analysis. The dataset contains information about FIFA 21 players, including their attributes, personal details, and performance data. In order to perform meaningful analyses on this dataset, we address the following key questions:

1. **Handling Missing Values**:
   - We identify and deal with missing values in the dataset. Missing data can affect the quality of analysis, and our approach ensures that we don't lose critical information during data cleaning.

2. **Data Type Correction**:
   - We assess the data types of the 'height' and 'weight' columns. If necessary, we convert them to appropriate data types to facilitate further analysis.

3. **Splitting Date Columns**:
   - We split the date-related column, typically 'joined,' into separate 'year,' 'month,' and 'day' columns. This separation makes it easier to analyze player acquisition dates.

4. **Value, Wage, and Release Clause Transformation**:
   - We clean and transform the 'value,' 'wage,' and 'release clause' columns into integer data types. This conversion simplifies monetary calculations and comparisons.
