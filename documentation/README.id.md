<p align="center">
<img src="https://i.ibb.co/mCwWq30J/chatunity-bot.jpg" 
</p>

<h1 align="center">© ChatUnity-Bot X 🤖</h1>
<p align="center"><strong>Bot WhatsApp canggih dengan banyak fitur, otomatisasi, dan hiburan!</strong></p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J">
    <img src="https://img.shields.io/badge/Saluran_Resmi-black?style=for-the-badge&logo=whatsapp" alt="Saluran Resmi">
  </a>
</p>

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/Main_README-Kembali_ke_root-00897B?style=for-the-badge" alt="Main README">
  </a>
</p>

---

## 📌 Pendahuluan

© ChatUnity-Bot adalah bot WhatsApp multifungsi yang dirancang untuk mempermudah pengelolaan chat dan menyediakan fitur-fitur lanjutan. Dengan antarmuka yang intuitif dan konfigurasi yang mudah, bot ini cocok untuk siapa saja yang ingin meningkatkan pengalaman menggunakan WhatsApp.

---

## 🚀 Instalasi Termux

### 1. Instalasi Termux tanpa ZIP (disarankan)

[![Tutorial Instalasi](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Unduh [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
2. Tempel semua perintah di bawah ini sekaligus, tanpa ada yang terlewat dan sesuai urutan

```bash
termux-setup-storage && \
pkg update && pkg upgrade -y && \
pkg install git nodejs ffmpeg imagemagick yarn -y && \
cd ~ && \
git clone https://github.com/chatunitycenter/chatunity-bot.git && \
cd chatunity-bot && \
yarn install && \
yarn start
```

---

### 2. Instalasi Termux dengan ZIP (untuk developers)

[![Tutorial Instalasi](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Unduh file ZIP bot dari GitHub
2. Unduh [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
3. Tempel semua perintah di bawah ini ke Termux

```bash
termux-setup-storage && \
pkg update && pkg upgrade -y && \
pkg install x11-repo tur-repo -y && \
pkg install git nodejs ffmpeg imagemagick yarn -y && \
cd ~ && \
cd ~/storage/downloads && \
unzip chatunity-bot-main.zip && \
cd chatunity-bot-main && \
yarn install && \
yarn start
```

---

### 3. Instalasi Termux dengan fork milikmu

[![Tutorial Instalasi](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

Gunakan metode ini jika kamu punya fork sendiri dan ingin menginstal langsung dari repositorimu.

1. Buat fork proyek ini di GitHub
2. Ganti `YOUR-USERNAME` pada perintah di bawah dengan username GitHub milikmu
3. Tempel semua perintah di bawah ini sekaligus di Termux

```bash
termux-setup-storage && \
pkg update && pkg upgrade -y && \
pkg install git nodejs ffmpeg imagemagick yarn -y && \
cd ~ && \
git clone https://github.com/YOUR-USERNAME/chatunity-bot.git && \
cd chatunity-bot && \
yarn install && \
yarn start
```

Jika fork milikmu memakai nama repositori yang berbeda, ganti `chatunity-bot` pada perintah `git clone` dan `cd` dengan nama yang benar.

---

## 🕒 Online 24/7 dengan PM2 (Termux)

<details>
<summary><b>Klik di sini untuk melihat langkah-langkah</b></summary>

```bash
npm i -g pm2
pm2 start index.js
pm2 save
pm2 logs
```

</details>

---

## 🌐 Instalasi di Windows/VPS/RDP

<details>
<summary><b>Klik di sini untuk melihat langkah-langkah</b></summary>

1. Unduh:
   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en/download)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [ImageMagick](https://imagemagick.org/script/download.php)

2. Clone dan instal:
   ```bash
   git clone https://github.com/chatunitycenter/chatunity-bot
   cd chatunity-bot
   npm install
   npm update
   npm start
   ```

</details>

---

## 📂 Sumber daya berguna

- **Dashboard GitHub**: [Kunjungi di sini](https://github.com/chatunity-bot)
- **Saluran WhatsApp**: [Gabung di sini](https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J)
- **Kontak**: [Tulis di sini](https://wa.me/393773842461)
- **Kolaborasi**: [Ikut di sini](https://whatsapp.com/channel/0029Vb1C4od5vKA35u1Mqc06)

---

## VPS ChatUnity

Butuh solusi siap pakai agar bot tetap online 24/7 tanpa harus mengatur semuanya secara manual?

VPS ChatUnity dirancang untuk meng-host bot secara stabil dan berkelanjutan.

- Konfigurasi mudah
- Lebih stabil untuk penggunaan terus-menerus
- Cocok untuk bot yang selalu aktif

Untuk informasi dan ketersediaan hubungi [393773842461](https://wa.me/393773842461).

## 📜 Lisensi

© ChatUnity-Bot. Semua hak dilindungi. Lihat lisensi untuk detail lebih lanjut.

<p align="center"><strong>🌟 Dukung proyek ini dengan memberikan bintang di GitHub! 🌟</strong></p>