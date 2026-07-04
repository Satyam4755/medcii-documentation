# Appointment Form Flow

```mermaid
graph TD

User --> AppointmentForm

AppointmentForm --> appointment_js

appointment_js --> appointment_py

appointment_py --> MariaDB
```
