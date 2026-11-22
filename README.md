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
│   │   ├── 567808adb4d859323424c3a6bc183e13a1ac59e8
│   │   │   └── chunk-001.nq.gz
│   │   └── f47de9688d03411b6e73e6023d21d8335947b46b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f47de9688d03411b6e73e6023d21d8335947b46b.nq.gz
│   └── repolex
│       ├── 567808adb4d859323424c3a6bc183e13a1ac59e8
│       │   └── chunk-001.nq.gz
│       └── f47de9688d03411b6e73e6023d21d8335947b46b
│           └── chunk-001.nq.gz
├── blob
│   ├── 001a87396ad798a181a31f2ecabf08c2c329b23a.nq.gz
│   ├── 0149db11a0b892e879f1d4dec0bc95bcaf16987e.nq.gz
│   ├── 0247c676e2a0439bd654421961baf1d7809fe555.nq.gz
│   ├── 02c54d731c5edc9d730061aa3c9158062a7650a0.nq.gz
│   ├── 0a32754764fdff083402ef9e5b0d896dc1538167.nq.gz
│   ├── 0ae586b2ba84067b29677810f9e43fe69078d392.nq.gz
│   ├── 0c78b314db25721845deb91f231228c1b2cbfbd6.nq.gz
│   ├── 0cfbf08886fca9a91cb753ec8734c84fcbe52c9f.nq.gz
│   ├── 10e5df792b6aabc07a2a613daecf01230a0f0ff3.nq.gz
│   ├── 15317cd5160126e607be538d12f787debc0815ba.nq.gz
│   ├── 18789b8e1d298e7f2cce72d0114279b9dd23529a.nq.gz
│   ├── 192e346f2e0bacac1ca9fd381e5da5fa5da60c01.nq.gz
│   ├── 1a16d726b1bbb5cef95d4cc228fa2701cf85a308.nq.gz
│   ├── 1eba7bd4bebba05184cf5443b232ab8730b0b602.nq.gz
│   ├── 1f4c466383756da7911572ea0dfc5b2a0eebf047.nq.gz
│   ├── 20074851316615bd78b6f9963f77745d2af24582.nq.gz
│   ├── 2705399a4265f4a4e2bfe1753b5e7cbd022d8665.nq.gz
│   ├── 2a525bb27aa93526f364a40056ff825ea87cb9b7.nq.gz
│   ├── 2c6359c1e1813929a4cd30f6d6c0f13653d21d59.nq.gz
│   ├── 2d64d3b1ecd29dc064a415c43a3ced76dbd686c1.nq.gz
│   ├── 2ec425b23683256ffeb7a9b3f1850446ab81d28b.nq.gz
│   ├── 317291fdbe42d049d3ef3574f66d430c3d23fd08.nq.gz
│   ├── 37e36ddfc63cf19c2681e3bf4e21c44f201ddd10.nq.gz
│   ├── 3af722f5a2aa0376b7f70126fe99652be4686161.nq.gz
│   ├── 3bed3597793a4ca40a61bfde7ba50a93e715f61b.nq.gz
│   ├── 4202bee5a1b48a040b43fedf41c293abf33866eb.nq.gz
│   ├── 43b418afdfb6c3c91f984d9192609c5f9f1ccc33.nq.gz
│   ├── 46b8c863b58d22b3b33018dad4cf680aedcc65b1.nq.gz
│   ├── 46ea4822bb8322a500b61d4d4122f8726cc5958c.nq.gz
│   ├── 4c74eb5139844c3f7525dc8e76996d22a75ac884.nq.gz
│   ├── 4f11958e1382de46af482f02547ceaec89b964d1.nq.gz
│   ├── 561251d5b1d5055590ce09414e1585d309dcbc1e.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 5b936718a19b1bb138dfe21394c0197fd59e0667.nq.gz
│   ├── 5c0620f37dbd7a51fe2065da043de8a94b772cb3.nq.gz
│   ├── 5d33a7f7ee58f5346b327520837f3b0401452f20.nq.gz
│   ├── 5db934275ad2f9fdd02b1ec3f782636b3bf83696.nq.gz
│   ├── 5ef04def806e410d7abdd5c37e02ca6bd7b268ea.nq.gz
│   ├── 5ffe57bc0db496f3d6122e8c50cd8af246a4dc20.nq.gz
│   ├── 62e1a580860d24bf7084559b1d6fe769e6bdfbff.nq.gz
│   ├── 64e1fca90dbd5d639184178d54adb1f703733632.nq.gz
│   ├── 6a3925c9669bcc88faa2880225f2175ca3ab0f09.nq.gz
│   ├── 6a9af926d1d76f4c08195348a4e822a0f7fe7feb.nq.gz
│   ├── 6f742ab55e12b708c8200061a4fb7427ecf16595.nq.gz
│   ├── 757b49c040dec7bedc79c323e6a53c8ea71acdd6.nq.gz
│   ├── 7b077cf70dfd69223f4b1813b443ec71825423b7.nq.gz
│   ├── 7c77b03b38a99c7c2ba4d22dfdcff81b4c1df114.nq.gz
│   ├── 7d2559eb4b8ca9ba1ebe85607ad453c77395cbe6.nq.gz
│   ├── 7ed6ff82de6bcc2a78243fc9c54d3ef5ac14da69.nq.gz
│   ├── 805693b0b44d1af0fa63c423e2b8b64d426da911.nq.gz
│   ├── 8137258a005faaf41cba4d445d84bbbfd518d0d1.nq.gz
│   ├── 826ec4da2b91f05016bb59e0a0398473aeb06db9.nq.gz
│   ├── 839c446840b2c951189f0cc2dc56b8aa66e222a6.nq.gz
│   ├── 87384168166a855d41d9128876157ff2fdcffec6.nq.gz
│   ├── 881d4096b4348749ad99fdd02cd74a5d75ea506d.nq.gz
│   ├── 884deb8d0c81b1070cd7d7f7e9b216b2c37c3e96.nq.gz
│   ├── 8b3b3ffa6debec980b4eac0797f36df476daef67.nq.gz
│   ├── 8d955f64bd8665a3eaeaaf80df8531ffeb576ec2.nq.gz
│   ├── 92e656844a688add579e239cfffd0c5c08697c64.nq.gz
│   ├── 95cf45bd0551614a50a2981b72771cbcf77ade64.nq.gz
│   ├── 995e14c4e77a5863f30a0b681809fc1d89ef0c0c.nq.gz
│   ├── 9b08060ca535909b13904140a27378352c4ac8a2.nq.gz
│   ├── 9c461857a26de0f1bed561c45f321df27d190fa2.nq.gz
│   ├── 9d33a4a8b59e68ca1504b03be02ad4c249bf62a1.nq.gz
│   ├── 9d7ad2f82642de825bfecdc6857b0fb77085d070.nq.gz
│   ├── 9dfdd2ed575c161fe158e4b4072534cdf7f04329.nq.gz
│   ├── 9f8b2de9438f026933c527754c15ef01842f30a9.nq.gz
│   ├── 9fc195ba75526bebce6cca3057cb8576d181bd04.nq.gz
│   ├── a05c798a134f0ec04a65b6d4026cc98b57c91acd.nq.gz
│   ├── a0729983e8812e81e62940def4aedf5bb246bd64.nq.gz
│   ├── a0e389c1e14a2096801402036ffa133ccaf5e5a6.nq.gz
│   ├── a1ebbdd194a33e1d8d274a6a5de5407f8eaa1f0d.nq.gz
│   ├── a23a75e3ea077afe7a141b194f03ed74e8d13267.nq.gz
│   ├── a2a4cdcef92e21dc9b957781acba0cbc40fd4e4d.nq.gz
│   ├── a5d78efeaa473725166b7b98f281c5e370da93a1.nq.gz
│   ├── a63df87fead329da47954c1cecfb57faeb049022.nq.gz
│   ├── a87a5e8175d5a9e5bd80b48c85faf431d23bd9c2.nq.gz
│   ├── a9db879098fa35886a2dfa432133503e056c064f.nq.gz
│   ├── aa5692b571fda81fa56faf9b01e0c6245b2d5b9a.nq.gz
│   ├── aa83ac83456ce904114733b4abb4cbd584bcba50.nq.gz
│   ├── af106976a3e80e47a93314fb5a3aa564a347db6a.nq.gz
│   ├── af39efc95034c41ef96eefea43d4c621115c4ffd.nq.gz
│   ├── afe4ddc5392f576188ca546b76bfcd5452ff597c.nq.gz
│   ├── b015ddf82558cc26b882f805ace72a3b6b42070c.nq.gz
│   ├── b094864ab9fb06a95a4bbd9e11ed6b648e255e0f.nq.gz
│   ├── b0cabac8adcecfcc368120d1e9996d8d8e476540.nq.gz
│   ├── b19683dc693185c6ee3625e4e65d92dab369f402.nq.gz
│   ├── b2cdb2de65a4177007f5a115877c5beda1d78b99.nq.gz
│   ├── b506757d35d1648450d7740745d2dbf77fa03d53.nq.gz
│   ├── b5ca3f2d4efd35ac9a1d507499862c639ff3b462.nq.gz
│   ├── b8a263cb31385c54ff11756796b4a54f5d8d586a.nq.gz
│   ├── b945e1cadca44fe991dbddeef1b46ff391bf007e.nq.gz
│   ├── ba1663051201a85807f2171d47f74efb35249dc8.nq.gz
│   ├── ba71655da9de2126e8e6686efe97c6c346324872.nq.gz
│   ├── ba734c9bbccfcd16c889672f270f654616f3036f.nq.gz
│   ├── bc398a164a48a4ff0b0ac19becc7e864d93f0ba9.nq.gz
│   ├── bf98eac116f1ef413073848e601d67c83d203311.nq.gz
│   ├── c2332c4203f699f2d87a075dcc528ec6525527d2.nq.gz
│   ├── c29f80c8d4bbcece93539b63b771f63b43da98b9.nq.gz
│   ├── c4cfff3b579eb6a3fcfa7c3030ba25b8f0d9c036.nq.gz
│   ├── cbcf642440f7e2b81d8906aa285de91ac55cf0c0.nq.gz
│   ├── cc1cfed72f968d19fbd8ca0e9f813e4bed1dcb6d.nq.gz
│   ├── cddfd2db1a76c6e030af257fb04982b8ca44cfe8.nq.gz
│   ├── cf25a729f461c4f8eebb517a54b7c704beb12000.nq.gz
│   ├── cf81330f7fcb54fa31d94da52157d7f4e02d37ce.nq.gz
│   ├── d5505580a127321cf59e48e7c4c34f5b89d003ac.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d85e5e7c7831ced79d351b8d975d523eed17d6e1.nq.gz
│   ├── d91915bc299ef03bdef55dc9c671a6c2bbc51840.nq.gz
│   ├── db96e1fbde99865b5309cf599d8b9b316da859ed.nq.gz
│   ├── dd50c332bcc55ad1432194b302b095c64a08e800.nq.gz
│   ├── deafcac1a482dba58e0cab3bd53a78931ef3e21a.nq.gz
│   ├── e0ed3f81d62d090e0310cc8b0b78042821b12e86.nq.gz
│   ├── e174728f54fd3c99ea7c8b2567f53bf2198c3a19.nq.gz
│   ├── e30b68c9e46dd421b8dda51279483eff90831e43.nq.gz
│   ├── e39721e20f0708703dc6d9b607634636d625e9b2.nq.gz
│   ├── e57425f33b9988cd64936113f720ba4d0917f791.nq.gz
│   ├── e57eb3fad2cb2d50aef92323d7c291986712c55f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e886b4805a85e721e444be9d5dbf297637b00f3f.nq.gz
│   ├── ea7416d535d24456c149e2c7184fad4e8d8366a0.nq.gz
│   ├── ecf95e5d635ff4574073e6183b46c5d7826e5634.nq.gz
│   ├── edca32488eafd6870519499922fa9472932efc73.nq.gz
│   ├── ef7a37eca093fda5ca451abc2e306ba2f7e96b96.nq.gz
│   ├── f1572357d43fb44fc8d4c42845ac65fa50093ab8.nq.gz
│   ├── f172dd0088a30d4165af796b10c09a53228c6d3a.nq.gz
│   ├── f5257261fce6030b6dc6d9fe70d95eba9ab4415e.nq.gz
│   └── f7b9b7c3da6fe46405355e57f9ce33b4aedc705d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── f47de9688d03411b6e73e6023d21d8335947b46b.nq.gz
├── filetree
│   ├── 567808adb4d859323424c3a6bc183e13a1ac59e8.nq.gz
│   └── f47de9688d03411b6e73e6023d21d8335947b46b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 141 files
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
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
