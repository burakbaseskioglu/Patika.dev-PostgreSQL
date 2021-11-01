# Ödev 5

## Soru 1

```sql
select title, length from film
where title like '%n'
order by length desc
limit 5
```

## Soru 2

```sql
select title, length from film
where title like '%n'
order by length
offset 5 limit 5
```

## Soru 3

```sql
select customer_id, store_id, first_name, last_name, email from customer
where store_id = 1
order by last_name desc
limit 4
```
