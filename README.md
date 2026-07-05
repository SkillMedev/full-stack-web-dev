# Full-Stack Web Dev

**For devs shipping a Next.js + Postgres app: auth, billing, and a fast launch end to end.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when you're building a real Next.js + Supabase/Postgres product and need it production-ready, not just running locally. It carries you from data model and API to OAuth login, Stripe subscriptions, and a fast, Core-Web-Vitals-clean launch - so the full path from schema to shipped feature is covered by one coherent stack instead of stitched-together advice.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/full-stack-web-dev](https://skillme.dev/pack/full-stack-web-dev) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/full-stack-web-dev`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Next.js App Router](skills/nextjs-app-router/SKILL.md)** — Builds and reviews Next.js App Router code - server/client component boundaries, data fetching, caching and revalidation choices, streaming with Suspense, and Server Action mutations - and delivers routes where every dynamic-vs-cached decision is explicit.
- **[GraphQL Schema](skills/graphql-schema/SKILL.md)** — Designs GraphQL schemas and resolvers that scale - domain-modeled types, Relay pagination, DataLoader batching to kill N+1, mutation payloads with typed user errors, and depth/complexity limits that stop abusive queries.
- **[Database Schema Designer](skills/database-schema/SKILL.md)** — Designs normalized, constrained, migration-friendly relational schemas - entity modeling, key and type selection, indexes derived from real query patterns, and safe forward/rollback migrations.
- **[OAuth & Auth Flow](https://skillme.dev/skill/oauth-flow)** — Implements OAuth 2.0, JWT, and session auth correctly with security best practices. _(external — see source)_
- **[Stripe Expert](skills/stripe-integration/SKILL.md)** — Implements Stripe payments, subscriptions, and webhooks so billing state stays correct - Checkout Sessions, signature-verified idempotent webhook handlers, dunning, and SCA handling.
- **[Supabase Expert](skills/supabase-expert/SKILL.md)** — Builds secure Supabase apps - Row Level Security policies as the authorization layer, schema design against auth.users, Edge Functions for service-role work, realtime subscriptions, and versioned migrations.
- **[Web Performance](skills/web-performance/SKILL.md)** — Diagnoses and fixes Core Web Vitals - LCP, INP, and CLS - through an ordered audit procedure with concrete code-level changes for images, fonts, JavaScript, and third-party scripts.
- **[REST API Design](skills/api-design/SKILL.md)** — Designs REST API surfaces - resource naming, HTTP method and status-code semantics, error shapes, pagination, and filtering - and delivers an endpoint spec a consumer can build against without asking questions.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
