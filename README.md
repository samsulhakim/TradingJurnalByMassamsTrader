TradeJournalByMassamsTrader

Berikut draf README.md yang sudah diperbarui dengan nama repositori dan aplikasi TradeJournalByMassamsTrader:

Markdown
# 📈 TradeJournalByMassamsTrader

Aplikasi **Trading Journal** modern, ringan, dan responsif berbasis Web. Memudahkan trader untuk mencatat riwayat transaksi, menganalisis performa trading (*win rate*, total PnL, *equity curve*), dan menyimpan data secara otomatis ke **Google Sheets** tanpa memerlukan sewa server/backend tambahan!

![License](https://img.shields.io/badge/License-MIT-emerald.svg)
![Frontend](https://img.shields.io/badge/Frontend-HTML%20%7C%20TailwindCSS%20%7C%20JS-blue.svg)
![Database](https://img.shields.io/badge/Database-Google%20Sheets-green.svg)

---

## ✨ Fitur Utama

- 🔐 **Sistem Login & Autentikasi** – Akses terproteksi menggunakan sesi *LocalStorage* & JWT simulasi.
- 📊 **Dashboard Analytics & Grafik** –
  - **Equity Curve Chart**: Grafik pertumbuhan saldo/akumulasi profit secara *real-time*.
  - **Win/Loss Ratio**: Visualisasi rasio kemenangan trading.
  - **Statistik Otomatis**: Total Trade, Win Rate (%), Total PnL ($), dan Profit Factor.
- 📝 **Manajemen Jurnal (CRUD)** – Tambah, filter berdasarkan statistik, dan hapus riwayat transaksi.
- ☁️ **Integrasi Google Sheets** – Menyimpan semua catatan transaksi secara otomatis ke Google Sheets via Google Apps Script (Gratis & Tanpa Server).
- 📱 **Mobile-Friendly & Dark Mode** – Desain antarmuka bersih dan nyaman menggunakan Tailwind CSS.

---

## 🚀 Panduan Memulai (Quick Start)

### 1. Jalankan Secara Lokal

1. *Clone* repositori ini:
   ```bash
   git clone [https://github.com/USERNAME/TradeJournalByMassamsTrader.git](https://github.com/USERNAME/TradeJournalByMassamsTrader.git)
