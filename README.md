# -ODEV2-SQL
dvdrental sorgu senaryoları çözümleri
Sorgu 1- film tablosunda bulunan tüm sütunlardaki verileri replacement cost değeri 12.99 dan büyük eşit ve 16.99 küçük olma koşuluyla sıralayınız ( BETWEEN - AND yapısını kullanınız.)
Çözüm 1- SELECT * FROM film 
WHERE replacement_cost BETWEEN 12.99 AND 16.99;
<img width="730" alt="Ekran Resmi 2023-03-01 18 06 47" src="https://user-images.githubusercontent.com/116847744/222179476-2d6ebff8-dc4d-427b-849d-c36e224d403e.png">
Sorgu 2- actor tablosunda bulunan first_name ve last_name sütunlardaki verileri first_name 'Penelope' veya 'Nick' veya 'Ed' değerleri olması koşuluyla sıralayınız. ( IN operatörünü kullanınız.)
Çözüm 2- SELECT first_name, last_name FROM actor 
WHERE first_name IN ('Penelope', 'Nick', 'Ed' );
<img width="706" alt="Ekran Resmi 2023-03-01 18 09 22" src="https://user-images.githubusercontent.com/116847744/222180178-062f5f60-63a4-43f1-a2f1-addaf38eba70.png">
Sorgu 3- film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99, 2.99, 4.99 VE replacement_cost 12.99, 15.99, 28.99 olma koşullarıyla sıralayınız. ( IN operatörünü kullanınız.)
Çözüm 3- SELECT * FROM film 
WHERE rental_rate IN (0.99, 2.99, 4.99 ) 
AND replacement_cost IN (12.99, 15.99, 28.99);
<img width="772" alt="Ekran Resmi 2023-03-01 18 12 44" src="https://user-images.githubusercontent.com/116847744/222181006-59ec636b-b750-406c-94d8-c57d7f7b78a8.png">
