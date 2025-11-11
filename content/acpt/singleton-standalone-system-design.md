---
title: Singleton Standalone System Design
---

stand alone system = thani db

meka fail wenw wela enterprise level application

java ee hadenne web based application ekk.

API - data request krl aye gannawa

data bases kipayak use krl application ekkt kiynw database connection pool.

**StandAlone system making**

Object hadana eka stop krnw default constructor eka private krl.

Static Reference variable ekk dala method ekk hadagannawa.

Then 1 object ekk withrk hadanawa,

```java
Static method ekk hadagannawa get db connection kiyala.static krnne class eke naming ma call krnnh
```

Ita passe reference variable eka null num new object ekk hadagannw.

Then return krnw.

Meka call krddi palweni para withraia object eka hadenne.

Ilaga eke idn asame ip eka repeat wenw.

![image1](/media/image1.png)

Java fx jdk eke nna ekh krnne java FX organization ekk

Meke libraries have

Open jfx

Object eka hadana ekh stop krl eka eka parak withrk hadala eka reuse krn ekt kiynw singleton design pattern

Data base transaction – eka button ekkin tables gdk wenas wena ekk.
