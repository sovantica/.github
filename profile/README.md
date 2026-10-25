# Sovantica

**Cognitive infrastructure for AI agents.**

We build the substrate AI agents run on - memory, reasoning scaffolds, verifiable state. Starting with the hardest part: memory that doesn't collapse under context-window limits, and that an agent can actually reason over.

## What we ship

**[Engrava](https://github.com/sovantica/engrava)** - the memory database for AI agents.

An in-process Python library over one SQLite file: a queryable memory graph with bi-temporal valid-time predicates, and no generative-model call in the core write path. Seven edge types, hybrid FTS5 + vector search, consolidation from six fixed signals, a SHA-256-linked thought/edge journal.

```bash
pip install engrava
```

- **[engrava-mcp](https://github.com/sovantica/engrava-mcp)** - MCP server for Engrava, over stdio.
- **[engrava-benchmark](https://github.com/sovantica/engrava-benchmark)** - runners and results; reproduce our [published numbers](https://engrava.ai/benchmarks/) against the package from PyPI.

MIT licensed | [engrava.ai](https://engrava.ai) | [docs](https://docs.engrava.ai)

## How we work

- **Code-first.** Every claim is backed by implementation. No whitepapers without running code.
- **Research posture.** We draw on prior work in cognitive science, neuroscience and algorithms. Where we cite, we cite; where we deviate, we explain why.
- **Open by default.** Primary artifacts ship under MIT; questions go to GitHub Discussions.

## Elsewhere

- Studio: [sovantica.ai](https://sovantica.ai)
- Engrava: [engrava.ai](https://engrava.ai)
- Contact: [hello@sovantica.ai](mailto:hello@sovantica.ai)
- Security: [security@sovantica.ai](mailto:security@sovantica.ai), see [SECURITY.md](../SECURITY.md)
