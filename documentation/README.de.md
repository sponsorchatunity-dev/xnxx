<p align="center">
<img src="https://i.ibb.co/mCwWq30J/chatunity-bot.jpg" 
</p>

<h1 align="center">© ChatUnity-Bot X 🤖</h1>
<p align="center"><strong>Ein fortschrittlicher WhatsApp-Bot voller Funktionen und Unterhaltung!</strong></p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J">
    <img src="https://img.shields.io/badge/Offizieller_Kanal-black?style=for-the-badge&logo=whatsapp" alt="Offizieller Kanal">
  </a>
</p>

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/HauptREADME-Zur%C3%BCck%20zur%20Root-696969?style=for-the-badge" alt="Haupt README">
  </a>
</p>

---

## 📌 Einführung

© ChatUnity-Bot ist ein multifunktionaler WhatsApp-Bot, der entwickelt wurde, um die Chat-Verwaltung zu vereinfachen und erweiterte Funktionen bereitzustellen. Mit einer intuitiven Oberfläche und einfacher Einrichtung ist er ideal für alle, die ihre WhatsApp-Erfahrung verbessern möchten.

---

## 🚀 Termux-Installation

### 1. Termux-Installation ohne ZIP (empfohlen)

[![Installationsanleitung](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Lade [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/) herunter
2. Füge alle folgenden Befehle auf einmal und in der angegebenen Reihenfolge ein

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

### 2. Termux-Installation mit ZIP (für Developers)

[![Installationsanleitung](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Lade die ZIP des Bots von GitHub herunter
2. Lade [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/) herunter
3. Füge alle folgenden Befehle in Termux ein

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

### 3. Termux-Installation mit deinem Fork

[![Installationsanleitung](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

Nutze diese Methode, wenn du einen eigenen Fork hast und direkt aus deinem Repository installieren willst.

1. Erstelle deinen Fork des Projekts auf GitHub
2. Ersetze `YOUR-USERNAME` im folgenden Befehl durch deinen GitHub-Benutzernamen
3. Füge alle folgenden Befehle auf einmal in Termux ein

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

Wenn dein Fork einen anderen Repository-Namen verwendet, ersetze `chatunity-bot` sowohl im `git clone`- als auch im `cd`-Befehl.

---

## 🕒 Mit PM2 24/7 online bleiben (Termux)

<details>
<summary><b>Klicke hier, um die Schritte zu sehen</b></summary>

```bash
npm i -g pm2
pm2 start index.js
pm2 save
pm2 logs
```

</details>

---

## 🌐 Installation auf Windows/VPS/RDP

<details>
<summary><b>Klicke hier, um die Schritte zu sehen</b></summary>

1. Herunterladen:
   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en/download)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [ImageMagick](https://imagemagick.org/script/download.php)

2. Klonen und installieren:
   ```bash
   git clone https://github.com/chatunitycenter/chatunity-bot
   cd chatunity-bot
   npm install
   npm update
   npm start
   ```

</details>

---

## 📂 Nützliche Ressourcen

- **GitHub-Dashboard**: [Hier besuchen](https://github.com/chatunity-bot)
- **WhatsApp-Kanal**: [Hier beitreten](https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J)
- **Kontakt**: [Hier schreiben](https://wa.me/393773842461)
- **Zusammenarbeit**: [Hier teilnehmen](https://whatsapp.com/channel/0029Vb1C4od5vKA35u1Mqc06)

---

## ChatUnity VPS

Brauchst du eine fertige Lösung, um den Bot 24/7 online zu halten, ohne alles manuell zu konfigurieren?

Die ChatUnity-VPS sind dafür gedacht, den Bot stabil und dauerhaft zu hosten.

- Einfache Konfiguration
- Mehr Stabilität für den Dauereinsatz
- Ideal für dauerhaft aktive Bots

Für Informationen und Verfügbarkeit kontaktiere [393773842461](https://wa.me/393773842461).

## 📜 Lizenz

© ChatUnity-Bot. Alle Rechte vorbehalten. Siehe Lizenz für weitere Details.

<p align="center"><strong>🌟 Unterstütze das Projekt mit einem Stern auf GitHub! 🌟</strong></p>