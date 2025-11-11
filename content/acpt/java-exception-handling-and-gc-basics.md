---
title: Java Exception Handling And Gc Basics
---

**Java Exception handling**

Computer programme ekk problems 2 ekt katendw

1.  **Error** eg: stack overflow-raw eke memoey eka madi,syntax error-spelling error,out of memory-ram ekk upgrade krnn oni.(developer t fix krnn bh)

2.  **Exception eg:** arithmetic exepection ,number format exception,nullformat exception,filenot found,

> Exception 2 parts,
- Run time exception
- Compile time exception

Expection ekk handle krnn widi 1 thiyenne.

Expection wala bad side eka thamai application eka crash karawana eka .(exception eken passe program eka stop wenw)

Compile time ekk nm expection eka kalinm hoyagann puluwn.

Run time ekk hoygnn amarui,runn weddi thmi enne

How to handle arithmetic exception,

Expection ekk handle krnn try catch block ekk use krnn puluwn.

1.  Arithmetic exception

![image1](/media/image1.png)

![image2](/media/image2.png)

2.  Array index is out of bounds

![image3](/media/image3.jpeg)

3.  Number format Exception

4.  Null point exception

5.  File not found error

```java
arithmetic reference variable ekt super class reference variable eka danna puluwn…(Exception).super type reference variable ekkt sub time object ekk assign krnn puluwn.
```

Apita expections types deck handle krnn awoth,

```java
Super class eka danna.
```

![image4](/media/image4.jpeg)

Catch blocks 2 danna.

![image5](/media/image5.tmp)

Eka ma catch bock eke or operator eka dala krnn puluwn.

![image6](/media/image6.tmp)

Trows =main method eke eliye method ekk hadala eka main eke call krddi expeceoption handle krnn oni method eke throws keyword eka use krl

Eg:

Public Static void dance() throws NumberFormatException{

String name=”kk”;

Int num =Integer.parse(name)

}

![image7](/media/image7.tmp)

Trows =eka method ekkin thawa method ekt expection eka parse krnw

Trow=exeption ekk balen athi krnwnw

![image8](/media/image8.jpeg)

Finally{}

Apita aniwaren run wenna oni line ekk oni nm Finally block eka danna puluwn.

Try ekt giyth nathth ,

Catch ekt gith nathath,

Finally block athule thoyana eka run wenw

![image9](/media/image9.tmp)

Apita Expection ekk danna oni wunama,

![image10](/media/image10.tmp)

![image11](/media/image11.tmp)

Non reference objects clean krnn-garbage collector ekk thiynw thiynw jvm eke

**Garbage collector**

```java
Student student =new Student();
```

Student=null;

Object eka thani wela garbage collector eka eka clear krnw.

Garbage nicn ma awilla object eka clean krnne .

Java 7 8 version wala meka api danna oni ----System.gc();

Java 17 dn updated version wala meka danna oni na

**Package(folder)**




Finalize

```java
Object class eke finalize override method ekk dnn puluwn.
```

Garbage collector elligle object eke(non reference object eka)final task eka krnnn oni nm finalize method eka use krnn puluwn.

Final key word eka krnn.

String

![image12](/media/image12.tmp)

Ram eke application ekk run wenn ida hadagnnw.eh ida 2 bedenw stack ekai heap ekai.

Heap eke special cotasak have ekt kiynw String constant pool kiynw.

Literal based string ekk haduwth String name=”yasindu”.

Meke string name save wenne stack eke “yasindu ” kiyna eka save wenw string constant pool ekeeke id eka store wenw name kiyana eke.

Object based string

```java
String name2 = new String(“pasindu”);---meka set na mkd meke wadipura object ekk hadenw=a nisa
```

Mekedi stack eke string name2 kiyana eka save wenw.new keyword eka nisa obect ekk hadenw ita passe value eka yanawa string constant pool ekt.object eke id eka stack reference variable eke save wenw.ara value eke id eka aluth object eke variable ekt assign wenw. ![image13](/media/image13.jpeg)

String methods.

![image14](/media/image14.jpeg)

```
Why String Immutable =const pool eke value reference variable kipayakata link wenna puluwn.eh nisa string wenas wiya nohaki.
```

**Eg.string name5 =rumesh;**

```java
**System.out.print(name5);**
```

**Name5.concat(“sathsara”);**

```java
**System.out.print(name5);**
```

Meke output eka wenas wenne na concat kra kiyala mkd string wenas wenne na.

Habay,
- string concate krnn puluwn. Concate weddi pool eke value eka wenas wenne na.dynamically nicn watenw witharai.

![image15](/media/image15.tmp)

String ekk wenuwata String builder or String buffer danna puluwn.

![image16](/media/image16.tmp)

String builder, string buffer(mutable)---kisima welwk pool eka consume krnn na()

> String builder ekei string ekei wenasa = string immutable string builder eka mutable.

```java
Yam class ekkt char sequence eka implement krl thiynw character array ekk store krnn puluwn.
```

Final- key word

Variable re initialize krnn bh.

Final keyword eka method ekk danna puluwn.final method ekk override krnn bh

```java
Final class ekk extend krnnh bh.
```

Finally- try catch block ekt giya ho nathi finally wenna kiyala

Finalize –

```java
Object class eke finalize override method ekk dnn puluwn.
```

Garbage collector elligle object eke(non reference object eka)final task eka krnnn oni nm finalize method eka use krnn puluwn.
