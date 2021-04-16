---
layout: default
title: Formulas and Function
nav_order: 5
---


# Formulas and Functions

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


Functions in Excel are some defined formulas to help users efficiently calculate their values and even analyze the data. A comprehensive function library is included in Excel where people can quickly find many popular ones like sum, average, maximum, minimum and so on. The goal of this section is to explain how to enter formulas and calculate the values of cells by applying existing functions.  


## Introduction to Parts of Functions

In Excel, functions must be written in a specific way for the system to read and operate user’s commands, so a function has to be shown as below. Every single function mainly consists of three parts: equals sign, function name and arguments.

Arguments are not as straightforward as equals sign and function name, so they might seem confusing. One or more arguments are required in a function, and the positions of needed values are in the bracket.

![average-function](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image1.png?raw=true)
 For example, this function is to calculate the average from cell A1 to cell A10.

---

## Edit Formulas

Many people prefer to edit their own formulas to calculate the values in their own ways without the help of Excel functions. For example, if we want to multiply both value of A1 and A2 then add the value of A3, we should follow the steps below.

1. Click on the cell where you want to get the value. In this case, we choose B5 for instance. 
    ![click-cell](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image2.png?raw=true)

2. Type the formula “=A1*A2+A3”. 
   ![type-formula](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image3.png?raw=true)

3. Press “enter”, then the value of this formula is in B5. Also, the formula will still be presented in the bar in the top right.
   ![enter-to-see](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image4.png?raw=true)

Note:  
* If you are afraid of typing the position of cells wrong, you can easily click on the cells you want to select. 
* Do not forget to type “=” in front of every function for Excel newbies.    

---

## Arrays

A key purpose of Excel is to work with many values. A group of cells is called an array. This can be a row, a column, or a table (row and column). Some functions that calculate many values, such as SUM(), accept arrays as an input. The array has is identified by its starting cell and ending cell, separated by the colon. Notice that Excel uses letters for columns and numbers for rows.

## Applying your formula to multiple data sets

What if we want to apply the same formula to the same type of data, but there are multiple examples of such data? This is done by hovering over a cell with formula as shown, and dragging across to adjacent cells. This shifts the arguments in the formula to corresponding respective cells in the direction dragged. However, what if you want to shift some arguments but not others? We use the “$” symbol in the cell name. A shortcut is to select the cell and press F4.

## Defined Names

So far, notice that values in a formula are shown with the cell location, that is, its address. However, the address (e.g. B2) does not tell you anything about the meaning of the value. This makes the formula hard to understand for other spreadsheet users at first glance as shown below. 

![unnamed-variables](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/defined-names-1.PNG?raw=true)

1. In this example, the formula tells us we are simply multiplying three values. However, looking at the formula alone, it's not known what the result means.
The solution is to give the cells a name. You can do this by right-clicking on a cell and selecting “Define Name…”. The following dialog box will appear
![defined-names-dialog-box](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/defined-names-2.PNG?raw=true)
2. In the dialog box, enter the desired name for your cell value. When complete, the formula now consists of the name of the values, “Length”, “Width”, and “Height”. From this, another user can quickly deduce that whoever wrote the formula wanted to find the volume of a rectangular prism. As you can see, the formula is much more intuitive and easier to understand, especially in cases where formulas can have 10 or more cells. 
![formula-with-defined-names](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/defined-names-3.PNG?raw=true)
3. This feature also works for arrays as well. Simply drag and select an array of cells, right-click, and select “Define Name…” to name your array.
![formula-with-defined-names](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/defined-names-4.PNG?raw=true)


## Apply Function Library

Instead of manually typing the formulas by ourselves, users can apply redefined functions in the library. Here are the 5 most popular functions in Excel. 

  - SUM: Add all the values of cells in arguments. 
  - AVERAGE: Calculate the sum of values in arguments, then divide the sum by the number of values. 
  - COUNT: Get the number of cells in the arguments. 
  - MAX: Find the maximum value in the whole arguments. 
  - MIN: Find the minimum value in the whole arguments.    
  - AutoSum:

![auto-sum](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image5.png?raw=true)

  AutoSum is most frequently used icon for many Excel users because it contains the most popular functions in Excel. So, how can we use that? 
  
1. Choose the right cells as your arguments. In this example, we have to choose from B2 to B6. 
  ![choose-cells](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image6.png?raw=true)
2. Click the  on the right of AutoSum and select which specific function you need. In this example, we choose function Max to find the greatest numerical values       in the argument. 
![click-autosum](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image7.png?raw=true)
 ![choose-max](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image8.png?raw=true)
3. The maximum numerical value is automatically shown under the last cell of the argument (B7) which is highlighted in yellow. 
  ![maximum-value](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image9.png?raw=true)

  Note:  
    There is no need to enter “=” before using AutoSum because everything has been automatically set up. The only thing the user is required to make sure is the       cells of values in the argument. 
    
  

---

## Insert Function

Beside AutoSum, users are also able to insert Excel functions from the comprehensive library. Let us use IF as a harder example. 

1. Click formulas, and then find “Insert Function” in the very left.  
 ![click-formulas](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image10.png?raw=true)
2. Click OK to choose IF and carefully read the syntax of this function. In other words, make sure you know how to write this function correctly and list all the conditions needed to operate it.    
  ![select-if](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image-11.png?raw=true)
3. List all the conditions needed in the blank. 
  ![list-conditions](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image-12.png?raw=true)
4. In our example, people can receive a gift in the Chinese New Year if and only if they are younger than 18. Therefore, our Logical_test is B2<18.  
  ![condition-example](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image-13.png?raw=true)
5. Choose OK to confirm your syntax. 
 ![result-example](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image-14.png?raw=true)

Note:

It is extremely important to study the syntax of the function you want to use. 
  
Now you know how to flexibly apply functions in Excel. The key of this task is to practice more and gradually get familiar with the syntax.  


If you are having trouble, see [Troubleshooting](https://hannah019.github.io/excel-instructions/docs/index-test/)

