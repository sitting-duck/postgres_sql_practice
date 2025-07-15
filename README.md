# postgres_sql_practice
practice for learning postgres sql
 studying from this site: 
https://neon.com/postgresql/postgresql-getting-started/postgresql-sample-database

We are using the DVD Rental sample database.

The superuser password is : password
The port is 5432 by default for the server

Connect to the server:
``` bash
psql -U postgres
```
Example output showing my version: 
```bash
postgres=# SELECT version();
                                                     version                                                      
------------------------------------------------------------------------------------------------------------------
 PostgreSQL 17.5 on x86_64-apple-darwin23.6.0, compiled by Apple clang version 16.0.0 (clang-1600.0.26.6), 64-bit
(1 row)

```

how to connect to the dbase using pgAdmin: 
https://neon.com/postgresql/postgresql-getting-started/connect-to-postgresql-database
