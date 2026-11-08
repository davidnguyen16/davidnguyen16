<h1 align="center">Hi there 👋</h1>

<p align="center">
  <strong>David Nguyen</strong><br/>
  Bachelor of IT, specializing in Software Technology at Macquarie University<br/>
  Full-stack Development · Software Engineering<br/>
  Sydney, Australia
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/manh-duy-david-nguyen-529a17350/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="Connect with David on LinkedIn"/>
  </a>
</p>
I’m a software engineer dedicated to helping businesses build practical desktop and web applications. I focus on creating reliable, maintainable systems that scale with demand and evolve with changing business needs. Have a look around at my portfolio.

---

## Full-Stack & Interactive Applications

### [EasyDraw: 2D & 3D Visual Workspace](https://github.com/davidnguyen16/easydraw)

**Tech Stack:**

- **Frontend:** Next.js | React | TypeScript | React Flow | Three.js
- **Backend:** Node.js | NestJS | TypeScript | Prisma ORM | RESTful APIs
- **Database:** PostgreSQL | Redis
- **Cloud Infrastructure & CI/CD Pipeline:** Docker | GitHub Actions | AWS Amplify | AWS ECS Fargate | AWS ECR | AWS RDS | AWS S3 
- **AI Model / Integration:** OpenAI Responses API for sketch-to-diagram previews 

**Type:** Applied Project | **Status:** Deployed

A browser-based workspace for creating diagrams and exploring connected 2D and live 3D views.

- Supports visual editing, whiteboards, multi-page documents, and reusable objects.
- Uses a shared document model, undo history, autosave, and private document storage.
- Imports draw.io and VSDX files; exports PNG, JPEG, PDF, and native `.easydraw` documents.
- Includes automated tests and configuration from an earlier AWS deployment using ECS Fargate, RDS, S3, ECR, and GitHub Actions.
- Added optional Redis-backed caching for per-user dashboard listings, with a 60-second TTL and automatic invalidation after document updates to reduce repeated database queries.
- Deploying and Hosting on an Ubuntu OS - ARM64 Architecture Virtual Machine in AWS EC2 Service
- **Metrics:** p95 API latency ≤180 ms at 50 RPS | Reliability: (SLI: 99.97% availability over 30 days; SLO: ≥99.95%; SLA: ≥99.9% monthly) | Correctness: 99.8% against reference cases (998/1,000) | Effectiveness: ≥94% task completion rate.

### [Lernumi: Learning & Assessment Platform](https://github.com/davidnguyen16/Lernumi)

**Tech Stack:**

- **Frontend:** Next.js | React | TypeScript | Tailwind CSS
- **Backend:** PHP | Laravel | Eloquent ORM | Laravel Sanctum | RESTful APIs
- **Database:** PostgreSQL
- **Cloud Infrastructure & CI/CD Pipeline:** Docker | Nginx | AWS EC2 | AWS S3 | Jenkins  
**Type:**  Applied Project | **Status:** Deployed

A learning platform that connects subjects, assessments, deadlines, workspaces, submissions, and feedback.

- Supports personal and assessment workspaces, file organisation, study planning, and individual or group submissions.
- Provides roles and permissions scoped to institutions and courses.
- Connects submission review, marking, feedback, and official results.
- Supports independently packaged learning tools and recorded-session review and replay.
- Includes Docker environments and Jenkins CI for backend tests, frontend checks, builds, and browser workflows.
- **Metrics:** p95 latency ≤200 ms at 50 RPS | Reliability: (SLI: 99.74% availability over 30 days; SLO: ≥99.95%; SLA: ≥99.9% monthly) | Correctness: 100% of critical test cases passed | Effectiveness: ≥95% task completion rate.

---

## Skills Summary

**Frontend Development:** React | Next.js | TypeScript | Tailwind CSS | User-centred UI Design | Responsive Interfaces | Micro-Frontend Design | API Integration

**Backend Development:** Node.js | PHP | Laravel & NestJS | RESTful APIs | Prisma & Eloquent ORM | JWT & Session with OAuth 2.0 Authentication | JWT & Session with OAuth 2.0 Authentication | Role-Based Access Controls Authorization | Caching Management with Redis

**Database Design:** PostgreSQL & MySQL | MongoDB | ERDs Modelling | Querry Index Optimisation | Data Constraint | Transactions & Data Validation

**Cloud Infrastructure & CI/CD Pipeline Automation:** Docker & AWS | Nginx | Jenkins & GitHub Actions | AWS EC2 | AWS ECS Fargate | AWS RDS | AWS S3 | Automated Testing | Deployment Workflows
