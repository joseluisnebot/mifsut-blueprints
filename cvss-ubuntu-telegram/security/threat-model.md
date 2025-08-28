# Threat Model – CVSS Ubuntu → Telegram

- **Datos procesados**: Avisos públicos de Ubuntu Security Notices.
- **Credenciales sensibles**: `TELEGRAM_BOT_TOKEN`, `TELEGRAM_CHAT_ID`.
- **Riesgos**:
  - Fuga del token → acceso no autorizado al bot.
  - Spam en el chat si la frecuencia es demasiado alta.
- **Mitigaciones**:
  - Usar variables de entorno en n8n.
  - Rotar el token periódicamente.
  - Limitar el bot al chat necesario.
