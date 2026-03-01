# 🛡️ KeelStack Security Policy

At **KeelStack**, we are committed to building secure **AI‑Native SaaS Starter Kits** for solo founders and indie hackers. We welcome the efforts of security researchers to help us maintain the highest level of integrity for our customers and our code.

---

## 🚀 Reporting a Vulnerability

If you discover a security vulnerability in any KeelStack repository (including our public community repo or private template repos), **please do not open a public issue**. Public disclosure before a fix is available puts our users at risk.

Instead, report all security concerns directly to:

- **Email:** [security@keelstack.me](mailto:security@keelstack.me)
- **Encryption:** Reports are handled privately and access is restricted to core maintainers.

### ⏱️ What to Expect

- **Acknowledgement:** You will receive an acknowledgement of your report within **24 hours** (often sooner).  
- **Investigation:** Our team will investigate and validate the issue.  
- **Updates:** We will keep you informed as we work toward a resolution.  
- **Resolution:** Once a fix is ready, we will notify affected users (if any) and release an update.

---

## 🛠️ Disclosure Policy

We follow **Coordinated Vulnerability Disclosure**. We ask that you allow us a reasonable amount of time to resolve the issue before making any public disclosure. We will work with you to agree on a disclosure timeline.

### ✅ In Scope

Vulnerabilities in the following areas are considered in scope:

- Authentication bypass (e.g., Auth.js, JWT logic)  
- Data leakage (API endpoints, middleware, environment variables)  
- Injection flaws (Prisma, SQL, NoSQL)  
- Insecure configuration (deployment scripts, Cloudflare settings)  
- Broken access control (RBAC, user permissions)  
- Code execution vulnerabilities

Note: Security reports for **custom implementations** built using KeelStack are out of scope; we only cover the **Core Template logic (authentication, authorization, billing, and infrastructure scaffolding)**

### ❌ Out of Scope

- Issues in third‑party dependencies (please report to the respective maintainers)  
- Theoretical attacks without proof of concept  
- Social engineering, phishing, or physical attacks  
- Denial‑of‑service attacks  
- Automated tooling reports without manual verification  

---

## 🛡️ Safe Harbor

We will not pursue legal action against security researchers who discover and report vulnerabilities responsibly and in good faith, in accordance with this policy.

---

## 🤝 Acknowledgments

We believe in giving credit where it’s due. If you are the **first** to report a unique, valid security issue, we will:

- Give you **public credit** in our release notes (unless you prefer to remain anonymous).  
- Grant you a **complimentary Premium License** (scope and duration determined at our discretion) to our latest SaaS Starter Kits.

We may also include your name in our Release Notes (with your permission).

---

Thank you for helping us keep KeelStack and the indie hacking community safe. Together, we build better.

**– The KeelStack Team** ⚓
