# Writer (writer)

Writer is a generative AI platform purpose-built for the enterprise. The Writer AI Studio Platform API exposes the proprietary Palmyra family of LLMs, knowledge-graph retrieval, no-code Application invocation, tool calling, vision, translation, and content guardrails for enterprise content, summarization, and process-automation workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/writer/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=writer-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags:

 - AI, LLM, Enterprise, Content Generation, Palmyra, Agents

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| Writer Chat Completion API | Multi-turn chat with Palmyra models, tool calling, structured outputs. |
| Writer Text Generation API | Single-shot text completion. |
| Writer Tool Calling API | Custom function execution and external service integration. |
| Writer Knowledge Graph API | Graph-based retrieval/RAG over enterprise data. |
| Writer Files API | File upload/download/list/delete attached to Graphs and Agents. |
| Writer Applications API | Invoke no-code agents and Blueprints via HTTP. |
| Writer Vision API | Image and document analysis with vision-capable Palmyra models. |
| Writer Web Search API | Real-time web search with citations. |
| Writer Translation API | 30+ language translation with enterprise tone guidance. |
| Writer Models API | Lists Palmyra and external models (e.g., AWS Bedrock). |
| Writer Guardrails API | Safety, PII, and compliance enforcement. |
| Writer API Keys API | Programmatic key creation/rotation. |

## Common Properties

- [Website](https://writer.com/)
- [Documentation](https://dev.writer.com/)
- [Plans](plans/writer-plans-pricing.yml) — API Commons Plans 0.1
- [RateLimits](rate-limits/writer-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/writer-finops.yml) — FOCUS-aligned FinOps Framework 1.0

## Artifacts

| Artifact | Path | Notes |
|---|---|---|
| Plans | `plans/writer-plans-pricing.yml` | Starter (14-day trial) / Enterprise (contact sales) / AI Studio API. Per-seat & per-token rates not public. |
| Rate Limits | `rate-limits/writer-rate-limits.yml` | RPM/TPM enforced per organization; specific values contract-dependent. |
| FinOps | `finops/writer-finops.yml` | FOCUS-aligned, subscription + usage hybrid (seats, tokens, KG queries, vision calls, storage). |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
