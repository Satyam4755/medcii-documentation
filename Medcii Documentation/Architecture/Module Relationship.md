# Module Relationship

```mermaid
graph LR

Doctor --> Appointment
Patient --> Appointment

Appointment --> Prescription

Prescription --> PrescriptionItem
```