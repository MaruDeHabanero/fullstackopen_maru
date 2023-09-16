```mermaid
sequenceDiagram
  Client->>Server: POST /new_note
  Server->>Server: Updates data.json
  Server->>Client: Redirects /notes
  Server->>Client: Loads main.css
  Server->>Client: Loads main.js
  Server->>Client: Loads data.json
```