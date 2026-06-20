# 🌍 Добро пожаловать в экосистему Last SMP

**Last SMP** — это не просто сервер Minecraft[cite: 1]. Это полноценная, масштабируемая экосистема, состоящая из игровых серверов, веб-инфраструктуры и ботов, тесно интегрированных друг с другом через единую базу данных[cite: 1]. 

Мы навсегда отказались от публичных "сборок" и чужих плагинов[cite: 1]. Наша миссия — создавать уникальный игровой опыт с идеальной оптимизацией и глубоким погружением[cite: 1].

---

## 🏗️ Архитектура Экосистемы

Все наши сервисы связаны между собой[cite: 1]. Игровая статистика моментально отображается на сайте, донат покупается через Telegram-бота, а Discord-бот управляет модерацией и тикетами, синхронизируясь с игровыми событиями[cite: 1].

### 🗡️ 1. LastSMP-Server
**Сердце проекта.** Полностью самописная сеть серверов Minecraft (1.21)[cite: 1].
* **Стек:** Kotlin, Java 21, Paper API, Velocity API, HikariCP (MySQL)[cite: 1].
* **Модули:** `last-velocity` (прокси), `lsmp-auth` (авторизация), `lsmp-lobby` (хаб), `lsmp-api` (ядро и экономика), `lsmp-survival` (режим SMP)[cite: 1].
* **Фишки:** 3D-косметика, уникальные артефакты, глобальный лор и расширяющийся бордер мира, самописные ИИ-зомби[cite: 1].

### 🌐 2. LastSMP-Web
**Лицо проекта в сети.** Официальный сайт и Личный кабинет игрока.
* **Стек:** Next.js (App Router), React, CSS Modules[cite: 4].
* **Фишки:** 
  * Интерактивный личный кабинет с системой сессий и динамическим распределением привилегий (от `player` до `admin`)[cite: 6].
  * Безопасная система активации одноразовых кодов для получения статуса SMP+ из Telegram[cite: 5].
  * Интегрированные страницы с публичным банлистом, правилами сервера и модулем управления составом администрации (Staff)[cite: 4, 8].
  * Встроенный функционал "Demo Admin" для тестирования ролей и доступов[cite: 7].

### 🤖 3. LastSMP-Discord
**Управление комьюнити.** Многофункциональный бот для нашего Discord-сервера[cite: 1].
* **Стек:** TypeScript, Node.js, Discord.js v14, SQLite[cite: 1].
* **Фишки:** Система тикетов (модальные окна, приватные каналы), система репортов, музыкальный плеер, расширенная модерация (баны, муты) и конструктор постов через UI[cite: 1].

### 📱 4. LastSMP-Telegram
**Монетизация и донат.** Бот для продажи доната на сервере[cite: 2].
* **Стек:** Kotlin, Ktor (HTTP API), Exposed, SQLite, Telegram Bot API[cite: 2, 3].
* **Фишки:** 
  * Продажа подписки SMP+ и пакетов изумрудов за внутреннюю валюту Telegram Stars[cite: 2].
  * Автоматическая генерация уникальных одноразовых кодов активации после оплаты[cite: 2].
  * Встроенный HTTP API для бесшовной интеграции с сайтом и безопасного погашения кодов в личном кабинете[cite: 2].

---

## 💻 Технологический Стек Организации

| Backend / Game API | Web & Discord bot | Telegram Bot | Databases & Infra |
|--------------------|-------------------|--------------|-------------------|
| ![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=flat-square&logo=kotlin&logoColor=white) | ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) | ![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=flat-square&logo=kotlin&logoColor=white) | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| ![Java 21](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white) | ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white) | ![Ktor](https://img.shields.io/badge/Ktor-087CFA?style=flat-square&logo=ktor&logoColor=white) | ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| ![Paper](https://img.shields.io/badge/PaperMC-000000?style=flat-square&logo=paper&logoColor=white) | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) | | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |
| | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) | | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |

---

## 📈 Главные достижения

1. **Беспрецедентная оптимизация:** Стабильные `20.0 TPS` при спаме сотнями сущностей, работая на бюджетном сервере[cite: 1].
2. **Нулевая зависимость:** 90% кода (от капчи при входе до расширения мира) написано нашей командой с нуля без использования "тяжелых" плагинов[cite: 1].

---

## 🔗 Присоединяйтесь к нам

Мы всегда открыты для баг-репортов, предложений и новых игроков[cite: 1].

- 🎮 **IP Сервера:** `play.lastsmp.ru` (Версия 1.21+)[cite: 4]
- 🌐 **Сайт:** last-smp.net
- 💬 **Discord:** Ссылка в футере сайта[cite: 4]
