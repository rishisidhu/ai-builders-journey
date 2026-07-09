# The AI Builder's Journey

**A self-paced curriculum that takes you from LLM basics to shipping production agents, loops, and RAG systems as a company's AI builder.**

[**Read the curriculum**](https://rishisidhu.github.io/ai-builders-journey/) · Curated June 2026

## What this is

A twelve-stage journey, plus two "new in 2026" interludes. The reading and watching stay deep throughout, while the hands-on exercises start small and grow more demanding chapter by chapter. You don't need machine-learning math. The goal is to wield large language models as a builder who can reason about architecture, cost, reliability, and risk, and who can build the thing rather than only describe it.

Every chapter follows the same five parts:

1. **Why it matters.** The product or business reason the topic exists.
2. **Core concepts.** The vocabulary and mechanics you can explain to an engineer.
3. **Hands-on.** A tiered exercise set (Warm-up, Core build, Level-up) that grows your building skill.
4. **Curated resources.** Blogs, papers, docs, books, and lazy-embedded videos, chosen for signal over volume.
5. **Checkpoint.** Questions to answer before moving on.

## Who it's for

Anyone who wants depth in how AI works alongside the practical ability to build agents, loops, and RAG pipelines: engineers moving into AI, product people, founders, analysts, and self-taught builders. No prior AI experience is assumed. The goal is to become the person a team relies on to build and ship LLM systems.

## How the hands-on works

The exercises compound. Each chapter gives three tiers: a **Warm-up** that confirms the concept, a **Core build** that is the real skill, and a **Level-up** that pulls in earlier chapters. Builds tagged **CARRIES FORWARD** get reused later, so by Part III you are assembling a working system you already built rather than starting something new.

The thread runs like this: token-counting (Ch 1), then a spec and eval set (Ch 2), a context assembler (Ch 3), a chosen use case (Ch 4), a RAG pipeline (Ch 5), an agent that uses the RAG (Ch 6), a loop that drives the agent (Ch 6½), the RAG exposed as an MCP tool (Ch 7), structured-output hardening (Ch 8), cost attribution and caching (Ch 9), evaluation (Ch 10), red-teaming and identity (Ch 11 and 11½), and finally the assembled system you present and defend (Ch 12).

## Curriculum index

### Part I: Foundations
*The vocabulary and instincts every AI builder needs.*

- **Ch 1 · How LLMs Behave.** Tokens, the context window, statelessness, prefill and decode, and predictable failure modes. Start here with Karpathy's videos.
- **Ch 2 · Prompt Engineering and Spec-by-Example.** Turning prompts into testable specifications.
- **Ch 3 · Context Engineering.** Feeding the model the right slice of everything; the four strategies and tool-set hygiene.
- **Ch 4 · Choosing the Right Tool.** Prompt, RAG, fine-tune, or distill: the decision ladder and when each is the wrong fit.

### Part II: Core Builder Skills
*Retrieval, agents, tools, and reliable outputs.*

- **Ch 5 · RAG Architecture.** Chunking, embeddings, hybrid search, reranking, freshness, and Contextual Retrieval.
- **Ch 6 · Agents and Agentic Frameworks.** Workflows versus agents, the core loop, common patterns, and the framework landscape.
- **Ch 6½ · Loop Engineering** *(new in 2026)*. The five-step cycle, the six building blocks, the four-box test for whether a loop is warranted, cost per accepted change, and the build order.
- **Ch 7 · MCP and Tool Design.** Architecture, the tool contract, and how to govern and secure MCPs.
- **Ch 8 · Structured Output and Reliability.** Schema validation, repair loops, and fallback chains.

### Part III: Production and Systems Thinking
*Cost, evals, observability, safety, and architecture.*

- **Ch 9 · Cost and Latency Engineering.** Token optimization, prompt versus semantic caching, latency, routing, and fallback.
- **Ch 10 · Evals and Observability.** Golden sets, LLM-as-judge, retrieval metrics, tracing, and the closed loop.
- **Ch 11 · Safety, Security, and Multi-Tenant Isolation.** Prompt injection, data-leak prevention, isolation, and agent guardrails.
- **Ch 11½ · Human-Agent Teams and Agent Identity** *(new in 2026)*. Supervisor and worker delegation, real human-in-the-loop, and agents as governed non-human identities.
- **Ch 12 · Putting It Together.** Architecture, pipelines, and cost attribution: the capstone, where you assemble and defend the system you built.

### Appendix
- **Standing Sources and Video Library.** The primary feeds to keep current, recommended books, and the full watch-list in one place.

## How to read it

- **On the go.** Open the live link on your phone. The layout adapts and the videos open natively.
- **For focus work.** Open it on a laptop. Click any video card to play it in-page (lazy-loaded, so the page stays fast). The sticky left journey spine tracks where you are.
- **Offline.** Save `index.html` locally and open it in any browser. Everything works except the video previews and web fonts, which need a connection.

It is a single self-contained `index.html` with no build step and no dependencies.

## A note on sources

This curriculum links to and briefly summarizes primary sources from Anthropic, OpenAI, the MCP maintainers, and various academic and engineering publications, and it embeds publicly available videos. Those linked works remain the property of their respective owners. The license below covers only the original curriculum: its structure, writing, and exercises. The field moves quickly, so model names, prices, and version numbers will drift even as the concepts hold. Verify any specific figure before relying on it.

## License

The original curriculum content is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). You are free to share and adapt it, including commercially, as long as you give appropriate credit. Linked articles, videos, and third-party resources are not covered by this license and remain under their owners' terms.

© 2026 Rishi Sidhu. Built as a personal learning resource.
