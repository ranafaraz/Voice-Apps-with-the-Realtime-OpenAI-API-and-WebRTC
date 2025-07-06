# 🎙️ Voice Apps with the Realtime OpenAI API and WebRTC

This project demonstrates a real-time voice-enabled web application built using WebRTC, Node.js, and the OpenAI API. It allows users to speak with an AI assistant directly from their browser using microphone input and receive real-time, natural language responses.

## 🚀 Features

- **Live Voice Capture** using WebRTC
- **Streaming Speech-to-Text** (STT) with the OpenAI API
- **Dynamic AI Responses** via OpenAI’s GPT models
- **Text-to-Speech (TTS)** to convert AI responses into spoken audio
- **Real-Time Interaction Loop**: speak, process, respond — all seamlessly

## 🛠️ Technologies Used

- Node.js
- Express.js
- Vanilla JavaScript (Front End)
- WebRTC
- WebSockets
- OpenAI API (Streaming)
- Text-to-Speech (Web Speech API)

## 📁 Project Structure

```
├── public/
│   ├── index.html         # Main UI
│   ├── styles.css         # Basic styling
│   └── app.js             # Client-side logic for audio and WebSocket
├── server.js              # Node/Express WebSocket server
├── package.json
└── README.md
```

## 🔧 Setup Instructions

1. Clone the repo:
   ```bash
   git clone <this-repo-url>
   cd <project-folder>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file and add your OpenAI API key:
   ```
   OPENAI_API_KEY=your_openai_key_here
   ```

4. Start the server:
   ```bash
   node server.js
   ```

5. Open `http://localhost:3000` in your browser and start speaking.

## 🧪 Demo

> Live voice conversation with a GPT-based AI assistant in your browser using your mic.

---

## 📄 License

This project is intended for learning and experimentation. No personal identity or proprietary data is included. Contributions welcome!
