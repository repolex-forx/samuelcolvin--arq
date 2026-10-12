# Repolex Knowledge Graph of samuelcolvin/arq

RDF knowledge graph data for [samuelcolvin/arq](https://github.com/samuelcolvin/arq), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/arq
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5ee4b48cf6faf4dc181f1ccb76dfb1bc1fedf9bf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5ee4b48cf6faf4dc181f1ccb76dfb1bc1fedf9bf
│           └── chunk-001.nq.gz
├── blob
│   ├── 0ea43a0282c44b7daa620fc9431b66175372a5a2.nq.gz
│   ├── 1148591c87fa45fa295b057fc4aa4706d86ae89b.nq.gz
│   ├── 16b5b50730b448fb7ecd059d68f23a91979761d5.nq.gz
│   ├── 24c51ff8a62721f20ce5932609f4d7615dbba38d.nq.gz
│   ├── 29bf49a043390be99a45ab821adc5263657ae5dd.nq.gz
│   ├── 2bc336feab41b3ddd9194b8335f573b347822257.nq.gz
│   ├── 323b1b4a216204ae38d32174bb78130bfeff2ce3.nq.gz
│   ├── 36a046139921f47d5f4f5b95d9b9917c856e8cf2.nq.gz
│   ├── 3d3aa30062b7061167840b7ea693f9be8daff33d.nq.gz
│   ├── 3d3c639e154f0ad313ac7391927574a6e5eb7f0e.nq.gz
│   ├── 441a83eb47434aa49da42279dd3185b175a1a9c6.nq.gz
│   ├── 455963f41782c79a8b56535770d474fc3decb00c.nq.gz
│   ├── 49378efcf1d98863a81251556ba0624961a7c03e.nq.gz
│   ├── 58af8221a95c1f485d95c517daf09b3240814a9a.nq.gz
│   ├── 6a69c6b25344801aaafe7733a0804550a18b2a90.nq.gz
│   ├── 8118ecc6753b09896c609c9ac0e4fb2666e1874e.nq.gz
│   ├── 81c1cf250b26cfc4c056df38fe458c7aa45217cc.nq.gz
│   ├── 84c009aa0f5f5bc93beb6895f177c918e8812fb1.nq.gz
│   ├── 8b8a80cff896bbbb4d7406e3c73cbed62ccee472.nq.gz
│   ├── 8cd98028593c2e78e14eb91bb6446ae0eb3057d3.nq.gz
│   ├── 8e122c90d482577e548935c9d0ecf2ba1eff4acf.nq.gz
│   ├── 8f7d29a57ba341168dd5c69416c4c799dd78996f.nq.gz
│   ├── 936861870fdbf1419dc690132f305705d50b1c0c.nq.gz
│   ├── 96c9a25c8d32dfa51ce83824d2fe9b907535f775.nq.gz
│   ├── 96f6beac8fda6d6bf26c400dbc81e734903ab752.nq.gz
│   ├── 98b00ac75b64b46ce7ca3f476eaaf36e40cc04a7.nq.gz
│   ├── 9bb509ac40161a8d0c33f1229f71590e4756e0d3.nq.gz
│   ├── 9df6183eb840de8678ade1c4a1fd8234687bed04.nq.gz
│   ├── a8a9dc2e3e13b61a5607f97ac83b2279026d43f4.nq.gz
│   ├── b794b92768eb5fa2c925724a0e58be63abba42b1.nq.gz
│   ├── b8a9f0587d30c0401ae88e722ee9e1ea0390ba4e.nq.gz
│   ├── c57f627e25784c84bbd8197ff50ea629d787bbd3.nq.gz
│   ├── c5dd0fc4ac2724a6c18c0b900f1160d40626dbf2.nq.gz
│   ├── d32648cdf8764a2ee54915a6c596d888dc28ec6f.nq.gz
│   ├── d396c2a7cb4a9c69d07b596337b1fffb249c0191.nq.gz
│   ├── d9f5f7289e2ed9c0f4402da52853dcdc66a7e256.nq.gz
│   ├── db4ae7b7bb9e1c54f2a8427bf95616148f232f60.nq.gz
│   ├── e1b5334e6e627a1b294ebbe2c1501d5f8992d235.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ca76e4b0607b18e9e605565a15bbcefac65045.nq.gz
│   ├── ee990eebea85f22147085fde6972c4f8b286fc39.nq.gz
│   ├── f17cd896442ba3bc8a06c3a7cff5b1fcca92e8f3.nq.gz
│   ├── f2229e02ef79ccb3395d14305e8a907ea9f6b8a5.nq.gz
│   ├── f7959e70d6ac3421e45a539fb8331a1bc2ec9d5b.nq.gz
│   ├── fac42f6ac60f9a69fdfe7319ba62390f4b69475b.nq.gz
│   └── feb4a6ade813bf612536d4d15cc41c12589b6307.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5ee4b48cf6faf4dc181f1ccb76dfb1bc1fedf9bf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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

[samuelcolvin/arq](https://github.com/samuelcolvin/arq)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
