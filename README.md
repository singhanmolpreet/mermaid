# Mermaid

``` mermaid
flowchart LR
    A-- Hlo -->B
    A-->C
    B-->D
    C-->D
    D-->E 
```

```mermaid
flowchart TD
    A(Christmas)-- Get money -->B(Go shopping)
    B --> C{Let me think}
    C -->|One| D[Laptop] 
    C -->|Two| E[iPhone]
    C -->|Three| F[fa:fa-car Car]
    style A fill:red,stroke:white
    style B fill:green,stroke:black,stroke-width:4px,shadow:shadow
    style C fill:blue,stroke:black,stroke-width:4px,shadow:shadow
    style D fill:yellow,stroke:black,stroke-width:2px,shadow:shadow
    style E fill:brown,stroke:black,stroke-width:2px,shadow:shadow
    style F fill:navy,stroke:black,stroke-width:2px,shadow:shadow
   
    
```
