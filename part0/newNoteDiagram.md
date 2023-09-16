```mermaid
sequenceDiagram
  Client->>Server: POST /new_note
  Server->>Server: Updates data.json
  Server->>Client: Redirects /notes
  Server->>Client: HTML
  Server->>Client: main.css
  Server->>Client: main.js
  Server->>Client: data.json
```