# iChat

## Конфигурация
Приложение запускается через docker compose.

Перед запуском нужно скачать код из репозитория сервиса чата и SSO-сервиса, для этого выполнить в корневой папке команды:
```
git clone https://github.com/kkonst40/chat-service.git
git clone https://github.com/kkonst40/sso-service.git
```

Для запуска используется команда:
```
docker compose up -d --build`  
```
или, при наличии Make:
```
make build
```