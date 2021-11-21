# Ödev 8

## Soru 1

```sql
create table employee(
    id serial primary key,
    name varchar(50),
    birthday date,
    email varchar(100)
)
```

## Soru 3

```sql
update employee set 
name = 'Joe'
where id = 7
returning *

update employee set
name = 'Michael', birthday = '2021-11-21'
where name like 'A_%'

update employee set
name = 'Steve', birthday = '2000-05-15', email = 'steve2000@php.net'
where email like '%php.net'
returning *

update employee set
birthday = '1995-12-30'
where name = 'Wendall'
returning *

update employee set
email = 'monday@monday.com'
where email like '%mon%'
returning *
```

## Soru 4

```sql
delete from employee
where id = 6

delete from employee
where email = 'ccurner5@ucoz.ru'

delete from employee
where name like 'Za%'

delete from employee
where birthday between '2001-01-01' and '2001-12-30'
returning *

delete from employee 
where name = 'Barri'
```
