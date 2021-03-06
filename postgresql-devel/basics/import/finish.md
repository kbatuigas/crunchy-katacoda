We've looked at a few different ways of loading data into a PostgreSQL database.
 Data can be added in bulk via a script or the COPY interface:  the `\copy` meta-command in psql, the SQL `COPY` command, driver level `COPY`, or a client like pgAdmin.

These are certainly not the only methods of loading data into Postgres - there 
are many others that might be suitable depending on your requirements. For example, foreign data wrappers (such as [`postgres_fdw`](https://www.postgresql.org/docs/current/postgres-fdw.html)) allow access to external databases, from which you could then import to your own. There are [many types of foreign data wrappers](https://wiki.postgresql.org/wiki/Foreign_data_wrappers) that give you access to other kinds of DBMS's such as MySQL, SQL Server, and MongoDB.

[pgloader](https://pgloader.io/) is an example of a data migration tool that 
supports database migrations to PostgreSQL from other DBMS's like MySQL, as 
well as other file formats in addition to flat files like CSV.  

_Enjoy learning about PostgreSQL? [Sign up for our newsletter](https://www.crunchydata.com/newsletter/) and get the latest tips from us each month._
