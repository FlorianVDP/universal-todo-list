# Todo Universe

This project is a universal **Todo App** implemented in multiple languages and frameworks, both frontend and backend, to explore different ecosystems and architectures.

## 🚀 Project Goals
- Build a consistent Todo List App with CRUD features.
- Explore the syntax, tooling, and strengths of each stack.
- Use a mono-repo architecture for easy navigation and consistency.
- Learn and compare backend and frontend patterns across languages.

## 📁 Structure
```
todo-universe/
├── backend/        # All backend implementations
├── frontend/       # All frontend implementations
├── docker/         # Shared Docker services (PostgreSQL etc.)
├── docker-compose.yml
└── README.md       # This file
```

## 🧱 Features to implement in each version
- [ ] Create a task
- [ ] Get all tasks
- [ ] Update a task
- [ ] Delete a task
- [ ] Mark task as completed
- [ ] Optional: Priority, due date, tags
- [ ] Optional: Authentication (JWT / OAuth)

---

## 🧪 Technology Todo List

### Frontend
- [ ] React
- [ ] Vue 3
- [ ] Angular
- [ ] Svelte
- [ ] SolidJS
- [ ] Flutter Web
- [ ] Vanilla JS + HTMX

### Backend
- [ ] Node.js (Express + TypeORM)
- [ ] Go (Gin / Fiber)
- [ ] Python (FastAPI / Django)
- [ ] Java (Spring Boot)
- [ ] PHP (Laravel)
- [ ] C# (ASP.NET Core)
- [ ] Ruby (Rails)
- [ ] Rust (Actix / Axum)
- [ ] Kotlin (Ktor)
- [ ] Elixir (Phoenix)

---

## 🐳 Run the project
You must have Docker installed.

```bash
# Start backend + postgres
docker compose up backend db

# Or start all services
docker compose up
```

## 📬 Contributions
This project is designed to evolve over time. Contributions, fixes, or adding new languages/frameworks are welcome!
