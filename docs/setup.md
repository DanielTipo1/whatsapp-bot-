# Setup rápido (n8n + WhatsApp + GPT)

## Requisitos
- Docker y Docker Compose instalados.
- API Key de OpenAI.
- WhatsApp Cloud API (Meta) o 360dialog (API URL + API Key).
- URL pública para n8n (puede ser temporal al inicio).

## 1) Variables
Crea `.env` a partir de `.env.example` y rellena:
- OPENAI_API_KEY=
- WHATSAPP_API_URL=
- WHATSAPP_API_KEY=
- WEBHOOK_URL=  (ej. http://localhost:5678/ o tu dominio)

## 2) Levantar n8n
```bash
docker compose up -d
