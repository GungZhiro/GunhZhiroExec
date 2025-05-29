# SC RAVAGE SQL Version

Ini adalah versi modifikasi dari SC RAVAGE V3 yang telah diintegrasikan dengan database SQLite untuk menyimpan data owner dan lainnya.

## 📦 Struktur Utama

- `db.js` – koneksi SQLite
- `init-db.js` – inisialisasi database dan data awal
- `database.sqlite` – file database (jangan upload ke GitHub)
- `lib/` – fungsi dan konfigurasi bot
- `index.js` atau `DaffaDev.js` – file utama bot

## 🚀 Cara Menjalankan

1. Install dependency SQLite:
   ```bash
   npm install sqlite3
