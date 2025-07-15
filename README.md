Это мобильное приложение-чат, разработанное на React Native с использованием Expo, которое общается с моделью ChatGPT (gpt-3.5-turbo) через API OpenAI.

![React Native](https://img.shields.io/badge/React%20Native-blue?logo=react)
![Expo](https://img.shields.io/badge/Expo-000020?logo=expo)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai)
![Status](https://img.shields.io/badge/Status-Working-brightgreen)

---

## Возможности

-  Отправка сообщений в чате
-  Ответы от искусственного интеллекта (GPT-3.5 Turbo)
-  Удобный и минималистичный интерфейс
-  Поддержка Android и iOS (Expo)
-  Безопасное хранение API-ключа с помощью `.env`

---

## Используемые технологии

| Технология     | Назначение                      |
|----------------|---------------------------------|
| React Native   | Основной фреймворк              |
| Expo           | Быстрая разработка и сборка     |
| OpenAI API     | ИИ-ответы                       |
| dotenv         | Хранение API-ключей             |
| Fetch API      | Работа с запросами              |

---


##  Установка и запуск

1. **Клонируйте репозиторий**
   git clone https://github.com/DianaKurt/chat-bot-app.git
   cd chat-bot-app

2. **Установите зависимости**
    npm install
3. **Создайте файл .env и добавьте свой ключ OpenAI**
   OPENAI_API_KEY=ваш_секретный_ключ
   
4. **Запустите Expo**
   npx expo start
   
5. **Сканируйте QR-код через приложение Expo Go**


**Доступ из браузера**
web-версию:
http://localhost:8082

**Идеи для развития**
- История сообщений
- Темная тема 
- Голосовой ввод 
- Выбор моделей (GPT-3.5, GPT-4 и т.д.)
- Подключение к другим API (например, DALL·E, Weather, News)
