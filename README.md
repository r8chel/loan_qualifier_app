![Python Logo](Images/python.png)

# Loan Qualifier Application

This is a python command-line interface application that allows users to see qualifying loans from lenders quickly and easily. The application works by taking in a `daily_rate_sheet` of loan criteria from various loan providers, asking the user a number of questions to evaluate their loan eligibility, and then returning to them a list of qualifying loans.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
```

---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

Upon launching the loan qualifier application you will be greeted with the following prompts.

```
  Enter a file path to a rate-sheet (.csv):
  What is your credit score?
  What is your current amount of monthly debt?
  What is your total monthly income?
  What is your desired loan amount?
```
You will be shown your monthly debt to income ratio, the loan to value ratio and the number of qualifying loans if any.

You will then be asked if you want to save the information to a new .csv file and what you would like that file to be named.

```
Would you like to save this to a .csv file? (Y/N)
Enter a file name to save (.csv):
```


---

## Contributors

Brought to you by Rachel Bates.

---

## License

MIT
