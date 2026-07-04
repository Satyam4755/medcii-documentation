# Deployment Architecture

```mermaid
graph TD

Developer

Developer --> GitHub

GitHub --> ProductionServer

ProductionServer --> Frappe

Frappe --> MariaDB

Users --> Website
```
