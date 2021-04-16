---
layout: default
title: Data Analysis
nav_order: 6
---

# Data Analysis
{: .no_toc }

Data analysis is a primary function in Excel. In this section, we will show you how to make meaning and find patterns out of the raw data you have. We will show you how to sort, perform conditional formatting, and set up graphs and charts in your Excel spreadsheet.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## About Sorting: Sort sheet versus Sort range

To demonstrate sorting, we will use a table of data for students who bought T-shirts. There are two ways to sort your data. Sort sheet means when we sort a category of values according to a specific pattern, all other correlated values will be moved because of it. Excel can recognize the data and pattern around a given cell.

![sort-by-number](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image1.png?raw=true)
![sort-by-name](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image2.png?raw=true)

In the original worksheet, all the information was sorted by the “Homeroom” column. However, if we sort the whole sheet again alphabetically by the “Last Name” of people, then not only the order of “Last Name” did change, but information in other columns which is related to this name also moves. That is, Excel recognizes and treats each row of data as an entry and each entry will move up or down the table as it is sorted.

Sort range means we only sort a part of the cells in a sheet, and it will be convenient when there are multiple different tables in the same worksheet. That is, Excel will **only** sort the data that you selected. Unlike Sort sheet, Excel will not automatically recognize surrounding cells to include in the sort.

![before-sorting](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image3.png?raw=true)
![after-sorting](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image4.png?raw=true)

In our case, there are more than one table in our demonstration sheet. We want to only sort the “Total Orders (by Grade)” table on the right. After sorting range alphabetically by “Class”, you will notice that all the cells in the columns from "Homeroom" to “Payment Method” on the left were unaffected. 

## Instructions
### Sort sheet

Goal: Sort the whole sheet alphabetically by “Last Name”.

1. Select any cell in the “Last Name” column. For instance, we will choose cell C2 this time.
 ![select-cells](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image5.png?raw=true)
2. Find the “Data” tab on the top of the menu and click the “A-Z” command as shown to rank last names that start with A to those that start with Z. 
 ![click-data-sort](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image6.png?raw=true)
3. The result has been presented below in column C.
 ![result](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image7.png?raw=true)

### Sort range

Goal: Sort the number of “Orders” in increasing value only in the table, “Total orders (by Grade)”.

1. Select all the values in “Class” and “Orders” columns. 
 ![select-class-orders](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image8.png?raw=true)
2. Find “Data” on the top of the menu, and click the “sort” command. 
 ![click-data-sort](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image9.png?raw=true)
3. Click the ![small-arrow](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image10.png?raw=true) in “sort by” category and choose “Orders”. 
 ![choose-orders](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image11.png?raw=true)
4. Choose “Cell values” and “Smallest to Largest” separately. 
 ![choose-operations](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image12.png?raw=true)
5. Confirm all your operations by clicking OK to see the result below. 
 ![click-ok](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image13.png?raw=true)
 ![result](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image14.png?raw=true)


<img src="https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/notice-advice-logo.png" width="50" height="50" />
Remember to save your work often, especially if you might want your data to go back to an unsorted state. Also, be mindful of any of your formulas that use values in the table that is being sorted since data has moved to different cells. Normally, Excel will compensate for this so that your formulas still output the same values before sorting.

### Conditional Formatting

Conditional formatting is a functionality which allows users to format cells according to some specific criteria. It can draw attention to important trends in the data. It can also make the data more immediately clear and understandable, since varying shades of colours are more readable than texts of numbers. In this example, we are going to apply conditional formatting rules, so that the percentage of anyone which is greater than 100% is shown in green. 

1. Select all the values in the “Percentage” column.
 ![click-percentage](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image15.png?raw=true)
2. Click “Home” and find “Conditional formatting”. Then Choose the first “Highlight Cell Rules” -> “Greater Than”.  
 ![conditional-formatting](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image16.png?raw=true)
3. Enter “100%” into the blanck in the left under the text “Format cells that are GREATER THAN”. 
 ![enter-100%](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image17.png?raw=true)
4. Click  in the right blanck after text “with” and find “Green Fill with Dark Green Text”.   
 ![Green-Fill-with-Dark-Green-Text](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image18.png?raw=true)
5. Confirm all the choices by clicking the “OK”, and the final result is shown in below.
 ![click-ok](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image19.png?raw=true)
 ![result](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image20.png?raw=true)
 Observe that all the entries where Percentage is over 100% is more immediately clear when it is green, than when without formatting the reader will need to read each and every number one by one.
 
<img src="https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/notice-advice-logo.png" width="50" height="50" />
You can clear conditional formatting (and any other kind of formatting) by clicking on the eraser symbol (a white and purple rectangle) in the Editing section under the Home tab.

### Charts and Graphs

Excel has many types and styles of graphs and charts to analyze your data. For instructional purposes, we will demonstrate with inserting a scatter plot graph on your spreadsheet. The concept is similar for inserting other types of graphs and charts onto your spreadsheet.

Here we have some data for the position in meters of a ball thrown up vertically in the air as time goes by. We have three data columns in this case: Time, Position-exp (expected), and Position-equation. We have two sets of data: Time and Position-exp, and Time and Position-equation. We want to display both on the same scatter plot.

![chart-data](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-1.PNG?raw=true)

1. To access graphs and charts, select the insert tab and select the desired chart icon as shown. 
 A blank box will appear on your spreadsheet. This is because there is no data in it.
 ![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-2.PNG?raw=true)

2. The next step is to tell Excel where our data is located in the spreadsheet. Right-click the blank box and select “Select Data…”. A dialog box will appear as shown. 
![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-3.PNG?raw=true)

3. Under Legend Entries (Series), select “Add” to add your data sets. Our first data set is Time and Position-exp. 
 This will trigger another dialog box.
 ![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-4.PNG?raw=true)

4. With the typing cursor over “Series X values”, drag and select the desired values for the x-axis as shown. Do the same for the Y values (Position-exp), but remove “{1}” which appears by default. Then, give your data set a name and press “OK” to finish. We now have our first set of data.
 ![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-6.PNG?raw=true)
 ![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-7.PNG?raw=true)

5. Repeat the same process with the second data set, Time and Position-equation. When finished, it may look like this.
 ![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-8.PNG?raw=true)

Excel gives you many options to format your chart. Click on the x-axis, y-axis, or data points themselves and right-click to adjust and format. You can change colours, adjust size, adjust positioning, add Trendlines (line of best fit), add labels, etc.

Now, you have some basic knowledge about how to analyze data with Excel. However, the functionalities of sorting and conditional formatting are not limited to the content mentioned above. There are many ways to sort data and many different conditions that conditional formatting can go by. 

If you are having trouble, see [Troubleshooting](https://hannah019.github.io/excel-instructions/docs/index-test/)
