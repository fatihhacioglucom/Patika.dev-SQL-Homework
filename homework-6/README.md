# Patika.dev SQL Homework 6 - Aggregate Functions

Aşağıdaki sorgu senaryolarının tümü **dvdrental** örnek veri tabanı üzerinden gerçekleştirilmiştir.

`Soru` Film tablosunda bulunan rental_rate sütunundaki değerlerin ortalaması nedir?
```sql
SELECT AVG(rental_rate) FROM film;
```
`Soru` Film tablosunda bulunan filmlerden kaç tanesi 'C' karakteri ile başlar?
```sql
SELECT COUNT(*) FROM film WHERE title LIKE 'C%';
```
`Soru` Film tablosunda bulunan filmlerden rental_rate değeri 0.99 a eşit olan en uzun (length) film kaç dakikadır?
```sql
SELECT MAX(length) FROM film WHERE rental_rate = 0.99;
```
`Soru` Film tablosunda bulunan filmlerin uzunluğu 150 dakikadan büyük olanlarına ait kaç farklı replacement_cost değeri vardır?
```sql
SELECT COUNT(DISTINCT replacement_cost) FROM film WHERE length>150;
```
