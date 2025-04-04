# Fullstack-part0.4 New note diagram

```mermaid
sequenceDiagram
participant browser
participant server

    browser->>server: POST http://fullstack-exampleapp.herokuapp.com/new_note
    activate server
    server->>browser: text/html
    deactivate server
```
