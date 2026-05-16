# 💫 About Me:
Hi, I'm Dushyant! 👋 I'm a Computer Science student (6th Semester) at IIIT Manipur, focused on backend development and building production-grade full-stack systems.

- 🔭 Recently Shipped: **UniTrade** — a campus-scoped C2C marketplace with three production AI subsystems: a Weighted Jaccard Similarity discovery engine with temporal decay, a category-specific depreciation valuation engine, and a cascading Gemini Vision → Gemini Text → rule-based AutoTagger pipeline.
- 💻 Also Built: **Fintrace** — an audit-grade double-entry financial ledger API with a 10-step ACID transaction pipeline, immutable Mongoose pre-hooks, layered Redis rate limiting, and idempotent transfer semantics.
- 🌱 Currently Exploring: System design, DSA, and internship prep for backend/full-stack roles.
- 🚀 Stack: **Node.js, Express.js, React, MongoDB, Redis, Socket.io, Google Gemini, JWT**

## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/dushyant_6) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/dushyant06) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:dushyantyaduvanshi51@gmail.com)

---

# 🚀 Projects

### [UniTrade](https://unitrade-1-6oct.onrender.com/register) — Campus C2C Marketplace
> A campus-scoped C2C marketplace with three production AI subsystems: discovery, valuation, and auto-tagging

- **Discovery Engine:** 3-phase content-based recommendations using Weighted Jaccard Similarity with time-decayed click history ($w = 0.95^d$), solving the cold-start problem for a 1,500-user closed campus
- **AI AutoTagger Pipeline:** Cascading fallback chain (Gemini Vision → Gemini Text → rule-based) guaranteeing 100% valid taxonomy output across 11 categories
- **Valuation Engine:** Category-specific depreciation model ($P_{fair} = P_{orig} \times (1-r)^A \times c$) that auto-suggests resale prices at listing creation
- **Real-Time Chat:** Socket.io virtual rooms per conversation with live typing indicators and MongoDB aggregation for full history retrieval
- **Testing:** 33/33 Jest unit tests and 8/8 black-box API tests across all three algorithmic modules

`Node.js` `Express.js` `React` `MongoDB` `Socket.io` `Google Gemini` `Cloudinary` `JWT` `Jest`

---

### [Fintrace](https://fintrace-4ltx.onrender.com/api-docs/) — Audit-Grade Financial Ledger API
> A tamper-proof double-entry financial API with ACID transaction guarantees and idempotent transfer semantics

- **Immutable Double-Entry Ledger:** 8 Mongoose pre-hooks block all mutation operations; every transfer produces permanent, unalterable DEBIT/CREDIT pairs — balances derived from ledger aggregation, never stored directly
- **ACID Transaction Pipeline:** 10-step transfer flow (validate → idempotency check → PENDING → debit → credit → COMPLETED → commit) using MongoDB sessions with automatic rollback on failure
- **Layered Rate Limiting:** Two independent Upstash Redis limiters — IP-keyed on auth routes to block credential stuffing, user-keyed on transaction routes post-auth
- **Idempotency:** Transfer endpoint handles all four terminal states (COMPLETED/PENDING/FAILED/REVERSED) with correct status per state, not blind rejection

`Node.js` `Express.js` `MongoDB` `Redis (Upstash)` `JWT` `Nodemailer` `Swagger`

---

# 💻 Tech Stack:
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=Dushyant0608&theme=dark&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=Dushyant0608&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Dushyant0608&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)
