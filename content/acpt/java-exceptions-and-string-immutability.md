---
title: Java Exceptions And String Immutability
---

***Exception Handling***

Computer program ekaka problems dekakata kadenna puluwn,

1.  **Errors**: Developer ta handle karanna bari dewal

Ex.: syntax errors(spelling errors)

> Stack overflow

2.  **Exception:** Devoloper ta handle karanna puluwan dewal

Ex:. Arithmatic exception

Array index out of bound exception

Number format exception

Nullformat exception

File not found

**:**Exceptions types 2,

1.  Run time Exception

2.  Compile Time Exception

:Exception Handle karanna Try Catch Block ekk use krnn puluwn

:Exception eka handle kare nathnm program eka crash wenawa

# Types of Exception

1.  **Arithmetic Exception**

![image1](/media/image1.png)

Handling part

![image2](/media/image2.png)

Output

![image3](/media/image3.jpeg)

2.  **Number Format Exception**

![image4](/media/image4.jpeg)

Handling part

![image5](/media/image5.tmp)

Output

![image6](/media/image6.tmp)

3.  **Array index out of bound exception**

![image7](/media/image7.tmp)

Handling part

![image8](/media/image8.jpeg)

Output

![image9](/media/image9.tmp)

4.  **Null Format Exception**

![image10](/media/image10.tmp)

Handling

![image11](/media/image11.tmp)

Output

5.  **File Not Found Exception**

```java
<span class="mark">Arithmetic reference variable ekakata super class reference variable eka danna puluwn…(Exception).Super type reference variable ekkt sub time object ekk assign krnn puluwn.</span>
```

Exceptions types 2 handle karanna awoth,


> ![image12](/media/image12.tmp)

2.  Catch blocks 2 danna puluwn

> ![image13](/media/image13.jpeg)

3.  Ekama catch block eke OR operator eka dala krnn puluwn

> ![image14](/media/image14.jpeg)

## Method Exception Handling

Main method eke eliye method ekk hadala eka main eke call krddi exception handle krnn oni method ekt throws kiyana keyword eka use krnn puluwn.

**Trows** =eka method ekkin thawa method ekt expection eka parse krnw

Eg:

Public Static void dance() throws NumberFormatException{

String name=”kk”;

Int num =Integer.parse(name)

}

![image15](/media/image15.tmp)

**Trow** =Apita Exception ekk balen athi karanna oni wunama

![image16](/media/image16.tmp)

## Aluthen Exception ekk danna oni wunama

```java
Class ekk hadala eka extend karanna oni exception class ekat(super class)-eete passe athule constructor eka hadala message ekk pass krnn one super keyword eka use krl.
```

![image17](/media/image17.tmp)

## Finally {}

Try block ekata giyath naththnm,catch block ekata giyath nathath Finally block eka athule thiyana eka run wenawa.

![image18](/media/image18.tmp)

**Garbage Collector**

Jvm eke thiyana Non-Reference objects clean karanawa.

```java
Student s = new Student ();
```

S =null;
- Java 7 8 version wala meka api danna oni mkd ewa slow ----System.gc();
- Java 17 dn updated version wala meka danna oni na

**Stand Package convention(Folder)**

lk.acpt -Adala software eka hadana company site eke reverse eka

**Finalize**

Non-Reference object eka heap eken garbage collector eka clean karanna kalin eke finally output ekk ganna oni nm.

```java
Object class eke finalize override method ekk dnn puluwn.
```

![image19](/media/image19.tmp)

**String**
- Character array ekk
- String widi dekakata liyanna pulluwn,

1.  **Literal Based**

2.  **Object based**

> ![image20](/media/image20.tmp)

Ram eke application ekk run wenn ida hadagnnw.Eh ida 2 bedenw **Stack** ekai **Heap** ekai.

Heap eke special part ekk thiyana wa ekata kiyanawa **String Constant pool**.
- Literal based string ekk haduwoth eg**. String name=”yasindu” kiyala.**
- Meke string name save wenne stack eke .
- “yasindu ” kiyna eka save wenw string constant pool eke.
- eke id eka store wenw name kiyana referenece variable eke eke.
- Eka ma value eka thibbth **String name2=”yasindu**” kiyala. Hby constant pool eke aye yasindu kiyala value ekk hadenne na.kalin eke id ekm araka assign wenw echcharai.

(aththatama meka set na mkd meke wadipura object ekk hadenw=a nisa)
- Mekedi stack eke string name2 kiyana eka save wenw.
- New keyword eka nisa object ekk hadenw
- Ita passe pasindu kiyana value eka yanawa string constant pool ekt.
- object eke id eka stack reference variable eke save wenw.
- Ara value eke id eka aluth object eke variable ekt assign wenw.

**Copied from wasana akka**

meekedi kalin wagee reference variable ek stack ekee store wenwa Hebei new key word ek nisa pool ekn pita heap ek athule new object ekk hedenwa…ekt String pool ekee value ekn hmba wena unique address ek hmba wenwa ..a hedena object ek eta passe stack ekee reference variable ekt link wenwa.-----use krnne neee(anwashya object ekk hedena nisa ----redundant )

![image21](/media/image21.tmp)

**String Methods**

![image22](/media/image22.tmp)

**Why String Immutable (never change or cannot be changed)**

```
String const pool eke value reference variable kipayakata link wenna puluwn. Ethkot api pool ekee string ekk value ekk wens karoth ara reference variable seertm balapaana nisa string wenas wiya nohaki.
```

![image23](/media/image23.tmp)

**Concat**

![image24](/media/image24.tmp)

Meke output eka wenas wenne na concat kra kiyala mkd string wenas wenne na.

Habay,
- string concate krnn puluwn. Concate weddi pool eke value eka wenas wenne na.dynamically nicn watenw witharai.

![image25](/media/image25.tmp)
- String buffer builder and builder append wenw.

![image26](/media/image26.tmp)

\*\*String immutable

\*\*StringBuffer and StringBuilder – mutable ( wens krnna puluwn --- append use karala )

String builder, string buffer(mutable)---kisima welwk pool eka consume krnn na()

> String builder ekei string ekei wenasa = string immutable string builder eka mutable.

```java
Yam class ekkt char sequence eka implement krl thiynw character array ekk store krnn puluwn.
```

**Final keyword**
- Re-assign karanna bh.
- Variable re initialize krnn bh.
- Final keyword eka method ekk danna puluwn.final method ekk override krnn bh

**Finally**
- try- catch block ekee try catch ek athult giya hoo netha end ekee krnna ona ekk krnna puluwn.(Scanner ek close krnna puluwn.)

**Finalize**
- Garbage collector elligle object eke(non reference object eka)final task eka krnnn oni nm finalize method eka use krnn puluwn.
