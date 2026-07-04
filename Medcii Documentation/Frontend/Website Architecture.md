# Website Architecture

```mermaid
graph TD

Visitor

Visitor --> Home
Visitor --> Doctors
Visitor --> Patients
Visitor --> Appointments

Home --> AppointmentBooking

AppointmentBooking --> DoctorModule
AppointmentBooking --> PatientModule
```
