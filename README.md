<div align="center">
<img src="assets/banner.svg" alt="Awesome Data API Platform Banner" width="100%">
<br>

<a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a> <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

# 🚀 Awesome Data API Platform
</div>

## 🌟 Top Data API Platform Tools Ecosystem
**A Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Instant REST & GraphQL APIs on Databases, Auto-Generated Data Layers, Backend-as-a-Service Data APIs & Low-Code Backend Platforms*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data API Platforms**. These tools automatically expose secure, production-ready REST and/or GraphQL APIs from existing databases (or visual data models), often with authentication, authorization, real-time capabilities, and admin interfaces — dramatically accelerating backend development. ⚡

**Examples** include Hasura, PostgREST, DreamFactory, Supabase Data API, Xano, Nhost, 8base, Appsmith, Directus, and Fastgen (the category leaders and widely used platforms).

**Open-source emphasis**: This category is exceptionally strong in open source. The section below prioritizes mature, actively maintained projects that let you self-host instant data APIs on PostgreSQL, MySQL, and other databases with full control over schema, permissions, and infrastructure. 🛠️

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites / GitHub repos.

## 📑 Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)
- [Star History](#star-history)

## ☁️ SaaS/Hosted Platforms
| Platform | Description | Valuation (Est.) | Pricing (Starting Tier) | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Supabase](https://supabase.com/)** (Data API) | Open-source Firebase alternative whose core Data API is powered by PostgREST (REST) + pg_graphql. Hosted platform with auth, storage, realtime, and edge functions. | ~$10.5B | $25/month | 2 active projects, 500MB DB storage, 1GB file storage, 50k MAU |
| **[Hasura](https://hasura.io/)** | Instant GraphQL (and REST) APIs on databases with fine-grained authorization, real-time subscriptions, remote schemas, and Actions. Available as open-source engine + managed cloud. | ~$1.0B | $1.50/active hour | 3 projects, 3M API requests/month, 100MB data passthrough |
| **[Appsmith](https://www.appsmith.com/)** | Open-source low-code platform that includes strong API creation, integration, and internal-tool capabilities (often used alongside data APIs). | ~$100M+ (Est.) | $15/user/month | Maximum of 5 users on cloud |
| **[Directus](https://directus.io/)** (Cloud) | Instant REST & GraphQL APIs plus a beautiful admin app on any SQL database. Self-hosted open-source core with commercial cloud offering. | Private ($7M+ funding) | $99/month | No free cloud tier, Self-hosted version has no limits |
| **[Xano](https://www.xano.com/)** | No-code / low-code backend platform that generates production REST APIs from a visual data model, with business logic, auth, and background tasks. | ~$18.2M | $85/month | 1 workspace, 100,000 records, 1GB file storage |
| **[DreamFactory](https://www.dreamfactory.com/)** | Enterprise-focused platform that auto-generates secure REST APIs from 20+ databases and services, with role-based access control and on-premises options. | ~$2.7M ARR | $1,500/month | Open Source tier limited to 1 PostgreSQL connector |
| **[Nhost](https://nhost.io/)** | Open-source GraphQL backend (built on Hasura + PostgreSQL) offering auth, storage, functions, and real-time capabilities with a managed cloud option. | ~$2.0M | $25/month | 1 active project, 1GB database storage |
| **[Fastgen](https://fastgen.dev/)** (or similar rapid backend tools) | Emerging platforms focused on fast generation of data APIs and backend logic. | Acquired | $12/month | Flow runs limited by action blocks executed |
| **[8base](https://www.8base.com/)** | Low-code GraphQL backend and application platform with managed infrastructure, auth, and front-end tools. | Private | $25/month | Limited experimental capacity with community support |
| **[PostgREST](https://postgrest.org/)** (hosted offerings / managed services) | While primarily open-source, various managed and commercial wrappers exist around the PostgREST engine. | N/A (Open Source) | $25/month (via Supabase) | Dependent on host (e.g., Supabase offers 2 free projects limit) |

## 🔓 Open-Source GitHub Projects
- **[Supabase](https://github.com/supabase/supabase)** [![Stars](https://img.shields.io/github/stars/supabase/supabase?style=social&color=white)](https://github.com/supabase/supabase/stargazers)  
  Fully open-source Firebase alternative. Its Data API layer is built on PostgREST + pg_graphql, delivering automatic REST and GraphQL endpoints on PostgreSQL with auth, realtime, and storage.
- **[Strapi](https://github.com/strapi/strapi)** [![Stars](https://img.shields.io/github/stars/strapi/strapi?style=social&color=white)](https://github.com/strapi/strapi/stargazers)  
  Open-source headless CMS. It's 100% JavaScript, fully customizable and developer-first. It creates a Data API instantly based on your content types.
- **[Appwrite](https://github.com/appwrite/appwrite)** [![Stars](https://img.shields.io/github/stars/appwrite/appwrite?style=social&color=white)](https://github.com/appwrite/appwrite/stargazers)  
  Open-source backend-as-a-service with database APIs (REST), authentication, storage, functions, and real-time capabilities — broader than pure data APIs but frequently used in the same stack.
- **[Prisma](https://github.com/prisma/prisma)** [![Stars](https://img.shields.io/github/stars/prisma/prisma?style=social&color=white)](https://github.com/prisma/prisma/stargazers)  
  Next-generation Node.js and TypeScript ORM that auto-generates a type-safe data API layer for your databases.
- **[PocketBase](https://github.com/pocketbase/pocketbase)** [![Stars](https://img.shields.io/github/stars/pocketbase/pocketbase?style=social&color=white)](https://github.com/pocketbase/pocketbase/stargazers)  
  Single-binary open-source backend with embedded SQLite, automatic REST API, realtime, auth, and file storage — ideal for smaller projects and rapid prototyping.
- **[Hasura GraphQL Engine](https://github.com/hasura/graphql-engine)** [![Stars](https://img.shields.io/github/stars/hasura/graphql-engine?style=social&color=white)](https://github.com/hasura/graphql-engine/stargazers)  
  Blazing-fast, open-source engine that gives you instant GraphQL and REST APIs on PostgreSQL and other databases with built-in authorization, real-time subscriptions, and remote schema stitching.
- **[Directus](https://github.com/directus/directus)** [![Stars](https://img.shields.io/github/stars/directus/directus?style=social&color=white)](https://github.com/directus/directus/stargazers)  
  Flexible open-source data platform that wraps any SQL database with instant REST + GraphQL APIs, a powerful visual Studio, granular permissions, and extensibility.
- **[PostgREST](https://github.com/PostgREST/postgrest)** [![Stars](https://img.shields.io/github/stars/PostgREST/postgrest?style=social&color=white)](https://github.com/PostgREST/postgrest/stargazers)  
  The classic open-source tool that turns any PostgreSQL database into a fully RESTful API. Extremely performant, standards-compliant, and the foundation used by Supabase and many other platforms.
- **[RedwoodJS](https://github.com/redwoodjs/redwood)** [![Stars](https://img.shields.io/github/stars/redwoodjs/redwood?style=social&color=white)](https://github.com/redwoodjs/redwood/stargazers)  
  The App Framework for Startups. Brings React, GraphQL, Prisma, and more together in a full-stack framework with auto-generated data APIs.
- **[PostGraphile](https://github.com/graphile/postgraphile)** [![Stars](https://img.shields.io/github/stars/graphile/postgraphile?style=social&color=white)](https://github.com/graphile/postgraphile/stargazers)  
  High-performance, highly customizable open-source GraphQL API generator for PostgreSQL. Favored by teams that want deep GraphQL control and excellent performance.
- **[API Platform](https://github.com/api-platform/core)** [![Stars](https://img.shields.io/github/stars/api-platform/core?style=social&color=white)](https://github.com/api-platform/core/stargazers)  
  Powerful open-source framework (PHP/Symfony) for creating hypermedia REST and GraphQL APIs with OpenAPI, JSON-LD, and excellent developer experience.
- **[Nhost](https://github.com/nhost/nhost)** [![Stars](https://img.shields.io/github/stars/nhost/nhost?style=social&color=white)](https://github.com/nhost/nhost/stargazers)  
  Open-source backend platform built on Hasura GraphQL Engine + PostgreSQL, providing GraphQL APIs, authentication, storage, and serverless functions.
- **[DreamFactory](https://github.com/dreamfactorysoftware/dreamfactory)** [![Stars](https://img.shields.io/github/stars/dreamfactorysoftware/dreamfactory?style=social&color=white)](https://github.com/dreamfactorysoftware/dreamfactory/stargazers)  
  Open-source core that generates secure REST APIs from multiple databases; enterprise features available commercially.
- **[pREST](https://github.com/prest/prest)** [![Stars](https://img.shields.io/github/stars/prest/prest?style=social&color=white)](https://github.com/prest/prest/stargazers)  
  Lightweight open-source RESTful API server for PostgreSQL written in Go — a fast, simple alternative in the PostgREST family.
- **[Space Cloud](https://github.com/spacecloud-io/space-cloud)** [![Stars](https://img.shields.io/github/stars/spacecloud-io/space-cloud?style=social&color=white)](https://github.com/spacecloud-io/space-cloud/stargazers)  
  Open-source Firebase + Heroku-style platform that provides instant GraphQL and REST APIs on multiple databases with real-time and event triggers.

### ✨ Additional Strong Open-Source Options
- **pg_graphql** — Native PostgreSQL extension (used by Supabase) that adds GraphQL support directly inside the database.
- Database-specific or multi-database auto-API tools appearing in the automatic-api community lists.
- Combinations of PostgREST/Hasura + open auth (GoTrue, Keycloak) + open storage for full BaaS stacks.

**Frameworks for building custom systems**: Start with **PostgREST** or **Hasura** as the core data API engine on PostgreSQL, layer **Directus** when you need a visual admin + multi-database support, add **Supabase** or **Nhost** components for auth/realtime/storage, and use **API Platform** or custom code for advanced business logic — resulting in a fully owned, high-performance data API layer.

## 🤝 How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful! ⭐

## ⚠️ Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Data API platforms should be evaluated for authorization model strength (especially row/column-level security), performance at scale, database support, real-time capabilities, and operational complexity of self-hosting.
- Always apply proper authentication, rate limiting, and least-privilege database roles when exposing data APIs.

## 📈 Star History
[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Data-API-Platform&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Data-API-Platform&type=date&legend=top-left)

---
**Made for backend engineers, full-stack developers, platform teams, and anyone who wants instant, secure, and self-hostable APIs on their databases.**
Let's make data access layers more open, automatic, and free from vendor lock-in. 🌍
