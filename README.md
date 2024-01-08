# python_data_wrangling_roman_emperors
#### A repository to exercise data wrangling in Python working with a Wikipedia list of Roman Emperors.

The goal of this project is to laod a list of the Roman Emperors from Wikipedia and to wrangle and clean the list in Python.
The data used comes from the Wikipedia page: <https://en.wikipedia.org/wiki/List_of_Roman_emperors>.

--------------------------------------

#### The repository contains five files:

**1. list_roman_emperors_2023_wikipedia.htm**

The file contains data from the Wikipedia page >https://en.wikipedia.org/wiki/List_of_Roman_emperors>.

**2. get_emperor_list_from_wikipedia.ipynb**

The Jupyter Notebook takes the data from 'list_roman_emperors_2023_wikipedia.htm', creates a Python Pandas dataframe and saves the dataframe to the csv file 'data_roman_emperors.csv'.

**3. data_roman_emperors.csv**

The file is the output of the Jupyter Notebook 'get_emperor_list_from_wikipedia.ipynb'.

**4. wrangle_emperor_list.ipynb**

The Jupyter Notebook loads the data from 'data_roman_emperors.csv', cleans the data, and saves the data to the file 'data_roman_emperors_cleaned.csv'.

**5. data_roman_emperors_cleaned.csv**

The file is the output of 'wrangle_emperor_list.ipynb' and the end result of the project. It contains the cleaned list of the Roman Emperor data from Wikipedia.
