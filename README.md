## New database setup

```postgresql
create database name;
create user name with password 'password';
grant all privileges on database name to name;
-- connect to new database
grant all on schema public to name;

-- may need this too?
alter user name createdb;
```
