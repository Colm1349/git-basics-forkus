# git-basics
Repository for Git course.

## Mermaid Test
```mermaid
graph LR
    A[Клиент] -->|"curl http://localhost:80"| B["Nginx"]
    B -->|"Запрос в backend (порт 8080)"| C["Backend "]
    C -->|"Ответ &quotHello from Effective Mobile!&quot" | B
    B -->|Ответ клиенту| A

    %% Добавляем цвет
    linkStyle 0,1 stroke:lightblue, stroke-width:3px;
    linkStyle 2,3 stroke:green, stroke-width:3px;
```
