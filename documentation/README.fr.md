<p align="center">
<img src="https://i.ibb.co/mCwWq30J/chatunity-bot.jpg" 
</p>

<h1 align="center">© ChatUnity-Bot X 🤖</h1>
<p align="center"><strong>Un bot WhatsApp avancé, riche en fonctionnalités et en divertissement !</strong></p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J">
    <img src="https://img.shields.io/badge/Canal_Officiel-black?style=for-the-badge&logo=whatsapp" alt="Canal Officiel">
  </a>
</p>

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/README%20Principal-Retour%20%C3%A0%20la%20racine-4169E1?style=for-the-badge" alt="README principal">
  </a>
</p>

---

## 📌 Introduction

© ChatUnity-Bot est un bot WhatsApp multifonction conçu pour simplifier la gestion des chats et offrir des fonctionnalités avancées. Avec une interface intuitive et une configuration simple, il est parfait pour tous ceux qui veulent améliorer leur expérience sur WhatsApp.

---

## 🚀 Installation Termux

### 1. Installation Termux sans ZIP (recommandée)

[![Tutoriel Installation](https://img.shields.io/badge/Tutoriel-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Téléchargez [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
2. Collez toutes les commandes ci-dessous en une seule fois et dans le bon ordre

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

### 2. Installation Termux avec ZIP (pour les developers)

[![Tutoriel Installation](https://img.shields.io/badge/Tutoriel-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Téléchargez le ZIP du bot depuis GitHub
2. Téléchargez [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
3. Collez toutes les commandes ci-dessous dans Termux

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

### 3. Installation Termux avec votre fork

[![Tutoriel Installation](https://img.shields.io/badge/Tutoriel-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

Utilisez cette méthode si vous avez votre propre fork et souhaitez installer directement depuis votre dépôt.

1. Créez votre fork du projet sur GitHub
2. Remplacez `YOUR-USERNAME` dans la commande ci-dessous par votre nom d'utilisateur GitHub
3. Collez toutes les commandes ci-dessous en une seule fois dans Termux

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

Si votre fork utilise un nom de dépôt différent, remplacez `chatunity-bot` à la fois dans la commande `git clone` et dans la commande `cd`.

---

## 🕒 Actif 24/7 avec PM2 (Termux)

<details>
<summary><b>Cliquez ici pour voir les étapes</b></summary>

```bash
npm i -g pm2
pm2 start index.js
pm2 save
pm2 logs
```

</details>

---

## 🌐 Installation sur Windows/VPS/RDP

<details>
<summary><b>Cliquez ici pour voir les étapes</b></summary>

1. Téléchargez :
   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en/download)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [ImageMagick](https://imagemagick.org/script/download.php)

2. Clonez et installez :
   ```bash
   git clone https://github.com/chatunitycenter/chatunity-bot
   cd chatunity-bot
   npm install
   npm update
   npm start
   ```

</details>

---

## 📂 Ressources utiles

- **Tableau de bord GitHub** : [Visitez ici](https://github.com/chatunity-bot)
- **Canal WhatsApp** : [Rejoignez ici](https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J)
- **Contact** : [Écrivez ici](https://wa.me/393773842461)
- **Collaborations** : [Participez ici](https://whatsapp.com/channel/0029Vb1C4od5vKA35u1Mqc06)

---

## VPS ChatUnity

Vous avez besoin d'une solution prête à l'emploi pour garder le bot en ligne 24h/24 et 7j/7 sans tout configurer manuellement ?

Les VPS ChatUnity sont pensées pour héberger le bot de manière stable et continue.

- Configuration simple
- Meilleure stabilité pour une utilisation continue
- Idéal pour les bots toujours actifs

Pour informations et disponibilités, contactez [393773842461](https://wa.me/393773842461).

## 📜 Licence

© ChatUnity-Bot. Tous droits réservés. Consultez la licence pour plus de détails.

<p align="center"><strong>🌟 Soutenez le projet avec une étoile sur GitHub ! 🌟</strong></p>