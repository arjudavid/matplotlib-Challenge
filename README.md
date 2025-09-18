# Matplotlib-Challenge

In this assignment, I’ll apply Matplotlib to a real-world situation and dataset. This is the background of the challenge to take in mind:

**Background**: You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens. The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

**<ins>First<ins>** we will have to prepare the Data. I will run the provided package dependency and data imports, and then merge the "mouse_metadata" and "study_results" DataFrames into a single DataFrame.

Then I will display the number of unique mice IDs in the data, and then check for any mouse ID with duplicate time points. Display the data associated with that mouse ID, and then create a new DataFrame where this data is removed. Use this cleaned DataFrame for the remaining steps, and display the updated number of unique mice IDs.

**<ins>Second<ins>** I will generate a "Summary Statistics", create a DataFrame of summary statistics. The summary statistics should include:

- A row for each drug regimen. These regimen names should be contained in the index column.
- A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.

Generate two bar charts. Both charts should be identical and show the total total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.

**<ins>Third<ins>** I will create the first and second bar chart with the Pandas DataFrame.plot() method. Then generate two pie charts. Both charts should be identical and show the distribution of unique female versus male mice in the study. Create the first and second pie chart with the Pandas DataFrame.plot() method.

**<ins>Fourth<ins>** I will calculate Quartiles, Find Outliers, and Create a Box Plot. To calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens. Use the following substeps:

Using Matplotlib, I will generate a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group. Highlight any potential outliers in the plot by changing their color and style.

**<ins>Lastly<ins>** Create a Line Plot and a Scatter Plot, and a the Correlation and Regression of each one.


## Analysis

In conclusion Capomulin and Ramicane were the only drug regimens to show significant progress in the reduction of the tumor, but Capomulin is slightly better option. The gender of the mice does not affect the size of the tumor, both genders were tested and the average tumor size is about 40 mm3. Most mice with tumors weighted between 17-21 g, and the progression of the Capomulin drug for most mices was around every 20-30 days with an increament size of the tumor followed by a significant reduction of the tumor.

> [!NOTE]
> The data was provided by Mockaroo, LLC (2022). The starter code by edX Boot Camps LLC. The code was written by DAVID ARJUNA, and assisted by Xpert Learning Assistant.
