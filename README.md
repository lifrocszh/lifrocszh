# Hi, I'm Ziheng

I'm a Business Analytics student at the National University of Singapore building systems for search, observability, and AI developer tooling.

My focus is systems engineering: distributed crawling, bounded-memory data processing, and tools that make software behavior easier to inspect.

## Selected projects

### [Scout](https://github.com/lifrocszh/scout) — Distributed crawler and search engine

A Rust system for crawling allowlisted technical documentation and serving search results.

- Coordinator/worker crawling over gRPC, with PostgreSQL-backed task leases, retries, and recovery across worker and coordinator restarts.
- Immutable corpus snapshots and validated index generations with atomic activation.
- Keyword, semantic, and hybrid search through an HTTP API.
- `robots.txt` handling and per-origin concurrency and request-spacing budgets.

### [Logalyze](https://github.com/lifrocszh/logalyze) — Bounded-memory log analysis

A Rust-native log summarizer with a Python API for streaming Apache/nginx combined access logs.

- Reports request and error counts, response sizes, top endpoints and IPs, and UTC error hours without loading the whole log into memory.
- Includes a Python/SQLite fallback when the native binary is unavailable.

### [RunLens](https://github.com/lifrocszh/runlens) — Command execution diagnostics

A Rust CLI for Linux and macOS that observes a command and its descendants.

- Reports CPU and memory usage, process trees, surviving descendants, sampled filesystem activity, and observed network connections.
- Preserves the wrapped command's standard I/O and exit status, with best-effort observation and explicit measurement limits.


## Tools I work with

- **Languages:** Rust, Python, SQL, Java, JavaScript, Bash
- **Systems and storage:** Linux, PostgreSQL, SQLite, gRPC, HTTP APIs, Docker
- **AI and observability:** MCP, FastMCP, LangGraph, Datadog, Azure AI Foundry

## More projects

- [RLM-mcp](https://github.com/lifrocszh/RLM-mcp) — MCP tools for inspecting large files and sending focused context to worker models.
- [video-rag](https://github.com/lifrocszh/video-rag) — A local-first multimodal video RAG scaffold with timestamped retrieval.
- [AI Daily Assistant](https://github.com/lifrocszh/AI_Daily_Assistant) — A meal-tracking and daily-news bot scaffold.
- [Projects](https://github.com/lifrocszh/Projects) — Data science and machine learning notebooks.

## Contact

[LinkedIn](https://www.linkedin.com/in/wangzh516/) · [Email](mailto:wangziheng516@gmail.com)
