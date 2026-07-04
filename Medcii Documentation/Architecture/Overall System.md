# Overall System

```mermaid
graph TD

User --> Website

Website --> Doctor
Website --> Patient
Website --> Appointment
Website --> Prescription

Doctor --> MariaDB
Patient --> MariaDB
Appointment --> MariaDB
Prescription --> MariaDB
```