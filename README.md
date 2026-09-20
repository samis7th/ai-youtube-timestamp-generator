# AI YouTube Timestamp Generator 🚀

Projeto de estudo e experimentação com IA: um app web que gera automaticamente timestamps (capítulos) para vídeos do YouTube usando um modelo de IA para analisar o conteúdo do vídeo.

Este repositório foi usado como prática para explorar a integração entre frontend (React), backend/serverless (Firebase Functions) e uma API de IA de terceiros para processamento de vídeo.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🎯 Objetivo do projeto

- Testar na prática o fluxo de uma aplicação full-stack com IA integrada.
- Entender como consumir uma API de IA (Bumpups) para gerar timestamps a partir de um vídeo.
- Praticar autenticação, banco de dados e functions serverless com Firebase.
- Servir como peça de portfólio demonstrando integração de IA em produtos web.

## 🛠️ Tech Stack

- ☁️ **Firebase** — backend, autenticação e banco de dados.
- 💬 **Bumpups** — API de IA usada para analisar o vídeo e gerar os timestamps.
- ⚛️ **React** — frontend da aplicação.
- 🐱 **GitHub** — versionamento e hospedagem do código.

## 🔑 Variáveis de ambiente

É necessário fornecer suas próprias chaves de API. Crie um arquivo `.env` na raiz do projeto com:

```env
# Firebase
REACT_APP_API_KEY=sua_firebase_api_key
REACT_APP_AUTH_DOMAIN=seu_auth_domain
REACT_APP_PROJECT_ID=seu_project_id
REACT_APP_STORAGE_BUCKET=seu_storage_bucket
REACT_APP_MESSAGING_SENDER_ID=seu_messaging_sender_id
REACT_APP_APP_ID=seu_firebase_app_id
REACT_APP_MEASUREMENT_ID=seu_measurement_id

# YouTube Data API
REACT_APP_YOUTUBE_API_KEY=sua_youtube_api_key

# reCAPTCHA
REACT_APP_RECAPTCHA_SITE_KEY=sua_recaptcha_site_key

# Bumpups API
BUMPUPS_API_KEY=sua_bumpups_api_key
```

Nunca faça commit do seu `.env` — ele já está incluído no `.gitignore`.

## ▶️ Como rodar localmente

```bash
npm install
npm start
```

---

*Projeto usado para fins de estudo e teste de tecnologias de IA aplicadas a produtos web. Não possui vínculo comercial.*
