1. Запускаем PostgreSQL и pgAdmin:
```bash
docker compose up -d
```

2. Откройте браузер на странице `http://localhost:5050` (если не меняли порт pgAdmin'а).
3. Подключитесь к базе через внешний IP адрес вашей машины (можно найти через `ipconfig` в Windows или `ifconfig` в Linux/MacOS), укажите порт, укажите логин/пароль (если не меняли в YAML файле - `admin`/`admin`.
