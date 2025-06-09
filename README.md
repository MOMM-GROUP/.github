## Hi there welcome to MoralAuthority, a Passion Project 👋 🙋‍♀️ 

> ⚠️ **Important Note**  
> This codebase reflects a **previous version** of Moral Authority, when it was being built as a multivendor ethical marketplace.  
> As of **June 2025**, we’ve **pivoted** to a protocol-first architecture focused on decentralized trust verification, AI agent alignment, and federated product data.  
>
> While the UI and backend in this repo are no longer actively maintained, we’re keeping it public as a record of our journey — and we’ll link new repos here as they launch.
>
> ✅ See updated product direction below ↓

---

Originally conceived as a multi-vendor ethical marketplace, **Moral Authority** has evolved into something more foundational:

> A protocol for **verifying product claims**, **tracking brand certifications**, and **making ethical commerce programmable**.

With MOMM, we aim to give consumers tools to shop by what they value — not just what's marketed — and give brands a transparent, verifiable way to prove their impact.

🌈 [Please sign up here to volunteer](https://docs.google.com/forms/d/e/1FAIpQLScy40j_1cKaDunuKNfzWs_60GK3Vz4643qkxNv1LN9t3jDNDw/viewform)  
👩‍💻 Useful resources — technical docs and roadmap coming soon!

---

# Moral Authority 🧠🌱

**Moral Authority** is building the internet’s trust layer for ethical commerce.  
We're evolving from a multi-vendor marketplace into a federated platform for:

- Verifying ethical claims  
- Indexing trust data  
- Empowering values-based purchasing

---

### 🔍 Current Focus (Q2–Q3 2025)

We’re currently building:

🖥️ **Phase 1: Web-Based Vendor Dashboard**  
- Built with Plasmic + React  
- OAuth integration with Shopify and Etsy  
- Unified dashboard to view and (eventually) update listings  
- Live backend: Node.js + Postgres

🔎 **Phase 2: Auto-Verification Engine (starting with B Corp)**  
- Crawls public certifier data (e.g. B Corp)  
- Matches vendors to certifications  
- Verified certifications are logged as events to smart contracts  
- Indexed by The Graph and surfaced via our public TRUST subgraph

📡 **Phase 3: Federation Layer (ActivityPub)**  
- Ethical product listings, claims, and certifications published as ActivityPub objects  
- Buyer apps, Mastodon clients, and certifier feeds can follow vendor updates  
- Groundwork for zero-knowledge proofs (ZKPs) for privacy-preserving claims

---

### 💡 Core Components

- **MOMM** = *Moral Oracle for Meaningful Markets*  
  The protocol logic and coordination layer

- **TRUST** = *Tamper-Resistant Universal Standards Tracker*  
  Smart contracts + subgraph infrastructure for verified certifications and claims

- **LENS** = *Layer for Ethical Networked Scores*  
  AI-generated trust scoring personalized to each user’s values

---

### 📚 Repo Status

> ⚠️ This repo currently contains early marketplace code and brand documentation.

✅ We’re migrating toward a modular structure:

- `/dashboard` – Plasmic + React UI  
- `/contracts` – Solidity contracts + Graph subgraph  
- `/infra` – Node.js backend and Make.com workflows  
- `/docs` – Technical roadmap, governance model, API specs (coming soon)

---

### 🧪 Live Work (2025 Dev Stack)

- **Frontend:** Plasmic + React  
- **Backend:** Node.js (Go transition planned) + PostgreSQL  
- **Infra:** Supabase, Make.com, Tally  
- **Smart Contracts:** Solidity + Polygon zkEVM  
- **Indexing:** The Graph Protocol (subgraph in progress)  
- **Federation:** ActivityPub with JSON-LD format

---

### ✋ Want to get involved?

We welcome engineers, product thinkers, and researchers interested in:

- Decentralized identity & verifiability  
- Subgraph and certification schema design  
- Multi-agent architecture & ethical AI tooling

📩 DM or [open an issue](#) to say hello.

---

### 🛠️ Repo Cleanup / Legacy Notice

If you're browsing historical commits:

> This repo represents an early-stage marketplace MVP. We've since **pivoted to a protocol-first architecture** focused on verifiable data infrastructure for the ethical commerce ecosystem — while preserving the mission to make ethical shopping accessible and real.

---
