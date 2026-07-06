# Hi, I'm Anuj 👋

Full-stack developer from Noida. I build web applications, work with APIs, and care about writing code that actually works in production — not just on localhost.

Currently wrapping up my B.Tech (ECE) at JSS Academy of Technical Education, Noida (graduating Jul 2026). I interned at Quizzard in early 2024 doing MERN stack work, and since then I've been building projects on the side while grinding DSA.

***

## What I work with

**Languages** — JavaScript, TypeScript, C++, SQL  
**Frontend** — React.js, Next.js, Tailwind CSS  
**Backend** — Node.js, Express.js, REST APIs, WebSockets  
**Databases** — MongoDB, PostgreSQL, Redis  
**DevOps/Cloud** — Docker, Git, Vercel, Render, AWS (basics — CCP certified)

***

## Projects

### Real-Time Collaborative Code Editor
A multiplayer code editor where multiple people can edit the same file simultaneously with live cursor positions and no merge conflicts.

The interesting part was getting the synchronization right — it's easy to broadcast changes, it's harder to make sure two people editing the same line at the same time don't corrupt each other's work. Ended up using an event-driven WebSocket architecture with room-based session management.

Supports 10+ simultaneous users. Sub-200ms latency on a single server.

- 🔗 [GitHub](https://github.com/AnujYadav-1915/sync-code-realtime-editor)
- 🌐 [Live](https://realtime-collaborative-code-editor-master.onrender.com/) *(free tier — may take ~30s to cold start)*

**Tech:** React, Node.js, Socket.io, WebSockets, Docker

***

### LearnMate – AI Career Platform
Built an AI-powered SaaS platform that gives users automated resume feedback and mock interview practice.

Integrated OpenAI's API for the analysis part. Backend is Next.js API routes with PostgreSQL (Neon) for persistence, JWT + RBAC for auth. Deployed on Vercel with GitHub Actions for CI/CD.

Currently at 40+ users. Not millions — but it's real, I can log into the DB and count them.

- 🔗 [GitHub](https://github.com/AnujYadav-1915/Learnmate)
- 🌐 [Live](https://anuj-kumar-ai-career-coach.vercel.app/)

**Tech:** Next.js, Node.js, PostgreSQL, OpenAI API, GitHub Actions

***

### Vynkify – URL Shortener
High-throughput URL shortener with analytics. The main challenge here was the redirect speed — every millisecond counts since users are mid-flow when they click a short link.

Used Redis for caching hot links (the ones that get clicked frequently). Implemented Base62 collision-safe ID generation. Built an analytics dashboard that tracks click trends.

Handles 50+ monthly redirects currently. Latency improved ~10% after adding Redis layer compared to direct DB lookups.

- 🔗 [GitHub](https://github.com/AnujYadav-1915/URL-Shortener)
- 🌐 [Live](https://frontend-rust-ten-44.vercel.app/)

**Tech:** Node.js, Express, Redis, MongoDB

***

## Experience

**Software Development Intern — Quizzard** *(Jan 2024 – Mar 2024, Remote)*

Worked on their MERN stack platform. My main contributions:
- Added lazy loading + API batching that cut page load by ~10%
- Built REST API endpoints + MongoDB schemas for a new quiz module
- Refactored React components across 6 pages to reduce duplication
- Worked through Git PRs and Agile sprints — delivered 8+ features

***

## Certifications

- **AWS Certified Cloud Practitioner** — [verify on Credly](https://www.credly.com)
- **FreeCodeCamp (5x):** Responsive Web Design · JS Algorithms & Data Structures · Front End Libraries · Back End Dev & APIs · Quality Assurance

***

## DSA / CP

500+ problems solved across LeetCode, CodeChef, and GeeksforGeeks.

Mostly focused on arrays, graphs, DP, and sliding window patterns. LeetCode handle: [AnujxPhoenix](https://leetcode.com/u/AnujxPhoenix/)

***

## Currently working on

Improving the LearnMate interview simulation feature — right now it's basic Q&A, want to add adaptive difficulty and proper scoring rubrics.

***

## Connect

- [LinkedIn](https://www.linkedin.com/in/anuj-kumar-918415295/)
- [Portfolio](https://anujyadav-1915.github.io/updated-portfolio-website/)
- [LeetCode](https://leetcode.com/u/AnujxPhoenix/)
