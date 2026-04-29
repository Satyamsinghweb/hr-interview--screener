# 🎙️ HR Interview Screener

> AI-powered voice interviews that screen candidates automatically — no recruiter required.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Bolna AI](https://img.shields.io/badge/Bolna-Voice%20AI-8B5CF6?style=for-the-badge)

---

## 🧠 About

**HR Interview Screener** is a voice AI-powered recruitment tool built on the [Bolna](https://bolna.ai) platform. It automates the initial HR screening round by conducting natural, human-like phone conversations with candidates — asking qualifying questions, evaluating responses, and pushing results back into your hiring workflow.

No more repetitive screening calls. Let the AI handle the pipeline while your team focuses on the candidates that actually matter.

---

## 🗂️ Project Structure

```
hr-interview--screener/
└── hr-interview-screener-bolna-main/   # Core Bolna voice agent integration
    ├── ...                              # Agent config, prompts & API logic
```

---

## ✨ Features

- 📞 Automated voice-based HR screening calls (inbound & outbound)
- 🤖 Natural, conversational AI powered by **Bolna Voice AI**
- 🌐 Multilingual support — English, Hindi, Hinglish & more
- 📋 Structured candidate data capture (notice period, availability, shift fit)
- ✅ Auto-categorization: Shortlisted / Rejected / Follow-up Required
- 📊 Call transcripts and analytics for every interview
- 🔗 ATS/HRMS integration ready via Bolna's API
- ⚡ Deploy and go live in minutes

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+)
- A [Bolna AI](https://bolna.ai) account
- A Bolna API key and configured phone number

---

### 1. Clone the Repository

```bash
git clone https://github.com/Satyamsinghweb/hr-interview--screener.git
cd hr-interview--screener/hr-interview-screener-bolna-main
```

---

### 2. Install Dependencies

```bash
npm install
```

---

### 3. Configure Environment Variables

Create a `.env` file in the project root:

```env
BOLNA_API_KEY=your_bolna_api_key
BOLNA_AGENT_ID=your_agent_id
PORT=3000
```

---

### 4. Start the Server

```bash
npm start
```

The server will be live at `http://localhost:3000`.

---

## 🛠️ Tech Stack

| Layer         | Technology                    |
|---------------|-------------------------------|
| Runtime       | Node.js / JavaScript          |
| Voice AI      | [Bolna AI Platform](https://bolna.ai) |
| Telephony     | Bolna (Twilio / Plivo backed) |
| Frontend      | HTML5, CSS3                   |

---

## 🔄 How It Works

```
Candidate receives call
        ↓
Bolna Voice Agent answers
        ↓
Structured screening questions asked
        ↓
Responses captured & evaluated
        ↓
Candidate tagged: Shortlisted / Rejected / Follow-up
        ↓
Data pushed to ATS / dashboard
```

---

## 💡 Sample Screening Flow

```
Agent  → "Hi, is now a good time for a quick screening call?"
Candidate → "Yes, sure."
Agent  → "Are you currently employed? What's your notice period?"
Candidate → "Yes, 30 days."
Agent  → "This role involves rotational shifts. Are you comfortable with that?"
Candidate → "Yes, I am."
Agent  → "Great! Your profile has been marked for the next round. Our team will reach out shortly."
```

---

## 🤝 Contributing

Pull requests are welcome!

1. Fork the repo
2. Create your branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add feature'`
4. Push: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Satyam Singh**
- GitHub: [@Satyamsinghweb](https://github.com/Satyamsinghweb)

---

## 🔗 Resources

- [Bolna AI Documentation](https://docs.bolna.dev/)
- [Bolna Recruitment Agent Templates](https://bolna.ai/agents/recruitment-agent)
- [Bolna API Reference](https://bolna.ai/apis)

---

> *"Hire smarter. Screen faster. Let the AI do the calling."*
