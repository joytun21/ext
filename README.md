# 🚀 Installer SHC

## 📜 Deskripsi

**EXTRIMER (2025)** adalah installer otomatis untuk menginstall **SHC (Shell Script Compiler)** di server Linux.  
Dengan menggunakan installer ini, Anda dapat dengan mudah:

- Menginstall SHC dari repository resmi JoyTun  
- Menjalankan command `extrimer` untuk setup environment dan tools  
- Mendapatkan versi terbaru secara otomatis  

> Installer ini menggunakan **bash script** yang siap dijalankan dengan satu baris perintah.

---

## 🖥 Tested OS

- Debian 10 / 11 / 12 / 13  
- Ubuntu 20 / 22 / 24 / 25  

---

## 🛠 Instalasi

Jalankan perintah berikut **di terminal server Anda**:

```bash
curl -o /usr/bin/extrimer https://raw.githubusercontent.com/joytun21/ext/main/extrimer \
&& chmod +x /usr/bin/extrimer \
&& extrimer
