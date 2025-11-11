---
title: Database Tables And Http Methods
---

# Tables
- appoinment
- appoinment_doctor_details
- appoinment_medicine_details
- doctors
- medicine

when appointment is placed effect following tables,
- appoinment
- appoinment_doctor_details
- appoinment_medicine_details
- medicine(quantity eka adu wenna oni)

1.  **one** doctor can have **many** appointment_doctor_details.

2.  **one** medicine can have **many** appointment_doctor_details.

3.  **one** appointment have **many** appointment medicine details.

4.  **one** appointment have **one** appointment doctor details.

![image1](/media/image1.jpeg)

------------------------------------------------------------------------

------------------------------------------------------------------------

Issra eka application ekk hama computer ekktm wena wenama danna wuna.

Issr wena wena software hadala thibbe na wena wena os walata, hama os ekktm web ekk thamai hadala thibbe.

Desktop application =standalone system

Enterprise level nm -webbased ekk wenna oni

Api -data dennai ganna puluwn thanakata kiynw api ekk

Http client-(HTTP Client Library (API))- environmenr=(Java/.NET/Angular) ,

Fetch()- Web API / Built-in HTTP Client -environemnt= Browser (JavaScript)

Axios- JavaScript HTTP Client Library-environment = Browser/Node.js

Fetch html Methods,

1.  GET

2.  POST

3.  PUT


5.  PATCH
- Multiple frontend single backend.

> Frontend= web,mobile,sm-t

ORACLE eken liyapu interface implent krl java ee haduwa,

Java ee implementations,

1.  Apache

2.  Jboss

3.  GlassFish

Oracle eka java ee wikunanawa eclipse ekt 2017.

Eclipse eka javax. Kiyana eka maru krnw Jakartha EE.

Apache tom cat 10 idn thamai jakartha walata liyala thiyenne.

Eke pallehata ewa liyala thiyenne Javax. Package ekata.soo 10

![image2](/media/image2.jpeg)

![image3](/media/image3.jpeg)

Fxml wenuwama thiyenne JSP ekk.

Issr thibbe oracle haduwa kale post ekai get

Dn eclipse la develop krl thiynw 5 ma.

```java
JavaBean class ekk wenna oni,
```

1.  Attribute private wenna oni

2.  Getter setter use krl encapsulate krl thiyenne oni

3.  Default constructor(no arg cons)

4.  Full arg constructor ekk override wenna oni (parameters okkm dala )

5.  To string override

6.  Implement krl thiyenne oni serizable( encrypt decrypt wenw ) ekk thiyenne.

> Initializable kiyana interface eke thiyana initialize method eke wenne page ekk load wenakotama data tika load wena eka.
>
> Database eke thiyana data service layer ekt parse krnne array list ekkin ita passe eka kin.
>
> Apita data parse krnn observable array list ekk danna puluwn.
>
> Table eke coloumn ekkt eka dto object ekk hadenw

```
AppoinmenDto appoinmentDetailDto = new AppoinmenDto(doc_id,subtotal,doc_fee,orderList);
```

> Meka hadanne controller eke idn service ekt table godaka details genibyanna
