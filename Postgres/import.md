# Importing your PostgreSQL database

### Warning: 
<div>
	Before you can import a postgres database, you need to create a database to import data into.
	<br>
	<br>
</div>

### Creating a postgres database:
<div>
	[create.md]
</div>

<br>

###	Importing a postgres database:

<div>
	In your terminal:
</div>

```sh
psql -U postgres -d import_questions -f questions.sql
```

