<p align="center">
<img src="https://i.ibb.co/mCwWq30J/chatunity-bot.jpg" 
</p>

<h1 align="center">© ChatUnity-Bot X 🤖</h1>
<p align="center"><strong>Un bot avanzato per WhatsApp, ricco di funzionalità e divertimento!</strong></p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J">
    <img src="https://img.shields.io/badge/Canale_Ufficiale-black?style=for-the-badge&logo=whatsapp" alt="Canale Ufficiale">
  </a>
</p>

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/README%20Principale-Torna%20alla%20root-2E8B57?style=for-the-badge" alt="README principale">
  </a>
</p>

---

## 📌 Introduzione

© ChatUnity-Bot è un bot multifunzionale per WhatsApp, progettato per semplificare la gestione delle chat e offrire funzionalità avanzate. Con un'interfaccia intuitiva e una configurazione semplice, è perfetto per chiunque voglia migliorare l'esperienza su WhatsApp.

---

## 🚀 Installazione Termux

### 1. Installazione Termux senza ZIP (consigliata)

[![Tutorial Installazione](https://img.shields.io/badge/Tutorial-Installazione-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Scarica [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
2. Incolla tutti i comandi qui sotto in una sola volta, senza escluderne nessuno e nell'ordine indicato

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

### 2. Installazione Termux con ZIP (per developers)

[![Tutorial Installazione](https://img.shields.io/badge/Tutorial-Installazione-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Scarica la ZIP del bot da GitHub
2. Scarica [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
3. Incolla tutti i comandi qui sotto su Termux

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

### 3. Installazione Termux con il tuo fork

[![Tutorial Installazione](https://img.shields.io/badge/Tutorial-Installazione-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

Usa questo metodo se hai un tuo fork e vuoi installare direttamente dal tuo repository.

1. Crea il tuo fork del progetto su GitHub
2. Sostituisci `YOUR-USERNAME` nel comando qui sotto con il tuo username GitHub
3. Incolla tutti i comandi qui sotto in una sola volta su Termux

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

Se il tuo fork usa un nome repository diverso, sostituisci `chatunity-bot` sia nel comando `git clone` sia nel comando `cd`.

---

## 🕒 Attivo 24/7 con PM2 (Termux)

<details>
<summary><b>Clicca qui per vedere i passaggi</b></summary>

```bash
npm i -g pm2
pm2 start index.js
pm2 save
pm2 logs
```

</details>

---

## 🌐 Installazione su Windows/VPS/RDP

<details>
<summary><b>Clicca qui per vedere i passaggi</b></summary>

1. Scarica:
   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en/download)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [ImageMagick](https://imagemagick.org/script/download.php)

2. Clona e installa:
   ```bash
   git clone https://github.com/chatunitycenter/chatunity-bot
   cd chatunity-bot
   npm install
   npm update
   npm start
   ```

</details>

---

## 📂 Risorse Utili

- **Dashboard GitHub**: [Visita qui](https://github.com/chatunity-bot)
- **Canale WhatsApp**: [Unisciti qui](https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J)
- **Contatto**: [Scrivi qui](https://wa.me/393773842461)
- **Collaborazioni**: [Partecipa qui](https://whatsapp.com/channel/0029Vb1C4od5vKA35u1Mqc06)

---

## VPS ChatUnity

Hai bisogno di una soluzione pronta per tenere il bot online 24/7 senza configurare tutto manualmente?

Le VPS ChatUnity sono pensate per ospitare il bot in modo stabile e continuativo.

- Configurazione semplice
- Maggiore stabilita per utilizzo continuativo
- Ideale per bot sempre attivi

Per informazioni e disponibilita contattare [393773842461](https://wa.me/393773842461).

## 📜 Licenza

© ChatUnity-Bot. Tutti i diritti riservati. Consulta la licenza per i dettagli.

<p align="center"><strong>🌟 Supporta il progetto con una stella su GitHub! 🌟</strong></p>