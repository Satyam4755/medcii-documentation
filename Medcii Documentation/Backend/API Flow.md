# API Flow

```mermaid
graph LR

Browser --> ClientScript

ClientScript --> PythonAPI

PythonAPI --> Database

Database --> PythonAPI

PythonAPI --> Browser
```
