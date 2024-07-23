1.Soru : test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee(
	id SERIAL PRIMARY KEY,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);

2.Soru : Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.


insert into MOCK_DATA (id, name, email, birthday) values (1, 'Rosina', 'rmossop0@latimes.com', '2015-06-07 12:17:43');
insert into MOCK_DATA (id, name, email, birthday) values (2, 'Thorstein', 'tgrisdale1@vimeo.com', '2019-01-05 20:35:56');
insert into MOCK_DATA (id, name, email, birthday) values (3, 'Arielle', 'amartijn2@hatena.ne.jp', '2001-10-28 22:36:57');
insert into MOCK_DATA (id, name, email, birthday) values (4, 'Teodor', 'tbrame3@cnet.com', '2006-01-03 03:56:55');
insert into MOCK_DATA (id, name, email, birthday) values (5, 'Ralina', 'rpettersen4@fc2.com', '2014-04-04 22:49:18');
insert into MOCK_DATA (id, name, email, birthday) values (6, 'Christi', 'cdrinkhill5@friendfeed.com', '2024-07-01 23:38:21');
insert into MOCK_DATA (id, name, email, birthday) values (7, 'Sayre', 'stotman6@booking.com', '2009-08-07 22:31:31');
insert into MOCK_DATA (id, name, email, birthday) values (8, 'Kathryn', 'kpringley7@boston.com', '2013-11-07 21:53:12');
insert into MOCK_DATA (id, name, email, birthday) values (9, 'Darsie', 'dtaysbil8@sohu.com', '2002-05-08 01:38:39');
insert into MOCK_DATA (id, name, email, birthday) values (10, 'Andriette', 'aasker9@google.nl', '2014-05-09 08:52:40');
insert into MOCK_DATA (id, name, email, birthday) values (11, 'Caye', 'ctoopina@1688.com', '2023-11-28 11:10:00');
insert into MOCK_DATA (id, name, email, birthday) values (12, 'Miguela', 'mwessonb@webnode.com', '2011-01-09 23:06:01');
insert into MOCK_DATA (id, name, email, birthday) values (13, 'Glenine', 'gciccottioc@reference.com', '2018-11-25 02:32:15');
insert into MOCK_DATA (id, name, email, birthday) values (14, 'Marian', 'mhuped@economist.com', '2004-05-23 15:05:55');
insert into MOCK_DATA (id, name, email, birthday) values (15, 'Nola', 'nshevelse@netlog.com', '2012-06-13 03:58:25');
insert into MOCK_DATA (id, name, email, birthday) values (16, 'Wolf', 'whavef@salon.com', '2021-12-20 03:47:01');
insert into MOCK_DATA (id, name, email, birthday) values (17, 'Bernard', 'bmillamg@delicious.com', '2016-07-25 06:48:56');
insert into MOCK_DATA (id, name, email, birthday) values (18, 'Dari', 'dbateriph@seesaa.net', '2017-04-19 03:41:04');
insert into MOCK_DATA (id, name, email, birthday) values (19, 'Gun', 'gdrewi@scientificamerican.com', '2024-06-12 01:43:38');
insert into MOCK_DATA (id, name, email, birthday) values (20, 'Gamaliel', 'gbicknellj@state.tx.us', '2013-07-23 02:42:53');
insert into MOCK_DATA (id, name, email, birthday) values (21, 'Corrianne', 'cbehningk@aboutads.info', '2009-12-07 06:27:19');
insert into MOCK_DATA (id, name, email, birthday) values (22, 'Eveleen', 'eoluwatoyinl@patch.com', '2015-03-04 21:44:55');
insert into MOCK_DATA (id, name, email, birthday) values (23, 'Marga', 'mgleadhallm@icio.us', '2023-09-29 10:11:38');
insert into MOCK_DATA (id, name, email, birthday) values (24, 'Marie', 'mgwillymn@soup.io', '2007-08-19 04:50:13');
insert into MOCK_DATA (id, name, email, birthday) values (25, 'Silas', 'scoggano@mtv.com', '2007-07-04 20:33:08');
insert into MOCK_DATA (id, name, email, birthday) values (26, 'Jackie', 'jsussansp@redcross.org', '2001-04-13 16:03:04');
insert into MOCK_DATA (id, name, email, birthday) values (27, 'Whit', 'wstuckfordq@pen.io', '2022-09-03 17:26:53');
insert into MOCK_DATA (id, name, email, birthday) values (28, 'Stesha', 'sdaymondr@census.gov', '2010-02-07 01:15:39');
insert into MOCK_DATA (id, name, email, birthday) values (29, 'Muire', 'mhollerans@umn.edu', '2010-07-18 02:06:01');
insert into MOCK_DATA (id, name, email, birthday) values (30, 'Stoddard', 'sguardt@gizmodo.com', '2001-07-29 08:11:02');
insert into MOCK_DATA (id, name, email, birthday) values (31, 'Corny', 'cpavicu@huffingtonpost.com', '2023-09-05 00:47:26');
insert into MOCK_DATA (id, name, email, birthday) values (32, 'Denny', 'dstoeckv@chronoengine.com', '2007-03-23 14:44:05');
insert into MOCK_DATA (id, name, email, birthday) values (33, 'Matti', 'msynnottw@redcross.org', '2015-04-27 08:26:41');
insert into MOCK_DATA (id, name, email, birthday) values (34, 'Wendie', 'wnormandalex@nba.com', '2007-01-21 19:46:45');
insert into MOCK_DATA (id, name, email, birthday) values (35, 'Rheba', 'rmacroryy@bluehost.com', '2008-06-10 07:06:26');
insert into MOCK_DATA (id, name, email, birthday) values (36, 'Galven', 'gbeatyz@yelp.com', '2002-05-05 08:18:40');
insert into MOCK_DATA (id, name, email, birthday) values (37, 'Paco', 'pcrosscombe10@wikia.com', '2005-09-18 17:03:42');
insert into MOCK_DATA (id, name, email, birthday) values (38, 'Ernaline', 'earnley11@usgs.gov', '2007-06-01 22:52:21');
insert into MOCK_DATA (id, name, email, birthday) values (39, 'Joby', 'jvonsalzberg12@blog.com', '2001-12-31 09:05:13');
insert into MOCK_DATA (id, name, email, birthday) values (40, 'Carlos', 'cpainten13@geocities.jp', '2002-02-13 15:02:40');
insert into MOCK_DATA (id, name, email, birthday) values (41, 'Adrianna', 'aseywood14@craigslist.org', '2014-11-01 22:58:32');
insert into MOCK_DATA (id, name, email, birthday) values (42, 'Donnell', 'dcoghlin15@webmd.com', '2014-05-11 23:03:23');
insert into MOCK_DATA (id, name, email, birthday) values (43, 'Harriot', 'hrainsdon16@intel.com', '2015-11-13 15:05:52');
insert into MOCK_DATA (id, name, email, birthday) values (44, 'Charley', 'chofler17@ca.gov', '2020-05-05 22:48:10');
insert into MOCK_DATA (id, name, email, birthday) values (45, 'Dion', 'dgrinsted18@nsw.gov.au', '2022-02-24 15:52:33');
insert into MOCK_DATA (id, name, email, birthday) values (46, 'Gwenette', 'gdorgan19@ameblo.jp', '2000-07-29 07:38:27');
insert into MOCK_DATA (id, name, email, birthday) values (47, 'Carr', 'crigmond1a@t.co', '2013-03-29 16:29:51');
insert into MOCK_DATA (id, name, email, birthday) values (48, 'Essie', 'egallager1b@tmall.com', '2019-03-02 02:48:54');
insert into MOCK_DATA (id, name, email, birthday) values (49, 'Ange', 'afiller1c@about.me', '2014-05-14 11:09:11');
insert into MOCK_DATA (id, name, email, birthday) values (50, 'Abbey', 'ajuden1d@japanpost.jp', '2023-07-21 16:15:46');

3.Soru : Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee SET name = 'Atakan Yilmaz' WHERE id = 1 RETURNING *;
UPDATE employee SET birthday = '1998-09-12' WHERE id = 1 RETURNING *;
UPDATE employee SET email = 'aspar@aspar.com' WHERE id = 1 RETURNING *;
UPDATE employee SET email = 'napar@aspar.com' WHERE id = 2 RETURNING *;
UPDATE employee SET name = 'Aspar Napar' WHERE id = 2 RETURNING *;

4.Soru :Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee WHERE id = 3 RETURNING *;
DELETE FROM employee WHERE name LIKE 'Ba%' RETURNING *;
DELETE FROM employee WHERE name LIKE '%d' RETURNING *;
DELETE FROM employee WHERE id = 5 RETURNING *;
DELETE FROM employee WHERE id = 6 RETURNING *;
