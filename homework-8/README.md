# Patika.dev SQL Homework 8

`Soru` Test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```sql
CREATE TABLE employee(
	id INTEGER PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100)
);
```
`Soru` Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```sql
insert into employee (id, name, birthday, email) values (1, 'Burlie Mary', '1954-05-11', 'bmary0@upenn.edu');
insert into employee (id, name, birthday, email) values (2, 'Susanne Mastrantone', '1941-10-11', 'smastrantone1@engadget.com');
insert into employee (id, name, birthday, email) values (3, 'Cecil Caunt', '1938-08-07', 'ccaunt2@theglobeandmail.com');
insert into employee (id, name, birthday, email) values (4, 'Lauryn Souter', '1921-04-12', 'lsouter3@webnode.com');
insert into employee (id, name, birthday, email) values (5, 'Marys Tunny', '1910-10-08', 'mtunny4@newyorker.com');
insert into employee (id, name, birthday, email) values (6, 'Karlen De Fraine', '1982-07-11', 'kde5@dion.ne.jp');
insert into employee (id, name, birthday, email) values (7, 'Evanne Cess', '1995-10-13', 'ecess6@dion.ne.jp');
insert into employee (id, name, birthday, email) values (8, 'Gaile Kubacki', '1956-01-21', 'gkubacki7@etsy.com');
insert into employee (id, name, birthday, email) values (9, 'Ronda Cummine', '1960-05-05', 'rcummine8@dagondesign.com');
insert into employee (id, name, birthday, email) values (10, 'Kimbra Olsen', '1914-03-03', 'kolsen9@infoseek.co.jp');
insert into employee (id, name, birthday, email) values (11, 'Irv Rawcliffe', '1956-08-27', 'irawcliffea@discuz.net');
insert into employee (id, name, birthday, email) values (12, 'Jemimah Livens', '1917-03-28', 'jlivensb@flavors.me');
insert into employee (id, name, birthday, email) values (13, 'Leah Fernier', '1963-07-29', 'lfernierc@dagondesign.com');
insert into employee (id, name, birthday, email) values (14, 'Loleta Jado', '1907-01-04', 'ljadod@scribd.com');
insert into employee (id, name, birthday, email) values (15, 'Reilly Genney', '1966-12-18', 'rgenneye@ebay.com');
insert into employee (id, name, birthday, email) values (16, 'Osmund Gissing', '1991-10-31', 'ogissingf@bluehost.com');
insert into employee (id, name, birthday, email) values (17, 'Aubine Forbear', '1978-06-07', 'aforbearg@shop-pro.jp');
insert into employee (id, name, birthday, email) values (18, 'Adriano Grange', '1907-07-08', 'agrangeh@google.com.br');
insert into employee (id, name, birthday, email) values (19, 'Roxanna Edy', '1990-05-07', 'redyi@chicagotribune.com');
insert into employee (id, name, birthday, email) values (20, 'Fawnia Moscone', '1922-09-07', 'fmosconej@europa.eu');
insert into employee (id, name, birthday, email) values (21, 'Merv Williamson', '1993-02-14', 'mwilliamsonk@independent.co.uk');
insert into employee (id, name, birthday, email) values (22, 'Anatollo Swatridge', '1908-07-02', 'aswatridgel@mtv.com');
insert into employee (id, name, birthday, email) values (23, 'Bird Joyson', '1904-07-07', 'bjoysonm@elpais.com');
insert into employee (id, name, birthday, email) values (24, 'Mair Tramel', '1971-12-28', 'mtrameln@newsvine.com');
insert into employee (id, name, birthday, email) values (25, 'Johanna Guage', '1929-05-02', 'jguageo@statcounter.com');
insert into employee (id, name, birthday, email) values (26, 'Teriann Yesipov', '1970-11-10', 'tyesipovp@sitemeter.com');
insert into employee (id, name, birthday, email) values (27, 'Aleta Sekulla', '1927-05-19', 'asekullaq@xrea.com');
insert into employee (id, name, birthday, email) values (28, 'Waneta Liff', '1942-06-30', 'wliffr@spotify.com');
insert into employee (id, name, birthday, email) values (29, 'Allyce Beer', '1943-02-12', 'abeers@free.fr');
insert into employee (id, name, birthday, email) values (30, 'Bertine Padmore', '1933-09-06', 'bpadmoret@tuttocitta.it');
insert into employee (id, name, birthday, email) values (31, 'Jarrod Giamo', '1977-07-07', 'jgiamou@t.co');
insert into employee (id, name, birthday, email) values (32, 'Ashlee Giannini', '1950-11-29', 'agianniniv@fema.gov');
insert into employee (id, name, birthday, email) values (33, 'North Begbie', '1998-08-20', 'nbegbiew@1und1.de');
insert into employee (id, name, birthday, email) values (34, 'Rafaellle Sphinxe', '1920-06-17', 'rsphinxex@earthlink.net');
insert into employee (id, name, birthday, email) values (35, 'Gerty Reglar', '1932-12-24', 'greglary@springer.com');
insert into employee (id, name, birthday, email) values (36, 'Elli Reisenberg', '1978-06-19', 'ereisenbergz@ebay.co.uk');
insert into employee (id, name, birthday, email) values (37, 'Derwin Coppo', '1962-03-23', 'dcoppo10@nhs.uk');
insert into employee (id, name, birthday, email) values (38, 'Cherilynn Giraudot', '1960-04-04', 'cgiraudot11@boston.com');
insert into employee (id, name, birthday, email) values (39, 'Lodovico Thurlborn', '1939-06-26', 'lthurlborn12@phpbb.com');
insert into employee (id, name, birthday, email) values (40, 'Camile Hart', '1906-02-01', 'chart13@army.mil');
insert into employee (id, name, birthday, email) values (41, 'Gilda Roark', '1979-06-17', 'groark14@bing.com');
insert into employee (id, name, birthday, email) values (42, 'Karil Minors', '1980-12-19', 'kminors15@dot.gov');
insert into employee (id, name, birthday, email) values (43, 'Baxie Cicculi', '1977-11-27', 'bcicculi16@123-reg.co.uk');
insert into employee (id, name, birthday, email) values (44, 'Madge Lowing', '1988-12-02', 'mlowing17@cnbc.com');
insert into employee (id, name, birthday, email) values (45, 'Ludwig Piletic', '1965-01-18', 'lpiletic18@zdnet.com');
insert into employee (id, name, birthday, email) values (46, 'Lanny Fenning', '1959-09-02', 'lfenning19@reference.com');
insert into employee (id, name, birthday, email) values (47, 'Malva McLanachan', '1950-03-14', 'mmclanachan1a@ning.com');
insert into employee (id, name, birthday, email) values (48, 'Arch Duplan', '1921-02-09', 'aduplan1b@reverbnation.com');
insert into employee (id, name, birthday, email) values (49, 'Aguie Maxsted', '1966-09-20', 'amaxsted1c@businessinsider.com');
insert into employee (id, name, birthday, email) values (50, 'Deana Beardsworth', '1908-08-07', 'dbeardsworth1d@who.int');
```
`Soru` Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```sql
UPDATE employee
	SET name = 'Fatih Hacioglu',
		birthday = '1990-01-01',
		email = 'fatihhacioglucom@gmail.com'
	WHERE id=1;
```
`Soru` Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```sql

```
