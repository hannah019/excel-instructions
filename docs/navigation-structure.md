---
layout: default
title: Foumulas and Function
nav_order: 5
---


# Foumulas and Function

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


Functions in Excel are some defined formulas to help users efficiently calculate their values and even analyze the data. A comprehensive function library is included in Excel where people can quickly find many popular ones like sum, average, maximum, minimum and so on. The goal of this section is to explain how to enter formulas and calculate the values of cells by applying existing functions.  


## Introduction of Parts of Functions

In Excel, functions must be written in a specific way for the system to read and operate user’s commands, so a function has to be shown as below. Every single function mainly consists of three parts: equals sign, function name and arguments.

Arguments, not as straightforward as equals sign and function name, might be a bit confused. One or more arguments are required in a function, and the positions of needed values are in the bracket.

![average-function](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image1.png?raw=true)
 For example, this function is to calculate the average from cell A1 to cell A10.

---

## Edit Formulas

Many people prefer to edit their own formulas to calculate the values in their own ways without the help of Excel functions. For example, if we want to multiply both value of A1 and A2 then add the value of A3, we should follow the steps below.

1.Click on the cell where you want to get the value. In this case, we choose B5 for instance. 

![click-cell](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image2.png?raw=true)

2.Type the formula “=A1*A2+A3”. 

![type-formula](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image3.png?raw=true)

3.Press “enter”, then the value of this formula is in B5. Also, the formula will still be presented in the bar in the top right. 

![enter-to-see](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image4.png?raw=true)

Note: 

  -If you are afraid of typing the position of cells wrong, you can easily click on the cells you want to select. 
  
  -Do not forget to type “=” in front of every function for Excel newbies.    

---

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
  
  1.Choose the right cells as your arguments. In this example, we have to choose from B2 to B6. 
  
  ![choose-cells](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image6.png?raw=true)

  2.Click the  on the right of AutoSum and select which specific function you need. In this example, we choose function Max to find the greatest numerical values       in the argument. 
  
![click-autosum](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image7.png?raw=true)
 ![choose-max](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image8.png?raw=true)

  3.The maximum numerical value is automatically shown under the last cell of the argument (B7) which is highlighted in yellow. 
  
  ![maximum-value](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image9.png?raw=true)

  Note:  
    There is no need to enter “=” before using AutoSum because everything has been automatically set up. The only thing the user is required to make sure is the       cells of values in the argument. 
    
  

---

## Insert Function

Beside AutoSum, users are also able to insert Excel functions from the comprehensive library. Let us use IF as a harder example. 

1.Click formulas, and then find “Insert Function” in the very left.  

 ![click-formulas](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image10.png?raw=true)

2.Click OK to choose IF and carefully read the syntax of this function. In other words, make sure you know how to write this function correctly and list all the conditions needed to operate it.    

  ![select-if](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image11.png?raw=true)

3.List all the conditions needed in the blank. 

  ![list-conditions](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image12.png?raw=true)

4.In our example, people can receive a gift in the Chinese New Year if and only if they are younger than 18. Therefore, our Logical_test is B2<18.  

  ![condition-example](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image13.png?raw=true)

5.Choose OK to confirm your syntax. 

  ![click-ok](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image14.png?raw=true)
    ![result-example](https://github.com/hannah019/excel-instructions/blob/gh-pages/assets/images/functions-image15.png?raw=true)

Note:

It is extremely important to study the syntax of the function you want to use. 
  
Now you know how to flexibly apply functions in Excel. The key of this task is to practice more and gradually get familiar with the syntax.  
