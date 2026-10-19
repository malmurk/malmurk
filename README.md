# Cătălin Friptu

Applied AI / LLM engineer in Chișinău, Moldova (UTC+2/+3). I design ML and LLM systems, set the eval bar, direct AI coding agents to build them, and decide what ships.

**Public: [agent-ops-harness](https://github.com/malmurk/agent-ops-harness)**, the hooks, federated RAG and model router I run around my coding agents, with the eval method and its limits written down.

Main work, in private repos (pilot projects for a Moldovan marketplace; I can share my screen and go through the code):

- **Hybrid ML + LLM product categorizer.** 84.8% acceptable-set accuracy vs 47.4% for the previous model on a 599-row blind test; 63.6% auto-assigned at 95.5% precision; $0.04 per 1,000 rows.
- **Marketplace buyer app** (React Native, TypeScript), two developers, release candidate: ~2,800 tests and 72 Maestro E2E flows.
- **Agent harness and federated RAG** (supporting): retrieval over 5 knowledge bases with bge-m3 on my own GPU; on a 20-query eval, the model switch plus a chunking-bug fix took recall@1 from 0.467 to 0.733 and MRR from 0.598 to 0.771.

Day job: Support Engineer at Stefanini EMEA. friptu.05@gmail.com
