- Import SQLite3 library (library is pre-written code)
```Python
import sqlite3
```

- Connect your `.db` file with sqlite3 library with `.connect()` method
- Assign a variable to use this code later
```Python
VarA = sqlite3.connect('YourFileName.db')
```

- Create a cursor variable to run SQL commands
```Python
VarB = VarA.cursor()
```

- Run SQL commands inside `.execute()` method.
```Python
VarB.execute("CREATE TABLE IF NOT EXISTS users (id INTEGER, name TEXT)")
```

- Use `.executescript()` for multi commands
```Python
cursor.executescript("""
    INSERT INTO users (id, name) VALUES (1, 'Alice');
    INSERT INTO users (id, name) VALUES (2, 'Bob');
""")
```






- Basic necessary methods in sqlite3
```Text
.connect() → to connect to a database 
.cursor() → to create a cursor for running SQL commands
.execute() → to execute single line SQL commands
.executescript() → to execute multi line SQL commands
.commit() → to save changes
.close() → to close the database connection
```
