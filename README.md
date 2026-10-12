# Repolex Knowledge Graph of executablebooks/rst-to-myst

RDF knowledge graph data for [executablebooks/rst-to-myst](https://github.com/executablebooks/rst-to-myst), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download executablebooks/rst-to-myst
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 10d1edcb965af9451c3cfbb62951a13890a7a672
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 10d1edcb965af9451c3cfbb62951a13890a7a672
│           └── chunk-001.nq.gz
├── blob
│   ├── 097175aa3ecb72ad46a33ab906e2635673bb4d14.nq.gz
│   ├── 11c60dde69a066fa25645ee608cb3317fe88aba5.nq.gz
│   ├── 213625e1f7f6a5ed765ac6e534600e20f9a648dd.nq.gz
│   ├── 2bd62d13f13ccd924b0e84b62ed43c4b3211ac5d.nq.gz
│   ├── 2bf2dbe5f58d665f0cd884452540477d80583275.nq.gz
│   ├── 30021289eba3b1f3e102ec3bcae57d2fa4163eed.nq.gz
│   ├── 30157e00296b9244883447de4c59692789497cc0.nq.gz
│   ├── 36d474e8d24da78f8324d735ab580b6990354998.nq.gz
│   ├── 40e05d2dd04719da37ce47b6f44e71717ee740ea.nq.gz
│   ├── 47135b1c128f14fb4eac57d22611b8bb03ecea09.nq.gz
│   ├── 662ab70993a7b6b8e008ef8a3ba1c5bdbc63212e.nq.gz
│   ├── 6894fcfdfa12b93a22c22a4363ce6fc3532e7cd0.nq.gz
│   ├── 786be571a2fea0343f1107421961f2a24032b85d.nq.gz
│   ├── 7c36e6ae1be823b1f6fdabdc0c3816c8b7e9e503.nq.gz
│   ├── 7d64305c207eaa090fadaa2f6e3eaabc74c4da3f.nq.gz
│   ├── 7daec5166aeab514057329106a402404a7c83d89.nq.gz
│   ├── 7e3ba2b64417b213392e7dbc952375a69bc6b28b.nq.gz
│   ├── 7f5ee87f1821adeadbd2b5da2f9d3054bc1c3f22.nq.gz
│   ├── 847f13ad11aafd76fde247a79eb4d2246b343850.nq.gz
│   ├── 84dfb91b13df917f8b4870a3ff7a23488c9589ce.nq.gz
│   ├── 90fe7626b4b2a5fba443972283d18926ea70da3b.nq.gz
│   ├── 924ca2f3eb0fbd6bde1bc43505cdf75f88c24254.nq.gz
│   ├── 977209f4b5e1db426cedbcb89f0b0ff520eb7a6c.nq.gz
│   ├── 9a13288401640f7f57cd2665102d18b04824bb03.nq.gz
│   ├── 9b91bdef06f9b2a72b603ba777381645a89738da.nq.gz
│   ├── 9d26cf0ca6de16c89d9facd9e5b4e9a2b109410d.nq.gz
│   ├── aac2d5a3aed8d249106b256bd12f17aad460d79b.nq.gz
│   ├── ae820ed7a0d3ae5a9fa104b76fea29753ac030d5.nq.gz
│   ├── b2a38b4f0b6f37c00f7c131f7ec75ace51d988a1.nq.gz
│   ├── be1052cae80c27ebdd5b1e79138544504f51beaa.nq.gz
│   ├── c097215d9e2293e43c8280d8902c903093d58f56.nq.gz
│   ├── c33e1361a6e3006e72c4bc7fe913f226833646f8.nq.gz
│   ├── c4a68dd759188976d1e9bd41b8b811ddf79d381f.nq.gz
│   ├── cd7b64530cf7a35f789d001a20e911a48dd4fb16.nq.gz
│   ├── d9180d4a0f5f725ce6e3d9580b851a4b40876bec.nq.gz
│   ├── d995ed458421fbdac5e488c1e2ee7c4cbef28e09.nq.gz
│   ├── ddd91c2ad78d4030ecca81f628561a472ab179c2.nq.gz
│   ├── dfe0770424b2a19faf507a501ebfc23be8f54e7b.nq.gz
│   ├── e59605a561a96a5a243fb102aaf71536e2b9184f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e831b4116c011a3fd2068fe7fd7d12ac09b4b1ba.nq.gz
│   ├── f0296e7529624486437ae98d2e48cc0c346f316f.nq.gz
│   └── f922081ebec08e54be3873bd88f57da41617200c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 10d1edcb965af9451c3cfbb62951a13890a7a672.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[executablebooks/rst-to-myst](https://github.com/executablebooks/rst-to-myst)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
