Data Wrangling highlights to use:

1. Story and background for each step and code.
2. Read csv from website (github)
3. Aggregations using sum, mean
4. Comparing similar columns using !=
5. Groupby for comparison of similar columns
6. Explanation of subplots
7. setting "style" to plot on darkmode colab
8. ex. of side-by-side barplot on same graph
9. pd.melt to compare very similar columns (ticket prices)
10. side-by-side bar plot and "hue" which is groupby
11. how to deal with missing values and explanation/code of why we did it
    - when comparing 2 columns, finding percentages of values where we're not missing any data, 1 data in either column, or missing data in both columns (per row).
    - dropping column using "!="
12. histogram of dataframe and explanation of problem plots/variables
    - usling logic for outliers such as "2019" for years open
    - checking outliers using ">" (and subsequently "dropping" rows using the same instead of .drop())
    - loc and ">" gets the entire dataframe while df.column[df.column > #] just gets the stupid number (value)
13. Data cleaning using Google to verify outliers
14. changing value using df.loc[row#, column name] = new value
15. plotting histogram using "<" (don't have to make a new variable to plot)
    - same thing with describe()
    - "dropping" data just by subsetting using "<"
16. insane groupby using aggregation
17. importing dataframe using read_html
    - use is to get extra data such as population, state names, area
    - using set() to subtract one df from the other to see missing values (states)
18. using str.contains to find values (equivalent to LIKE in SQL)
    - also using "|" as OR
19. regex to remove string inside bracket "[]"
20. merge dataframes using left join
21. comparing price of 1 column to another (equal should meet at the 45% line)
22. .loc and subsetting by column == value to subset, [output column 1, output column 2]
    
