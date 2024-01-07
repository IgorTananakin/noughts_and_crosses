npm init -y инициализация сервера
npm install express ws express для получения статических файлов. ws сам websocket
npm install nodemon --save-dev для перезапуска приложения
в файле server.js заменить 
"scripts": {
    "start": "nodemon server.js"
  },

запустить npm start