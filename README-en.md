# yudao-cloud - Modern Microservice Architecture Platform

<p align="center">
  <img src="https://img.shields.io/badge/Spring%20Cloud-2021-blue.svg" alt="Spring Cloud 2021">
  <img src="https://img.shields.io/badge/Spring%20Boot-2.7.18-blue.svg" alt="Spring Boot 2.7.18">
  <img src="https://img.shields.io/badge/Vue-3.2-blue.svg" alt="Vue 3.2">
  <img src="https://img.shields.io/github/license/YunaiV/yudao-cloud" alt="License MIT">
</p>

> **Solemn Statement: There will never be a commercial version. All code is 100% open source!**
>
> **"I love writing code, never get tired of it"**
>
> **"I love open source, take it as my joy"**

---

## 📚 Table of Contents

- [🏠 Introduction](#-introduction)
- [🗂️ Project Structure](#️-project-structure)
- [🚀 Tech Stack](#-tech-stack)
- [🎯 Features](#-features)
- [🖼️ Screenshots](#️-screenshots)
- [💡 Implementation Details](#-implementation-details)
- [🔐 Security & Authentication](#-security--authentication)
- [🛡️ Permission Control](#️-permission-control)
- [⚡ High Concurrency](#-high-concurrency)
- [🗄️ Database Design](#️-database-design)
- [📱 Mobile Applications](#📱-mobile-applications)
- [💡 Quick Start](#-quick-start)
- [📄 License](#-license)

---

## 🏠 Introduction

**yudao-cloud (Taro Dao)** - Developer-centered, building China's top rapid development platform. All open source, 100% free for individuals and enterprises.

### 🌟 Project Positioning

This is an enterprise-grade microservices architecture system using **Spring Cloud Alibaba 2021 + Vue3 + UniApp** technology stack.

Designed to provide Java developers with **a ready-to-use enterprise solution**, with 100% open source code for free personal and enterprise use.

| Target Audience | Learning Content | Benefits |
|:---|:---|:---|
| **Java Beginners** | Spring Boot basics, Web development, DB operations | Master enterprise project development process |
| **Mid-level Developers** | Spring Cloud, distributed systems, caching, MQ | Become a microservices development engineer |
| **Senior Developers** | Architecture design, high concurrency, performance tuning | Move towards architect career path |
| **Architects** | Reference designs, rapid system building | Improve development efficiency by 80%+ |

### 🌟 Core Features

| Feature | Description |
|:---|:---|
| 🌈 Microservices | Spring Cloud Alibaba architecture, high concurrency & availability |
| 👤 Multi-terminal | Vue3 + element-plus/vben (PC), uni-app (Mobile) |
| 🔐 Security | Spring Security + Token + Redis, SSO support |
| 🏢 SaaS Tenant | Multi-tenant architecture with flexible permissions |
| ⚡ Rapid Dev | Code generator for Java/Vue/SQL |
| 📊 Workflow | Flowable + BPMN + DingTalk-style dual designers |
| 💰 Payment | Alipay & WeChat Pay integration |
| 🤖 AI | AI LLM integration, intelligent Q&A |

### 🌟 Core Technical Capabilities

```
┌────────────────────────────────────────────────────────────────────────┐
│                      Core Technical Capability Matrix                    │
├────────────────┬───────────────────────────────────────────────────────┤
│                │                                                        │
│ Service        │  • Nacos: Service registration & discovery            │
│ Governance     │  • Gateway: Unified gateway, routing, rate limiting   │
│                │  • Sentinel: Flow control, circuit breaker             │
│                │  • LoadBalancer: Client-side load balancing           │
│                │                                                        │
├────────────────┼───────────────────────────────────────────────────────┤
│                │                                                        │
│ Distributed    │  • Seata AT Mode: Auto compensation, non-invasive    │
│ Transaction    │  • Seata TCC Mode: Two-phase commit, strong consist. │
│                │  • Seata Saga Mode: Long transaction orchestration   │
│                │                                                        │
├────────────────┼───────────────────────────────────────────────────────┤
│                │                                                        │
│ Message Queue  │  • RocketMQ: Transactional, ordered, delayed messages │
│                │  • Message reliability: ACK, dead letter queue        │
│                │  • Message idempotency: Prevent duplicate consumption│
│                │                                                        │
├────────────────┼───────────────────────────────────────────────────────┤
│                │                                                        │
│ Caching        │  • Redis Master-Slave: Read-write separation           │
│ Strategy       │  • Redis Cluster: Data sharding, horizontal scaling  │
│                │  • Local Cache: Caffeine, reduce Redis access         │
│                │  • Multi-level Cache: Local + Redis hybrid           │
│                │                                                        │
├────────────────┼───────────────────────────────────────────────────────┤
│                │                                                        │
│ Task          │  • XXL-Job: Distributed task scheduling center         │
│ Scheduling    │  • Task Sharding: Massive data parallel processing     │
│                │  • Retry: Automatic task retry on failure            │
│                │  • Task Dependency: Inter-task dependencies          │
│                │                                                        │
├────────────────┼───────────────────────────────────────────────────────┤
│                │                                                        │
│ Distributed    │  • SkyWalking: Full链路追踪                           │
│ Tracing        │  • Performance monitoring: Interface latency           │
│                │  • Log aggregation: ELK unified logging platform      │
│                │                                                        │
└────────────────┴───────────────────────────────────────────────────────┘
```

### 🌟 Applicable Business Scenarios

yudao-cloud can rapidly build various types of enterprise applications, covering 95% of business scenarios.

| Scenario | Description | Quick Development |
|:---|:---|:---|
| **Internal Management** | Permissions, workflow, reports | OA, archive, attendance, work order systems |
| **SaaS Platform** | Multi-tenant isolation, package management | Enterprise services, industry SaaS |
| **E-commerce** | Product, order, payment | B2C mall, O2O platform |
| **CRM** | Customer, opportunity, contract | Sales management, customer service |
| **ERP** | Purchase, inventory, sales, finance | SME ERP, supply chain |
| **IoT** | Device, data collection, alerts | Smart home, industrial IoT |

### 🌟 Project Highlights

| Highlight | Description | Value |
|:---|:---|:---|
| **High Code Quality** | Alibaba Java coding standards, complete comments | Easy to learn and extend |
| **Complete Features** | 70+ modules, covering 95% scenarios | Out-of-the-box, reduce 80% duplicate work |
| **True Microservices** | Production-grade, not pseudo-distributed | Supports millions of daily active users |
| **High Concurrency** | Cache, rate limiting, distributed lock, async | Single machine QPS 10000+ |
| **Security** | Authentication, authorization, data encryption | Meets Level 3 security certification |
| **Documentation** | Videos, docs, hands-on tutorials | 7x24 tech support |
| **Continuous Updates** | Active maintenance, monthly iteration | Always up-to-date |
| **Active Community** | 10000+ knowledge planet members | Quick answers, easy communication |

### 🌟 Architecture Design Highlights

This project uses a four-tier architecture design with unified authentication, multi-terminal access, and microservices governance.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    Enterprise Architecture Overview                          │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│    ┌─────────────────────────────────────────────────────────────────┐      │
│    │                      Unified Authentication Center                │      │
│    │  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐            │      │
│    │  │   Portal    │  │    APP      │  │   WeChat    │            │      │
│    │  │   (Web)     │  │  (Mobile)   │  │   (MiniApp) │            │      │
│    │  └──────┬──────┘  └──────┬──────┘  └──────┬──────┘            │      │
│    │         │                 │                 │                     │      │
│    │         └─────────────────┼─────────────────┘                     │      │
│    │                           │                                       │      │
│    │                    ┌──────▼──────┐                               │      │
│    │                    │   Gateway   │                               │      │
│    │                    │  / Auth API │                               │      │
│    │                    └──────┬──────┘                               │      │
│    └──────────────────────────┼───────────────────────────────────────┘      │
│                               │                                                │
│         ┌─────────────────────┼─────────────────────┐                         │
│         │                     │                     │                         │
│         ▼                     ▼                     ▼                         │
│  ┌─────────────┐      ┌─────────────┐      ┌─────────────┐                │
│  │   Internal  │      │    External │      │   Mobile    │                │
│  │  Management │      │   Users    │      │     APP     │                │
│  │    (Vue3)   │      │   (Vue3)   │      │  (uni-app)  │                │
│  └─────────────┘      └─────────────┘      └─────────────┘                │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 📊 Business Architecture

![Architecture](./前端/yudao-ui-admin-vue3/.image/common/ruoyi-vue-pro-biz.png)

---

## 🗂️ Project Structure

```
e:/code/yudao-cloud/
│
├── 📂 后端/ (Backend)                   # Java Microservices
│   └── yudao-cloudmaster/
│       ├── yudao-dependencies/           # Maven dependency management
│       ├── yudao-framework/              # Core framework
│       │   ├── yudao-common/            # Common utilities
│       │   ├── yudao-spring-boot-starter-web/        # Web enhancement
│       │   ├── yudao-spring-boot-starter-security/  # Security
│       │   ├── yudao-spring-boot-starter-mybatis/   # MyBatis
│       │   ├── yudao-spring-boot-starter-redis/     # Redis cache
│       │   ├── yudao-spring-boot-starter-mq/        # Message queue
│       │   ├── yudao-spring-boot-starter-job/       # Task scheduling
│       │   └── yudao-spring-boot-starter-rpc/       # RPC calls
│       │
│       ├── yudao-gateway/               # API Gateway
│       ├── yudao-server/                # Service entry point
│       │
│       ├── yudao-module-system/         # 🚀 System module (User/Role/Menu)
│       ├── yudao-module-infra/          # 🚀 Infrastructure (Code gen/File)
│       ├── yudao-module-bpm/             # 🚀 Workflow module (Flowable)
│       ├── yudao-module-pay/            # 🚀 Payment module
│       ├── yudao-module-mall/           # 🚀 Mall module (Product/Order)
│       ├── yudao-module-member/         # 🚀 Member module
│       ├── yudao-module-mp/             # 🚀 WeChat MP module
│       ├── yudao-module-crm/            # 🚀 CRM module
│       ├── yudao-module-erp/            # 🚀 ERP module
│       ├── yudao-module-iot/           # 🚀 IoT module
│       ├── yudao-module-report/         # 🚀 Report module
│       ├── yudao-module-ai/            # 🚀 AI module
│       │
│       └── script/                      # Docker/IDEA scripts
│
├── 📂 前端/ (Frontend)                   # Vue3 Frontend
│   ├── yudao-ui-admin-vue3/             # ⭐ Vue3 + element-plus
│   ├── yudao-ui-admin-vben/             # Vue3 + ant-design-vue
│   ├── yudao-ui-admin-uniapp/           # uni-app Mobile Admin
│   └── yudao-mall-uniapp/               # uni-app Mall
│
└── 📂 数据库/ (Database)                 # SQL Scripts
    └── sql/
        ├── mysql/                       # MySQL
        ├── postgresql/                  # PostgreSQL
        ├── oracle/                      # Oracle
        ├── sqlserver/                   # SQL Server
        ├── dm/                          # DM (DaMeng)
        └── tools/                       # Database tools
```

---

## 🚀 Tech Stack

### Backend Technologies (20+)

| Category | Technology | Version | Description |
|:---|:---|:---:|:---|
| **Framework** | Spring Boot | 2.7.18 | Core framework |
| | Spring Cloud | 2021.0.4.0 | Microservice framework |
| | Spring Cloud Alibaba | 2021.0.4.0 | Alibaba ecosystem |
| **Service Governance** | Nacos | 2.3.2 | Config & Registry center |
| | Spring Cloud Gateway | 3.4.1 | API Gateway, routing |
| | Sentinel | 1.8.6 | Rate limiting, circuit breaker |
| | LoadBalancer | 3.4.1 | Client-side load balancing |
| **Transaction** | Seata | 1.6.1 | Distributed transaction |
| **Cache** | Redis | 5.0+ | Cache, session storage |
| | Redisson | 3.32.0 | Distributed lock |
| **Message Queue** | RocketMQ | 5.2.0 | Transactional message |
| **Database** | MySQL | 8.0+ | Primary database |
| | MyBatis Plus | 3.5.7 | ORM framework |
| **Security** | Spring Security | 5.7.5 | Authentication & Authorization |
| | JWT | 0.9.1 | Token based auth |
| | Sa-Token | 1.37.0 | Simple auth framework |
| **Task Scheduling** | XXL-Job | 2.3.1 | Distributed task scheduling |
| **Workflow** | Flowable | 6.8.0 | BPMN workflow engine |
| **Monitoring** | SkyWalking | 8.12.0 | Distributed tracing |
| | Spring Boot Admin | 2.7.10 | Application monitoring |
| **Build** | Maven | 3.8+ | Build tool |
| | Docker | 20+ | Containerization |

### Frontend Technologies

| Category | Technology | Description |
|:---|:---|:---|
| **PC Backend** | Vue 3.2 | Progressive JS framework |
| | Element Plus | Vue3 UI component library |
| | Ant Design Vue | Enterprise UI library |
| | Pinia | Vue3 state management |
| | Vite | Next-gen build tool |
| **Mobile** | uni-app | Cross-platform (iOS/Android/WeChat) |
| | Vue 3 + Composition API | Modern Vue development |
| | uni-ui | Mobile UI component library |

### Middleware

| Technology | Version | Purpose |
|:---|:---:|:---|
| Nacos | 2.3.2 | Service registry, config center |
| Sentinel | 1.8.6 | Flow control, degradation |
| Seata | 1.6.1 | Distributed transaction |
| RocketMQ | 5.2.0 | Message queue |
| Redis | 5.0+ | Cache, session, lock |
| XXL-Job | 2.3.1 | Task scheduling |
| SkyWalking | 8.12.0 | Tracing, monitoring |
| MySQL | 8.0+ | Database |
| Nginx | 1.20+ | Reverse proxy, load balancer |

---

## 🎯 Features

### 🖥️ System Features

| Feature | Description | Screenshot |
|:---|:---|:---:|
| User Management | System operator configuration | ![](.image/用户管理.jpg) |
| Online Users | Active user monitoring | ![](.image/在线用户.jpg) |
| Role Management | Role menu permission assignment | ![](.image/角色管理.jpg) |
| Menu Management | System menu & button permissions | ![](.image/菜单管理.jpg) |
| Department | Organization structure | ![](.image/部门管理.jpg) |
| Tenant Management | SaaS multi-tenant config | ![](.image/租户管理.jpg) |
| Dict Management | Static data maintenance | ![](.image/字典类型.jpg) |
| SMS Management | Aliyun/Tencent SMS integration | ![](.image/短信渠道.jpg) |
| Operation Logs | System operation logs | ![](.image/操作日志.jpg) |
| Login Logs | Login logs with exceptions | ![](.image/登录日志.jpg) |

### 🔄 Workflow

| Feature | Description |
|:---|:---|
| SIMPLE Designer | DingTalk/Feishu style, drag-drop form builder |
| BPMN Designer | BPMN standard, complex business |
| Countersign | All approvers must approve |
| Or-sign | Any approver can approve |
| CC / Reject / Transfer | Approval flow control |
| Form Permissions | Node-level permission control |

### ⚙️ Infrastructure

| Feature | Description |
|:---|:---|
| Code Generator | Generate Java/Vue/SQL |
| API Docs | Swagger auto-generated docs |
| DB Docs | Auto-generate database docs |
| Job Scheduler | Distributed task scheduling |
| MySQL/Redis Monitor | Connection pool monitoring |
| Java Monitor | Spring Boot Admin |
| Trace | SkyWalking distributed tracing |

### 💰 Payment System

| Feature | Description |
|:---|:---|
| Merchant Info | Merchant configuration |
| App Info | Payment app, multi-channel |
| Payment Orders | Alipay/WeChat Pay |
| Refund Orders | Refund processing |

### 📊 Reports

| Feature | Description |
|:---|:---|
| Report Designer | Data report, chart report, print design |
| Dashboard Designer | Drag-drop data dashboard |

---

## 🖼️ Screenshots

### Login & Dashboard

| Login | Dashboard | Profile |
|:---:|:---:|:---:|
| ![Login](./后端/yudao-cloudmaster/.image/登录.jpg) | ![Dashboard](./后端/yudao-cloudmaster/.image/首页.jpg) | ![Profile](./后端/yudao-cloudmaster/.image/个人中心.jpg) |

### Users & Permissions

| User Management | Token Management | App Management |
|:---:|:---:|:---:|
| ![Users](./后端/yudao-cloudmaster/.image/用户管理.jpg) | ![Tokens](./后端/yudao-cloudmaster/.image/令牌管理.jpg) | ![Apps](./后端/yudao-cloudmaster/.image/应用管理.jpg) |

| Tenant Management | Tenant Package | Department |
|:---:|:---:|:---:|
| ![Tenant](./后端/yudao-cloudmaster/.image/租户管理.jpg) | ![Package](./后端/yudao-cloudmaster/.image/租户套餐.png) | ![Dept](./后端/yudao-cloudmaster/.image/部门管理.jpg) |

### Workflow

| Process Model | Process Design | Task List |
|:---:|:---:|:---:|
| ![Model](./后端/yudao-cloudmaster/.image/流程模型-列表.jpg) | ![Design](./后端/yudao-cloudmaster/.image/流程模型-设计.jpg) | ![Tasks](./后端/yudao-cloudmaster/.image/任务列表-待办.jpg) |

| BPMN Designer | Simple Designer | Leave Request |
|:---:|:---:|:---:|
| ![BPMN](./后端/yudao-cloudmaster/.image/工作流设计器-bpmn.jpg) | ![Simple](./后端/yudao-cloudmaster/.image/工作流设计器-simple.jpg) | ![Leave](./后端/yudao-cloudmaster/.image/OA请假-发起.jpg) |

### Infrastructure

| Code Generator | Generated Code | API Docs |
|:---:|:---:|:---:|
| ![Generator](./后端/yudao-cloudmaster/.image/代码生成.jpg) | ![Result](./后端/yudao-cloudmaster/.image/生成效果.jpg) | ![API](./后端/yudao-cloudmaster/.image/系统接口.jpg) |

| MySQL Monitor | Redis Monitor | Java Monitor |
|:---:|:---:|:---:|
| ![MySQL](./后端/yudao-cloudmaster/.image/MySQL.jpg) | ![Redis](./后端/yudao-cloudmaster/.image/Redis.jpg) | ![Java](./后端/yudao-cloudmaster/.image/Java监控.jpg) |

### Mobile Admin

| Login | Home | My |
|:---:|:---:|:---:|
| ![](.image/admin-uniapp/01.png) | ![](.image/admin-uniapp/02.png) | ![](.image/admin-uniapp/03.png) |

| Workbench | Menu | Settings |
|:---:|:---:|:---:|
| ![](.image/admin-uniapp/04.png) | ![](.image/admin-uniapp/05.png) | ![](.image/admin-uniapp/06.png) |

---

## 💡 Implementation Details

### Module Division Principles

This project follows **Domain-Driven Design (DDD)** principles, dividing modules by business domains with high cohesion and low coupling.

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                          Module Division Principles                             │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│  【Principle 1: High Cohesion, Low Coupling】                                   │
│  ┌───────────────────────────────────────────────────────────────────────────┐  │
│  │  • Each module has single responsibility                                    │  │
│  │  • Modules communicate via API, not implementation                          │  │
│  │  • High internal cohesion, related logic together                          │  │
│  │  • Low external coupling, stable interfaces                                │  │
│  └───────────────────────────────────────────────────────────────────────────┘  │
│                                                                                 │
│  【Principle 2: Frontend-Backend Separation】                                    │
│  ┌───────────────────────────────────────────────────────────────────────────┐  │
│  │  • Backend provides RESTful API with JSON                                   │  │
│  │  • Frontend fully independent, can be deployed separately                  │  │
│  │  • Frontend and backend develop in parallel                               │  │
│  │  • Support multi-terminal: Web, iOS, Android, WeChat                       │  │
│  └───────────────────────────────────────────────────────────────────────────┘  │
│                                                                                 │
│  【Principle 3: Domain-Driven Design】                                          │
│  ┌───────────────────────────────────────────────────────────────────────────┐  │
│  │  • Modules divided by business domains (System/BPM/Mall/CRM/ERP/IoT)      │  │
│  │  • Each module contains complete functionality (Controller/Service/Repo)   │  │
│  │  • Modules expose services via API layer, hide internal implementation    │  │
│  └───────────────────────────────────────────────────────────────────────────┘  │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

### Code Layer Architecture

This project uses a **four-layer architecture** for clear separation of concerns.

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                         Four-Layer Architecture                                  │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│  ┌───────────────────────────────────────────────────────────────────────────┐  │
│  │  Layer 1: Controller (Web Layer)                                           │  │
│  │  • Receive HTTP requests, parameter binding & validation                  │  │
│  │  • Call Service layer for business logic                                  │  │
│  │  • Return CommonResult response                                          │  │
│  │  • @PreAuthorize for permission check                                     │  │
│  └───────────────────────────────────────────────────────────────────────────┘  │
│                                     │                                            │
│                                     ▼                                            │
│  ┌───────────────────────────────────────────────────────────────────────────┐  │
│  │  Layer 2: Service (Business Logic Layer) - API Interface + Impl           │  │
│  │  • 2.1 API Interface: Define method signatures, use DTO/VO               │  │
│  │  • 2.2 Service Impl: Implement business logic, transaction management      │  │
│  │  • Call Repository layer for data operations                              │  │
│  └───────────────────────────────────────────────────────────────────────────┘  │
│                                     │                                            │
│                                     ▼                                            │
│  ┌───────────────────────────────────────────────────────────────────────────┐  │
│  │  Layer 3: Repository (Data Access Layer)                                  │  │
│  │  • MyBatis Plus DAO layer                                                │  │
│  │  • DO (Data Object): Database entity                                     │  │
│  │  • DTO/VO: Data transfer, shield internal entities                         │  │
│  └───────────────────────────────────────────────────────────────────────────┘  │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

### Request Processing Flow

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                         Request Processing Flow                                  │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│    ┌─────────┐                                                                  │
│    │  User   │  HTTP Request + Token                                            │
│    │ Request │                                                                   │
│    └────┬────┘                                                                  │
│         │                                                                        │
│         ▼                                                                        │
│    ┌─────────┐                                                                  │
│    │ Gateway │  ① Route ② Token Parse ③ Rate Limit                              │
│    └────┬────┘                                                                  │
│         │                                                                        │
│         ▼                                                                        │
│    ┌─────────┐                                                                  │
│    │         │  ① Parameter Binding ② @Valid ③ @PreAuthorize                  │
│    │Controller│  ④ Call Service Layer                                           │
│    └────┬────┘                                                                  │
│         │                                                                        │
│         ▼                                                                        │
│    ┌─────────┐                                                                  │
│    │ Service │  ① Business Logic ② Transaction ③ MQ                             │
│    └────┬────┘                                                                  │
│         │                                                                        │
│         ▼                                                                        │
│    ┌─────────┐                                                                  │
│    │  Repo   │  MyBatis Plus CRUD                                              │
│    └────┬────┘                                                                  │
│         │                                                                        │
│         ▼                                                                        │
│    ┌─────────┐                                                                  │
│    │  MySQL  │  Data Persistence                                                │
│    └─────────┘                                                                  │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

---

## 🔐 Security & Authentication

This system uses **JWT Token + Spring Security** for stateless authentication, supporting multi-terminal login, Token renewal, and forced logout.

### User Login Flow

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                         User Login Flow                                          │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│    ┌─────────┐                                                                  │
│    │  User   │  Enter username & password                                      │
│    │  Login  │                                                                   │
│    └────┬────┘                                                                  │
│         │                                                                        │
│         ▼                                                                        │
│    ┌─────────────────────────────────────────────────────────────────────────┐  │
│    │              AuthController receives request                              │  │
│    │   POST /auth/login { username, password, captchaUuid, captchaCode }     │  │
│    └─────────────────────────────────────────────────────────────────────────┘  │
│                                     │                                            │
│                                     ▼                                            │
│    ┌─────────────────────────────────────────────────────────────────────────┐  │
│    │                 Username & Password Verification                          │  │
│    │  ┌─────────────────┐     ┌─────────────────┐                           │  │
│    │  │ UserDetailsSvc │────▶│ Spring Security │                          │  │
│    │  │ Query user info │     │ BCrypt match    │                          │  │
│    │  └────────┬────────┘     └────────┬────────┘                           │  │
│    │           └───────────┬───────────┘                                      │  │
│    │                       ▼                                                  │  │
│    │               ┌─────────────┐                                           │  │
│    │               │   Database  │                                           │  │
│    │               │ system_users│                                           │  │
│    │               └─────────────┘                                           │  │
│    └─────────────────────────────────────────────────────────────────────────┘  │
│                                     │                                            │
│                                     ▼                                            │
│    ┌─────────────────────────────────────────────────────────────────────────┐  │
│    │                         Token Generation                                 │  │
│    │  ┌─────────────────────────────────────────────────────────────────┐    │  │
│    │  │  JWT Payload:                                                    │    │  │
│    │  │  {                                                               │    │  │
│    │  │    userId: 123456,        // User ID                             │    │  │
│    │  │    username: "admin",     // Username                            │    │  │
│    │  │    tenantId: 1,           // Tenant ID                          │    │  │
│    │  │    expiresTime: 172800,   // Expiry (2 hours)                    │    │  │
│    │  │    loginIp: "127.0.0.1", // Login IP                            │    │  │
│    │  │    loginDate: "2026-04-15" // Login Date                        │    │  │
│    │  │  }                                                               │    │  │
│    │  └─────────────────────────────────────────────────────────────────┘    │  │
│    └─────────────────────────────────────────────────────────────────────────┘  │
│                                     │                                            │
│                                     ▼                                            │
│    ┌─────────┐                                                                  │
│    │ Return  │  { code: 0, data: { accessToken: "xxx", expiresTime: 7200 } }   │
│    └─────────┘                                                                  │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

### Request Authentication Flow

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                       Request Authentication Flow                               │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│    ┌─────────┐                                                                  │
│    │ Request │  Header: Authorization: Bearer {accessToken}                      │
│    └────┬────┘                                                                  │
│         │                                                                        │
│         ▼                                                                        │
│    ┌─────────────────────────────────────────────────────────────────────────┐  │
│    │                         Gateway Routing Layer                            │  │
│    │  ① Route matching (forward by path)                                      │  │
│    │  ② Token parsing (extract from Header)                                   │  │
│    │  ③ Rate limit check (Sentinel)                                           │  │
│    │  ④ Blacklist blocking                                                   │  │
│    └─────────────────────────────────────────────────────────────────────────┘  │
│                                     │                                            │
│                                     ▼                                            │
│    ┌─────────────────────────────────────────────────────────────────────────┐  │
│    │                   TokenAuthenticationFilter                              │  │
│    │  1. Extract Token from Header                                           │  │
│    │  2. Validate Token (signature, expiry)                                   │  │
│    │  3. Parse user info from Token                                           │  │
│    │  4. Store in SecurityContext                                            │  │
│    └─────────────────────────────────────────────────────────────────────────┘  │
│                                     │                                            │
│                                     ▼                                            │
│    ┌─────────────────────────────────────────────────────────────────────────┐  │
│    │                   Controller Permission Check                            │  │
│    │  @PreAuthorize("@ss.hasPermission('system:user:create')")              │  │
│    └─────────────────────────────────────────────────────────────────────────┘  │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

### Token Lifecycle Management

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                      Token Lifecycle Management                                  │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│  ┌─────────────────────────────────────────────────────────────────────────┐  │
│  │                       Token Three States                                  │  │
│  │                                                                         │  │
│  │   ┌─────────────┐    ┌─────────────┐    ┌─────────────┐                │  │
│  │   │   Valid     │───▶│  Near Expiry │───▶│   Expired   │                │  │
│  │   │ (Normal)    │    │ (Auto Renew) │    │(Re-login)   │                │  │
│  │   │  >30min left│    │  <30min left │    │ >2 hours    │                │  │
│  │   └─────────────┘    └─────────────┘    └─────────────┘                │  │
│  │                                                                         │  │
│  └─────────────────────────────────────────────────────────────────────────┘  │
│                                                                                 │
│  Token Renewal Strategy:                                                        │
│  • When Token is near expiry (<30min), frontend auto-calls refresh API        │
│  • Refresh Token mechanism: 7-day validity                                    │
│  • POST /auth/refresh for active renewal                                      │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

---

## 🛡️ Permission Control

This system implements **four-level permission control** for URL, menu, button, and data security.

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                      Four-Level Permission System                                │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│  ┌─────────────────────────────────────────────────────────────────────────┐  │
│  │  Level 1: URL Permission Control                                         │  │
│  │  Layer: Spring Security Filter    Timing: Before Controller              │  │
│  │  Implementation: Config class + Dynamic permission loading               │  │
│  └─────────────────────────────────────────────────────────────────────────┘  │
│                                     │                                            │
│                                     ▼                                            │
│  ┌─────────────────────────────────────────────────────────────────────────┐  │
│  │  Level 2: Menu Permission Control                                        │  │
│  │  Layer: Vue Router + Backend menu service    Timing: After login         │  │
│  │  Implementation: Query menus by role → Build menu tree → Frontend route │  │
│  └─────────────────────────────────────────────────────────────────────────┘  │
│                                     │                                            │
│                                     ▼                                            │
│  ┌─────────────────────────────────────────────────────────────────────────┐  │
│  │  Level 3: Button Permission Control                                      │  │
│  │  Layer: @PreAuthorize annotation    Timing: Before Controller method      │  │
│  │  Implementation: Custom annotation + SpEL + PermissionService           │  │
│  └─────────────────────────────────────────────────────────────────────────┘  │
│                                     │                                            │
│                                     ▼                                            │
│  ┌─────────────────────────────────────────────────────────────────────────┐  │
│  │  Level 4: Data Permission Control                                        │  │
│  │  Layer: MyBatis Plus plugin    Timing: Before SQL execution              │  │
│  │  Types: ALL/DEPT_AND_CHILD/DEPT_ONLY/SELF/CUSTOM                         │  │
│  └─────────────────────────────────────────────────────────────────────────┘  │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

### Data Permission Types

| Type | Scope | SQL Condition |
|:---|:---|:---|
| **ALL** | All data | No restriction |
| **DEPT_AND_CHILD** | Current dept + child depts | `dept_id IN (SELECT id FROM dept WHERE path LIKE '%deptId%')` |
| **DEPT_ONLY** | Current dept only | `dept_id = #{deptId}` |
| **SELF** | Own data only | `creator = #{userId}` |
| **CUSTOM** | Custom dept list | `dept_id IN (#{customDeptIds})` |

### Permission Data Structure

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                       Permission Data Table Design                               │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│  ┌─────────────────┐     ┌─────────────────┐                                    │
│  │  system_user   │────▶│ system_user_role│                                    │
│  │  User Table     │     │ User-Role Map   │                                    │
│  └─────────────────┘     └────────┬────────┘                                    │
│                                  │                                               │
│                                  ▼                                               │
│                          ┌───────────────┐                                      │
│                          │ system_role   │                                      │
│                          │   Role Table   │                                      │
│                          └───────┬───────┘                                      │
│                                  │                                               │
│                                  ▼                                               │
│                          ┌───────────────┐                                      │
│                          │system_role_menu│                                     │
│                          │ Role-Menu Map  │                                     │
│                          └───────┬───────┘                                      │
│                                  │                                               │
│                                  ▼                                               │
│                          ┌───────────────┐                                      │
│                          │  system_menu  │                                      │
│                          │  Menu Table   │                                      │
│                          └───────────────┘                                      │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

---

## ⚡ High Concurrency

This system uses **Rate Limiting + Cache + Queue + Lock** strategy for high concurrency.

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                        High Concurrency Architecture                              │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│                              ┌─────────────────┐                                │
│                              │   User Request  │                                │
│                              │  (10K+ QPS)     │                                │
│                              └────────┬────────┘                                │
│                                       │                                          │
│                                       ▼                                          │
│                         ┌────────────────────────┐                             │
│                         │    Sentinel Rate Limit  │                             │
│                         │  ┌────┐ ┌────┐ ┌────┐  │                             │
│                         │  │QPS │ │ THD│ │ PATH│ │                             │
│                         │  └────┘ └────┘ └────┘  │                             │
│                         └────────────┬───────────┘                             │
│                                        │                                          │
│                                        ▼                                          │
│                         ┌────────────────────────┐                             │
│                         │      Redis Cache       │                             │
│                         │  ┌────┐ ┌────┐ ┌────┐  │                             │
│                         │  │HOT │ │SESS│ │LOCK│ │                             │
│                         │  └────┘ └────┘ └────┘  │                             │
│                         └────────────┬───────────┘                             │
│                                        │                                          │
│                                        ▼                                          │
│                         ┌────────────────────────┐                             │
│                         │   RocketMQ Message Queue │                             │
│                         └────────────┬───────────┘                             │
│                                        │                                          │
│                                        ▼                                          │
│                         ┌────────────────────────┐                             │
│                         │    Business Logic       │                             │
│                         │  (Redisson Dist. Lock)  │                             │
│                         └────────────┬───────────┘                             │
│                                        │                                          │
│                                        ▼                                          │
│                         ┌────────────────────────┐                             │
│                         │       MySQL Database    │                             │
│                         └────────────────────────┘                             │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

### 1. Rate Limiting (Sentinel)

| Capability | Description |
|:---|:---|
| Flow Control | QPS limit, concurrent thread limit, warm-up |
| Circuit Breaker | RT degradation, exception ratio, exception count |
| Hotspot Param | Parameter index limit, parameter value limit |

**Algorithms**: Counter / Sliding Window / Token Bucket / Leaky Bucket

### 2. Cache (Redis)

| Data Type | Use Case |
|:---|:---|
| String | Token, verification code, counter |
| Hash | User info, product details |
| List | Latest message queue, delayed tasks |
| Set | User tags, blacklist, permissions |
| ZSet | Leaderboard, hot search |
| BitMap | User check-in, online status |

**Cache Strategies**:
- Cache-Aside: Read-through, write-delete
- Cache Problems: Snowflake / Penetration / Breakdown solutions

### 3. Message Queue (RocketMQ)

| Scenario | Description |
|:---|:---|
| Async Decoupling | Welcome email, SMS after registration |
| Peak Shaving | Flash sales, queue buffer |
| Delayed Processing | Auto-cancel unpaid orders after 30min |
| Data Sync | Sync stock after payment |

### 4. Distributed Lock (Redis / Redisson)

```java
RLock lock = redissonClient.getLock("order:create:" + productId);
try {
    boolean locked = lock.tryLock(10, 30, TimeUnit.SECONDS);
    if (!locked) throw new BizException("System busy");
    
    orderService.create(userId, productId);
} finally {
    if (lock.isHeldByCurrentThread()) lock.unlock();
}
```

**Features**: Auto-renewal (watchdog), reentrant, fair lock, read-write lock

### 5. Database Concurrency Control

| Type | Mechanism | Use Case |
|:---|:---|:---|
| Optimistic Lock | @Version annotation | Read-heavy, low conflict |
| Pessimistic Lock | FOR UPDATE | Write-heavy, high conflict |
| Row Lock | InnoDB index condition | Specific row operation |

---

## 🗄️ Database Design

This system follows **8 database design conventions**.

### Convention 1: Unified Primary Key

Snowflake Algorithm: `1 + 41(timestamp) + 10(machineId) + 12(sequence)`

```java
@TableId(type = IdType.ASSIGN_ID)
private Long id;  // Snowflake ID
```

### Convention 2: Unified Time Fields

| Field | Type | Description |
|:---|:---|:---|
| create_time | DATETIME(3) | Creation time |
| update_time | DATETIME(3) | Last update time |
| deleted | TINYINT | 0=normal, 1=deleted |

### Convention 3: Unified Audit Fields

| Field | Description |
|:---|:---|
| creator | Creator user ID |
| updater | Last updater user ID |
| dept_id | Department ID (for data permission) |

### Convention 4: Index Naming

| Prefix | Meaning | Example |
|:---|:---|:---|
| idx_ | Normal index | idx_user_status |
| uk_ | Unique index | uk_username |
| fk_ | Foreign key | fk_order_user_id |

### Convention 5: Logical Delete

```java
@TableLogic
private Integer deleted;  // 0=normal, 1=deleted
```

### Convention 6: Tenant Isolation

```java
// TenantLineInnerInterceptor auto-appends tenant_id
@TableName(value = "system_user", autoResultMap = true)
public class AdminUserDO extends TenantBaseDO { ... }
```

### Convention 7-8: Naming Conventions

- **Field**: snake_case (user_name, create_time)
- **Table**: {module}_{entity} (system_user, mall_order)

### Base Table Template

```sql
CREATE TABLE `{table_name}` (
    `id` BIGINT UNSIGNED NOT NULL COMMENT 'Primary Key',
    `tenant_id` BIGINT UNSIGNED NOT NULL DEFAULT 0 COMMENT 'Tenant ID',
    `status` TINYINT NOT NULL DEFAULT 0 COMMENT 'Status',
    `creator` BIGINT UNSIGNED DEFAULT NULL COMMENT 'Creator',
    `create_time` DATETIME(3) NOT NULL DEFAULT CURRENT_TIMESTAMP(3) COMMENT 'Create Time',
    `updater` BIGINT UNSIGNED DEFAULT NULL COMMENT 'Updater',
    `update_time` DATETIME(3) NOT NULL DEFAULT CURRENT_TIMESTAMP(3) ON UPDATE CURRENT_TIMESTAMP(3) COMMENT 'Update Time',
    `dept_id` BIGINT UNSIGNED DEFAULT NULL COMMENT 'Dept ID',
    `deleted` BIT NOT NULL DEFAULT b'0' COMMENT 'Deleted',
    PRIMARY KEY (`id`),
    KEY `idx_tenant_id` (`tenant_id`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COMMENT='{remark}';
```

---

## 📱 Mobile Applications

### Admin App (yudao-ui-admin-uniapp)

uni-app based, supports **iOS/Android/WeChat** multi-platform.

#### Feature Modules

| Module | Features |
|:---|:---|
| **Login** | Account login, captcha, Token refresh |
| **Dashboard** | Data overview, shortcuts, to-do list |
| **User/Role/Menu** | CRUD, Excel import/export |
| **Department** | Org tree, CRUD |
| **Dict** | Dict type, dict data maintenance |
| **Logs** | Login logs, operation logs |
| **Profile** | Personal info, password change |

#### Technical Architecture

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                      Admin App Architecture                                      │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│  uni-app + Vue3 + Pinia + uni-ui                                               │
│                                                                                 │
│  ┌───────────────────────────────────────────────────────────────────────────┐  │
│  │  State Management: userStore, appStore, dictStore                         │  │
│  └───────────────────────────────────────────────────────────────────────────┘  │
│                                     │                                            │
│  ┌───────────────────────────────────────────────────────────────────────────┐  │
│  │  Network Layer: request.ts (auto token, error handling, interceptors)      │  │
│  └───────────────────────────────────────────────────────────────────────────┘  │
│                                     │                                            │
│  ┌───────────────────────────────────────────────────────────────────────────┐  │
│  │  Permission: v-permission directive + router guard                        │  │
│  └───────────────────────────────────────────────────────────────────────────┘  │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

### Mall App (yudao-mall-uniapp)

C-end mall with shopping flow, supports **WeChat/AliPay/H5**.

#### Feature Modules

| Module | Features |
|:---|:---|
| **Home** | Banner, categories, flash sales, coupons |
| **Product** | Multi-level categories, details, search, favorites |
| **Cart** | Add, edit, checkout |
| **Order** | Confirm, list, logistics, refund |
| **Payment** | WeChat Pay, balance pay |
| **Member** | Level, points, coupons |
| **Customer** | Online chat, FAQ |

#### Mall Shopping Flow

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                        Mall Shopping Flow                                         │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│  Browse Products → Product Details → Add to Cart → Checkout → Pay → Logistics → Receive │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

#### Payment Flow (WeChat Pay)

```
1. MiniApp calls wx.login() to get code
2. Send code to backend
3. Backend calls WeChat API to get openid
4. Backend creates payment order, returns pre-pay order
5. MiniApp calls wx.requestPayment()
6. WeChat notifies backend after payment
7. Backend processes result, MiniApp shows success page
```

---

## 💡 Quick Start

### Environment Requirements

| Environment | Version |
|:---|:---|
| JDK | 8 or 17+ |
| MySQL | 5.7 / 8.0+ |
| Redis | 5.0 / 6.0 |
| Node.js | 16+ |
| Nacos | 2.3.2 |

### 1. Database Setup

```bash
# Import MySQL scripts
mysql -u root -p < 数据库/sql/mysql/*.sql
```

### 2. Start Backend

```bash
# Start Nacos first
# Update yudao-server/src/main/resources/application.yml with DB/Redis config

# Import project in IDEA, run yudao-server main class
```

### 3. Start Frontend

```bash
cd 前端/yudao-ui-admin-vue3
npm install
npm run dev
```

### 4. Access System

- Frontend: <http://localhost:80>
- Default User: admin
- Default Password: admin123

---

## 📄 License

This project is licensed under the [MIT License](https://gitee.com/zhijiantianya/ruoyi-vue-pro/blob/master/LICENSE).

**Why choose this project?**

1. MIT License - more permissive than Apache 2.0, 100% free
2. All code open source, clean architecture
3. Follows Alibaba Java Development Guide, detailed comments

---

**Please give this project a Star! It means a lot to the developers!** ⭐⭐⭐

---

**Document Version**: v1.0
**Last Updated**: 2026-04-15
