<div align="center">

# Nihonjin AI

**Antarmuka chat AI yang dingin, minimalis, dan deterministik.**

<br/>

[![License: MIT](https://img.shields.io/badge/License-MIT-6366f1?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Cerebras](https://img.shields.io/badge/Cerebras_API-qwen--3--235b-00D4AA?style=for-the-badge&logo=lightning&logoColor=white)](https://cerebras.ai)

<br/>

[![KaTeX](https://img.shields.io/badge/KaTeX-LaTeX_Rendering-008080?style=flat-square&logo=latex&logoColor=white)](https://katex.org)
[![Marked.js](https://img.shields.io/badge/Marked.js-Markdown-000000?style=flat-square&logo=markdown&logoColor=white)](https://marked.js.org)
[![Highlight.js](https://img.shields.io/badge/Highlight.js-Syntax_Highlighting-BE6464?style=flat-square&logo=code&logoColor=white)](https://highlightjs.org)
[![DOMPurify](https://img.shields.io/badge/DOMPurify-XSS_Safe-4CAF50?style=flat-square&logo=shield&logoColor=white)](https://github.com/cure53/DOMPurify)
[![LocalStorage](https://img.shields.io/badge/Storage-LocalStorage-FFA500?style=flat-square&logo=databricks&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)

<br/>

[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=flat-square&logo=github)](CONTRIBUTING.md)
[![Maintenance](https://img.shields.io/badge/Maintained-Yes-6366f1?style=flat-square&logo=checkmarx&logoColor=white)]()
[![No Server Required](https://img.shields.io/badge/Server-Not_Required-lightgrey?style=flat-square&logo=serverfault&logoColor=white)]()
[![Mobile Ready](https://img.shields.io/badge/Responsive-Mobile_%26_Desktop-blue?style=flat-square&logo=responsive&logoColor=white)]()

</div>

---

## 📋 Gambaran Umum

**Nihonjin AI** adalah antarmuka chat berbasis web dengan karakteristik **dingin, minimalis, dan profesional**. Nama ini terinspirasi dari filosofi desain Jepang — presisi tanpa dekorasi berlebihan, fungsi tanpa distraksi.

Sistem ini dibangun di atas prinsip inti berikut:

| Prinsip | Filosofi |
|---|---|
| 🎯 **Presisi** | Lebih penting daripada panjang penjelasan |
| 🔍 **Kejelasan** | Lebih penting daripada gaya santai |
| ⚡ **Efisiensi** | Lebih penting daripada estetika berlebihan |
| 🧊 **Determinisme** | Output yang terkontrol dan konsisten |

Dibangun menggunakan teknologi web murni dan terintegrasi dengan **Cerebras API** model `qwen-3-235b-a22b-instruct-2507` — salah satu model inferensi tercepat yang tersedia secara publik.

> **Filosofi:** Nihonjin AI bukan sekadar chat interface. Ini adalah sistem komunikasi dengan AI yang dirancang untuk pengguna yang mengutamakan hasil atas pengalaman, substansi atas gaya, dan kontrol atas kenyamanan pasif.

---

## ⚠️ Peringatan Penting

> **Proyek ini tidak menyertakan API key.**

Pengguna wajib memahami dan mematuhi hal berikut:

- ✅ Gunakan **API key milik sendiri** yang diperoleh dari [console.cerebras.ai](https://console.cerebras.ai)
- ✅ **Jaga kerahasiaan** API key Anda setiap saat
- ✅ **Jangan commit** API key ke repositori publik
- ❌ **Jangan bagikan** API key ke pihak lain
- ❌ **Jangan hardcode** API key di versi publik fork Anda

Penggunaan tanpa pengamanan yang tepat dapat menyebabkan **penyalahgunaan akses dan biaya tak terduga** pada akun Anda.

---

## 📖 Daftar Isi

- [Gambaran Umum](#-gambaran-umum)
- [Peringatan Penting](#️-peringatan-penting)
- [Fitur](#-fitur)
- [Teknologi](#-teknologi)
- [Cara Memulai](#-cara-memulai)
  - [Prasyarat](#prasyarat)
  - [Instalasi](#instalasi)
  - [Konfigurasi API Key](#konfigurasi-api-key)
  - [Konfigurasi Avatar](#konfigurasi-avatar-opsional)
  - [Menjalankan Aplikasi](#menjalankan-aplikasi)
- [Penggunaan](#-penggunaan)
  - [Interaksi Chat](#interaksi-chat)
  - [Manajemen Percakapan](#manajemen-percakapan)
  - [Dukungan LaTeX](#dukungan-latex)
  - [Tampilan Kode](#tampilan-kode)
- [Kustomisasi](#-kustomisasi)
  - [Persona AI](#persona-ai)
  - [Tema Warna](#tema-warna)
  - [Library Eksternal](#library-eksternal)
- [Integrasi API](#-integrasi-api)
- [Arsitektur Sistem](#-arsitektur-sistem)
- [Pemecahan Masalah](#-pemecahan-masalah)
- [FAQ](#-faq)
- [Lisensi](#-lisensi)
- [Kontribusi](#-kontribusi)
- [Kredit](#-kredit)
- [Kontak](#-kontak)

---

## ✨ Fitur

### Core Features

| Fitur | Deskripsi |
|---|---|
| 🧊 **Persona Deterministik** | AI dengan kepribadian dingin, singkat, dan terkontrol |
| ⚡ **Streaming Real-time** | Respons muncul secara inkremental tanpa delay |
| 📐 **Rendering LaTeX** | Dukungan penuh untuk ekspresi matematika inline dan display |
| 💻 **Syntax Highlighting** | Penyorotan sintaks kode multi-bahasa + tombol salin |
| 💾 **Persistent History** | Riwayat chat tersimpan otomatis via localStorage |
| 📁 **Manajemen Percakapan** | Sidebar untuk navigasi, rename, dan hapus percakapan |
| 📱 **Fully Responsive** | Tampilan optimal di mobile dan desktop |
| 🖼️ **Avatar Kustom** | Dukungan avatar base64 untuk AI dan pengguna |
| 🛡️ **XSS Protection** | Sanitasi konten HTML via DOMPurify |
| 🌑 **Dark Theme** | Tema gelap murni, ramah mata, cocok untuk penggunaan panjang |

### Fitur Detail

**Streaming Responses**
Respons AI tidak menunggu sampai selesai — teks muncul karakter demi karakter secara real-time, memberikan pengalaman interaksi yang lebih natural dan cepat secara persepsi.

**Persistent Storage**
Semua percakapan disimpan di localStorage browser. Tidak ada data yang dikirim ke server eksternal selain permintaan API ke Cerebras. Privasi terjaga sepenuhnya di sisi klien.

**Smart Conversation Grouping**
Sidebar mengelompokkan percakapan berdasarkan waktu: Hari ini, Kemarin, 7 hari terakhir, dan Lebih lama — memudahkan navigasi riwayat chat.

---

## 🛠️ Teknologi

<div align="center">

[![HTML5](https://img.shields.io/badge/HTML5-Struktur_Semantik-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Custom_Properties_%26_Transitions-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+_Modules-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

[![Cerebras](https://img.shields.io/badge/Cerebras-qwen--3--235b-00D4AA?style=for-the-badge&logo=lightning&logoColor=white)](https://cerebras.ai)
[![KaTeX](https://img.shields.io/badge/KaTeX-Math_Rendering-008080?style=for-the-badge&logo=latex&logoColor=white)](https://katex.org)
[![Marked](https://img.shields.io/badge/Marked.js-Markdown_Parser-000000?style=for-the-badge&logo=markdown&logoColor=white)](https://marked.js.org)
[![HighlightJS](https://img.shields.io/badge/Highlight.js-Code_Coloring-BE6464?style=for-the-badge&logo=code&logoColor=white)](https://highlightjs.org)
[![DOMPurify](https://img.shields.io/badge/DOMPurify-XSS_Protection-4CAF50?style=for-the-badge&logo=shield&logoColor=white)](https://github.com/cure53/DOMPurify)

</div>

### Stack Breakdown

```
Nihonjin AI
├── Frontend Layer
│   ├── HTML5          → Struktur dan semantik dokumen
│   ├── CSS3           → Tema gelap, variabel CSS, animasi, responsivitas
│   └── JavaScript     → Logic aplikasi, event handling, state management
│
├── AI Layer
│   └── Cerebras API   → Inferensi model qwen-3-235b (streaming)
│
├── Rendering Layer
│   ├── KaTeX          → Rendering ekspresi matematika LaTeX
│   ├── Marked.js      → Parsing dan rendering Markdown
│   └── Highlight.js   → Syntax highlighting kode program
│
├── Security Layer
│   └── DOMPurify      → Sanitasi HTML untuk mencegah XSS
│
└── Storage Layer
    └── LocalStorage   → Persistensi riwayat percakapan di browser
```

---

## 🚀 Cara Memulai

### Prasyarat

Sebelum memulai, pastikan Anda memiliki:

- [![Browser](https://img.shields.io/badge/Browser-Chrome_%7C_Firefox_%7C_Edge_%7C_Safari-4285F4?style=flat-square&logo=googlechrome&logoColor=white)](https://www.google.com/chrome/) Browser modern dengan dukungan ES6+
- [![Internet](https://img.shields.io/badge/Internet-Koneksi_Stabil-0078D4?style=flat-square&logo=internetexplorer&logoColor=white)]() Koneksi internet aktif
- [![Cerebras](https://img.shields.io/badge/Cerebras-API_Key_(Opsional)-00D4AA?style=flat-square&logo=lightning&logoColor=white)](https://console.cerebras.ai) Akun Cerebras untuk mendapatkan API key

> **Catatan:** Aplikasi ini berjalan **100% di sisi klien**. Tidak ada backend, tidak ada database, tidak ada server yang perlu dikonfigurasi.

---

### Instalasi

**Clone repositori:**

```bash
git clone https://github.com/ikyletwar/Nihonjin-AI.git
cd Nihonjin-AI
```

**Struktur direktori setelah clone:**

```
Nihonjin-AI/
├── index.html       ← File utama aplikasi
├── README.md        ← Dokumentasi ini
└── LICENSE          ← Lisensi MIT
```

**Buka aplikasi:**

```
Buka file index.html langsung di browser
```

Tidak diperlukan `npm install`, tidak diperlukan build process, tidak diperlukan konfigurasi server.

---

### Konfigurasi API Key

Buka `index.html` dengan text editor pilihan Anda (VS Code, Notepad++, Sublime Text, dll.), kemudian cari bagian konfigurasi:

```javascript
// Temukan bagian ini di dalam index.html
API_KEY: ''
```

Ganti dengan API key Anda:

```javascript
API_KEY: 'csk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'
```

Simpan file, lalu muat ulang halaman di browser.

**Cara mendapatkan API Key:**
1. Kunjungi [console.cerebras.ai](https://console.cerebras.ai)
2. Login atau buat akun baru (gratis)
3. Navigasi ke bagian **API Keys**
4. Klik **Create New Key**
5. Salin key dan simpan di tempat yang aman
6. Paste ke konfigurasi `index.html`

> ⚠️ **Penting:** Jangan commit file `index.html` yang sudah berisi API key ke repositori publik. Gunakan `.gitignore` atau buat file konfigurasi terpisah.

---

### Konfigurasi Avatar (Opsional)

Avatar ditampilkan di samping setiap pesan dalam percakapan. Anda dapat menggunakan gambar kustom dalam format base64:

```javascript
const AVATAR_CONFIG = {
  // Avatar untuk pesan AI — gunakan base64 atau URL gambar
  ASSISTANT_AVATAR: 'data:image/jpeg;base64,/9j/4AAQSkZJRgAB...',
  
  // Avatar untuk pesan pengguna — kosongkan untuk menggunakan inisial
  USER_AVATAR: ''
};
```

**Cara mengonversi gambar ke base64:**

```bash
# Di terminal (Linux/macOS)
base64 -i avatar.jpg | tr -d '\n'

# Atau gunakan tools online seperti base64encode.org
```

Jika `AVATAR_CONFIG` dibiarkan kosong, sistem akan otomatis menggunakan **inisial nama** sebagai avatar fallback.

---

### Menjalankan Aplikasi

**Metode 1 — Langsung (paling simpel):**
```
Klik dua kali pada file index.html
```

**Metode 2 — Local Server (direkomendasikan untuk fitur clipboard):**

```bash
# Python 3
python -m http.server 8080

# Node.js (dengan npx)
npx serve .

# PHP
php -S localhost:8080
```

Kemudian buka browser dan akses: `http://localhost:8080`

**Metode 3 — VS Code Live Server:**
1. Install ekstensi **Live Server** di VS Code
2. Klik kanan `index.html`
3. Pilih **Open with Live Server**

---

## 💬 Penggunaan

### Interaksi Chat

Antarmuka chat dirancang untuk kesederhanaan maksimal:

1. **Ketik pesan** di input field di bagian bawah layar
2. **Tekan `Enter`** untuk mengirim (atau klik tombol kirim)
3. **Respons AI** akan muncul secara streaming — teks mengalir real-time
4. **Tekan `Shift + Enter`** untuk baris baru tanpa mengirim pesan

**Tips penggunaan efektif:**
- Bersikap langsung dan spesifik — persona AI ini menghargai kejelasan
- Hindari basa-basi berlebihan; AI akan merespons dengan gaya yang sama
- Gunakan formatting Markdown dalam pesan Anda — AI memahami dan merespons dengan format yang sesuai

---

### Manajemen Percakapan

Sidebar dapat diakses melalui **ikon menu (☰)** di pojok kiri atas:

| Aksi | Cara |
|---|---|
| 📝 Buat percakapan baru | Klik tombol **New Chat** |
| ✏️ Rename percakapan | Klik nama percakapan → Edit |
| 🗑️ Hapus percakapan | Hover percakapan → Klik ikon hapus |
| 📂 Navigasi antar chat | Klik nama percakapan di sidebar |

**Pengelompokan otomatis berdasarkan waktu:**
- 🕐 Hari ini
- 📅 Kemarin
- 📆 7 hari terakhir
- 🗓️ Lebih lama

---

### Dukungan LaTeX

Nihonjin AI mendukung rendering LaTeX melalui KaTeX untuk ekspresi matematika:

**Inline Math** — gunakan `$...$`:
```
Rumus energi Einstein: $E = mc^2$
Teorema Pythagoras: $a^2 + b^2 = c^2$
```

**Display Math** — gunakan `$$...$$`:
```
$$\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}$$
$$\sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6}$$
$$\nabla \times \vec{B} = \mu_0\vec{J} + \mu_0\varepsilon_0\frac{\partial \vec{E}}{\partial t}$$
```

**Contoh ekspresi yang didukung:**
- Integral dan turunan
- Matriks dan vektor
- Notasi sigma dan pi
- Pecahan dan akar
- Simbol Yunani dan operator matematika

> ⚠️ **Perhatian:** Pastikan tidak ada spasi setelah tanda `$` pembuka. `$E = mc^2$` ✅ — `$ E = mc^2$` ❌

---

### Tampilan Kode

Semua blok kode dalam respons AI dirender dengan:

- 🎨 **Syntax highlighting** — warna berbeda untuk keyword, string, komentar, dll.
- 📋 **Tombol salin** — klik sekali untuk menyalin kode ke clipboard
- 🏷️ **Label bahasa** — menampilkan bahasa pemrograman yang digunakan
- 📏 **Scrollbar horizontal** — untuk kode panjang tanpa line wrapping

**Bahasa yang didukung** (via Highlight.js):
Python, JavaScript, TypeScript, Rust, Go, Java, C/C++, C#, PHP, Ruby, Swift, Kotlin, SQL, Bash, YAML, JSON, XML, HTML, CSS, dan banyak lagi.

---

## 🎨 Kustomisasi

### Persona AI

Persona AI diatur melalui system prompt yang dapat dikustomisasi. Temukan variabel berikut di `index.html`:

```javascript
SYS: `IDENTITAS AI: NIHONJIN
Kepribadian: dingin, presisi, profesional
Gaya komunikasi: singkat, langsung, tanpa basa-basi
Prioritas: akurasi dan kejelasan di atas segalanya`
```

**Panduan kustomisasi persona:**

```javascript
// Contoh: Persona lebih ramah
SYS: `Kamu adalah asisten AI yang helpful dan friendly.
Berikan penjelasan yang mudah dipahami.
Gunakan bahasa yang santai namun tetap informatif.`

// Contoh: Persona akademik
SYS: `Kamu adalah asisten riset akademik.
Selalu sertakan referensi dan konteks ilmiah.
Gunakan terminologi teknis yang tepat.`

// Contoh: Persona coding expert
SYS: `Kamu adalah senior software engineer.
Fokus pada best practices, performance, dan clean code.
Berikan code review yang kritis dan konstruktif.`
```

> ⚠️ Pastikan format string template literal tetap valid setelah perubahan.

---

### Tema Warna

Tema warna dikontrol melalui CSS custom properties (variabel). Temukan dan modifikasi di bagian `<style>`:

```css
:root {
  /* Background utama — sangat gelap */
  --bg-primary: #0a0c10;
  
  /* Background sekunder — sedikit lebih terang */
  --bg-secondary: #0f1218;
  
  /* Warna aksen — indigo/violet */
  --accent: #6366f1;
  
  /* Teks utama */
  --text-primary: #e2e8f0;
  
  /* Teks sekunder/muted */
  --text-secondary: #94a3b8;
  
  /* Border/divider */
  --border: #1e2432;
}
```

**Contoh tema alternatif:**

```css
/* Tema Hijau Terminal */
:root {
  --bg-primary: #0a0f0a;
  --bg-secondary: #0d140d;
  --accent: #22c55e;
  --text-primary: #dcfce7;
}

/* Tema Merah Cyberpunk */
:root {
  --bg-primary: #0f0a0a;
  --bg-secondary: #140d0d;
  --accent: #ef4444;
  --text-primary: #fee2e2;
}

/* Tema Amber Retro */
:root {
  --bg-primary: #0f0e0a;
  --bg-secondary: #14120d;
  --accent: #f59e0b;
  --text-primary: #fef3c7;
}
```

---

### Library Eksternal

Untuk menambahkan library JavaScript tambahan, sisipkan di bagian `<head>` sebelum script utama:

```html
<head>
  <!-- Library yang sudah ada -->
  <script src="https://cdn.jsdelivr.net/npm/katex/dist/katex.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/highlight.js/lib/core.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/dompurify/dist/purify.min.js"></script>
  
  <!-- Tambahkan library baru di sini -->
  <script src="https://cdn.jsdelivr.net/npm/your-library@version/dist/library.min.js"></script>
</head>
```

---

## 🔌 Integrasi API

### Model yang Digunakan

```
Provider : Cerebras AI
Model    : qwen-3-235b-a22b-instruct-2507
Endpoint : https://api.cerebras.ai/v1/chat/completions
Streaming: Server-Sent Events (SSE)
```

### Mendapatkan API Key

[![Cerebras Console](https://img.shields.io/badge/Cerebras_Console-Daftar_Sekarang-00D4AA?style=for-the-badge&logo=lightning&logoColor=white)](https://console.cerebras.ai)

1. Kunjungi **[console.cerebras.ai](https://console.cerebras.ai)**
2. Klik **Sign Up** atau **Log In**
3. Verifikasi email Anda
4. Navigasi ke **API Keys** di dashboard
5. Klik **Generate New API Key**
6. **Salin dan simpan** key dengan aman — key hanya ditampilkan sekali
7. Paste ke konfigurasi `index.html`

### Informasi Rate Limit & Quota

| Parameter | Detail |
|---|---|
| 💰 **Tier Gratis** | Tersedia (kuota terbatas, cek kebijakan terkini) |
| ⚡ **Kecepatan** | Salah satu inferensi tercepat yang tersedia |
| 🔄 **Rate Limit** | Tergantung tier akun |
| 📊 **Token Limit** | Bergantung pada model dan plan |

> Selalu periksa [dokumentasi resmi Cerebras](https://inference-docs.cerebras.ai/) untuk informasi quota dan pricing terbaru.

### Format Request API

Berikut adalah contoh request yang dikirim aplikasi ke Cerebras API:

```javascript
{
  "model": "qwen-3-235b-a22b-instruct-2507",
  "messages": [
    {
      "role": "system",
      "content": "IDENTITAS AI: NIHONJIN..."
    },
    {
      "role": "user",
      "content": "Pesan pengguna di sini"
    }
  ],
  "stream": true,
  "temperature": 0.7,
  "max_tokens": 2048
}
```

---

## 🏗️ Arsitektur Sistem

```
┌─────────────────────────────────────────────────┐
│                  BROWSER (Client)                │
│                                                 │
│  ┌──────────────┐    ┌────────────────────────┐ │
│  │   Sidebar    │    │     Chat Interface     │ │
│  │              │    │                        │ │
│  │ • New Chat   │    │ ┌────────────────────┐ │ │
│  │ • Conv List  │◄──►│ │   Message Renderer │ │ │
│  │ • Time Group │    │ │ • Markdown (Marked)│ │ │
│  │ • Rename     │    │ │ • Math (KaTeX)     │ │ │
│  │ • Delete     │    │ │ • Code (Highlight) │ │ │
│  └──────────────┘    │ │ • Safety (DOMPurify│ │ │
│                      │ └────────────────────┘ │ │
│                      │                        │ │
│                      │ ┌────────────────────┐ │ │
│                      │ │   Input Handler    │ │ │
│                      │ │ • Text Input       │ │ │
│                      │ │ • Enter to Send    │ │ │
│                      │ │ • Shift+Enter      │ │ │
│                      │ └────────┬───────────┘ │ │
│                      └──────────┼─────────────┘ │
│                                 │               │
│  ┌──────────────────────────────▼─────────────┐ │
│  │              LocalStorage                  │ │
│  │     (Riwayat percakapan persisten)          │ │
│  └────────────────────────────────────────────┘ │
└─────────────────────────────┬───────────────────┘
                              │ HTTPS / SSE Stream
                              ▼
                ┌─────────────────────────┐
                │      Cerebras API       │
                │  qwen-3-235b-a22b       │
                │  (Streaming Response)   │
                └─────────────────────────┘
```

---

## 🔧 Pemecahan Masalah

### ❌ API Key Tidak Valid

**Gejala:** Muncul error `401 Unauthorized` atau `Invalid API Key`

**Solusi:**
1. Periksa apakah API key sudah disalin dengan benar (tanpa spasi tambahan)
2. Pastikan API key masih aktif di [console.cerebras.ai](https://console.cerebras.ai)
3. Cek apakah quota akun masih tersedia
4. Coba buat API key baru jika masalah berlanjut

```javascript
// Pastikan formatnya benar
API_KEY: 'csk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'
//        ^^^ Prefix 'csk-' harus ada
```

---

### ❌ Tidak Ada Respons dari AI

**Gejala:** Pesan terkirim tapi tidak ada balasan, atau loading tidak berhenti

**Langkah diagnostik:**
1. Buka **DevTools** browser (`F12` atau `Ctrl+Shift+I`)
2. Pergi ke tab **Console** — cek error messages
3. Pergi ke tab **Network** — cek apakah request ke Cerebras API dikirim
4. Pastikan koneksi internet stabil
5. Coba refresh halaman dan kirim ulang pesan

---

### ❌ LaTeX Tidak Ter-render

**Gejala:** Rumus matematika tampil sebagai teks biasa, bukan simbol

**Penyebab umum dan solusi:**

```
❌ Salah: $ E = mc^2$    (spasi setelah $ pembuka)
✅ Benar: $E = mc^2$

❌ Salah: $$E = mc^2$    (tanda $ tidak seimbang)
✅ Benar: $$E = mc^2$$

❌ Salah: \(E = mc^2\)   (format LaTeX berbeda)
✅ Benar: $E = mc^2$
```

---

### ❌ Tombol Salin Kode Tidak Berfungsi

**Gejala:** Klik tombol salin tidak melakukan apa-apa

**Penyebab:** Clipboard API memerlukan konteks HTTPS atau localhost

**Solusi — jalankan local server:**

```bash
# Python 3
python -m http.server 8080

# Node.js
npx serve .

# PHP
php -S localhost:8080
```

Akses melalui `http://localhost:8080` bukan `file://`

---

### ❌ Riwayat Chat Tidak Tersimpan

**Gejala:** Percakapan hilang setelah refresh halaman

**Penyebab dan solusi:**

| Penyebab | Solusi |
|---|---|
| Mode Incognito/Private | Gunakan window browser normal |
| localStorage diblokir | Cek pengaturan privasi browser |
| Storage penuh | Hapus beberapa percakapan lama |
| Extension browser | Coba disable extension dan coba lagi |

---

### ❌ Tampilan Rusak di Mobile

**Gejala:** Layout berantakan di layar kecil

**Solusi:**
1. Pastikan tidak ada zoom manual pada halaman
2. Coba rotate layar dan rotate kembali
3. Hard refresh: `Ctrl+Shift+R` (atau `Cmd+Shift+R` di Mac)
4. Coba browser berbeda (Chrome Mobile biasanya paling kompatibel)

---

## ❓ FAQ

**Q: Apakah data percakapan saya dikirim ke server selain Cerebras?**
A: Tidak. Data hanya dikirim ke Cerebras API untuk mendapatkan respons AI. Riwayat chat disimpan lokal di browser Anda melalui localStorage.

**Q: Bisakah saya menggunakan model AI lain selain qwen-3-235b?**
A: Ya, selama model tersebut kompatibel dengan Cerebras API. Cari dan ganti nilai `model` di konfigurasi API request.

**Q: Apakah ada batas jumlah percakapan yang bisa disimpan?**
A: Batas ditentukan oleh kapasitas localStorage browser (biasanya 5-10MB). Jika penuh, hapus percakapan lama yang tidak diperlukan.

**Q: Bisakah saya deploy aplikasi ini ke web hosting?**
A: Ya, unggah file `index.html` ke hosting statis manapun (GitHub Pages, Netlify, Vercel, dll.). Pastikan API key tidak ikut ter-upload.

**Q: Apakah aplikasi ini bisa digunakan offline?**
A: Tidak sepenuhnya. Library eksternal (KaTeX, Highlight.js, dll.) dimuat dari CDN, dan permintaan AI memerlukan koneksi ke Cerebras API. Namun riwayat chat yang sudah ada bisa dilihat offline.

---

## 📄 Lisensi

```
MIT License

Copyright (c) 2024 Hizkia Letwar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

[![License: MIT](https://img.shields.io/badge/License-MIT-6366f1?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)

---

## 🤝 Kontribusi

Kontribusi sangat disambut! Berikut cara berkontribusi:

### Workflow Kontribusi

```bash
# 1. Fork repositori ini
# 2. Clone fork Anda
git clone https://github.com/USERNAME/Nihonjin-AI.git
cd Nihonjin-AI

# 3. Buat branch baru untuk fitur/perbaikan Anda
git checkout -b fitur/nama-fitur-baru
# atau
git checkout -b fix/nama-bug

# 4. Lakukan perubahan dan commit
git add .
git commit -m "feat: tambahkan fitur XYZ"
# atau
git commit -m "fix: perbaiki bug ABC"

# 5. Push ke fork Anda
git push origin fitur/nama-fitur-baru

# 6. Buat Pull Request ke repositori utama
```

### Panduan Commit Message

| Prefix | Digunakan untuk |
|---|---|
| `feat:` | Fitur baru |
| `fix:` | Perbaikan bug |
| `docs:` | Perubahan dokumentasi |
| `style:` | Perubahan CSS/tampilan |
| `refactor:` | Refactoring kode |
| `perf:` | Peningkatan performa |

### Area yang Bisa Diimprovisasi

- [ ] 🌐 Dukungan multi-bahasa (i18n)
- [ ] 📤 Export percakapan ke PDF/Markdown
- [ ] 🔍 Fitur pencarian dalam riwayat chat
- [ ] 🔊 Text-to-speech untuk respons AI
- [ ] 📁 Upload file dan gambar
- [ ] ⚙️ Panel pengaturan UI (tanpa edit kode)
- [ ] 🔒 Enkripsi localStorage untuk privasi lebih baik

---

## 👏 Kredit

| Komponen | Kontributor/Source |
|---|---|
| 💻 **Pengembang Utama** | [Hizkia Letwar](https://github.com/ikyletwar) |
| 🧠 **AI Model** | [Cerebras AI](https://cerebras.ai) — `qwen-3-235b-a22b-instruct-2507` |
| 📐 **Math Rendering** | [KaTeX](https://katex.org) oleh Khan Academy |
| 📝 **Markdown Parser** | [Marked.js](https://marked.js.org) |
| 🎨 **Syntax Highlighting** | [Highlight.js](https://highlightjs.org) |
| 🛡️ **XSS Protection** | [DOMPurify](https://github.com/cure53/DOMPurify) oleh Cure53 |

---

## 📬 Kontak

[![GitHub Issues](https://img.shields.io/badge/GitHub-Issues-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ikyletwar/Nihonjin-AI/issues)
[![GitHub Discussions](https://img.shields.io/badge/GitHub-Discussions-6366f1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ikyletwar/Nihonjin-AI/discussions)

Untuk pertanyaan, laporan bug, atau saran fitur:

- 🐛 **Bug Report** → Gunakan [GitHub Issues](https://github.com/ikyletwar/Nihonjin-AI/issues) dengan label `bug`
- 💡 **Feature Request** → Gunakan [GitHub Issues](https://github.com/ikyletwar/Nihonjin-AI/issues) dengan label `enhancement`
- 💬 **Diskusi Umum** → Gunakan [GitHub Discussions](https://github.com/ikyletwar/Nihonjin-AI/discussions)

---

## 📊 Project Stats

[![GitHub stars](https://img.shields.io/github/stars/ikyletwar/Nihonjin-AI?style=for-the-badge&logo=github&color=6366f1)](https://github.com/ikyletwar/Nihonjin-AI/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ikyletwar/Nihonjin-AI?style=for-the-badge&logo=github&color=6366f1)](https://github.com/ikyletwar/Nihonjin-AI/network)
[![GitHub issues](https://img.shields.io/github/issues/ikyletwar/Nihonjin-AI?style=for-the-badge&logo=github&color=ef4444)](https://github.com/ikyletwar/Nihonjin-AI/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/ikyletwar/Nihonjin-AI?style=for-the-badge&logo=github&color=22c55e)](https://github.com/ikyletwar/Nihonjin-AI/commits)

---

<div align="center">

## Penutup

**Nihonjin AI** dirancang untuk **efisiensi, kontrol, dan konsistensi output.**

```
Tanpa distraksi.
Tanpa elemen berlebih.
Fokus pada hasil.
```

---

*Jika proyek ini bermanfaat, pertimbangkan untuk memberikan ⭐ di GitHub.*

[![GitHub](https://img.shields.io/badge/GitHub-ikyletwar%2FNihonjin--AI-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ikyletwar/Nihonjin-AI)

</div>
