# 🌍 Добро пожаловать в экосистему Last SMP

**Last SMP** — это не просто сервер Minecraft. Это полноценная, масштабируемая экосистема, состоящая из игровых серверов, веб-инфраструктуры и ботов, тесно интегрированных друг с другом через единую базу данных. 

Мы навсегда отказались от публичных "сборок" и чужих плагинов. Наша миссия — создавать уникальный игровой опыт с идеальной оптимизацией и глубоким погружением.

---

## 🏗️ Архитектура Экосистемы

Все наши сервисы связаны между собой. Игровая статистика моментально отображается на сайте, донат покупается через Telegram-бота, а Discord-бот управляет модерацией и тикетами, синхронизируясь с игровыми событиями.

### 🗡️ 1. [LastSMP-Server]([https://github.com/Last-SMP/LastSMP-Core](https://github.com/Last-SMP/lsmp-server-system))
**Сердце проекта.** Полностью самописная сеть серверов Minecraft (1.21).
* **Стек:** Kotlin, Java 21, Paper API, Velocity API, HikariCP (MySQL).
* **Модули:** `last-velocity` (прокси), `lsmp-auth` (авторизация), `lsmp-lobby` (хаб), `lsmp-api` (ядро и экономика), `lsmp-survival` (режим SMP).
* **Фишки:** 3D-косметика, уникальные артефакты, глобальный лор и расширяющийся бордер мира, самописные ИИ-зомби.

### 🌐 2. [LastSMP-Web]()
**Лицо проекта в сети.** Официальный сайт и Личный кабинет игрока (last-smp.net).
* **Стек:** *(???)*
* **Фишки:** ???

### 🤖 3. [LastSMP-Discord]([https://github.com/Last-SMP/LastSMP-Discord](https://github.com/Last-SMP/lsmp-discord-bot))
**Управление комьюнити.** Многофункциональный бот для нашего Discord-сервера.
* **Стек:** TypeScript, Node.js, Discord.js v14, SQLite.
* **Фишки:** Система тикетов (модальные окна, приватные каналы), система репортов, музыкальный плеер, расширенная модерация (баны, муты) и конструктор постов через UI.

### 📱 4. [LastSMP-Telegram]()
???
* **Стек:** *(???)*
* **Фишки:** Прием платежей через новую валюту **Telegram Stars**, автоматическая генерация одноразовых ключей для активации подписки в личном кабинете на сайте.

---

## 💻 Технологический Стек Организации

| Backend / Game API | Web & Bots | Databases & Infra |
|--------------------|------------|-------------------|
| ![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=flat-square&logo=kotlin&logoColor=white) | ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| ![Java 21](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white) | ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white) | ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| ![Paper](https://img.shields.io/badge/PaperMC-000000?style=flat-square&logo=paper&logoColor=white) | *(???)* | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |

---

## 📈 Главные достижения

1. **Беспрецедентная оптимизация:** Стабильные `20.0 TPS` при спаме сотнями сущностей, работая на бюджетном сервере.
2. **Нулевая зависимость:** 90% кода (от капчи при входе до расширения мира) написано нашей командой с нуля без использования "тяжелых" плагинов.

---

## 🔗 Присоединяйтесь к нам

Мы всегда открыты для баг-репортов, предложений и новых игроков.

- 🎮 **IP Сервера:** `???` (Версия 1.21+)
- 🌐 **Сайт:** ???
- 💬 **Discord:** ???
