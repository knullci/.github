<div align="center">
  
# 🌑 KnullCI

### **The Open Source CI/CD Ecosystem**

*Fast. Lightweight. Developer-First.*

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Open Source](https://img.shields.io/badge/Open%20Source-❤️-red.svg)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]()

</div>

---

## 👋 Welcome

**KnullCI** is a community-driven, open source CI/CD platform built for teams who value **transparency**, **performance**, and **simplicity**. We're on a mission to democratize continuous integration and deployment—making it accessible to everyone, from solo developers to enterprise teams.

> *"Why depend on black-box SaaS when you can run your own blazing-fast CI/CD?"*

---

## 🚀 Our Projects

| Repository | Description | Tech |
|------------|-------------|------|
| [**knull-ci-cd**](https://github.com/knullci/knull-ci-cd) | The core CI/CD platform — dashboard, pipelines, GitHub webhooks, real-time logs | Java 21, Spring Boot 4, gRPC |
| [**necrosword**](https://github.com/knullci/necrosword) | Ultra-fast process executor with streaming output | Go 1.22, gRPC |

---

## ✨ Why KnullCI?

### 🛡️ Truly Open Source
- MIT Licensed — forever free
- No telemetry, no tracking
- Self-host anywhere

### ⚡ Built for Speed
- GraalVM native compilation
- Sub-second startup times
- Go-powered executor

### 🔒 Secure by Default
- AES-256 encrypted credentials
- Sandboxed command execution
- No external dependencies

### 🧩 Developer Experience
- Pipeline as code (`.knull.yml`)
- Real-time streaming logs
- Beautiful, intuitive UI

---

## 🏗️ Architecture

```
   ┌─────────────────┐         gRPC          ┌──────────────┐
   │   KnullCI       │◄────────────────────► │  Necrosword  │
   │   (Java/Spring) │    Stream Execution   │     (Go)     │
   │                 │                       │              │
   │  • Dashboard    │                       │ • Fast Exec  │
   │  • Pipelines    │                       │ • Streaming  │
   │  • Webhooks     │                       │ • Sandboxing │
   └─────────────────┘                       └──────────────┘
           │                                        
           ▼                                        
   ┌─────────────────┐                              
   │   GitHub/Git    │                              
   └─────────────────┘                              
```

---

## 🌍 Get Started

```bash
# Clone the main platform
git clone https://github.com/knullci/knull-ci-cd.git
cd knull-ci-cd

# Run with Maven
mvn spring-boot:run

# Access at http://localhost:8080
# Default login: knull / knull
```

📖 **[Full Documentation](https://github.com/knullci/knull-ci-cd#readme)** | 🗡️ **[Necrosword Docs](https://github.com/knullci/necrosword#readme)**

---

## 🤝 Contributing

We ❤️ contributions! KnullCI thrives because of our community.

- 🐛 **Report bugs** — Open an issue in the relevant repository
- 💡 **Suggest features** — Share your ideas via GitHub Discussions  
- 🔧 **Submit PRs** — Bug fixes, features, documentation improvements
- ⭐ **Star us** — It helps a lot!

Look for issues tagged with `good first issue` to get started!

---

## 📜 License

All projects are released under the **MIT License** — free to use, modify, and distribute.

---

<div align="center">

**Built with ❤️ for developers, by developers**

</div>
