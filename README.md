# Ke-Jie Kuo 郭科頡

I build AI systems that coordinate multiple LLMs and can be checked, not just trusted.

M.S. student, National Taiwan University of Science and Technology · B.S. in Electrical Engineering (Communications), Tamkang University

## What I'm building: LAVA

I am building **LAVA (LLM-Augmented Validation & Analysis)** in an early-stage AI venture.
LAVA is a domain-agnostic multi-model control plane. It routes each task (extraction, generation,
verification, reasoning) to a suitable model, checks model health before binding it to a task,
and keeps private data on local models. Each domain plugs in its own knowledge sources,
evidence rules, and acceptance tests; the control plane stays the same.

| Domain | Application | Status |
|---|---|---|
| Speech | **LAVASR**: Mandarin-English code-switching ASR with multi-LLM arbitration. Third author; my scope is containerized inference, the GKE Standard + V100 benchmark environment, and staged dry → smoke → official evaluation | Manuscript in preparation for IEEE TCDS |
| Clinical medicine | **RootMedicals**: evidence-based-medicine RAG. Literature retrieval, evidence grading, draft recommendations, and human review before publishing | In development; clinical workflow demonstrable |
| Enterprise data | **Secretarix / Querix**: natural-language-to-SQL with AST-level query checking. A secure Text-to-SQL assistant is also running in a tutoring-center management system: the model sees only view schemas, and generated SQL runs read-only under five layers of limits | Customer trial |
| Research literature | **roothinks**: from research question and paper parsing to a knowledge space and an editable Word manuscript | Working prototype |
| Decision memory | **Rickie Second Brain**: traceable decision memory with six acceptance criteria and a fixed 24-question regression set | In progress |
| Science and engineering | **Laboratory Innovation Brain**: traceable research-evidence system. Silicon photonics is the first domain pack | M0a complete, M0b in progress |

## Research interests

- **Verifiable generative AI**: evidence attribution, evaluation metrics that can fail, and human-in-the-loop review
- **Multi-model orchestration**: when to trust a model's output and when to veto it
- **Speech and language**: code-switching ASR with LLM post-processing
- **Reproducible benchmarking**: pinned data, containers, and GPU environments behind every comparison

## How I work

Each system starts with a written spec (SAI), keeps a decision ledger (NOTE) for choices that need a reason,
and ends with an acceptance matrix that links requirements to runnable checks.
AI agents do much of the implementation. I own problem definition, architecture decisions, and acceptance.

## Public repositories

- [dev-triangle-mcp](https://github.com/SpadesZ/dev-triangle-mcp): MCP multi-agent workflow control plane. A task counts as successful only when the target repository's real tests pass
- [codex-ime-enter-guard](https://github.com/SpadesZ/codex-ime-enter-guard): Windows helper that prevents accidental submission while CJK input-method composition is active

## Access to private repositories

Most LAVA applications are private because they contain unpublished manuscripts, customer data, or collaborator material.
Reviewers may contact me at [rickiekuo1203@gmail.com](mailto:rickiekuo1203@gmail.com) to arrange read access.
