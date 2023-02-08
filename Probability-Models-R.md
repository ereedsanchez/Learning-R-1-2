### This R! exercise will use data from the "Two way Tables" worksheet.

 
##### 1. Who eats breakfast? 
 Students in an urban school were curious about how many children regularly eat breakfast.
 They conducted a survey, asking, “Do you eat breakfast on a regular basis?” 
 All 595 students in the school responded to the survey. The resulting data are shown in the two-way table.
 
 ![Breakfeast](/pics/breakfeast.png)
 
###### The spreadsheet is avaliable here: [Breakfeast Spreadsheet](https://docs.google.com/spreadsheets/d/1U5P_smU_C096gMEMD6o8aTGvJkylD2-HfzRLgivz8ss/edit?usp=sharing)

Suppose we select a student from the school at random. Define event F as getting a female student and event B as getting a student who eats breakfast regularly.

a. Find P(B).

b. Find P(F and B). Interpret this value in context.

c. Find P(F or B).

##### Graphing probabilities in R

Lets take question a. Find P(B)

Steps:
1. Download spreadsheet as CSV file. 
2. Upload CSV file to Replit using R! code
3. import code to R! with the following commands: 

`data <- read.csv("Breakfeast.csv")`

use `print(data)` to view data in R!
