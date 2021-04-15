---
layout: default
title: Data Analysis
nav_order: 6
---

# Data Analysis
{: .no_toc }


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
Microsoft Excel has become one of the most widely used software in all the industries. And data analysis is one of the most important functionalities in Excel which includes sorting, conditional formatting, charts and so on.

## Sorting

### Sort Sheet or sort range

Sort sheet means when we sort a category of values according to a specific pattern, all other correlated values will be moved because of it.

![sort-by-number](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image1.png?raw=true)
![sort-by-name](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image2.png?raw=true)

In the original worksheet, all the information was sorted by the “Homeroom” column. However, if we sort the whole sheet again alphabetically by the “Last Name” of people, then not only the order of “Last Name” did change, but information in other columns which is related to this name also moves. 

Sort range means we only sort a part of the cells in a sheet, and it will be convenient when there are a few different tables in the same worksheet. 

![before-sorting](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image3.png?raw=true)
![after-sorting](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image4.png?raw=true)

There are more than 1 table in the sheet, so we only want to sort the “Total Orders (by Grade)” on the right. Then after sorting range alphabetically by “Class”, all the cells of “Payment Method” on the left will never be affected. 

## Instructions
### Sort Sheet

Goal: Sort the whole sheet alphabetically by “Last Name”.

1.Select any cells in the “Last Name” column. For instance, we choose C2 this time.

![select-cells](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image5.png?raw=true)

2.Find “Data” on the top of the menu, and click the “A-Z” command to rank names from initial A to initial Z. 

![click-data-sort](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image6.png?raw=true)
 
3.The result has been presented below. 

![result](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image7.png?raw=true)

### Sort range

Goal: Sort the number of “Orders” increasingly only in table “Total orders (by Grade)”.

1.Select all the values in “Class” and “Orders” columns. 

![select-class-orders](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image8.png?raw=true)

2.Find “Data” on the top of the menu, and click the “sort” command. 

![click-data-sort](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image9.png?raw=true)

3.Click the ![small-arrow](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image10.png?raw=true) in “sort by” category and choose “Orders”. 

![choose-orders](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image11.png?raw=true)

4.Choose “Cell values” and “Smallest to Largest” separately. 

![choose-operations](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image12.png?raw=true)

5.Confirm all your operations by clicking OK to see the result below. 

![click-ok](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image13.png?raw=true)

![result](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image14.png?raw=true)

### Conditional Formatting

Conditional formatting is a functionality which allows users to format cells which meet some specific criteria. Conditional formatting enables users to do the following things. It is able to work as a reminder by asking people to pay attention to some important data. In addition, it can make some big data more visible so that these complicated values can be understood more easily. In this example, we are going to apply conditional formatting rules, so that the percentage of anyone which is greater than 100% is shown in green. 

1.Select all the values in the “Percentage” column.

![click-percentage](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image15.png?raw=true)

2.Click “Home” and find “Conditional formatting”. Then Choose the first “Highlight Cell Rules” -> “Greater Than”.  

![conditional-formatting](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image16.png?raw=true)

3.Enter “100%” into the blanck in the left under the text “Format cells that are GREATER THAN”. 

![enter-100%](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image17.png?raw=true)

4.Click  in the right blanck after text “with” and find “Green Fill with Dark Green Text”.   

![Green-Fill-with-Dark-Green-Text](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image18.png?raw=true)

5.Confirm all the choices by clicking the “OK”, and the final result is shown in below.

![click-ok](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image19.png?raw=true)
![result](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/data-analysis-image20.png?raw=true)

Now, you know some basic knowledge about how to analyze data by using Excel. However, the functionalities of sorting and conditional formatting are not limited to the content mentioned above. We can still explore them by ourselves to analyze the data in a more personalized way.  

### Charts and Graphs

Excel has many types and styles of graphs and charts to analyze your data. For instructional purposes, we will demonstrate with inserting a scatter plot graph on your spreadsheet. The concept is similar for other types of graphs and charts.

Here we have some data for the position in meters of a ball thrown up vertically in the air as time goes by. We have three data columns in this case: Time, Position-exp (expected), and Position-equation. We have two sets of data: Time and Position-exp, and Time and Position-equation. We want to display both on the same scatter plot.

![chart-data](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-1.PNG?raw=true)

To access graphs and charts, select the insert tab and select the desired chart icon as shown. 
A blank box will appear on your spreadsheet. This is because there is no data in it.

![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-2.PNG?raw=true)

The next step is to tell Excel where our data is located in the spreadsheet. Right-click the blank box and select “Select Data…”. A dialog box will appear as shown. 


![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-3.PNG?raw=true)

Under Legend Entries (Series), select “Add” to add your data sets. Our first data set is Time and Position-exp. 
This will trigger another dialog box.

![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-4.PNG?raw=true)

With the typing cursor over “Series X values”, drag and select the desired values for the x-axis as shown. Do the same for the Y values (Position-exp), but remove “{1}” which appears by default. Then, give your data set a name and press “OK” to finish. We now have our first set of data.

![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-6.PNG?raw=true)
![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-7.PNG?raw=true)

Repeat the same process with the second data set, Time and Position-equation. When finished, it may look like this.

![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/chart-demo-8.PNG?raw=true)

Excel gives you many options to format your chart. Click on the x-axis, y-axis, or data points themselves and right-click to adjust and format. You can change colours, adjust size, adjust positioning, add Trendlines (line of best fit), add labels, etc.

If you are having trouble, see [Troubleshooting](https://hannah019.github.io/excel-instructions/docs/index-test/)
