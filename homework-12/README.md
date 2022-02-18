# Patika.dev SQL Homework 12 - Any, All

Aşağıdaki sorgu senaryolarının tümü **dvdrental** örnek veri tabanı üzerinden gerçekleştirilmiştir.

`Soru` Film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?
```sql
SELECT COUNT(*)
FROM film
WHERE length>
(
	SELECT AVG(length) FROM film
);
```
`Soru` Film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?
```sql
SELECT COUNT(*)
FROM film
WHERE rental_rate =
(
	SELECT MAX(rental_rate) FROM film
);
```
`Soru` Film tablosunda en düşük rental_rate ve en düşük replacement_cost değerlerine sahip filmleri sıralayınız.
```sql
SELECT *
FROM film
WHERE rental_rate = 
(
	SELECT MIN(rental_rate) FROM film
) 
AND replacement_cost = 
(
	SELECT MIN(replacement_cost) FROM film
);
```
`Soru` Payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.
```sql
SELECT customer.first_name, customer.last_name 
FROM payment 
INNER JOIN customer 
ON payment.customer_id = customer.customer_id
WHERE payment.amount =
(
	SELECT MAX(amount) FROM payment
);
```
