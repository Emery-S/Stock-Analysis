# Stock-Analysis
## Project Overview
### The purpose of this project was to refractor a piece of VBA code originally built to organize the data of several green companies to determine investment potential. Refactoring the code was neccessary to increase its efficiency. Now, should someone wish, it is possible to apply the code to a more extensive data set and get a better understaning of a wider range of stocks. 

## Results
###  I believe it has to do with the utilization of the arrays which are able to encompass a larger grouping of data and allow for fewer iterations. I also believe assigning variables to the tickers before it interacts with the data set makes the compilation of data faster as it already knows what it is looking for, no excess sorting. (To be frank, I am unsure as to the results and how I actually got there).
# Smmary
## Advantages and Disadvantages of Code Refactoring 
### It can definitely be beneficial to refactor especially if you have code that can only run small scale operations, but has potential for larger analysis. It is a bit like the adadge "two heads are better than one", taking ones bit of code and repurposing the principle of it for another puprose can make ones work a lot simpler and more efficient. Of course there is always a concern that a code, written a certain way, cannot be refactored the way one thought. This can cause a bit of a headache with more complicated codes, always best to save code before attempting.

## Advantages and Disadvantages of Refactoring the Code in This Project
### As seen through both images, the newly refactored code is 0.21875 seconds faster than the original. In the grand scheme of things this seems to be insignificant, but for the purpose of running hundreds of different data pieces it is invaluable time that will prevent lags or worse a system crash. It also means you can have many more data sets without running into any issue and get a much deeper understanding of each companies stocks over different years. One disadvantage is that one can only analyze 12 companies at a time and would have to rewrite the code according to which ones you were analysing as it will not sort the tickers. VBA is also very reliant on syntax which can make it difficult to rewrite and modify what has already been written.
<img width="854" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/112206035/197100284-da7367ac-d210-442e-b2b1-785718db7cdf.png">
<img width="853" alt="VBA_Challenge_2018 (Refactored)" src="https://user-images.githubusercontent.com/112206035/197100286-e25568e8-e25d-443e-99d4-24f6a9722066.png">
