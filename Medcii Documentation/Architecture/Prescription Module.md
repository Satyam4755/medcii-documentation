# Prescription Module

```mermaid
graph TD

Prescription

Prescription --> Patient
Prescription --> Doctor
Prescription --> Appointment
Prescription --> PrescriptionDate
Prescription --> PrescriptionItems

PrescriptionItems --> Medicine
PrescriptionItems --> Dosage
PrescriptionItems --> Frequency
PrescriptionItems --> Duration
```
