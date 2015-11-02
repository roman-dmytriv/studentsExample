# Приклад клієнтсько-серверного веб додатку
Додаток дозволяє логінізуватись в систему за рахунок кодової фрази.
Якщо фраза відсутня в базі данних, можна створити нову. 
Після авторизації кодову фразу можна змінити 
# Технології
При верстанні сторінки використовувався фрейморк [Twitter Bootstrap](http://getbootstrap.com/).
Для для опрацювання клієнтських подій, маніпуляцій DOM, та HTTP запитів використовувався 
[Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) та бібліотека [JQuery](https://jquery.com/)
Для створення серверної частини використовувалась технологія [Node.js](https://nodejs.org/en/) і фреймворк [Express.js](http://expressjs.com/)
В якості бази даних використовуватась технологія [MongoDB](https://www.mongodb.org/) та [MongoLab](https://mongolab.com/) в якості хмарного хранилища.
Для комунікації між [Express.js](http://expressjs.com/) та [MongoDB](https://www.mongodb.org/) використовувалась бібліотека [Mongoose](http://mongoosejs.com/)
# Інсталяція

Для запуску додатку потрібно встановити Node.js - https://nodejs.org/en/

Після установки потрібно проінсталювати залежності(dependency). Для цього знаходячись в папці з додатком в консолі потрібно прописати команду
```js
npm install
```
Після закінчення завантаження залежностей потрібно запустити сервер командою (знаходячись в папці з додатком)
```js
node server.js
```
Додаток буде доступний за адрессою: [http://localhost:3000](http://localhost:3000)
