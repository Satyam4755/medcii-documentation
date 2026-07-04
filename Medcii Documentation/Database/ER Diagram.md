# ER Diagram

```mermaid
erDiagram

DOCTOR ||--o{ PATIENT : assigned

PATIENT ||--o{ APPOINTMENT : books

DOCTOR ||--o{ APPOINTMENT : attends

APPOINTMENT ||--|| PRESCRIPTION : generates
```
