# Ödev 6

## Soru 1

```sql
select round(avg(rental_rate), 2) from film
```

## Soru 2

```sql
select count(*) from film
where title like 'C%'
-- Output: 92
```

## Soru 3

```sql
select max(length) from film
where rental_rate = 2.99
```

## Soru 4

```sql
select count(distinct replacement_cost) from film
where length > 150
-- Output: 21
```
