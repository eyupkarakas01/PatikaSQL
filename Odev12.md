1.Soru : film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?

SELECT * FROM film WHERE length>
(
SELECT AVG(length) FROM film
);

2.Soru : film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?

SELECT COUNT(*) FROM film WHERE rental_rate=
(
SELECT MAX(rental_rate) FROM film
);

3.Soru : film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.

SELECT * FROM film WHERE rental_rate =
(
SELECT MIN(rental_rate) FROM film
)
INTERSECT ALL
SELECT * FROM film WHERE replacement_cost =
(
SELECT MAX(replacement_cost) FROM film
);


4.Soru : payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.

SELECT customer.customer_id, customer.first_name, customer.last_name, COUNT(*) AS ALISVERIS_SAYISI FROM payment
JOIN customer ON payment.customer_id = customer.customer_id
GROUP BY customer.customer_id
ORDER BY ALISVERIS_SAYISI DESC;
