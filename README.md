## Andrei Shishkov — QA Engineer

[![Telegram](https://img.shields.io/badge/Telegram-@Andrei__Shishkov-26A5E4?logo=telegram&logoColor=white)](https://t.me/Andrei_Shishkov) · 🇷🇺 [Русская версия](#на-русском)

Manual QA with 3 years of commercial experience in systems where a bug costs money: car leasing deals, payments, travel bookings with dozens of suppliers. I test the UI and what's underneath it — REST API, database, logs, message queues — and bring developers the cause of a bug, not just the symptom.

📍 Yerevan, Armenia · remote or hybrid

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
- Going deeper into microservices: monitoring, logs and request tracing (OpenTelemetry)

**Languages:** Russian (native), English (B1)
**Contact:** Telegram [@Andrei_Shishkov](https://t.me/Andrei_Shishkov)

---

### На русском

<details>
<summary><b>Нажмите, чтобы открыть русскую версию</b></summary>

<br>

**Андрей Шишков — QA-инженер**

QA-инженер, 3 года коммерческого опыта в ручном тестировании систем, где ошибка стоит денег: лизинговые сделки, платежи, бронирование туров с десятками поставщиков. Проверяю экран и то, что под ним — REST API, базу данных, логи, очереди сообщений — и прихожу к разработчику с причиной бага, а не с симптомом.

📍 Ереван, Армения · удалёнка или гибрид

#### Опыт

**QA-инженер — CARCADE** · автолизинг для бизнеса · *дек 2024 — окт 2026*
Внутренняя система, которая ведёт лизинговую сделку от заявки до выкупа: проверка клиента, документы с электронной подписью, платежи. Микросервисы на Kafka, команда 19 человек.
- Поймал двойное списание при досрочном выкупе до релиза: через Seq и Kafka UI нашёл причину — повторное сообщение без проверки на идемпотентность
- 900+ тест-кейсов в TestRail; 220 из них вошли в регресс, который автоматизировали
- Сверял графики платежей и расчёт налогов до копейки через SQL (PostgreSQL) и Excel

**QA-инженер — «Русский Экспресс» (Online Express)** · B2B-платформа бронирования туров · *окт 2023 — ноя 2024*
Турагентства бронируют отели, перелёты и пакетные туры; цены приходят в реальном времени от десятков поставщиков через REST API.
- Нашёл уязвимость IDOR: одно агентство могло читать брони другого с паспортными данными (200 вместо 403). Critical, исправили за день
- Сократил регресс с 3–4 до 2–2,5 часов: почистил чек-лист (250+ → ~180 пунктов), багов с прода больше не стало

#### Инструменты

| Область | Инструменты |
|---|---|
| Тестирование | тест-дизайн (граничные значения, классы эквивалентности, pairwise), регресс, ревью требований, тест-кейсы, баг-репорты |
| API | Postman, Swagger / OpenAPI, REST, JSON, XML, Charles Proxy |
| Данные | SQL, PostgreSQL, DBeaver |
| Логи и мониторинг | Kafka UI, Seq, Graylog, Grafana, Chrome DevTools |
| Процесс | Jira, Confluence, TestRail, TestIT, Figma, Scrum |
| Свои проекты | Python, pytest, Testinfra, Allure, Git, GitHub Actions, Docker, Linux, OpenTelemetry Demo |

#### Проекты

Код в этих проектах писал AI-ассистент. Моя часть: идея и требования, тест-дизайн, проверка и тестирование результата, ведение репозитория.

**[VPN Infrastructure QA Suite](https://github.com/Andrei-Shishkov-QA/vpn-infrastructure-qa-suite)** — Python · pytest · Testinfra · GitHub Actions · Allure · *в архиве*
QA-набор для моего личного VPN для друзей и знакомых: 4 Linux-сервера, на пике 50+ человек. Тест-стратегия, матрица трассировки требований, ночные автопроверки (защита, скорость сети, бэкапы, состояние серверов), отчёты Allure, уведомления в Telegram и чек-лист ручной проверки на телефонах. Сделан в начале 2026 года; сейчас серверы выключены, репозиторий в архиве.

**[Astronomy Shop API](https://github.com/Andrei-Shishkov-QA/astronomy-shop-api_v1)** — OpenAPI · Swagger UI · Chrome DevTools · GitHub Pages
Демо к моему учебному видеоуроку: как тестировщику начать документацию API, если её нет. Поймал запрос корзины в OpenTelemetry Demo через DevTools, сделал из него спецификацию OpenAPI и опубликовал [живую страницу Swagger](https://andrei-shishkov-qa.github.io/astronomy-shop-api_v1/).

**[Video-to-Anki Automation](https://github.com/Andrei-Shishkov-QA/video-to-anki-automation)** — Python · PyQt5 · Tkinter · SQLite · Google Cloud TTS
Два десктопных инструмента, которые я сделал для себя, чтобы учить английский по фильмам: находят нужные фразы в субтитрах и собирают колоды Anki с кусками видео и озвучкой. Работал в ветках Git, релиз — в отдельной ветке; тестировал руками на своих фильмах.

#### Сейчас

- Перехожу от Postman-коллекций к автотестам API на Python
- Изучаю микросервисы: мониторинг, логи и трассировку запросов (OpenTelemetry)

**Языки:** русский (родной), английский (B1)
**Контакт:** Telegram [@Andrei_Shishkov](https://t.me/Andrei_Shishkov)

</details>
