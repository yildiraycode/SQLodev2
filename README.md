# SQLodev2
## sql sorgulari patika odev 2
**Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.**<br/>
1.film tablosunda bulunan tüm sütunlardaki verileri replacement cost değeri 12.99 dan büyük eşit ve 16.99 küçük olma koşuluyla sıralayınız ( BETWEEN - AND yapısını kullanınız.)<br/><br/>
select * from film<br/>
where replacement_cost between 12.99 and 16.99;<br/><br/><br/>
2..actor tablosunda bulunan first_name ve last_name sütunlardaki verileri first_name 'Penelope' veya 'Nick' veya 'Ed' değerleri olması koşuluyla sıralayınız. ( IN operatörünü kullanınız.)<br/><br/>
select first_name,last_name from actor<br/>
where first_name IN('Penelope','Nick','Ed');<br/><br/><br/>
3.film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99, 2.99, 4.99 VE replacement_cost 12.99, 15.99, 28.99 olma koşullarıyla sıralayınız. ( IN operatörünü kullanınız.).<br/><br/>
select * from film<br/>
where rental_rate IN(0.99,2.99,3.99) AND replacement_cost IN(12.99,15.99,28.99);<br/><br/><br/>
