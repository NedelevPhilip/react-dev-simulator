
Привет👋

Для того чтоб начать клонируй этот проект

Можешь сразу добавить его в свой GitHub

Для запуска проекта нужна версия Node Version 16.13.0+

Если у тебя другая версия ноды можешь переустановить ее или использовать 
[nvm](https://github.com/nvm-sh/nvm#installing-and-updating) для управления версиями

### Установка
***
Установи все npn зависимости
```bash
npm install
```

В качестве базы данных мы будем использовать [json-server](https://github.com/typicode/json-server)
```bash
npm install -g json-server
```

Файл БД уже в проекте - **db.json**

### Запуск
***
Запусти react проект 
```bash
react-scripts start
```

Запусти локальную БД
```bash
json-server --watch db.json --port 3004
```

Если все ок, можешь возвращаться в [чат симулятора](https://t.me/Dev_Simulatot_Bot) и принимайся за первое задание

Если возникли проблемы напиши мне в [чате](https://t.me/Dev_Simulatot_Bot)