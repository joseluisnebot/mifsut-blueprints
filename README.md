# MIFSUT Blueprints 🚀

Colección oficial de **blueprints de automatización** mantenidos por [MIFSUT](https://mifsut.com).  
Incluye flujos listos para importar en **[n8n](https://n8n.io/)**, centrados en seguridad, monitorización y notificaciones multicanal.

## 📂 Blueprints disponibles

### 1. [CVSS Ubuntu → Telegram](https://mifsut.com/blueprints/cvss-ubuntu-telegram)
Envía avisos de seguridad de Ubuntu a Telegram filtrando por un umbral mínimo de CVSS.  
- **Stack**: n8n (Cron + HTTP Request + Function + Telegram)  
- **Fuente**: [Ubuntu Security Notices](https://ubuntu.com/security/notices)  
- **Salida**: Mensaje formateado en Telegram con CVEs y enlaces oficiales  
- **Descarga**: [Última versión](https://github.com/mifsut/mifsut-blueprints/releases/latest)

---

## 🚀 Uso rápido

1. Descarga el `.json` de un blueprint desde la sección [Releases](https://github.com/mifsut/mifsut-blueprints/releases).
2. En **n8n**, importa el archivo (`Workflows → Import from File`).
3. Configura las variables de entorno según la documentación del blueprint.
4. Activa el workflow y comienza a automatizar.

---

## 📖 Documentación detallada

Cada blueprint incluye:
- `README.md` con explicación, instalación y variables de entorno.  
- `blueprint/` con el flujo en formato `.json`.  
- Ejemplo de `.env`.  
- Changelog y notas de seguridad.

👉 Además, puedes ver la documentación extendida y guías en [mifsut.com/blueprints](https://mifsut.com/blueprints).

---

## 🔒 Seguridad

- Nunca publiques tus credenciales en el repositorio.  
- Usa **variables de entorno** en n8n (`.env` o panel de Settings).  
- Rota periódicamente tokens y claves de API.  

---

## 📜 Licencia

Este repositorio se publica bajo licencia [MIT](./LICENSE).  
Puedes usar, modificar y compartir los blueprints libremente, citando la autoría de MIFSUT.

---
