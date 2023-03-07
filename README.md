### АУТЕНТИФИКАЦИЯ ПОЛЬЗОВАТЕЛЯ REST API
 
### Введение

<img width="810" alt="Снимок экрана 2023-03-07 в 17 57 37" src="https://user-images.githubusercontent.com/86431195/223494003-4869f564-04dc-410f-853b-1f47c8bcbfe3.png">

Серверная часть API построена с помощью Express.js Framework из Node.js, а клиентская часть построена с помощью Vue.js Framework. MongoDB используется для хранения пользовательской информации и заметок.

### Требования

* [MongoDB](https://www.mongodb.com/try/download/community)
* [Node](https://nodejs.org/en/)

* Перейдите в папку сервера и установите пакеты npm для сервера.

```bash
    npm install
  ```
 
* Создание файла .env в папке сервера.
 
 ```bash
    touch .env
  ```
 
* Затем создайте TOKEN_SECRET, используя буквы, цифры и символы.
 
  ```bash
      TOKEN_SECRET=kwqejnrlkqwe%423%@$^klsd;flka1
    ```
 
* Запустить сервер
 
```bash
    npm start
  ```
   
* Перейдите в папку клиента и установите пакеты npm для клиента.
   
  ```bash
    npm install
  ```
   
  * Запустить клиент
   
 ```bash
    npm run serve
  ```
   
   
