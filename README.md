# Hi there, I'm Hyun-kyu Lee (이현규) 👋

> **Software Developer** specialized in high-performance server applications, middleware, distributed systems, and cross-platform software.  
> Experienced in **C++23**, **Go**, **Python**, **C#**, and **TypeScript**, building production-oriented software across **Windows**, **Linux**, and macOS environments.

---

## 🛠 Tech Stack

### Operating Systems

[![Windows](https://img.shields.io/badge/-Windows-0078D6?style=flat-square&logo=Windows&logoColor=white)](https://www.microsoft.com/windows)  
[![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)](https://ubuntu.com/)  
[![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)](https://www.apple.com/macos/)

### Languages

[![C++23](https://img.shields.io/badge/C++-23-00599C?style=flat-square&logo=C%2B%2B&logoColor=white)](https://en.cppreference.com/w/cpp)  
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)  
[![Go](https://img.shields.io/badge/GoLang-00ADD8?style=flat-square&logo=go&logoColor=white)](https://go.dev/)  
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)  
[![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)](https://learn.microsoft.com/en-us/dotnet/csharp/)

### Frameworks / Libraries

[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)](https://nextjs.org/)  
[![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://react.dev/)  
[![Boost](https://img.shields.io/badge/Boost.Asio-%230078D7.svg?style=flat-square&logoColor=white)](https://www.boost.org/doc/libs/release/doc/html/boost_asio.html)  
[![Qt](https://img.shields.io/badge/Qt-41CD52?style=flat-square&logo=Qt&logoColor=white)](https://www.qt.io/)  
[![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)  
[![WPF](https://img.shields.io/badge/WPF-5C2D91?style=flat-square&logo=.net&logoColor=white)](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/)  
[![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)](https://www.rabbitmq.com/)  
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)](https://redis.io/)  
[![Kafka](https://img.shields.io/badge/Kafka-000000?style=flat-square&logo=apache-kafka&logoColor=white)](https://kafka.apache.org/)  
[![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)  
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)](https://opencv.org/)

### Database / Infra / Tools

[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)  
[![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)](https://www.prisma.io/)  
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)  
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)  
[![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)](https://cmake.org/)  
[![vcpkg](https://img.shields.io/badge/vcpkg-0099FF?style=flat-square&logo=visual-studio&logoColor=white)](https://github.com/microsoft/vcpkg)  
[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)  
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)](https://github.com/features/actions)  
[![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)](https://playwright.dev/)

---

## ⚙️ Development Environment

- **OS**: Windows, Ubuntu, macOS
- **Backend / Systems**: C++23, Boost.Asio, Go, Python, C#/.NET
- **Web**: Next.js, React, TypeScript
- **Database / Messaging**: PostgreSQL, Redis, RabbitMQ, Kafka
- **Build & Package**: CMake, vcpkg, Makefile, MSBuild, npm
- **IDE**: Visual Studio, VS Code, Qt Creator
- **SCM**: Git (GitHub), SVN
- **CI/CD**: GitHub Actions, Jenkins
- **Container / Cloud**: Docker, AWS

---

## 🔭 Featured Projects

### 1. **yirang-onnx**
- C++23-based CLI inference engine and ONNX model parser
- Parses ONNX models and performs inference using ONNX Runtime
- Supports Protocol Buffer-based tensor input processing

### 2. **yirang-message-queue**
- Lightweight message queue designed for legacy and resource-constrained embedded systems
- Supports file-based mailbox IPC, SQLite-backed queues, and filesystem-based storage
- Enables reliable communication between legacy modules and modern components without requiring a network stack

### 3. **yirang-taskforge**
- Distributed task execution service based on queue-driven job processing
- Executes whitelisted applications on distributed C++23 workers
- Tracks task execution, status, and completion across workers

### 4. **yirang-jobfit-nextjs**
- Full-stack job application management platform built with **Next.js, TypeScript, PostgreSQL, and Prisma**
- Analyzes job descriptions against candidate profiles and technical skills using AI-assisted matching
- Manages job postings, application workflows, interview stages, and career analytics
- Includes production-oriented architecture, validation, authentication, and E2E testing with Playwright

### 5. **RealTimeMessageChat**
- **Boost.Asio**-based TCP/IP server for real-time message broadcasting
- Uses **Redis** for low-latency state access and **RabbitMQ (AMQP)** for asynchronous messaging
- Broadcasts messages across multiple connected client sessions

### 6. **Various Samples / Study Repositories**
- Unreal Engine integration, C++ Kafka examples, .NET toolkit demos, and other technical experiments
- Check [Pinned Repositories](https://github.com/ngee044?tab=repositories) for more details

---

## 🌱 About Me

- Previously worked at **PozaLabs**, developing **audio rendering modules** and **high-performance multi-process server systems**
- Experienced across the full software development lifecycle, including **domain analysis, architecture design, implementation, testing, and deployment**
- Primarily focused on **C++ server / middleware / distributed systems**, while expanding into **modern full-stack development with Next.js and TypeScript**
- Comfortable working across **embedded, desktop, server, and web application environments**
- Interested in designing pragmatic software architectures that balance performance, maintainability, and operational complexity
- Continuously exploring new technologies through production-oriented personal projects

### Contact

- **GitHub**: [ngee044](https://github.com/ngee044)
- **Notion**: [Portfolio & Projects (Korean)](https://elemental-treatment-3fc.notion.site/e4cc2b3172cf4b368baf80fead9c1b7e?pvs=4)
- **Email**: [mgee044@naver.com](mailto:mgee044@naver.com)

---

### 🙌 Thanks for visiting!

> “Building reliable software, continuously learning, and turning complex requirements into practical systems.”
