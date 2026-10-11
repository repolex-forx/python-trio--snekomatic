# Repolex Knowledge Graph of python-trio/snekomatic

RDF knowledge graph data for [python-trio/snekomatic](https://github.com/python-trio/snekomatic), parsed by [repolex](https://repolex.ai).

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
rlex download python-trio/snekomatic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 43e8e6d2602e053a31e6590a6be4511f9bf375b1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 43e8e6d2602e053a31e6590a6be4511f9bf375b1
│           └── chunk-001.nq.gz
├── blob
│   ├── 04a22d885da26e0ca8954cd04a8c7e8f2e98c020.nq.gz
│   ├── 104c402ebf17ef55f9cdca2114f0a4449f6dd039.nq.gz
│   ├── 10bf80af1a277ff0de703b42d8dade382317d626.nq.gz
│   ├── 11949f50921061943be1a6478be9e3f7c02ad2e3.nq.gz
│   ├── 171169484f0936f91f7367db140202951c0046e3.nq.gz
│   ├── 1adb49e8a45464ded6ad167851c6cf308ddbbada.nq.gz
│   ├── 1c760e12070dbb2a3043c95d9cd47775678df025.nq.gz
│   ├── 20537512b01cc0f2f1fc8f80eadb1faf42b25639.nq.gz
│   ├── 2c0156303a8df3ffdc9de87765bf801bf6bea4a5.nq.gz
│   ├── 38828983074bac29a86e3adfd57e1734d6df701d.nq.gz
│   ├── 44d9514eefa8d6ca86d68cce3adff100181d5164.nq.gz
│   ├── 48a4ad348fd408885fc4ec05fb57925f03dfcfe7.nq.gz
│   ├── 493ee1896808a865e0b680d08c81e2d0bb498893.nq.gz
│   ├── 4f5645e0a2378031862847a3abd73850621e9869.nq.gz
│   ├── 51f3442917839f8e0f0cccb52b3c10968ad0779e.nq.gz
│   ├── 58e2dd47472b768891ba50f9593598bd1a9cca5f.nq.gz
│   ├── 5cf58523f64ed0de9e4b315cde67a34f9787c288.nq.gz
│   ├── 5fa16570ff87aebb4dcf8997688a4143263e9409.nq.gz
│   ├── 681108d9b33ff387b2a50eb909af21b9cab6ed19.nq.gz
│   ├── 6ad96706ef8ef33f5f046755c39378e78d717152.nq.gz
│   ├── 6d839121d5a5b5de6222b3537496f0433b7c484d.nq.gz
│   ├── 6f651a3b1c6c3883792309809b8fbdcb4df23cb0.nq.gz
│   ├── 736182ce3018896d38736bc153b7ddd6195b2683.nq.gz
│   ├── 768e5781c02aae9ce3e5b61160de312db389f613.nq.gz
│   ├── 7ee85ad2bc3ee81de422c6c91e9aaca689cba237.nq.gz
│   ├── 89e7591445a3a96ef24f8b267f6c99cee9892c8d.nq.gz
│   ├── 8b61667ec38361235ed2f964f34a7f1ab5cae585.nq.gz
│   ├── 8e0b3c6e8a1a52c953184b037e22e4bde0cdc7b4.nq.gz
│   ├── 8eb2678c6a39b65aeee7f8bc066c8a8124063a24.nq.gz
│   ├── 945ab80ad47c7654819c309c83a16b2b4f634ece.nq.gz
│   ├── a0b9b4cd2aace181284eb35a72e6c7f628179367.nq.gz
│   ├── a3a9b42f26c82ee8407b96cb021db65c1ba844f0.nq.gz
│   ├── b73dd4e243a8d9c8d251c3f1f3fa91e627dbd770.nq.gz
│   ├── b8bb97185926d7daed314609753173945ed4ff1a.nq.gz
│   ├── bf13533b5939cbfae0abd37bdbc30e3dbf46efed.nq.gz
│   ├── c2abb381ae8489ea478201e85181931ea5868ad1.nq.gz
│   ├── c425f7d18b811c9614245969e2042be9b96a5e76.nq.gz
│   ├── c97f75a0bbc56cc87539ffdd93c0b5a17909e75b.nq.gz
│   ├── cbf29db714fbb71bb89230599af5ae2bfe6c3d1e.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── dcd003369dcffafbed26728f98c01c8b81f10987.nq.gz
│   ├── e585d0d3bed7402d478e76e954b10950057d21dd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e97d6f126ba8fc82d85c15b73e03f7e939b70142.nq.gz
│   ├── f38c5167733eb2fd1cb677450f876788a4aa603e.nq.gz
│   ├── f6e83bd799cd7f5f9dd1425990b696ae8ac768a7.nq.gz
│   └── fcfcf0d2cfe1bcbc61d3b0d502b732f3fb2e03a8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 43e8e6d2602e053a31e6590a6be4511f9bf375b1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[python-trio/snekomatic](https://github.com/python-trio/snekomatic)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
