<div align="center">

  <img src="./assets/header.svg" alt="Miqueas Aguirre — Backend Lead & Python Architect" width="100%" />

  <br/>

  <!-- Dynamic Typing Telemetry -->
  <a href="https://github.com/MiqueasAguirreANX">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=15&duration=3000&pause=1000&color=00F0FF&center=true&vCenter=true&width=750&height=42&lines=%3E+High-Availability+Distributed+Architecture;%3E+MQTT+Broker+Mesh%2C+Kafka+%26+Industrial+IoT;%3E+Real-Time+ML+Anomaly+Detection+%26+Local+LLMs;%3E+Async+Python%3A+FastAPI+%E2%80%A2+Django-Bolt+%E2%80%A2+Asyncio" alt="Typing SVG" />
  </a>

  <p align="center">
    <a href="https://www.linkedin.com/in/miqueas-aguirre-621511167">
      <img src="https://img.shields.io/badge/LinkedIn-Miqueas_Aguirre-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:miqueasburzum@gmail.com">
      <img src="https://img.shields.io/badge/Email-miqueasburzum%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <img src="https://img.shields.io/badge/Focus-HA_Infrastructure_%26_AI-7AA2F7?style=for-the-badge&logo=linux&logoColor=white" alt="Focus" />
    <img src="https://img.shields.io/badge/Base-Buenos_Aires%2C_AR-10B981?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
  </p>

</div>

---

### 🖥️ `whoami` // System Specification

```yaml
miqueas@arch-cluster-01:~$ cat /etc/architect/spec.yaml
---
identity:
  name: "Miqueas Aguirre"
  role: "Backend Lead & Python Architect | Infrastructure & AI Engineer"
  experience: "5+ years designing mission-critical, high-availability systems"
  foundation: "Electronic Engineering background (UTN) -> hardware-to-cloud systems mindset"

core_capabilities:
  high_availability:
    - "Zero-downtime failover clusters (PostgreSQL HA, CrateDB, Apache Kafka)"
    - "Distributed MQTT Broker Mesh orchestration for resilient telemetry ingestion"
    - "Load balancing & reverse-proxy hardening (HAProxy, Nginx, Docker, Kubernetes)"
  backend_architecture:
    - "High-throughput async Python services (FastAPI, Django, Django-Bolt, Asyncio, Celery)"
    - "Multi-tenant SaaS architectures, FinTech payment integrations & cybersecurity MVPs"
  industrial_iot:
    - "Large-scale real-time telemetry ingestion via MQTT, Paho-MQTT, LoRaWAN & SNMP"
  enterprise_ai:
    - "Real-time statistical & ML anomaly detection for multi-tenant IoT data streams"
    - "Generative AI pipelines with Google Gemini & Local LLMs (Mistral 119B via Ollama)"
    - "AI-native engineering workflows (Cursor) for autonomous & accelerated delivery"

off_duty_processes:
  - "🎸 Dialing in heavy metal riffs on electric guitar"
  - "🛡️ Defending towers in Kingdom Rush"
  - "🐧 Daily-driving & tuning Linux Mint"
```

---

### 🏗️ Reference Architecture // What I Build in Production

> A snapshot of the distributed, fault-tolerant ecosystems I design and lead—bridging **industrial edge telemetry**, **high-availability broker meshes**, **async Python microservices**, and **real-time AI/ML inference**:

```mermaid
flowchart LR
    subgraph Edge["📡 Industrial Edge & IoT"]
        LORA["LoRaWAN Gateways"]
        SNMP["SNMP Devices"]
        SENSORS["Industrial Telemetry"]
    end

    subgraph Mesh["🛡️ HA Ingress & Broker Mesh"]
        HAP["HAProxy / Nginx LB"]
        MQTT["MQTT Broker Mesh<br/>(Failover Clustering)"]
    end

    subgraph Stream["⚡ Distributed Event Backbone"]
        KAFKA["Apache Kafka Cluster"]
        REDIS["Redis / Celery Queue"]
    end

    subgraph Core["🐍 Async Python & AI Engine"]
        API["FastAPI / Django-Bolt<br/>Asyncio Microservices"]
        ML["Real-Time ML<br/>Anomaly Detection"]
        LLM["Enterprise AI Engine<br/>Gemini + Ollama (Mistral 119B)"]
    end

    subgraph Data["🗄️ High-Availability Storage"]
        PG["PostgreSQL<br/>(HA Cluster)"]
        CRATE["CrateDB<br/>(Time-Series Cluster)"]
        MONGO["MongoDB"]
    end

    LORA & SNMP & SENSORS --> HAP
    HAP --> MQTT
    MQTT --> KAFKA
    KAFKA --> API & ML
    API <--> REDIS
    API --> LLM
    API & ML --> PG & CRATE & MONGO
```

---

### 🧠 Core Technical Arsenal

<table>
  <thead>
    <tr>
      <th width="26%">Domain</th>
      <th width="74%">Stack & Production Capabilities</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>🐍 Backend & Async Python</b></td>
      <td>
        <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
        <img src="https://img.shields.io/badge/Django--Bolt-10B981?style=for-the-badge&logo=lightning&logoColor=white" />
        <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
        <img src="https://img.shields.io/badge/Asyncio-38BDF8?style=for-the-badge&logo=python&logoColor=black" />
        <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" />
        <br/>
        <sub>Multi-tenant SaaS architectures • High-concurrency microservices • Event-driven workers • REST & real-time APIs</sub>
      </td>
    </tr>
    <tr>
      <td><b>🛡️ Architecture & HA Infra</b></td>
      <td>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
        <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
        <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
        <img src="https://img.shields.io/badge/HAProxy-191A1B?style=for-the-badge&logo=haproxy&logoColor=white" />
        <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
        <img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
        <br/>
        <sub>High Availability (HA) clustering • Automated failover node management • Container orchestration • Zero-downtime deployments</sub>
      </td>
    </tr>
    <tr>
      <td><b>🗄️ Distributed Data & Brokers</b></td>
      <td>
        <img src="https://img.shields.io/badge/PostgreSQL_HA-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/CrateDB-0099D8?style=for-the-badge&logo=databricks&logoColor=white" />
        <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
        <img src="https://img.shields.io/badge/MQTT_Mesh-660066?style=for-the-badge&logo=mqtt&logoColor=white" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
        <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" />
        <br/>
        <sub>Replicated PostgreSQL clusters • Distributed CrateDB time-series storage • Kafka event streaming • Fault-tolerant MQTT Broker Mesh</sub>
      </td>
    </tr>
    <tr>
      <td><b>🤖 Enterprise AI & ML</b></td>
      <td>
        <img src="https://img.shields.io/badge/Machine_Learning-FF6F00?style=for-the-badge&logo=scikitlearn&logoColor=white" />
        <img src="https://img.shields.io/badge/Ollama_Local_LLMs-000000?style=for-the-badge&logo=meta&logoColor=white" />
        <img src="https://img.shields.io/badge/Mistral_119B-F97316?style=for-the-badge&logo=sparkles&logoColor=white" />
        <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
        <img src="https://img.shields.io/badge/Cursor_AI-111827?style=for-the-badge&logo=terminal&logoColor=00F0FF" />
        <br/>
        <sub>Real-time statistical & ML anomaly detection • On-prem Local LLM inference (Mistral 119B via Ollama) • Autonomous GenAI pipelines</sub>
      </td>
    </tr>
    <tr>
      <td><b>📡 Industrial IoT & Protocols</b></td>
      <td>
        <img src="https://img.shields.io/badge/LoRaWAN-00A3E0?style=for-the-badge&logo=rss&logoColor=white" />
        <img src="https://img.shields.io/badge/SNMP-475569?style=for-the-badge&logo=cisco&logoColor=white" />
        <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white" />
        <img src="https://img.shields.io/badge/Paho--MQTT-3776AB?style=for-the-badge&logo=eclipseide&logoColor=white" />
        <br/>
        <sub>High-throughput industrial device ingestion • Low-latency telemetry parsing • Multi-protocol edge-to-cloud bridges</sub>
      </td>
    </tr>
    <tr>
      <td><b>⚛️ Frontend & Integrations</b></td>
      <td>
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
        <img src="https://img.shields.io/badge/React.js-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/Mercado_Pago-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white" />
        <br/>
        <sub>Fullstack SPA dashboards • Regional payment gateways & taxation workflows • European market & global crypto analytics</sub>
      </td>
    </tr>
  </tbody>
</table>

---

### 📜 Production Track Record // `git log --career`

```
* commit HEAD -> main (2023.09 - PRESENT)
│ Role:   Backend Lead & Infrastructure Engineer @ Daitek (Buenos Aires)
│ Impact: • Architected & deployed mission-critical HA infrastructure (PostgreSQL HA, CrateDB & Kafka clusters).
│         • Orchestrated a fault-tolerant mesh network of MQTT brokers with automated failover node management.
│         • Built large-scale real-time industrial telemetry ingestion engines (MQTT, LoRaWAN, SNMP).
│         • Designed a real-time ML & statistical anomaly detection microservice for multi-tenant IoT streams.
│         • Directed R&D and core backend optimization across FastAPI, Django, Django-Bolt & Asyncio services.
│
* commit a8f42c1 (2021.05 - 2023.08)
│ Role:   Fullstack Developer @ Kensa (Saudi Arabia · Remote)
│ Impact: • Delivered rapid end-to-end Cyber Security MVPs under tight commercial launch deadlines.
│         • Engineered scalable fullstack architectures (Django/DRF, Flask, React.js), bridging legacy systems
│           into modern microservices and optimizing high-volume security event log parsing.
│         • Automated CI/CD delivery pipelines, custom data-processing scripts, and distributed scrapers.
│
* commit 7d91e04 (2020.06 - PRESENT)
│ Role:   Software Engineer & SaaS Architect @ Independent Consultant (Remote)
│ Impact: • Architected multi-tenant SaaS platforms: reservation systems, cybersecurity suites, and a complete
│           end-to-end Pharmacy Management Platform (inventory, staff, billing & receipt lifecycle).
│         • Integrated regional payment gateways & tax engines (Mercado Pago) and built analytics pipelines
│           for European market datasets and global Crypto projects.
│         • Spearheaded enterprise GenAI workflows with Google Gemini, Local LLMs (Ollama), and Cursor.
│
* commit 1b00f99 (2018 - 2021)
  Foundation: Electronic Engineering (Level 2 Foundation) @ UTN - Facultad Regional Haedo
  Focus:      Algorithms & Data Structures, Advanced Calculus & Linear Algebra, Electromagnetism, Digital Logic.
```

---

### 📊 GitHub Telemetry

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=MiqueasAguirreANX&show_icons=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f0ff&icon_color=7aa2f7&text_color=c9d1d9&hide=contribs,issues" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MiqueasAguirreANX&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f0ff&text_color=c9d1d9&langs_count=6" alt="Top Languages" />
</div>

---

<div align="center">
  <sub>
    <code>[STATUS: READY FOR COMPLEX ARCHITECTURE CHALLENGES]</code> •
    Built with 🐍 Python mindset, 🐧 Linux Mint &amp; 🎸 Heavy Metal by <b>Miqueas Aguirre</b>
  </sub>
</div>
