# 📦 WhatsApp Backend para Render.com

Este projeto é um backend em Node.js com `whatsapp-web.js`, pronto para rodar no [Render.com](https://render.com/).

---

## 🚀 Como fazer o deploy

1. Acesse [https://render.com](https://render.com) e crie uma conta ou faça login.

2. Clique em **"New + > Web Service"**

3. Conecte com o repositório do GitHub onde está este projeto

4. Confirme as seguintes configurações:

- **Environment:** Node
- **Build Command:** `npm install`
- **Start Command:** `node index.js`
- **Node Version:** 18
- **Branch:** `main` (ou o nome da sua branch)

5. Após o deploy, acesse a URL pública fornecida pelo Render.

---

## 🌐 Endpoints disponíveis

- `GET /qr` → Retorna QR ou status
- `GET /reset-session` → Reseta a sessão atual
- `POST /send` → Envia mensagens para uma lista

---

## ⚠️ Importante

O Render já possui suporte para `puppeteer` com Chromium headless.  
Você não precisa configurar nada extra. Basta subir este projeto que já vem pronto.

