Praktikum Python - Rian Rahmat Hidayat

Repositori ini berisi kumpulan kode, latihan, dan tugas praktikum menggunakan bahasa pemrograman Python. Proyek ini dilengkapi dengan fitur interaktif, pengelolaan virtual environment, serta pustaka tambahan untuk mempercantik antarmuka terminal.

📁 Struktur Direktori Proyek

PraktikumRendi-python/
│
├── .venv/               # Folder Virtual Environment (terisolasi)
├── halo.py              # Program utama Python (interaktif & berwarna)
├── requirements.txt     # Daftar pustaka/dependensi proyek
└── README.md            # Panduan dan dokumentasi proyek


🛠️ Cara Membuat dan Mengaktifkan Virtual Environment

Sebelum menjalankan program, disarankan menggunakan virtual environment agar pustaka proyek tidak tercampur dengan sistem global Python Anda.

1. Membuat Virtual Environment

Buka terminal (Command Prompt / PowerShell) di dalam folder proyek, lalu jalankan:

python -m venv .venv


2. Mengaktifkan Virtual Environment

PowerShell:

.venv\Scripts\Activate.ps1


Command Prompt (CMD):

.venv\Scripts\activate.bat


(Pastikan tanda (.venv) muncul di awal baris terminal Anda).

📦 Cara Menginstal Dependensi

Proyek ini menggunakan beberapa pustaka pihak ketiga termasuk colorama untuk pewarnaan teks terminal. Instal seluruh dependensi dengan perintah:

pip install -r requirements.txt


▶️ Cara Menjalankan Program

Setelah virtual environment aktif dan dependensi terinstal, jalankan file utama halo.py menggunakan perintah:

python halo.py


Program akan meminta Anda memasukkan nama, umur, dan hobi, lalu menampilkan hasilnya di terminal dengan teks berwarna yang menarik!

🚀 Panduan Git & Push ke GitHub

Jika Anda melakukan perubahan pada kode dan ingin menyimpannya ke GitHub, gunakan perintah berikut di terminal:

# 1. Cek atau tambahkan file yang berubah
git add .

# 2. Buat pesan commit
git commit -m "Memperbarui program praktikum python"

# 3. Kirim ke GitHub
git push
