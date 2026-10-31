<div align="center">

<a href="https://hrshanto.vercel.app/" target="_blank">
  <img src="assets/images/readme-banner.svg" alt="Hasibur Rahman Shanto - Senior Full-Stack Software Developer" width="100%" />
</a>

<br/><br/>

<a href="https://hrshanto.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=3000&pause=1000&color=22D3EE&center=true&vCenter=true&width=760&height=45&lines=%E2%9A%A1+Senior+Full-Stack+Engineer+%7C+Laravel%2C+MySQL+%26+Redis+at+Scale;%E2%9A%A1+Multi-Tenant+SaaS+ERP+%26+High-Concurrency+POS+Engines;%E2%9A%A1+Real-Time+Systems+with+WebRTC+%26+WebSockets;%E2%9A%A1+Optimized+SQL+Queries+%E2%80%A2+42%25+Latency+Cut+%E2%80%A2+68%25+DB+Load+Drop;%E2%9A%A1+Building+Resilient+Microservices+%26+Automated+Pipelines" alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/●_SYSTEM_OPERATIONAL-AVAILABLE_FOR_HIRE-10b981?style=for-the-badge&labelColor=070a12" alt="System Status" />
<a href="https://hrshanto.vercel.app/" target="_blank">
  <img src="https://img.shields.io/badge/⚡_EXPLORE_3D_PORTFOLIO-hrshanto.vercel.app-6366f1?style=for-the-badge&logo=vercel&logoColor=white&labelColor=070a12" alt="Visit 3D Portfolio" />
</a>

<br/><br/>

<!-- Performance Metrics Bar -->
<img src="https://img.shields.io/badge/PRODUCTION_EXP-4%2B_YEARS-6366f1?style=for-the-badge&labelColor=070a12" alt="Experience" />
<img src="https://img.shields.io/badge/ENTERPRISE_SYSTEMS-7%2B_SHIPPED-06b6d4?style=for-the-badge&labelColor=070a12" alt="Enterprise Systems" />
<img src="https://img.shields.io/badge/WEB_APPS-50%2B_DEPLOYED-3b82f6?style=for-the-badge&labelColor=070a12" alt="Web Apps" />
<br/>
<img src="https://img.shields.io/badge/API_LATENCY_CUT-42%25_FASTER-10b981?style=for-the-badge&labelColor=070a12" alt="Latency Cut" />
<img src="https://img.shields.io/badge/PEAK_DB_LOAD-68%25_REDUCED-22d3ee?style=for-the-badge&labelColor=070a12" alt="DB Load Cut" />
<img src="https://img.shields.io/badge/BATCH_ENGINE-10K%2B_PER_RUN-818cf8?style=for-the-badge&labelColor=070a12" alt="Batch Scale" />

</div>

<br/>

```bash
┌──(shanto㉿production)-[~/system/telemetry]
└─$ sysctl --status --metrics

● Identity     : Hasibur Rahman Shanto // Senior Backend & Full-Stack Systems Engineer (4+ Years)
● Core Focus   : Multi-Tenant SaaS, Concurrency Tuning, High-Throughput POS, Real-Time WebRTC
● Proven Stats : 42% API Latency Reduction (WanIT) | 68% Peak MySQL Load Elimination (EduTab)
● Architecture : Laravel 11, Redis Horizon Clusters, MySQL 8 InnoDB, Docker Microservices
● Live Engine  : https://hrshanto.vercel.app [SYSTEM OPERATIONAL]
```

<br/>

---

### ⚡ // 01 • ENGINEERING DIRECTIVE & FOCUS

> **"I build and scale the invisible, mission-critical infrastructure businesses rely on every single second."**  
> *Full-Stack Software Engineer based in Dhaka with 4+ years of production experience architecting 7+ enterprise systems and deploying 50+ high-concurrency web applications.*

<br/>

| Bottleneck Scenario | Engineering Intervention & Result |
| :--- | :--- |
| ⏱️ **45s+ Heavy Financial Reports** | Offloaded to chunked **Redis Horizon worker clusters** with streaming data buffers. |
| 🔒 **Peak Checkout MySQL Deadlocks** | Eliminated table locks using **composite indexing** and atomic **pessimistic row locking**. |
| 💳 **Sporadic Double-Charge Webhooks** | Implemented **idempotency keys** with atomic DB transaction locks & HMAC signature verification. |
| 📉 **Database Memory & CPU Spikes** | Profiled execution plans with **`EXPLAIN`**, refactored N+1 Eloquent loops, and pruned scans. |

<br/>

---

### 🛠️ // 02 • SYSTEM ARCHITECTURAL PILLARS

| 🏢 Multi-Tenant SaaS Isolation | ⚡ Query Tuning & Deadlock Rescue |
| :--- | :--- |
| **Database-per-tenant architecture** with dynamic subdomains, automated zero-downtime tenant migrations, tenant context switching, and plan-based feature flags. | Deep profiling using MySQL **`EXPLAIN`**, composite indexes, removing N+1 Eloquent relationships, and tuning row locks to prevent concurrency deadlocks. |
| **🚀 Asynchronous Queue Pipelines** | **🔐 Financial Integrity & Idempotency** |
| **Redis Horizon worker clusters** prioritizing heavy PDF generation, chunked imports, and automated dispatchers. Slashed API response times by **42%** at WanIT. | Stripe Connect, bKash, and SSLCommerz integrations with strict **HMAC webhook verification**, atomic DB transactions, and idempotency keys. |
| **📹 Real-Time WebRTC Media & State** | **📦 Omnichannel POS & Stock Sync** |
| Custom WebSocket signaling server, **STUN/TURN NAT traversal**, low-latency screen sharing, and Redis Pub/Sub live presence tracking. | Distributed multi-counter **barcode POS synchronized with central warehouses** using row locks to eliminate overselling under high concurrency. |

<br/>

---

### 🚀 // 03 • PRODUCTION SYSTEMS SHOWCASE

| System & Domain | Architecture & Engineering Highlights | Core Stack |
| :--- | :--- | :--- |
| 🏢 **BNSMSoft**<br/><sub>Multi-Tenant SaaS ERP</sub> | Database-per-tenant isolation, dynamic subdomains, double-entry ledger, barcode POS, subscription billing | `Laravel 11` `Vue.js`<br/>`MySQL` `Redis` |
| 🎓 **EduTab Engine**<br/><sub>High-Concurrency Results</sub> | Generates 10,000+ transcripts in a single batch. Chunked queue workers reduced peak database load by **68%** | `Laravel` `Redis Horizon`<br/>`Queue Workers` |
| 🧾 **Invoicing Engine**<br/><sub>Tax & Compliance Engine</sub> | Thousands of VAT/GST compliant tax invoices per minute with automated delivery, QR validation & payment webhooks | `Laravel` `Redis`<br/>`Puppeteer` `Docker` |
| 🛒 **Multi-Vendor Hub**<br/><sub>Marketplace & Escrow</sub> | Independent vendor portals, 8.5% automated commission splitting, split-cart checkouts, and automated payouts | `Laravel` `Stripe Connect`<br/>`bKash API` |
| 🏭 **Manufacturing ERP**<br/><sub>Supply Chain Pipeline</sub> | End-to-end textile factory pipeline (dyeing to sewing), QC inspection, delivery challans, and payroll accounting | `Laravel` `MySQL`<br/>`Vue.js` `Docker` |
| 🏗️ **Kadamati Logistics**<br/><sub>Construction ERP</sub> | Heavy equipment tracking, fuel logs, site safety compliance audits, and biometric attendance across 12 active sites | `Laravel` `MySQL`<br/>`Docker` `Nginx` |
| 📹 **WebRTC Meet & Collab**<br/><sub>Real-Time Video Platform</sub> | Custom WebRTC signaling server, STUN/TURN traversal, screen sharing, and live presence tracking over WebSockets | `Laravel` `WebRTC`<br/>`Socket.io` `Redis` |

> 💡 **Explore live 3D demos, system telemetry monitors, and full architectural write-ups on my portfolio:**  
> **[hrshanto.vercel.app](https://hrshanto.vercel.app/)**

<br/>

---

### 💻 // 04 • TECHNICAL STACK & ARSENAL

<div align="center">

<img src="https://skillicons.dev/icons?i=php,laravel,mysql,postgres,redis,vue,nextjs,js,ts,tailwind,bootstrap,docker,nginx,linux,githubactions,git,nodejs&theme=dark&perline=8" alt="tech stack" />

</div>

<br/>

| Layer | Technologies & Architectural Methodologies |
| :--- | :--- |
| ⚙️ **Core Backend** | PHP 8.3+, Laravel 10–12, Eloquent ORM, Redis Horizon, Queue Workers, Sanctum, JWT, Repository & Service Patterns, SOLID Principles |
| 🗄️ **Databases & Cache** | MySQL 8 InnoDB, PostgreSQL, Redis Cache & Pub/Sub, `EXPLAIN` Query Profiling, Composite Indexing, Zero-Downtime Migrations |
| ⚡ **Realtime & Payments** | WebRTC (P2P Mesh, Screen Share), WebSockets / Socket.io, Stripe Connect, bKash Merchant API, SSLCommerz |
| 🐳 **DevOps & Cloud** | Docker, Docker Compose, Nginx Reverse Proxy, Ubuntu / Linux VPS, GitHub Actions CI/CD Pipelines |
| 🤖 **AI & Modern Workflow** | OpenAI & Gemini APIs, Cursor, Claude AI, Automated System Telemetry & Testing Workflows |

<br/>

---

### 📬 // 05 • LET'S CONNECT & BUILD HIGH-IMPACT SYSTEMS

Whether you need a senior engineer to architect a new SaaS platform, scale an existing Laravel/MySQL infrastructure, or eliminate stubborn database performance bottlenecks:

<br/>

<div align="center">

<a href="https://hrshanto.vercel.app/" target="_blank">
  <img src="https://img.shields.io/badge/⚡_EXPLORE_3D_PORTFOLIO-hrshanto.vercel.app-6366f1?style=for-the-badge&logo=vercel&logoColor=white&labelColor=070a12" alt="3D Portfolio" />
</a>
&nbsp;
<a href="mailto:shantorhaman81@gmail.com">
  <img src="https://img.shields.io/badge/📧_DIRECT_EMAIL-shantorhaman81%40gmail.com-06b6d4?style=for-the-badge&logo=gmail&logoColor=white&labelColor=070a12" alt="Direct Email" />
</a>
&nbsp;
<a href="https://wa.me/8801738450807" target="_blank">
  <img src="https://img.shields.io/badge/💬_WHATSAPP-Chat_Directly-10b981?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=070a12" alt="WhatsApp" />
</a>

<br/><br/>

<a href="https://hrshanto.vercel.app/" target="_blank">
  <img src="assets/images/readme-footer.svg" alt="Code. Build. Scale. Repeat. - Hasibur Rahman Shanto" width="100%" />
</a>

<br/>

<sub>© 2026 Hasibur Rahman Shanto • High-Throughput Distributed Architecture</sub>

</div>
