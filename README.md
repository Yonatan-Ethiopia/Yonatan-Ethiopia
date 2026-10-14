# Yonatan Ethiopia

I am a Full-Stack backend-focused developer building APIs, production features, automation tools, and systems software.

Currently working with Go, Python, TypeScript, and Rust. I enjoy figuring out how systems behave under real conditions, from database queries and access control to concurrency and deployment.

[Projects](#featured-projects) · [Tech Stack](#tech-stack) · [Currently Learning](#currently-learning) · [Contact](#contact)

---

## Featured Projects

### [tnylinks](https://github.com/Yonatan-Ethiopia/linkshortener)
**Deployed URL shortener**

A URL shortener with Google OAuth, custom slugs, and a link management dashboard.

- Base62 ID encoding for direct database lookups
- Redis-based fixed-window rate limiting
- Server-side ownership checks to prevent IDOR vulnerabilities
- Deployed with PostgreSQL, nginx, and a Linux VPS

**Stack:** Python, FastAPI, PostgreSQL, Redis, SQLModel, Alembic, htmx

[Live demo](https://tnylinks.ethiodeploy.com)

### [AI Video Dubbing Pipeline](https://github.com/Yonatan-Ethiopia/live-translator)
A video processing pipeline that transcribes speech, translates content, generates dubbed audio, and produces timestamped subtitles.

- Audio extraction and processing with FFmpeg
- Speech recognition using Whisper
- Job status tracking with SQLite
- Automated coordination of processing stages

**Stack:** Python, FastAPI, FFmpeg, Whisper

### [RBoard](https://github.com/Yonatan-Ethiopia/rboard)
A lightweight native clipboard manager written in Rust.

- Native desktop interface
- Persistent clipboard history
- SQLite-backed storage

**Stack:** Rust, egui, rusqlite

### [Go vs. Rust Concurrency Benchmark](https://www.reddit.com/r/rust/)
A technical investigation into a misleading concurrency benchmark, tracing the discrepancy to page-cache behavior and comparing the results against cold-cache disk I/O.

The write-up received 500+ upvotes on r/rust.

---

## Experience

**ERP Full-stack Developer Intern | HEMIN Business PLC**

*August 2026 – October 2026*

- Built the Finance & Accounting module for a production ERP used by a live client.
- Designed the module's implementation plan and Prisma schema before development.
- Worked on petty cash, voucher approvals, replenishment, cash counts, reconciliation, and employee advances.
- Developed with mandatory senior-engineer pull request reviews.

**Backend Development Intern | CodeAlpha**

*August 2026 – September 2026*

- Built a job board backend with employer and candidate accounts, job listings, search filters, applications, and resume uploads.
- Implemented authentication using JWT and Passport.
- Built a URL shortener backend with persistent storage and redirect handling.

[Job Board Platform](https://github.com/Yonatan-Ethiopia/codealpha_tasks/tree/main/job_board_platform) · [URL Shortener](https://github.com/Yonatan-Ethiopia/codealpha_tasks/tree/main/url-shortener)

---

## Tech Stack

**Languages**

TypeScript, JavaScript, Python, Go, Rust, SQL

**Backend**

Node.js, Express, NestJS, FastAPI, REST APIs, Prisma, SQLModel, JWT, OAuth2

**Databases & Infrastructure**

PostgreSQL, Redis, SQLite, Docker, Linux, nginx, DNS, Git

**Frontend**

React, Next.js, htmx, HTML, CSS

---

## Currently Learning

- Go and Rust internals
- Database internals and query performance
- Distributed systems and system design
- Networking and asynchronous architecture
- Concurrency and resource management

---

## Contact

- **GitHub:** [Yonatan-Ethiopia](https://github.com/Yonatan-Ethiopia)
- **LinkedIn:** [Yonatan Ethiopia](https://www.linkedin.com/in/yonatan-ethiopia-67b4963a5/)
- **Email:** yonatanethiopia1@gmail.com

---

I prefer software that solves a real problem, behaves predictably, and doesn't need an entire ecosystem just to do one thing.
