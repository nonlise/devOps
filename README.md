# Тестовое задание: Junior DevOps

## Выполненные задания

### 1. Подготовка окружения
- Установлены пакеты: git, curl, wget, nano.
- Создан скрипт `startup-script.sh`, который логирует время старта системы.
- Настроен автозапуск через systemd (`startup-script.service`).

### 2. GitLab CI/CD
- Файл `.gitlab-ci.yml` настроен для проверки версий Git и Nginx.
- Используется образ `ubuntu:20.04`.
- Логи Nginx сохраняются как артефакты.

### 3. Docker
- Создан `Dockerfile` на основе `nginx:stable`.
- На главной странице выводится "Hello from DevOps!".
- Инструкции для сборки и запуска:
  ```bash
  docker build -t devops-nginx .
  docker run -d -p 8080:80 devops-nginx

### answers.md (ответы на вопросы)
### com (скриншоты)
