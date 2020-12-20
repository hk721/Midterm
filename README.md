# Pandas is a data anylasis and manipulation tool that is built on top of the python language. It is a fast and easy to use open source tool, having endless possiblties of use. This tools main use being data analysis, it allows for importanting data from many file formats, amongst the all the popular ones being SQL and Microsoft Excel.Another feature of pandas being manipulation, it offeres operations such as merging, reshaping, and data cleaning. Pandas is a fast and extremly powerful tool that is used by many.
# The installtion of Pandas is very simple, it can be installed at https://pandas.pydata.org/. In order to implement it in the code, you must import the tool, in which the way I did it was, "import pandas as pd".

import pandas as pd

series1 = pd.Series(['Manchester United', 'Real Madrid', 'Barcelona', 'Olympiacos'])

print(" First Series:")

print(series1)

solution = series1.map(lambda x: len(x))

print("\nNumber of letters in each word in the list:")

print(solution)

# The code seen above is a basic use of Python with pandas. It allows for the words in the series, to output the number of letter in each of the words that are present. This specfic use of Pandas can be used for anyone looking to count the number of letters, and to check errors. For instance if they know a list is all the same thing and has 5 letter words, when this is run it can provide a checking system to see if any word is too long or too short.

# A future idea I can use this tool for can be to make a grading system. By importing data I can create a grading system and provide the students with there grades currently, and calculate what is needed on future assignments in order to attain a passing grade or a grade of there choice.
