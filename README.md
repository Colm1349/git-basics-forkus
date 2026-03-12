# git-basics
Repository for Git course.

## Mermaid Test
```mermaid
graph LR
    A[Клиент] -->|"curl http://localhost"| B[Nginx<br>(порт 80)<br>]
    B -->|"proxy_pass http://backend:8080"| C[Backend<br> (порт 8080)<br>]
    C -->|"Hello from Effective Mobile!"| B
    B -->|Ответ клиенту| A
```
