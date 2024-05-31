[MySQL 8.0 Command Line Client.txt](https://github.com/user-attachments/files/15517749/MySQL.8.0.Command.Line.Client.txt)# SQLTEST[Uploading MySQL 8.0 Command Enter password: *******
Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is 11
Server version: 8.0.37 MySQL Community Server - GPL

Copyright (c) 2000, 2024, Oracle and/or its affiliates.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql> SOURCE C:\Users\Student.BOSPF39YB8B\Downloads\sakila-db\sakila-db\sakila-data.sql
Query OK, 0 rows affected (0.02 sec)

Query OK, 0 rows affected (0.01 sec)

Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

Database changed
Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'actor.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'address.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'category.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'city.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'country.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'customer.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

ERROR 1359 (HY000): Trigger already exists
Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'film.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1-1' for key 'film_actor.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1-6' for key 'film_category.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'inventory.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'language.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'payment.PRIMARY'
ERROR 1062 (23000): Duplicate entry '14886' for key 'payment.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

ERROR 1359 (HY000): Trigger already exists
Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'rental.PRIMARY'
ERROR 1062 (23000): Duplicate entry '12382' for key 'rental.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

ERROR 1359 (HY000): Trigger already exists
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.01 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'staff.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

ERROR 1062 (23000): Duplicate entry '1' for key 'store.PRIMARY'
Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

Query OK, 0 rows affected (0.00 sec)

mysql> SOURSEC:\Users\Student.BOSPF39YB8B\Downloads\sakila-db\sakila-db\sakila-schema.sql
ERROR:
Unknown command '\U'.
ERROR:
Unknown command '\S'.
ERROR:
Unknown command '\D'.
--------------
C:\Program Files\MySQL\MySQL Server 8.0\bin\mysql.exe  Ver 8.0.37 for Win64 on x86_64 (MySQL Community Server - GPL)

Connection id:          11
Current database:       sakila
Current user:           root@localhost
SSL:                    Cipher in use is TLS_AES_256_GCM_SHA384
Using delimiter:        ;
Server version:         8.0.37 MySQL Community Server - GPL
Protocol version:       10
Connection:             localhost via TCP/IP
Server characterset:    utf8mb4
Db     characterset:    utf8mb4
Client characterset:    utf8mb4
Conn.  characterset:    utf8mb4
TCP port:               3306
Binary data as:         Hexadecimal
Uptime:                 23 hours 6 min 17 sec

Threads: 2  Questions: 82  Slow queries: 0  Opens: 191  Flush tables: 3  Open tables: 107  Queries per second avg: 0.000
--------------

--------------
C:\Program Files\MySQL\MySQL Server 8.0\bin\mysql.exe  Ver 8.0.37 for Win64 on x86_64 (MySQL Community Server - GPL)

Connection id:          11
Current database:       sakila
Current user:           root@localhost
SSL:                    Cipher in use is TLS_AES_256_GCM_SHA384
Using delimiter:        ;
Server version:         8.0.37 MySQL Community Server - GPL
Protocol version:       10
Connection:             localhost via TCP/IP
Server characterset:    utf8mb4
Db     characterset:    utf8mb4
Client characterset:    utf8mb4
Conn.  characterset:    utf8mb4
TCP port:               3306
Binary data as:         Hexadecimal
Uptime:                 23 hours 6 min 17 sec

Threads: 2  Questions: 85  Slow queries: 0  Opens: 191  Flush tables: 3  Open tables: 107  Queries per second avg: 0.001
--------------

--------------
C:\Program Files\MySQL\MySQL Server 8.0\bin\mysql.exe  Ver 8.0.37 for Win64 on x86_64 (MySQL Community Server - GPL)

Connection id:          11
Current database:       sakila
Current user:           root@localhost
SSL:                    Cipher in use is TLS_AES_256_GCM_SHA384
Using delimiter:        ;
Server version:         8.0.37 MySQL Community Server - GPL
Protocol version:       10
Connection:             localhost via TCP/IP
Server characterset:    utf8mb4
Db     characterset:    utf8mb4
Client characterset:    utf8mb4
Conn.  characterset:    utf8mb4
TCP port:               3306
Binary data as:         Hexadecimal
Uptime:                 23 hours 6 min 17 sec

Threads: 2  Questions: 88  Slow queries: 0  Opens: 191  Flush tables: 3  Open tables: 107  Queries per second avg: 0.001
--------------

    -> ^C
mysql> USE SAKILA
Database changed
mysql> SHOW TABLES
    -> SHOW TABLES;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SHOW TABLES' at line 2
mysql> ^C
mysql> show tables;
+----------------------------+
| Tables_in_sakila           |
+----------------------------+
| actor                      |
| actor_info                 |
| address                    |
| category                   |
| city                       |
| country                    |
| customer                   |
| customer_list              |
| film                       |
| film_actor                 |
| film_category              |
| film_list                  |
| film_text                  |
| inventory                  |
| language                   |
| nicer_but_slower_film_list |
| payment                    |
| rental                     |
| sales_by_film_category     |
| sales_by_store             |
| staff                      |
| staff_list                 |
| store                      |
+----------------------------+
23 rows in set (0.04 sec)

mysql> ^C
mysql> show databases;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| mysql              |
| performance_schema |
| sakila             |
| sys                |
| world              |
+--------------------+
6 rows in set (0.02 sec)

mysql> use sakila
Database changed
mysql> use sakila;
Database changed
mysql> select * from sakila
    -> select * from sakila;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'select* from sakila' at line 2
mysql> show tables;
+----------------------------+
| Tables_in_sakila           |
+----------------------------+
| actor                      |
| actor_info                 |
| address                    |
| category                   |
| city                       |
| country                    |
| customer                   |
| customer_list              |
| film                       |
| film_actor                 |
| film_category              |
| film_list                  |
| film_text                  |
| inventory                  |
| language                   |
| nicer_but_slower_film_list |
| payment                    |
| rental                     |
| sales_by_film_category     |
| sales_by_store             |
| staff                      |
| staff_list                 |
| store                      |
+----------------------------+
23 rows in set (0.00 sec)

mysql> select * from actor;
+----------+-------------+--------------+---------------------+
| actor_id | first_name  | last_name    | last_update         |
+----------+-------------+--------------+---------------------+
|        1 | PENELOPE    | GUINESS      | 2006-02-15 04:34:33 |
|        2 | NICK        | WAHLBERG     | 2006-02-15 04:34:33 |
|        3 | ED          | CHASE        | 2006-02-15 04:34:33 |
|        4 | JENNIFER    | DAVIS        | 2006-02-15 04:34:33 |
|        5 | JOHNNY      | LOLLOBRIGIDA | 2006-02-15 04:34:33 |
|        6 | BETTE       | NICHOLSON    | 2006-02-15 04:34:33 |
|        7 | GRACE       | MOSTEL       | 2006-02-15 04:34:33 |
|        8 | MATTHEW     | JOHANSSON    | 2006-02-15 04:34:33 |
|        9 | JOE         | SWANK        | 2006-02-15 04:34:33 |
|       10 | CHRISTIAN   | GABLE        | 2006-02-15 04:34:33 |
|       11 | ZERO        | CAGE         | 2006-02-15 04:34:33 |
|       12 | KARL        | BERRY        | 2006-02-15 04:34:33 |
|       13 | UMA         | WOOD         | 2006-02-15 04:34:33 |
|       14 | VIVIEN      | BERGEN       | 2006-02-15 04:34:33 |
|       15 | CUBA        | OLIVIER      | 2006-02-15 04:34:33 |
|       16 | FRED        | COSTNER      | 2006-02-15 04:34:33 |
|       17 | HELEN       | VOIGHT       | 2006-02-15 04:34:33 |
|       18 | DAN         | TORN         | 2006-02-15 04:34:33 |
|       19 | BOB         | FAWCETT      | 2006-02-15 04:34:33 |
|       20 | LUCILLE     | TRACY        | 2006-02-15 04:34:33 |
|       21 | KIRSTEN     | PALTROW      | 2006-02-15 04:34:33 |
|       22 | ELVIS       | MARX         | 2006-02-15 04:34:33 |
|       23 | SANDRA      | KILMER       | 2006-02-15 04:34:33 |
|       24 | CAMERON     | STREEP       | 2006-02-15 04:34:33 |
|       25 | KEVIN       | BLOOM        | 2006-02-15 04:34:33 |
|       26 | RIP         | CRAWFORD     | 2006-02-15 04:34:33 |
|       27 | JULIA       | MCQUEEN      | 2006-02-15 04:34:33 |
|       28 | WOODY       | HOFFMAN      | 2006-02-15 04:34:33 |
|       29 | ALEC        | WAYNE        | 2006-02-15 04:34:33 |
|       30 | SANDRA      | PECK         | 2006-02-15 04:34:33 |
|       31 | SISSY       | SOBIESKI     | 2006-02-15 04:34:33 |
|       32 | TIM         | HACKMAN      | 2006-02-15 04:34:33 |
|       33 | MILLA       | PECK         | 2006-02-15 04:34:33 |
|       34 | AUDREY      | OLIVIER      | 2006-02-15 04:34:33 |
|       35 | JUDY        | DEAN         | 2006-02-15 04:34:33 |
|       36 | BURT        | DUKAKIS      | 2006-02-15 04:34:33 |
|       37 | VAL         | BOLGER       | 2006-02-15 04:34:33 |
|       38 | TOM         | MCKELLEN     | 2006-02-15 04:34:33 |
|       39 | GOLDIE      | BRODY        | 2006-02-15 04:34:33 |
|       40 | JOHNNY      | CAGE         | 2006-02-15 04:34:33 |
|       41 | JODIE       | DEGENERES    | 2006-02-15 04:34:33 |
|       42 | TOM         | MIRANDA      | 2006-02-15 04:34:33 |
|       43 | KIRK        | JOVOVICH     | 2006-02-15 04:34:33 |
|       44 | NICK        | STALLONE     | 2006-02-15 04:34:33 |
|       45 | REESE       | KILMER       | 2006-02-15 04:34:33 |
|       46 | PARKER      | GOLDBERG     | 2006-02-15 04:34:33 |
|       47 | JULIA       | BARRYMORE    | 2006-02-15 04:34:33 |
|       48 | FRANCES     | DAY-LEWIS    | 2006-02-15 04:34:33 |
|       49 | ANNE        | CRONYN       | 2006-02-15 04:34:33 |
|       50 | NATALIE     | HOPKINS      | 2006-02-15 04:34:33 |
|       51 | GARY        | PHOENIX      | 2006-02-15 04:34:33 |
|       52 | CARMEN      | HUNT         | 2006-02-15 04:34:33 |
|       53 | MENA        | TEMPLE       | 2006-02-15 04:34:33 |
|       54 | PENELOPE    | PINKETT      | 2006-02-15 04:34:33 |
|       55 | FAY         | KILMER       | 2006-02-15 04:34:33 |
|       56 | DAN         | HARRIS       | 2006-02-15 04:34:33 |
|       57 | JUDE        | CRUISE       | 2006-02-15 04:34:33 |
|       58 | CHRISTIAN   | AKROYD       | 2006-02-15 04:34:33 |
|       59 | DUSTIN      | TAUTOU       | 2006-02-15 04:34:33 |
|       60 | HENRY       | BERRY        | 2006-02-15 04:34:33 |
|       61 | CHRISTIAN   | NEESON       | 2006-02-15 04:34:33 |
|       62 | JAYNE       | NEESON       | 2006-02-15 04:34:33 |
|       63 | CAMERON     | WRAY         | 2006-02-15 04:34:33 |
|       64 | RAY         | JOHANSSON    | 2006-02-15 04:34:33 |
|       65 | ANGELA      | HUDSON       | 2006-02-15 04:34:33 |
|       66 | MARY        | TANDY        | 2006-02-15 04:34:33 |
|       67 | JESSICA     | BAILEY       | 2006-02-15 04:34:33 |
|       68 | RIP         | WINSLET      | 2006-02-15 04:34:33 |
|       69 | KENNETH     | PALTROW      | 2006-02-15 04:34:33 |
|       70 | MICHELLE    | MCCONAUGHEY  | 2006-02-15 04:34:33 |
|       71 | ADAM        | GRANT        | 2006-02-15 04:34:33 |
|       72 | SEAN        | WILLIAMS     | 2006-02-15 04:34:33 |
|       73 | GARY        | PENN         | 2006-02-15 04:34:33 |
|       74 | MILLA       | KEITEL       | 2006-02-15 04:34:33 |
|       75 | BURT        | POSEY        | 2006-02-15 04:34:33 |
|       76 | ANGELINA    | ASTAIRE      | 2006-02-15 04:34:33 |
|       77 | CARY        | MCCONAUGHEY  | 2006-02-15 04:34:33 |
|       78 | GROUCHO     | SINATRA      | 2006-02-15 04:34:33 |
|       79 | MAE         | HOFFMAN      | 2006-02-15 04:34:33 |
|       80 | RALPH       | CRUZ         | 2006-02-15 04:34:33 |
|       81 | SCARLETT    | DAMON        | 2006-02-15 04:34:33 |
|       82 | WOODY       | JOLIE        | 2006-02-15 04:34:33 |
|       83 | BEN         | WILLIS       | 2006-02-15 04:34:33 |
|       84 | JAMES       | PITT         | 2006-02-15 04:34:33 |
|       85 | MINNIE      | ZELLWEGER    | 2006-02-15 04:34:33 |
|       86 | GREG        | CHAPLIN      | 2006-02-15 04:34:33 |
|       87 | SPENCER     | PECK         | 2006-02-15 04:34:33 |
|       88 | KENNETH     | PESCI        | 2006-02-15 04:34:33 |
|       89 | CHARLIZE    | DENCH        | 2006-02-15 04:34:33 |
|       90 | SEAN        | GUINESS      | 2006-02-15 04:34:33 |
|       91 | CHRISTOPHER | BERRY        | 2006-02-15 04:34:33 |
|       92 | KIRSTEN     | AKROYD       | 2006-02-15 04:34:33 |
|       93 | ELLEN       | PRESLEY      | 2006-02-15 04:34:33 |
|       94 | KENNETH     | TORN         | 2006-02-15 04:34:33 |
|       95 | DARYL       | WAHLBERG     | 2006-02-15 04:34:33 |
|       96 | GENE        | WILLIS       | 2006-02-15 04:34:33 |
|       97 | MEG         | HAWKE        | 2006-02-15 04:34:33 |
|       98 | CHRIS       | BRIDGES      | 2006-02-15 04:34:33 |
|       99 | JIM         | MOSTEL       | 2006-02-15 04:34:33 |
|      100 | SPENCER     | DEPP         | 2006-02-15 04:34:33 |
|      101 | SUSAN       | DAVIS        | 2006-02-15 04:34:33 |
|      102 | WALTER      | TORN         | 2006-02-15 04:34:33 |
|      103 | MATTHEW     | LEIGH        | 2006-02-15 04:34:33 |
|      104 | PENELOPE    | CRONYN       | 2006-02-15 04:34:33 |
|      105 | SIDNEY      | CROWE        | 2006-02-15 04:34:33 |
|      106 | GROUCHO     | DUNST        | 2006-02-15 04:34:33 |
|      107 | GINA        | DEGENERES    | 2006-02-15 04:34:33 |
|      108 | WARREN      | NOLTE        | 2006-02-15 04:34:33 |
|      109 | SYLVESTER   | DERN         | 2006-02-15 04:34:33 |
|      110 | SUSAN       | DAVIS        | 2006-02-15 04:34:33 |
|      111 | CAMERON     | ZELLWEGER    | 2006-02-15 04:34:33 |
|      112 | RUSSELL     | BACALL       | 2006-02-15 04:34:33 |
|      113 | MORGAN      | HOPKINS      | 2006-02-15 04:34:33 |
|      114 | MORGAN      | MCDORMAND    | 2006-02-15 04:34:33 |
|      115 | HARRISON    | BALE         | 2006-02-15 04:34:33 |
|      116 | DAN         | STREEP       | 2006-02-15 04:34:33 |
|      117 | RENEE       | TRACY        | 2006-02-15 04:34:33 |
|      118 | CUBA        | ALLEN        | 2006-02-15 04:34:33 |
|      119 | WARREN      | JACKMAN      | 2006-02-15 04:34:33 |
|      120 | PENELOPE    | MONROE       | 2006-02-15 04:34:33 |
|      121 | LIZA        | BERGMAN      | 2006-02-15 04:34:33 |
|      122 | SALMA       | NOLTE        | 2006-02-15 04:34:33 |
|      123 | JULIANNE    | DENCH        | 2006-02-15 04:34:33 |
|      124 | SCARLETT    | BENING       | 2006-02-15 04:34:33 |
|      125 | ALBERT      | NOLTE        | 2006-02-15 04:34:33 |
|      126 | FRANCES     | TOMEI        | 2006-02-15 04:34:33 |
|      127 | KEVIN       | GARLAND      | 2006-02-15 04:34:33 |
|      128 | CATE        | MCQUEEN      | 2006-02-15 04:34:33 |
|      129 | DARYL       | CRAWFORD     | 2006-02-15 04:34:33 |
|      130 | GRETA       | KEITEL       | 2006-02-15 04:34:33 |
|      131 | JANE        | JACKMAN      | 2006-02-15 04:34:33 |
|      132 | ADAM        | HOPPER       | 2006-02-15 04:34:33 |
|      133 | RICHARD     | PENN         | 2006-02-15 04:34:33 |
|      134 | GENE        | HOPKINS      | 2006-02-15 04:34:33 |
|      135 | RITA        | REYNOLDS     | 2006-02-15 04:34:33 |
|      136 | ED          | MANSFIELD    | 2006-02-15 04:34:33 |
|      137 | MORGAN      | WILLIAMS     | 2006-02-15 04:34:33 |
|      138 | LUCILLE     | DEE          | 2006-02-15 04:34:33 |
|      139 | EWAN        | GOODING      | 2006-02-15 04:34:33 |
|      140 | WHOOPI      | HURT         | 2006-02-15 04:34:33 |
|      141 | CATE        | HARRIS       | 2006-02-15 04:34:33 |
|      142 | JADA        | RYDER        | 2006-02-15 04:34:33 |
|      143 | RIVER       | DEAN         | 2006-02-15 04:34:33 |
|      144 | ANGELA      | WITHERSPOON  | 2006-02-15 04:34:33 |
|      145 | KIM         | ALLEN        | 2006-02-15 04:34:33 |
|      146 | ALBERT      | JOHANSSON    | 2006-02-15 04:34:33 |
|      147 | FAY         | WINSLET      | 2006-02-15 04:34:33 |
|      148 | EMILY       | DEE          | 2006-02-15 04:34:33 |
|      149 | RUSSELL     | TEMPLE       | 2006-02-15 04:34:33 |
|      150 | JAYNE       | NOLTE        | 2006-02-15 04:34:33 |
|      151 | GEOFFREY    | HESTON       | 2006-02-15 04:34:33 |
|      152 | BEN         | HARRIS       | 2006-02-15 04:34:33 |
|      153 | MINNIE      | KILMER       | 2006-02-15 04:34:33 |
|      154 | MERYL       | GIBSON       | 2006-02-15 04:34:33 |
|      155 | IAN         | TANDY        | 2006-02-15 04:34:33 |
|      156 | FAY         | WOOD         | 2006-02-15 04:34:33 |
|      157 | GRETA       | MALDEN       | 2006-02-15 04:34:33 |
|      158 | VIVIEN      | BASINGER     | 2006-02-15 04:34:33 |
|      159 | LAURA       | BRODY        | 2006-02-15 04:34:33 |
|      160 | CHRIS       | DEPP         | 2006-02-15 04:34:33 |
|      161 | HARVEY      | HOPE         | 2006-02-15 04:34:33 |
|      162 | OPRAH       | KILMER       | 2006-02-15 04:34:33 |
|      163 | CHRISTOPHER | WEST         | 2006-02-15 04:34:33 |
|      164 | HUMPHREY    | WILLIS       | 2006-02-15 04:34:33 |
|      165 | AL          | GARLAND      | 2006-02-15 04:34:33 |
|      166 | NICK        | DEGENERES    | 2006-02-15 04:34:33 |
|      167 | LAURENCE    | BULLOCK      | 2006-02-15 04:34:33 |
|      168 | WILL        | WILSON       | 2006-02-15 04:34:33 |
|      169 | KENNETH     | HOFFMAN      | 2006-02-15 04:34:33 |
|      170 | MENA        | HOPPER       | 2006-02-15 04:34:33 |
|      171 | OLYMPIA     | PFEIFFER     | 2006-02-15 04:34:33 |
|      172 | GROUCHO     | WILLIAMS     | 2006-02-15 04:34:33 |
|      173 | ALAN        | DREYFUSS     | 2006-02-15 04:34:33 |
|      174 | MICHAEL     | BENING       | 2006-02-15 04:34:33 |
|      175 | WILLIAM     | HACKMAN      | 2006-02-15 04:34:33 |
|      176 | JON         | CHASE        | 2006-02-15 04:34:33 |
|      177 | GENE        | MCKELLEN     | 2006-02-15 04:34:33 |
|      178 | LISA        | MONROE       | 2006-02-15 04:34:33 |
|      179 | ED          | GUINESS      | 2006-02-15 04:34:33 |
|      180 | JEFF        | SILVERSTONE  | 2006-02-15 04:34:33 |
|      181 | MATTHEW     | CARREY       | 2006-02-15 04:34:33 |
|      182 | DEBBIE      | AKROYD       | 2006-02-15 04:34:33 |
|      183 | RUSSELL     | CLOSE        | 2006-02-15 04:34:33 |
|      184 | HUMPHREY    | GARLAND      | 2006-02-15 04:34:33 |
|      185 | MICHAEL     | BOLGER       | 2006-02-15 04:34:33 |
|      186 | JULIA       | ZELLWEGER    | 2006-02-15 04:34:33 |
|      187 | RENEE       | BALL         | 2006-02-15 04:34:33 |
|      188 | ROCK        | DUKAKIS      | 2006-02-15 04:34:33 |
|      189 | CUBA        | BIRCH        | 2006-02-15 04:34:33 |
|      190 | AUDREY      | BAILEY       | 2006-02-15 04:34:33 |
|      191 | GREGORY     | GOODING      | 2006-02-15 04:34:33 |
|      192 | JOHN        | SUVARI       | 2006-02-15 04:34:33 |
|      193 | BURT        | TEMPLE       | 2006-02-15 04:34:33 |
|      194 | MERYL       | ALLEN        | 2006-02-15 04:34:33 |
|      195 | JAYNE       | SILVERSTONE  | 2006-02-15 04:34:33 |
|      196 | BELA        | WALKEN       | 2006-02-15 04:34:33 |
|      197 | REESE       | WEST         | 2006-02-15 04:34:33 |
|      198 | MARY        | KEITEL       | 2006-02-15 04:34:33 |
|      199 | JULIA       | FAWCETT      | 2006-02-15 04:34:33 |
|      200 | THORA       | TEMPLE       | 2006-02-15 04:34:33 |
+----------+-------------+--------------+---------------------+
200 rows in set (0.01 sec)

mysql> show 10;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near '10' atline 1
mysql> show databases;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| mysql              |
| performance_schema |
| sakila             |
| sys                |
| world              |
+--------------------+
6 rows in set (0.00 sec)

mysql> use world;
Database changed
mysql> select * from world;
ERROR 1146 (42S02): Table 'world.world' doesn't exist
mysql> select * from world;
ERROR 1146 (42S02): Table 'world.world' doesn't exist
mysql> create table promotions(
    -> id int,
    -> name varchar(50)
    -> catagory varchar(15)
    ->
    ->
    ->
    ->
    ->
    ->
    ->
    ->
    ->
    -> );
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'catagory varchar(15)









)' at line 4
mysql> create table promotions(
    -> id int,
    -> name varchar(50)
    -> catagory varchar(15)
    -> );
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'catagory varchar(15)
)' at line 4
mysql> create table promotions(
    -> id int,
    -> name varchar(50),
    -> catagory varchar(15),
    -> );
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near ')' at line 5
mysql> create table promotions(
    -> id int,
    -> name varchar(50),
    -> catagory varchar(15)
    -> );
Query OK, 0 rows affected (0.07 sec)

mysql> show tables
    -> show tables;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'show tables' at line 2
mysql> select * from promotion;
ERROR 1146 (42S02): Table 'world.promotion' doesn't exist
mysql> show tables;
+-----------------+
| Tables_in_world |
+-----------------+
| city            |
| country         |
| countrylanguage |
| promotions      |
+-----------------+
4 rows in set (0.00 sec)

mysql> select * from promotions;
Empty set (0.01 sec)

mysql> describe promotions;
+----------+-------------+------+-----+---------+-------+
| Field    | Type        | Null | Key | Default | Extra |
+----------+-------------+------+-----+---------+-------+
| id       | int         | YES  |     | NULL    |       |
| name     | varchar(50) | YES  |     | NULL    |       |
| catagory | varchar(15) | YES  |     | NULL    |       |
+----------+-------------+------+-----+---------+-------+
3 rows in set (0.02 sec)

mysql> show tables;
+-----------------+
| Tables_in_world |
+-----------------+
| city            |
| country         |
| countrylanguage |
| promotions      |
+-----------------+
4 rows in set (0.00 sec)

mysql> create table inventory(
    -> product int unsigned not null auto_increment,
    -> productCode char(3) not null default '',
    -> name varchar(30) not nulldefault '',
    -> quantity int unsigned not null default 0,
    -> price decimal(7,2) not null default 99999.99),
    -> primary key(productId)
    -> c
    -> C
    -> ^c
    -> );
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'nulldefault '',
quantity int unsigned not null default 0,
price decimal(7,2) not' at line 4
mysql> create table inventory(
    -> product int unsigned not null auto_increment,
    -> productCode char(3) not null default '',
    -> name varchar(30) not nulldefault '',
    -> quantity int unsigned not null default 0,
    -> price decimal(7,2) not null default 99999.99,
    -> primary key(productId)
    -> );
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'nulldefault '',
quantity int unsigned not null default 0,
price decimal(7,2) not' at line 4
mysql> create table inventory(
    -> productID INT UNSIGNED NOT NULL AUTO_INCREMENT,
    -> productCode CHAR(30) NOT NULL DEFAULT '',
    -> name VARCHAR(30) NOT NULL DEFAULT '',
    -> price DECIMAL (7, 2) NOT NULL DEFAULT 99999.99,
    -> PRIMARY KEY(productID)
    -> );
Query OK, 0 rows affected (0.04 sec)

mysql> select * from promotions
    -> select * from promotions;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'select* from promotions' at line 2
mysql> desc inventory
    -> desc inventory;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'desc inventory' at line 2
mysql> show tables;
+-----------------+
| Tables_in_world |
+-----------------+
| city            |
| country         |
| countrylanguage |
| inventory       |
| promotions      |
+-----------------+
5 rows in set (0.00 sec)

mysql> describe inventory;
+-------------+--------------+------+-----+----------+----------------+
| Field       | Type         | Null | Key | Default  | Extra          |
+-------------+--------------+------+-----+----------+----------------+
| productID   | int unsigned | NO   | PRI | NULL     | auto_increment |
| productCode | char(30)     | NO   |     |          |                |
| name        | varchar(30)  | NO   |     |          |                |
| price       | decimal(7,2) | NO   |     | 99999.99 |                |
+-------------+--------------+------+-----+----------+----------------+
4 rows in set (0.01 sec)

mysql> ALTER TABLE PROMOTIONS
    -> ADD PRIMARY KEY(ID):
    -> ALTER TABLE PROMOTIONS
    ->
    -> ADD PRIMARY KEY(ID):R
    -> R
    -> C
    -> );
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near ':
ALTER TABLE PROMOTIONS

ADD PRIMARY KEY(ID):R
R
C
)' at line 2
mysql> describe inventory;
+-------------+--------------+------+-----+----------+----------------+
| Field       | Type         | Null | Key | Default  | Extra          |
+-------------+--------------+------+-----+----------+----------------+
| productID   | int unsigned | NO   | PRI | NULL     | auto_increment |
| productCode | char(30)     | NO   |     |          |                |
| name        | varchar(30)  | NO   |     |          |                |
| price       | decimal(7,2) | NO   |     | 99999.99 |                |
+-------------+--------------+------+-----+----------+----------------+
4 rows in set (0.01 sec)

mysql> ALTER TABLE PROMOTIONS
    -> ADD PRIMARY KEY(id);
Query OK, 0 rows affected (0.07 sec)
Records: 0  Duplicates: 0  Warnings: 0

mysql> describe inventory;
+-------------+--------------+------+-----+----------+----------------+
| Field       | Type         | Null | Key | Default  | Extra          |
+-------------+--------------+------+-----+----------+----------------+
| productID   | int unsigned | NO   | PRI | NULL     | auto_increment |
| productCode | char(30)     | NO   |     |          |                |
| name        | varchar(30)  | NO   |     |          |                |
| price       | decimal(7,2) | NO   |     | 99999.99 |                |
+-------------+--------------+------+-----+----------+----------------+
4 rows in set (0.00 sec)

mysql> insert into inventory VALUES(1001,'PEN','pen red', 5000, 1.23)
    -> insert into inventory VALUES(1001,'PEN','pen red', 5000, 1.23);
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'insertinto inventory VALUES(1001,'PEN','pen red', 5000, 1.23)' at line 2
mysql> insert into inventory VALUES(1001,'PEN','pen red', 5000, 1.23);
ERROR 1136 (21S01): Column count doesn't match value count at row 1
mysql> insert into inventory VALUES(1001,'PEN','pen red', 5000, 1.23);
ERROR 1136 (21S01): Column count doesn't match value count at row 1
mysql> ALTER TABLE PROMOTIONS
    -> ADD PRIMARY KEY(id);
ERROR 1068 (42000): Multiple primary key defined
mysql> discribe inventory;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'discribe inventory' at line 1
mysql> describe inventory;
+-------------+--------------+------+-----+----------+----------------+
| Field       | Type         | Null | Key | Default  | Extra          |
+-------------+--------------+------+-----+----------+----------------+
| productID   | int unsigned | NO   | PRI | NULL     | auto_increment |
| productCode | char(30)     | NO   |     |          |                |
| name        | varchar(30)  | NO   |     |          |                |
| price       | decimal(7,2) | NO   |     | 99999.99 |                |
+-------------+--------------+------+-----+----------+----------------+
4 rows in set (0.00 sec)

mysql> select * from inventory;
Empty set (0.00 sec)

mysql> ADD PRIMARY KEY(id);
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'ADD PRIMARY KEY(id)' at line 1
mysql> ^C
mysql>
mysql> ^C
mysql> show tables;
+-----------------+
| Tables_in_world |
+-----------------+
| city            |
| country         |
| countrylanguage |
| inventory       |
| promotions      |
+-----------------+
5 rows in set (0.00 sec)

mysql> use products;
ERROR 1049 (42000): Unknown database 'products'
mysql> show databases;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| mysql              |
| performance_schema |
| sakila             |
| sys                |
| world              |
+--------------------+
6 rows in set (0.00 sec)

mysql> create database products;
Query OK, 1 row affected (0.01 sec)

mysql> use products;
Database changed
mysql> CREATE TABLE promotions(
    -> create table inventory(
    -> create table inventory(^C
mysql> show databases;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| mysql              |
| performance_schema |
| products           |
| sakila             |
| sys                |
| world              |
+--------------------+
7 rows in set (0.00 sec)

mysql> use products;
Database changed
mysql> create table inventory(
    -> productID INT UNSIGNED NOT NULL AUTO_INCREMENT,
    -> productCode CHAR(30) NOT NULL DEFAULT '',
    -> name VARCHAR(30) NOT NULL DEFAULT '',
    -> price DECIMAL (7, 2) NOT NULL DEFAULT 99999.99,
    -> PRIMARY KEY(productID)
    -> );
Query OK, 0 rows affected (0.03 sec)

mysql> describe inventory;
+-------------+--------------+------+-----+----------+----------------+
| Field       | Type         | Null | Key | Default  | Extra          |
+-------------+--------------+------+-----+----------+----------------+
| productID   | int unsigned | NO   | PRI | NULL     | auto_increment |
| productCode | char(30)     | NO   |     |          |                |
| name        | varchar(30)  | NO   |     |          |                |
| price       | decimal(7,2) | NO   |     | 99999.99 |                |
+-------------+--------------+------+-----+----------+----------------+
4 rows in set (0.01 sec)

mysql> select * from inventory;
Empty set (0.00 sec)

mysql> ALTER TABLE PROMOTIONS
    -> ADD PRIMARY KEY(id);
ERROR 1146 (42S02): Table 'products.promotions' doesn't exist
mysql> select * from products;
ERROR 1146 (42S02): Table 'products.products' doesn't exist
mysql> insert into inventory (productCode, name, quantity, price) VALUES
    -> ('pec','Pencil 2B',10000,0.48),
    -> ('pec','Pencil 2H',8000,0.49);
ERROR 1054 (42S22): Unknown column 'quantity' in 'field list'
mysql> update inventory
    -> quantity INT UNSIGNED NOT NULL DEFAULT'';
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'INT UNSIGNED NOT NULL DEFAULT''' at line 2
mysql> update inventory
    -> quantity INT UNSIGNED NOT NULL DEFAULT 0;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'INT UNSIGNED NOT NULL DEFAULT 0' at line 2
mysql> ALTER TABLE inventory
    -> ADD COLUMN quantity INT UNSIGHED NOT NULL DEFAULT 0;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'UNSIGHED NOT NULL DEFAULT 0' at line 2
mysql> ALTER TABLE inventory
    -> ADD COLUMN quantity INT UNSIGNED NOT NULL DEFAULT 0;
Query OK, 0 rows affected (0.04 sec)
Records: 0  Duplicates: 0  Warnings: 0

mysql> insert into inventory (productCode, name, quantity, price) VALUES
    -> ('pec','Pencil 2B',10000,0.48),
    -> ('pec','Pencil 2H',8000,0.49);
Query OK, 2 rows affected (0.01 sec)
Records: 2  Duplicates: 0  Warnings: 0

mysql> select * from inventory;
+-----------+-------------+-----------+-------+----------+
| productID | productCode | name      | price | quantity |
+-----------+-------------+-----------+-------+----------+
|         1 | pec         | Pencil 2B |  0.48 |    10000 |
|         2 | pec         | Pencil 2H |  0.49 |     8000 |
+-----------+-------------+-----------+-------+----------+
2 rows in set (0.01 sec)

mysql> insert into inventory (productCode, name, quantity, price) VALUES
    -> ('pec','Pencil 2B',10000,0.48),^C
mysql> insert into inventory VALUES(1001,'PEN',Pen Red',5000,1.23);
    '> select * from inventory;
    '> ^C
mysql> select * from inventory;
+-----------+-------------+-----------+-------+----------+
| productID | productCode | name      | price | quantity |
+-----------+-------------+-----------+-------+----------+
|         1 | pec         | Pencil 2B |  0.48 |    10000 |
|         2 | pec         | Pencil 2H |  0.49 |     8000 |
+-----------+-------------+-----------+-------+----------+
2 rows in set (0.00 sec)

mysql> insert into inventory (productCode, name, quantity, price) VALUES
    -> ('pen','Pen Red',5000,1.23),
    -> ('pen','Pen Blue',8000,1.25),
    -> ('pen','Pen Black',2000,1.25);
Query OK, 3 rows affected (0.01 sec)
Records: 3  Duplicates: 0  Warnings: 0

mysql> select * from inventory;
+-----------+-------------+-----------+-------+----------+
| productID | productCode | name      | price | quantity |
+-----------+-------------+-----------+-------+----------+
|         1 | pec         | Pencil 2B |  0.48 |    10000 |
|         2 | pec         | Pencil 2H |  0.49 |     8000 |
|         3 | pen         | Pen Red   |  1.23 |     5000 |
|         4 | pen         | Pen Blue  |  1.25 |     8000 |
|         5 | pen         | Pen Black |  1.25 |     2000 |
+-----------+-------------+-----------+-------+----------+
5 rows in set (0.00 sec)

mysql> SELECT productID, productCode, name, Quantity , Price FROM inventory;
+-----------+-------------+-----------+----------+-------+
| productID | productCode | name      | Quantity | Price |
+-----------+-------------+-----------+----------+-------+
|         1 | pec         | Pencil 2B |    10000 |  0.48 |
|         2 | pec         | Pencil 2H |     8000 |  0.49 |
|         3 | pen         | Pen Red   |     5000 |  1.23 |
|         4 | pen         | Pen Blue  |     8000 |  1.25 |
|         5 | pen         | Pen Black |     2000 |  1.25 |
+-----------+-------------+-----------+----------+-------+
5 rows in set (0.00 sec)

mysql> select * from inventory;
+-----------+-------------+-----------+-------+----------+
| productID | productCode | name      | price | quantity |
+-----------+-------------+-----------+-------+----------+
|         1 | pec         | Pencil 2B |  0.48 |    10000 |
|         2 | pec         | Pencil 2H |  0.49 |     8000 |
|         3 | pen         | Pen Red   |  1.23 |     5000 |
|         4 | pen         | Pen Blue  |  1.25 |     8000 |
|         5 | pen         | Pen Black |  1.25 |     2000 |
+-----------+-------------+-----------+-------+----------+
5 rows in set (0.02 sec)

mysql> where id = 1;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'where id = 1' at line 1
mysql> select * from inventory
    -> where productID = 1;
+-----------+-------------+-----------+-------+----------+
| productID | productCode | name      | price | quantity |
+-----------+-------------+-----------+-------+----------+
|         1 | pec         | Pencil 2B |  0.48 |    10000 |
+-----------+-------------+-----------+-------+----------+
1 row in set (0.02 sec)

mysql> ADD COLUMN ratings INT UNSIGNED NOT NULL DEFAULT 0;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'ADD COLUMN ratings INT UNSIGNED NOT NULL DEFAULT 0' at line 1
mysql> ALTER TABLE inventory
    -> ADD rating int;
Query OK, 0 rows affected (0.08 sec)
Records: 0  Duplicates: 0  Warnings: 0

mysql> describe invintory;
ERROR 1146 (42S02): Table 'products.invintory' doesn't exist
mysql> describe inentory;
ERROR 1146 (42S02): Table 'products.inentory' doesn't exist
mysql> describe inventory;
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
6 rows in set (0.03 sec)

mysql> select * from inventory
    -> rating
    -> ^C
mysql> select * from inventory;
+-----------+-------------+-----------+-------+----------+--------+
| productID | productCode | name      | price | quantity | rating |
+-----------+-------------+-----------+-------+----------+--------+
|         1 | pec         | Pencil 2B |  0.48 |    10000 |   NULL |
|         2 | pec         | Pencil 2H |  0.49 |     8000 |   NULL |
|         3 | pen         | Pen Red   |  1.23 |     5000 |   NULL |
|         4 | pen         | Pen Blue  |  1.25 |     8000 |   NULL |
|         5 | pen         | Pen Black |  1.25 |     2000 |   NULL |
+-----------+-------------+-----------+-------+----------+--------+
5 rows in set (0.00 sec)

mysql> update inventory SET rating=8 where name='pen Red'
    ->
    -> ^C
mysql> update inventory SET rating=8 WHERE name='pen Red'
    -> select * from inventory;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'select* from inventory' at line 2
mysql> select * from inventory;
+-----------+-------------+-----------+-------+----------+--------+
| productID | productCode | name      | price | quantity | rating |
+-----------+-------------+-----------+-------+----------+--------+
|         1 | pec         | Pencil 2B |  0.48 |    10000 |   NULL |
|         2 | pec         | Pencil 2H |  0.49 |     8000 |   NULL |
|         3 | pen         | Pen Red   |  1.23 |     5000 |   NULL |
|         4 | pen         | Pen Blue  |  1.25 |     8000 |   NULL |
|         5 | pen         | Pen Black |  1.25 |     2000 |   NULL |
+-----------+-------------+-----------+-------+----------+--------+
5 rows in set (0.00 sec)

mysql> update inventory SET rating=8 where name='pen Red';
Query OK, 1 row affected (0.02 sec)
Rows matched: 1  Changed: 1  Warnings: 0

mysql> update inventory SET rating=5 where name='pen Blue';
Query OK, 1 row affected (0.01 sec)
Rows matched: 1  Changed: 1  Warnings: 0

mysql> select * from inventory;
+-----------+-------------+-----------+-------+----------+--------+
| productID | productCode | name      | price | quantity | rating |
+-----------+-------------+-----------+-------+----------+--------+
|         1 | pec         | Pencil 2B |  0.48 |    10000 |   NULL |
|         2 | pec         | Pencil 2H |  0.49 |     8000 |   NULL |
|         3 | pen         | Pen Red   |  1.23 |     5000 |      8 |
|         4 | pen         | Pen Blue  |  1.25 |     8000 |      5 |
|         5 | pen         | Pen Black |  1.25 |     2000 |   NULL |
+-----------+-------------+-----------+-------+----------+--------+
5 rows in set (0.00 sec)

mysql> select name,price from inventory;
+-----------+-------+
| name      | price |
+-----------+-------+
| Pencil 2B |  0.48 |
| Pencil 2H |  0.49 |
| Pen Red   |  1.23 |
| Pen Blue  |  1.25 |
| Pen Black |  1.25 |
+-----------+-------+
5 rows in set (0.00 sec)

mysql> select * from inventory where productID>3;
+-----------+-------------+-----------+-------+----------+--------+
| productID | productCode | name      | price | quantity | rating |
+-----------+-------------+-----------+-------+----------+--------+
|         4 | pen         | Pen Blue  |  1.25 |     8000 |      5 |
|         5 | pen         | Pen Black |  1.25 |     2000 |   NULL |
+-----------+-------------+-----------+-------+----------+--------+
2 rows in set (0.01 sec)

mysql> select name,quantity from inventory Where name='Pen Black'; ;
+-----------+----------+
| name      | quantity |
+-----------+----------+
| Pen Black |     2000 |
+-----------+----------+
1 row in set (0.00 sec)

ERROR:
No query specified

mysql> select name,price from inventory Where name like 'Pencil%'; ;
+-----------+-------+
| name      | price |
+-----------+-------+
| Pencil 2B |  0.48 |
| Pencil 2H |  0.49 |
+-----------+-------+
2 rows in set (0.01 sec)

ERROR:
No query specified

mysql> select name,price from inventory Where name like 'Pencil%';
+-----------+-------+
| name      | price |
+-----------+-------+
| Pencil 2B |  0.48 |
| Pencil 2H |  0.49 |
+-----------+-------+
2 rows in set (0.00 sec)

mysql> select name,price from inventory Where name like 'P%_';
+-----------+-------+
| name      | price |
+-----------+-------+
| Pencil 2B |  0.48 |
| Pencil 2H |  0.49 |
| Pen Red   |  1.23 |
| Pen Blue  |  1.25 |
| Pen Black |  1.25 |
+-----------+-------+
5 rows in set (0.01 sec)

mysql> select name,price from inventory Where name like 'P%_';
+-----------+-------+
| name      | price |
+-----------+-------+
| Pencil 2B |  0.48 |
| Pencil 2H |  0.49 |
| Pen Red   |  1.23 |
| Pen Blue  |  1.25 |
| Pen Black |  1.25 |
+-----------+-------+
5 rows in set (0.00 sec)

mysql> select name,price from inventory Where name like 'P__%';
+-----------+-------+
| name      | price |
+-----------+-------+
| Pencil 2B |  0.48 |
| Pencil 2H |  0.49 |
| Pen Red   |  1.23 |
| Pen Blue  |  1.25 |
| Pen Black |  1.25 |
+-----------+-------+
5 rows in set (0.00 sec)

mysql> select name,price from inventory Where name like 'P__ %';
+-----------+-------+
| name      | price |
+-----------+-------+
| Pen Red   |  1.23 |
| Pen Blue  |  1.25 |
| Pen Black |  1.25 |
+-----------+-------+
3 rows in set (0.00 sec)

mysql> select * from inventory where quantity>=5000,Where name like pen%;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near ',Wherename like pen%' at line 1
mysql> select * from inventory where quantity>=5000,Where name like 'pen%';
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near ',Wherename like 'pen%'' at line 1
mysql> select * from inventory where (price between1.0 and 2.0) and (quantity between 1000 and 2000);
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'between1.0 and 2.0) and (quantity between 1000 and 2000)' at line 1
mysql> select * from inventory where (price between 1.0 and 2.0) and (quan
tity between 1000 and 2000);
+-----------+-------------+-----------+-------+----------+--------+
| productID | productCode | name      | price | quantity | rating |
+-----------+-------------+-----------+-------+----------+--------+
|         5 | pen         | Pen Black |  1.25 |     2000 |   NULL |
+-----------+-------------+-----------+-------+----------+--------+
1 row in set (0.01 sec)

mysql> select * from inventory where productCode like 'Pen %' ORDER by pri
ce DESC;
Empty set (0.00 sec)

mysql> select * from inventory where productCode like 'Pen %' ORDER by price DESC;
Empty set (0.00 sec)

mysql> select AVG(PRICE);
ERROR 1054 (42S22): Unknown column 'PRICE' in 'field list'
mysql> select AVG(PRICE) from inventory;
+------------+
| AVG(PRICE) |
+------------+
|   0.940000 |
+------------+
1 row in set (0.01 sec)

mysql> select sum(quantity) from inventory;
+---------------+
| sum(quantity) |
+---------------+
|         33000 |
+---------------+
1 row in set (0.00 sec)

mysql> select productcode. sum(quantiry)
    -> from inventory
    -> group by productCode;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'sum(quantiry)
from inventory
group by productCode' at line 1
mysql> select productCode. sum(quantiry)
    -> FROM inventory
    -> group by productCode;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'sum(quantiry)
FROM inventory
group by productCode' at line 1
mysql> select productcode. count(quantity) FROM group by productCode;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'count(quantity) FROM group by productCode' at line 1
mysql> select productcode. count(*) FROM inventry group by productCode;
ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'count(*) FROM inventry group by productCode' at line 1
mysql> SELECT productcode, count(*) FROM inventry group by productCode;
ERROR 1146 (42S02): Table 'products.inventry' doesn't exist
mysql> SELECT productcode, count(*) FROM inventory group by productCode;
+-------------+----------+
| productcode | count(*) |
+-------------+----------+
| pec         |        2 |
| pen         |        3 |
+-------------+----------+
2 rows in set (0.01 sec)

mysql> drop table promotions;
ERROR 1051 (42S02): Unknown table 'products.promotions'
mysql> show tables;
+--------------------+
| Tables_in_products |
+--------------------+
| inventory          |
+--------------------+
1 row in set (0.03 sec)

mysql> create TABLE promotions(
    -> id int PRIMARY KEY,
    -> inventory_productID int,
    -> REFERENCES inventory(productID),
    -> name varchar(50),
    -> category  varchar(15)
    -> );
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

mysql>
Line Client.txt…]()

