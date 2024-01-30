---

Soru 1 : film tablosunda bulunan rental_rate sütunundaki değerlerin ortalaması nedir?

```
SELECT AVG(rental_rate) as "Ortalama rental_rate"
FROM film
```

Soru 2 : film tablosunda bulunan filmlerden kaç tanesi 'C' karakteri ile başlar?

```
SELECT COUNT(title) as "C ile baslayan film sayisi"
FROM film
WHERE title LIKE 'C%'
```

Soru 3 : film tablosunda bulunan filmlerden rental_rate değeri 0.99 a eşit olan en uzun (length) film kaç dakikadır?

```
SELECT MAX(length) as "rental_rate değeri 0.99 olan en uzun film"
FROM film
WHERE rental_rate =0.99;
```

Soru 4: film tablosunda bulunan filmlerin uzunluğu 150 dakikadan büyük olanlarına ait kaç farklı replacement_cost değeri vardır?

```
SELECT count(DISTINCT replacement_cost) as"150dk dan uzun filmlerin replacement_cost değerleri"
FROM film
WHERE length>150
