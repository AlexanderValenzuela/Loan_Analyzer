# *Loan Analyzer* 
**Python program that automates specific tasks associated with valuing microlending loans.**

---
## Technologies
This project leverages python 3.7 with the following libraries:
* csv - For writing rows of data to a .csv file.
* pathlib - For setting a path for a .csv file.
---
## Installation 
Install an Integrated Developer Environment such as Visual Studio Code or PyCharm.  

---
## Usage
Below are automated tasks for specific calculations with valuing microlending loans.  

* Part 1 - Automate the Calculations<br>
Purpose: Automate the calculations for the loan portfolio summaries to obtain average loan price.
How to: On line 14, provide the various loan prices.  The default is set to five loan prices.<br>

![Alt text](screen%20shots/Screenshot%202023-03-18%20at%202.04.04%20PM.png)

* Part 2 - Analyze Loan Data<br>
Purpose: Analyze the loan to determine the investment evaluation between fair loan price and cost.<br>
How to: On lines 56-61, provide the values for loan price, remaining months, repayment interval and future value.<br>

![Alt text](screen%20shots/Screenshot%202023-03-18%20at%201.57.40%20PM.png)

* Part 3 - Perform Financial Calculations<br>
Purpose: Calculate the present value of a loan using a function.<br>
How to: On line 102-107, provide the values for loan price, remaining months and future value.<br>

![Alt text](screen%20shots/Screenshot%202023-03-18%20at%202.01.27%20PM.png)

* Part 4 - Conditionally Filter List of Loans<br>
Purpose: Gathering a series of loans and filtering out the inexpensive loans depending on the value and conditional operators.<br>
How to: On lines 137-162, provide the values for loan price, remaining months and future value.  The default number of loans is set to five loans.  On line 169, feel free to adjust the value.<br>

![Alt text](screen%20shots/Screenshot%202023-03-18%20at%203.01.50%20PM.png)

* Part 5 - Save the results<br>
Purpose: From Part 4, the results are written to a .cvs file. Please see below for a sample output.<br>

![Alt text](screen%20shots/Screenshot%202023-03-18%20at%203.03.05%20PM.png)

* Running the program
Launch an IDE program. In this I'm using Visaul Studio Code.<br>
In terminal or the command line, change to a dev environment by typing, conda activate dev.<br>
To run the program, type, python loan_analyzer.py

Sample Output
![Alt text](screen%20shots/Screenshot%202023-03-18%20at%206.27.34%20PM.png)
---
## Contributors
Alexander Valenzuela<br>
[LinkedIn Profile](<https://www.linkedin.com/in/alex-valenzuela-97826842/>)

---
## License
The Unlicense

