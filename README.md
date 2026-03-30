# Dev Tool

Aplicacao web para visualizar, validar e converter JSON/XML, publicada via Firebase Hosting.

## Requisitos

- Node.js 18+
- Conta Firebase autenticada

## Rodar localmente

1. Instale dependencias:

npm install

2. Inicie o emulador do Firebase Hosting:

npm run serve

## Deploy

1. Faça login no Firebase:

npx firebase login

2. Publique no Hosting:

npm run deploy

## Estrutura

- index.html: aplicacao frontend (SPA)
- firebase.json: configuracao de Hosting
- .firebaserc: projeto Firebase padrao
