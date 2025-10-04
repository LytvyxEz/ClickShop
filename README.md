# 🚀 Fullstack App — Django REST + React + Docker

This project is a **fullstack web application** built with:
- ⚡ **Backend:** [Django REST Framework](https://www.django-rest-framework.org/)
- 🎨 **Frontend:** [React](https://react.dev/)
- 🐳 **Docker + Docker Compose** for containerization and easy deployment

---

yaml
---

## 🔧 Prerequisites
You need the following installed:
- [Docker](https://www.docker.com/get-started) 🐳
- [Docker Compose](https://docs.docker.com/compose/)

---

## ⚙️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/username/project-name.git
cd project-name
```
2. Start the containers
bash```
docker-compose up --build```
Frontend: http://localhost:3000
Backend API: http://localhost:8000

3. Run migrations
If the database is empty:

bash```
docker-compose exec backend python manage.py migrate
docker-compose exec backend python manage.py createsuperuser
yaml```


