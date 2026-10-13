# Toy | Enterprise AI & LLM Solutions

**Turning enterprise IT challenges into practical AI solutions — from local LLM deployment to ERP integration and workflow automation.**

My background is in enterprise IT management and system integration. I lead requirements definition, solution selection, architecture direction, and engineering decisions, working with AI coding agents on implementation and reviewing results against acceptance criteria.

以企業 IT 與系統整合經驗為基礎，將 AI 方案落實到可驗證的工程案例。我的角色是需求、方案與架構決策，以及 AI Agent 協作與成果驗收。

## Featured Projects

Published engineering case studies, with maturity labels describing the underlying systems.

### [Enterprise ERP AI Agent](https://github.com/Toy-Lab-Re/enterprise-erp-ai-agent)

Natural-language access to official ERP Web Services through **18 read-only Tool functions**, with parameter validation and bounded results. **17/17 archived fixed tests reported passing**.

**Read-only POC** — write and approval actions remain incomplete.

### [DGX Spark LLM Journey](https://github.com/Toy-Lab-Re/dgx-spark-llm-journey)

Inference engineering on NVIDIA DGX Spark / GB10: **six public LLM checkpoints and ten launched Model × Runtime configurations**. Covers vLLM, SGLang, DFlash2, MTP, NVFP4, and measurement pitfalls.

**Engineering case study / POC deployments** — single-stream observations; ten launches are not ten complete benchmark comparisons.

### [Qwen 27B Domain QLoRA](https://github.com/Toy-Lab-Re/qwen-27b-domain-qlora)

NVFP4 domain adaptation with loss masking and teacher traces, separating training from serving. Small Golden Set checks explore model behavior and the cost of deeper analysis.

**v0.5 Adopted Candidate for internal trial** — no Production Promotion or general accuracy claim.

## Additional Projects

- **[LINE ITSM AI Bot](https://github.com/Toy-Lab-Re/line-itsm-ai-bot)** — LINE Messaging API, FastAPI, and a local LLM for issue triage and ticket workflows. **51 messages / 22 tickets** in archived records, with failure analysis and reliability limits. **Internal pilot**; weekly knowledge consolidation remains unverified end to end.
- **[AI-Assisted Security Advisory Digest](https://github.com/Toy-Lab-Re/security-intelligence-ai)** — Public-advisory classification and two audience-specific drafts for human review; one successful manual run recorded. **POC + Future Design Study**; scheduling is unverified, and Log, EDR, and SOC capabilities are not implemented.

## Technical Focus

- **Enterprise AI Integration** — tool boundaries, validated business parameters, deterministic data handling, and integration with existing systems.
- **Local LLM Inference & Evaluation** — runtime selection, precision and memory trade-offs, model adaptation, and evidence-aware measurement.
- **AI Workflow Automation** — contextual triage, bounded processing, human review, and explicit recovery and reliability limits.
- **AI-Assisted Engineering & Architecture Governance** — clear responsibilities, scoped changes, recorded decisions, and acceptance criteria.

## My Role & AI-Assisted Development

**Human-Directed, AI-Assisted Engineering.** I guide requirements, solution choices, engineering direction, test evaluation, and acceptance.

Claude Code performed most hands-on development, deployment, model experiments, testing, and debugging. Codex supported evidence review, documentation, and portfolio management; historical infrastructure attribution is qualified in the DGX Spark case study. Each project documents its responsibilities and evidence limits.

## Contact

[GitHub · Toy-Lab-Re](https://github.com/Toy-Lab-Re)
