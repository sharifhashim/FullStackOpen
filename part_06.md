```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST http://fullstack-exampleapp.herokuapp.com/new_note_spa
    activate server
    server->>browser: status code 201
    deactivate server
```
