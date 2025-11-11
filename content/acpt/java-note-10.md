variable 3—–local instance static

inheritance
super class eka dana nisa thamai eka mulin run wenne

multiple inheritance na -super class 2 thibbth confution ekk ekk enw eh nisa thamai naththe–mekata thmai kiyanne diamond problem kiyanne
diamond problem occur because of multiple inheritance

multi level inheritance
level gananawak inheritance krnn puluwn

super class referance var ekkt sub eke object ekk assign krnn puluwn.
class 2 extend wenakota super class ekei sub class ekei dekema ekama method eka thiynwnm content eka wenas wunata aulk na. ekt kiynw method over wridding kiyala.

dynamic method dispatched
chamodi(super) and yasiru(sub) class deka extend wela thiyenna oni(inherit wela),
super class reference variable ekk sub class object ekk assign wela thiyenna oni,override wuna method ekk thiyanakota(method),
compile wena time ekedi = sign eke wama mulin balala check karanawa over ride method eka thiyanawada kiyala.
eh method eka thibbth run time ekedi dakunu paththe thiyana object eke method eka thamai run wenne.

constructor chain =multi level inheritance waladi eka class ekk super keyword ekh nisa thawa class ekk call wenawa.mehema class godak super keyword eka nisa inheritt
wewi yana ekata thamai constructor chain kiyanne.

hama super class ekktm obe=ject class ekk thiynw
Object class = the most super class in java
eg for method = to string ,equals, hashcode

to string dammama thamai id eka enne

Achini achini = new Achini();
Sytsem.out.println(achini.toString());

object eke thiyana to string method eka super class ekth dmama super class eke thiyana eka thamai run wenne
method over ride
public String toString(){
return “no return”
}

Abstraction
hiding the implementation.
eg: ac remote

method eke body eka danne naththnm method eka abstract krnn oni ita passe class ekth abstract krnn oni
abstract class ekk athule non abstract(concreat e class ekk) ekk thiynn puluwn
abstract class eken wadak na mkd eke logic ekk implement krnn bh
abstract class 0-100 dakwa liviya haki

interface eke public anstract danna oni na
interface ekk abstracts methods witharai thiyenna puluwn.

interface and abstract eke wena
abstract ekaka concreate method abstract method dekama thiyenne puluwn
interface eke abstract method witahrai thiyn puluwn

abstract class or instance ekkin object hdann bh .reference variables withrai hadann puluwn.
abstract class ekk 0-100 implement wenw interface class ekk 100 implement wenw

oni nm
interface eke default or static keywords ekk use karala concreate method thiyanna puluwn.
call krddi static nm class name ekenm call krnn puluwn

interface eke object hdnn bh

content ekk adui nm meka use krnw,
anonymous (class eka penne na) inner class.
main class eke wenne.

maker interface =abstract method ekk wath nmtnm kiynne mkd
eka abstract method ekk withrai nm thiyenne,ekt kiyanne funtional interface.
lambda expression -Anonymous inner class eke interface eka funtional wenna oni
sheet3 sheet =()-\>{}

(class eka wenuwata thiyana adeshakayak)record = Vehical vehical = new Vehical (brand:“Toyota”, model:“Corolla”,noOfGears:5);

Polymophism=
single interface many forms
eg.child -student ,passenger,son,customer

polymophism wala kotas dekai.
run time polymophism(ekama method eka yasiru class eketh thiynw chamodi eketh thiyanawa -method over ridding (class eka extend wela thiyanawa welwdi dynamic dispatched welawa
wena welwe method eka run time welwe method eka thirane wenne))
compile time polymophism(method overload wena awasthawe )

download scene biulder
