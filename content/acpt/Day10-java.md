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

<img src="media/media/image1.tmp" style="width:6.5in;height:3.85417in" />

<img src="media/media/image2.tmp" style="width:6.5in;height:4.49861in" />

2.  Array index is out of bounds

<img src="media/media/image3.tmp" style="width:6.5in;height:3.71319in" />

3.  Number format Exception

4.  Null point exception

5.  File not found error

arithmetic reference variable ekt super class reference variable eka danna puluwn…(Exception).super type reference variable ekkt sub time object ekk assign krnn puluwn.

Apita expections types deck handle krnn awoth,

Super class eka danna.

<img src="media/media/image4.tmp" style="width:4.89652in;height:1.87526in" />

Catch blocks 2 danna.

<img src="media/media/image5.tmp" style="width:4.72983in;height:2.20864in" />

Eka ma catch bock eke or operator eka dala krnn puluwn.

<img src="media/media/image6.tmp" style="width:4.87568in;height:1.81275in" />

Trows =main method eke eliye method ekk hadala eka main eke call krddi expeceoption handle krnn oni method eke throws keyword eka use krl

Eg:

Public Static void dance() throws NumberFormatException{

String name=”kk”;

Int num =Integer.parse(name)

}

<img src="media/media/image7.tmp" style="width:5.85498in;height:4.02139in" />

Trows =eka method ekkin thawa method ekt expection eka parse krnw

Trow=exeption ekk balen athi krnwnw

<img src="media/media/image8.tmp" style="width:3.29213in;height:1.61481in" />

Finally{}

Apita aniwaren run wenna oni line ekk oni nm Finally block eka danna puluwn.

Try ekt giyth nathth ,

Catch ekt gith nathath,

Finally block athule thoyana eka run wenw

<img src="media/media/image9.tmp" style="width:4.56314in;height:2.45868in" />

Apita Expection ekk danna oni wunama,

<img src="media/media/image10.tmp" style="width:5.77164in;height:2.11488in" />

<img src="media/media/image11.tmp" style="width:3.97972in;height:1.12516in" />

Non reference objects clean krnn-garbage collector ekk thiynw thiynw jvm eke

**Garbage collector**

Student student =new Student();

Student=null;

Object eka thani wela garbage collector eka eka clear krnw.

Garbage nicn ma awilla object eka clean krnne .

Java 7 8 version wala meka api danna oni ----System.gc();

Java 17 dn updated version wala meka danna oni na

**Package(folder)**

Standard package convention

Domain name .coperation name.package name

Base package ekk hdnn oni src eke----website eka reverse krl danne

Finalize

Object class eke finalize override method ekk dnn puluwn.

Garbage collector elligle object eke(non reference object eka)final task eka krnnn oni nm finalize method eka use krnn puluwn.

Final key word eka krnn.

String

<img src="media/media/image12.tmp" style="width:4.59439in;height:2.81289in" />

Ram eke application ekk run wenn ida hadagnnw.eh ida 2 bedenw stack ekai heap ekai.

Heap eke special cotasak have ekt kiynw String constant pool kiynw.

Literal based string ekk haduwth String name=”yasindu”.

Meke string name save wenne stack eke “yasindu ” kiyna eka save wenw string constant pool ekeeke id eka store wenw name kiyana eke.

Object based string

String name2 = new String(“pasindu”);---meka set na mkd meke wadipura object ekk hadenw=a nisa

Mekedi stack eke string name2 kiyana eka save wenw.new keyword eka nisa obect ekk hadenw ita passe value eka yanawa string constant pool ekt.object eke id eka stack reference variable eke save wenw.ara value eke id eka aluth object eke variable ekt assign wenw. <img src="media/media/image13.jpeg" style="width:6.5in;height:4.09792in" />

String methods.

<img src="media/media/image14.tmp" style="width:4.28185in;height:3.32338in" />

Why String Immutable =const pool eke value reference variable kipayakata link wenna puluwn.eh nisa string wenas wiya nohaki.

**Eg.string name5 =rumesh;**

**System.out.print(name5);**

**Name5.concat(“sathsara”);**

**System.out.print(name5);**

Meke output eka wenas wenne na concat kra kiyala mkd string wenas wenne na.

Habay,

- string concate krnn puluwn. Concate weddi pool eke value eka wenas wenne na.dynamically nicn watenw witharai.

<img src="media/media/image15.tmp" style="width:4.71941in;height:2.77122in" />

String ekk wenuwata String builder or String buffer danna puluwn.

<img src="media/media/image16.tmp" style="width:4.38603in;height:2.42742in" />

String builder, string buffer(mutable)---kisima welwk pool eka consume krnn na()

> String builder ekei string ekei wenasa = string immutable string builder eka mutable.

Yam class ekkt char sequence eka implement krl thiynw character array ekk store krnn puluwn.

Final- key word

Variable re initialize krnn bh.

Final keyword eka method ekk danna puluwn.final method ekk override krnn bh

Final class ekk extend krnnh bh.

Finally- try catch block ekt giya ho nathi finally wenna kiyala

Finalize –

Object class eke finalize override method ekk dnn puluwn.

Garbage collector elligle object eke(non reference object eka)final task eka krnnn oni nm finalize method eka use krnn puluwn.
