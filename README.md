# Brisa Task Manager

**Brisa Task Manager** — это кросс-платформенный менеджер задач, построенный на фреймворке **Brisa**.

Приложение позволяет пользователям создавать, отслеживать и совместно работать над задачами с реальным временем обновлений.

Используя возможности Brisa для работы с серверными компонентами, сигналами и веб-компонентами, проект стремится предоставить эффективный и современный подход к управлению задачами.

## 🛠️ Технологии

- **Brisa** — современный веб-фреймворк для создания full-stack приложений с использованием серверных компонентов и веб-компонентов.
- **JSX** — для написания как серверных, так и клиентских компонентов.
- **Web Components** — для создания переиспользуемых элементов интерфейса.
- **Signals** — для обработки событий в реальном времени.
- **Tauri** (по желанию) — для создания кросс-платформенных приложений.

Project created with [Brisa](https://github.com/brisa-build/brisa).

## Getting Started

### Installation

```bash
bun install
```

### Development

```bash
bun dev
```

### Build

```bash
bun build
```

### Start

```bash
bun start
```

> Это запустит приложение на вашем локальном сервере.

## 📄 Структура проекта
```plaintext
brisa-task-manager/
│
├── src/
│   ├── components
│   |   ├── counter-server.tsx
│   |   ├── footer.tsx
│   |   └── navigator.tsx
│   ├── layout
│   |   └── index.tsx
│   ├── pages
│   |   ├── about/
│   |   ├── index.test.tsx
│   |   └── index.tsx
│   ├── public
│   |   └── brisa.svg
│   ├── styles
│   |   ├── footer.css
│   |   ├── nav.css
│   |   └── style.css
│   └── web-components
│       └── counter-client.tsx
|
├── .gitignore
├── bun.lockb
├── bunfig.toml
├── package.json                 # Файл зависимостей проекта
├── tsconfig.json
└── README.md                    # Документация по проекту
```

---

### ⚙️ Функциональные возможности

- `Создание и управление задачами`: Пользователи могут создавать, редактировать и удалять задачи.

- `Реальное время`: Обновления задач происходят в реальном времени благодаря использованию сигналов.

- `Коллаборация`: Задачи можно делиться с другими пользователями для совместной работы.

- `Уведомления`: Пользователи получают уведомления о дедлайнах и изменениях в задачах.

- `Аутентификация`: Встроенная система аутентификации и управления профилем.

---

### 📬 Контакты
**Если у вас есть вопросы, не стесняйтесь обращаться:**

▶️ `Telephone:` +7-915-048-02-49

▶️ `Email`: maksimqwe42@mail.ru

▶️ `Twitter`: @MaksimDupley

---

### 🤝 Лицензия
`Этот проект лицензируется по лицензии MIT`
> См. LICENSE для подробностей

---

**Автор:** Дуплей Максим Игоревич

**Дата:** 21.11.2024