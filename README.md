# Hi, I'm Dhanush Kumar 👋

**Full-stack developer** who ships complete products: frontend, REST API, database, and deployment. I build tools that real users rely on: an AI admission helpdesk, an internship portal, a Telegram freelance marketplace, and a school management app headed for the Play Store.

- 🚀 Run **DS Tech Developers**, building digital tools for schools and colleges
- 🎓 Vice President, **SAP Tech Club** · PR Domain Head, **CINTEL Student Association**
- 🔍 Open to **software engineering internships** and freelance projects

<!-- CONTACT -->

---

## 🛠️ Tech stack

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)

| Area | What I use |
|---|---|
| Frontend | React, Next.js (App Router), TypeScript, Tailwind CSS, Framer Motion |
| Backend | Node.js, Express, REST API design, JWT auth, bcrypt |
| Data | MySQL (schema design, views, triggers, stored functions), Supabase, Google Sheets API |
| AI | Local LLMs with Ollama, retrieval from SQL data, OpenAI Moderation API |
| Mobile | Flutter, Dart |
| Bots and DevOps | Python, python-telegram-bot, APScheduler, Docker, Render, Git |

---

## ⭐ Featured projects

### 🤖 [SRM Query.AI](https://github.com/dhanushkumat04062007-ship-it/admission-query-chat-bot-SRM-): AI admission helpdesk
An admission chatbot for SRMIST that answers course, fee and hostel questions. It retrieves matching rows from MySQL and grounds a local LLM's answer in them, so it doesn't make up fees or deadlines.
- Retrieval from live SQL data, then generation with **Llama 3 via Ollama**; falls back to plain database answers if the model is offline
- Three roles (guest, allow-listed student, admin) with **JWT + role-based middleware** and bcrypt-hashed passwords
- MySQL schema with views, a trigger and a stored function; admin console with stats and allow-list management

`Next.js 16` `React 19` `TypeScript` `Express` `MySQL` `Ollama`

### 💼 [InternLink](https://github.com/dhanushkumat04062007-ship-it/Internlink): Internship portal
A two-sided marketplace: students search, apply and track applications; companies post openings and review applicants.
- 25+ REST endpoints covering auth, postings, applications, bookmarks, profiles and dashboard stats
- Search with category, job type and payment filters; unread badges when an application's status changes
- Relational schema with foreign keys and cascade deletes; **unique constraints block duplicate applications at the database level**

`React 19` `Express 5` `MySQL` `bcrypt`

### 🎬 [EditorsHub-AURA](https://github.com/dhanushkumat04062007-ship-it/editorshub-telebot): Telegram freelance marketplace
A bot that runs a video-editing marketplace end to end: orders, editor recruitment with a skill test, job assignment, payments and reviews.
- **AURA reputation system** ranks editors from Rookie to Legend based on delivery and ratings
- **Anonymous relay chat** with two-layer moderation (regex privacy filter + OpenAI Moderation API)
- Scheduled auto-approval, 15% margin tracking, and an admin revenue dashboard; about 3,400 lines of async Python, Dockerized

`Python` `python-telegram-bot` `Google Sheets API` `OpenAI` `Docker`

### 🏫 School Management App *(private, in testing for Play Store launch)*
A school management system for real schools, built with Flutter and Supabase.

`Flutter` `Dart` `Supabase`

### 🎓 [Unify-Ed](https://github.com/dhanushkumat04062007-ship-it/unify-ed): University assistant dashboard
A frontend prototype with role-based login, chat support, exam updates, timetable, question papers, complaints and faculty search.

`React` `Vite` `Tailwind CSS`

---

## 📈 Currently

- Launching the School Management App on the Play Store
- Deploying live demos of SRM Query.AI and InternLink
- Adding JWT authentication and automated tests to InternLink

