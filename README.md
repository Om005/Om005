<div align="center">
  <h1>Om Chavda</h1>
  <p>Focused on backend engineering and system design | Final Year B.Tech ICT @ DAU</p>

  <br/>

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/om-chavda-06a390302/)
  [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chavdaom84@gmail.com)
  [![GitHub](https://img.shields.io/badge/GitHub-111111?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Om005)
  [![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/chavdaom84/)
  [![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/Om_007)
  [![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/chavdaom84)

</div>

---

## About Me

- B.Tech Student in Information and Communication Technology (ICT) at Dhirubhai Ambani Institute of Information and Communication Technology (DA-IICT), Gandhinagar (Aug 2023 - Present) — CGPA: 8.64
- Backend Engineer & Full Stack Developer with a passion for architecting secure, scalable APIs, and system design.
- 2100+ algorithmic problems solved across LeetCode, and Codeforces.


## Featured Projects

### Dokit — Cloud-Native Collaborative IDE
[![GitHub](https://img.shields.io/badge/GitHub-Repository-111111?style=flat-square&logo=github&logoColor=white)](https://github.com/Om005/Dokit)
[![Live Demo](https://img.shields.io/badge/Live-dokit--ide.vercel.app-00C853?style=flat-square&logo=vercel&logoColor=white)](https://dokit-ide.vercel.app)

*A cloud-native development platform provisioning isolated Linux workspace containers in the browser, complete with real-time multiplayer coding, dynamic HTTP routing, and a repository-aware AI assistant.*

- **Tech Stack:** Next.js 16 (App Router), Express 5, PostgreSQL (Prisma ORM), Redis, TypeScript, Docker Engine API, Yjs, CodeMirror 6, Socket.IO, BullMQ, Cloudflare R2, Nginx, Tailwind CSS 4.
- **Key Features:**
  - **On-Demand Linux Sandboxes:** Dynamic provisioning of isolated container environments running restricted permissions under non-root users.
  - **Multiplayer Collaboration:** Low-latency collaborative code editing powered by Yjs CRDTs, CodeMirror 6, and WebSocket cursor tracking.
  - **Bidirectional Filesystem Sync:** Background sync framework using Linux `inotify`, Socket.IO, and BullMQ to sync changes to Cloudflare R2.
  - **Project-Aware RAG (ASTra):** Codebase search and explanation using pgvector, local Ollama embeddings (`nomic-embed-text`), and MMR re-ranking.
  - **Dynamic Networking:** Wildcard subdomain routing via Nginx (`[port]-[projectId].dokit.backends.live`) for instant dev-server preview.
  - **Hardened Security:** Built-in TOTP 2FA, JWT access token rotation, MaxMind GeoIP session auditing, and Redis rate limiting.

---

### Ingenium — Autonomous Local AI Coding Partner
[![GitHub](https://img.shields.io/badge/GitHub-Repository-111111?style=flat-square&logo=github&logoColor=white)](https://github.com/Om005/Ingenium)

*An intelligent local developer AI assistant and autonomous coding companion running on CLI and Telegram, enabling remote codebase orchestration and secure approvals.*

- **Tech Stack:** Node.js, SQLite (Drizzle ORM), Telegram Bot API, OpenRouter, Tavily Search, TypeScript.
- **Key Features:**
  - **Agent Mode:** Autonomous execution of staged actions (filesystem modifications, git commands, shell scripts) requiring inline manual authorization.
  - **Plan Mode:** Structured execution engine that drafts implementation steps in `ingenium-plan.md` for developers to review, edit, and execute.
  - **Telegram Bot Control:** Manage active workspace sessions, view graphical file diffs, and approve/reject actions remotely via interactive callback buttons.
  - **Transient Sessions:** Secure, `/temporary` mode that runs without saving prompt logs or chat history to the local machine.
  - **Developer Tools:** Complete built-in suite for file manipulations, git history auditing, Tavily web search, custom cron reminders, and token count analytics.

---

### PayNest — Online Payment & P2P Transfer App
[![GitHub](https://img.shields.io/badge/GitHub-Repository-111111?style=flat-square&logo=github&logoColor=white)](https://github.com/Om005/paynest)

*A secure peer-to-peer payment platform integrating the Razorpay SDK, NextAuth, and automated transaction analytics.*

- **Tech Stack:** Next.js 15, Tailwind CSS, NextAuth (Google OAuth), Razorpay SDK, MongoDB (Mongoose), Radix UI.
- **Key Features:**
  - **Secure P2P Transfers:** Native Razorpay integration enabling active users to send and receive payments with custom transaction notes.
  - **Credential Security:** Google OAuth via NextAuth with secure account activation requiring encrypted Razorpay credentials to accept payments.
  - **Smart Contact Management:** Customizable contact lists featuring a dynamic filter showing contacts with transaction activity in the last 2 days.
  - **Transaction Auditing:** High-speed dashboard filtering and multi-field search (by receiver name, email, or transaction message text).


## Technical Skills

<table>
  <tr>
    <td valign="top" width="25%">
      <b>Languages</b><br/><br/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" /><br/>
      <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
    </td>
    <td valign="top" width="25%">
      <b>Frontend</b><br/><br/>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" /><br/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Radix_UI-151718?style=flat-square&logo=radixui&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
    </td>
    <td valign="top" width="25%">
      <b>Backend & Databases</b><br/><br/>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Prisma_ORM-2D3748?style=flat-square&logo=prisma&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black" />
    </td>
    <td valign="top" width="25%">
      <b>Tools & DevOps</b><br/><br/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" /><br/>
      <img src="https://img.shields.io/badge/Render-000000?style=flat-square&logo=render&logoColor=white" />
    </td>
  </tr>
</table>


## Education

- **Dhirubhai Ambani Institute of Information and Communication Technology (DA-IICT)**, Gandhinagar, Gujarat
  - B.Tech in Information and Communication Technology, CGPA: 8.64 *(Aug 2023 - Present)*
- **B.N. Virani Higher Secondary School**, Bhavnagar, Gujarat
  - Higher Secondary Certificate (GSEB), Score: 99.21 %ile *(Jun 2021 - Jun 2023)*


## Key Achievements

- 2nd Prize in Winter of Code 7.0 at MSTC DA-IICT (65+ participants).
- 427th Rank in the Amritapuri region in the ICPC 2025 Preliminary Round.
- Global Rank 108 in CodeChef Starters 174 Div.3.
- Global Rank 716 in LeetCode Biweekly Contest 151 (out of 29K+ participants).
- 1100+ LeetCode problems solved with a peak rating of 2039 (Knight).
- 940+ Codeforces problems solved with a peak rating of 1438 (Specialist).


## Competitive Programming

<div align="center">
  
  <div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
  <a href="https://leetcode.com/u/chavdaom84/">

<img src="https://leetcard.jacoblin.cool/chavdaom84?theme=dark&font=Inter&ext=contest" width="400" alt="LeetCode stats" />
  </a>
  <a href="https://codeforces.com/profile/Om_007">
    <img src="https://codeforces-readme-stats.vercel.app/api/card?username=Om_007&theme=dark" alt="Codeforces Stats" height="190" />
  </a>
  </div>
</div>

## Github

<div align="center">
  
  <div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
    <a href="https://github.com/Om005">
    <img src="https://github-readme-stats-fast.vercel.app/api?username=Om005&show_icons=true&theme=dark&title_color=00e5ff&icon_color=00e5ff&border_color=21262d&bg_color=0d1117" alt="Om005's GitHub stats" height="190" />
  </a>
  <a href="https://github.com/Om005">
    <img src="https://github-readme-stats-fast.vercel.app/api/top-langs?username=Om005&layout=compact&theme=dark&title_color=00e5ff&icon_color=00e5ff&border_color=21262d&bg_color=0d1117" alt="Top Languages" height="190" />
  </a>
  
  </div>
</div>
