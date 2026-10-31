## Andrei Shishkov — QA Engineer

[![Telegram](https://img.shields.io/badge/Telegram-@Andrei__Shishkov-26A5E4?logo=telegram&logoColor=white)](https://t.me/Andrei_Shishkov)

Manual QA with 3 years of commercial experience in systems where a bug costs money: car leasing deals, payments, travel bookings with dozens of suppliers. I test the UI and what's underneath it — REST API, database, logs, message queues — and bring developers the cause of a bug, not just the symptom.

📍 Yerevan, Armenia · remote or hybrid · 🇷🇺 [Русская версия ниже](#на-русском)

---

### Experience

**QA Engineer — CARCADE** · car leasing for business · *Dec 2024 – Oct 2026*
Internal system that runs a leasing deal from application to buyout: client checks, e-signed documents, payments. Microservices on Kafka, team of 19.
- Caught a double charge on early buyout before release: traced it via Seq and Kafka UI to a retried message without an idempotency check
- 900+ test cases in TestRail; 220 of them became part of the automated regression suite
- Verified payment schedules and tax calculations to the cent with SQL (PostgreSQL) and Excel

**QA Engineer — Russian Express (Online Express)** · B2B travel booking platform · *Oct 2023 – Nov 2024*
Travel agencies book hotels, flights and packages; prices come in real time from dozens of suppliers via REST API.
- Found an IDOR vulnerability: one agency could read another agency's bookings with passport data (200 instead of 403). Critical, fixed within a day
- Cut regression time from 3–4 to 2–2.5 hours by auditing the checklist (250+ → ~180 items) with no increase in production bugs

---

### Toolbox

| Area | Tools |
|---|---|
| Testing | test design (boundary values, equivalence classes, pairwise), regression, requirements review, test cases, bug reports |
| API | Postman, Swagger / OpenAPI, REST, JSON, XML, Charles Proxy |
| Data | SQL, PostgreSQL, DBeaver |
| Observability | Kafka UI, Seq, Graylog, Grafana, Chrome DevTools |
| Process | Jira, Confluence, TestRail, TestIT, Figma, Scrum |
| Own projects | Python, pytest, Testinfra, Allure, Git, GitHub Actions, Docker, Linux, OpenTelemetry Demo |

---

### Projects

The code in these projects was written by an AI coding assistant. My part: the idea and requirements, test design, checking and testing the result, and running the repository.

**[VPN Infrastructure QA Suite](https://github.com/Andrei-Shishkov-QA/vpn-infrastructure-qa-suite)** — Python · pytest · Testinfra · GitHub Actions · Allure · *archived*
QA suite for my personal VPN for friends and acquaintances: 4 Linux servers, 50+ users at peak. Test strategy, requirements traceability matrix, nightly automated checks (security, network speed, backups, server health), Allure reports, Telegram alerts and a manual checklist for phones. Built in early 2026; the servers are shut down now and the repository is archived.

**[Astronomy Shop API](https://github.com/Andrei-Shishkov-QA/astronomy-shop-api_v1)** — OpenAPI · Swagger UI · Chrome DevTools · GitHub Pages
Demo for my training video lesson: how a tester can start API documentation when there is none. I captured the cart request of the OpenTelemetry Demo in DevTools, turned it into an OpenAPI spec and published a [live Swagger page](https://andrei-shishkov-qa.github.io/astronomy-shop-api_v1/).

**[Video-to-Anki Automation](https://github.com/Andrei-Shishkov-QA/video-to-anki-automation)** — Python · PyQt5 · Tkinter · SQLite · Google Cloud TTS
Two desktop tools I made for myself to learn English from films: find study phrases in subtitles and build Anki decks with video clips and audio. Work went in Git branches, with a separate release branch; tested by hand on my own films.

---

### Now

- Moving from Postman collections to API test automation in Python
- Going deeper into microservices and observability: traces, OpenTelemetry

**Languages:** Russian (native), English (B1)
**Contact:** Telegram [@Andrei_Shishkov](https://t.me/Andrei_Shishkov)

---

### На русском

QA-инженер, 3 года в ручном тестировании систем, где ошибка стоит денег: лизинговые сделки, платежи, бронирование с десятками поставщиков. Проверяю экран и то, что под ним — REST API, базу данных, логи, очереди сообщений — и прихожу к разработчику с причиной бага, а не с симптомом.

**Опыт**
- **CARCADE** (автолизинг для бизнеса), дек 2024 — окт 2026. Система лизинговых сделок от заявки до выкупа, микросервисы на Kafka. Поймал двойное списание до релиза; 900+ тест-кейсов, 220 — в автоматизированном регрессе; сверка расчётов через SQL.
- **«Русский Экспресс»** (Online Express, B2B-бронирование туров), окт 2023 — ноя 2024. Нашёл уязвимость IDOR (Critical); сократил регресс с 3–4 до 2–2,5 часов.

**Свои проекты** — код писал AI-ассистент; моя часть: идея и требования, тест-дизайн, проверка результата, ведение репозитория.
- **VPN Infrastructure QA Suite** — QA-набор для личного VPN для друзей и знакомых: 4 сервера, 50+ человек. Тест-стратегия, матрица требований, ночные автопроверки, ручные тесты. В архиве.
- **Astronomy Shop API** — демо к учебному видеоуроку: как тестировщику начать документацию API в Swagger, если её нет.
- **Video-to-Anki Automation** — два инструмента для себя: фильм + субтитры → карточки Anki с видео и озвучкой.

**Сейчас:** перехожу от Postman-коллекций к автотестам API на Python; изучаю микросервисы и наблюдаемость.

Ереван · удалёнка или гибрид · Telegram [@Andrei_Shishkov](https://t.me/Andrei_Shishkov)
