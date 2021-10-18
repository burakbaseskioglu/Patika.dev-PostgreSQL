# Ödev 4

## Soru 1

```sql
select distinct replacement_cost from film
```

## Soru 2

```sql
select Count(distinct replacement_cost) from film
-- count : 21
```

## Soru 3

```sql
select count(*) from film
where title like 'T%' and rating = 'G'
-- count : 9
```

## Soru 4

```sql
select count(*) from country
where length(country) = 5
-- count : 13
```

## Soru 5

```sql
select count(*) from city
where city like 'R%' or city like '%r'
-- count : 45
```
