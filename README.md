# n8n Outlook AI Auto Reply

Workflow de n8n que responde automáticamente emails de Outlook usando OpenAI (GPT-5).

## 🚀 Qué hace

- Escucha emails entrantes en Outlook
- Filtra spam básico
- Usa IA para generar respuestas profesionales
- Envía la respuesta automáticamente

## 🧠 Stack

- n8n
- Microsoft Outlook Trigger
- OpenAI (GPT-5)
- LangChain Agent

---

## ⚙️ Cómo usarlo

### 1. Importar workflow en n8n
- Abre n8n
- Click en **Import Workflow**
- Sube `workflow.json`

---

### 2. Configurar credenciales

Necesitas:

- Microsoft Outlook OAuth2
- OpenAI API Key

Configúralos en:
- Settings → Credentials

---

### 3. Variables necesarias

Este workflow usa:

- Outlook email
- OpenAI API key


## 🧪 Lógica del workflow

1. Trigger: nuevo email en Outlook
2. IF: filtro básico anti-spam
3. AI Agent: genera respuesta
4. Outlook: envía respuesta automática

---

## ⚠️ Importante

- Usa GPT-5 (puedes cambiar modelo)
- Revisa costes de OpenAI
- Prueba en entorno sandbox antes de producción
