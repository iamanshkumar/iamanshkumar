## Ansh Kumar
**Backend / Full-Stack Engineer** — Node.js · FastAPI · Next.js · TypeScript
 
I build backend systems around real constraints: role-based access, concurrent writes, graph algorithms and security hardening. Final-year B.Tech CS (Data Science) student, graduating June 2027, looking for SDE / backend roles.
 
Solved 600+ LeetCode problems in Java · Contest rating 1939 · Top 3.62%
 
---
 
### Projects
 
**MuleNet: Financial Forensics Engine**
Fraud-detection platform that flags money-mule rings in transaction ledgers. Built with a team of 3 at a hackathon.
`FastAPI` `React 19` `Express` `MongoDB Atlas`
- Cut cycle-detection time 80x by splitting the transaction graph into Strongly Connected Components before running Johnson's algorithm
- Combined five detectors (cycles, Benford's Law, smurfing, centrality, false-positive filtering) and a GraphSAGE anomaly score into one 0–100 suspicion score per account
- 3-tier architecture: FastAPI scoring service, Express API, React 19 dashboard
[Repository](#) · [Live](#)
 
**BookMyEvent: Event Booking Platform**
Full-stack booking platform with separate attendee, organizer and admin dashboards.
`Next.js` `TypeScript` `Prisma` `MySQL`
- Enforced role-based access in middleware on every route
- Booking flow: tiered tickets with seat limits, fixed/percentage coupons with per-user limits, tax calculation, and cancellations that release seats back to inventory
- Organizer/admin tools: bulk CSV import/export, email verification, and an admin panel for email, CAPTCHA and maintenance mode
[Repository](#) · Live deployment coming soon
 
**Campus Eye: Placement Tracking Platform**
Placement platform with role-based access for students and administrators.
`MongoDB` `Express` `React` `Node.js`
- Built atomic voting (`$addToSet` / `$pull`) and cascading-deletion pipelines to eliminate race conditions on concurrent writes
- Secured auth with JWT in httpOnly cookies, TTL-indexed OTPs, and rate limiting against brute force
- Escaped user input in search filters to block ReDoS attacks
- Cut frontend data-retrieval latency by 40% with a debounced filtering engine
[Repository](#) · [Live](#)
 
---
 
### Technical Skills
 
| | |
|---|---|
| **Languages** | Java, TypeScript, JavaScript (ES6+), Python, SQL |
| **Frameworks / Libraries** | Node.js, Express, Next.js, React, FastAPI, Prisma, Tailwind CSS |
| **Cloud / DevOps** | Vercel, MongoDB Atlas |
| **Databases** | MongoDB, MySQL |
| **Tools** | Git/GitHub, Postman|
| **Core CS** | DSA, OOP, DBMS |
 
---
 
### Contact
 
[LinkedIn](https://linkedin.com/in/anshkumar46) · [LeetCode](http://leetcode.com/iamanshkumar)
 
