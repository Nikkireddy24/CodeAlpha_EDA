Titanic Dataset — Exploratory Data Analysis (EDA)

Perform Exploratory Data Analysis (EDA) on the Titanic dataset to:
- Ask meaningful questions
- Explore the data structure
- Identify trends, patterns, and anomalies
- Test hypotheses and validate assumptions
- Detect and address potential data issues

EDA Questions
1. What was the overall survival rate?  
2. Did gender affect survival?  
3. Did passenger class affect survival?  
4. What is the age distribution of passengers?  
5. Are there any outliers in passenger ages?

Dataset Details
- Source: Titanic dataset (built-in from the Seaborn library)
- Description: Passenger details including age, sex, ticket class, fare, and survival status
-Tools Used - Python, Pandas, Seaborn, Matplotlib 

Key Steps Performed
- Loaded the dataset using Seaborn
- Inspected the data structure using `.head()`, `.info()`, `.describe()`
- Checked for missing values and duplicates
- Cleaned the data:
  - Dropped the `deck` column due to many missing values
  - Filled missing `age` values with the median age
  - Removed duplicate rows
- Asked key EDA questions and answered them using:
  - Grouped statistics (`groupby` survival rates by gender and class)
  - Visualizations: histogram, boxplot