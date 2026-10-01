# Ke-Jie Kuo 郭科頡

Research, engineering, software, and developer tools.

AI Architect, AI startup (in formation) · M.S. student, National Taiwan University of Science and Technology · B.S. in Electrical Engineering (Communications), Tamkang University

## Featured Projects

Three public projects you can inspect and try:

- **[PC-MEF](https://github.com/SpadesZ/PC-MEF)** — Camera and depth sensing for liquid-state recognition inside pipes. Research in progress; final evaluation is incomplete.

- **[Dev Triangle MCP](https://github.com/SpadesZ/dev-triangle-mcp)** — Coding-agent handoffs, patch reviews, and recorded test results. Local tools are implemented; real handoffs need provider setup.

- **[Codex IME Enter Guard](https://github.com/SpadesZ/codex-ime-enter-guard)** — Helps avoid accidental messages while typing CJK text on Windows. Early release; behavior depends on the input method.

[Explore by domain](#explore-by-domain) | [Contact](mailto:rickiekuo1203@gmail.com)

## Explore by domain

### Research Systems

[PC-MEF](https://github.com/SpadesZ/PC-MEF) is the public research-code entry point. My other research work includes speech-recognition evaluation and tracking scientific evidence. Laboratory Innovation Brain belongs to this area: its core evidence and revision logic is implemented; lab applications are planned.

### Scientific & Engineering

My background is electrical engineering, with graduate study at National Taiwan University of Science and Technology. My interests include sensor-based research and reproducible experiments.

### Applied Software

The background below describes private work on research-literature workspaces, clinical-evidence prototypes, and data-query tools. RootMedicals remains a prototype with a synthetic demo path; its outputs require review.

### Developer Tools

[Dev Triangle MCP](https://github.com/SpadesZ/dev-triangle-mcp) supports coding-agent handoffs and verification. [Codex IME Enter Guard](https://github.com/SpadesZ/codex-ime-enter-guard) addresses a separate Windows typing problem.

## Technical background and contribution scope

These summaries retain work described in my earlier public profile. Each domain has its own goals, evidence, and status. Dated records describe their original validation scope.

### LAVA work

I am the **AI Architect** of an AI startup in formation, working with its founder to build
**LAVA (LLM-Augmented Validation & Analysis)**.
Within that work, LAVA is a domain-agnostic multi-model control plane. It routes each task (extraction, generation,
verification, reasoning) to a suitable model, checks model health before binding it to a task,
and keeps private data on local models. Each domain plugs in its own knowledge sources,
evidence rules, and acceptance tests; the control plane stays the same.

### Work described in the earlier profile

| Domain | Application | Status |
|---|---|---|
| Research Systems: speech | **LAVASR**: Mandarin-English code-switching ASR with multi-LLM arbitration. Third author; my scope is containerized inference, the GKE Standard + V100 benchmark environment, and staged dry → smoke → official evaluation | Manuscript in preparation for IEEE TCDS |
| Applied Software: clinical medicine | **RootMedicals**: evidence-based-medicine RAG. Literature retrieval, evidence grading, draft recommendations, and human review before publishing | Prototype; includes a synthetic demo path; outputs require review |
| Applied Software: enterprise data | **Secretarix / Querix**: natural-language-to-SQL with AST-level query checking. A secure Text-to-SQL assistant is also running in a tutoring-center management system: the model sees only view schemas, and generated SQL runs read-only under five layers of limits | Customer trial recorded in the earlier profile; no new deployment check here |
| Applied Software: research literature | **roothinks**: from research question and paper parsing to a knowledge space and an editable Word manuscript | Working prototype |
| Developer Tools: decision memory | **Rickie Second Brain**: traceable decision memory; the earlier profile recorded six acceptance criteria and a 24-question regression set | In progress |
| Research Systems: scientific evidence | **Laboratory Innovation Brain**: traceable research-evidence system. Silicon photonics is planned as the first domain pack | Core evidence and revision logic implemented; lab applications planned |

## Research interests

- **Verifiable generative AI**: evidence attribution, evaluation metrics that can fail, and human-in-the-loop review
- **Multi-model orchestration**: when to trust a model's output and when to veto it
- **Speech and language**: code-switching ASR with LLM post-processing
- **Reproducible benchmarking**: pinned data, containers, and GPU environments behind every comparison

## How I work

Each system starts with a written spec (SAI), keeps a decision ledger (NOTE) for choices that need a reason,
and ends with an acceptance matrix that links requirements to runnable checks.
AI agents do much of the implementation. I own problem definition, architecture decisions, and acceptance.

## Access to private repositories

Some projects are private because they contain unpublished manuscripts, customer data, or collaborator material.
Reviewers may contact me at [rickiekuo1203@gmail.com](mailto:rickiekuo1203@gmail.com) to arrange read access.
