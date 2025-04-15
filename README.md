# YBLL 2.0 Advanced Masterclass #3: Python Pandas (2025 edition)

A hands-on workshop focused on applying pandas fundamentals to analyze Olympic Games dataset

> [!WARNING]  
> Make sure you are using **Python 3.11**. Check your version using this command: `python --version`.

## Learning Objectives

Students will practice:

- Loading and exploring dataframes
- Data manipulation and analysis using pandas
- Answering real-world analytical questions

## Setting up

Clone the remote Github repository into your local project folder:

```bash
$ cd ./ybll_workshops/
$ git clone git@github.com:maronavenue/ybll-workshop-2-python-pandas.git
$ cd ybll-workshop-2-python-pandas.git/
```

Make sure we are in a virtual environment so we don't impact system-wide Python dependencies:

### Linux

```bash
$ python -m venv venv
$ source venv/bin/activate
```

### Windows

```windows
$ python -m venv venv
$ venv\Scripts\activate
```

### Install dependencies

```bash
$ pip install -r requirements.txt
```

### Install dependencies manually

In case it did not work, you can install the dependencies manually:

```bash
$ pip install pandas
$ pip install jupyter
$ pip install pyarrow
$ pip install openpyxl
```

And then you can compare your dependencies against `./requirements.txt` by running `pip freeze`.