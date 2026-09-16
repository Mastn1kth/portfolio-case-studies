# Александр Симунин — кейсы проектов

[English](README.md) | [Русский](README_RU.md)

Этот каталог описывает самостоятельные проекты из портфолио. Ссылки ведут на безопасные публичные экспортные версии исходников. Остальные проекты приведены без кода, когда публикация могла бы раскрыть приватные интеграции, рабочие данные или материалы с неясными правами на распространение.

| Проект | Задача | Стек и реализованное | Доступность |
| --- | --- | --- | --- |
| [Gory Staff](https://github.com/Mastn1kth/gory-staff) | Операционные процессы и лояльность ресторана | Expo React Native, Node.js, PostgreSQL, Socket.IO, iikoCloud, Twilio, OAuth | Публичный репозиторий |
| AstraChat Onda | Realtime-мессенджер | React, Express, PostgreSQL, Redis, WebSocket, WebRTC, Capacitor, бэкапы и модерация | Исходники закрыты |
| [LectureVault](https://github.com/Mastn1kth/lecturevault) | Кроссплатформенная запись лекций и конспекты | Клиенты Android, Windows, iOS и macOS; защищённый AI Gateway, облачная обработка по согласию, Obsidian vault, восстановление, мини-тесты и локальный Android fallback | Публичный репозиторий |
| [Logisim Lab](https://github.com/Mastn1kth/logisim) | Обучение цифровой логике | Форк Logisim-evolution, Circuit Check / «Проверка схемы», русская локализация, Windows/macOS-сборки со встроенной Java | Публичный репозиторий; основан на open-source проекте |
| [Goal Rings](https://github.com/Mastn1kth/goal-rings) | Трекер целей | Flutter, локальное хранение, уведомления, виджеты, offline fallback | Публичный репозиторий |
| Clinic Pulse | Операционная PWA клиники | React, TypeScript, Cloudflare Workers/D1, роли, журнал аудита, бэкапы | Только описание |
| [Pet Translator AI](https://github.com/Mastn1kth/pet-translator-ai) | Локальная обработка медиа животных | React Native, Expo, TFLite, работа с аудио и камерой, уведомления | Публичный репозиторий |
| [Casino Mini App](https://github.com/Mastn1kth/casino-mini-app) | Демонстрационное Telegram Mini App | FastAPI, SQLite, WebSocket, Telegram-авторизация, только виртуальные монеты | Публичный репозиторий |
| [AI/IT News Bot](https://github.com/Mastn1kth/ai-news-bot) | Автоматизация новостей | Python, RSS/Atom, скоринг, дедупликация, SQLite, Docker, Telegram Bot API | Публичный репозиторий |
| AI Startup Radar | Дашборд исследования стартапов | FastAPI, React, PostgreSQL, Redis, Celery, Qdrant, Ollama, Docker | Только описание |
| CultureMatch | Продуктовый прототип | React Native, Node.js, PostgreSQL/PostGIS, Socket.IO, OpenAPI | Только описание |
| Peptide Tools | Веб-продукт для расчётов | Vite-интерфейс, изолированный Python API, Docker, CI smoke tests | Исходники закрыты |
| FPV Unreal prototype | Симуляция дрона | Unreal Engine C++, физика полёта, AI, миссии, HUD, сохранения | Только описание |
| Rocket Game | Стратегический прототип | Unity, игровые системы и документация | Только описание |
| VPN Bot | Telegram-автоматизация | Python, aiogram, Docker, тесты, конфигурация через окружение | Только описание |
| Боты записи, городских новостей и фильмов | Telegram-workflows | Python-автоматизация, модерация, поиск и запись для бизнеса | Только описание |
| Alarm App | Прототип будильника | Flutter, локальное хранение, уведомления, state management и тесты | Только описание |

## Инженерные направления

- Full-stack и mobile разработка: интерфейсы, API, модели данных, интеграции, деплой и тестирование.
- Realtime-системы: WebSocket, Socket.IO и WebRTC.
- Приватность и надёжность: роли, TOTP, шифрование, rate limiting, бэкапы, health checks и структурированные логи.
- AI и медиа: Groq Whisper, Gemini, Ollama, TFLite, обработка аудио и видео.

## Безопасность публичных исходников

В публичных репозиториях нет `.env`, API-ключей, ключей подписи, локальных баз, логов, пользовательских данных и артефактов сборки. Для новых открытых репозиториев включены Dependabot и предупреждения GitHub об уязвимостях.
