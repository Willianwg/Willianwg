## Willian Guedes

**Senior Backend & AI Engineer**: Go, Node.js/TypeScript, AWS, LLM systems.
Salvador, Brazil · UTC-3 · Remote

I design and ship backend systems end to end: architecture, data model, infrastructure and the AI layer. Then I
keep them running in production.

### Production work

Software engineer at a consultancy, working on client systems in fintech, e-commerce and education.

- **Payments.** Built a Node.js service connecting a fintech's payment provider to multiple VTEX marketplaces. It
  handles purchases, cancellations and payment splits through asynchronous events on AWS SQS.
- **Business-model migration.** Led the move from one-time purchases to subscriptions with a credit system: data
  model, end-to-end flow, and core services in Go built for concurrency and high throughput.
- **Cloud cost.** Traced a video platform's main cost to S3 egress and led a full migration of compute, databases
  and storage, cutting infrastructure costs by ~60%.
- **Performance.** Moved search and recommendations from SQL to Apache Solr, cutting API response times by 70%.
- **AI.** Built the backend of an AI education platform: a conversational LangChain agent with RAG (Pinecone), fine-tuned models
  and streamed responses, deployed on AWS.

### Built independently

- **[Nehva CRM](https://github.com/Willianwg/nehva-crm-case-study).** A WhatsApp & Instagram customer-service inbox for
  small stores, which I designed, built and operate.
  - Multi-tenant API with tenant-isolation tests.
  - Webhooks are stored first and processed by a worker; outbound webhooks go through a transactional outbox.
  - A public REST API.
  - Registered Meta Tech Provider, with advanced access to WhatsApp Business messaging approved by Meta.
- **[Cobrowser](https://github.com/Willianwg/cobrowser-case-study).** An autonomous browser agent, engineered from
  its traces.
  - Loop detection that stops runs that are paying for repeated actions.
  - Intent resolution that starts the agent on the right page.
  - DOM pruning and history compaction to cut tokens per step.
  - Langfuse tracing, and an MCP server so IDE agents can drive it.
- **Real-time multiplayer game.** A co-op 3D dungeon in the browser where fights are quizzes.
  - Server-authoritative simulation at 20 Hz.
  - Client-side prediction reconciled with server snapshots, and interpolation for remote players.
  - The same movement code runs on client and server.
  - The question bank never leaves the server.

<details>
<summary>Game demo</summary>

![Running through the dungeon; a fight where the right answer fires the Lightning skill at a skeleton; the merchant's shop](game-3d.gif)

</details>

### Open source

**[Activepieces](https://github.com/activepieces/activepieces/pulls?q=is%3Apr+author%3Awillianwg+is%3Amerged)**
(open-source Zapier alternative, 25k+ stars): 9 merged pull requests, including 6 new integrations: VTEX,
PostgreSQL, Amazon S3, StabilityAI, XML and MailerLite.

### Stack

**Backend:** Go, Node.js, TypeScript, NestJS, Python · **Cloud:** AWS (SQS, Lambda, RDS, S3), Terraform, Docker, GitHub Actions

**Data:** PostgreSQL, Redis, MongoDB, Apache Solr · **AI:** LLM agents, RAG, LangChain, MCP

[LinkedIn](https://www.linkedin.com/in/willian-guedes) · willian.wg70@gmail.com
