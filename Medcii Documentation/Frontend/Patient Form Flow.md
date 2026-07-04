# Patient Form Flow

```mermaid
graph TD

User --> PatientForm

PatientForm --> patient_js

patient_js --> patient_py

patient_py --> MariaDB
```
