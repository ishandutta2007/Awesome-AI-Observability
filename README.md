# Awesome-AI-Observability

# Top AI Observability Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on LLM Tracing, Prompt Monitoring, Agent Spans, Eval Dashboards, Model Performance & Production AI Telemetry*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Observability**. These systems capture traces of LLM and agent runs, monitor prompts and costs, run evaluations, detect drift, and help teams debug and improve AI applications in production.

**Examples** include Arize AI, Fiddler AI, WhyLabs, Galileo, Langfuse, LangSmith, Helicone, Arthur AI, TruEra, and Weights & Biases (the category leaders).

**Open-source emphasis**: AI observability has excellent open options. **Langfuse**, **Arize Phoenix**, **OpenLLMetry**, **Helicone**, and related projects provide self-hosted tracing and evals. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Arize AI](https://arize.com/)**  
  Leading ML and LLM observability platform—tracing, evaluation, drift, and production monitoring for classical and generative models.

- **[LangSmith](https://www.langchain.com/langsmith)**  
  Observability, evaluation, and prompt hub tightly integrated with the LangChain/LangGraph ecosystem.

- **[Langfuse (Cloud)](https://langfuse.com/)**  
  Hosted LLM engineering platform for tracing, prompt management, datasets, and evals—built on a popular open-source core.

- **[Fiddler AI, WhyLabs, Arthur AI, TruEra](https://www.fiddler.ai/)**  
  Model performance, explainability, and data/LLM monitoring platforms for enterprise AI reliability and governance.

- **[Galileo, Helicone](https://www.rungalileo.io/)**  
  LLM evaluation and observability tools focused on quality scoring, cost tracking, and production insights.

- **[Weights & Biases](https://wandb.ai/)**  
  Experiment tracking and MLOps platform with expanding LLM/agent observability and evaluation workflows.

- **[Other commercial AI observability platforms](https://arize.com/)**  
  Additional solutions for agent tracing, cost analytics, and production AI health.

## Open-Source GitHub Projects

- **[Langfuse](https://github.com/langfuse/langfuse)**  
  Leading open-source (MIT) LLM engineering platform—tracing, sessions, prompt management, evals, and datasets; fully self-hostable with a strong developer experience.

- **[Arize Phoenix](https://github.com/Arize-ai/phoenix)**  
  Open-source AI observability from Arize—tracing, evaluation, experiments, and notebook-friendly workflows; pairs with Arize AX for enterprise scale.

- **[OpenLLMetry (Traceloop)](https://github.com/traceloop/openllmetry)**  
  OpenTelemetry-based instrumentation for GenAI—standard traces for LLM providers and vector DBs that plug into existing observability backends (Datadog, Honeycomb, etc.).

- **[Helicone](https://github.com/Helicone/helicone)**  
  Open-source LLM observability via proxy logging—one-line integration for request/response capture, cost, and latency analytics.

- **[Opik (Comet)](https://github.com/comet-ml/opik)**  
  Open LLM evaluation and observability toolkit from Comet—tracing and eval workflows for development and production.

- **[Evidently](https://github.com/evidentlyai/evidently)**  
  Open ML/LLM monitoring framework with reports, tests, and dashboards for drift, quality, and generative metrics.

- **[AgentOps & agent tracing open tools](https://github.com/search?q=agent+observability+OR+agent+tracing+open+source)**  
  Libraries focused on multi-agent session tracking, tool-call spans, and cost attribution.

- **[OpenTelemetry GenAI semantic conventions](https://opentelemetry.io/)**  
  Emerging standard instrumentation for LLM spans—foundation for vendor-neutral observability pipelines.

### Additional Strong Open-Source Options

- **Full LLM platform**: Langfuse for traces, prompts, and evals in one self-hosted stack.
- **Dev-friendly tracing**: Phoenix for notebooks and fast iteration; OpenLLMetry for OTel-native pipelines.
- **Proxy simplicity**: Helicone for quick request logging without code changes deep in the stack.
- **ML + LLM**: Evidently when you also monitor classical models and data drift.
- **Composable stacks**: OpenLLMetry/Langfuse SDK → your collector → Grafana/Jaeger or Langfuse UI.
- Commercial platforms still lead in multi-team RBAC, SLAs, and combined ML+LLM estates.

**Frameworks for building custom systems**:  
**Langfuse** and **Phoenix** are the strongest open observability products.  
**OpenLLMetry** connects GenAI traces to any OpenTelemetry backend.  
**Helicone** and **Evidently** fill proxy and monitoring gaps.  
Commercial platforms (Arize, LangSmith, Fiddler, WhyLabs, Galileo, W&B, etc.) add scale and enterprise workflows.  
Many teams self-host Langfuse or Phoenix for development and use commercial observability for production multi-team environments. Fully open stacks are production-viable with your own storage and auth.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Observability data often includes prompts, outputs, and user content. Treat traces as sensitive: encrypt, retain appropriately, and restrict access. Comply with privacy laws when logging personal data.
- Open-source tools offer data residency and control but require you to operate storage and security. Commercial platforms shift operational burden to the vendor. Choose based on scale, compliance, and team needs.

---

**Made for AI engineers, MLOps teams, and anyone debugging LLMs and agents in production.**  
Let's expand open AI observability while recognizing the scale and workflow depth that leading commercial platforms deliver.
