
                                                AI Chatbot Capstone Projects

Generative AI + Retrieval-Augmented Generation (RAG)
This repository showcases two real-world AI chatbot solutions designed to solve high-impact customer support challenges using LLMs, RAG pipelines, and real-time data retrieval.

Projects Overview

Blink Assist- Airline Passenger Chatbot

An AI-powered assistant integrated into an airline platform to provide real-time support for passengers.

Key Capabilities:

 Flight status & delay updates (live APIs)
 Booking & rebooking assistance
 Baggage policies & travel advisories
 Instant responses with context awareness

Impact:

 60% reduction in call center volume
 24/7 passenger support
~$1.8M annual cost savings

HealthBridge AI (“Clara”) — Patient Support Chatbot

A HIPAA-compliant healthcare chatbot delivering accurate, real-time patient assistance using RAG.

Key Capabilities:

📅 Appointment scheduling & reminders
💊 Medication guidance
📝 Post-visit care instructions
💳 Insurance & billing FAQs

Impact:

📉 60% reduction in support calls
❤️ Improved patient engagement
💰 ~$1.4M annual cost savings
🧠 Architecture Overview

Both systems follow a Retrieval-Augmented Generation (RAG) pipeline:

User Query → Data Retrieval → Context Injection → LLM Response
🔧 Core Components
Frontend: React / React Native
Backend: FastAPI
Vector DB: Pinecone
LLMs: OpenAI / Anthropic Claude
Cloud: AWS (S3, Redis, CloudWatch)
🔍 Key Features
🔎 Semantic Search — fast retrieval using embeddings
🧠 Context-Aware Conversations — session-based memory
🛡️ Guardrails & Safety Controls
Hallucination prevention
Policy validation
Escalation to human agents
📊 Audit Logging & Monitoring
⚡ Real-Time API Integration
🔐 Compliance & Safety
Aviation (Blink Assist)
Policy validation against airline data
Real-time flight data verification
Full audit traceability
Healthcare (HealthBridge AI)
HIPAA-compliant architecture
PHI encryption & access control
Medical response validation via trusted APIs
📊 Data Sources
Airline Chatbot
Airline Operations APIs
Booking systems (GDS)
Travel advisory APIs
Real-time web data
Healthcare Chatbot
EHR systems (FHIR APIs)
Clinical policy documents
FDA / MedlinePlus APIs
Medical knowledge sources
📈 Evaluation & Accuracy
✅ ≥92% accuracy target via A/B testing
📌 100% source citation enforcement
🔁 Continuous feedback loop
🧪 Monthly red-team testing
🚀 Getting Started
Prerequisites
Python 3.9+
Node.js
API keys (OpenAI / Anthropic)
Pinecone account
Installation
git clone https://github.com/your-repo/ai-chatbot-capstone.git
cd ai-chatbot-capstone

# Backend
pip install -r requirements.txt

# Frontend
cd client
npm install
Run the App
# Backend
uvicorn app.main:app --reload

# Frontend
npm start
🧩 Future Improvements
🤖 Multi-modal support (voice + images)
🌍 Multi-language capabilities
📊 Advanced analytics dashboard
