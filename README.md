# Repolex Knowledge Graph of UKPLab/GroundInc

RDF knowledge graph data for [UKPLab/GroundInc](https://github.com/UKPLab/GroundInc), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/GroundInc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d0b0f201125b5759161dbf91a0a0c2a584450d03
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d0b0f201125b5759161dbf91a0a0c2a584450d03
│           └── chunk-001.nq.gz
├── blob
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 0e4765dfaea62bf86d9514a1cf4b76c9f5cfcabd.nq.gz
│   ├── 0fbd9262d9e4ed6d107ae11e01ff15bcaf0ec85a.nq.gz
│   ├── 101220a85901bf739582d029d086123422441f1d.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 144c1e713381b7e41c476fc67fcc006ba7d4d55d.nq.gz
│   ├── 160f1c0939241067ae4afd04ad4151749af2ce8c.nq.gz
│   ├── 1c230ce3e2f8b81fc21e0f4f6c795641b1e4a240.nq.gz
│   ├── 243a79675c4662d3f001e57a3c26a481c26fae44.nq.gz
│   ├── 24957d820a1119837b3a2c0077aaee9a8148c15c.nq.gz
│   ├── 24bc62996ca8aa9069062c967902d6954eba4a3d.nq.gz
│   ├── 2521f53098dab4eb1240d8a408d8fc3a5fd87df5.nq.gz
│   ├── 2af6f44018cb3ee31c8673826e1cec845d8b5450.nq.gz
│   ├── 2c8ba5cc7d2d5d932ebc04bb5dbcd73296bffe55.nq.gz
│   ├── 307813bcd52faa8b1b1e619e5280ce5ef70f1442.nq.gz
│   ├── 314fe89dc14500f436bcdfad573f17c25c14b5a0.nq.gz
│   ├── 3654e1eea01d3ca9944e1d656994f82769a90884.nq.gz
│   ├── 385237a45d5b8737692458e60431b8fd088c8ac3.nq.gz
│   ├── 3b8b913c837aa39e199dc94be9a8f9f89e669cb5.nq.gz
│   ├── 3c1c85838aee0ba5fe7cc82b13b1f472ee00d51e.nq.gz
│   ├── 3d95858c391d25230a20c74566956eef5b96818c.nq.gz
│   ├── 4257636f05fcfb6786b07225432f4fc4e9d17c28.nq.gz
│   ├── 434c5459a4249ae912039be58b97c535aeea5075.nq.gz
│   ├── 440fcba5ef0afa5307fbaa6f913f87582169cfd6.nq.gz
│   ├── 4620d58c3e11b9933b3a05493ae5121fcbc1ec1b.nq.gz
│   ├── 4f82c92b1883e0e46b2123310c080923cce37fcb.nq.gz
│   ├── 543a475cf459af532aab107026509f619e8ba1e6.nq.gz
│   ├── 56441bbcdd5b403d0b52cab1c356d4585a914456.nq.gz
│   ├── 56b9c38624e9e8f1e0c02867d5d50cdb9808cab1.nq.gz
│   ├── 570cf688f73d6a8de6c9596fff687fc462b81162.nq.gz
│   ├── 58c0109d95fcf2feaf30b9693513f7e53f984bcc.nq.gz
│   ├── 5dcef726f671e400c7a0873dc8e9d9f061889630.nq.gz
│   ├── 6004f010613de77b8daad84bef7435d838a97abc.nq.gz
│   ├── 613128fe8a7f0a01670f73b595552bc19fd171c9.nq.gz
│   ├── 67be2ae5ab000cc3f46bd6542ef25183e1378154.nq.gz
│   ├── 6b8ade6fc0077d677a5e09bca1c774c5eff20025.nq.gz
│   ├── 70f9a51a6724b350b1354cac8940cfa5e6f335ba.nq.gz
│   ├── 7193265c067257ace29f5626f4b4d439fb8f0019.nq.gz
│   ├── 79c43743dcb2ddad4fe91bd57e3c76fb426066a4.nq.gz
│   ├── 7a3122c4f4ee649207cc8bff4406c741cfd9d527.nq.gz
│   ├── 7fbd4b93b954f05797921d96116f226fe5a31a73.nq.gz
│   ├── 81ea7ff2c1c78c27c7e362e7ebbc2df6128a2f7a.nq.gz
│   ├── 84806011c5df6cb2432bdf8892b91239d38a8e76.nq.gz
│   ├── 8d1e35ab24c87c27ae1cc1b1307cbc1c053cdf2d.nq.gz
│   ├── 930a5bb1425758d6160a0564b904210b7422bbae.nq.gz
│   ├── 945228d0940aa7f8d21ad262e470c288f8a8253e.nq.gz
│   ├── 9bf1156f1300557be8d78e903a752c37aee737cc.nq.gz
│   ├── a33e09464f3f4002782d8d6b909200a78e3ed708.nq.gz
│   ├── a8d3a7c26fec9c5f8b0647f299ed6becb3372baa.nq.gz
│   ├── a9266405fe092e0b67a088438f6ec85338036338.nq.gz
│   ├── a99fb77bc4ffa7872e3177c8967af803e8b68961.nq.gz
│   ├── ab330b8efe4ce272c1f0e4ff23675e8b84d9308a.nq.gz
│   ├── aeeaaf71d3410102f28ab259fa7421a5b3df5141.nq.gz
│   ├── b2f443859c37be1d2cdf9c608bd00e525a79e7dc.nq.gz
│   ├── b437a555d782b4b7cf4f01b029db43688d217324.nq.gz
│   ├── b6e37aaee122f591d2cfae173134e4d882402ad6.nq.gz
│   ├── b7e1d5e3d62d2439a2b7b9a2f9befd936640b05e.nq.gz
│   ├── c0ecae199ac4dbdc198cfca6a5197196d03364fc.nq.gz
│   ├── c328554246f70a6c14d9f27d435c644cf9a54770.nq.gz
│   ├── c4161bd8e908bcd06d9a5ef80fc9adf4cff378e3.nq.gz
│   ├── c7a351776c6d721e4c4b745d42d4091fc5346cc1.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── d3905c482a5f1d2352642e76c81703baf64dcf50.nq.gz
│   ├── d635904aceb98adc78448db8084261f692c69f49.nq.gz
│   ├── d6dc7e93e419ce72d3042034d9745cbb8f27227d.nq.gz
│   ├── e92a69ba6eb5d6325a175646e1de808c31dd9fb9.nq.gz
│   ├── ed408d8ef5ae0e48f2eec2d23d2bab15fcddfabf.nq.gz
│   ├── f3a52d10474c69115a5c23f8ef579e8755589182.nq.gz
│   ├── f8975ce0548993bb4ea5f6e6bfab181b57a6a3e9.nq.gz
│   ├── fb99a19131ec34d0593106206d30325af83a05e9.nq.gz
│   ├── fe0bc475cfc6ea64d651725b4ca4faa1fcba84ce.nq.gz
│   └── ff8e994b3d4f79deb6c628fd0bd2a14a5b9aa49f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d0b0f201125b5759161dbf91a0a0c2a584450d03.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 79 files
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

[UKPLab/GroundInc](https://github.com/UKPLab/GroundInc)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
