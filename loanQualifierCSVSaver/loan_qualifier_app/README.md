# Project Title

A Command Line Application to match loan applicants with a bank they qualify for a loan at. Gives option to save .csv file in a desired directory on local machine.

---

## Technologies

fire- tool for building CLI's
sys
questionary- tool for making CLI's easier to use with an easy way to ask questions in the terminal/ command prompt
pathlib-standard utility module to standardize how file paths are typed accross operating system.


---

## Installation Guide
in terminal...
pip install fire 
pip install questionary
pip install sys
pip install pathlib


---

## Usage
go to videoDemo directory for full video demo...

'''
#imports from custom script modules from qualifier.utils.fileio import load_csv

from qualifier.utils.calculators import ( calculate_monthly_debt_ratio, calculate_loan_to_value_ratio, ) from qualifier.filters.max_loan_size import filter_max_loan_size from qualifier.filters.credit_score import filter_credit_score from qualifier.filters.debt_to_income import filter_debt_to_income from qualifier.filters.loan_to_value import filter_loan_to_value
'''

^^^^You will need to build functions to iterate through each applicant's desired stat and filter the applicants by their debt to income ratio, credit score, loan size, and loan to home value ratio. to later import each function into the main app.

#Running the CLI video demo in videoDemo directory...

step-by-step:

change directory until you are in the same directory as the main application file 'app.py' in our case.
Once in directory. run the command 'python' followed by the name of the application file. 'python app.py'
The terminal should prompt you (the user) to anwser some questions regarding your financial statistics.
When the questions are complete the program will filter our the loans that you qualify for and organize them in a .csv file.
The program will give you the option 'Yes' or 'No', when asked if youd like to save the .csv file with the banks you were approved for loans at. If you select 'No' then the program will end.
If 'yes' is selected then the user will be given an option to type in a file path to the desired directory the user wants the file to be saved at. If no directory is given the .csv file will be saved in the current working directory.


---

## Contributors

Ethan Rosenberg
Automate Finance
---

## License

None
