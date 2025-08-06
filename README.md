# 👋 Hi, I'm Sajjad Naqvi

Welcome to my GitHub! I'm an AI and voice interface developer with experience in real-time speech systems, Flask APIs, and cross-platform Flutter apps. I’ve recently built a suite of intelligent voice agents for domains like hospitality, healthcare, blue-collar services, and pet care.

---

## 🔊 Voice Agent Projects

### ✅ 1. Restaurant Voice Assistant
- **Purpose:** Helps customers place orders, ask about the menu, and make reservations.
- **Tech Stack:** Whisper (STT), gTTS (TTS), Flask, Mistral via Groq, LangChain-style architecture
- **Features:** Conversational memory, local voice I/O, JSON logging, GUI & terminal support
- **Path:** `Datalytics/VOIP/Restaurant-agent`

### ✅ 2. Clinic Appointment Assistant
- **Purpose:** Assists patients with doctor schedules and bookings.
- **Upgrades:** Gemini API, Pinecone for embeddings, improved conversation context

### ✅ 3. Blue-Collar Service Agent – *Gullu*
- **Purpose:** Assigns plumbers, electricians, and more via VoIP.
- **VoIP Integration:** FreeSWITCH + Zoiper
- **Features:** Real-time Whisper STT, interruptible TTS, memory, JSON logging

### ✅ 4. Pet Care Voice Agent – *Alamgir*
- **Purpose:** Friendly vet appointment assistant
- **Unique Traits:** Uses slang, local tone, Flask GUI with real-time mic listening
- **Backend:** Whisper, gTTS (to be upgraded), Ollama (Mistral)

### ✅ 5. Real Estate Voice Agent (Planned)
- **Purpose:** Guides users in buying/renting homes
- **Status:** Mock dialogues + Notion template planned

### ✅ 6. Nutritionist Voice Agent (Planned)
- **Purpose:** Personalized voice diet planner
- **Status:** Structure drafted, build pending

### ✅ 7. Courier/Delivery Assistant (Planned)
- **Purpose:** Track parcels, schedule pickups
- **Features:** Track ID logic, address parsing

### ✅ 8. Consultant Voice Receptionist
- **Purpose:** Live call receptionist with greeting logic
- **Current Task:** Finalizing FreeSWITCH barge-in support

---

## 🧠 Shared Features Across Agents
- **Real-time STT (Whisper)**
- **Interruptible TTS (chunk-based)**
- **Session Memory & Logs**
- **Flask API endpoints per agent**
- **Voice GUI or CLI-based control**
- **Conversation history stored in `memory.py`**

---

## 🔧 Core Backend Modules
- `memory.py`: Handles session memory
- `agent.py`: Sends queries to LLM (Groq/Ollama/Gemini)
- `tts.py`: Real-time audio output with interruption
- `stt.py`: Whisper-based transcription
- `interrupt.py`: Detects user speech for barge-in
- `logger.py`: JSON logging with timestamps
- `run_server.py`: Flask-based main server

---

## 🚧 Upcoming Features / Improvements
- Switch from gTTS to faster TTS (e.g. Bark, Piper)
- Live streaming STT (Whisper streaming)
- Docker-based deployment
- Centralized Notion-style documentation

---

## 📱 Flutter Projects (Past Highlights)
- 🔹 **Smart Inventory App** – Scanned and managed product inventory with Firebase
- 🔹 **Crypto Dashboard** – Real-time prices & chart visualization
- 🔹 **Voice ChatBot UI** – ChatGPT-based frontend using voice
- 🔹 **Todo Manager App** – Custom animations, state management (Provider)
- 🔹 **Portfolio App** – Fully responsive portfolio with project showcase

---

## 📫 Let's Connect!
Feel free to explore my repositories or reach out to collaborate on AI, voice agents, or Flutter apps.

