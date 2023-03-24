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

![Screenshot 2023-03-18 at 2 04 04 PM](https://user-images.githubusercontent.com/111409358/227440931-b74ef9aa-de89-40e2-80a8-5258eebbfdb2.png)

* Part 2 - Analyze Loan Data<br>
Purpose: Analyze the loan to determine the investment evaluation between fair loan price and cost.<br>
How to: On lines 56-61, provide the values for loan price, remaining months, repayment interval and future value.<br>

![Screenshot 2023-03-18 at 1 57 40 PM](https://user-images.githubusercontent.com/111409358/227441087-ee78796f-ecf8-4033-b7eb-62028a9ea58c.png)

* Part 3 - Perform Financial Calculations<br>
Purpose: Calculate the present value of a loan using a function.<br>
How to: On line 102-107, provide the values for loan price, remaining months and future value.<br>

![Screenshot 2023-03-18 at 2 01 27 PM](https://user-images.githubusercontent.com/111409358/227441212-b5f12e31-1188-4c90-abd4-65397547af99.png)

* Part 4 - Conditionally Filter List of Loans<br>
Purpose: Gathering a series of loans and filtering out the inexpensive loans depending on the value and conditional operators.<br>
How to: On lines 137-162, provide the values for loan price, remaining months and future value.  The default number of loans is set to five loans.  On line 169, feel free to adjust the value.<br>

![Screenshot 2023-03-18 at 3 01 50 PM](https://user-images.githubusercontent.com/111409358/227441362-4454aac9-71c7-42c2-9497-e73e0a266458.png)

* Part 5 - Save the results<br>
Purpose: From Part 4, the results are written to a .cvs file. Please see below for a sample output.<br>

![Screenshot 2023-03-18 at 3 03 05 PM](https://user-images.githubusercontent.com/111409358/227441455-b813b18e-4ded-4596-adea-c27fee841ac7.png)

* Running the program
Launch an IDE program. In this I'm using Visaul Studio Code.<br>
In terminal or the command line, change to a dev environment by typing, conda activate dev.<br>
To run the program, type, python loan_analyzer.py

Sample Output
![Screenshot 2023-03-18 at 6 27 34 PM](https://user-images.githubusercontent.com/111409358/227441535-736daf32-773c-41c5-9643-a7dc2a399a0a.png)

---
## Contributors
Alexander Valenzuela<br>
[LinkedIn Profile](<https://www.linkedin.com/in/alex-valenzuela-97826842/>)

---
## License
The Unlicense

