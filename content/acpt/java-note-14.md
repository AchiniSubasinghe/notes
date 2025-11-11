---
title: java-note-14
---

stand alone system = thani db
meka fail wenw wela enterprise level application

java ee hadenne web based application ekk.
API - data request krl aye gannawa

data bases kipayak use krl application ekkt kiynw database connection pool.

c drive
progrm files
my sql
8.0 bin

propertiews advance setting environment

mysqldump -root

```
package lk.acpt.demo_jdbc.controller;
```

```
import javafx.event.ActionEvent;
import javafx.fxml.FXML;
import javafx.scene.control.TextField;
import lk.acpt.demo_jdbc.dto.DoctorDto;
import lk.acpt.demo_jdbc.dto.MedicineDto;
import lk.acpt.demo_jdbc.service.DoctorService;
import lk.acpt.demo_jdbc.service.MedicineService;
import lk.acpt.demo_jdbc.service.impl.DoctorServiceImpl;
import lk.acpt.demo_jdbc.service.impl.MedicineServiceImpl;
```

```java
public class OrderViewController {
```

    @FXML private TextField txtDocID;
    @FXML private TextField txtDocName;
    @FXML private TextField txtSpecialization;
    @FXML private TextField txtFee;

    @FXML private TextField txtMediID;
    @FXML private TextField txtName;
    @FXML private TextField txtonHand;
    @FXML private TextField txtUPrice;

```java
    private final DoctorService doctorService = new DoctorServiceImpl();
    private final MedicineService medicineService = new MedicineServiceImpl();
```

    @FXML
    private void getDocID() {
        String docId = txtDocID.getText().trim();

        if (!docId.isEmpty()) {
            DoctorDto doctor = doctorService.findDoctor(docId);
            if (doctor != null) {
                txtDocName.setText(doctor.getName());
                txtSpecialization.setText(doctor.getSpecialization());
                txtFee.setText(String.valueOf(doctor.getFee()));
            } else {
                clearDoctorFields();
                txtDocName.setText("Not Found");
            }
        }
    }

    @FXML
    private void getMediID() {
        String mediId = txtMediID.getText().trim();

        if (!mediId.isEmpty()) {
            MedicineDto medicine = medicineService.get(mediId);
            if (medicine != null) {
                txtName.setText(medicine.getName());
                txtonHand.setText(String.valueOf(medicine.getQty()));
                txtUPrice.setText(String.valueOf(medicine.getPrice()));
            } else {
                clearMedicineFields();
                txtName.setText("Not Found");
            }
        }
    }

    private void clearDoctorFields() {
        txtDocName.clear();
        txtSpecialization.clear();
        txtFee.clear();
    }

    private void clearMedicineFields() {

    }

    public void addtoCart(ActionEvent actionEvent) {


    }

    public void completeAppoinment(ActionEvent actionEvent) {
    }

}
