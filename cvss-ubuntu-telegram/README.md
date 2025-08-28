# CVSS Ubuntu → Telegram

Envía **avisos de seguridad de Ubuntu** a **Telegram** filtrando por un umbral mínimo de CVSS.

- **Stack**: n8n (Cron + HTTP Request + Function + Telegram)
- **Fuente**: Ubuntu Security Notices (RSS)
- **Salida**: Mensaje en Telegram con título, CVEs, CVSS y enlace

## Variables de entorno

Ver [`examples/.env.example`](./examples/.env.example).

## Instalación

1. Importa `blueprint/cvss-ubuntu-telegram.json` en n8n.
2. Configura las variables de entorno (`TELEGRAM_BOT_TOKEN`, `TELEGRAM_CHAT_ID`, `UBUNTU_FEED_URL`, `MIN_CVSS`).
3. Activa el workflow.

## Licencia

MIT. Ver [LICENSE](../LICENSE).
