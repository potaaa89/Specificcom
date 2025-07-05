
# Specificcom Full Project

## Запуск

1. Установить зависимости:
   - client: npm install
   - server: npm install express socket.io cors

2. Запустить сервер:
   cd server
   node index.js

3. Запустить клиент:
   cd client
   npm start

4. Настроить firebaseConfig.js с собственным проектом

Проект содержит:
- Чат
- WebRTC видеозвонки
- Авторизация (реализуется через Firebase Auth)
- Загрузка медиа (через Firebase Storage)
