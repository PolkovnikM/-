```mermaid
graph TB
    Client[Браузер] -->|HTTP/JSON| Server[Apache + PHP]
    Server -->|PDO/SQL| DB[(MySQL)]
    
    subgraph Клиентская часть
        HTML[HTML/CSS/JS]
        React[React виджеты]
    end
    
    subgraph Серверная часть
        API[REST API]
        Auth[Авторизация]
        Session[Сессии]
    end
```
