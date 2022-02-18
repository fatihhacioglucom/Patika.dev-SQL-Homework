# Patika.dev SQL Homework 10 - Left Join , Right Join, Full Join

Aşağıdaki sorgu senaryolarının tümü **dvdrental** örnek veri tabanı üzerinden gerçekleştirilmiştir.

`Soru` City tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu yazınız.
```sql
SELECT city, country
FROM city
LEFT JOIN country
ON city.country_id = country.country_id;
```
`Soru` Customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yazınız.
```sql
SELECT city, country
FROM city
LEFT JOIN country
ON city.country_id = country.country_id;
```
`Soru` Customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yazınız.
```sql
SELECT rental_id, first_name, last_name
FROM customer
FULL JOIN rental
ON customer.customer_id = rental.customer_id;
```
