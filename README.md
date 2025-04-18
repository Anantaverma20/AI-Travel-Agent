# 🌍 AI Travel Agent

An interactive AI-powered travel planning assistant that generates personalized itineraries, AI voiceovers, destination images, and cinematic videos — all from a single prompt.

![Screenshot 2025-02-16 161217](https://github.com/user-attachments/assets/8575e242-3413-446d-b74d-74c2ea75ba37)


---

## ✨ Features

- 🗺️ **AI Itinerary Generator** – Custom travel plans using LLaMA 3 via Ollama.
- 🔊 **Voiceover Creation** – Google TTS for immersive travel narration.
- 🖼️ **Image Generation** – Beautiful visuals using DALL·E-style image tools.
- 🎞️ **Video Generator** – Generate short cinematic travel videos using LumaAI.
- 🤖 **Chat Agent Ready** – Easily extendable with LangChain Agents for booking, weather, etc.

---

## 🛠️ Built With

- **Frontend**: HTML, CSS (Bootstrap, custom styles)
- **Backend**: Python + Flask
- **AI Tools**: Ollama, OpenAI GPT-4o, Google TTS
- **Media APIs**: LumaAI API for videos, OpenAI DALL-E API for images, Google Cloud

---

## 📁 Project Structure

```bash
AI-Travel-Agent/
│
├── app.py                 # Flask backend
├── config.txt             # API keys and config
├── load_config.py         # Environment loader
│
├── templates/
│   └── index.html         # Frontend layout
│
├── static/
│   ├── styles.css         # UI styles
│         
│
└── README.md              # You're here!
```

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.9+
- Git
- A modern browser

### 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Anantaverma20/AI-Travel-Agent.git
   cd AI-Travel-Agent
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv .venv
   .venv\Scripts\activate   # Windows
   source .venv/bin/activate  # macOS/Linux
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up API Keys**:
   - Edit `config.txt` with your keys:
     ```
     GOOGLE_TTS_KEY=
     OLLAMA_MODEL=llama3
     OPENAI_API_KEY=
     LUMA_API_KEY=
     ```

5. **Run the app**:
   ```bash
   python app.py
   ```
   The app will launch on `http://127.0.0.1:5000/`


---

## 📌 Future Improvements

- [ ] Integrate chatbot using LangChain or Gemini
- [ ] Enable real hotel/flight searches via Amadeus or Skyscanner APIs
- [ ] Offline itinerary downloads
- [ ] User login to save past trips

---

## 🤝 Contribution Guide

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request!


---

## 👤 Author

- **Ananta Verma**
- [LinkedIn](https://www.linkedin.com/in/ananta-verma)
- [Portfolio](https://anantas-portfolio-d0858a.webflow.io/)

---
