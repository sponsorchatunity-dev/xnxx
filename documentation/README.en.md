<p align="center">
<img src="https://i.ibb.co/mCwWq30J/chatunity-bot.jpg" 
</p>

<h1 align="center">© ChatUnity-Bot X 🤖</h1>
<p align="center"><strong>An advanced WhatsApp bot packed with features and entertainment!</strong></p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J">
    <img src="https://img.shields.io/badge/Official_Channel-black?style=for-the-badge&logo=whatsapp" alt="Official Channel">
  </a>
</p>

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/Main%20README-Back%20to%20root-1E90FF?style=for-the-badge" alt="Main README">
  </a>
</p>

---

## 📌 Introduction

© ChatUnity-Bot is a multifunctional WhatsApp bot designed to simplify chat management and provide advanced features. With an intuitive interface and easy setup, it is perfect for anyone who wants to improve their WhatsApp experience.

---

## 🚀 Termux Installation

### 1. Termux installation without ZIP (recommended)

[![Installation Tutorial](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Download [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
2. Paste all commands below in one go, in the same order

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

### 2. Termux installation with ZIP (for developers)

[![Installation Tutorial](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Download the bot ZIP from GitHub
2. Download [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
3. Paste all commands below in Termux

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

### 3. Termux installation with your fork

[![Installation Tutorial](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

Use this method if you have your own fork and want to install directly from your repository.

1. Create your fork of the project on GitHub
2. Replace `YOUR-USERNAME` in the command below with your GitHub username
3. Paste all commands below in one go inside Termux

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

If your fork uses a different repository name, replace `chatunity-bot` in the clone command and in the `cd` command with the correct name.

---

## 🕒 Stay online 24/7 with PM2 (Termux)

<details>
<summary><b>Click here to view the steps</b></summary>

```bash
npm i -g pm2
pm2 start index.js
pm2 save
pm2 logs
```

</details>

---

## 🌐 Installation on Windows/VPS/RDP

<details>
<summary><b>Click here to view the steps</b></summary>

1. Download:
   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en/download)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [ImageMagick](https://imagemagick.org/script/download.php)

2. Clone and install:
   ```bash
   git clone https://github.com/chatunitycenter/chatunity-bot
   cd chatunity-bot
   npm install
   npm update
   npm start
   ```

</details>

---

## 📂 Useful Resources

- **GitHub Dashboard**: [Visit here](https://github.com/chatunity-bot)
- **WhatsApp Channel**: [Join here](https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J)
- **Contact**: [Write here](https://wa.me/393773842461)
- **Collaborations**: [Join here](https://whatsapp.com/channel/0029Vb1C4od5vKA35u1Mqc06)

---

## ChatUnity VPS

Need a ready-to-use solution to keep the bot online 24/7 without configuring everything manually?

ChatUnity VPS plans are designed to host the bot in a stable and continuous way.

- Simple setup
- Better stability for continuous usage
- Ideal for always-on bots

For information and availability contact [393773842461](https://wa.me/393773842461).

## 📜 License

© ChatUnity-Bot. All rights reserved. Check the license for details.

<p align="center"><strong>🌟 Support the project with a GitHub star! 🌟</strong></p>