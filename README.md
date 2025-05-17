## Workforce Recruitment Effectiveness Analysis

# Table of Content
1. [Problem Statement](#problem-statement)
2. [Data Collection](#data-collection)
3. [Data Cleaning](#data-cleaning)
4. [Exploratory Data Analysis EDA](#exploratory-data-analysis-eda)
5. [Insights and Results](#insights-and-results)
6. [Conclusion](#conclusion)
7. [Suggestions for Further Analysis](#suggestions-for-further-analysis)
8. [Tools Used](#tools-used)

## Problem Statement
An agency responsible for recruiting talent across various organizations was recently asked by their new manager to evaluate the effectiveness of its hiring efforts. Specifically, the manager wanted answers to the following:

- Which division has the highest number of recruitments?

- What position level has the most hires?

- What is the most preferred gender in hiring, and why?

- What additional questions could further enhance recruitment strategy?

However, the records were stored in a cluttered and disorganized CSV file, making it necessary to clean and structure the data before any meaningful analysis.

## Data Collection
The dataset was provided as a CSV file containing the agency's historical recruitment records.

It consisted of 193 rows and over 90 columns, most of which were irrelevant or completely empty.

## Data Cleaning
The data cleaning steps involved:

Removing unnecessary columns: Over 90 columns were dropped due to being irrelevant or empty.

Renaming columns for clarity (e.g., long question-style headers simplified to Division, Position Level, etc.).

Handling nulls and duplicates: Any rows missing critical information were removed.

Standardizing column data (e.g., fixing typos, uniform formatting).

Resetting the index and checking data types to ensure consistency.

After cleaning, we retained 9 meaningful columns for analysis, such as:

- Division

- Position Level

- Gender

- Generation

- Tenure

- Employment Type

## Exploratory Data Analysis (EDA)
Below is a breakdown of the key recruitment metrics based on the cleaned dataset:

1. Division with the Highest Number of Employment
Division	Count
Infrastructure	48
Finance	40
IT	26

Insight: The Infrastructure division has the highest number of recruits, suggesting a high demand for operational or support roles.

2. Most Common Position Level
Position Level	Count
Staff	113
Manager	46
Department Lead	28
Chief/Executive	6

Insight: The majority of hires are at the Staff level, indicating a focus on entry-level or operational workforce.

3. Most Preferred Gender in Hiring
Gender	Count
Female	94
Male	85
Prefer not to answer	13
Non-Binary	1

Insight: Females are slightly more represented in the recruitment data. This may be due to department-specific preferences (e.g., People & Finance divisions traditionally having more female hires).

Insights and Results
Division Insight: Infrastructure and Finance lead recruitment counts, which could reflect organizational priorities or turnover rates.

Position Insight: Entry-level (Staff) positions dominate, showing a potential focus on fresh hires or junior roles.

Gender Insight: While the gender distribution is fairly balanced, there's a slight tilt toward female hires — possibly influenced by the nature of roles or inclusivity efforts.

## Conclusion
The analysis revealed that:

Infrastructure is the division with the highest recruitment rate.

Staff-level positions are most frequently filled.

There’s a slight female majority in hiring, possibly influenced by the nature of roles or organizational culture.

These findings provide insight into recruitment trends and highlight areas that may benefit from strategic hiring plans or deeper analysis.

Suggestions for Further Analysis
To improve future recruitment decisions, the following questions could be explored:

Which generation is most frequently hired?
→ Helps understand age-group preferences or biases.

What is the average tenure across different position levels or divisions?
→ Helps measure retention and satisfaction.

How is gender distributed across divisions or employment types?
→ Helps evaluate diversity and inclusion efforts.

Tools Used
Python: For data wrangling (using Pandas & NumPy)

Seaborn & Matplotlib: For data visualization

Jupyter Notebook: For writing and documenting the workflow

CSV: Data format provided

