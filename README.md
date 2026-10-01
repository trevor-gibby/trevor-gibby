# Hi, I'm Trevor 👋

**Senior Full-Stack Engineer & Hands-On Technical Lead**

I build and modernize full-stack systems across product, platform, integrations, and infrastructure — with a focus on turning fragile workarounds and legacy constraints into practical, reusable systems.

I'm currently a Senior Software Engineer and Team Lead at Ninthroot, where I lead a four-engineer team while remaining hands-on with architecture, feature development, integrations, platform modernization, and production support.

## What I Work On

- **Pragmatic modernization** — improving established systems without assuming a rewrite is the answer
- **Reusable product capabilities** — replacing repetitive implementation work and one-off fixes with maintainable systems
- **Full-stack architecture** — working across frontend, backend, databases, integrations, infrastructure, and delivery
- **Technical leadership** — improving engineering processes, tooling, documentation, mentoring, and architectural decision-making
- **Business-aware engineering** — balancing performance, complexity, cost, maintainability, and actual user needs

## Selected Engineering Work

### Reusable CMS Component Engine

Designed and built a component system for a legacy PHP CMS after identifying repeated implementation patterns that weren't well served by the existing architecture.

The system included component definitions, structured content data, conditional rendering, editor tooling, and reusable templates — without introducing a new frontend runtime into the legacy platform.

**Result:** approximately **50% faster site implementation** and adoption as the primary implementation approach for new projects across the engineering team.

### Platform Modernization

I help maintain and incrementally modernize a business-critical custom PHP MVC platform rather than treating legacy code as something that must be replaced wholesale.

Recent work has included:

- Leading PHP 7.3 → PHP 8+ migration efforts
- Standardizing dozens of controllers and views around reusable patterns
- Introducing more structured data-access architecture
- Improving developer tooling and documentation
- Building agent-ready engineering instructions for AI-assisted development

### Business Continuity & Cloud Infrastructure

After a major hosting-provider outage exposed a resilience gap, I helped establish an emergency recovery process and then designed a more sustainable continuity system.

The resulting architecture uses **Node.js, AWS EventBridge, Step Functions, Lambda, SNS, APIs, and automated DNS workflows** to maintain lightweight backup experiences while keeping infrastructure costs to only a few dollars per month.

### Performance Engineering

Built and benchmarked a Redis caching proof of concept that reduced representative page-load times from roughly **3 seconds to 0.1 seconds**.

The infrastructure required to deploy it wasn't economically justified, so I recommended a lower-cost alternative rather than pushing the technically faster solution into production.

Sometimes the right engineering outcome is proving what *not* to build.

## Current Independent Projects

### Operations Platform

I'm rebuilding an operations platform originally created as an academic capstone, using the project to explore modern product architecture and AI-assisted software development.

**Current stack:**

`Next.js` · `TypeScript` · `React` · `Prisma` · `PostgreSQL`

The platform models operational workflows for organizations managing multi-location clients, including:

- Hierarchical accounts and sub-accounts
- Contacts associated with multiple organizations
- Custom fields and event history
- Scope-based access control
- User and team management
- Gmail integration

It's an independent, in-progress prototype and a chance to revisit an older product idea with several more years of production engineering experience behind me.

### Capaxle

I'm building an open-source TypeScript backend framework around **capabilities**: application operations defined once and exposed through HTTP APIs, CLI commands, and MCP tools for AI agents.

The goal is to keep business logic, typed contracts, and access policies together while giving different callers ways to use the same operation.

**Current stack:**

`TypeScript` · `Node.js` · `Zod`

The published alpha includes:

- Capability definitions with typed input and output schemas
- A shared runtime for validation and policy enforcement
- HTTP, CLI, and MCP adapters
- Generated OpenAPI contracts, JSON Schemas, and documentation
- Generated TypeScript SDKs

It's an independent project exploring reusable backend architecture and how applications can serve both traditional clients and AI agents. Alpha packages are available on npm, with APIs continuing to evolve.

[Repository](https://github.com/trevor-gibby/capaxle) · [Getting started](https://github.com/trevor-gibby/capaxle#getting-started)

## Technologies

**Languages**  
PHP · TypeScript · JavaScript · Python · SQL

**Frontend**  
React · Next.js · Vue · HTML · CSS · SCSS

**Backend**  
Node.js · Express · PHP MVC · REST APIs

**Data**  
PostgreSQL · MySQL / MariaDB · MongoDB · Redis · Prisma

**Cloud & Infrastructure**  
AWS · Lambda · Step Functions · EventBridge · S3 · EC2 · RDS · DynamoDB · Docker · Vercel

**Engineering**  
System Design · API Integrations · Automated Testing · CI/CD · Performance Optimization · Legacy Modernization · Technical Leadership

## How I Approach Engineering

I tend to gravitate toward problems where the obvious solution isn't necessarily the right one.

That might mean introducing a reusable abstraction instead of repeating implementation work, incrementally modernizing a legacy platform instead of rewriting it, prototyping a performance improvement before paying for infrastructure, or building a small operational tool that removes an engineering dependency for someone else.

The goal isn't to use the newest technology.

The goal is to build the simplest system that solves the real problem well and can continue evolving afterward.

## Find Me

🌐 [trevorgibby.dev](https://www.trevorgibby.dev/)

I'm currently exploring **Senior Full-Stack Engineer, Senior Software Engineer, Lead Software Engineer, and hands-on Technical Lead** opportunities involving product/platform ownership, modernization, integrations, or practical AI-enabled development.

<!---
trevor-gibby/trevor-gibby is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
