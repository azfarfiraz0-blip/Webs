# 🚀 Termux API Master Ultimate Tool

Tool otomatisasi dan kontrol hardware Android lengkap menggunakan **Python** dan **Termux:API**.

## 📌 Fitur Utama
- **Kamera & Media**: Foto kamera depan/belakang, perekam audio mikrofon, dan ubah wallpaper HP.
- **Hardware & Sensor**: Senter, getar, cek baterai, baca live data sensor, transmiter IR, dan tes sidik jari (biometrik).
- **Komunikasi & Jaringan**: Panggil nomor telepon, kontrol/info Wi-Fi, kirim notifikasi kustom, dan clipboard.
- **Sistem & Navigasi**: Kontrol volume media/panggilan/ringtone, serta tombol navigasi (Back, Home, Status Bar).

## 📥 Cara Install & Gunakan

```bash
# Update & Install Dependensi
pkg update && pkg upgrade -y
pkg install python git termux-api -y

# Setup Akses Storage
termux-setup-storage

# Clone & Jalankan
git clone [https://github.com/USERNAME_KAMU/NAMA_REPO_KAMU.git](https://github.com/USERNAME_KAMU/NAMA_REPO_KAMU.git)
cd NAMA_REPO_KAMU
python termux_master.py


Simpan dengan **CTRL + X**, ketik **Y**, lalu **ENTER**.

---

### Langkah 2: Unggah ke GitHub

Jalankan perintah-perintah Git ini satu per satu di Termux (ganti `USERNAME_KAMU` dan `NAMA_REPO_KAMU` sesuai akun GitHub milikmu):

```bash
# 1. Inisialisasi Git di folder saat ini
git init

# 2. Tambahkan file skrip dan README
git add termux_master.py README.md

# 3. Buat catatan commit
git commit -m "Initial commit - Complete Termux API Master Tool"

# 4. Atur branch utama ke main
git branch -M main

# 5. Hubungkan ke repositori GitHub kamu
git remote add origin https://github.com/USERNAME_KAMU/NAMA_REPO_KAMU.git

# 6. Unggah file ke GitHub
git push -u origin main
