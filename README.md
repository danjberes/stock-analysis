# stock-analysis

## Overview of Project
The purpose of this code is to automate the process of analyzing a year return for particular stocks. Previously, the code was created with a nested loop that worked well for the small sample size of stocks we were analyzing. However, if we were to expand the number of stocks we were analyzing, the amount of time it would take to run through the code would increase significantly. Refactoring the code from the module is more efficient due to the removal of a nested for loop statement. 

## Results
The [2017 results](https://github.com/danjberes/stock-analysis/blob/master/Resources/VBA_Challenge_2017.png) yielded much higher returns on most stocks when compared to the [2018 results](https://github.com/danjberes/stock-analysis/blob/master/Resources/VBA_Challenge_2018.png). The execution times as shown in the linked images were from the refactored code, which ran in less than one third of the time of the original nested for loop code. 

## Summary
The advantages of refactoring code is that code may become more clean and have unnecessary code removed from it, as well as running more optimally. Disadvantages to refactoring code may be the time taken to refactor the code that could have been used working on different projects or it could be faster to rewrite some code entirely. Partially refactored code may introduce more bugs into increasingly more complex code, however that is unlikely in simple scripts such as the one used in this project.

The refactored script in this project ran much faster than the previously written VBA script. The cons were apparent in the deadline that was not able to be achieved due to other projects taking higher priority.
