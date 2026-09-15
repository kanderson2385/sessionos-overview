# SessionOS

AI-powered workflow and collaboration platform for sync composers.
🔗 Live: https://sessionos.io

## Overview

SessionOS is an AI-powered workflow and collaboration platform built for sync composers, writer camps, and sync licensing agencies. 
It brings session collaboration, split sheet documentation, and sync-readiness scoring into one workflow,
helping composers go from a co-writing session to a licensable, properly-cleared track without juggling separate tools.

## Tech Stack

- **Frontend:** TypeScript, TanStack Router
- **Backend:** Supabase (Postgres), Row-Level Security policies
- **Auth:** Google OAuth
- **Hosting:** Cloudflare Workers
- **CI/CD:** GitHub → Cloudflare Workers Builds → Cloudflare DNS

## Highlights

- Designed and built independently, end-to-end — architecture, backend, and deployment
- Applied a 13-migration SQL schema and configured full authentication flow
- Resolved backend routing and database-level access control (RLS) issues during development
- Five core workflow areas: Collab Studio, Track Discovery, Free Agency, Matchmaker, and Search

## Status

SessionOS is live and in active development.

---

*This repository is a public overview. The production codebase is maintained privately.*
