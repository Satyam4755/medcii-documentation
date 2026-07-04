# Patient Backend

```mermaid
graph TD

Patient

Patient --> validate

Patient --> before_insert

Patient --> before_save

Patient --> after_insert

validate --> MariaDB
```
