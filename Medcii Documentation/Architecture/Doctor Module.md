# Doctor Module

```mermaid
graph TD

Doctor

Doctor --> BasicInfo
Doctor --> ContactInfo
Doctor --> ProfessionalInfo

BasicInfo --> FirstName
BasicInfo --> LastName
BasicInfo --> Gender
BasicInfo --> ProfilePhoto

ContactInfo --> Phone
ContactInfo --> Email
ContactInfo --> Address

ProfessionalInfo --> Specialization
ProfessionalInfo --> Qualification
ProfessionalInfo --> Experience
ProfessionalInfo --> ConsultationFee
ProfessionalInfo --> Availability
```
