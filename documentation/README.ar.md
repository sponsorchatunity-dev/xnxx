<p align="center">
<img src="https://i.ibb.co/mCwWq30J/chatunity-bot.jpg" 
</p>

<h1 align="center">© ChatUnity-Bot X 🤖</h1>
<p align="center"><strong>بوت واتساب متقدم مليء بالميزات والأدوات والترفيه!</strong></p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J">
    <img src="https://img.shields.io/badge/%D8%A7%D9%84%D9%82%D9%86%D8%A7%D8%A9_%D8%A7%D9%84%D8%B1%D8%B3%D9%85%D9%8A%D8%A9-black?style=for-the-badge&logo=whatsapp" alt="القناة الرسمية">
  </a>
</p>

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/README_%D8%A7%D9%84%D8%B1%D8%A6%D9%8A%D8%B3%D9%8A-%D8%A7%D9%84%D8%B9%D9%88%D8%AF%D8%A9_%D8%A5%D9%84%D9%89_%D8%A7%D9%84%D8%AC%D8%B0%D8%B1-6A1B9A?style=for-the-badge" alt="README الرئيسي">
  </a>
</p>

---

## 📌 المقدمة

© ChatUnity-Bot هو بوت واتساب متعدد الوظائف صُمم لتسهيل إدارة الدردشات وتقديم ميزات متقدمة. بفضل واجهته البسيطة وسهولة إعداده، فهو مناسب لكل من يريد تحسين تجربته على واتساب.

---

## 🚀 التثبيت على Termux

### 1. التثبيت على Termux بدون ZIP (موصى به)

[![شرح التثبيت](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. حمّل [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
2. الصق جميع الأوامر التالية دفعة واحدة وبالترتيب نفسه

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

### 2. التثبيت على Termux باستخدام ZIP (للمطورين)

[![شرح التثبيت](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. حمّل ملف ZIP الخاص بالبوت من GitHub
2. حمّل [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
3. الصق جميع الأوامر التالية داخل Termux

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

### 3. التثبيت على Termux باستخدام fork الخاص بك

[![شرح التثبيت](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

استخدم هذه الطريقة إذا كان لديك fork خاص بك وتريد التثبيت مباشرة من مستودعك.

1. أنشئ fork خاصًا بك للمشروع على GitHub
2. استبدل `YOUR-USERNAME` في الأمر التالي باسم مستخدم GitHub الخاص بك
3. الصق جميع الأوامر التالية دفعة واحدة داخل Termux

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

إذا كان fork الخاص بك يستخدم اسم مستودع مختلفًا، فاستبدل `chatunity-bot` في أمري `git clone` و `cd`.

---

## 🕒 تشغيل 24/7 باستخدام PM2 (Termux)

<details>
<summary><b>اضغط هنا لعرض الخطوات</b></summary>

```bash
npm i -g pm2
pm2 start index.js
pm2 save
pm2 logs
```

</details>

---

## 🌐 التثبيت على Windows/VPS/RDP

<details>
<summary><b>اضغط هنا لعرض الخطوات</b></summary>

1. قم بالتنزيل:
   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en/download)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [ImageMagick](https://imagemagick.org/script/download.php)

2. انسخ المشروع وثبّت المتطلبات:
   ```bash
   git clone https://github.com/chatunitycenter/chatunity-bot
   cd chatunity-bot
   npm install
   npm update
   npm start
   ```

</details>

---

## 📂 روابط مفيدة

- **لوحة GitHub**: [اضغط هنا](https://github.com/chatunity-bot)
- **قناة واتساب**: [انضم هنا](https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J)
- **التواصل**: [راسل هنا](https://wa.me/393773842461)
- **التعاون**: [شارك من هنا](https://whatsapp.com/channel/0029Vb1C4od5vKA35u1Mqc06)

---

## VPS ChatUnity

هل تحتاج إلى حل جاهز لإبقاء البوت متصلاً 24/7 بدون إعداد كل شيء يدويًا؟

تم تصميم خوادم ChatUnity VPS لاستضافة البوت بشكل مستقر ومستمر.

- إعداد بسيط
- استقرار أفضل للاستخدام المستمر
- مناسب للبوتات التي تعمل دائمًا

للمعلومات والتوفر تواصل مع [393773842461](https://wa.me/393773842461).

## 📜 الترخيص

© ChatUnity-Bot. جميع الحقوق محفوظة. راجع الترخيص لمزيد من التفاصيل.

<p align="center"><strong>🌟 ادعم المشروع بوضع نجمة على GitHub! 🌟</strong></p>