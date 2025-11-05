# Random-Data-Analysis-Tasks
This page houses different tasks and gigs on data analysis.
# Caveat
Please note that you might edit the file path when uploading on your jupyter notebook


# Task 1:

1. Write Python code to filter rows where City_Development_Index > 0.8 and Company_Size is greater than 3.

2. Use iloc to select the first 10 rows and specific columns like Experience and Education_Level.

3. Group data by Relevant_Experience and calculate the average City_Development_Index for each group.

4. Group by Company_Size and count the number of unique entries in Last_New_Job.

5. Analyze the frequency distribution of Company_Type using value_counts().

6. Identify numerical columns with missing values and fill them using the mean

7. Drop rows where more than 50% of data is missing, and document the impacton dataset size.

8. Query the dataset to extract rows where Experience > 10 and Company_Size == 7.

9. Create a new feature Experience_Gap by subtracting Last_New_Job from Experience.

10. Normalize City_Development_Index to a 0–1 scale and explain the benefits of normalization.

11. Create new column cdi_per and merge it to the original dataframe using pd.merge and analyze the combined insights.



# Task 2:
We will use two datasets. One part will involve using the HR Analytics dataset ('job_change_data.csv'), while the other part will use the Students' Performance Record dataset ('students_performance_records.xlsx').

# Steps
Import the required libraries (pandas, matplotlib, numpy).
Load the provided student performance dataset into a pandas DataFrame.
Check for any missing or inconsistent data and handle them accordingly


Questions
**Bar Chart of Average GPA by Grade Class:**
1. Check for any missing or inconsistent data and handle them accordinglyGroup the data by GradeClass and calculate the average GPA for each grade class.

2. Create a bar chart displaying the average GPA for each grade class.
   
3. Use a colormap to color the bars based on the GPA values. Choose a color map that reflects the gradient from low to high GPA.

4. Add annotations to display the exact GPA values on top of the bars.

5. Make sure the chart has an appropriate title, and labels for the x and y axes.

**Scatter Matrix for Study Time, Absences, and GPA:**
1. Create a scatter matrix for the variables StudyTimeWeekly, Absences, and GPA.
   
2. Set the diagonal to histograms to show the distribution of each variable.
   
3. Use a color that stands out for the points, and add titles and grid lines to improve readability.


**Box Plot for Study Time Distribution by Grade Class:**
1. Create a box plot to visualize the distribution of StudyTimeWeekly for each GradeClass.

2. Ensure each grade class has a corresponding box, and label them properly.

3. Add a grid, axis labels, and a title to the plot.

4. Customize the box plot with different colors for each grade class.
   
