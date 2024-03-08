# Importing your PostgreSQL database

### Warning: 
Before you can import a postgres database, you need to create a database to import data into. 

### Creating a postgres database:
[Create a database](https://github.com/BloodyAngel22/Notes/blob/main/Postgres/create.md)

###	Importing a postgres database:

#### In your terminal:

```bash
psql -U postgres -d import_questions -f questions.sql
```