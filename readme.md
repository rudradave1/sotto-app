# Sotto — Your Life, In Your Own Words

> *Sotto Voce: to speak quietly, under your breath.*

<p align="center">
  <img src="assets/logo.png" alt="Sotto Logo" width="120" />
</p>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.sotto.memories">
    <img src="https://img.shields.io/badge/Google_Play-Available-4CAF50?style=flat&logo=google-play&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=flat&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-Multiplatform-7F52FF?style=flat&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat" />
</p>

---

Sotto is a private, voice-first memory app for people who think out loud.

Instead of typing journal entries, you simply speak. Sotto captures your words, transcribes them privately, structures your thoughts with AI, and builds a personal archive of your life over time.

No prompts. No streaks. No pressure to write. Just speak and move on.

---

## Download

<a href="https://play.google.com/store/apps/details?id=com.sotto.memories">
  <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" width="200" />
</a>

---

## Why Sotto Exists

Most journaling apps fail because writing is work.

People have memories, ideas, frustrations, wins, and moments worth preserving — but rarely have the energy to open a text editor and write a structured entry.

Sotto removes that friction entirely.

Press record. Speak naturally. Done.

---

## Features

- 🎙 **Voice-first** — no typing, ever
- 🔒 **Encrypted local storage** — SQLCipher AES-256
- 🤖 **AI reflections** — insight, mood, and tags from your words
- 🔍 **Full-text search** — find any memory instantly
- 📊 **Patterns** — weekly mood trends and memory activity
- ⭐ **Starred entries** — bookmark moments that matter
- 🌐 **Multilingual** — English and Hindi. Gujarati coming soon.
- 📴 **Offline mode** — 100% on-device transcription via Vosk
- 🔄 **Background processing** — entries process even when app is closed

---

## Privacy Promise

- No ads
- No tracking
- No behavioral analytics
- No selling your data
- SQLCipher encrypted local database
- Groq Zero Data Retention (Accurate mode)
- Full offline option available (Offline mode)
- You control your memories. Always.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Kotlin Multiplatform |
| Android UI | Jetpack Compose |
| Navigation | Voyager |
| Database | SQLDelight + SQLCipher |
| Networking | Ktor |
| Dependency Injection | Koin |
| Background Processing | WorkManager |
| Cloud Transcription | Groq Whisper (whisper-large-v3) |
| AI Structuring | Groq Llama (llama-3.3-70b-versatile) |
| On-device Transcription | Vosk |
| API Proxy | Cloudflare Workers |

---

## Architecture

```
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
Journal Timeline UI
```

Offline-first. Privacy-first. Clean Architecture (Presentation → Domain → Data).

---

## Roadmap

- [ ] On This Day — resurface memories from past years
- [ ] Semantic memory search
- [ ] Life chapter clustering
- [ ] Gujarati language support
- [ ] iOS client

---

## Thanks & Credits

Sotto wouldn't be possible without these incredible tools and teams:

**[Groq](https://groq.com)** — blazing fast Whisper transcription and Llama inference with Zero Data Retention. The privacy-respecting AI backbone of Sotto.

**[Vosk](https://alphacephei.com/vosk)** — open source on-device speech recognition that makes true offline mode possible.

**[SQLCipher](https://www.zetetic.net/sqlcipher)** — transparent AES-256 encryption for SQLite. Your memories are safe.

**[Jetpack Compose](https://developer.android.com/compose)** — modern Android UI that made building Sotto a joy.

**[Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform.html)** — shared business logic across Android and iOS.

---

## Support the Project

Sotto is free, ad-free, and built by one person in their spare time.

If it brought you value, a coffee goes a long way. ☕

<a href="https://www.buymeacoffee.com/YOUR_USERNAME">
  <img src="https://img.shields.io/badge/Buy_Me_A_Coffee-Support-FFDD00?style=flat&logo=buy-me-a-coffee&logoColor=black" />
</a>

---

## Legal

- [Privacy Policy](https://YOUR-USERNAME.github.io/sotto-legal/privacy-policy)
- [Terms of Service](https://YOUR-USERNAME.github.io/sotto-legal/terms-of-service)

---

## Contact

Built with ❤️ by **The Solitary Dev**

[your-dev-email@gmail.com]

---

*Sotto — speak freely. Your memories stay yours.*