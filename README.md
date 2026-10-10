<div align="center">

# Paginota

### Your bookmarks, finally intentional.

**A privacy-minded workspace for importing, organizing and rediscovering the links that matter.**

<br />

![Private source](https://img.shields.io/badge/source-private-111827?style=flat-square)
![Built with React](https://img.shields.io/badge/interface-React_%2B_TypeScript-38bdf8?style=flat-square)
![Architecture](https://img.shields.io/badge/architecture-local--first-8b5cf6?style=flat-square)
![Status](https://img.shields.io/badge/status-active-10b981?style=flat-square)

[Overview](#why-paginota) · [Capabilities](#everything-in-its-place) · [Architecture](#designed-for-trust) · [Availability](#availability)

</div>

---

## Why Paginota?

Bookmarks are valuable context, but browser folders are rarely enough. Paginota turns a neglected export into a personal knowledge space: easier to search, cleaner to maintain, and more useful over time.

It is designed for people whose browser is part of their work: developers, students, researchers, consultants and anyone who has accumulated more links than they can reasonably remember.

> **Import once. Find anything. Keep only what matters.**

## Everything in its place

| | Capability | What it brings |
|:--:|---|---|
| ↗ | **Universal import** | Bring in bookmarks from Chrome, Edge, Firefox or Brave via standard HTML export or the companion extension. |
| ✦ | **Intelligent organization** | Enrich links with categories, tags, domains, language, site type and priority signals. |
| ⌕ | **Powerful retrieval** | Navigate with search, filters, collections, favourites, reading lists and domain exploration. |
| ≋ | **Cleaner libraries** | Identify duplicates, inspect broken links and keep an actionable view of your collection’s health. |
| ⤴ | **Controlled sharing** | Create focused, shareable collections without exposing your full personal library. |
| ◌ | **Thoughtful assistance** | Optional AI-supported organization helps structure a large collection while preserving user control. |

## A workflow, not another bookmark folder

```text
Export or capture links
        ↓
Import and normalize
        ↓
Organize, enrich and deduplicate
        ↓
Search, curate and share
        ↓
Rediscover knowledge when it matters
```

Paginota makes the messy middle visible: what is duplicated, what is stale, what is important, and what deserves to become a collection.

## Designed for trust

Paginota is built as a modern web product with a clear separation between the experience, identity and data layers.

```text
React interface
    ├── local-first interactions for a responsive experience
    ├── authenticated API boundary
    └── browser extension bridge

Secure services
    ├── Clerk identity and sessions
    ├── server-side API functions
    └── Neon PostgreSQL persistence
```

The product is deliberately local-first: interactions remain fast and resilient, while account-backed synchronization supports a continuous experience. Database credentials and privileged operations remain server-side; no direct database access is exposed to the browser.

## Built for the details

- Accessible navigation patterns and responsive layouts
- Progressive loading for a faster perceived experience
- Feature flags and administration controls for measured releases
- Import/export workflows that respect browser standards
- Dedicated extension workflow for collecting bookmarks from the browser
- Privacy-conscious boundaries between client, API and persistence layers

## Technology

`React` · `TypeScript` · `Vite` · `Tailwind CSS` · `Clerk` · `Neon PostgreSQL` · `Vercel Functions` · `WebExtensions`

## Availability

Paginota is an active private product. Its source code, infrastructure configuration and proprietary implementation details are not distributed in this repository.

This public space exists to present the product, share selected updates and provide a way to connect.

**Interested in a demo, collaboration or early access?** Open a discussion or contact the project owner through GitHub.

---

<div align="center">

Built around a simple conviction: **your saved links should be easier to use than to lose.**

</div>

