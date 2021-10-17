# Ödev 3

## Soru 1

```sql
select * from country
where country like 'A%a'
```

## Soru 2

```sql
select * from country 
where country like '%n' and length(country) >= 6
```

## Soru 3

```sql
select * from film
where title ilike '%T%T%T%T%'
```

## Soru 4

```sql
select * from film
where title like 'C%' and length > 90 and rental_rate = 2.99
```
