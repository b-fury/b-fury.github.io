**Multiple Regression Project**

The is the only deliverable in Week Four.  It is the case study titled “Locating New Pam and Susan’s Stores,” described at the end of Chapter 12 of your textbook.

The case involves the decision to locate a new store at one of two candidate sites. The decision will be based on estimates of sales potential, and for this purpose, you will need to develop a multiple regression model to predict sales. Specific case questions are given in the textbook, and the necessary data is in the file named **pamsue.xls.**

Assuming that you are reasonably comfortable with using Excel and its Analysis ToolPak add-in, you should expect to spend _approximately_ 2-3 hours on computer work, and another 3-4 hours on writing the report. It is a good idea not to wait until the last day to do the entire project and write the report.  Content of the report consists of your answers to the case questions, plus computer output(s) to support your answers.  Please keep the entire report - including computer outputs - under 8 printed pages.  Thus, your write up should be concise, and you need to be selective in deciding which computer outputs to include.  You can use your discretion in formatting your write up, but use good writing practices and try to make it look professional  (more on the report format below).

**Project Hints and Guidelines**

It is assumed that you have access to

1. Microsoft Excel with Analysis ToolPak (do NOT use stepwise regression for this project even if it runs on your computer).
2. Data file named **xls** in the DataSets.zip folder.

Basic Excel skills you need are the ability to construct histograms and scatterplots, to create dummy variables, copying or moving columns of data in a spreadsheet, and the ability to use the Correlation and Regression facilities under Data Analysis (available when Analysis ToolPak has been added in). Remember that Analysis ToolPak requires _contiguous_ ranges of data for correlation or regression.

1. Open the file **xls**. First, move the column for **sales** so that it is the rightmost column (it is now to the right of **comtype**). If the old sales column remains but appears empty, delete that column.
2. Obtain a scatterplot of the **sales** on the vertical axis against **comtype** on the horizontal axis. This will give you a good idea of whether different categories of **comtype** appear to differ in sales. In the scatterplot, you should see that sales in the middle categories 3 - 6 are in similar ranges on the vertical axis, but 1 and 2 have somewhat higher sales, and category 7 appears to have somewhat lower sales. This implies that, when you create dummy variables for **comtype**, dummy variables for categories 1, 2, 7 are likely to be statistically significant in the multiple regression model (and dummy variables for categories 3 - 6 are likely to be not significant). Although it would be desirable to also obtain the scatterplot of **sales** against every other X variable, you can omit these if you do not have time, and use the correlation coefficients instead (see step 4 below).
3. Insert seven new columns immediately to the left of **comtype**, and in these columns, create seven dummy variables to represent the seven categories of site types. Name them **comtype1, comtype2, ..., comtype7**. At this point, you have 40 columns of data in the spreadsheet with **comtype** and **sales** in the last two columns.
4. Use the Correlation facility under Data Analysis to obtain the correlation coefficients between **sales** and all of the other variables except **store** and **comtype** (why exclude comtype?). This will produce a matrix of correlation coefficients between **sales** and every X variable, as well as between every pair of X variables. To make them easy to read, you may want to format the cells to show numbers with 2 or 3 decimal places.
5. Write down the names of 10 quantitative X variables having the highest correlations with **sales**. From the correlations worksheet, move to the data worksheet. Select the following columns: **sales**, plus the 10 quantitative X variables you wrote down, plus **comtype1**, **comptype2**, **comptype7** (here, you could include up to three more dummy variables, but they are likely to be statistically not significant, so you can save some work - see 2. above). Copy these onto a blank worksheet. Make sure there are no blank columns in within the data range in the new worksheet. : To prevent unexpected changes in copying data when formulas are involved, use Paste Special with Values selected when pasting data into a new worksheet.
    
    Note
    
6. Use Regression under Data Analysis to obtain the regression output table for **sales** using the variables in the columns you had selected, making sure that Labels and New Worksheet Ply checkboxes are checked, and leave the other boxes unchecked. On the name tab of the output sheet (at the bottom), change the name of the worksheet to Model1.
7. Using appropriate statistics in the regression output table, see if any of the X variables is statistically not significant. If there is at least one insignificant X variable, write down the most insignificant variable, move to the data sheet and delete that column, and re-run Regression without that variable. Repeat until there are no insignificant X variables. Name each output sheet Model2, Model3, and so on for easy identification.
8. When you get to a model in which all remaining X variables are statistically significant, you will have found the final regression equation for predicting Re-run the last model, but this time checking the Residuals checkbox. This will reproduce the last regression table, but below it, you will see columns for Predicted sales and Residuals. Obtain a scatterplot of Residuals against Predicted sales. Also obtain a histogram of Residuals.
9. Use the final regression equation you found in the last step to predict **sales** at the two sites under consideration.

You have just completed all necessary computer work for your project report.  Now you have to write a report to present your answers to the case questions (see pages 433-434 of your textbook), and the reasons for those answers.  In terms of physical organization, a reasonable format for the report is described below.

**Content and Format of the Project Report**

**Cover page**

Include the report title, your name, course, section, facilitator, and date.  Go to a new page, and use the following subsection headings for the report.

**Introduction**

One paragraph (two at most) describing the subject and context of the project.

**Data**

One or two paragraphs describing the data in plain English (number of variables, number of observations, units for data values, etc.)

**Results and Discussion**

This is the main body of the report.  It is where you will describe what you have done, what you found, and answer the case questions with the reasons for your answers.  These reasons should be based on the analytical work you have done using Excel.  Depending on how concisely you write and how many tables and graphs you include, this page could be 3-4 pages long.

**Conclusion**

One or two paragraphs discussing any remaining issues (e.g. shortcomings and possible improvements of the analyses in the report).

In the Results and Discussion section, you should include a few informative tables or graphs derived from your computer analyses.  DO NOT include anything that is not absolutely necessary.  DO NOT include entire worksheets form Excel, but only the parts you need.  For example, do not include the entire correlation matrix found in step 4 above, but you can make a small table to show the 10 variables having the highest correlations with **sales**.   You _should_ include the scatterplot of **sales** against **comtype**, relevant portion of the final regression output table, the final regression equation, and the two residual graphs you obtained in step 8.  Please keep the total length of the report under 8 printed pages (5 to 6 pages should be sufficient in most cases).

Please submit you report as a Word or PDF file.