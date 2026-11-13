# Moisés Bessalle

**AI engineer and full-stack developer.** I build LLM systems that are measured and observable: extraction
pipelines, agent workflows and the evals, checks and traces that make them safe to run unattended.

Open to work: **Amsterdam · Spain · Switzerland · remote.** EU citizen, no visa sponsorship needed.

[LinkedIn](https://www.linkedin.com/in/mbessalle)

## What I work with

| | |
|---|---|
| **LLM and agents** | OpenAI API, Google Gemini API, LangGraph, LangChain, AutoGen, multi-agent systems, RAG, hierarchical LLM indexing, context and prompt engineering |
| **Agent harnesses and orchestration** | Orca, Herder, Pi, OMP, Claude Code, Codex and other model-agnostic agent harnesses; multi-agent development workflows |
| **Reliability of LLM output** | Pydantic schema validation, evals on real data, deterministic grounding checks, OpenTelemetry tracing (Jaeger) |
| **Search and retrieval** | Vector databases (Pinecone, Chroma), text embeddings, semantic search, Elasticsearch |
| **Backend and data** | Python, FastAPI, Node.js, Express, PostgreSQL, MySQL, MongoDB, Redis, Pandas, web scraping (Playwright, BeautifulSoup) |
| **Front end** | TypeScript, JavaScript, React, Redux, Next.js, HTML, CSS |
| **Cloud and delivery** | GCP (Dataflow, BigQuery, Cloud Storage), Azure, AWS, Docker, Terraform, Ansible, GitHub Actions, GitLab CI/CD, Linux |
| **ML and analytics** | PyTorch, TensorFlow, scikit-learn, Tableau, n8n |

## Selected work

### [motherlode-data-pipeline](https://github.com/mbessalle/motherlode-data-pipeline)
An unattended pipeline that turns mining deal announcements into a structured Postgres database.
The model extracts; code decides what is written.
- LangGraph state machine with a validate → retry → quarantine loop
- Pydantic schema for every extracted record, and every number checked against its source:
  **98% supported on 33 real press releases**
- OpenTelemetry traces with model and token counts per call, viewed in Jaeger
- 67 offline tests, CI on every push, scheduled runs on GitHub Actions

### [ai-interviewer](https://github.com/mbessalle/ai-interviewer)
A voice interviewer for hiring: companies create interviews, candidates talk to an AI agent, and the
platform stores the conversation and produces an analysis report. TypeScript, full stack.

### [llm-pipeline-cookbook](https://github.com/mbessalle/llm-pipeline-cookbook)
Code examples from my cookbook of production patterns for LLM pipelines: routing between classic NLP and
LLM calls, cost calculation, and the failure handling a pipeline needs to run every day.

### [brineguard-coast](https://github.com/mbessalle/brineguard-coast)
Scientific Python: does coordinating desalination plants reduce coastal brine exposure? An analytic transport
kernel cross-checked numerically, a linear-programming dispatch, preregistered claims with frozen evidence,
and a reported null result. Built with a multi-agent workflow orchestrated through Orca.

### [divergence-curl-explorer](https://github.com/mbessalle/divergence-curl-explorer) · [live](https://mbessalle.github.io/divergence-curl-explorer/)
An interactive vector-field explorer in the browser: paint a 2D field on a canvas and see its divergence.
A single HTML file, no build step.

## Background

Chemical engineer turned software and AI engineer.
- MSc Artificial Intelligence, VU Amsterdam (in progress)
- MSc Science, Business & Innovation, VU Amsterdam (coursework completed, thesis pending)
- BSc Chemical Engineering, Universidad de Concepción

I run Mois Analytics, a consultancy for analytics, web development and process automation.
