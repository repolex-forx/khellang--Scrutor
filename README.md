# Repolex Knowledge Graph of khellang/Scrutor

RDF knowledge graph data for [khellang/Scrutor](https://github.com/khellang/Scrutor), parsed by [repolex](https://repolex.ai).

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
rlex download khellang/Scrutor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7f315dab5b0f7134a6be58941db1da8c904507e2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7f315dab5b0f7134a6be58941db1da8c904507e2
│           └── chunk-001.nq.gz
├── blob
│   ├── 02c127c150cc1b1a21e2389c88c10c601a40ded0.nq.gz
│   ├── 1545876554ac3894b04e2f76b41bcf840964fa54.nq.gz
│   ├── 1618e3d1c45f253407c8876aecb020307079f54e.nq.gz
│   ├── 1a59a793980b38f1b78417893faa869be7d05a93.nq.gz
│   ├── 2158275cf8f3e43d323e3616ca91ad464db6cf01.nq.gz
│   ├── 24c759bf9ca24d80c22283df1a497078a5c31c1f.nq.gz
│   ├── 28c7b54ad56919f35339199518cd9e2a39dd9ca3.nq.gz
│   ├── 3df56f52e9241bc9f847a3df5b4c86308d9c83f3.nq.gz
│   ├── 3e07acd8ba4abd1ff6374347f322cf00afa82c67.nq.gz
│   ├── 47e8965a24dae2dca8099b5af5567dd3935f09b9.nq.gz
│   ├── 486281609ff6c1022d3a5ab16ecf97dff5625953.nq.gz
│   ├── 49e5582685a2305656ef062cf2d94ab06e757324.nq.gz
│   ├── 56a18b7e77221b4a12aa71784b57be64cdce138c.nq.gz
│   ├── 5afe35d4716c4f037262b410ed0bc0e6689b0c6d.nq.gz
│   ├── 5e83ebf3cdc31f27b45b5986f00eef31d94690a7.nq.gz
│   ├── 61b96fc2a4c1cdb6a05d66f4a80a99aa84178dd0.nq.gz
│   ├── 627cb40a0591d0c95f4e5f52c28606a8caeed8c9.nq.gz
│   ├── 62da015f61877a50492034fb5eb29b6658934e61.nq.gz
│   ├── 6388d3cc1070d49a2fc6bc59165990ce0ff6429e.nq.gz
│   ├── 6604ba06a9a89ce35e8fc0c1223db614ef36f2f7.nq.gz
│   ├── 66c1b372710f91242297411217787eb1b32fb19a.nq.gz
│   ├── 67b7fbc23be217e94ebc8820c1565177aa1565ea.nq.gz
│   ├── 6a6cb841296a10e6b7eb1d18cd3aa5714b67755c.nq.gz
│   ├── 6b5545636f7874d221495ab4a0fb5b5215d0fd21.nq.gz
│   ├── 6bd4065aa308f32c44351acf4079174ac728d957.nq.gz
│   ├── 6dac1a6075d0bec89c09eb2a4712dbf80863ffc3.nq.gz
│   ├── 6dbd7fa27dbfecacd6b902d2f45cea2633262fec.nq.gz
│   ├── 74ee08ac6a2471768ff5dc56b09ea762dbbdd8eb.nq.gz
│   ├── 76f8345da3e19b8a4466dd8fa2cf8b92e47dd315.nq.gz
│   ├── 7bbd69c7394d4f5825346f0fe6d045e71c163d4c.nq.gz
│   ├── 7dc8d0151298e4bba6c9d89944e57e4930a2903d.nq.gz
│   ├── 80ab91eec23bb414181fb63d1451c6d7597c81e6.nq.gz
│   ├── 84ce9756afae488d6d9b8214b83f8b612fae2859.nq.gz
│   ├── 8e1b446d1a9def5a0c7ae2c586796566ad86187b.nq.gz
│   ├── 8f96427a3a9dbe6541b1ab8bf373fa369ecace89.nq.gz
│   ├── 9b86bdf8439bbedf20f33f50a14e118857436f00.nq.gz
│   ├── 9bab980d6c18d97dbc1bafd3a48b74cc24289938.nq.gz
│   ├── 9c6253a7ffa3db3c0bf193cbe0685faaf73a6cc5.nq.gz
│   ├── 9e7998d2909cb565f6e8302bca19b1e21b913b89.nq.gz
│   ├── a87832c31b1774f7516ecaf9ff1fee708ff70ce8.nq.gz
│   ├── a8e30f666996768d9cf69d4e0d17c0c8e4282b79.nq.gz
│   ├── ae29a124ae257cead4767ec430e79cf94c711e42.nq.gz
│   ├── af3ee630fbbf3cde92aaec9556613d7c9f4c9b28.nq.gz
│   ├── b161e6296aed41672dad37b1fc2536f9ae077b07.nq.gz
│   ├── b28c003ecb2a567ad6560706994793a1e5dcc909.nq.gz
│   ├── b90fe69f8e4423a4a2a6679a19cab990825c65e5.nq.gz
│   ├── bd7fe731a54b8a6adf7ce8f8709cb417500ecb89.nq.gz
│   ├── bda4e6d0ef85c1020fc1aef2a1d9cfb774bb6d61.nq.gz
│   ├── c971e55224dec0c2cfa1a664b9f3d59876c72e78.nq.gz
│   ├── caf24de8b77f2f71472000094aa68a233f7f1f39.nq.gz
│   ├── d9625893001aa280c6df42165b428df21affcd1d.nq.gz
│   ├── da9c516dd744b6c88dd8c91f58f7bcf8f7e8341b.nq.gz
│   ├── db6546c4a59edd304c49698d116353aea87213d4.nq.gz
│   ├── db6f338345cd633262315a6a95856ed5072c3e0b.nq.gz
│   ├── dc389c8610164cd535016671589607f28e71f456.nq.gz
│   ├── e0ddda006c63cef2662ab8f359019119c70fbdbf.nq.gz
│   ├── edddb0bce77265b74c74bcdb123ec0d681550106.nq.gz
│   └── f9db7b4853993fd0a839ace0e39119bd257e30a5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7f315dab5b0f7134a6be58941db1da8c904507e2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 66 files
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

[khellang/Scrutor](https://github.com/khellang/Scrutor)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
