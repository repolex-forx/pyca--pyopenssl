# Repolex Knowledge Graph of pyca/pyopenssl

RDF knowledge graph data for [pyca/pyopenssl](https://github.com/pyca/pyopenssl), parsed by [repolex](https://repolex.ai).

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
rlex download pyca/pyopenssl
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 567808adb4d859323424c3a6bc183e13a1ac59e8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 567808adb4d859323424c3a6bc183e13a1ac59e8
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a32754764fdff083402ef9e5b0d896dc1538167.nq.gz
│   ├── 10e5df792b6aabc07a2a613daecf01230a0f0ff3.nq.gz
│   ├── 15317cd5160126e607be538d12f787debc0815ba.nq.gz
│   ├── 1a16d726b1bbb5cef95d4cc228fa2701cf85a308.nq.gz
│   ├── 1eba7bd4bebba05184cf5443b232ab8730b0b602.nq.gz
│   ├── 1f4c466383756da7911572ea0dfc5b2a0eebf047.nq.gz
│   ├── 2c6359c1e1813929a4cd30f6d6c0f13653d21d59.nq.gz
│   ├── 2d64d3b1ecd29dc064a415c43a3ced76dbd686c1.nq.gz
│   ├── 317291fdbe42d049d3ef3574f66d430c3d23fd08.nq.gz
│   ├── 3bed3597793a4ca40a61bfde7ba50a93e715f61b.nq.gz
│   ├── 4202bee5a1b48a040b43fedf41c293abf33866eb.nq.gz
│   ├── 43b418afdfb6c3c91f984d9192609c5f9f1ccc33.nq.gz
│   ├── 46ea4822bb8322a500b61d4d4122f8726cc5958c.nq.gz
│   ├── 561251d5b1d5055590ce09414e1585d309dcbc1e.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 5c0620f37dbd7a51fe2065da043de8a94b772cb3.nq.gz
│   ├── 5db934275ad2f9fdd02b1ec3f782636b3bf83696.nq.gz
│   ├── 5ef04def806e410d7abdd5c37e02ca6bd7b268ea.nq.gz
│   ├── 64e1fca90dbd5d639184178d54adb1f703733632.nq.gz
│   ├── 6f742ab55e12b708c8200061a4fb7427ecf16595.nq.gz
│   ├── 7b077cf70dfd69223f4b1813b443ec71825423b7.nq.gz
│   ├── 9b08060ca535909b13904140a27378352c4ac8a2.nq.gz
│   ├── 9c461857a26de0f1bed561c45f321df27d190fa2.nq.gz
│   ├── 9f8b2de9438f026933c527754c15ef01842f30a9.nq.gz
│   ├── 9fc195ba75526bebce6cca3057cb8576d181bd04.nq.gz
│   ├── a05c798a134f0ec04a65b6d4026cc98b57c91acd.nq.gz
│   ├── a23a75e3ea077afe7a141b194f03ed74e8d13267.nq.gz
│   ├── a2a4cdcef92e21dc9b957781acba0cbc40fd4e4d.nq.gz
│   ├── a5d78efeaa473725166b7b98f281c5e370da93a1.nq.gz
│   ├── aa5692b571fda81fa56faf9b01e0c6245b2d5b9a.nq.gz
│   ├── aa83ac83456ce904114733b4abb4cbd584bcba50.nq.gz
│   ├── af106976a3e80e47a93314fb5a3aa564a347db6a.nq.gz
│   ├── b015ddf82558cc26b882f805ace72a3b6b42070c.nq.gz
│   ├── b2cdb2de65a4177007f5a115877c5beda1d78b99.nq.gz
│   ├── b5ca3f2d4efd35ac9a1d507499862c639ff3b462.nq.gz
│   ├── b8a263cb31385c54ff11756796b4a54f5d8d586a.nq.gz
│   ├── b945e1cadca44fe991dbddeef1b46ff391bf007e.nq.gz
│   ├── ba1663051201a85807f2171d47f74efb35249dc8.nq.gz
│   ├── ba734c9bbccfcd16c889672f270f654616f3036f.nq.gz
│   ├── bf98eac116f1ef413073848e601d67c83d203311.nq.gz
│   ├── c2332c4203f699f2d87a075dcc528ec6525527d2.nq.gz
│   ├── c4cfff3b579eb6a3fcfa7c3030ba25b8f0d9c036.nq.gz
│   ├── cc1cfed72f968d19fbd8ca0e9f813e4bed1dcb6d.nq.gz
│   ├── cf25a729f461c4f8eebb517a54b7c704beb12000.nq.gz
│   ├── cf81330f7fcb54fa31d94da52157d7f4e02d37ce.nq.gz
│   ├── d5505580a127321cf59e48e7c4c34f5b89d003ac.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d91915bc299ef03bdef55dc9c671a6c2bbc51840.nq.gz
│   ├── dd50c332bcc55ad1432194b302b095c64a08e800.nq.gz
│   ├── e0ed3f81d62d090e0310cc8b0b78042821b12e86.nq.gz
│   ├── e57425f33b9988cd64936113f720ba4d0917f791.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea7416d535d24456c149e2c7184fad4e8d8366a0.nq.gz
│   ├── edca32488eafd6870519499922fa9472932efc73.nq.gz
│   ├── f172dd0088a30d4165af796b10c09a53228c6d3a.nq.gz
│   └── f7b9b7c3da6fe46405355e57f9ce33b4aedc705d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 567808adb4d859323424c3a6bc183e13a1ac59e8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 64 files
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

[pyca/pyopenssl](https://github.com/pyca/pyopenssl)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
