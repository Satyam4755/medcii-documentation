# Backend Architecture

```mermaid
graph LR

doctor_py --> Validation

patient_py --> Validation

appointment_py --> Validation

prescription_py --> Validation

Validation --> MariaDB
```
