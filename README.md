# Kittygram — Платформа для обмена фотографиями котиков
---

## Технологии

- **Backend:** Django REST Framework  
- **Frontend:** React  
- **База данных:** PostgreSQL  
- **Контейнеризация:** Docker  
- **CI/CD:** GitHub Actions  
- **Развертывание:** Docker compose  

---

## Структура проекта

Проект состоит  компонентов:

- `backend/` - Django сервер  
- `frontend/` - React приложение  
- `nginx/` - конфигурации для прокси сервера
- `tests/` - Тесты для frontand и backend
- `.github/workflows/` —  GitHub Actions CI/CD пайплайн  

---

## Быстрый старт
### Предварительные требования

- Docker и Docker Compose  
- Аккаунт на Docker Hub  
- Python 3.8+ (для локальной разработки)

### Запуск в контейнерах

```bash
docker compose up -d
```
