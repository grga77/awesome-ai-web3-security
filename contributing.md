# Contributing

Thanks for your interest in contributing! This list aims to be the highest-quality curated resource at the intersection of AI and Web3 security. Quality over quantity — every entry must earn its place.

## Before You Submit

Please read these criteria carefully. PRs that don't meet them will be closed.

## General Requirements

All entries must satisfy **both**:

1. **Real AI/ML/LLM component.** The tool must meaningfully use AI, machine learning, or large language models in its core functionality. Traditional static analyzers, rule-based scanners, symbolic executors, and fuzzers without AI do not qualify — even if they market themselves as "AI-powered."
2. **Web3 security focus.** The tool must specifically target smart contract, blockchain, or DeFi security. General code review tools, general security scanners, and general development tools do not qualify.

## Category-Specific Criteria

### AI Auditors

Tools that orchestrate finding vulnerabilities — you point them at code, they produce findings.

- **Open source entries** must have **25+ GitHub stars** as a minimum signal of community validation.
- **Commercial entries** must provide at least one concrete technical detail about their AI approach (e.g., "trained on X audit reports," "uses GPT-4 + Slither," "multi-agent with Y architecture"). Saying "AI-powered" on a landing page is not sufficient.
- The tool must be **live and usable** — no vaporware, "coming soon" pages, or waitlists.

### AI Agent Toolkit

Components that plug into an AI agent's workflow to make it smarter — data connectors, skills, MCP servers, training frameworks.

- **Must be free and open source.** Paid tools with free MCP wrappers do not qualify. If the underlying service requires a paid subscription, it does not belong here.
- Must have **25+ GitHub stars**.
- Must augment AI security workflows specifically — general development tools and general blockchain data tools do not qualify.

### Runtime Security

Real-time AI/ML-powered monitoring of live blockchain activity.

- **Highest evidence bar.** Entries must provide verifiable proof of AI/ML usage through at least one of:
  - Published ML model architectures or training methodology.
  - Peer-reviewed research papers describing the ML approach.
  - Open-source model code demonstrating ML usage.
  - Granted patents with ML in the claims.
- "We use AI" marketing copy with no technical details is not accepted. Show your work.

### Benchmarks & Datasets

- Benchmarks must specifically evaluate **AI security tools** on smart contracts — not general analysis tool comparisons.
- Datasets must be designed for or widely used in **ML-based vulnerability detection** research.
- Must have **25+ GitHub stars** (for GitHub-hosted entries).

## Formatting

Follow the standard awesome-list format:

```
- [Name](link) - Description starting with uppercase, ending with period. `Tag` (★ 123)
```

- Description should be one sentence, concise, factual.
- No marketing language or unverifiable claims.
- Include delivery mechanism tag where relevant: `` `Skill` `` `` `CLI` `` `` `GitHub Action` ``
- Include pricing tag for commercial entries: `` `Paid` `` `` `Freemium` `` `` `Free` ``
- Include star count for GitHub repos: `(★ 123)`
- Place new entries at the bottom of the appropriate subsection.

## Freshness

Tools should be actively maintained. Abandoned projects (no commits in 18+ months) may be removed during periodic review. Published research tools with stable codebases are exempt from this — a working tool doesn't need frequent commits.

## What Will Get Your PR Closed

- Tool doesn't exist or website is down.
- "AI-powered" marketing with zero technical substance.
- Traditional tool (static analyzer, fuzzer, formal verifier) with no AI component.
- General security tool not specific to Web3.
- Paid tool submitted to the AI Agent Toolkit section.
- Open source entry with fewer than 25 GitHub stars.
- Duplicate of an existing entry.
- Self-promotion without disclosure.
