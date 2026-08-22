
#### Import Pandas library
```python
import pandas as pd

# here 'pd' can be set for a shortcut use and you can give anything you want
```

#### Series vs DataFrame
- `1 column`  data is a series. `Multi Column` data is DataFrame
- `list` can be converted as `series`. (because it has a single column of data)
- `Dictionary` can be converted as `DataFrame`.
```text
Series (1 column)            Dataframe (Table)
     Name                         Name    Age    City   
0    Alice                   0    Alice    25    New York
1    Bob                     1    Bob      30    London
2    Charlie                 2    Charlie  35    Paris
```

- to convert a list to series we use --> `pd.Series()`
- to convert a dictionary we use --> `pd.DataFrame()`
```python
import pandas as pd

# list converted to Series

numbers = [1, 2, 3, 4, 5]
numbers_series = pd.Series(numbers)
print(numbers_series)

# Dictionary converted to Dataframe

students = {
		"Name" : ["Alice", "Bob", "Charlie"],
		"Age" : [25, 30, 35]
}
students_dataframe = pd.DataFrame(students)
print(students_dataframe)
```

#### Custom index
- use `index = [a, b, c]`  inside `Series` and `DataFrame` method for custom index.
```python
# Custom indexing

df = [1, 2, 3, 4, 5]         # df means dataframe (commonly used)
new_df = pd.Series(numbers, index = ["a", "b", "c", "d", "e"])
print(new_df)
```

#### Load CSV files
- use `pd.read_csv()` to import csv files
```python
variable_name = pd.read_csv("csv path here")
```

#### Select rows & columns
```python
students = {
		"Name" : ["Alice", "Bob", "Charlie"],
		"Age" : [25, 30, 35]
}


```
#### Show Data
```python
df.head()      # show first 5 rows default (mention how many rows inside brackets)
df.tail()      # show last 5 rows (mention how many rows inside brackets)
df.sample()    # show random rows (mention how many rows inside brackets)
df.info()      # show number of rows, columns, data type and more
df.describe()  # show quick (mean, min, max)
df.shape()     # show number of rows and columns
```

#### Handle missing data
- use `.isnull()` to find how many missing data in a column/ table