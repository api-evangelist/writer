# Writer (writer)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Writer is a generative AI platform purpose-built for the enterprise. The Writer AI Studio Platform API exposes the proprietary Palmyra family of LLMs, knowledge-graph retrieval, no-code Application invocation, tool calling, vision, translation, and content guardrails for enterprise content, summarization, and process-automation workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/writer/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/writer/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Enterprise
- Content Generation
- Palmyra
- Agents

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-19

## APIs

### Writer Chat Completion API

Generates multi-turn conversational completions using Palmyra family models with streaming, tool calling, and structured outputs.

- **Human URL:** [https://dev.writer.com/api-reference/chat-api](https://dev.writer.com/api-reference/chat-api)
- **Base URL:** `https://api.writer.com/v1`

#### Tags

- Chat
- Completions
- LLM

#### Properties

- [Documentation](https://dev.writer.com/api-guides/chat-completion)
- [API Reference](https://dev.writer.com/api-reference/chat-api)
- [OpenAPI](openapi/writer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/writer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/writer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Writer Text Generation API

Single-shot text completion endpoint for prompts that don't require conversational context.

- **Human URL:** [https://dev.writer.com/api-reference/completion-api](https://dev.writer.com/api-reference/completion-api)
- **Base URL:** `https://api.writer.com/v1`

#### Tags

- Completions
- Text Generation

#### Properties

- [Documentation](https://dev.writer.com/api-guides/text-generation)
- [API Reference](https://dev.writer.com/api-reference/completion-api)
- [OpenAPI](openapi/writer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/writer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/writer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Writer Tool Calling API

Defines and executes custom functions and external service integrations during chat completions.

- **Human URL:** [https://dev.writer.com/api-guides/tool-calling](https://dev.writer.com/api-guides/tool-calling)
- **Base URL:** `https://api.writer.com/v1`

#### Tags

- Tools
- Function Calling

#### Properties

- [Documentation](https://dev.writer.com/api-guides/tool-calling)
- [OpenAPI](openapi/writer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/writer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/writer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Writer Knowledge Graph API

Builds and queries graph-based retrieval indexes that connect enterprise data sources to agents for accurate, grounded responses.

- **Human URL:** [https://dev.writer.com/api-reference/graph-api](https://dev.writer.com/api-reference/graph-api)
- **Base URL:** `https://api.writer.com/v1`

#### Tags

- Knowledge Graph
- RAG
- Retrieval

#### Properties

- [Documentation](https://dev.writer.com/api-guides/knowledge-graph)
- [API Reference](https://dev.writer.com/api-reference/graph-api)
- [OpenAPI](openapi/writer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/writer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/writer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Writer Files API

Upload, download, list, and delete files; attach them to Knowledge Graphs and Agents.

- **Human URL:** [https://dev.writer.com/api-reference/file-api](https://dev.writer.com/api-reference/file-api)
- **Base URL:** `https://api.writer.com/v1`

#### Tags

- Files
- Storage
- Documents

#### Properties

- [Documentation](https://dev.writer.com/api-guides/file-management)
- [API Reference](https://dev.writer.com/api-reference/file-api)
- [OpenAPI](openapi/writer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/writer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/writer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Writer Applications API

Invokes no-code agents and AI Studio Applications as microservices or programmatically triggers Blueprints via HTTP.

- **Human URL:** [https://dev.writer.com/api-reference/application-api](https://dev.writer.com/api-reference/application-api)
- **Base URL:** `https://api.writer.com/v1`

#### Tags

- Applications
- No-Code
- Agents

#### Properties

- [Documentation](https://dev.writer.com/api-guides/applications)
- [API Reference](https://dev.writer.com/api-reference/application-api)
- [OpenAPI](openapi/writer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/writer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/writer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Writer Vision API

Submits images and documents with a prompt to generate an analysis using vision-capable Palmyra models.

- **Human URL:** [https://dev.writer.com/api-guides/vision](https://dev.writer.com/api-guides/vision)
- **Base URL:** `https://api.writer.com/v1`

#### Tags

- Vision
- Multimodal
- Documents

#### Properties

- [Documentation](https://dev.writer.com/api-guides/vision)
- [OpenAPI](openapi/writer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/writer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/writer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Writer Web Search API

Queries the web for real-time information to include in agent responses, with citation support.

- **Human URL:** [https://dev.writer.com/api-guides/web-search](https://dev.writer.com/api-guides/web-search)
- **Base URL:** `https://api.writer.com/v1`

#### Tags

- Web Search
- Real-Time

#### Properties

- [Documentation](https://dev.writer.com/api-guides/web-search)
- [OpenAPI](openapi/writer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/writer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/writer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Writer Translation API

Converts text between 30+ supported languages with enterprise tone and style guidance.

- **Human URL:** [https://dev.writer.com/api-guides/translation](https://dev.writer.com/api-guides/translation)
- **Base URL:** `https://api.writer.com/v1`

#### Tags

- Translation
- Languages

#### Properties

- [Documentation](https://dev.writer.com/api-guides/translation)
- [OpenAPI](openapi/writer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/writer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/writer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Writer Models API

Lists Palmyra models and external models (e.g., AWS Bedrock) accessible to the account, with metadata and parameters.

- **Human URL:** [https://dev.writer.com/api-reference/model-api](https://dev.writer.com/api-reference/model-api)
- **Base URL:** `https://api.writer.com/v1`

#### Tags

- Models
- Catalog

#### Properties

- [API Reference](https://dev.writer.com/api-reference/model-api)
- [OpenAPI](openapi/writer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/writer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/writer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Writer Guardrails API

Enforces content safety, PII protection, and compliance policies across AI agents and chat completions.

- **Human URL:** [https://dev.writer.com/api-guides/guardrails](https://dev.writer.com/api-guides/guardrails)
- **Base URL:** `https://api.writer.com/v1`

#### Tags

- Guardrails
- Safety
- PII

#### Properties

- [Documentation](https://dev.writer.com/api-guides/guardrails)
- [OpenAPI](openapi/writer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/writer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/writer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Writer API Keys API

Programmatically creates, lists, and rotates API keys for authenticating to the Writer Platform.

- **Human URL:** [https://dev.writer.com/api-guides/quickstart](https://dev.writer.com/api-guides/quickstart)
- **Base URL:** `https://api.writer.com/v1`

#### Tags

- API Keys
- Authentication

#### Properties

- [Documentation](https://dev.writer.com/api-guides/quickstart)
- [OpenAPI](openapi/writer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/writer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/writer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/writer)
- [LinkedIn](https://www.linkedin.com/company/getwriter)
- [Website](https://writer.com/)
- [Documentation](https://dev.writer.com/)
- [Plans](plans/writer-plans-pricing.yml)
- [Rate Limits](rate-limits/writer-rate-limits.yml)
- [Fin Ops](finops/writer-finops.yml)
- [Integrations](https://writer.com/partners/)
- [L L Ms Txt](https://api.writer.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
