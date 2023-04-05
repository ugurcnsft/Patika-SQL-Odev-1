1#SORU - film tablosunda bulunan title ve description sütunlarındaki verileri sıralayınız.

1#CEVAP - SELECT title, description FROM film;

1#<img width="960" alt="1" src="https://user-images.githubusercontent.com/129968939/230118367-34797765-49bc-4acf-bac1-2e8e7e78a995.png">

2#SORU - film tablosunda bulunan tüm sütunlardaki verileri film uzunluğu (length) 60 dan büyük VE 75 ten küçük olma koşullarıyla sıralayınız.

2#CEVAP - SELECT * FROM film 
WHERE length > 60 
AND length < 75;

2#<img width="960" alt="2" src="https://user-images.githubusercontent.com/129968939/230126048-9ff72b04-d5ad-4e7b-9114-8a478d8b756e.png">

3#SORU - film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99 VE replacement_cost 12.99 VEYA 28.99 olma koşullarıyla sıralayınız.

3#CEVAP - SELECT * FROM film 
WHERE (rental_rate = 0.99) 
AND (replacement_cost = 12.99 OR replacement_cost = 28.99);

3#<img width="960" alt="3" src="https://user-images.githubusercontent.com/129968939/230129881-da95d522-a748-49b6-9292-c1ddb80b0537.png">

4#SORU - customer tablosunda bulunan first_name sütunundaki değeri 'Mary' olan müşterinin last_name sütunundaki değeri nedir?

4#CEVAP - SELECT first_name, last_name FROM customer 
WHERE first_name = 'Mary';

4#<img width="960" alt="4" src="https://user-images.githubusercontent.com/129968939/230131133-10a283ba-930f-41fe-8fe2-f73fd1245c5f.png">

5#SORU - film tablosundaki uzunluğu(length) 50 ten büyük OLMAYIP aynı zamanda rental_rate değeri 2.99 veya 4.99 OLMAYAN verileri sıralayınız.

5#CEVAP - SELECT length, rental_rate FROM film
WHERE NOT length > 50
AND NOT (rental_rate = 2.99 OR rental_rate = 4.99);

5#<img width="960" alt="5" src="https://user-images.githubusercontent.com/129968939/230135473-4620d6e5-1ca6-4c71-ab05-9b14db7e20d5.png">
