---
title: Java Arrays Memory And Heap Stack
---

varaiable =thawakalika data ekk
array= ekam type eke data godak store krnn

java wala type safe arrayas witharai hadanna puluwn
```java
int\[\] age = new int\[7\]; ======value eka newint\[700\]====data type= int array
```
ages\[1\] = 5;====value eka 5===daat type int

default watila thiyeenee,
string= null
int=0
double=0.0

java demo command eka dunn gaman jvm is loaded to ram
```java
the jvm has class loader
```

```java
class loader hard eke thiyana demo.class file eka ram(jvm) ekata load krnwnw
```
```
scanner ekk plug krl thibbth class file 2 load wenw 1.demo.claa 2.scanner.class
```
eh wen krpu ida bedenw 2,

1.stack memory (code eke thiyn hama variables and ewage values store wela thiyenne meke)rack ekk wage
2.heap memory (array object eka watenw eka watuna gaman ekata unique address ekk hambenw , eh address eka store wenw ages kiyn variable eke )just like a empty room

```java
int\[\] age = new int\[7\]; ======value eka newint\[700\]====data type= int array
```
new keyword = int array object

int \[\] ages = reference variable(ages kiyn array type variable eka)

apita puluwn address same eka pass krnn
```java
int\[\] ages = new int\[7\]
```
—–\_\_\_\_\_ ==========
data variable array object
type

int\[\] xr =ages;
(mekata thiyenne ages eke same address eka )

1d 2d 3d task ekt adunawa thamai gnnae
ex. panthiye lamai 35 innw eyalata sem 4 thiynw 1 sem ekk subject 7 thiynw
meka 3d

continue = round ekak skip krnnn puluwn loop ekk danne
for(int i=0; i\<5; i++){
if(i==3){
continue;
}
```java
System.out.println(i);
```
}
