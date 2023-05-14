# Setup
- Download precompiled binaries for windows here: https://www.sqlite.org/download.html
- Extract to a path like D:\sqlite.
- Add above path to the PATH environment variable.
- Test with the following
```
sqlite3 -version
```
- URL: https://www.sqlitetutorial.net/download-install-sqlite/

# Getting Started
- Enter the sqlite3 prompt with `sqlite3`.
- Common sqlite3 commands:
    - `.quit`: Exits the prompt
    - `.help`: Displays help on commands
    - `.open <database>`: Opens the _database_ database
    - `.databases`: Displays opened databases.
    - `ATTACH DATABASE <database> AS <database_name>`: Attach _database_ and
      alias as *database_name*.
    - `.tables`: Lists all tables
    - `.table '%es'`: Lists tables matching the `'%es'` pattern. 
    - `.schema <table_name or pattern>`: Shows the schema of a table/tables
      matching the pattern.
    - `.fullschema`: Shows schema of entire database.
    - `.indexes`: Shows all indexes in the database.
    - `.indexes TABLE`: Shows indexes for a table.
    - `.output <filename>`: Writes output to _filename_.
    - `.output`: Writes output to stdout.
    - `.read <filename>`: Executes commands in _filename_.
- Download the sample chinook database to play with: https://www.sqlitetutorial.net/wp-content/uploads/2018/03/chinook.zip
- Start prompt and open the chinook database.
  ```
  sqlite3 chinook.db
  ```

# Optimizations
- `REPLACE` instead of `DELETE`-`INSERT`. https://www.sqlitetutorial.net/sqlite-replace-statement/
- `VACUUM`. https://www.sqlitetutorial.net/sqlite-vacuum/
- `AUTOINCREMENT`. https://www.sqlitetutorial.net/sqlite-autoincrement/
- Transaction management. https://www.sqlitetutorial.net/sqlite-transaction/
- `INSTEAD OF` triggers. https://www.sqlitetutorial.net/sqlite-instead-of-triggers/
- Full-text search. https://www.sqlitetutorial.net/sqlite-full-text-search/

# Links
- sqlite tutorial: https://www.sqlitetutorial.net/
- sqlite cheat sheet: https://www.sqlitetutorial.net/sqlite-cheat-sheet/
- sqlite resources: https://www.sqlitetutorial.net/sqlite-resources/