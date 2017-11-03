## Script to create a SQLITE3 database with SQL friendly column names.

## Example Usage
```
create_jira_db jira.sqlite
```

Creates a sqlite database with the column names for all Jira columns
with the table name *jira*.

Requires and validates that you have sqlite3 in your path and you pass
in a database name.
