
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

numbers = [1, 2, 3, 4, 5]
numbers_series = pd.Series(numbers, index = ["a", "b", "c", "d", "e"])
print(numbers_series)
```

#### Load CSV files
- use `pd.read_csv()` to import csv files
```python
variable_name = pd.read_csv("csv path here")
```

