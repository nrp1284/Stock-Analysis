## Client: Steve
#Project Manager:Nayan Patel

## Deliverable 2: Written Analysis

#Overview of Project:

Steve wants to find the total daily volume and yearly return for each stock to measures how actively a stocks are trade to see yearly return is the percentage difference in price from the beginning of the year to the end of the year. Steve's parents are starting to pester him about some selected stocks(EX:DQ) and he wants to analyze the entire data set of year 2017 and 2018 to see how well the ROI is for individual tickers.

**DQ Analysis for Year 2017:**

All Stocks performed well except "TERP" and If we see the result of the stock that Steve's parents considering(DQ) has out perform all the tickers and has an ROI of 199.4%.

DQ Analysis: +ve 199.4% 

DQ Analysis: -ve 62.6% 

# Image DQ Analysis

![DQ Analysis](
    VBA_Challenge_2017-DQ.png)





# Image: Stock Anaysis 2017


![Stock Analysis 2017](
    VBA_Challenge_2017-Refactored.png)


**DQ Analysis for Year 2018:**

All Stocks under performed  except "ENPH" amd "RUN" and If we see the result of the stock that Steve's parents considering(DQ) has negative ROI of 62.6% for year 2018

# Image: Stock Anaysis 2018

![Stock Analysis 2018](
    VBA_Challenge_2018-Refactored.png)


## Results Comaprig Stock performance 2017 v/s 2018

# Results Year 2017

Average Return: 67.3%

Max Return:199.4% ("DQ" Out Performed)

Min Return: -7.2% for "TERP" 


# Results Year 2018

Average Return: -8.5%

Max Return: 84% ("RUN" Out Performed)

Min Return: -62.6%("DQ" was worst performer for Year 2018)

_ve return on Investment was -7.2% for "TERP" Only

# Image showing execution times of the original script run time.

![Stock Analysis not Refactores](
    VBA_Challenge_2017-NotRefactored.png)


Over All 2017 results were best for ROI for All stocks Analysis


# Summary:

## 1) Advantages and Disadvantages of Refactored code:

 Code Refactoring makes the code more extensible for adding many other function to it. It also helps in increasing the flexibility of the code and by this the capability of code increases.
 
 ## Advantages:
 Refactoring makesthe code a fresher, easier to understand or read, less complex and easier to maintain. 
 Refactoring is a wise method of extending the code and making it more capable
 Refactoring may include improved code readability and reduced complexity; these can improve the source code's maintainability and create a simpler, cleaner, or more expressive internal architecture or object model to improve extensibility.
 Refactoring is usually motivated by noticing a code smell.For example, the method at hand may be very long, or it may be a near duplicate of another nearby method. Once recognized, such problems can be addressed by refactoring the source code, or transforming it into a new form that behaves the same as before but that no longer "smells".
 There are two general categories of benefits to the activity of refactoring.

 
 ## Disadvantage:
 Time Consuming: You may have no idea how much time it may take to complete the process. It may also land you into a situation where you have no idea where to go.
 In case if it went wrong, you will have to waste much more time in solving the problem and there are probable chances that it may go wrong due to complexity of the code.

## 2) How do these pros and cons apply to refactoring the original VBA script?

#Pros:

1. Programmers who have worked on the project or who have access to the back-end don’t need permission for refactoring as it won’t affect the external behaviors
2. Refactoring almost always improves the code, speeding up the performance of the code
3. Unlike rewriting, refactoring can be done in tandem with the development of a project
4. Developers can target a section of the codebase, so they don’t need to do a lot to improve small portions of a code

#Cons:
1. Refactoring only maintains the architectural code, so new functionalities can’t be added during refactoring
2. Skill and discipline are required when refactoring, so unskilled programmers should not venture into refactoring, especially without a test suite, or they risk breaking the code
3. Sometimes refactoring changes complex functions into simple ones, making it harder to manage and unit test
