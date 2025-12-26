# KARTYOM3248 — Node.js project skeleton

This repository now contains a minimal **Node.js** project skeleton to get started quickly.

## 🔧 Что в проекте
- **package.json** — basic scripts (`start`, `dev`, `test`)
- **src/index.js** — минимальный HTTP-сервер
- **.gitignore** — стандартные правила для Node.js

## 🚀 Быстрый старт
```bash
# установить зависимости (если добавите пакеты в package.json)
npm install

# запустить приложение
npm start

# запустить в режиме разработки
npm run dev
```

Приложение слушает порт `3000` по умолчанию (или `process.env.PORT`).

---

<!-- Сохранённый оригинал README ниже -->

## Hi there 👋

<!--
**KARTYOM3248/KARTYOM3248** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
## 🚀 Projects

I'm working on **COCOON Worker** - a distributed AI model serving platform on TON blockchain.

### COCOON Worker

Run a COCOON worker to earn TON by serving AI models securely with Intel TDX and NVIDIA H100+ GPU confidential computing.

**Key Features:**
- Secure TEE-based AI model inference
- TON blockchain integration for payments
- Multi-GPU support
- Real-time monitoring and health checks

**Quick Start:**
```bash
wget https://ci.cocoon.org/cocoon-worker-release-latest.tar.xz
tar xvf cocoon-worker-release-latest.tar.xz
cp worker.conf.example worker.conf
./scripts/cocoon-launch worker.conf
```

**Requirements:**
- Linux 6.16+ with Intel TDX CPU and NVIDIA H100+ GPU
- SGX enclave support for key derivation
- Hugging Face token for model access

**Learn more:** See the full [COCOON Worker documentation](https://cocoon.org/docs/worker) for setup, configuration, and monitoring.
package.json\рабочие области\KARTYOM3248
12
