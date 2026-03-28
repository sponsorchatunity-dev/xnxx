<p align="center">
<img src="https://i.ibb.co/mCwWq30J/chatunity-bot.jpg" 
</p>

<h1 align="center">© ChatUnity-Bot X 🤖</h1>
<p align="center"><strong>Продвинутый WhatsApp-бот с множеством функций, автоматизацией и развлечениями!</strong></p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J">
    <img src="https://img.shields.io/badge/%D0%9E%D1%84%D0%B8%D1%86%D0%B8%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9_%D0%BA%D0%B0%D0%BD%D0%B0%D0%BB-black?style=for-the-badge&logo=whatsapp" alt="Официальный канал">
  </a>
</p>

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/Main_README-%D0%9D%D0%B0%D0%B7%D0%B0%D0%B4_%D0%B2_%D0%BA%D0%BE%D1%80%D0%B5%D0%BD%D1%8C-3949AB?style=for-the-badge" alt="Главный README">
  </a>
</p>

---

## 📌 Введение

© ChatUnity-Bot — это многофункциональный WhatsApp-бот, созданный для упрощения управления чатами и предоставления расширенных возможностей. Благодаря понятному интерфейсу и простой настройке он отлично подходит всем, кто хочет улучшить свой опыт использования WhatsApp.

---

## 🚀 Установка через Termux

### 1. Установка через Termux без ZIP (рекомендуется)

[![Видео по установке](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Скачайте [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
2. Вставьте все команды ниже за один раз и строго по порядку

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

### 2. Установка через Termux с ZIP (для developers)

[![Видео по установке](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Скачайте ZIP-архив бота с GitHub
2. Скачайте [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
3. Вставьте все команды ниже в Termux

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

### 3. Установка через Termux с вашим fork

[![Видео по установке](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

Используйте этот способ, если у вас есть собственный fork и вы хотите установить бот напрямую из своего репозитория.

1. Создайте свой fork проекта на GitHub
2. Замените `YOUR-USERNAME` в команде ниже на ваш GitHub username
3. Вставьте все команды ниже за один раз в Termux

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

Если ваш fork использует другое имя репозитория, замените `chatunity-bot` и в команде `git clone`, и в команде `cd`.

---

## 🕒 Работа 24/7 с PM2 (Termux)

<details>
<summary><b>Нажмите здесь, чтобы посмотреть шаги</b></summary>

```bash
npm i -g pm2
pm2 start index.js
pm2 save
pm2 logs
```

</details>

---

## 🌐 Установка на Windows/VPS/RDP

<details>
<summary><b>Нажмите здесь, чтобы посмотреть шаги</b></summary>

1. Скачайте:
   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en/download)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [ImageMagick](https://imagemagick.org/script/download.php)

2. Клонируйте и установите:
   ```bash
   git clone https://github.com/chatunitycenter/chatunity-bot
   cd chatunity-bot
   npm install
   npm update
   npm start
   ```

</details>

---

## 📂 Полезные ресурсы

- **GitHub Dashboard**: [Перейти сюда](https://github.com/chatunity-bot)
- **WhatsApp-канал**: [Присоединиться](https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J)
- **Контакт**: [Написать сюда](https://wa.me/393773842461)
- **Сотрудничество**: [Участвовать здесь](https://whatsapp.com/channel/0029Vb1C4od5vKA35u1Mqc06)

---

## ChatUnity VPS

Нужна готовая платформа, чтобы бот работал 24/7 без ручной настройки всего окружения?

VPS от ChatUnity созданы для стабильного и постоянного хостинга бота.

- Простая настройка
- Более высокая стабильность для постоянной работы
- Идеально для всегда активных ботов

Для информации и доступности свяжитесь с [393773842461](https://wa.me/393773842461).

## 📜 Лицензия

© ChatUnity-Bot. Все права защищены. Подробнее смотрите в лицензии.

<p align="center"><strong>🌟 Поддержите проект звездой на GitHub! 🌟</strong></p>