- Import SQLite3 library (library is pre-written code)
```Python
import sqlite3
```

- Connect your `.db` file with sqlite3 library with `.connect()` method
- Assign a variable to use this code later
```Python
VariableName = sqlite3.connect('YourFileName.db')
```

- Basic necessary methods in sqlite3
```Text
.connect() → to connect to a database 
.cursor() → to create a cursor for running SQL commands
.commit() → to save changes
.close() → to close the database connection
```
