config-private.json format
```json
{
    "bot_name": "Freqtrade - TradingBot",
    "fiat_display_currency": "USD",
    "exchange": {
        "name": "binance",
        "key": "",
        "secret": ""
    },
    "telegram": {
        "enabled": false,
        "token": "",
        "chat_id": ""
    },
    "api_server": {
        "enabled": true,
        "listen_ip_address": "0.0.0.0",
        "listen_port": 8070,
        "verbosity": "info",
        "jwt_secret_key": "",
        "CORS_origins": [],
        "username": "freqtrader",
        "password": "freqtrader"
    }
}

'''