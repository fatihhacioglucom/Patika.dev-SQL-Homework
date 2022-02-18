# Patika.dev SQL Homework 4 - Distinct, Count

Aşağıdaki sorgu senaryolarının tümü **dvdrental** örnek veri tabanı üzerinden gerçekleştirilmiştir.

`Soru` Film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.
```sql
SELECT DISTINCT replacement_cost FROM film;
```
`Soru` Film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?
```sql
SELECT COUNT(DISTINCT replacement_cost) FROM film;
```
`Soru` Film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?
```sql
SELECT COUNT(*) FROM film WHERE title LIKE 'T%' AND rating='G' ;
```
`Soru` Country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?
```sql
SELECT COUNT(*) FROM country WHERE country LIKE '_____';
```
`Soru` City tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?
```sql
SELECT COUNT(*) FROM city WHERE city ILIKE '%r';
```
