<p align="center">
<img src="https://i.ibb.co/mCwWq30J/chatunity-bot.jpg" 
</p>

<h1 align="center">© ChatUnity-Bot X 🤖</h1>
<p align="center"><strong>¡Un bot avanzado para WhatsApp, lleno de funciones y diversión!</strong></p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J">
    <img src="https://img.shields.io/badge/Canal_Oficial-black?style=for-the-badge&logo=whatsapp" alt="Canal Oficial">
  </a>
</p>

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/README%20Principal-Volver%20a%20la%20ra%C3%ADz-FF8C00?style=for-the-badge" alt="README principal">
  </a>
</p>

---

## 📌 Introducción

© ChatUnity-Bot es un bot multifuncional para WhatsApp, diseñado para simplificar la gestión de chats y ofrecer funciones avanzadas. Con una interfaz intuitiva y una configuración sencilla, es perfecto para cualquiera que quiera mejorar su experiencia en WhatsApp.

---

## 🚀 Instalación en Termux

### 1. Instalación en Termux sin ZIP (recomendada)

[![Tutorial de instalación](https://img.shields.io/badge/Tutorial-Instalaci%C3%B3n-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Descarga [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
2. Pega todos los comandos de abajo de una sola vez y en el mismo orden

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

### 2. Instalación en Termux con ZIP (para developers)

[![Tutorial de instalación](https://img.shields.io/badge/Tutorial-Instalaci%C3%B3n-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Descarga el ZIP del bot desde GitHub
2. Descarga [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
3. Pega todos los comandos de abajo en Termux

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

### 3. Instalación en Termux con tu fork

[![Tutorial de instalación](https://img.shields.io/badge/Tutorial-Instalaci%C3%B3n-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

Usa este método si tienes tu propio fork y quieres instalar directamente desde tu repositorio.

1. Crea tu fork del proyecto en GitHub
2. Sustituye `YOUR-USERNAME` en el comando de abajo por tu nombre de usuario de GitHub
3. Pega todos los comandos de abajo de una sola vez dentro de Termux

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

Si tu fork usa un nombre de repositorio distinto, reemplaza `chatunity-bot` tanto en el comando `git clone` como en el comando `cd`.

---

## 🕒 Activo 24/7 con PM2 (Termux)

<details>
<summary><b>Haz clic aquí para ver los pasos</b></summary>

```bash
npm i -g pm2
pm2 start index.js
pm2 save
pm2 logs
```

</details>

---

## 🌐 Instalación en Windows/VPS/RDP

<details>
<summary><b>Haz clic aquí para ver los pasos</b></summary>

1. Descarga:
   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en/download)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [ImageMagick](https://imagemagick.org/script/download.php)

2. Clona e instala:
   ```bash
   git clone https://github.com/chatunitycenter/chatunity-bot
   cd chatunity-bot
   npm install
   npm update
   npm start
   ```

</details>

---

## 📂 Recursos útiles

- **Panel GitHub**: [Visita aquí](https://github.com/chatunity-bot)
- **Canal de WhatsApp**: [Únete aquí](https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J)
- **Contacto**: [Escribe aquí](https://wa.me/393773842461)
- **Colaboraciones**: [Participa aquí](https://whatsapp.com/channel/0029Vb1C4od5vKA35u1Mqc06)

---

## VPS ChatUnity

¿Necesitas una solución lista para mantener el bot en línea 24/7 sin configurar todo manualmente?

Las VPS ChatUnity están pensadas para alojar el bot de forma estable y continua.

- Configuración sencilla
- Mayor estabilidad para uso continuo
- Ideal para bots siempre activos

Para información y disponibilidad contacta a [393773842461](https://wa.me/393773842461).

## 📜 Licencia

© ChatUnity-Bot. Todos los derechos reservados. Consulta la licencia para más detalles.

<p align="center"><strong>🌟 ¡Apoya el proyecto con una estrella en GitHub! 🌟</strong></p>