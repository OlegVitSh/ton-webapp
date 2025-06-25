# Ladder Levels TON Bot

Telegram-бот с уровневой системой и оплатой через TON (Tonkeeper/TonConnect).

## 📦 Структура
- `bot/` — логика бота и конфигурации
- `web/` — WebApp для оплаты через TonConnect
- `ton_webhook.py` — сервер, принимающий уведомления об оплате
- `.env` — конфигурационные данные (TON и токен бота)

## 🚀 Запуск
```bash
pip install -r requirements.txt
python bot/main.py
python ton_webhook.py
```

## 🐳 Docker
```bash
docker build -t ton-ladder-bot .
docker run -p 8080:8080 --env-file .env ton-ladder-bot
```

## 💰 Адрес TON:
`UQCijAB8cHLJM54kBIHCiqHNiduac0JNIH_1iZsCzc65m3zj`
