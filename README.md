# GitLab + GitLab Runner docker compose 
Этот файл docker-compose.yml настраивает два сервиса:
- GitLab CE (Community Edition) – платформа для DevOps с CI/CD, репозиториями и управлением проектами.
- GitLab Runner – агент для выполнения CI/CD-пайплайнов.

Клонируйте репозиторий с GitHub:
```bash
git clone https://github.com/A3th3rS3t/GitLab.git
cd GitLab
```
Запуск сервиса: 
```bash
docker compose up -d
```

Первичная авторизация и ее настройка: 
https://docs.gitlab.com/user/profile/account/create_accounts/