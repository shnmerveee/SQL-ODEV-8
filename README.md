# SQL-ODEV-8
test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
ÇÖZÜM:CREATE TABLE employee (
id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
)

Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

![Capture](https://user-images.githubusercontent.com/128131203/226906361-9a222c12-1b6f-4816-b187-78d41623675c.PNG)

Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
ÇÖZÜM:
UPDATE employee
SET 
name= 'düzenlendi'
where id <15

Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
ÇÖZÜM: DELETE from employee
WHERE id BETWEEN 35 and 40
