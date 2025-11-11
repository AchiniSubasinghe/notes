---
title: java-note-15
---

Scene ekk hadenna FXML file ekai Controller ekai dekama thiyenna oni.

Eh scene eke user gen ganna data tike functionality dewl krnne service layer eke.

Controller eke idn service ekata data yawanna DTO eka use krnw.

```java
Service layer eke apita full code eka danna bh eh nisa api abstraction kiyala oop concept eka use krnw.ekata Interface and impl class ekk use krnw implement krl.
```

Meka eka software ekk.

---------------------------------------------------------------------------------------------------------------------

Database(mysql) eka wena software ekk.

Sevice ekai my sql ekai connect krnn JDBC eka use krnw.

JDBC= java database connector

![image1](/media/image1.png)

Mysql eka connect krn steps 4 have,

1.  Load the connector

Meaven repo eka gihin mysql connector eka copy krl aran pom.xml eke danna oni

2.  Create a connection with DB server and database

![image2](/media/image2.png)

3.  Ready the query

![image3](/media/image3.jpeg)

4.  Execute the query

![image4](/media/image4.jpeg)

Ape sw eke idan db ekata------ insert, delete,update ----------execute update() return int

Return -1 if false return positive number if true

![image5](/media/image5.tmp)

DB eke idn sw ekata ---- search,getall----Execute Query() ---resultset

Search eke ---if ekai ekak gann nisa.

Get all eke ---while ekk use krnw gdk ganna nisa.

![image6](/media/image6.tmp)

![image7](/media/image7.tmp)

**Data yana widiha**

![image8](/media/image8.jpeg)
