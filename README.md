<p align="center">
  <img src="./assets/banner.png" alt="Freedom Project" width="100%">
</p>

<h1 align="center">🚀 Freedom Project</h1>

<p align="center">

The Ultimate Serverless Ecosystem for Subscription Aggregation, Cloudflare Automation, News Collection and Multi-Platform Distribution.

</p>

<p align="center">

Merge • Publish • Archive • Automate

</p>

<p align="center">

<img src="https://img.shields.io/github/license/amyrmhdyfrhzady/Freedom-Project?style=for-the-badge">

<img src="https://img.shields.io/badge/Cloudflare-Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white">

<img src="https://img.shields.io/badge/GitHub-Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">

<img src="https://img.shields.io/badge/Telegram-Bot_API-26A5E4?style=for-the-badge&logo=telegram&logoColor=white">

<img src="https://img.shields.io/badge/Bale-Bot_API-00AEEF?style=for-the-badge">

<img src="https://img.shields.io/badge/Node.js-20+-339933?style=for-the-badge&logo=node.js&logoColor=white">

<img src="https://img.shields.io/badge/Playwright-Chromium-2EAD33?style=for-the-badge&logo=playwright&logoColor=white">

</p>

---

# 🌍 About

Freedom Project is a complete automation ecosystem built to simplify the process of collecting, generating and distributing Subscription files while also archiving important news automatically.

Instead of being just another Subscription repository, Freedom Project combines multiple independent automation systems into one unified platform.

Everything runs automatically.

No VPS.

No dedicated server.

No manual work.

---

# 🚀 Core Components

## 📦 Subscription Aggregator

Freedom Project continuously collects Subscription sources and merges them into one clean Subscription.

Supported formats include:

- V2Ray
- Clash
- Sing-box
- Base64 Subscription

---

## ☁ Cloudflare Workers

Dedicated Workers automatically download the latest generated Subscription and distribute it across multiple platforms.

Current Workers:

- Telegram Publisher
- Bale Publisher

Workers run completely serverless.

---

## 📡 Automatic Distribution

Whenever GitHub generates a new Subscription...

Cloudflare Workers automatically download it and publish it.

Platforms:

- Telegram
- Bale

Users always receive the newest Subscription.

---

## 📰 Telegram News System

Freedom Project also includes a dedicated News Collection project.

It monitors selected Telegram news channels, captures webpages using Chromium and Playwright and generates offline MHTML archives.

This project is maintained separately.

Repository:

https://github.com/amyrmhdyfrhzady/telegram-news-mhtml

---

# 🔥 Features

- Merge multiple Subscription sources
- Automatic Subscription generation
- Cloudflare Workers
- Telegram Publisher
- Bale Publisher
- GitHub Actions Automation
- Telegram News Collector
- Website Archiver
- MHTML Generator
- Serverless Infrastructure
- No VPS Required
- Fully Automated
- Easy to Extend
- Open Source

---

<p align="center">

<img src="./assets/architecture.png" width="100%">

</p>

---

# 🏗 Architecture

```text
                 Subscription Sources
                         │
                         ▼
                Merge Configurations
                         │
                         ▼
               Unified Subscription
                         │
          ┌──────────────┴──────────────┐
          ▼                             ▼
 Cloudflare Telegram Worker      Cloudflare Bale Worker
          │                             │
          ▼                             ▼
   Telegram Channel              Bale Channel


──────────────────────────────────────────────────────────


 Selected Telegram News Channels
                │
                ▼
         GitHub Actions
                │
                ▼
      Chromium + Playwright
                │
                ▼
        Generate MHTML
                │
                ▼
         Publish to Bale
```

---

# 📸 Preview

<p align="center">
<img src="./assets/preview.png" width="100%">
</p>

---
# ⚙️ Automation Workflow

```text
                      GitHub Actions
                             │
                             ▼
                 Download Subscription Sources
                             │
                             ▼
                    Merge Configurations
                             │
                             ▼
                 Generate Final Subscription
                             │
            ┌────────────────┴────────────────┐
            ▼                                 ▼
 Cloudflare Telegram Worker         Cloudflare Bale Worker
            │                                 │
            ▼                                 ▼
     Telegram Channel                 Bale Channel


────────────────────────────────────────────────────────────


 Selected Telegram Channels
            │
            ▼
      Telegram News Project
            │
            ▼
 Chromium + Playwright
            │
            ▼
      Capture Webpage
            │
            ▼
      Generate MHTML
            │
            ▼
        Send to Bale
```

---

# 📂 Project Structure

```text
.
├── .github
│   └── workflows
│
├── workers
│   ├── telegram-worker.js
│   └── bale-worker.js
│
├── src
│   ├── merge.js
│   ├── parser.js
│   ├── config.js
│   └── utils.js
│
├── subscriptions
│
├── assets
│   ├── banner.png
│   ├── architecture.png
│   ├── workflow.png
│   ├── preview.png
│   └── logo.png
│
├── README.md
└── package.json
```

---

# ⚡ Technologies

Freedom Project is powered by modern cloud technologies.

| Technology | Purpose |
|------------|---------|
| GitHub Actions | Automation |
| Cloudflare Workers | Distribution |
| GitHub Raw | File Hosting |
| Node.js | Runtime |
| Playwright | Browser Automation |
| Chromium | Website Capture |
| Telegram Bot API | Telegram Distribution |
| Bale Bot API | Bale Distribution |

---

# 📡 Official Channels

## Telegram

Latest Subscription Files

https://t.me/+R3IrPpe8sVY1OTg0

---

## Bale

Latest Subscription Files

https://ble.ir/join/AR6YgWwcpU

---

# 📚 Related Projects

## 📰 Telegram News MHTML

Freedom Project also includes an independent project dedicated to automatically archiving Telegram news websites into offline MHTML files.

Repository

https://github.com/amyrmhdyfrhzady/telegram-news-mhtml

Features

- Chromium
- Playwright
- GitHub Actions
- Automatic MHTML Generation
- Automatic Bale Publishing

---

# 🌟 Why Freedom Project?

Unlike ordinary Subscription repositories...

Freedom Project is an ecosystem.

It automatically

- Collects
- Merges
- Generates
- Downloads
- Publishes
- Archives
- Synchronizes

Everything works together.

---

# 📊 Project Highlights

| Feature | Status |
|----------|--------|
| Subscription Merge | ✅ |
| Cloudflare Workers | ✅ |
| Telegram Distribution | ✅ |
| Bale Distribution | ✅ |
| GitHub Actions | ✅ |
| News Collection | ✅ |
| MHTML Archive | ✅ |
| Serverless | ✅ |
| No VPS | ✅ |
| Automatic Updates | ✅ |
| Open Source | ✅ |

---

<p align="center">

<img src="./assets/workflow.png" width="100%">

</p>

---
# 🗺 Roadmap

The Freedom Project is actively evolving. Planned improvements include:

- [x] Subscription Aggregator
- [x] GitHub Actions Automation
- [x] Cloudflare Workers
- [x] Telegram Publisher
- [x] Bale Publisher
- [x] Telegram News Collector
- [x] Website MHTML Archiver
- [ ] Multi-language Support
- [ ] Web Dashboard
- [ ] Public REST API
- [ ] Subscription Statistics
- [ ] Web Interface
- [ ] Health Monitoring
- [ ] Automatic Source Validation
- [ ] Duplicate Detection Improvements
- [ ] Performance Optimizations

---

# 📈 Project Goals

Freedom Project aims to provide a completely automated and serverless platform for:

- Subscription aggregation
- Configuration distribution
- Website archiving
- News collection
- Multi-platform publishing

The long-term goal is to build a reliable ecosystem that requires minimal maintenance while remaining easy to extend.

---

# 🤝 Contributing

Contributions are always welcome.

If you would like to improve this project:

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

Bug reports, feature requests and suggestions are greatly appreciated.

---

# ❤️ Support

If you find this project useful, please consider:

- ⭐ Starring the repository
- 🍴 Forking the project
- 🛠 Contributing improvements
- 📢 Sharing it with others

Every contribution helps the project grow.

---

# 📜 License

This project is released under the **MIT License**.

See the `LICENSE` file for more information.

---

# 👨‍💻 Author

Developed and maintained by **amyrmhdyfrhzady**.

GitHub:

https://github.com/amyrmhdyfrhzady

---

# 🙏 Acknowledgements

Special thanks to the developers and communities behind:

- Cloudflare Workers
- GitHub Actions
- Node.js
- Playwright
- Chromium
- Telegram Bot API
- Bale Bot API

Their tools make this project possible.

---

# 🌐 Ecosystem

Freedom Project consists of multiple components working together:

```text
                Freedom Project
                       │
     ┌─────────────────┼─────────────────┐
     │                 │                 │
     ▼                 ▼                 ▼
Subscription      Cloudflare       News Collector
 Aggregator         Workers          (MHTML)

     │                 │                 │
     ▼                 ▼                 ▼
 Telegram          Telegram         GitHub Actions
 Bale              Bale             Playwright

```

---

# 📌 Repository Overview

| Component | Description |
|-----------|-------------|
| Subscription Aggregator | Merge multiple subscription sources |
| Cloudflare Workers | Automatic Telegram & Bale publishing |
| GitHub Actions | Automated workflows |
| Telegram News MHTML | Website archiving project |
| Serverless Infrastructure | No VPS required |

---

<p align="center">

<img src="./assets/logo.png" width="120">

</p>

<h2 align="center">

Freedom Project

</h2>

<p align="center">

A modern serverless ecosystem for Subscription aggregation, automated publishing and news archiving.

</p>

<p align="center">

Made with ❤️ using

GitHub Actions • Cloudflare Workers • Node.js • Playwright • Telegram Bot API • Bale Bot API

</p>
