<div align="center">

# `O(1)` constant·time

**everything you forgot, retrieved in constant time.**

a single-page field guide for technical interviews:
languages · principles · patterns · systems · machines that think

[**→ open it**](https://robert-schmidt.github.io/constant-time/)

</div>

---

```
lookup(concept)   → O(1)
understand(it)    → O(practice)
explain(it)       → the interview
```

## what lives here

~100 dense cards, one page, zero build step.

| layer | contents |
|---|---|
| **syntax** | Python · JS/TS · Java · Go · C# · Rust · C++ · PHP, plus side-by-side Rosetta tables |
| **shape** | OOP pillars · SOLID · DRY/KISS/YAGNI · code smells · GoF patterns · functional patterns |
| **structure** | clean / hexagonal · DDD · CQRS · event sourcing · microservices · anti-patterns |
| **flow** | event-driven design · delivery guarantees · outbox · sagas · Kafka & friends · streams |
| **ground** | cloud models · AWS/GCP/Azure map · Kubernetes · serverless · IaC · HA/DR |
| **scale** | system design loop · napkin math · caching · sharding · consistency · rate limiting |
| **state** | SQL · indexes · isolation levels · picking a store · analytics stack |
| **wire** | REST · GraphQL · gRPC · HTTP · auth · OWASP · crypto |
| **logic** | Big-O · problem→pattern map · templates · DP · graphs · concurrency |
| **signal** | ML fundamentals · deep learning · LLMs · prompting · RAG · agents · MCP · LLMOps · the buzzword decoder |
| **self** | testing · delivery · observability · RCA · STAR · senior signals |

## how it thinks

- **level-aware.** On first visit it asks what you're interviewing for (*junior · mid · senior · architect*) and shows the cards that matter at that level. Skip it to see everything; switch anytime from the header.
- **search that forgives.** Multi-word queries rank cards that match every word first, then fall back to the closest partial matches. Hidden synonyms mean `k8s`, `idor` or `lora` find the right card.
- **shareable state.** The query and level live in the URL: `?q=rag&lvl=s`.
- **keyboard first.** `/` to search, `Esc` to clear.

## run it

```sh
open index.html
```

No framework, no bundler, no dependencies. Just HTML, CSS and a bit of JS.

## contribute

Found a gap or a wrong claim? Open a PR. Each card is one `<article>`:

```html
<article class="card" data-lvl="m s a" data-cat="events" data-k="extra search synonyms">
```

- `data-lvl`: `j` `m` `s` `a` (the levels that should see it)
- `data-cat`: the filter chips it belongs to
- `data-k`: invisible keywords for search

---

<div align="center"><sub>syntax is lookup · judgment is the job</sub></div>
