1.  test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

  ``` SQL
  CREATE TABLE employee(
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)	
);
  ```
  
2.  Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

```SQL
insert into employee (name, email, birthday) values ('Orran', 'oantill0@shop-pro.jp', '2009-01-18');
insert into employee (name, email, birthday) values ('Tami', 'tverchambre1@ameblo.jp', '2014-06-26');
insert into employee (name, email, birthday) values ('Enrica', 'egriffin2@house.gov', '2007-12-30');
insert into employee (name, email, birthday) values ('Vittorio', 'vdowns3@sun.com', '2001-06-18');
insert into employee (name, email, birthday) values ('Silva', 'smaccahee4@globo.com', '2012-05-30');
insert into employee (name, email, birthday) values ('Lotti', 'ldubique5@utexas.edu', '2001-05-30');
insert into employee (name, email, birthday) values ('Jermayne', 'jburhouse6@ucoz.com', '2018-09-01');
insert into employee (name, email, birthday) values ('Norri', 'nburfield7@behance.net', '2010-10-06');
insert into employee (name, email, birthday) values ('Seline', 'sflight8@booking.com', '2006-05-18');
insert into employee (name, email, birthday) values ('Romona', 'rdoram9@hatena.ne.jp', '2001-02-23');
insert into employee (name, email, birthday) values ('Simona', null, null);
insert into employee (name, email, birthday) values ('Yank', 'ypackmanb@etsy.com', '2004-08-08');
insert into employee (name, email, birthday) values ('Tatiana', 'ttorrentc@slate.com', '2005-12-26');
insert into employee (name, email, birthday) values ('Cornell', null, null);
insert into employee (name, email, birthday) values ('Aubine', 'adune@spotify.com', '2022-01-08');
insert into employee (name, email, birthday) values ('Ellissa', 'emacroryf@washingtonpost.com', '2005-06-06');
insert into employee (name, email, birthday) values ('Derrek', 'dedmandg@state.gov', '2003-01-31');
insert into employee (name, email, birthday) values ('Alvan', 'apetkovich@alexa.com', '2008-08-30');
insert into employee (name, email, birthday) values ('Dennet', 'dpetzi@examiner.com', '2015-12-30');
insert into employee (name, email, birthday) values ('Avrit', 'abricketj@livejournal.com', '2021-11-09');
insert into employee (name, email, birthday) values ('Norma', 'nwandrichk@cornell.edu', '2003-11-23');
insert into employee (name, email, birthday) values ('Sheffy', 'sgribbinsl@exblog.jp', '2012-05-18');
insert into employee (name, email, birthday) values ('Porty', 'pbootm@state.tx.us', '2001-04-01');
insert into employee (name, email, birthday) values ('Cami', 'cdanettn@google.ca', '2008-05-01');
insert into employee (name, email, birthday) values ('Marylinda', 'mrickardso@sitemeter.com', '2022-03-17');
insert into employee (name, email, birthday) values ('Terrance', 'trathep@pinterest.com', '2013-08-14');
insert into employee (name, email, birthday) values ('Tatiana', 'tshooterq@omniture.com', '2016-05-28');
insert into employee (name, email, birthday) values ('Vere', 'vdulantyr@comcast.net', '2012-07-22');
insert into employee (name, email, birthday) values ('Dom', 'dedworthyes@omniture.com', '2004-07-23');
insert into employee (name, email, birthday) values ('Sergei', 'saizikowitzt@netvibes.com', '2001-05-19');
insert into employee (name, email, birthday) values ('Basilio', 'bfilasovu@purevolume.com', '2014-11-21');
insert into employee (name, email, birthday) values ('Rosemary', 'raburrowv@cpanel.net', '2019-02-17');
insert into employee (name, email, birthday) values ('Sebastian', 'scarisw@constantcontact.com', '2010-03-24');
insert into employee (name, email, birthday) values ('Reinold', null, null);
insert into employee (name, email, birthday) values ('Charo', 'ccolefordy@dot.gov', '2006-11-14');
insert into employee (name, email, birthday) values ('Mia', 'mduffynz@hao123.com', '2010-06-05');
insert into employee (name, email, birthday) values ('Christian', 'csommerled10@ibm.com', '2021-01-28');
insert into employee (name, email, birthday) values ('Kalvin', 'kdandie11@odnoklassniki.ru', '2000-07-01');
insert into employee (name, email, birthday) values ('Karly', 'kpirouet12@senate.gov', '2017-03-09');
insert into employee (name, email, birthday) values ('Saleem', 'shendrickson13@bravesites.com', '2002-06-14');
insert into employee (name, email, birthday) values ('Augustus', 'amoorhouse14@fastcompany.com', '2011-02-20');
insert into employee (name, email, birthday) values ('Mandi', 'mklemensiewicz15@cornell.edu', '2013-10-18');
insert into employee (name, email, birthday) values ('Sascha', 'sliptrod16@about.com', '2019-05-30');
insert into employee (name, email, birthday) values ('Karylin', 'kegdale17@webeden.co.uk', '2009-12-16');
insert into employee (name, email, birthday) values ('Lindi', 'lopdenort18@chronoengine.com', '2022-03-11');
insert into employee (name, email, birthday) values ('Suzy', 'sfiltness19@ibm.com', '2001-02-22');
insert into employee (name, email, birthday) values ('Osborne', 'odurnian1a@mozilla.com', '2011-12-03');
insert into employee (name, email, birthday) values ('Goober', 'gdunican1b@posterous.com', '2018-06-22');
insert into employee (name, email, birthday) values ('Kinny', null, null);
insert into employee (name, email, birthday) values ('Antonietta', null, null);
```

3.  Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

```SQL
UPDATE employee
		 SET name = 'Orran ' ,
		 email ='alberto3567@gmail.com' ,
		 birthday ='1995-03-23'
		 WHERE id = 1 ;

UPDATE employee
		 SET name = 'Ahmet' ,
		 email ='ahmet@gmail.com' ,
		 birthday ='1978-02-06'
		 WHERE name= 'Tami' ;
UPDATE employee
		 SET name = 'Nelson  ' ,
		 email ='h.seldon@gmail.com' ,
		 birthday ='1971-02-01'
		 WHERE birthday = '2001-05-30' ;
UPDATE employee
		 SET name = 'deneme ' ,
		 email ='deneme@gmail.com' ,
		 birthday ='2000-03-08'
		 WHERE email = 'egriffin2@house.gov' ;
UPDATE employee
		 SET name = 'Oscar ' ,
		 email ='oscar22@gmail.com' ,
		 birthday ='1994-02-24'
		 WHERE id = 5 ;
```

4.  5 adet DELETE işlemini tek komutta yapalım.

```SQL
DELETE FROM employee
		WHERE id IN (1,2,3,4,5)
		RETURNING *;
```
