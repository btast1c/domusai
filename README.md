<h1 align="center">
  <a href="https://domusai.ai">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/assets/logo.svg">
      <img alt="Domus Vita" src=".github/assets/logo.svg" width="600">
    </picture>
  </a>
  <br>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square&logo=opensourceinitiative&logoColor=white" alt="License">
  </a>
  <a href="https://www.rust-lang.org">
    <img src="https://img.shields.io/badge/%F0%9F%A6%80%20Backend-Rust-orange?style=flat-square" alt="Rust">
  </a>
  <a href="https://react.dev">
    <img src="https://img.shields.io/badge/%E2%9A%9B%EF%B8%8F%20Frontend-React_19-61DAFB?style=flat-square" alt="React">
  </a>
  <a href="https://www.postgresql.org">
    <img src="https://img.shields.io/badge/%F0%9F%90%98%20Database-PostgreSQL_18-336791?style=flat-square" alt="PostgreSQL">
  </a>
  <a href="https://www.dragonflydb.io">
    <img src="https://img.shields.io/badge/%F0%9F%94%A5%20Cache-Dragonfly-00ADD8?style=flat-square" alt="Dragonfly">
  </a>
  <a href="https://www.docker.com">
    <img src="https://img.shields.io/badge/%F0%9F%90%B3%20Deploy-Docker-2496ED?style=flat-square" alt="Docker">
  </a>
</h1>

<p align="center">
  <em><b>Domus Vita</b> — the AI-powered shared housing marketplace where listing a room is as easy as posting a photo and finding one is as fast as asking a question.<br>
  No code. No config. No landlord headaches.<br>
  Just <b>move in</b>.</em>
</p>

<p align="center">
  <b>Weekly payments. 1-day approval. AI that actually helps.</b>
</p>

<p align="center">
  <img src=".github/assets/atlas.png" width="200" alt="Atlas — Your AI Assistant">
  <br>
  <sub><b>Meet Atlas</b> — your AI assistant who knows every property, every neighborhood, and every answer.</sub>
</p>

---

## Why Domus Vita?

Shared housing is broken. Craigslist is a minefield. Facebook groups are chaos. Traditional rental platforms charge monthly rent that locks people in and shuts people out. Finding a compatible roommate shouldn't require a spreadsheet and a prayer.

**Domus Vita fixes this.** An AI-powered marketplace where hosts list rooms in minutes with zero technical setup, tenants find matches through natural conversation, and everyone pays weekly instead of drowning in first-month-last-month-deposit math.

**Everything just works.** No forms to configure. No templates to customize. No integrations to wire up. You sign up, and Atlas — your AI assistant — handles the rest, from property intelligence to encrypted vault storage for your private data.

---

<p align="center">
  <img src=".github/assets/header_listing.svg" width="600" alt="List a Room in Minutes">
</p>

The listing wizard is the heart of the no-code promise. Six steps. No decisions you haven't already made. No configuration screens. No "advanced settings."

| Step | What You Do | What Domus Does |
|:---|:---|:---|
| **1. Address** | Type your address | Autocomplete from 154M+ US addresses, auto-fill location data |
| **2. Type** | Pick property type | Pre-configured options, no custom fields to manage |
| **3. Occupancy** | Owner-occupied? One tap | Adjusts listing presentation automatically |
| **4. Photos** | Upload images | Handles resizing, thumbnails, and gallery layout |
| **5. Timeline** | Set availability | Calendar picker with minimum stay defaults |
| **6. Pricing** | Set weekly rate | Done. Your room is live. |

### Zero Friction, By Design

- **Auto-save everything** — walk away mid-step, come back tomorrow, pick up where you left off
- **Progress tracking** — visual progress bar shows exactly where you are
- **Save & exit** — close the browser, your draft is waiting when you return
- **One-click publish** — finalize and your listing is instantly live
- **No configuration needed** — sensible defaults handle everything behind the scenes

Hosts don't need to learn a platform. They need to list a room. That's it. That's the product.

---

<p align="center">
  <img src=".github/assets/header_search.svg" width="600" alt="Find Your Room with AI">
</p>

Two ways to search. Both feel effortless.

### AI-Powered Search

Just ask Atlas. *"I need a furnished room near downtown Tampa under $250 a week"* — he understands location, budget, amenities, and preferences. No dropdowns. No filter menus. No boolean queries. Just a conversation with your AI assistant.

### Map-Based Search

Interactive map with real-time property overlays. Drag, zoom, explore. Filter by price, beds, baths, property type. Quick links to popular cities. Click a pin, see the listing. Every search result enriched with neighborhood intelligence automatically.

### Under the Hood

| Metric | Number |
|:---|:---|
| **Searchable properties** | 11.2M+ (Florida, expanding) |
| **Address autocomplete** | 154M+ US addresses |
| **Search response time** | < 1ms (H3 spatial indexing) |
| **Autocomplete response** | Sub-millisecond (Tantivy FTS) |

You don't need to know any of that. You just need to know it's fast.

---

<p align="center">
  <img src=".github/assets/header_atlas.svg" width="600" alt="Meet Atlas">
</p>

<p align="center">
  <img src=".github/assets/atlas.png" width="120" alt="Atlas">
</p>

Every property page comes with **Atlas** — your personal AI assistant. He knows the property, the neighborhood, and the surrounding area. No setup. No API keys. No configuration. Atlas is just there, ready to help.

### What Atlas Knows

| Intelligence | Source |
|:---|:---|
| **Schools & Safety** | Neighborhood data, demographics, crime statistics |
| **Nearby Places** | Restaurants, shops, gyms, transit — Google Places API |
| **Air Quality** | Real-time AQI monitoring |
| **Transit** | Public transportation access and routes |
| **Property Details** | Auto-enriched from web sources when data is missing |

### How It Works

Ask Atlas anything about a property. *"Are there good schools nearby?"* *"What's the commute to downtown?"* *"Is this neighborhood safe?"* He pulls from multiple data sources, synthesizes an answer, and cites every source. If property data is missing or stale, Atlas automatically enriches it from the web.

No configuration. No data entry. Atlas handles it.

<details>
  <summary><b>Full enrichment capabilities</b></summary>

| Data Type | Description |
|:---|:---|
| **Property Info (.nfo)** | Core property details and characteristics |
| **Features (.fea)** | Property features, amenities, and upgrades |
| **Valuation (.val)** | Assessment and market value data |
| **Web Sources (.url)** | Curated links to property listings and records |
| **Schools (.sch)** | Nearby schools with ratings and distance |
| **Tax Records (.tax)** | Property tax history and assessments |
| **Insurance (.ins)** | Insurance estimates and risk factors |
| **Comparables (.cmp)** | Similar properties for price comparison |
| **Maps (.map)** | Satellite imagery and location context |
| **Research (.res)** | AI-generated research summaries with citations |

All data cached locally. All updates atomic. All enrichment automatic.

</details>

---

<p align="center">
  <img src=".github/assets/header_ai.svg" width="600" alt="AI Chat & Research">
</p>

Atlas isn't a chatbot bolted on as an afterthought. He's woven into every layer of the platform.

### Multi-Model Chat

Talk to **Claude, GPT, Gemini, Grok**, or a **self-hosted local model**. Switch providers mid-conversation. Every response streams in real-time over WebSocket — no waiting for a spinner to finish.

| Feature | Description |
|:---|:---|
| **5 AI Providers** | OpenAI, Anthropic, Google, Grok, vLLM (local) |
| **Real-Time Streaming** | WebSocket delivery, token by token |
| **Rich Rendering** | Markdown, code highlighting, KaTeX math, Mermaid diagrams |
| **Conversation History** | Full multi-turn context, encrypted in your vault |

### Cortex RAG Engine

The research engine powering Atlas. **Hybrid search** combining vector embeddings, BM25 full-text search, and knowledge graph traversal — fused with Reciprocal Rank Fusion for results that are both semantically relevant and keyword-precise.

### Deep Research Mode

Need to go deeper? Ask Atlas to research. He runs a full investigation with web search, source scraping, and citation tracking. Every claim traced to its source. Follow-up questions generated automatically to keep the research flowing.

---

<p align="center">
  <img src=".github/assets/header_marketplace.svg" width="600" alt="The Marketplace">
</p>

The entire rental lifecycle — from discovery to payment — in one platform. No external tools. No spreadsheet tracking. No chasing checks.

### For Tenants

```
Search  -->  Apply  -->  Get Approved  -->  Sign Lease  -->  Pay Weekly  -->  Build Credit
```

- **Weekly payments** — no massive upfront deposits, no first-and-last
- **1-day approval target** — fast enough for urgent housing needs
- **All-inclusive pricing** — utilities, WiFi, furniture bundled in the weekly rate
- **Flexible terms** — 12-week minimums, not 12-month leases
- **Credit building** — on-time weekly payments reported to build your score
- **Verified hosts** — background checks and income verification on all members

### For Hosts

```
List Room  -->  Review Applications  -->  Approve  -->  Collect Payments  -->  Track Earnings
```

- **2-minute listing** — the wizard handles everything
- **Application management** — review, approve, decline with notes
- **Payment collection** — Stripe-powered, automatic, weekly
- **Earnings dashboard** — track income, view payment history, download reports
- **Member management** — verified tenants with background checks
- **Direct messaging** — talk to applicants and tenants without leaving the platform

### Dashboard

Hosts and tenants each get a tailored dashboard. Hosts see earnings, active listings, pending applications, and member status. Tenants see payment history, application status, saved properties, and AI conversation history. Everything in one place. No tab-juggling.

---

<p align="center">
  <img src=".github/assets/header_security.svg" width="600" alt="Security & Privacy">
</p>

Your data is encrypted before it leaves your browser. The server stores ciphertext. We can't read it. Nobody can.

| Layer | Implementation |
|:---|:---|
| **Zero-Knowledge Vault** | Per-user encryption with password-derived keys — server never sees plaintext |
| **Encrypted Storage** | Favorites, saved searches, search history, preferences, AI conversations — all encrypted |
| **Recovery Key** | Lose your password, not your data — recovery key restores access |
| **Authentication** | JWT with 15-minute access tokens, 7-day refresh tokens, Google OAuth 2.0 |
| **Role-Based Access** | Granular permissions — member, host, admin — with full audit trail |
| **Price Alerts** | Saved properties trigger encrypted notifications on price or status changes |

No "trust us with your data." **Verify that we can't touch it.**

---

<p align="center">
  <img src=".github/assets/header_stack.svg" width="600" alt="The Stack">
</p>

Built for speed, safety, and scale.

| Layer | Technology | Why |
|:---|:---|:---|
| **Backend** | Rust + Axum | Single binary, memory safe, zero garbage collection pauses |
| **Frontend** | React 19 + TypeScript + Vite | Modern, reactive, type-safe |
| **Database** | PostgreSQL 18 + PostGIS + pgvector | Relational + geospatial + vector search in one engine |
| **Cache** | DragonflyDB | Redis-compatible, dramatically faster |
| **Object Storage** | MinIO | S3-compatible, self-hosted, no cloud bills |
| **Search** | Tantivy + H3 | Full-text search + hexagonal spatial indexing |
| **AI** | Multi-provider + Cortex RAG | Five providers, hybrid retrieval, knowledge graph |
| **Infrastructure** | Docker Compose | One command to launch everything |

### Performance

| Operation | Speed |
|:---|:---|
| Property search (viewport) | `< 1ms` |
| Address autocomplete | `< 1ms` |
| AI chat first token | Real-time streaming |
| Property enrichment | Automatic, cached |
| Wizard auto-save | 1.5s debounce, silent |

100% Rust backend. No cold starts. No garbage collector. No "please wait while we spin up your instance."

---

## Who Is This For?

- **Room seekers** who want to find affordable, flexible housing without signing their life away on a 12-month lease
- **Hosts** who have a spare room and want to earn income without becoming a property management company
- **Anyone** tired of Craigslist scams, Facebook group chaos, and platforms that charge monthly rent plus deposits plus fees
- **People who move** — digital nomads, traveling professionals, students, anyone who needs housing measured in weeks, not years
- **Privacy-conscious users** who want zero-knowledge encryption without having to configure anything

## No Code. No Config. Really.

Most platforms say "easy to use" and then hand you a settings page with 47 toggles. Domus Vita means it:

- **Hosts:** Type address, upload photos, set price. Done.
- **Tenants:** Search by conversation or map. Apply with one click. Pay weekly.
- **Atlas:** Already configured. Already enriching. Already answering your questions.
- **Encryption:** Already on. Already protecting. Already zero-knowledge.
- **Matching:** Already running. Already learning. Already connecting.

You don't configure Domus Vita. You just use it.

---

<p align="center">
  <sub>Built with Rust. Powered by AI. Designed for humans.</sub>
  <br><br>
  <a href="https://www.rust-lang.org/">
    <img src="https://img.shields.io/badge/Made_with-Rust-orange?style=for-the-badge&logo=rust&logoColor=white" alt="Made with Rust">
  </a>
  <a href="https://www.postgresql.org/">
    <img src="https://img.shields.io/badge/Data-PostgreSQL_18-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  </a>
  <a href="https://www.dragonflydb.io/">
    <img src="https://img.shields.io/badge/Cache-Dragonfly-00ADD8?style=for-the-badge" alt="Dragonfly">
  </a>
  <a href="https://www.docker.com/">
    <img src="https://img.shields.io/badge/Deploy-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  </a>
  <br><br>
  <b>Housing should be simple. Now it is.</b>
  <br>
  <em>No code. No config. Just move in.</em>
</p>
