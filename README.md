# pandas-challenge
#Imported the data, combined it into a dataset, and merged it.
#District Summary
    #Used "len" for counting purposes, "sum" for adding columns up, and "mean" for finding the averages.
    #Used the .loc function to find specific values that matched the condiitons desired, such as passing scores.
    #Combined all information into a dataframe.
#School Summary
    #Used "groupby" to extract data from certain columns. Made sure to include the "school name" column in every groupby.
    #Added "sum", "count", or "mean" to the groupbys to calculate the data while designating the columns
    #Merged each groupby by school name, adding them one by one, until they formed one large dataset. Renamed the columns to appropriately reflect their data.
#Top Performing Schools
    #Used the "sort" function and applied it to the previous "% Overall Passing" column. Because the default sorting is ascending, I added "ascending=False" to show the values in descending order. Added .head (5) to only show the top 5 performing schools.
#Bottom Performing Schools
    #Used the "sort" function and applied it to the "% Overall Passing" column. Ascending order is the default sorting type, so I left it as it was. I added .head(5) to only show the bottom 5 performing schools.
# Math Scores by Grade
    #Created groupbys for each grade's average math score. Involved .loc to find only values corresponding to the students' grade.
    #Merged all the math score groupbys by school name, one by one into a single dataframe.
    #Renamed the columns to appropriately reflect the data in each column.
#Reading Score by Grade
    #Repeated the same steps as above, but for reading scores instead.
#Scores by School Spending
    #Found the max and min values to determin appropriate bin ranges.
    #Created bins and ranges, then sliced the data according to the created bins.
    #Made a column for the spending ranges, then created a series for each parameter, all while taking the average per groupby.
    #Combined all the groupbys into a dataframe, organized by spending ranges per student.
#Scores by School Size
    #Created bins and labels, then added a column based on these bins.
    #Created groupbys for each column, taking the average of each.
    #Combined all groupbys into a single dataframe.
#Scores by School Type
    #Created a student count for each type of school to use for percentage calculations.
    #Grouped variables based on type and each parameter.
    #Created a dataframe to hold the scores by school type data.
