<p align="center">
<img src="https://i.ibb.co/mCwWq30J/chatunity-bot.jpg" 
</p>

<h1 align="center">© ChatUnity-Bot X 🤖</h1>
<p align="center"><strong>एक उन्नत WhatsApp बॉट, जिसमें फीचर्स, ऑटोमेशन और मनोरंजन सब कुछ है!</strong></p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J">
    <img src="https://img.shields.io/badge/%E0%A4%86%E0%A4%A7%E0%A4%BF%E0%A4%95%E0%A4%BE%E0%A4%B0%E0%A4%BF%E0%A4%95_%E0%A4%9A%E0%A5%88%E0%A4%A8%E0%A4%B2-black?style=for-the-badge&logo=whatsapp" alt="आधिकारिक चैनल">
  </a>
</p>

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/Main_README-%E0%A4%B0%E0%A5%82%E0%A4%9F_%E0%A4%AA%E0%A4%B0_%E0%A4%B5%E0%A4%BE%E0%A4%AA%E0%A4%B8-E65100?style=for-the-badge" alt="मुख्य README">
  </a>
</p>

---

## 📌 परिचय

© ChatUnity-Bot एक मल्टीफंक्शनल WhatsApp बॉट है, जिसे चैट मैनेजमेंट को आसान बनाने और उन्नत सुविधाएँ देने के लिए बनाया गया है। आसान सेटअप और सहज इंटरफ़ेस के कारण यह उन सभी के लिए उपयुक्त है जो WhatsApp अनुभव को बेहतर बनाना चाहते हैं।

---

## 🚀 Termux इंस्टॉलेशन

### 1. बिना ZIP के Termux इंस्टॉलेशन (सुझावित)

[![इंस्टॉलेशन ट्यूटोरियल](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/) डाउनलोड करें
2. नीचे दिए गए सभी कमांड एक साथ और सही क्रम में पेस्ट करें

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

### 2. ZIP के साथ Termux इंस्टॉलेशन (developers के लिए)

[![इंस्टॉलेशन ट्यूटोरियल](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. GitHub से बॉट की ZIP डाउनलोड करें
2. [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/) डाउनलोड करें
3. नीचे दिए गए सभी कमांड Termux में पेस्ट करें

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

### 3. अपने fork के साथ Termux इंस्टॉलेशन

[![इंस्टॉलेशन ट्यूटोरियल](https://img.shields.io/badge/Tutorial-Installation-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

अगर आपका अपना fork है और आप सीधे अपनी repository से इंस्टॉल करना चाहते हैं, तो यह तरीका इस्तेमाल करें।

1. GitHub पर प्रोजेक्ट का अपना fork बनाएं
2. नीचे दिए गए कमांड में `YOUR-USERNAME` को अपने GitHub username से बदलें
3. नीचे दिए गए सभी कमांड एक साथ Termux में पेस्ट करें

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

अगर आपके fork का repository name अलग है, तो `git clone` और `cd` दोनों कमांड में `chatunity-bot` को सही नाम से बदलें।

---

## 🕒 PM2 के साथ 24/7 ऑनलाइन रखें (Termux)

<details>
<summary><b>स्टेप्स देखने के लिए यहाँ क्लिक करें</b></summary>

```bash
npm i -g pm2
pm2 start index.js
pm2 save
pm2 logs
```

</details>

---

## 🌐 Windows/VPS/RDP पर इंस्टॉलेशन

<details>
<summary><b>स्टेप्स देखने के लिए यहाँ क्लिक करें</b></summary>

1. डाउनलोड करें:
   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en/download)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [ImageMagick](https://imagemagick.org/script/download.php)

2. क्लोन करें और इंस्टॉल करें:
   ```bash
   git clone https://github.com/chatunitycenter/chatunity-bot
   cd chatunity-bot
   npm install
   npm update
   npm start
   ```

</details>

---

## 📂 उपयोगी संसाधन

- **GitHub डैशबोर्ड**: [यहाँ जाएँ](https://github.com/chatunity-bot)
- **WhatsApp चैनल**: [यहाँ जुड़ें](https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J)
- **संपर्क**: [यहाँ लिखें](https://wa.me/393773842461)
- **सहयोग**: [यहाँ शामिल हों](https://whatsapp.com/channel/0029Vb1C4od5vKA35u1Mqc06)

---

## ChatUnity VPS

क्या आपको ऐसी तैयार सेवा चाहिए जिससे बॉट 24/7 ऑनलाइन रहे और सब कुछ हाथ से कॉन्फ़िगर न करना पड़े?

ChatUnity VPS को बॉट को स्थिर और लगातार होस्ट करने के लिए बनाया गया है।

- आसान कॉन्फ़िगरेशन
- लगातार उपयोग के लिए अधिक स्थिरता
- हमेशा ऑनलाइन रहने वाले बॉट्स के लिए आदर्श

जानकारी और उपलब्धता के लिए [393773842461](https://wa.me/393773842461) पर संपर्क करें।

## 📜 लाइसेंस

© ChatUnity-Bot. सभी अधिकार सुरक्षित। अधिक जानकारी के लिए लाइसेंस देखें।

<p align="center"><strong>🌟 प्रोजेक्ट को GitHub स्टार देकर सपोर्ट करें! 🌟</strong></p>