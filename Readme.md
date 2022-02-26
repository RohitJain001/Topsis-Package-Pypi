Check out Live: https://pypi.org/project/Topsis-Rohit-101903706/
# TOPSIS PACKAGE
## BY ROHIT JAIN

### Instalation of the package:
Install the package using the commnd `pip install Topsis-Rohit-101903706`

### Import the package:
After creating python file with any name, here `mypackage.py` where you need to use topsis package, Use folowing commands to import te package:
1. `varName = __import__('topsis')`
Here you can use any variable name to store te package
2. Call the package with command `varName.topsis()`
Now Save your python file.

### Get Results
Make sure you have your input file in the same directory with python file `mypackage.py`

Using comand line, use the package as:
`python myPackage.py inputData.csv weights Impats outputFile.csv`

Here weights is the string with weights of each column in inputData. e.g., `"1,2,3,4"` for input with 4 features.

Impacts is the string represting impact on each feature with '+' sign representing maximum and '-' sign representing minimum
e.g., "`+,-,-,-"` for input with 4 features

outputFileName.csv should have the name of the file you want to create eith output data stored.


#### Happy Coding! 

## Common Mistakes:
1. inputData.csv file not in same directory as myPackage.py file.
2. While running Command, your input arguments are less than 4. Make sure to have all 4 arguments consiting inputData.csv weights impacts outputFile.csv respectively.
3. Weigts or impacts are not a string
4. inputData comtains empty cells
5. Columns in input less than 3


For any doubts mail me at rjain1_be19@thapar.edu . I will be happy to help.
