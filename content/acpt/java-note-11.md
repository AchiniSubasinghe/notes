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

<u>Types of Exception</u>

1.  **Arithmetic Exception**

<img src="media/media/image1.tmp" style="width:6.5in;height:1.375in" />

Handling part

<img src="media/media/image2.tmp" style="width:4.93819in;height:3.08376in" />

Output

<img src="media/media/image3.tmp" style="width:2.04195in;height:1.59397in" />

2.  **Number Format Exception**

<img src="media/media/image4.tmp" style="width:6.5in;height:1.11111in" />

Handling part

<img src="media/media/image5.tmp" style="width:5.90707in;height:2.60453in" />

Output

<img src="media/media/image6.tmp" style="width:3.25045in;height:1.34394in" />

3.  **Array index out of bound exception**

<img src="media/media/image7.tmp" style="width:6.5in;height:0.97986in" />

Handling part

<img src="media/media/image8.tmp" style="width:6.04251in;height:2.14613in" />

Output

<img src="media/media/image9.tmp" style="width:3.71927in;height:0.91679in" />

4.  **Null Format Exception**

<img src="media/media/image10.tmp" style="width:6.5in;height:0.87778in" />

Handling

<img src="media/media/image11.tmp" style="width:5.8654in;height:1.90652in" />

Output

5.  **File Not Found Exception**

<span class="mark">Arithmetic reference variable ekakata super class reference variable eka danna puluwn…(Exception).Super type reference variable ekkt sub time object ekk assign krnn puluwn.</span>

Exceptions types 2 handle karanna awoth,

1.  Super class eka danna puluwn

> <img src="media/media/image12.tmp" style="width:4.83401in;height:1.87526in" />

2.  Catch blocks 2 danna puluwn

> <img src="media/media/image13.tmp" style="width:4.45896in;height:2.19822in" />

3.  Ekama catch block eke OR operator eka dala krnn puluwn

> <img src="media/media/image14.tmp" style="width:4.80275in;height:1.64606in" />

**<u>Method Exception Handling</u>**

Main method eke eliye method ekk hadala eka main eke call krddi exception handle krnn oni method ekt throws kiyana keyword eka use krnn puluwn.

**Trows** =eka method ekkin thawa method ekt expection eka parse krnw

Eg:

Public Static void dance() throws NumberFormatException{

String name=”kk”;

Int num =Integer.parse(name)

}

<img src="media/media/image15.tmp" style="width:5.82373in;height:4.01098in" />

**Trow** =Apita Exception ekk balen athi karanna oni wunama

<img src="media/media/image16.tmp" style="width:3.22962in;height:1.60439in" />

**<u>Aluthen Exception ekk danna oni wunama</u>**

Class ekk hadala eka extend karanna oni exception class ekat(super class)-eete passe athule constructor eka hadala message ekk pass krnn one super keyword eka use krl.

<img src="media/media/image17.tmp" style="width:5.57369in;height:3.30254in" />

**<u>Finally {}</u>**

Try block ekata giyath naththnm,catch block ekata giyath nathath Finally block eka athule thiyana eka run wenawa.

<img src="media/media/image18.tmp" style="width:4.4277in;height:2.28157in" />

**Garbage Collector**

Jvm eke thiyana Non-Reference objects clean karanawa.

Student s = new Student ();

S =null;

- Java 7 8 version wala meka api danna oni mkd ewa slow ----System.gc();

- Java 17 dn updated version wala meka danna oni na

**Stand Package convention(Folder)**

lk.acpt -Adala software eka hadana company site eke reverse eka

**Finalize**

Non-Reference object eka heap eken garbage collector eka clean karanna kalin eke finally output ekk ganna oni nm.

Object class eke finalize override method ekk dnn puluwn.

<img src="media/media/image19.tmp" style="width:4.79234in;height:2.55244in" />

**String**

- Character array ekk

- String widi dekakata liyanna pulluwn,

1.  **Literal Based**

2.  **Object based**

> <img src="media/media/image20.tmp" style="width:4.56314in;height:2.75038in" />

Ram eke application ekk run wenn ida hadagnnw.Eh ida 2 bedenw **Stack** ekai **Heap** ekai.

Heap eke special part ekk thiyana wa ekata kiyanawa **String Constant pool**.

- Literal based string ekk haduwoth eg**. String name=”yasindu” kiyala.**

- Meke string name save wenne stack eke .

- “yasindu ” kiyna eka save wenw string constant pool eke.

- eke id eka store wenw name kiyana referenece variable eke eke.

- Eka ma value eka thibbth **String name2=”yasindu**” kiyala. Hby constant pool eke aye yasindu kiyala value ekk hadenne na.kalin eke id ekm araka assign wenw echcharai.

- Object based string ekk haduwoth eg. **String name2 = new String(“pasindu”) ;**

(aththatama meka set na mkd meke wadipura object ekk hadenw=a nisa)

- Mekedi stack eke string name2 kiyana eka save wenw.

- New keyword eka nisa object ekk hadenw

- Ita passe pasindu kiyana value eka yanawa string constant pool ekt.

- object eke id eka stack reference variable eke save wenw.

- Ara value eke id eka aluth object eke variable ekt assign wenw.

**Copied from wasana akka**

meekedi kalin wagee reference variable ek stack ekee store wenwa Hebei new key word ek nisa pool ekn pita heap ek athule new object ekk hedenwa…ekt String pool ekee value ekn hmba wena unique address ek hmba wenwa ..a hedena object ek eta passe stack ekee reference variable ekt link wenwa.-----use krnne neee(anwashya object ekk hedena nisa ----redundant )

<img src="media/media/image21.tmp" style="width:6.24045in;height:3.78178in" />

**String Methods**

<img src="media/media/image22.tmp" style="width:6.34464in;height:2.78164in" />

**Why String Immutable (never change or cannot be changed)**

String const pool eke value reference variable kipayakata link wenna puluwn. Ethkot api pool ekee string ekk value ekk wens karoth ara reference variable seertm balapaana nisa string wenas wiya nohaki.

<img src="media/media/image23.tmp" style="width:5.80289in;height:1.11474in" />

**Concat**

<img src="media/media/image24.tmp" style="width:3.20878in;height:1.02098in" />

Meke output eka wenas wenne na concat kra kiyala mkd string wenas wenne na.

Habay,

- string concate krnn puluwn. Concate weddi pool eke value eka wenas wenne na.dynamically nicn watenw witharai.

<img src="media/media/image25.tmp" style="width:4.34436in;height:2.67746in" />

- String buffer builder and builder append wenw.

<img src="media/media/image26.tmp" style="width:4.53188in;height:4.02139in" />

\*\*String immutable

\*\*StringBuffer and StringBuilder – mutable ( wens krnna puluwn --- append use karala )

String builder, string buffer(mutable)---kisima welwk pool eka consume krnn na()

> String builder ekei string ekei wenasa = string immutable string builder eka mutable.

Yam class ekkt char sequence eka implement krl thiynw character array ekk store krnn puluwn.

**Final keyword**

- Re-assign karanna bh.

- Variable re initialize krnn bh.

- Final keyword eka method ekk danna puluwn.final method ekk override krnn bh

- Final class ekk extend krnnh bh.

**Finally**

- try- catch block ekee try catch ek athult giya hoo netha end ekee krnna ona ekk krnna puluwn.(Scanner ek close krnna puluwn.)

**Finalize**

- Object class eke finalize override method ekk dnn puluwn.

- Garbage collector elligle object eke(non reference object eka)final task eka krnnn oni nm finalize method eka use krnn puluwn.
