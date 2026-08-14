<div align="center">

# Om Kesharwani

### Software Engineer · Full-Stack Developer · Open-Source Contributor

<p>
  <a href="https://www.linkedin.com/in/omkesharwanidev/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:kesharwanio685@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://leetcode.com/u/om_kesharwani/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" /></a>
  <a href="https://codeforces.com/profile/om_kesharwani/"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=flat-square&logo=codeforces&logoColor=white" /></a>
  <a href="https://github.com/Om-Beast"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>

</div>

<br/>

## About

B.Tech in Smart Manufacturing at IIIT Design and Manufacturing, Jabalpur (2023–2027). I build full-stack systems with real backend logic — authentication, authorization, business rules, and API design — and contribute to open-source projects in the CNCF cloud-native ecosystem, primarily around **Meshery**.

**Currently:**

- Contributing to `Meshery` and `Meshery Schemas` within the CNCF ecosystem
- Studying the design space for a **Meshery MCP Server** — MCP, Go, and Meshery's REST/GraphQL APIs for safe, read-only cloud-native tooling
- Building `FleetFlow` and `QuickAI` — two full-stack products with meaningful backend design
- Solving DSA problems across LeetCode, Codeforces, and CodeChef

<br/>

## Tech Stack

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Redux](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & Infra**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Foundations:** Data Structures & Algorithms · OOP · System Design · DBMS · Operating Systems · Linux

<br/>

## Open Source & CNCF

I contribute to real, in-production repositories rather than tutorial projects — bug fixes, feature implementation, API/schema changes, documentation, and test improvements, through the standard workflow of issues, PRs, and maintainer review.

| Repository | Area |
|---|---|
| **Meshery** | CNCF cloud-native management plane |
| **Meshery Schemas** | Schema definitions powering Meshery's API surface |
| **Vaar** | Feature work & fixes |
| **Konfuse** | Feature work & fixes |
| **Agent-Sweep** | Feature work & fixes |
| **MCPSnoop** | Feature work & fixes |
| **Kana-Dojo** | Feature work & fixes |

Across these, I have multiple merged pull requests and have worked directly with maintainers on review feedback.

<table>
<tr>
<td width="90">
<a href="https://cloud.layer5.io/user/63af1c66-8ade-4ec8-9732-b56eeb122572?tab=badges&badge=first-design">
<img width="70" src="https://badges.layer5.io/assets/badges/first-design/first-design.png" alt="Meshery Design Pioneer" />
</a>
</td>
<td>
<strong>Meshery Design Pioneer</strong> — awarded by Layer5 / CNCF Meshery for design contribution.<br/>
<sub><a href="https://cloud.layer5.io/user/63af1c66-8ade-4ec8-9732-b56eeb122572?tab=badges&badge=first-design">View badge →</a></sub>
</td>
</tr>
</table>

**Meshery MCP Server — in exploration:** studying how to expose Meshery's REST/GraphQL APIs and MeshSync topology data as read-only MCP resources over stdio and streamable HTTP, without exposing secrets. A natural extension of my Meshery contribution work — not something I've shipped yet.

<br/>

## Featured Projects

### FleetFlow — Fleet Rental & Booking Platform
**Repo:** [Om-Beast/RentX](https://github.com/Om-Beast/RentX)

![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![JWT](https://img.shields.io/badge/-JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

A backend-heavy rental and fleet management platform with role-based access for customers, fleet owners, and admins.

- JWT authentication with role-based access control (RBAC) across three user roles
- End-to-end booking workflows with conflict detection and vehicle availability management
- A rule-based **Trust Score Engine** scoring users on payment history, booking completion, cancellations, and account activity to drive risk-aware booking decisions
- Dynamic pricing and automated email/in-app notifications
- Modular service architecture with request validation and audit logging across REST APIs

### QuickAI — Multi-Feature AI SaaS Platform

![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Clerk](https://img.shields.io/badge/-Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)

A product built around AI-assisted workflows, with the engineering focus on the system around the model rather than the model call itself.

- Secure authentication and user management via Clerk
- Modular backend APIs for content generation, document summarization, and image generation
- Persistent workspace history and prompt management backed by PostgreSQL
- Reusable React components with optimized Next.js rendering and API interaction

<br/>

## GitHub Activity

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=Om-Beast&show_icons=true&theme=default&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Om-Beast&layout=compact&theme=default&hide_border=true" />
</div>

<br/>

## Competitive Programming

- **Codeforces Specialist** — AIR 1066 in Codeforces Round 1086 (Div. 2)
- **CodeChef 2-star** programmer
- **900+** problems solved across LeetCode, Codeforces, and CodeChef
- Cleared the online assessment round of **HackWithInfinity**

<br/>

## Connect

<p>
  <a href="https://www.linkedin.com/in/omkesharwanidev/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:kesharwanio685@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/Om-Beast"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>
