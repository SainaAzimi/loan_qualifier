# **Loan Qualifier Application**
This is a python command_line interface application that allows users to see qualifying loans from lenders based on their inputs. The application works by taking the criteria from the data provided in `daily_rate_sheet.csv` that includes information about various loan providers, then the command_line interface provides a streamlined way to interact with the user and get the user to input their personal relevant information in realtime, and returning a set of available loans with an option to save those loans on a different path which in this case is a csv file called `qualifing_loans.csv`.

---

## Technologies
This project utalizes python 3.7 with the following packages:

[import csv](https://github.com/Alexmhack/py_handles_csv) - For importing a csv file that will display the specific loans the user qualifies for.

[pathlib](https://github.com/python/cpython/blob/main/Lib/pathlib.py) - For loading and saving files from and to specific paths.

[fire](https://github.com/google/python-fire) - For the command line interface, help page, and entry-point.

[questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs. 



---

## Installation Guide
Before running the application first install the following:
```
- pip install csv  

- pip install pathlib 

- pip install fire  

- pip install questionary 
```

---

## Usage
To use the `app.py` application simply clone the repository and run `python app.py`. 

![loan qualifier application screenshot](https://github.com/SainaAzimi/loan_qualifier_application/blob/main/screenshot.png)


---

## Contributors

*Contributors*: Saina Azimi

*Email*: azimi.sainaa@gmail.com

*LinkedIn*: https://www.linkedin.com/in/azimi-saina/ 

---

## License
UC Berkeley

---
