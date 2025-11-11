---
title: Generic
---

**Wrapper class**

```java
Primitive data type 8 ta Wrapper class 8 have,
```

1.  byte =Byte

2.  short =Short

3.  int =Integer

4.  long=Long

5.  float=Float

6.  double=Double

7.  char=Character

8.  boolean=Boolean

Eg:

![image1](/media/image1.png)

![image2](/media/image2.png)

**Boxing**

```java
wrapper class reference variable ekkt primitive data type value ekk dana ekt kiyanawa -boxing kiyala
```

**Unboxing**

```java
Primitive data type reference variable ekkt class wrapper class value ekk dana ekt kiyanawa -unboxing kiyala
```

![image3](/media/image3.jpeg)

**String conversion to integer and double**

![image4](/media/image4.jpeg)

**Collection Frameworks and Generics**

Java wala Array ekk haduwama eke limits deck thiynw,

1.  Type Specific

2.  Fix length

> ![image5](/media/image5.tmp)
>
```java
> Mekata solution ekk widihata Array list kiyana class eka java.util eke thiyanawa.
```
>
> Mekata onima type eke data ekk danna puluwn.
>
> ![image6](/media/image6.tmp)
>

# Generic
- Generic kiyanne compile time type safety mechanism ekk
- Default generic data type eka =object
- Generic krnne nathuwa default nm thiyenne oni data type ekk danna puluwn.

> ![image7](/media/image7.tmp)
>
> **HashSet**
- Hash set ektath generic krnn puluwn.
- Meke duplicate value ain krnw
- Eyata galapena piliwelak hadagannawa
- Meke result ekk widihata get method na
- Reason duplicate values ain krl eyage order ekkt eya indexex hadagann nisa.

> ![image8](/media/image8.jpeg)
>
> ![image9](/media/image9.tmp)
>
> **Priority Queue**
>
> Meka ascending order ekata yanne (aaarohana -podi sita loku).
>
> Meka hariyata wada karanne na
>
> ![image10](/media/image10.tmp)
>
> ![image11](/media/image11.tmp)
>
> **Hash Map**
>
> Meke( key, value) widihata yanne.
>
> Meke det method ekk have ,get krddi index eka nemei denne key eka
>
> Add wenuwata Put method eka thiyenne
>
> ![image12](/media/image12.tmp)

Collection frame work Class 5,

1.  Array list (class) -list(interface)

2.  Hash set-set(interface)

3.  Priority queue-queue(interface)

4.  HashMap-map(interface)

> GUI hadanna thiyenne – java FX
>
> Jdk eke nathi ewa danna oni 3 rd party depts(dependacies) denna oni ,
>
> Meka krnn puluwn widi 3,

1.  Download krl manualy

2.  Mevan

3.  Gradle

```java
> Build tools = user ta eka file ekkt hadala dena ekata meka udau wenw(executable file ekk user ta hadala dena eka) class okkm technically build krl final architecture ekk hanna ganna eka
```
>
> Meka karran thiyana tools,

1.  Apache Ant ---paranama build tool eka

2.  Mevan

3.  Gradle

> Eg. For using 3<sup>rd</sup> party dependancies
>
> Projects connector eking mysqul ekk connect krnw.
>
> **Apache ant eka manually apply krn widiha**
>
> Mvn repository—mysql connector/j eka download krl---hamburger option ekt gihin—project structure—libraries walata gihin------dowload file eka apply krnn oni.
>
- Pawichchi krn build tool ant eka nm download krl manually krnn oni
- Pawichchi krn build tool eka Mevan or Gradle nm athulema 3<sup>rd</sup> party dependency builder kenek innw.eka manuallay download krl krnn oni na

> ![image13](/media/image13.jpeg)
>
> JDK eke Java Fx eka ,java 8 version eka wenakan awith thiyenne.
>
> Java 11 eke idn java Fxkalla halala damma.
>
> Eh halapu eka JavaFX eka wena organization ekk aran build krl .meka dn jdk athule na .3<sup>rd</sup> party software ekk widihata aran aplly kraganna onia ra krama 3 kamathi widihatakata.
>
> **Java Fx**
>
> Scene ekk hadanna file 2 hadanna oni,

1.  FXML

2.  Java Controller

> Fxml ui controller ekai ekathu wela thamai scene ekk hadenne
>
> Stage eke eka scene ekk run wela eka ain wela wena scene ekk run wenna puluwn.
>
> ![image14](/media/image14.jpeg)

Apita scene ekk hadanna puluwn,

fxml

![image15](/media/image15.tmp)

Controller

![image16](/media/image16.tmp)

![image17](/media/image17.tmp)

Application![image18](/media/image18.tmp)

**Scene builder**


Text input -id

Button -on action

Assignment

Save = mekata array list ekk danna oni oe hash map ekk ganna puluwn

Delete =remove(int index)

Mysql ---cli

---gli
