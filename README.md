# Awesome-Data-API-Platform

## Top Data API Platform Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Instant REST & GraphQL APIs on Databases, Auto-Generated Data Layers, Backend-as-a-Service Data APIs & Low-Code Backend Platforms*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data API Platforms**. These tools automatically expose secure, production-ready REST and/or GraphQL APIs from existing databases (or visual data models), often with authentication, authorization, real-time capabilities, and admin interfaces — dramatically accelerating backend development.

**Examples** include Hasura, PostgREST, DreamFactory, Supabase Data API, Xano, Nhost, 8base, Appsmith, Directus, and Fastgen (the category leaders and widely used platforms).

**Open-source emphasis**: This category is exceptionally strong in open source. The section below prioritizes mature, actively maintained projects that let you self-host instant data APIs on PostgreSQL, MySQL, and other databases with full control over schema, permissions, and infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites / GitHub repos.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Hasura](https://hasura.io/)**  
  Instant GraphQL (and REST) APIs on databases with fine-grained authorization, real-time subscriptions, remote schemas, and Actions. Available as open-source engine + managed cloud.
- **[Supabase](https://supabase.com/)** (Data API)  
  Open-source Firebase alternative whose core Data API is powered by PostgREST (REST) + pg_graphql. Hosted platform with auth, storage, realtime, and edge functions.
- **[Xano](https://www.xano.com/)**  
  No-code / low-code backend platform that generates production REST APIs from a visual data model, with business logic, auth, and background tasks.
- **[Nhost](https://nhost.io/)**  
  Open-source GraphQL backend (built on Hasura + PostgreSQL) offering auth, storage, functions, and real-time capabilities with a managed cloud option.
- **[DreamFactory](https://www.dreamfactory.com/)**  
  Enterprise-focused platform that auto-generates secure REST APIs from 20+ databases and services, with role-based access control and on-premises options.
- **[Directus](https://directus.io/)** (Cloud)  
  Instant REST & GraphQL APIs plus a beautiful admin app on any SQL database. Self-hosted open-source core with commercial cloud offering.
- **[8base](https://www.8base.com/)**  
  Low-code GraphQL backend and application platform with managed infrastructure, auth, and front-end tools.
- **[Appsmith](https://www.appsmith.com/)**  
  Open-source low-code platform that includes strong API creation, integration, and internal-tool capabilities (often used alongside data APIs).
- **[Fastgen](https://fastgen.dev/)** (or similar rapid backend tools)  
  Emerging platforms focused on fast generation of data APIs and backend logic.
- **[PostgREST](https://postgrest.org/)** (hosted offerings / managed services)  
  While primarily open-source, various managed and commercial wrappers exist around the PostgREST engine.

## Open-Source GitHub Projects
- **[Hasura GraphQL Engine](https://github.com/hasura/graphql-engine)**  
  Blazing-fast, open-source (Apache 2.0) engine that gives you instant GraphQL and REST APIs on PostgreSQL and other databases with built-in authorization, real-time subscriptions, and remote schema stitching.
- **[PostgREST](https://github.com/PostgREST/postgrest)**  
  The classic open-source (MIT) tool that turns any PostgreSQL database into a fully RESTful API. Extremely performant, standards-compliant, and the foundation used by Supabase and many other platforms.
- **[Directus](https://github.com/directus/directus)**  
  Flexible open-source data platform that wraps any SQL database with instant REST + GraphQL APIs, a powerful visual Studio, granular permissions, and extensibility. Excellent for both headless CMS and pure data API use cases.
- **[PostGraphile](https://github.com/graphile/postgraphile)** (Graphile)  
  High-performance, highly customizable open-source GraphQL API generator for PostgreSQL. Favored by teams that want deep GraphQL control and excellent performance.
- **[Supabase](https://github.com/supabase/supabase)** (self-hosted stack)  
  Fully open-source Firebase alternative. Its Data API layer is built on PostgREST + pg_graphql, delivering automatic REST and GraphQL endpoints on PostgreSQL with auth, realtime, and storage.
- **[Nhost](https://github.com/nhost/nhost)**  
  Open-source backend platform built on Hasura GraphQL Engine + PostgreSQL, providing GraphQL APIs, authentication, storage, and serverless functions.
- **[Space Cloud](https://github.com/spacecloud-io/space-cloud)**  
  Open-source Firebase + Heroku-style platform that provides instant GraphQL and REST APIs on multiple databases (Postgres, MongoDB, MySQL, etc.) with real-time, event triggers, and Kubernetes-native scaling.
- **[pREST](https://github.com/prest/prest)**  
  Lightweight open-source (MIT) RESTful API server for PostgreSQL written in Go — a fast, simple alternative in the PostgREST family.
- **[API Platform](https://github.com/api-platform/core)**  
  Powerful open-source framework (PHP/Symfony) for creating hypermedia REST and GraphQL APIs with OpenAPI, JSON-LD, and excellent developer experience.
- **[Appwrite](https://github.com/appwrite/appwrite)**  
  Open-source backend-as-a-service with database APIs (REST), authentication, storage, functions, and real-time capabilities — broader than pure data APIs but frequently used in the same stack.
- **[PocketBase](https://github.com/pocketbase/pocketbase)**  
  Single-binary open-source backend with embedded SQLite, automatic REST API, realtime, auth, and file storage — ideal for smaller projects and rapid prototyping.
- **[DreamFactory](https://github.com/dreamfactorysoftware/dreamfactory)** (core)  
  Open-source (Apache 2.0) core that generates secure REST APIs from multiple databases; enterprise features available commercially.

### Additional Strong Open-Source Options
- **pg_graphql** — Native PostgreSQL extension (used by Supabase) that adds GraphQL support directly inside the database.
- Database-specific or multi-database auto-API tools appearing in the automatic-api community lists.
- Emerging AI-assisted and metadata-driven platforms (e.g., Steedos / ObjectStack style) that generate APIs from models or prompts.
- Combinations of PostgREST/Hasura + open auth (GoTrue, Keycloak) + open storage for full BaaS stacks.

**Frameworks for building custom systems**: Start with **PostgREST** or **Hasura** as the core data API engine on PostgreSQL, layer **Directus** when you need a visual admin + multi-database support, add **Supabase** or **Nhost** components for auth/realtime/storage, and use **API Platform** or custom code for advanced business logic — resulting in a fully owned, high-performance data API layer.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Data API platforms should be evaluated for authorization model strength (especially row/column-level security), performance at scale, database support, real-time capabilities, and operational complexity of self-hosting.
- Always apply proper authentication, rate limiting, and least-privilege database roles when exposing data APIs.
---
**Made for backend engineers, full-stack developers, platform teams, and anyone who wants instant, secure, and self-hostable APIs on their databases.**
Let's make data access layers more open, automatic, and free from vendor lock-in.
