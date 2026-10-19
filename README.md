# Repolex Knowledge Graph of lepture/captcha

RDF knowledge graph data for [lepture/captcha](https://github.com/lepture/captcha), parsed by [repolex](https://repolex.ai).

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
rlex download lepture/captcha
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 087b30be72640802fddc097472ef35a88020387a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 087b30be72640802fddc097472ef35a88020387a
│           └── chunk-001.nq.gz
├── blob
│   ├── 061ed22ca8dcc9787334bce9301706eb3a4bf4e1.nq.gz
│   ├── 0a217dd484509ec61bf815cb08ca33f592baff09.nq.gz
│   ├── 0e7137517330038a097d267a2fc0e5de18602245.nq.gz
│   ├── 0ea99e3c626430496e65d670877dd1cdd9ecb945.nq.gz
│   ├── 10f97c7c2c99184ec1b2fe423a6e937c896a79eb.nq.gz
│   ├── 169b734128e027fe544937de58c595b0e1034e8c.nq.gz
│   ├── 1bef6ea794f469717f3f9dee54850a93b285b66c.nq.gz
│   ├── 2b32ab2d1db4975ed6ee9e813ae44bb005fa92c1.nq.gz
│   ├── 2c6c74f1c1d903c72b375b64947bc4695c7bd304.nq.gz
│   ├── 2ce6ea818aa282c2ebd9382b5c49426890910328.nq.gz
│   ├── 2d38c4ee6f16397dd4d27c026200969b8fcc9a1d.nq.gz
│   ├── 2fdcb1668f8a0057b8c9586bf7b8d3befee7761b.nq.gz
│   ├── 32f39f2083213880d8243bb201d7d69cde4f7a62.nq.gz
│   ├── 36ba39e522018c82f51c7ad251da68c88ea0c612.nq.gz
│   ├── 3831937e5e0d0cb810b4b0d777a0c8f8208c9a71.nq.gz
│   ├── 3fdb89909a5b6355e22f301fdbc67bcd3e1313df.nq.gz
│   ├── 43b404b7e403f6e4b6bdb14cb0e33962ea4e9a73.nq.gz
│   ├── 4746fce9c4b5d537b0fc686e192e3c916b9f1fce.nq.gz
│   ├── 4e6afde01014a917867a5326673970f3ec89c70c.nq.gz
│   ├── 50b28ebb0ffa81e1be7c0dd827f7593476127fae.nq.gz
│   ├── 5384de88c7df0b2aecd177955ff2ad2b3f09f29f.nq.gz
│   ├── 5d66c12fecc85d383a32ebb6eeaf8ed359c12139.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 6d41c11cdae4340e2af362730d5562b0f8041d1d.nq.gz
│   ├── 6e3af66dee75f0bdaefc71182b23ebfdee5618fa.nq.gz
│   ├── 6f4b9a7c5cfa0133a8bc83d02e3ef3c85aa055bd.nq.gz
│   ├── 726e6e2e78c9bd6667a7b0f4186573034884d555.nq.gz
│   ├── 73c7c7554fff88221101afa8d3b8c869c03c40f4.nq.gz
│   ├── 73c9ec4912bd320312a1205eb914bcd0ae487650.nq.gz
│   ├── 772edeee7d858c6d0aa17aecc78d1a1fe4fe66ca.nq.gz
│   ├── 7c87c0799b6185aa42c27696e3435a09a12300e9.nq.gz
│   ├── 7d52c89b390ebee79475450be9b6a818d456b86d.nq.gz
│   ├── 7edb32cebcb5420694b617e39f08178179e410f4.nq.gz
│   ├── 8579958646420526a2e5a66380c283e512023495.nq.gz
│   ├── 86ca11f7b8a08e5785498b76940b4edcd36cf441.nq.gz
│   ├── 8eb6c39fbc8b6a9e69872a2177545d5dd1f76ed7.nq.gz
│   ├── 90aa5b2f4726d570dc9edb5ad764e75ef95be6e0.nq.gz
│   ├── 95b9fac576d845e0e585547b0db24947341847d7.nq.gz
│   ├── 963453c0a4a47803628aed7091ecb83837d1264f.nq.gz
│   ├── 96ea53baa67243642c27b1f98ac0678949f84c79.nq.gz
│   ├── 9c277ab3487d784a1cfe0fba2a57f69179f2a435.nq.gz
│   ├── a0d9acd54caef3e0aeedd84128f3bb87d3ebc61f.nq.gz
│   ├── a0e574f232c2b5d1b3ad61c7664535bf00e8c27d.nq.gz
│   ├── a0f45d9ec2c147693c2011b7a2bf1255e50ee2ad.nq.gz
│   ├── a1265db2ce603834c5b92577065ece484f6a3530.nq.gz
│   ├── a5b213b0d21c9e6f5c9c342eb9fd14d655fbc374.nq.gz
│   ├── ac7398019a15b9df69896c3e4275702eada15b4a.nq.gz
│   ├── b141cdb9f3cb8010b9c3dfb392ff1a00db58a413.nq.gz
│   ├── b66e19446992d091bd897fe4d8b202b990500cc6.nq.gz
│   ├── b7042865be31d02252c7c1c51a02e9aeb47def8c.nq.gz
│   ├── ba69a71242548ea3c5eba5d6e54a35418842b229.nq.gz
│   ├── c05d026ae6c48c96c54c5b62d3d8886529611d1a.nq.gz
│   ├── ce6c439861161e3b2cb0ec30f08a61f28d863b9f.nq.gz
│   ├── cf0e85e1af99447aec854ba4c4a8e7130e9c9f10.nq.gz
│   ├── d604425b26f52cc6415ccaa028d4b420f8043447.nq.gz
│   ├── d6631f6a66ddf79b2de22576292b71bdfe589e8d.nq.gz
│   ├── dfa9b8f7ae5f617a7064ca76fa84a9ac120a187b.nq.gz
│   ├── e08120f82f3e93d1b8cf5b9eb71cf8e0e44d98cf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ead49dd760a71052e018fc9d533271484240d93b.nq.gz
│   ├── edd2bfca99de0222e6ccf0a734de7dc32be3d1d1.nq.gz
│   ├── ef08f98d1ed40c8ccae197e64fbccd0345385a25.nq.gz
│   ├── f2e892c1fe37fe650586a1f10416aa9f282ec87e.nq.gz
│   ├── f5ec85c6e5ef14a51101a05bd18faf4895f61e51.nq.gz
│   ├── f82ef81f1a3a1dbffbae7a72e02ca5b5f42a8a79.nq.gz
│   ├── fc45c0c5106dc0ecc8f4674a58a35fb43852f9f1.nq.gz
│   ├── fc792feccbf8154231d47452c2539693fee0b1dd.nq.gz
│   ├── fdfe22b996877f876da0da705290e67b323e436e.nq.gz
│   └── fe77c33f420a05ff13722b7816e8ab1a3be61681.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 087b30be72640802fddc097472ef35a88020387a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 77 files
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

[lepture/captcha](https://github.com/lepture/captcha)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
