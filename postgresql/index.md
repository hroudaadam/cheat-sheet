### PostgreSQL

#### CLI

`psql -U user -d database` - login

`\l` - list databases

`\d table` - table structure

`\dt` - list tables

#### Queries

create database

``` sql
CREATE DATABASE database`;
```

create table

``` sql
CREATE TABLE table (column type constraint, ...)`;
```

drop table

``` sql
DROP TABLE table;
```

add row

``` sql
INSERT INTO table (column, ...)
VALUES (value, ...);
```
