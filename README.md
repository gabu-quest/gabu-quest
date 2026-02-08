# gabu-quest

**EN** | Building tools that make messy data behave.
**JP** | 散らかったデータをおとなしくさせる道具を作っています。

---

## What I Do / やっていること

Backend systems, data tooling, and the kind of automation that saves someone's weekend.
バックエンドシステム、データツール、そして誰かの週末を救う自動化。

- Python, FastAPI, SQL — the usual suspects
- Databases: SQLite, DuckDB, Postgres
- Obsessed with correctness and systems that outlive their creators

Python・FastAPI・SQL を中心に、正しさと長寿命なシステムを追求中。

---

## Projects / プロジェクト

### SQLer

Micro-ORM for SQLite. JSON-first, Pydantic-native, no ceremony.
SQLite用マイクロORM。JSON中心、Pydanticネイティブ、余計な儀式なし。

- Document-style models backed by SQLite's JSON1 extension
- Fluent query builder, FTS5 full-text search, relationship hydration
- Async + sync APIs, connection pooling, schema migrations
- Optimistic versioning for concurrent writes
- 11 interactive browser tours via Pyodide/WASM — no install needed
- Benchmarked: 84K rows/sec bulk insert, 470x index speedup, 0.28ms FTS

[Repository](https://github.com/gabu-quest/sqler) · [PyPI](https://pypi.org/project/sqler/) · [Interactive Tours](https://gabu-quest.github.io/sqler/)

### SQLer CLI

Persistent memory for LLMs. Store, search, and retrieve context across sessions.
LLM用の永続メモリ。セッションを跨いでコンテキストを保存・検索・取得。

- FTS5-powered search over stored memories
- Tagging, session organization, linking, deduplication
- Built on SQLer — dog-fooding all the way down

[Repository](https://github.com/gabu-quest/sqler-cli) · [PyPI](https://pypi.org/project/sqler-cli/)

### Procler

Process manager built for AI coding agents. One tool to run everything.
AIコーディングエージェント向けプロセスマネージャー。すべてを一つのツールで管理。

- JSON-native CLI designed for Claude Code integration
- Vue 3 web dashboard with real-time WebSocket updates
- Local shells and Docker containers under one roof
- Health monitoring, groups, recipes for multi-process workflows

[Repository](https://github.com/gabu-quest/procler) · [PyPI](https://pypi.org/project/procler/)

### SSHler

SSH multiplexer with tmux-in-browser. Local-only, nothing exposed.
ブラウザでtmux操作できるSSHマルチプレクサ。ローカル専用、外部公開なし。

- FastAPI-powered, HTMX-based file browser over SFTP
- Browser terminal sessions — no extra software on remote hosts
- Works with existing SSH keys and OpenSSH aliases
- Cross-platform, zero-config on the remote side

[Repository](https://github.com/gabu-quest/sshler) · [PyPI](https://pypi.org/project/sshler/)

### Logler

Log viewer with teeth. Thread tracking, correlation IDs, Rust-powered investigation engine.
本気のログビューア。スレッド追跡、相関ID、Rust製の調査エンジン。

- Rich terminal output with hierarchical visualization
- Bottleneck detection across distributed systems
- Multiple log format support
- Optimized for AI agent consumption

[Repository](https://github.com/gabu-quest/logler) · [PyPI](https://pypi.org/project/logler/)

### Logler Web

Web UI for Logler. Vue 3 + DuckDB in the browser.
Logler用WebUI。Vue 3とブラウザ上のDuckDB。

- Virtualized rendering for massive log files
- Multi-file interleaving, filtering, real-time WebSocket tailing
- Waterfall and hierarchy visualizations
- SQL queries over logs via in-browser DuckDB

[Repository](https://github.com/gabu-quest/logler-web) · [PyPI](https://pypi.org/project/logler-web/)

---

*Tools should be sharp, docs should be honest, and software should work when nobody's watching.*
*道具は鋭く、ドキュメントは正直に、ソフトウェアは誰も見ていない時でも動くべき。*
