# 🧪 Testes de API - Reqres

Este projeto consiste em uma simulação de testes de API REST utilizando a [API pública Reqres](https://reqres.in/), voltado para fins educacionais e prática de validações básicas com Postman e Newman.

## ✅ Funcionalidades Testadas

Foram realizadas simulações simples para os seguintes endpoints da API:

- 🔐 Validação de **login** (`POST /login`)
- 📝 Simulação de **registro** (`POST /register`)
- 👤 Listagem de **usuários** (`GET /users`)
- 🔎 Consulta de **usuário único** (`GET /users/8`)
- ➕ **Criação de usuário** (`POST /users`)   
- ✏️ **Atualização de usuário** (`PUT /users/8`) 
- ❌ **Remoção de usuário** (`DELETE /users/8`) 

## ⚠️ Limitações da API

A API Reqres é apenas uma simulação (mock), por isso:

- Os dados **não são persistidos** após as requisições.
- Não é possível validar alterações reais, como checar se o usuário criado pode ser buscado depois.
- Respostas são **pré-definidas** (hardcoded), o que limita a profundidade dos testes.

## 🛠 Ferramentas Utilizadas

- [Postman](https://www.postman.com/)
- [Newman](https://www.npmjs.com/package/newman)
- [newman-reporter-htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra)
