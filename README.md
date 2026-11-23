# Titanic-Data-Analysis
Exploratory data analysis and visualization of Titanic passenger survival.

## Dataset
[Kaggle Titanic dataset](https://www.kaggle.com/c/titanic): 891 passengers, 12 columns.

## Objective
Find out which factors affected survival on the Titanic.

## What I Did
- Inspected the data (shape, types, missing values, duplicates)
- Cleaned it: filled 177 missing ages with the median, 687 cabins with "Unknown" and 2 ports with the mode
- Created new features: `FamilySize`, `AgeGroup`, `Title`
- Explored survival by gender, class, age, family size and port using charts

## Key Findings
- Only about 38% of passengers survived
- 74% of women survived vs 19% of men
- 63% of 1st class survived vs 24% of 3rd class
- Children had the best chances (about 58%)
- Small families (2 to 4 people) did better than people travelling alone or in big families

## Conclusion
Survival was not random. Women, children and 1st class passengers had much better chances. These results show patterns, not proven causes.

## Limitations
Missing ages were filled with the median, and most cabin data is missing.

## Tools
Python, pandas, matplotlib, seaborn
