# Setup del Bot de WhatsApp (n8n + GPT)

## Requisitos
- Docker y Docker Compose instalados (VPS o tu PC).
- Cuenta de OpenAI (API Key).
- WhatsApp Cloud API (Meta) **o** proveedor compatible (360dialog, Twilio, etc.).
- Dominio/URL pública para n8n (HTTPS recomendado).

## 1. Clonar y variables
```bash
git clone https://github.com/<TU-USUARIO>/whatsapp-bot.git
cd whatsapp-bot
cp .env.example .env   # edita tus claves reales
