![IronHack Logo](shark-attack.jpg)

# Project: "Shark attacks" Data Cleaning and Manipulation with Pandas.

## Overview

The goal of the project is wrangling, cleaning, and manipulation a Shark attack dataset with Pandas. If you will follow the project download the dataset from [Shark Attack](https://www.kaggle.com/teajay/global-shark-attacks/version/1). 
at the end we will export it as a clean CSV data file.

## Technical Requirements

* The dataset shark-attacks.
* Pandas library.
* A Jupyter Notebook ** shark-attack-data-cleaning.ipyng ** with code.
* A clean shark_attack_clean_dataset.csv file.

## Development procedure

* 1- Import libraries we'll use ``Pandas``, ``Numpy``, ``digists`` and ``DateTime``.
* 2- Import shark-attack dataset into a pandas dataframe.
* 3- Analize data with pandas methods like **info(), head() and datacolums**.
* 4- Develop functions to treat data as follow:
    * 1 ``clean_headers()`` - Clean white spaces in headers.
    * 2 ``select_useful_columns_1()`` - Chosing relevants columns from main data.
    * 3 ``rename_columns()`` - Change some titles names to best undertanding.
    * 4 ``remove_empty_rows()`` - Delete empty rows from data.
    * 5 ``get_date()`` - Extract date from field with date in.
    * 6 ``nulls_treatment()`` - null's treatment.
    * 7 ``categorized_type()`` - categorize type of shark attak.
    * 8 ``to_numeric()`` - return just numeric values in string.
    * 9 ``get_numeric()`` - get numeric values from data.
    * 10 ``replace_specific_value()`` - replace specific_values from column.
    * 11 ``select_useful_columns_2()`` - Select final columns.
    * 12 ``re_order_columns()`` - to arrange columns appropriately.
* 5-**Main Pipeline** transform data from a function to another.
* 6-Export final dataframe to a **shark-attack.csv** file.

## Useful Resources

* [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
* [Pandas Tutorials](https://pandas.pydata.org/pandas-docs/stable/tutorials.html)
* [StackOverflow Pandas Questions](https://stackoverflow.com/questions/tagged/pandas)
* [Awesome Public Data Sets](https://github.com/awesomedata/awesome-public-datasets)
* [Kaggle Data Sets](https://www.kaggle.com/datasets)
