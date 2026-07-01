# Sotto | Private Voice Memory App for Android

> *Sotto Voce: to speak quietly, under your breath.*

<div align="center">
<img src="assets/logo.png" width="80" alt="Sotto Logo" />
</div>

### Capture ideas, conversations, and moments by speaking.

Private. Encrypted. Searchable. Offline first.

<div align="center">

[![Get it on Google Play](https://img.shields.io/badge/Get%20it%20on-Google%20Play-34A853?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.sotto.memories)
![Android Native](https://img.shields.io/badge/Android-Native-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin Multiplatform](https://img.shields.io/badge/Kotlin-Multiplatform-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Privacy First](https://img.shields.io/badge/Privacy-First-111111?style=for-the-badge)

[![Product Hunt](https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=1174120&theme=dark)](https://www.producthunt.com/products/sotto-5)
[![Open Launch](https://open-launch.com/api/badge/21e8245e-ceeb-45fc-bb66-be81d6127bc5/featured-dark.svg)](https://open-launch.com/projects/sotto)
[![Shipit](https://www.shipit.buzz/api/products/sotto/badge?theme=dark)](https://www.shipit.buzz/products/sotto?ref=badge)

</div>

---

Sotto is a private voice memory app for Android that helps you preserve ideas, conversations, lessons, book recommendations, and everyday moments before they are forgotten.

Simply press record and speak naturally. Sotto transcribes your voice, organizes your memories with AI, and stores everything securely on your device.

No ads. No tracking. No login. Just your memories.

---

## Screenshots

<table>
  <tr>
    <td align="center"><img src="assets/screenshots/Record.png" width="160" /></td>
    <td align="center"><img src="assets/screenshots/Memories.png" width="160" /></td>
    <td align="center"><img src="assets/screenshots/Patterns.png" width="160" /></td>
    <td align="center"><img src="assets/screenshots/Privacy.png" width="160" /></td>
  </tr>
</table>

---

## Download

<div align="center">

<a href="https://play.google.com/store/apps/details?id=com.sotto.memories">
  <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="60">
</a>


</div>

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

- 🎙 Voice first memory capture
- 🤖 AI generated titles, tags, mood, categories, and reflections
- 🔍 Full text search across every memory
- 🔒 SQLCipher encrypted local storage
- 📴 Fully offline transcription with Vosk
- 🎯 Accurate transcription with Groq Whisper Zero Data Retention
- 📊 Mood trends and memory insights
- ⭐ Star important memories
- 🌐 English and Hindi support
- 🔄 Background processing with WorkManager
- 🚫 No ads
- 🚫 No tracking
- 🚫 No login required

---

## Privacy

Your memories belong to you.

- Everything is stored locally.
- SQLCipher encrypts your database.
- Offline transcription is available.
- Accurate mode uses Groq Zero Data Retention.
- No advertising.
- No analytics.
- No tracking.
- No selling your data.

You stay in control of your memories.

---

## Tech Stack

| Layer | Technology |
| ------ | ---------- |
| Language | Kotlin Multiplatform |
| UI | Jetpack Compose |
| Navigation | Voyager |
| Database | SQLDelight + SQLCipher |
| Networking | Ktor |
| Dependency Injection | Koin |
| Background Jobs | WorkManager |
| Cloud Transcription | Groq Whisper |
| AI Memory Organization | Groq Llama |
| Offline Speech Recognition | Vosk |
| API Proxy | Cloudflare Workers |

---

## Architecture

```text
Record Audio
      ↓
Temporary Audio
      ↓
Background WorkManager Job
      ↓
Whisper Transcription
      ↓
AI Memory Organization
      ↓
Encrypted Memory Storage
      ↓
Temporary Audio Deleted
      ↓
Memory Timeline
````

Offline first.

Privacy first.

Clean Architecture.

```
Presentation
      ↓
Domain
      ↓
Data
```

---

## Roadmap

* [ ] On This Day
* [ ] Semantic memory search
* [ ] Life chapter clustering
* [ ] Gujarati support
* [ ] iOS app
* [ ] Optional encrypted cloud backup

---

## Built With

Sotto is powered by some incredible technologies.

* Groq
* Vosk
* SQLCipher
* Kotlin Multiplatform
* Jetpack Compose
* SQLDelight
* Ktor
* Koin
* WorkManager

---

## Legal

* Privacy Policy
* Terms of Service

These documents apply to the Sotto Android application available on Google Play.

---

## Contact

Built by Rudra Dave for [**The Solitary Dev**](https://play.google.com/store/apps/details?id=com.sotto.memories)

📧 [sottoapp.help@gmail.com](mailto:sottoapp.help@gmail.com)

Google Play:
https://play.google.com/store/apps/details?id=com.sotto.memories

---

```
"Never forget anything"

```
