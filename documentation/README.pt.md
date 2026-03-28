<p align="center">
<img src="https://i.ibb.co/mCwWq30J/chatunity-bot.jpg" 
</p>

<h1 align="center">© ChatUnity-Bot X 🤖</h1>
<p align="center"><strong>Um bot avançado para WhatsApp, cheio de recursos e diversão!</strong></p>

<p align="center">
  <a href="https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J">
    <img src="https://img.shields.io/badge/Canal_Oficial-black?style=for-the-badge&logo=whatsapp" alt="Canal Oficial">
  </a>
</p>

<p align="center">
  <a href="../README.md">
    <img src="https://img.shields.io/badge/README%20Principal-Voltar%20%C3%A0%20raiz-228B22?style=for-the-badge" alt="README principal">
  </a>
</p>

---

## 📌 Introdução

© ChatUnity-Bot é um bot multifuncional para WhatsApp, projetado para simplificar o gerenciamento de chats e oferecer recursos avançados. Com uma interface intuitiva e configuração simples, ele é perfeito para quem deseja melhorar a experiência no WhatsApp.

---

## 🚀 Instalação no Termux

### 1. Instalação no Termux sem ZIP (recomendada)

[![Tutorial de Instalação](https://img.shields.io/badge/Tutorial-Instala%C3%A7%C3%A3o-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Baixe [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
2. Cole todos os comandos abaixo de uma vez só e na ordem correta

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

### 2. Instalação no Termux com ZIP (para developers)

[![Tutorial de Instalação](https://img.shields.io/badge/Tutorial-Instala%C3%A7%C3%A3o-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

1. Baixe o ZIP do bot no GitHub
2. Baixe [Termux](https://www.mediafire.com/file/0npdmv51pnttps0/com.termux_0.119.1-119_minAPI21(arm64-v8a,armeabi-v7a,x86,x86_64)(nodpi)_apkmirror.com.apk/)
3. Cole todos os comandos abaixo no Termux

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

### 3. Instalação no Termux com seu fork

[![Tutorial de Instalação](https://img.shields.io/badge/Tutorial-Instala%C3%A7%C3%A3o-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/qek7wWadhtI?feature=share)

Use este método se você tiver seu próprio fork e quiser instalar diretamente do seu repositório.

1. Crie seu fork do projeto no GitHub
2. Substitua `YOUR-USERNAME` no comando abaixo pelo seu nome de usuário do GitHub
3. Cole todos os comandos abaixo de uma vez só dentro do Termux

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

Se o seu fork usar um nome de repositório diferente, substitua `chatunity-bot` tanto no comando `git clone` quanto no comando `cd`.

---

## 🕒 Ativo 24/7 com PM2 (Termux)

<details>
<summary><b>Clique aqui para ver os passos</b></summary>

```bash
npm i -g pm2
pm2 start index.js
pm2 save
pm2 logs
```

</details>

---

## 🌐 Instalação em Windows/VPS/RDP

<details>
<summary><b>Clique aqui para ver os passos</b></summary>

1. Baixe:
   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en/download)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [ImageMagick](https://imagemagick.org/script/download.php)

2. Clone e instale:
   ```bash
   git clone https://github.com/chatunitycenter/chatunity-bot
   cd chatunity-bot
   npm install
   npm update
   npm start
   ```

</details>

---

## 📂 Recursos úteis

- **Painel GitHub**: [Visite aqui](https://github.com/chatunity-bot)
- **Canal WhatsApp**: [Entre aqui](https://whatsapp.com/channel/0029VaZVlJZHwXb8naJBQN0J)
- **Contato**: [Escreva aqui](https://wa.me/393773842461)
- **Colaborações**: [Participe aqui](https://whatsapp.com/channel/0029Vb1C4od5vKA35u1Mqc06)

---

## VPS ChatUnity

Precisa de uma solução pronta para manter o bot online 24/7 sem configurar tudo manualmente?

As VPS ChatUnity foram pensadas para hospedar o bot de forma estável e contínua.

- Configuração simples
- Maior estabilidade para uso contínuo
- Ideal para bots sempre ativos

Para informações e disponibilidade, entre em contato com [393773842461](https://wa.me/393773842461).

## 📜 Licença

© ChatUnity-Bot. Todos os direitos reservados. Consulte a licença para mais detalhes.

<p align="center"><strong>🌟 Apoie o projeto com uma estrela no GitHub! 🌟</strong></p>