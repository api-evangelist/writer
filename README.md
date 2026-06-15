# Writer (writer)

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
