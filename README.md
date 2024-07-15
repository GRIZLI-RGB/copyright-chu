# Платформа с онлайн-курсом для копирайтеров

## 1. Технологический стек
Frontend:

- Next
- Typescript
- React Query
- Tailwind
- Redis
- MobX
- Cypress
- Jest

Backend:

- FastAPI
- PostgreSQL
- SQLAlchemy
- Uvicorn

## 2. Запуск проекта

### 2.1. Frontend

Чтобы запустить Frontend в режиме разработки, требуется выполнить следующие команды в рабочей папке:

```bash
npm install
npm run dev
```

Далее нужно открыть адрес [http://localhost:3000](http://localhost:3000) в браузере.

### 2.2. Backend

Чтобы запустить Backend в режиме разработки, требуется выполнить следующие команды в рабочей папке:

```bash
pipenv shell
uvicorn --factory src.main:create_app --reload
```

Далее нужно открыть адрес [http://127.0.0.1:8000](http://127.0.0.1:8000) в браузере.