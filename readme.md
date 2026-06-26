# Sotto — A Private Voice Memory App

> *Sotto Voce: to speak quietly, under your breath.*

<p align="center">
  <img src="assets/logo.png" alt="Sotto Logo" width="120" />
</p>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.sotto.memories">
    <img src="https://img.shields.io/badge/Google_Play-Available-4CAF50?style=flat&logo=google-play&logoColor=white" />
  </a>
<a href="https://www.producthunt.com/products/sotto-5?embed=true&amp;utm_source=badge-featured&amp;utm_medium=badge&amp;utm_campaign=badge-sotto-64b8bedd-b163-4f0f-908d-8b2a0fb441d5" target="_blank" rel="noopener noreferrer"><img alt="Sotto - Never forget a memory again. Just speak. | Product Hunt" width="250" height="54" src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=1174120&amp;theme=dark&amp;t=1782430078433"></a>
  <a href="https://github.com/rudradave1/sotto-app">
    <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=flat&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-Multiplatform-7F52FF?style=flat&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat" />
  <a href="https://www.shipit.buzz/products/sotto?ref=badge" target="_blank" rel="noopener noreferrer"><img src="https://www.shipit.buzz/api/products/sotto/badge?theme=dark" alt="Featured on Shipit" /></a>
</p>

<p align="center">
  <a href="https://open-launch.com/projects/sotto" target="_blank" rel="noopener">
    <img src="https://open-launch.com/api/badge/21e8245e-ceeb-45fc-bb66-be81d6127bc5/featured-dark.svg" alt="Featured on Open-Launch" width="200" height="50" />
  </a>
</p>

---

Sotto is a private, voice-first memory app for people who think out loud.

Instead of typing notes or journal entries, you simply speak. Sotto captures your words, transcribes them privately, structures them with AI, and helps you build a searchable archive of memories, ideas, experiences, and moments worth keeping.

No prompts. No streaks. No pressure to write. Just speak and move on.

---

## Download

<a href="https://play.google.com/store/apps/details?id=com.sotto.memories">
  <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" width="200" />
</a>

---

## Why Sotto Exists

Most people don't forget because they have bad memories.

They forget because life moves fast.

Ideas during walks. Recommendations from friends. Lessons learned. Small moments that matter.

The problem isn't that these things aren't important. It's that capturing them usually requires stopping what you're doing and typing everything out.

Sotto removes that friction.

Press record. Speak naturally. Done.

---

## Features

* 🎙 **Voice-first capture** — preserve memories by speaking naturally
* 🔒 **Encrypted local storage** — SQLCipher AES-256 protection
* 🤖 **AI-powered organization** — automatic titles, tags, mood, category, and reflection
* 🔍 **Full-text search** — instantly find past memories
* 📊 **Patterns & insights** — discover mood trends and recurring themes
* ⭐ **Starred memories** — save important moments for later
* 🌐 **Multilingual support** — English and Hindi
* 📴 **Offline mode** — fully local transcription with Vosk
* 🎯 **Accurate mode** — Groq Whisper transcription with Zero Data Retention
* 🔄 **Background processing** — memories continue processing even when the app is closed

---

## Privacy Promise

Your memories belong to you.

* No ads
* No tracking
* No behavioral analytics
* No selling your data
* SQLCipher encrypted local database
* Groq Zero Data Retention in Accurate mode
* Fully offline transcription available
* Local-first architecture

You control your memories. Always.

---

## Tech Stack

| Layer                   | Technology                           |
| ----------------------- | ------------------------------------ |
| Language                | Kotlin Multiplatform                 |
| Android UI              | Jetpack Compose                      |
| Navigation              | Voyager                              |
| Database                | SQLDelight + SQLCipher               |
| Networking              | Ktor                                 |
| Dependency Injection    | Koin                                 |
| Background Processing   | WorkManager                          |
| Cloud Transcription     | Groq Whisper (whisper-large-v3)      |
| AI Structuring          | Groq Llama (llama-3.3-70b-versatile) |
| On-device Transcription | Vosk                                 |
| API Proxy               | Cloudflare Workers                   |

---

## Architecture

```text
Record Audio
      ↓
Store Local Audio
      ↓
Background WorkManager Job
      ↓
Whisper Transcription (Groq or Vosk)
      ↓
AI Structuring Pipeline (Llama)
      ↓
Encrypted Database Storage (SQLCipher)
      ↓
Memory Timeline UI
```

Offline-first. Privacy-first. Clean Architecture.

```
Presentation → Domain → Data
```

---

## Roadmap

* [ ] On This Day memory resurfacing
* [ ] Semantic memory search
* [ ] Life chapter clustering
* [ ] Gujarati language support
* [ ] Cloud backup & sync
* [ ] iOS client

---

## Thanks & Credits

Sotto wouldn't be possible without these incredible projects and teams.

### Groq

Blazing-fast Whisper transcription and Llama inference with Zero Data Retention.

https://groq.com

### Vosk

Open source speech recognition that enables fully offline transcription.

https://alphacephei.com/vosk

### SQLCipher

Transparent AES-256 encryption for SQLite databases.

https://www.zetetic.net/sqlcipher

### Jetpack Compose

Modern Android UI toolkit.

https://developer.android.com/compose

### Kotlin Multiplatform

Shared business logic across platforms.

https://kotlinlang.org/docs/multiplatform.html

---

## Contact

Built with ❤️ by **The Solitary Dev**

📧 [sottoapp.help@gmail.com](mailto:sottoapp.help@gmail.com)

GitHub: https://github.com/rudradave1/sotto-app

---

*Sotto — speak freely. Your memories stay yours.*
