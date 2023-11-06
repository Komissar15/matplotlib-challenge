About
This project analyzes the data provided by Pymaceuticals Inc., focusing on various aspects of the study, including data cleaning, summary statistics, data visualization, and statistical analysis.

Dependencies and Setup
Before running the code in this repository, ensure that you have the necessary dependencies and setup. The following Python libraries are required:

matplotlib
pandas
scipy

Data Cleaning
The data cleaning process involves:

Identifying and removing duplicate entries for a mouse with ID 'g989.'
Confirming that the dataset is uniquely identified by 'Mouse ID' and 'Timepoint.'
Summary Statistics
This section calculates summary statistics for each drug regimen, including mean, median, variance, standard deviation, and standard error of the mean (SEM) of the tumor volume.

Bar and Pie Charts
Visualizations are created to represent the data, including:

Bar plots showing the total number of observations for each drug regimen.
Pie charts displaying the distribution of male and female mice in the study.
Quartiles, Outliers, and Boxplots
This section identifies potential outliers in the final tumor volume for specific treatment regimens, including Capomulin, Ramicane, Infubinol, and Ceftamin. Boxplots are used to visualize the distribution of tumor volume for each treatment group.

Line and Scatter Plots
A line plot is generated to show the tumor volume over time for a single mouse treated with Capomulin.
A scatter plot represents the relationship between mouse weight and the average observed tumor volume for the entire Capomulin regimen.
Correlation and Regression
A scatter plot is created to visualize the correlation between mouse weight and average tumor volume for Capomulin-treated mice. A linear regression model is fitted to the data, and the correlation coefficient is calculated.




