<p align="center">
<img src="https://i.ibb.co/mCwWq30J/chatunity-bot.jpg" 
</p>

<h1 align="center">© ChatUnity-Bot X 🤖</h1>
<p align="center"><strong>一个功能丰富、适合娱乐与管理的高级 WhatsApp 机器人！</strong></p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J">
    <img src="https://img.shields.io/badge/%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93-black?style=for-the-badge&logo=whatsapp" alt="官方频道">
  </a>
</p>

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/%E4%B8%BB_README-%E8%BF%94%E5%9B%9E%E6%A0%B9%E7%9B%AE%E5%BD%95-C62828?style=for-the-badge" alt="主 README">
  </a>
</p>

---

## 📌 介绍

© ChatUnity-Bot 是一个多功能 WhatsApp 机器人，旨在简化聊天管理并提供高级功能。它拥有直观的界面和简单的配置流程，非常适合想要提升 WhatsApp 使用体验的用户。

---

## 🚀 Termux 安装

### 1. 无 ZIP 的 Termux 安装（推荐）

[![安装教程](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. 下载 [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
2. 按顺序一次性粘贴下面所有命令，不要遗漏任何一条

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

### 2. 使用 ZIP 的 Termux 安装（开发者）

[![安装教程](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. 从 GitHub 下载机器人的 ZIP 文件
2. 下载 [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
3. 在 Termux 中粘贴下面所有命令

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

### 3. 使用你的 Fork 进行 Termux 安装

[![安装教程](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

如果你有自己的 fork 并希望直接从自己的仓库安装，请使用此方法。

1. 在 GitHub 上创建你自己的项目 fork
2. 将下面命令中的 `YOUR-USERNAME` 替换为你的 GitHub 用户名
3. 在 Termux 中一次性粘贴下面所有命令

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

如果你的 fork 使用不同的仓库名，请同时替换 `git clone` 和 `cd` 命令中的 `chatunity-bot`。

---

## 🕒 使用 PM2 保持 24/7 在线（Termux）

<details>
<summary><b>点击这里查看步骤</b></summary>

```bash
npm i -g pm2
pm2 start index.js
pm2 save
pm2 logs
```

</details>

---

## 🌐 在 Windows/VPS/RDP 上安装

<details>
<summary><b>点击这里查看步骤</b></summary>

1. 下载：
   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en/download)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [ImageMagick](https://imagemagick.org/script/download.php)

2. 克隆并安装：
   ```bash
   git clone https://github.com/chatunitycenter/chatunity-bot
   cd chatunity-bot
   npm install
   npm update
   npm start
   ```

</details>

---

## 📂 实用资源

- **GitHub 面板**: [点击访问](https://github.com/chatunity-bot)
- **WhatsApp 频道**: [点击加入](https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J)
- **联系方式**: [点击联系](https://wa.me/393773842461)
- **合作渠道**: [点击参与](https://whatsapp.com/channel/0029Vb1C4od5vKA35u1Mqc06)

---

## ChatUnity VPS

需要一种现成方案，让机器人 24/7 在线运行而无需手动配置全部环境吗？

ChatUnity VPS 旨在为机器人提供稳定、持续的托管环境。

- 配置简单
- 更适合长期稳定运行
- 非常适合持续在线的机器人

如需了解详情和可用性，请联系 [393773842461](https://wa.me/393773842461)。

## 📜 许可证

© ChatUnity-Bot. 保留所有权利。详情请查看许可证。

<p align="center"><strong>🌟 如果这个项目对你有帮助，欢迎点亮 GitHub Star！ 🌟</strong></p>