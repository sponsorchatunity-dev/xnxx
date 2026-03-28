<p align="center">
<img src="https://i.ibb.co/mCwWq30J/chatunity-bot.jpg" 
</p>

<h1 align="center">© ChatUnity-Bot X 🤖</h1>
<p align="center"><strong>Özellikler, otomasyon ve eğlence dolu gelişmiş bir WhatsApp botu!</strong></p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J">
    <img src="https://img.shields.io/badge/Resmi_Kanal-black?style=for-the-badge&logo=whatsapp" alt="Resmi Kanal">
  </a>
</p>

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/Ana_README-K%C3%B6ke_d%C3%B6n-AD1457?style=for-the-badge" alt="Ana README">
  </a>
</p>

---

## 📌 Giriş

© ChatUnity-Bot, sohbet yönetimini kolaylaştırmak ve gelişmiş özellikler sunmak için tasarlanmış çok işlevli bir WhatsApp botudur. Sezgisel arayüzü ve kolay kurulumu sayesinde WhatsApp deneyimini geliştirmek isteyen herkes için uygundur.

---

## 🚀 Termux Kurulumu

### 1. ZIP olmadan Termux kurulumu (önerilen)

[![Kurulum Eğitimi](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/) indir
2. Aşağıdaki tüm komutları eksiksiz ve doğru sırayla tek seferde yapıştır

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

### 2. ZIP ile Termux kurulumu (developers için)

[![Kurulum Eğitimi](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Botun ZIP dosyasını GitHub'dan indir
2. [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/) indir
3. Aşağıdaki tüm komutları Termux içine yapıştır

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

### 3. Kendi fork'un ile Termux kurulumu

[![Kurulum Eğitimi](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

Kendi fork'una sahipsen ve doğrudan kendi deposundan kurulum yapmak istiyorsan bu yöntemi kullan.

1. GitHub üzerinde projenin kendi fork'unu oluştur
2. Aşağıdaki komutta geçen `YOUR-USERNAME` kısmını GitHub kullanıcı adınla değiştir
3. Aşağıdaki tüm komutları tek seferde Termux içine yapıştır

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

Fork'un farklı bir depo adı kullanıyorsa `git clone` ve `cd` komutlarındaki `chatunity-bot` adını doğru isimle değiştir.

---

## 🕒 PM2 ile 24/7 açık tutma (Termux)

<details>
<summary><b>Adımları görmek için buraya tıklayın</b></summary>

```bash
npm i -g pm2
pm2 start index.js
pm2 save
pm2 logs
```

</details>

---

## 🌐 Windows/VPS/RDP Üzerinde Kurulum

<details>
<summary><b>Adımları görmek için buraya tıklayın</b></summary>

1. İndir:
   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en/download)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [ImageMagick](https://imagemagick.org/script/download.php)

2. Klonla ve kur:
   ```bash
   git clone https://github.com/chatunitycenter/chatunity-bot
   cd chatunity-bot
   npm install
   npm update
   npm start
   ```

</details>

---

## 📂 Faydalı Kaynaklar

- **GitHub Paneli**: [Burayı ziyaret et](https://github.com/chatunity-bot)
- **WhatsApp Kanalı**: [Buradan katıl](https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J)
- **İletişim**: [Buradan yaz](https://wa.me/393773842461)
- **İş birlikleri**: [Buradan katıl](https://whatsapp.com/channel/0029Vb1C4od5vKA35u1Mqc06)

---

## ChatUnity VPS

Botu 24/7 çevrimiçi tutmak için her şeyi elle yapılandırmadan hazır bir çözüme mi ihtiyacın var?

ChatUnity VPS, botu stabil ve sürekli şekilde barındırmak için tasarlanmıştır.

- Kolay kurulum
- Sürekli kullanım için daha yüksek stabilite
- Her zaman aktif botlar için ideal

Bilgi ve uygunluk için [393773842461](https://wa.me/393773842461) ile iletişime geçin.

## 📜 Lisans

© ChatUnity-Bot. Tüm hakları saklıdır. Ayrıntılar için lisansa bakın.

<p align="center"><strong>🌟 GitHub'da yıldız vererek projeyi destekleyin! 🌟</strong></p>