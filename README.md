# ✦ Lashhh AI Chatbot

A sleek, futuristic AI chatbot powered by the Groq API, with a responsive UI inspired by ChatGPT.

## Features

- Modern, responsive chat UI with a pink-purple theme
- Powered by Groq AI
- Voice input support
- Markdown rendering in responses
- Auto-growing textarea
- Mobile-friendly design

## Tech Stack

HTML · CSS · JavaScript · Groq API

## Preview

*(keep your existing preview images here)*

## Setup

```bash
git clone https://github.com/LashminiAD/Lashh-ChatBot.git
```

Open `bot.html` in your browser, enter your Groq API key when prompted, and start chatting.

Get a free API key at [console.groq.com/keys](https://console.groq.com/keys).

## ⚠️ Known Limitation

This is a client-side demo project — the Groq API key is stored in the browser's `localStorage` for convenience, which means it's **not encrypted and is readable by anyone with access to the browser** (devtools, extensions, or anyone using the same device). Don't use a key tied to a paid/production Groq account here. A safer approach for a real deployment would route requests through a small backend so the key never reaches the browser at all — this is on the future improvements list.

## Future Improvements

- Move API key handling to a backend proxy (remove client-side key storage)
- Chat history persistence
- User authentication
- Theme switcher
- File upload support

## License

MIT

## Author

**Lashmini Anand** — [@LashminiAD](https://github.com/LashminiAD)
