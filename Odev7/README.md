# Ödev 7

## Soru 1

```sql
select rating, count(*) from film
group by rating 
order by count(*)
```

## Soru 2

```sql
select replacement_cost, count(*) from film
group by replacement_cost
having count(*) > 50
```

## Soru 3

```sql
select store_id, count(*) from customer
group by store_id
```

## Soru 4

```sql
select country_id, count(*) from city
group by country_id
order by count(*) desc
limit 1
-- Output: 44, 60
```
