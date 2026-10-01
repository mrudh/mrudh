<div align="center">

# Hi, I'm Mrudhulaa 👋

### Frontend & Full Stack Software Engineer | 6+ Years Experience | MSc Advanced Software Engineering, University of Leicester

![Open to Work](https://img.shields.io/badge/Open%20to%20Work-Frontend%20%7C%20Full%20Stack%20Roles-brightgreen?style=for-the-badge)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mrudhulaa-pv/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mrudh)

</div>

---

## About Me

I started out in Electrical and Electronics Engineering, then moved into software because I wanted to build the systems that actually run on the hardware I was studying rather than just the hardware itself. That shift has shaped how I work: I care as much about *why* something works as whether it does.

Over 6+ years at **McAfee** and **Cognizant**, I've built and shipped production frontend and full stack systems using React, Angular, Vue, and Node.js, with a strong focus on accessibility (WCAG) and test coverage (Jest, Cypress). I'm currently completing an **MSc in Advanced Software Engineering** at the University of Leicester, where I'm building an AI-powered platform from the ground up as my dissertation project.

I'm actively looking for **Frontend Engineer** or **Software Engineer** roles where I can bring that mix of production experience and hands-on AI/ML curiosity.

---

## Core Competencies

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![WCAG](https://img.shields.io/badge/Accessibility-WCAG-blue?style=flat-square)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Testing & Quality**

![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-17202C?style=flat-square&logo=cypress&logoColor=white)

**Cloud & Tools**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![JIRA](https://img.shields.io/badge/JIRA-0052CC?style=flat-square&logo=jira&logoColor=white)

**Certifications:** Azure Fundamentals · Azure AI Fundamentals · PG Diploma in Data Science and Business Analytics (UT Austin)

---

## Featured Projects

### 🏠 [HomifyOne - AI-Powered Personalization and Workflow Management Platform for Residential Developments](https://github.com/mrudh/HomifyOne)

- **Four distinct user roles** (buyer, developer, supplier, admin) with server-side role-based access control enforced on every route, plus ownership-level checks so a developer can only act on their own plots and a supplier only on their own orders, not just role checks alone.
- **AI recommendation engine** built on FAISS vector search and sentence-transformer embeddings, scoring the product catalog against each buyer's questionnaire answers in a three-pass fallback, so buyers always get relevant results even with narrow filters.
- **AI buyer assistant** powered by Gemini, with its own retrieval step over products and FAQs, a defensive system prompt that treats all retrieved/user data as untrusted input, and regex-based prompt-injection detection before any message reaches the LLM.
- **Automated end-to-end order workflow**: approving a buyer's selections auto-generates a PDF summary, splits line items into separate purchase orders per supplier, and notifies every affected party in real time.
- **Real-time messaging and notifications** via Socket.IO, with a relationship-derived contact list, buyers, developers and suppliers can only message people they actually have an active order relationship with, not an open directory.
- **AI-assisted invoice processing**: suppliers upload invoices to S3, and a Gemini-backed extraction endpoint summarises each one and flags amount mismatches against the original purchase order automatically.
- **Secure file handling throughout**: all uploads (invoices, chat attachments, floor plans) are stored privately in S3 and only ever exposed via short-lived, time-limited signed URLs, never public links.
- **Budget-aware checkout logic** that tracks a plot's fixed extras allowance against both prior approved spend and the live basket total, added without touching any of the existing, already-tested pricing calculations.
- **Thoroughly tested**: 380+ automated test cases across four frameworks (Jest, Vitest, React-Testing-Library, pytest, Playwright), including real-database and real-HTTP integration tests, not just mocks.

### 🗳️ [MSLR (My Shangri La Referendum) - Full-Stack Referendum Management Platform](https://github.com/mrudh/MSLR-project) 

A full-stack **MERN** application for running referendums, with fully separate Voter and Election Commission experiences.

- Built separate **Voter** and **Election Commission** dashboards with distinct permissions and views
- Implemented **JWT-based authentication** with role-based authorization and bcrypt password hashing
- Built a **QR code scanning** flow for secure voter check-in
- Delivered results visualization using **Chart.js** (bar/donut charts) and a custom **word cloud** view for standout voting options
- Exposed a **public open-data REST API** for referendum results (`/mslr/referendums`, `/mslr/referendum/:id`)
- Backed by **MongoDB Atlas** with Mongoose schemas across voters, referendums, options, votes, and audit history

**Stack:** React (Vite), React Router, Axios, Bootstrap, Chart.js, Node.js, Express.js, JWT, bcrypt, MongoDB Atlas, Mongoose

---

## Other Projects

- **[food-delivery-app](https://github.com/mrudh/food-delivery-app)** — React app consuming the Swiggy API, with restaurant search, filtering by rating, and detail/menu pages
- **[shopping-cart](https://github.com/mrudh/shopping-cart)** — React shopping cart with product search/filtering and a full cart flow
- **[mini-store](https://github.com/mrudh/mini-store)** — React storefront focused on state management with the Context API
- **[pagination-project](https://github.com/mrudh/pagination-project)** — React product listing app with API-driven, client-side pagination

---

## Let's Connect

📫 Reach me on [LinkedIn](https://www.linkedin.com/in/mrudhulaa-pv/) — I'm actively interviewing for Frontend and Software Engineer roles and always happy to talk shop about React, accessibility, or applied AI.
