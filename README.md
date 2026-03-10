# 🛡️ Patroli VP v1.0 — Villa Pertiwi Depok

Aplikasi patroli satpam berbasis web (PWA) untuk Villa Pertiwi, Depok. Berjalan langsung di browser HP tanpa instalasi dari Play Store.

---

## 🚀 Demo / Akses Langsung

**[→ Buka Aplikasi](https://mitrawashlaundry-code.github.io/patroli-vp/)**

---

## ✨ Fitur Utama

| Fitur | Keterangan |
|-------|-----------|
| 👮 Multi-role | Satpam, Komandan/Ketua RT, Ketua RW |
| 🔑 Login PIN | PIN 6-digit satpam, 4-digit admin |
| 📷 QR Scanner | Scan titik patroli dengan kamera HP |
| ✅ Checklist | Progress patroli real-time |
| ⏱️ Timer shift | Otomatis lanjut meski app ditutup |
| 🚨 Laporan kejadian | Kirim ke WhatsApp Komandan |
| 📊 Statistik | Perbandingan performa satpam |
| 📅 Jadwal | Penjadwalan shift & deteksi keterlambatan |
| 🔥 Firebase sync | Sinkronisasi real-time antar HP (opsional) |
| 💾 Backup/Restore | Export/import konfigurasi JSON |
| 📵 Offline | Berjalan tanpa internet setelah install |
| 🏠 PWA | Install ke homescreen seperti aplikasi native |

---

## 📁 Struktur File

```
patroli-vp/
├── index.html          ← Aplikasi utama (semua-dalam-satu)
├── manifest.json       ← Konfigurasi PWA
├── sw.js               ← Service Worker (offline support)
├── icon-192.png        ← Icon PWA 192×192
├── icon-512.png        ← Icon PWA 512×512
├── PANDUAN.html        ← Panduan pengguna (versi cetak/baca)
└── README.md           ← Dokumentasi ini
```

---

## ⚙️ Setup GitHub Pages

1. Push semua file ke branch `main`
2. **Settings → Pages → Source: main → / (root) → Save**
3. Tunggu 1-2 menit → akses di `https://[username].github.io/[repo-name]/`

---

## 🔐 PIN Default

| Role | PIN Default |
|------|------------|
| Admin/Komandan | `1606` |
| Satpam | Diset saat onboarding |

> ⚠️ Ganti PIN default segera setelah setup pertama via menu **Konfigurasi**.

---

## 📱 Cara Install PWA di HP Android

1. Buka URL aplikasi di **Chrome atau Brave**
2. Tap ikon **⋮ (menu titik tiga)** di pojok kanan atas
3. Tap **"Add to Home screen"** / **"Install app"**
4. Tap **Install** → icon muncul di homescreen

---

## 🔥 Firebase (Opsional)

Untuk sinkronisasi data real-time antar HP:
1. Buat project di [console.firebase.google.com](https://console.firebase.google.com) (gratis)
2. Aktifkan **Firestore Database** (mode test)
3. Daftarkan **Web App** → copy konfigurasi
4. Login sebagai Komandan → **Konfigurasi → 🔥 Firebase** → isi dan simpan

---

## 📋 Versi

| Versi | Tanggal | Perubahan |
|-------|---------|-----------|
| v1.0 | Mar 2026 | Rilis perdana — multi-RT/RW, Firebase sync, backup/restore, Dashboard RW |

---

## 👤 Dibuat untuk

**Villa Pertiwi, Depok** — Sistem patroli satpam berbasis teknologi untuk RT/RW.
