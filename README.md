# Hi, I'm Jhonatan 👋

I'm a Python backend developer focused on building APIs, automation workflows, and SaaS backends.

I enjoy turning real-world problems into clean, scalable backend systems.

---

## 🧠 What I build

[ Client / UI ]
       |
       v
[ REST API — FastAPI ]
       |
       v
[ Business Logic ]
       |
       +── Automation & Workflows
       +── Chatbots / Webhooks
       +── Data Processing (CSV / JSON)
       |
       v
[ External APIs ]
(Google, WhatsApp, CRMs, Email, etc.)

---

## ⚙️ Example: API-first mindset

python
@app.post("/webhook/inbound")
async def handle_message(payload: InboundMessage):
    intent = classify_intent(payload.text)
    response = bot_router(intent, payload.text)
    return {"reply": response}

This structure keeps a clean separation between:

* input validation
* intent detection
* business rules
* external integrations

---

## 🧪 Recent work

* WhatsApp Business Platform chatbot (CSV-driven)
* Automation flows triggered by chat commands
* Bulk messaging simulation with delivery metrics
* Fully documented APIs using Swagger / OpenAPI
* Docker-ready backend services

---

## 🛠️ Tech stack

* Python · FastAPI · Pydantic
* REST APIs · Webhooks
* Docker · OpenAPI / Swagger
* Data-driven workflows
* LLM-ready architectures

---

## 🚀 What I'm doing now

Building small but complete backend products to demonstrate:

* real-world architecture
* production-ready patterns
* automation-first design

📫 Open to freelance and contract work.

```
