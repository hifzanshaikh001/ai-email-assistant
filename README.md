````markdown
# 🚀 AI Email Assistant

<p align="center">

![Java](https://img.shields.io/badge/Java-17-orange?style=for-the-badge)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?style=for-the-badge)
![React](https://img.shields.io/badge/React-blue?style=for-the-badge)
![Vite](https://img.shields.io/badge/Vite-purple?style=for-the-badge)
![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-success?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-2.5%20Flash-blueviolet?style=for-the-badge)

</p>

An AI-powered Chrome Extension that generates professional email replies directly inside Gmail using Google Gemini 2.5 Flash. The extension communicates with a Spring Boot backend to securely generate AI responses without exposing API keys.

---

## ✨ Features

- 🤖 AI-powered email reply generation
- 🎯 Multiple reply tones (Professional, Friendly, Formal, Casual)
- 📋 One-click copy to clipboard
- 🌐 Chrome Extension integration
- ⚡ Spring Boot REST API
- 🔒 Secure backend architecture
- 💻 React + Vite frontend
- 🚀 Fast AI response generation

---

## 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Frontend | React, Vite, HTML, CSS, JavaScript |
| Backend | Java, Spring Boot |
| AI | Google Gemini 2.5 Flash |
| Browser | Chrome Extension API |
| Tools | Git, GitHub |

---

## 🏗 Architecture

```text
User
   │
   ▼
Chrome Extension
   │
HTTP Request
   │
   ▼
Spring Boot Backend
   │
Gemini API
   │
   ▼
AI Generated Reply
   │
   ▼
Chrome Extension
```

---

## 📁 Project Structure

```text
ai-email-assistant/

├── email-writer-ext/
│
├── email-writer-frontend/
│
├── email-writer-sb/
│
└── README.md
```

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/hifzanshaikh001/ai-email-assistant.git
```

```bash
cd ai-email-assistant
```

---

## ⚙️ Backend Setup

```bash
cd email-writer-sb
```

Open

```text
src/main/resources/application.properties
```

Add your Gemini API key

```properties
gemini.api.key=YOUR_GEMINI_API_KEY
```

Run the backend

```bash
mvn spring-boot:run
```

Backend URL

```text
http://localhost:8080
```

---

## 💻 Frontend Setup

```bash
cd email-writer-frontend
```

Install dependencies

```bash
npm install
```

Run the project

```bash
npm run dev
```

Frontend URL

```text
http://localhost:5173
```

---

## 🌐 Chrome Extension

1. Open Chrome.
2. Go to `chrome://extensions`.
3. Enable Developer Mode.
4. Click **Load unpacked**.
5. Select the `email-writer-ext` folder.
6. Start the Spring Boot backend.
7. Open Gmail and generate AI replies.
````
```markdown
---

## ▶️ Usage

1. Start the Spring Boot backend.
2. Load the Chrome Extension in Chrome.
3. Open Gmail.
4. Open any email conversation.
5. Click the **AI Reply** button.
6. Select your preferred reply tone.
7. Click **Generate Reply**.
8. Copy the generated response and paste it into Gmail.

---

## 📸 Screenshots

> Screenshots will be added soon.

Suggested screenshots:

- Extension Popup
- Gmail AI Reply Button
- Generated Email Reply
- Spring Boot Backend Running

---

## 🔐 Security

- API keys are stored securely on the Spring Boot backend.
- The Chrome Extension never exposes the Gemini API key.
- Communication between the extension and backend is performed using REST APIs.

---

## 📌 Current Limitations

- The backend must be running locally.
- The extension currently communicates with `localhost`.
- Cloud deployment has not been implemented yet.

---

## 🚧 Future Improvements

- Deploy backend to Render or Railway
- Docker support
- User authentication
- Email history
- Regenerate AI replies
- Multiple AI model support
- Dark mode
- Reply length customization
- Streaming AI responses

---

## 👨‍💻 Author

**Hifzan Shaikh**

Computer Science Student

GitHub:
https://github.com/hifzanshaikh001

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ If you like this project

If you found this project useful, consider giving it a ⭐ on GitHub.
```
