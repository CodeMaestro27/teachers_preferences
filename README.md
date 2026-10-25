
🗓️ teachers_preferences

Веб-приложение для сбора и управления предпочтениями преподавателей относительно расписания занятий и экзаменов. Разработано для внутреннего использования в университете, с возможностью администрирования и экспорта данных.

 🚀 Технологии

- 🧠 Backend: Java + Spring Boot
- 🎨 Frontend: React.js
- 💾 Database: PostgreSQL / H2
- 🔐 Security: Spring Security + JWT 
- 🧾 Export: Apache POI (Excel)
- 🌐 API: RESTful
  
  Требования

- Git
- Java 17+
- Maven 3.6+
- Node.js 16+ (npm 8+)
- PostgreSQL 12+ (создать БД с именем `webapp`)

  bash
  git clone https://github.com/CodeMaestro27/teachers_preferences/tree/main.git
   cd teachers_preferences
   
   Запуск бэкенда

1. Создать базу данных `webapp`.

Подключись к PostgreSQL:


psql -U postgres

CREATE DATABASE webapp;

\q
 
3. Запустить:
```bash
cd backend
mvn spring-boot:run
```
Адрес: http://localhost:8080


Настройка и запуск фронтенда

```bash
cd frontend
npm install
npm run dev
```
Адрес: http://localhost:5173


Авторизация
Логин: admin 
Пароль: admin1

   
   
  👥 Роли пользователей

- 👨‍🏫 Преподаватель – входит в систему, указывает предпочтения по расписанию.
- 🧑‍💼 Администратор – просматривает данные, экспортирует их, управляет дедлайнами.

 📦 Структура проекта

project-root/
├── backend/ # Spring Boot проект (Java)
├── frontend/ # React приложение
└── README.md






💬 Telegram: @SHERIFALY



