- Import SQLite3 library (library is pre-written code).
```Python
import sqlite3
```

- Connect your `.db` file with sqlite3 library with `.connect()` method.
- Assign a variable to use this code later.
- If the database with the given name don't exists then it'll create one.
```Python
# use 'conn' instead of 'VarA' in real life scenario

VarA = sqlite3.connect('YourFileName.db')
```

- Create a cursor variable to run SQL commands.
```Python
# use 'curr' instead of 'VarB' in real life scenario

VarB = VarA.cursor()
```

- Run SQL commands inside `.execute()` method.
- Use `CREATE TABLE IF NOT EXISTS`  instead of `CREATE TABLE` to avoid errors.
```Python
VarB.execute("CREATE TABLE IF NOT EXISTS users (id INTEGER, name TEXT)")
```

- Use `.executescript()` for multi commands.
- Use `INSERT OR IGNORE INTO`  instead of `INSERT INTO` to avoid errors.
```Python
VarB.executescript("""
    INSERT OR IGNORE INTO users (id, name) VALUES (1, 'Alice');
    INSERT OR IGNORE INTO users (id, name) VALUES (2, 'Bob');
""")
```

- Fetch data from `cursor.execute()` and show in tuple list.
- `fetchone()` – gets **one row** from the result.
- `fetchall()` – gets **all rows** as a list of tuples.
- `fetchmany(n)` – gets **`n` rows** as a list of tuples.




- Save changes in database after editing.
```Python
VarA.commit()
```

- Close the connection
```Python
VarA.close()
```

- Write the whole code inside `With....` to `.commit()` and `.close()` automatically.
```Python
with sqlite3.connect('YourFileName.db') as VarA:
	# write your whole code here
```

- Basic necessary methods in sqlite3
```Text
.connect()       → Connect to a database 
.cursor()        → Create a cursor for running SQL commands
.execute()       → Execute a single SQL command
.executescript() → Execute multiple SQL commands at once
.commit()        → Save changes
.close()         → Close the database connection
```
