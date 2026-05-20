# Hospital Management System - ERD Design 🏥

A comprehensive Entity-Relationship Diagram (ERD) designed to manage hospital operations, including doctor-patient interactions, room assignments, and medical prescriptions.

## 📋 System Requirements

### 1. Doctors & Patients
* Each **Patient** is examined by exactly **one Doctor**.
* A **Doctor** can examine **multiple Patients**.
* The **Check-up Date** is recorded for every examination.

### 2. Patients & Rooms
* A **Patient** is assigned to stay in only **one Room**.
* Each **Room** can accommodate **multiple Patients** (shared rooms).

### 3. Doctors & Medicines
* A **Doctor** can prescribe **multiple Medicines**.
* The same **Medicine** can be prescribed by **multiple Doctors** for different patients.

---

## 🛠️ Data Model Details

### Entities & Attributes
* **Patient:** * `ID` (Primary Key)
  * `Name` (Composite: First, Last)
  * `Phone` (Multivalued)
  * `Birth Date`
* **Doctor:** * `Employee ID` (Primary Key)
  * `Specialization`
  * `Years of Experience`
  * `Age` (Derived from Birth Date/Join Date)
* **Medicine:** * `Medicine Code` (Primary Key)
  * `Name`
  * `Price`

---

## 🖼️ Entity Relationship Diagram (ERD)

![Hospital ERD](image_d7441c.png) 
*Note: Replace 'image_d7441c.png' with the actual filename of the image you upload to GitHub.*

---

## 📂 Files in this Repository
* `MyERD_2.drawio`: The original editable source file (Open via [draw.io](https://app.diagrams.net)).
* `image_d7441c.png`: The exported diagram image.
* `README.md`: Project documentation.

---

## 🚀 Tools Used
* [Draw.io](https://app.diagrams.net/) - For designing the ER diagram.
* [GitHub](https://github.com/) - For version control and portfolio hosting.
