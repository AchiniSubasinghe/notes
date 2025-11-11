**Wrapper class**

Primitive data type 8 ta Wrapper class 8 have,

1.  byte =Byte

2.  short =Short

3.  int =Integer

4.  long=Long

5.  float=Float

6.  double=Double

7.  char=Character

8.  boolean=Boolean

Eg:

<img src="media/media/image1.tmp" style="width:3.77136in;height:1.25017in" />

<img src="media/media/image2.tmp" style="width:2.00028in;height:0.58341in" />

**Boxing**

wrapper class reference variable ekkt primitive data type value ekk dana ekt kiyanawa -boxing kiyala

**Unboxing**

Primitive data type reference variable ekkt class wrapper class value ekk dana ekt kiyanawa -unboxing kiyala

<img src="media/media/image3.tmp" style="width:3.24003in;height:1.06265in" />

**String conversion to integer and double**

<img src="media/media/image4.tmp" style="width:3.43798in;height:0.8647in" />

**Collection Frameworks and Generics**

Java wala Array ekk haduwama eke limits deck thiynw,

1.  Type Specific

2.  Fix length

> <img src="media/media/image5.tmp" style="width:2.28157in;height:0.87512in" />
>
> Mekata solution ekk widihata Array list kiyana class eka java.util eke thiyanawa.
>
> Mekata onima type eke data ekk danna puluwn.
>
> <img src="media/media/image6.tmp" style="width:3.15669in;height:2.03153in" />
>
> **Generic**

- Generic kiyanne compile time type safety mechanism ekk

- Meka diamond brackets athule \<\> wrapper class type eka thamai danne.

- Default generic data type eka =object

- Generic krnne nathuwa default nm thiyenne oni data type ekk danna puluwn.

> <img src="media/media/image7.tmp" style="width:3.6776in;height:2.0107in" />
>
> **HashSet**

- Hash set ektath generic krnn puluwn.

- Meke duplicate value ain krnw

- Eyata galapena piliwelak hadagannawa

- Meke result ekk widihata get method na

- Reason duplicate values ain krl eyage order ekkt eya indexex hadagann nisa.

> <img src="media/media/image8.tmp" style="width:3.17753in;height:1.85443in" />
>
> <img src="media/media/image9.tmp" style="width:3.03167in;height:0.51049in" />
>
> **Priority Queue**
>
> Meka ascending order ekata yanne (aaarohana -podi sita loku).
>
> Meka hariyata wada karanne na
>
> <img src="media/media/image10.tmp" style="width:4.05265in;height:1.58355in" />
>
> <img src="media/media/image11.tmp" style="width:1.84401in;height:0.29171in" />
>
> **Hash Map**
>
> Meke( key, value) widihata yanne.
>
> Meke det method ekk have ,get krddi index eka nemei denne key eka
>
> Add wenuwata Put method eka thiyenne
>
> <img src="media/media/image12.tmp" style="width:3.55258in;height:1.44812in" />

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

> Build tools = user ta eka file ekkt hadala dena ekata meka udau wenw(executable file ekk user ta hadala dena eka) class okkm technically build krl final architecture ekk hanna ganna eka
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
> Import com.mysql.cj.jdbc .Driver ----base package.class

- Pawichchi krn build tool ant eka nm download krl manually krnn oni

- Pawichchi krn build tool eka Mevan or Gradle nm athulema 3<sup>rd</sup> party dependency builder kenek innw.eka manuallay download krl krnn oni na

> <img src="media/media/image13.jpeg" style="width:5.69792in;height:2.89583in" />
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
> <img src="media/media/image14.jpeg" style="width:4.92708in;height:3.27986in" />

Apita scene ekk hadanna puluwn,

fxml

<img src="media/media/image15.tmp" style="width:2.06279in;height:0.7501in" />

Controller

<img src="media/media/image16.tmp" style="width:1.62523in;height:0.25003in" />

<img src="media/media/image17.tmp" style="width:3.12544in;height:1.62523in" />

Application<img src="media/media/image18.tmp" style="width:6.5in;height:0.98681in" />

**Scene builder**

Palet

Text input -id

Button -on action

Assignment

Save = mekata array list ekk danna oni oe hash map ekk ganna puluwn

Delete =remove(int index)

Mysql ---cli

---gli
