
# SQLTEST[MySQL 8.0 Command Line Client.txt](https://github.com/user-attachments/files/15517827/MySQL.8.0.Command.Line.Client.txt)
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'REFERENCES inventory(productID),
name varchar(50),
category  varchar(15)
)' at line 4
mysql> create TABLE promotions(
    -> id int PRIMARY KEY,
    -> inventory_productID int
    -> REFERENCES inventory(productID),
    -> name varchar(50),
    -> category  varchar(15)
    -> );
Query OK, 0 rows affected (0.06 sec)

mysql> desc inventory;
+-------------+--------------+------+-----+----------+----------------+
| Field       | Type         | Null | Key | Default  | Extra          |
+-------------+--------------+------+-----+----------+----------------+
| productID   | int unsigned | NO   | PRI | NULL     | auto_increment |
| productCode | char(30)     | NO   |     |          |                |
| name        | varchar(30)  | NO   |     |          |                |
| price       | decimal(7,2) | NO   |     | 99999.99 |                |
| quantity    | int unsigned | NO   |     | 0        |                |
| rating      | int          | YES  |     | NULL     |                |
+-------------+--------------+------+-----+----------+----------------+
6 rows in set (0.00 sec)

mysql> insert into promotions(id, inventory_productID,name,category) values
    -> (1,1001,'rewardpoints','cashback');
Query OK, 1 row affected (0.01 sec)

mysql> select * from promotions;
+----+---------------------+--------------+----------+
| id | inventory_productID | name         | category |
+----+---------------------+--------------+----------+
|  1 |                1001 | rewardpoints | cashback |
+----+---------------------+--------------+----------+
1 row in set (0.01 sec)

mysql>
mysql> MAKE DATABASE MOVIES_DB;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'MAKE DATABASE MOVIES_DB' at line 1
mysql> CREATE DATABASE MOVIES_DB;
Query OK, 1 row affected (0.05 sec)

mysql> USE MOVIES_DB;
Database changed
mysql> CREATE TABLE MOVIES(
    -> TITLE VARCHAR(50),
    -> RUNTIME INT,
    -> GENRE VARCHAR(50),
    -> IMDB_SCORE DECIMAL(2,1),
    -> RATING VARCHAR(10)
    -> );
Query OK, 0 rows affected (0.06 sec)

mysql> SHOW * MOVIES;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near '* MOVIES' at line 1
mysql> SHOW TABLES FROM MOVIES;
ERROR 1049 (42000): Unknown database 'movies'
mysql> SHOW TABLES;
+---------------------+
| Tables_in_movies_db |
+---------------------+
| movies              |
+---------------------+
1 row in set (0.02 sec)

mysql> SHOW TABLES FROM movies;
ERROR 1049 (42000): Unknown database 'movies'
mysql> INSERT INTO MOVIES(TITLE,RUNTIME,GENRE,IMDB_SCORE,RATING)
    -> VALUES
    -> ('HOWARD THE DUCK',110,'SCI-FI',4.6,'PG'),
    -> ('LAVALANTULA',83,'HORROR',4.7,'TV-14'),
    -> ('STARSHIP TROOPERS',129,'SCI-FI',7.2,'PG-13'),
    -> ('WALTZ WITH BASHIR',90,'DOCUMENTARY',8.0,'R'),
    -> ('SPACEBALLS',96,'COMEDY',7.1,'PG'),
    -> ('MONSTERS INC.',92,'ANIMATION',8.1,'G');
Query OK, 6 rows affected (0.03 sec)
Records: 6  Duplicates: 0  Warnings: 0

mysql> SHOW TABLE
    -> ^C
mysql> SHOW TABLE;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near '' at line 1
mysql> SHOW TABLES FROM movies;
ERROR 1049 (42000): Unknown database 'movies'
mysql> SHOW * MOVIES;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near '* MOVIES' at line 1
mysql> drop table MOVIES;
Query OK, 0 rows affected (0.04 sec)

mysql> DESCRIBE MOVIES;
ERROR 1146 (42S02): Table 'movies_db.movies' doesn't exist
mysql> SHOW TABLES;
Empty set (0.00 sec)

mysql> CREATE DATABASE MOVIES_DB;
ERROR 1007 (HY000): Can't create database 'movies_db'; database exists
mysql> USE MOVIES_DB;
Database changed
mysql> SHOW TABLES;
Empty set (0.00 sec)

mysql> USE MOVIES_DB;
Database changed
mysql> CREATE TABLE MOVIES(
    -> TITLE VARCHAR(50),
    -> RUNTIME INT,
    -> GENRE VARCHAR(50),
    -> IMDB_SCORE DECIMAL(2,1),
    -> RATING VARCHAR(10)
    -> );
Query OK, 0 rows affected (0.04 sec)

mysql> INSERT INTO MOVIES(TITLE,RUNTIME,GENRE,IMDB_SCORE,RATING)
    -> VALUES
    -> ('HOWARD THE DUCK',110,'SCI-FI',4.6,'PG'),
    -> ('LAVALANTULA',83,'HORROR',4.7,'TV-14'),
    -> ('STARSHIP TROOPERS',129,'SCI-FI',7.2,'PG-13'),
    -> ('WALTZ WITH BASHIR',90,'DOCUMENTARY',8.0,'R'),
    -> ('SPACEBALLS',96,'COMEDY',7.1,'PG'),
    -> ('MONSTERS INC.',92,'ANIMATION',8.1,'G');
Query OK, 6 rows affected (0.02 sec)
Records: 6  Duplicates: 0  Warnings: 0

mysql> DESCRIBE MOVIES;
+------------+--------------+------+-----+---------+-------+
| Field      | Type         | Null | Key | Default | Extra |
+------------+--------------+------+-----+---------+-------+
| TITLE      | varchar(50)  | YES  |     | NULL    |       |
| RUNTIME    | int          | YES  |     | NULL    |       |
| GENRE      | varchar(50)  | YES  |     | NULL    |       |
| IMDB_SCORE | decimal(2,1) | YES  |     | NULL    |       |
| RATING     | varchar(10)  | YES  |     | NULL    |       |
+------------+--------------+------+-----+---------+-------+
5 rows in set (0.02 sec)

mysql> SHOW * FROM MOVIES;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near '* FROMMOVIES' at line 1
mysql> SELECT * FROM MOVIES;
+-------------------+---------+-------------+------------+--------+
| TITLE             | RUNTIME | GENRE       | IMDB_SCORE | RATING |
+-------------------+---------+-------------+------------+--------+
| HOWARD THE DUCK   |     110 | SCI-FI      |        4.6 | PG     |
| LAVALANTULA       |      83 | HORROR      |        4.7 | TV-14  |
| STARSHIP TROOPERS |     129 | SCI-FI      |        7.2 | PG-13  |
| WALTZ WITH BASHIR |      90 | DOCUMENTARY |        8.0 | R      |
| SPACEBALLS        |      96 | COMEDY      |        7.1 | PG     |
| MONSTERS INC.     |      92 | ANIMATION   |        8.1 | G      |
+-------------------+---------+-------------+------------+--------+
6 rows in set (0.01 sec)

mysql> INSERT INTO MOVIES(TITLE,RUNTIME,GENRE,IMDB_SCORE,RATING)
    -> VALUES
    -> ('PAID IN FULL',110,'CRIME',9.5,'R'),
    -> ('BELLY',120,'CRIME',9.5,'R'),
    -> );
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near ')' at line 5
mysql> INSERT INTO MOVIES(TITLE,RUNTIME,GENRE,IMDB_SCORE,RATING)
    -> VALUES
    -> ('PAID IN FULL',110,'CRIME',9.5,'R'),
    -> ('BELLY',120,'CRIME',9.5,'R');
Query OK, 2 rows affected (0.05 sec)
Records: 2  Duplicates: 0  Warnings: 0

mysql> SELECT * FROM MOVIES;
+-------------------+---------+-------------+------------+--------+
| TITLE             | RUNTIME | GENRE       | IMDB_SCORE | RATING |
+-------------------+---------+-------------+------------+--------+
| HOWARD THE DUCK   |     110 | SCI-FI      |        4.6 | PG     |
| LAVALANTULA       |      83 | HORROR      |        4.7 | TV-14  |
| STARSHIP TROOPERS |     129 | SCI-FI      |        7.2 | PG-13  |
| WALTZ WITH BASHIR |      90 | DOCUMENTARY |        8.0 | R      |
| SPACEBALLS        |      96 | COMEDY      |        7.1 | PG     |
| MONSTERS INC.     |      92 | ANIMATION   |        8.1 | G      |
| PAID IN FULL      |     110 | CRIME       |        9.5 | R      |
| BELLY             |     120 | CRIME       |        9.5 | R      |
+-------------------+---------+-------------+------------+--------+
8 rows in set (0.01 sec)

mysql> SELECT * FROM MOVIES WHERE GENRE ='SCI-FI';
+-------------------+---------+--------+------------+--------+
| TITLE             | RUNTIME | GENRE  | IMDB_SCORE | RATING |
+-------------------+---------+--------+------------+--------+
| HOWARD THE DUCK   |     110 | SCI-FI |        4.6 | PG     |
| STARSHIP TROOPERS |     129 | SCI-FI |        7.2 | PG-13  |
+-------------------+---------+--------+------------+--------+
2 rows in set (0.02 sec)

mysql> SELECT *  FROM WHERE SCORE >=6.5;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'WHERE SCORE >=6.5' at line 1
mysql> SELECT *  FROM MOVIES WHERE SCORE >=6.5;
ERROR 1054 (42S22): Unknown column 'SCORE' in 'where clause'
mysql> SELECT *  FROM MOVIES WHERE IMDB_SCORE >=6.5;
+-------------------+---------+-------------+------------+--------+
| TITLE             | RUNTIME | GENRE       | IMDB_SCORE | RATING |
+-------------------+---------+-------------+------------+--------+
| STARSHIP TROOPERS |     129 | SCI-FI      |        7.2 | PG-13  |
| WALTZ WITH BASHIR |      90 | DOCUMENTARY |        8.0 | R      |
| SPACEBALLS        |      96 | COMEDY      |        7.1 | PG     |
| MONSTERS INC.     |      92 | ANIMATION   |        8.1 | G      |
| PAID IN FULL      |     110 | CRIME       |        9.5 | R      |
| BELLY             |     120 | CRIME       |        9.5 | R      |
+-------------------+---------+-------------+------------+--------+
6 rows in set (0.00 sec)

mysql> SELECT * FROM MOVIES WHERE(RATING='G' OR RATING='GP') AND RUNTIME <100;
+---------------+---------+-----------+------------+--------+
| TITLE         | RUNTIME | GENRE     | IMDB_SCORE | RATING |
+---------------+---------+-----------+------------+--------+
| MONSTERS INC. |      92 | ANIMATION |        8.1 | G      |
+---------------+---------+-----------+------------+--------+
1 row in set (0.01 sec)

mysql> SELECT GENRE,AVG(RUNTIME)
    -> FROM MOVIES,
    -> WHERE IMDB_SCORE<7.5,
    -> GROUP BY GENRE;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'WHERE IMDB_SCORE<7.5,
GROUP BY GENRE' at line 3
mysql> SELECT GENRE,AVG(RUNTIME)
    -> FROM MOVIES,
    -> WHERE IMDB_SCORE<7.5
    -> GROUP BY GENRE;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'WHERE IMDB_SCORE<7.5
GROUP BY GENRE' at line 3
mysql> SELECT GENRE,AVG(RUNTIME) FROM MOVIES WHERE IMDB_SCORE<7.5 GROUP BY GENRE;

+--------+--------------+
| GENRE  | AVG(RUNTIME) |
+--------+--------------+
| SCI-FI |     119.5000 |
| HORROR |      83.0000 |
| COMEDY |      96.0000 |
+--------+--------------+
3 rows in set (0.02 sec)

mysql> SELECT * FROM MOVIES WHERE TITLE='STARSHIP TROOPERS';
+-------------------+---------+--------+------------+--------+
| TITLE             | RUNTIME | GENRE  | IMDB_SCORE | RATING |
+-------------------+---------+--------+------------+--------+
| STARSHIP TROOPERS |     129 | SCI-FI |        7.2 | PG-13  |
+-------------------+---------+--------+------------+--------+
1 row in set (0.00 sec)

mysql> UPDATE MOVIES SET RATING='R' WHERE TITLE='STARSHIP TROOPERS';
Query OK, 1 row affected (0.02 sec)
Rows matched: 1  Changed: 1  Warnings: 0

mysql> SELECT * FROM MOVIES;
+-------------------+---------+-------------+------------+--------+
| TITLE             | RUNTIME | GENRE       | IMDB_SCORE | RATING |
+-------------------+---------+-------------+------------+--------+
| HOWARD THE DUCK   |     110 | SCI-FI      |        4.6 | PG     |
| LAVALANTULA       |      83 | HORROR      |        4.7 | TV-14  |
| STARSHIP TROOPERS |     129 | SCI-FI      |        7.2 | R      |
| WALTZ WITH BASHIR |      90 | DOCUMENTARY |        8.0 | R      |
| SPACEBALLS        |      96 | COMEDY      |        7.1 | PG     |
| MONSTERS INC.     |      92 | ANIMATION   |        8.1 | G      |
| PAID IN FULL      |     110 | CRIME       |        9.5 | R      |
| BELLY             |     120 | CRIME       |        9.5 | R      |
+-------------------+---------+-------------+------------+--------+
8 rows in set (0.00 sec)

mysql> ALTER TABLE MOVIES ADD COLUMN MOVIEID INTUNSIGNED NOT NULL AUTO_INCREMENT;

ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'INTUNSIGNED NOT NULL AUTO_INCREMENT' at line 1
mysql> ALTER TABLE MOVIES ADD COLUMN MOVIEID INT UNSIGNED NOT NULL AUTO_INCREMENT
;
ERROR 1075 (42000): Incorrect table definition; there can be only one auto column and it must be defined as a key
mysql> ALTER TABLE MOVIES ADD COLUMN MOVIEID INT UNSIGNED NOT NULL UNIQUE(MOVIEID);
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near '(MOVIEID)' at line 1
mysql> ALTER TABLE MOVIES ADD COLUMN MOVIEID INT UNSIGNED NOT NULL, UNIQUE(MOVIEI
D);
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'UNIQUE(MOVIEID)' at line 1
mysql> ALTER TABLE MOVIES ADD COLUMN MOVIEID INT UNSIGNED NOT NULL, ADD UNIQUE(MO
VIEID);
ERROR 1062 (23000): Duplicate entry '0' for key 'movies.MOVIEID'
mysql> SELECT * FROM MOVIES;
+-------------------+---------+-------------+------------+--------+
| TITLE             | RUNTIME | GENRE       | IMDB_SCORE | RATING |
+-------------------+---------+-------------+------------+--------+
| HOWARD THE DUCK   |     110 | SCI-FI      |        4.6 | PG     |
| LAVALANTULA       |      83 | HORROR      |        4.7 | TV-14  |
| STARSHIP TROOPERS |     129 | SCI-FI      |        7.2 | R      |
| WALTZ WITH BASHIR |      90 | DOCUMENTARY |        8.0 | R      |
| SPACEBALLS        |      96 | COMEDY      |        7.1 | PG     |
| MONSTERS INC.     |      92 | ANIMATION   |        8.1 | G      |
| PAID IN FULL      |     110 | CRIME       |        9.5 | R      |
| BELLY             |     120 | CRIME       |        9.5 | R      |
+-------------------+---------+-------------+------------+--------+
8 rows in set (0.01 sec)

mysql> ALTER TABLE MOVIES ADD COLUMN MOVIEID INTUNSIGNED NOT NULL AUTO_INCREMENTPRIMARY KEY;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'INTUNSIGNED NOT NULL AUTO_INCREMENT PRIMARY KEY' at line 1
mysql> SELECT RATING , AVG(IMDB_SCORE) ,MAX(IMDB_SCORE),MIN(IMBD_SCORE) FROM MOVI
ES GROUP BY RATING HAVING COUNT(*)>1;
ERROR 1054 (42S22): Unknown column 'IMBD_SCORE' in 'field list'
mysql> SELECT RATING , AVG(IMDB_SCORE) ,MAX(IMDB_SCORE),MIN(IMDB_SCORE) FROM MOVI
ES GROUP BY RATING HAVING COUNT(*)>1;
+--------+-----------------+-----------------+-----------------+
| RATING | AVG(IMDB_SCORE) | MAX(IMDB_SCORE) | MIN(IMDB_SCORE) |
+--------+-----------------+-----------------+-----------------+
| PG     |         5.85000 |             7.1 |             4.6 |
| R      |         8.55000 |             9.5 |             7.2 |
+--------+-----------------+-----------------+-----------------+
2 rows in set (0.01 sec)

mysql> ALTER TABLE MOVIES ADD COLUMN MOVIEID INT UNSIGNED NOT NULL AUTO_INCREMENTPRIMARY KEY;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'AUTO_INCREMENTPRIMARY KEY' at line 1
mysql> ALTER TABLE MOVIES ADD COLUMN MOVIEID INT UNSIGNED NOT NULL AUTO_INCREMENTPRIMARY KEY;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'AUTO_INCREMENTPRIMARY KEY' at line 1
mysql> ALTER TABLE MOVIES ADD COLUMN MOVIEID INT UNSIGNED NOT NULL ;
Query OK, 0 rows affected (0.08 sec)
Records: 0  Duplicates: 0  Warnings: 0

mysql> SELECT * FROM MOVIES;
+-------------------+---------+-------------+------------+--------+---------+
| TITLE             | RUNTIME | GENRE       | IMDB_SCORE | RATING | MOVIEID |
+-------------------+---------+-------------+------------+--------+---------+
| HOWARD THE DUCK   |     110 | SCI-FI      |        4.6 | PG     |       0 |
| LAVALANTULA       |      83 | HORROR      |        4.7 | TV-14  |       0 |
| STARSHIP TROOPERS |     129 | SCI-FI      |        7.2 | R      |       0 |
| WALTZ WITH BASHIR |      90 | DOCUMENTARY |        8.0 | R      |       0 |
| SPACEBALLS        |      96 | COMEDY      |        7.1 | PG     |       0 |
| MONSTERS INC.     |      92 | ANIMATION   |        8.1 | G      |       0 |
| PAID IN FULL      |     110 | CRIME       |        9.5 | R      |       0 |
| BELLY             |     120 | CRIME       |        9.5 | R      |       0 |
+-------------------+---------+-------------+------------+--------+---------+
8 rows in set (0.00 sec)

mysql> SELECT MOVIEID RATINGS FROM MOVIES WHERE GENRE ='HORROR' AND 'DOCUMENTARY'
;
Empty set, 1 warning (0.01 sec)

mysql> SELECT MOVIEID, RATINGS FROM MOVIES WHERE GENRE ='HORROR' AND 'DOCUMENTARY
';
ERROR 1054 (42S22): Unknown column 'RATINGS' in 'field list'
mysql> SELECT MOVIEID, RATING FROM MOVIES WHERE GENRE ='HORROR' AND 'DOCUMENTARY'
;
Empty set, 1 warning (0.00 sec)

mysql> SELECT * FROM MOVIES;
+-------------------+---------+-------------+------------+--------+---------+
| TITLE             | RUNTIME | GENRE       | IMDB_SCORE | RATING | MOVIEID |
+-------------------+---------+-------------+------------+--------+---------+
| HOWARD THE DUCK   |     110 | SCI-FI      |        4.6 | PG     |       0 |
| LAVALANTULA       |      83 | HORROR      |        4.7 | TV-14  |       0 |
| STARSHIP TROOPERS |     129 | SCI-FI      |        7.2 | R      |       0 |
| WALTZ WITH BASHIR |      90 | DOCUMENTARY |        8.0 | R      |       0 |
| SPACEBALLS        |      96 | COMEDY      |        7.1 | PG     |       0 |
| MONSTERS INC.     |      92 | ANIMATION   |        8.1 | G      |       0 |
| PAID IN FULL      |     110 | CRIME       |        9.5 | R      |       0 |
| BELLY             |     120 | CRIME       |        9.5 | R      |       0 |
+-------------------+---------+-------------+------------+--------+---------+
8 rows in set (0.00 sec)

mysql> SELECT MOVIEID RATINGS FROM MOVIES WHERE GENRE ='HORROR' OR 'DOCUMENTARY';

+---------+
| RATINGS |
+---------+
|       0 |
+---------+
1 row in set, 1 warning (0.00 sec)

mysql> SELECT MOVIEID, RATINGS FROM MOVIES WHERE GENRE ='HORROR' OR 'DOCUMENTARY'
;
ERROR 1054 (42S22): Unknown column 'RATINGS' in 'field list'
mysql> SELECT MOVIEID, RATING FROM MOVIES WHERE GENRE ='HORROR' OR 'DOCUMENTARY';

+---------+--------+
| MOVIEID | RATING |
+---------+--------+
|       0 | TV-14  |
+---------+--------+
1 row in set, 1 warning (0.01 sec)

mysql> SELECT MOVIEID, RATING FROM MOVIES WHERE GENRE IN ('HORROR', 'DOCUMENTARY');
+---------+--------+
| MOVIEID | RATING |
+---------+--------+
|       0 | TV-14  |
|       0 | R      |
+---------+--------+
2 rows in set (0.01 sec)

mysql> DELETE FROM MOVIES WHERE RATING ='R';
Query OK, 4 rows affected (0.03 sec)

mysql> SELECT * FROM MOVIES;
+-----------------+---------+-----------+------------+--------+---------+
| TITLE           | RUNTIME | GENRE     | IMDB_SCORE | RATING | MOVIEID |
+-----------------+---------+-----------+------------+--------+---------+
| HOWARD THE DUCK |     110 | SCI-FI    |        4.6 | PG     |       0 |
| LAVALANTULA     |      83 | HORROR    |        4.7 | TV-14  |       0 |
| SPACEBALLS      |      96 | COMEDY    |        7.1 | PG     |       0 |
| MONSTERS INC.   |      92 | ANIMATION |        8.1 | G      |       0 |
+-----------------+---------+-----------+------------+--------+---------+
4 rows in set (0.01 sec)

mysql> ALTER TABLE MOVIES MODIFY COLUMN MOVIEID INT AUTO_INCREMENT;
ERROR 1075 (42000): Incorrect table definition; there can be only one auto column and it must be defined as a key
mysql> ALTER TABLE MOVIES MODIFY COLUMN MOVIEID INT AUTO_INCREMENT PRIMARY KEY;
Query OK, 4 rows affected (0.15 sec)
Records: 4  Duplicates: 0  Warnings: 0

mysql> SELECT * FROM MOVIES;
+-----------------+---------+-----------+------------+--------+---------+
| TITLE           | RUNTIME | GENRE     | IMDB_SCORE | RATING | MOVIEID |
+-----------------+---------+-----------+------------+--------+---------+
| HOWARD THE DUCK |     110 | SCI-FI    |        4.6 | PG     |       1 |
| LAVALANTULA     |      83 | HORROR    |        4.7 | TV-14  |       2 |
| SPACEBALLS      |      96 | COMEDY    |        7.1 | PG     |       3 |
| MONSTERS INC.   |      92 | ANIMATION |        8.1 | G      |       4 |
+-----------------+---------+-----------+------------+--------+---------+
4 rows in set (0.00 sec)

mysql>

