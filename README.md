# 🌊 Kai - Your Daily AI Companion

![React](https://img.shields.io/badge/React-18.2.0-blue?logo=react)
![Groq AI](https://img.shields.io/badge/Groq-Llama_3.3_70B-purple?logo=ai)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.x-06B6D4?logo=tailwindcss)
![Languages](https://img.shields.io/badge/Languages-16+-success?logo=google-translate)
![License](https://img.shields.io/badge/License-MIT-green)

> 💡 **Side Project Alert!** Ini adalah project sampingan sederhana yang saya buat untuk belajar dan bereksperimen dengan AI chatbot. Ternyata cukup berguna untuk membantu aktivitas sehari-hari - dari schedule management, hitung-hitungan, sampai translate 16+ bahasa!

## ✨ Tentang Project Ini

Kai adalah AI chatbot berbahasa Indonesia yang saya buat sebagai **project coba-coba** untuk mengeksplorasi:

* 🤖 Integrasi dengan AI API (Groq AI + Llama 3.3)
* ⚛️ React untuk UI interaktif
* 📅 Manajemen jadwal sederhana
* 🌍 Multi-language translation (16+ bahasa)
* 🧮 Kalkulator AI yang bisa menjelaskan rumus

Awalnya cuma iseng bikin chatbot, eh ternyata malah sering saya pakai sendiri buat:

* Track jadwal harian
* Translate dokumen & komunikasi
* Hitung-hitungan cepat (persentase, matematika, dll)
* Tanya-tanya hal random ke AI

## 🎯 Fitur Utama

### 1️⃣ **Multi-Language Translator** 🌍✨

* 🔤 16+ bahasa tersedia (Indonesia, English, 中文, 日本語, 한국어, العربية, dan lainnya)
* 🔍 Auto detect bahasa sumber
* 🔄 Swap language dengan cepat
* 📋 Copy hasil terjemahan dengan 1 klik
* 🎯 Powered by Llama 3.3 70B untuk akurasi tinggi
* 💼 Perfect untuk business, travel, atau belajar bahasa

### 2️⃣ **Smart Schedule Management**

* ✅ Tambah/hapus jadwal dengan form yang mudah
* 🔴 Status real-time: Sedang Berlangsung / Akan Datang / Selesai
* ⚠️ Deteksi otomatis jadwal yang bentrok
* 📊 Lihat jadwal hari ini dan yang akan datang

### 3️⃣ **AI-Powered Math Helper**

* 🧮 Perhitungan matematika (persentase, aljabar, kalkulus, dll)
* 📐 Penjelasan rumus dengan step-by-step
* 💡 Contoh soal dan cara pengerjaannya

### 4️⃣ **Chatbot Ramah**

* 💬 Bahasa Indonesia yang natural dan friendly
* ⏰ Info waktu dan tanggal real-time
* 🌊 Personality yang calm dan supportive
* ⚡ Response super cepat (thanks to Groq AI!)

## 🚀 Quick Start

### Prerequisites

* Browser modern (Chrome, Firefox, Edge, Safari)
* API Key dari [Groq](https://console.groq.com/) (gratis!)

### Installation

1. **Clone repository ini**

```bash
git clone https://github.com/yourusername/kai-chatbot.git
cd kai-chatbot
```

2. **Edit API Key**
   Buka file `Kai.html` dan ganti dengan API key Groq Anda:
   ```javascript
   const GROQ_API_KEY = 'your-groq-api-key-here';
   ```
3. **Buka di browser**
   Cukup double-click file `Kai.html` atau buka via browser!
   ```bash
   # Atau pakai simple HTTP server
   python -m http.server 8000
   # Buka http://localhost:8000
   ```

## 💻 Tech Stack

| Technology                        | Purpose                          |
| --------------------------------- | -------------------------------- |
| **React 18.2**              | UI Components & State Management |
| **Groq AI (Llama 3.3 70B)** | AI Brain - Super fast inference! |
| **TailwindCSS**             | Styling & Responsive Design      |
| **Vanilla JS**              | Schedule logic & commands        |
| **localStorage**            | Session data persistence         |

## 📸 Screenshots

### Chat Interface

```
┌─────────────────────────────────────┐
│  🌊 Kai - Your Daily AI Companion   │
├─────────────────────────────────────┤
│                                     │
│  [Bot] Halo! Saya Kai 🌊           │
│        Ada yang bisa saya bantu?    │
│                                     │
│              [User] Hitung 15% dari │
│                     250.000         │
│                                     │
│  [Bot] 🧮 PERHITUNGAN               │
│        15% dari 250.000 = 37.500   │
│                                     │
└─────────────────────────────────────┘
```

### Schedule Manager

* 🔴  **Sedang Berlangsung** : Meeting Tim (10:00 - 11:30)
* 🟢  **Akan Datang** : Presentation (14:00 - 15:00)
* ⚪  **Selesai** : Daily Standup (09:00 - 09:15) ✓

### Translator Interface

```
┌─────────────────────────────────────┐
│     🌍 TRANSLATOR                   │
├──────────────┬──────────────────────┤
│  🔍 Auto     │  🇬🇧 English         │
├──────────────┴──────────────────────┤
│  Source Text       │  Translation   │
│                    │                │
│  Selamat pagi,     │  Good morning, │
│  apa kabar?        │  how are you?  │
│                    │                │
└────────────────────┴────────────────┘
         [🌍 Translate]
```

## 🌍 Translator Feature Details

### Supported Languages (16+)

| Region                | Languages                                                                                                     |
| --------------------- | ------------------------------------------------------------------------------------------------------------- |
| **Asia**        | 🇮🇩 Indonesian, 🇨🇳 Chinese, 🇯🇵 Japanese, 🇰🇷 Korean, 🇮🇳 Hindi, 🇹🇭 Thai, 🇻🇳 Vietnamese             |
| **Europe**      | 🇬🇧 English, 🇪🇸 Spanish, 🇫🇷 French, 🇩🇪 German, 🇷🇺 Russian, 🇵🇹 Portuguese, 🇮🇹 Italian, 🇳🇱 Dutch |
| **Middle East** | 🇸🇦 Arabic                                                                                                   |

### Use Cases

* 📧 **Business Communication** - Translate emails, documents, proposals
* ✈️ **Travel** - Understand local language, menus, signs
* 📚 **Learning** - Study foreign languages with instant translation
* 🌐 **International Work** - Collaborate with global teams
* 📱 **Social Media** - Understand posts in different languages
* 📖 **Reading** - Translate articles, books, news

## 🎮 Cara Pakai

### Commands Dasar

```
💬 Percakapan:
   "Halo" / "Hi"              → Sapaan ramah dari Kai
   "Siapa kamu?"              → Info tentang Kai
   "Bantuan"                  → Panduan lengkap

⏰ Waktu & Tanggal:
   "Jam berapa?"              → Waktu saat ini
   "Tanggal berapa?"          → Tanggal hari ini

📅 Jadwal:
   Klik "➕ Jadwal"           → Form tambah jadwal
   "Lihat jadwal"             → Tampilkan semua jadwal
   "Hapus jadwal [ID]"        → Hapus jadwal tertentu

🌍 Translator:
   Klik "🌍 Translator"       → Buka modal translator (RECOMMENDED)
   "Translate..."             → Terjemah via chat
   "Terjemahkan..."           → Terjemah via chat
   
   Bahasa tersedia:
   • 🇮🇩 Indonesia  • 🇬🇧 English    • 🇨🇳 Chinese
   • 🇯🇵 Japanese   • 🇰🇷 Korean     • 🇸🇦 Arabic
   • 🇪🇸 Spanish    • 🇫🇷 French     • 🇩🇪 German
   • 🇷🇺 Russian    • 🇵🇹 Portuguese • 🇮🇳 Hindi
   • 🇹🇭 Thai       • 🇻🇳 Vietnamese • 🇮🇹 Italian
   • 🇳🇱 Dutch      + Auto Detect 🔍

🧮 Matematika:
   "Hitung 20% dari 500.000"  → Kalkulator persentase
   "Jelaskan rumus pythagoras" → Penjelasan rumus
   "Solve: 2x + 5 = 15"       → Selesaikan persamaan
```

## 🏗️ Project Structure

```
kai-chatbot/
│
├── simplebot.html          # Main file (All-in-one!)
│
└── README.md               # You are here 😊
```

Yep, cuma 1 file HTML! Simple kan? 🎉

## 🤔 Why This Project?

Ini adalah **learning project** yang saya buat untuk:

1. **Belajar AI Integration** - Gimana caranya panggil AI API dengan efisien
2. **Eksperimen React** - State management tanpa framework berat
3. **Explore UI/UX** - Bikin chatbot yang enak dipakai
4. **Multi-language Processing** - Implementasi translator dengan AI
5. **Solve Real Problems** - Ternyata berguna buat daily task management!

 **Bonus** : Fitur translator yang tadinya cuma eksperimen, sekarang jadi salah satu fitur favorit saya! 🌍

## ⚠️ Disclaimer

* 🔧 Ini adalah **project sampingan** yang dibuat untuk belajar dan fun
* 🐛 Mungkin ada bugs atau hal-hal yang bisa diimprove
* 🚀 Not production-ready, tapi cukup untuk daily use!
* 💡 Feel free to fork, modify, atau improve!

## 🎯 Roadmap

**Completed** ✅

* [X] Multi-language translator (16+ languages)
* [X] Smart schedule management
* [X] AI math helper
* [X] Conflict detection for schedules

**Maybe in the Future?** 🤔

Kalau sempat dan ada ide, mungkin akan ditambah:

* [ ] Export jadwal ke Google Calendar
* [ ] Dark mode toggle
* [ ] Voice input untuk chat dan translator
* [ ] Reminder notifications
* [ ] Text-to-speech untuk hasil translate
* [ ] Mobile app version
* [ ] Cloud sync untuk jadwal
* [ ] Translation history
* [ ] Batch translation untuk multiple texts

Tapi ya... ini side project, jadi no promises 😅

## 🤝 Contributing

Mau contribute? Silakan banget!

1. Fork this repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Any improvements welcome! 🙌

## 🐛 Known Issues

* [ ] Jadwal tidak persist setelah refresh (pakai localStorage untuk session only)
* [ ] AI parsing kadang tidak konsisten (makanya ditambah form manual)
* [ ] Translation via chat kurang optimal (gunakan modal translator untuk hasil terbaik)
* [ ] Belum ada unit tests (it's a side project 😬)

## 📝 License

MIT License - Feel free to use this project for anything!

## 👨‍💻 Author

**Your Name**

* GitHub: [@DavidMarioYS](https://github.com/DavidMarioYS)
* Project Link: [https://github.com/DavidMarioYS/kai-chatbot](https://github.com/DavidMarioYS/kai-chatbot)

## 🙏 Acknowledgments

* [Groq](https://groq.com/) - Amazing fast AI inference!
* [Meta&#39;s Llama 3.3](https://ai.meta.com/llama/) - Powerful language model with excellent multilingual support
* [React](https://react.dev/) - UI library
* [TailwindCSS](https://tailwindcss.com/) - Styling framework
* Kopi ☕ - Fuel for coding sessions
* All the language communities worldwide 🌍 - For inspiring the translator feature

---

<div align="center">
**⭐ Star this repo if you find it helpful!**

Made with ❤️ and lots of ☕ for learning purposes

🌊 *Stay calm like ocean waves* 🌊

 **NEW** : Now with 16+ languages translation! 🌍✨

</div>
