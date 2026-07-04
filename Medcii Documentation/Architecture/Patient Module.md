# Patient Module

```mermaid
graph TD

Patient

Patient --> BasicInfo
Patient --> ContactInfo
Patient --> MedicalInfo

BasicInfo --> FirstName
BasicInfo --> LastName
BasicInfo --> Gender
BasicInfo --> DOB
BasicInfo --> ProfilePhoto

ContactInfo --> Phone
ContactInfo --> Email
ContactInfo --> Address

MedicalInfo --> BloodGroup
MedicalInfo --> AssignedDoctor
MedicalInfo --> Notes
```