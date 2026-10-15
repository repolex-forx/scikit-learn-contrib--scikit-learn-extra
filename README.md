# Repolex Knowledge Graph of scikit-learn-contrib/scikit-learn-extra

RDF knowledge graph data for [scikit-learn-contrib/scikit-learn-extra](https://github.com/scikit-learn-contrib/scikit-learn-extra), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-learn-contrib/scikit-learn-extra
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── da55e27dbbc4c028874ab4f1e1057bd073480ba1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── da55e27dbbc4c028874ab4f1e1057bd073480ba1
│           └── chunk-001.nq.gz
├── blob
│   ├── 0119cfcc8c4c07e2d90abd2de122fadd7588da80.nq.gz
│   ├── 01daeb3582a4cc32e8d1083a51102cf483095fe5.nq.gz
│   ├── 0c90c2e8a6d6af7f8b5c3205e0609324214a1b1c.nq.gz
│   ├── 0cd28816af838d548a600737fadfb553c0954d80.nq.gz
│   ├── 11f5df9b7210ac2cc951a3438544e839b40730ca.nq.gz
│   ├── 1288ee1a082f312021964d8118320c1d9aea2735.nq.gz
│   ├── 155ba98545935f87457b4b2350858e70c79f176c.nq.gz
│   ├── 1c68b24e680a615f660a5a3358571df299b04708.nq.gz
│   ├── 25fc8ed87e9a420bfb97be058c17bab21476e9c0.nq.gz
│   ├── 278b3ed559dc12ff3643a6f7c53478579fd4f0c4.nq.gz
│   ├── 28f069939d0d68a915aab7384861a6ed9575090c.nq.gz
│   ├── 2aa121ca1b90f38a0280f40baf919821567e22f8.nq.gz
│   ├── 2ed4a4a1670be87c8a87cefcde38a0dec3637c13.nq.gz
│   ├── 317bb5d3241dca944b596ec8dbc546b1f9bd60b6.nq.gz
│   ├── 34ddbb9e31a7a4f9a879e9c716f7993c572ce15b.nq.gz
│   ├── 3ed98b3a6a3dc89725a9a0fa7527f88d1012e894.nq.gz
│   ├── 3eef97467222900287d032493c53eae152d5d599.nq.gz
│   ├── 426f8b99678c6c31d29e49abd8629181c6b99a31.nq.gz
│   ├── 4290451494606e5c62043be424a4df7420b4dbd9.nq.gz
│   ├── 42df44f03379f14442dcf2bf055904035977e744.nq.gz
│   ├── 4ba355d57c873dcd0f43e0471b0df1b8d2a98374.nq.gz
│   ├── 4daa97a55017c1bbddd34e7161cad73333106f95.nq.gz
│   ├── 4ed1fb41f74551e85acfb946e9a616957c4de25b.nq.gz
│   ├── 508376e44f20332a0a471b40ddf8c2484a99b015.nq.gz
│   ├── 526c9400bec2bfaf796b9180b0f647ccf5c61add.nq.gz
│   ├── 53be76dc113a8ecd2ddc05aa0dcee86afb2443a0.nq.gz
│   ├── 5b71ecf80e021dedd01e324284579ec3163b6523.nq.gz
│   ├── 5bf9e259bef454e902440b7ffbac85924076aaba.nq.gz
│   ├── 5ea04362ca81ce11bb896fbe23280d3d5e0f514a.nq.gz
│   ├── 60266e5a4fa5a3fd9212d7e82ed93425119edf67.nq.gz
│   ├── 640ad47573ef1efd938c639683eaaff0f15eb146.nq.gz
│   ├── 6727157bdd72d0bd3becff9fa641a7f7fa5a47fe.nq.gz
│   ├── 68ddb9b6970ef41884f2755f5e433649dd095a33.nq.gz
│   ├── 6b8dab52a29283f1e10d8991fb50273aea2cd778.nq.gz
│   ├── 757878b4c56589628ae9fcfc3b495fe6608d0084.nq.gz
│   ├── 770098423e989ab0f932fccb40bc551e2ac15327.nq.gz
│   ├── 77601d7a65e67f50ca7f7f7132433e3c23694a3c.nq.gz
│   ├── 79c1e1984b87bc0b5c10ae5cba2cc1a94a1051c3.nq.gz
│   ├── 79f45d8ff75fef42442b470312b8452a15928ad8.nq.gz
│   ├── 7ec24ab6e3908080c2e1575da042a685004eb6bf.nq.gz
│   ├── 802f8a577ee7e10a9221629da1e6b020b71bd752.nq.gz
│   ├── 88856743e7adad1c3885be42f6057899d8b2e78b.nq.gz
│   ├── 891890580b48ae04d23cfcaead4f96867a0fd525.nq.gz
│   ├── 8b9cc19c4412f419417fc9c612f241c3bbe512be.nq.gz
│   ├── 8bb7ab11fc8d5e766edc59b17d5996aea2224804.nq.gz
│   ├── 8d53658fb43a1de40383dbdbd4adc42c9ffe5292.nq.gz
│   ├── 939e9aff736d651067eef42b85a295078765174c.nq.gz
│   ├── 95407eb17a15dbb8f6f22fcc233897b5ffdee93e.nq.gz
│   ├── 9a9180459aa584ba82c756915c7f66fb458aff38.nq.gz
│   ├── 9cae3ec0914b35c079dbf9845aeab7c448144ffa.nq.gz
│   ├── 9febaed526985ed5ca71e1453e46c6193dd3d057.nq.gz
│   ├── a0eb1978589bbd4e40e82baab972f7772236a38b.nq.gz
│   ├── a5d244b84164bf4bd7c8db775c84bcaec6e179cc.nq.gz
│   ├── a703c9485a74beac7cae6fca19de70ed5151a604.nq.gz
│   ├── a833264caf979be2f674a3252abeb6f76666306d.nq.gz
│   ├── aaff11da2b567696ba4a66f0908ffd6c2e158f7c.nq.gz
│   ├── ad0ebf6aaf60756cae103e17bde723cdc1b3994b.nq.gz
│   ├── ad2f95febafc53c6c4a5bdbbe29b418f517f8aa2.nq.gz
│   ├── af48bdebe5c34f159b4542813d5a1dbc23cd9e9c.nq.gz
│   ├── b0be911c2d6cf107846b72ca62231f4925699fb8.nq.gz
│   ├── b234d691944dce0ae044621652c1b36086c7c83a.nq.gz
│   ├── b35d36954000ed0a008b45831c2d8c5236a4b044.nq.gz
│   ├── b56905888aafb840c04f3d962332be804028b16d.nq.gz
│   ├── b8478f0091c5e5b128ca10730916c32ad9c1e7b5.nq.gz
│   ├── b855d4eb4f66d677463be73ac80812d0990284dc.nq.gz
│   ├── b86c7265ea783e638ec1379e1dd45fd7abc0fd2f.nq.gz
│   ├── bbcece6abed789ff6f19499c463ca250e33425a4.nq.gz
│   ├── bbf6573092975c4548ad5d6a95ea917276ff2f42.nq.gz
│   ├── bd7535c9a447dcad80c5bdb826f0ffcb1403487a.nq.gz
│   ├── be0ee02c2baea1d25039447385de0c7dca7691d9.nq.gz
│   ├── be98325c4b3b8e7ac4ba18657c2abb4f0c74c4d8.nq.gz
│   ├── bfacad72f1a524a87586fb69c0ce387644e5de7f.nq.gz
│   ├── c16d9ed4be76994f089b28274db7a1d19f1c98e0.nq.gz
│   ├── c179a3dd5ee19bec5104cb80d6f4560a83a0f5ed.nq.gz
│   ├── cdd47308e34b1c8c0c5c6cdd74ff2c558e8d3e11.nq.gz
│   ├── d6ff8b6a3646ab029a3e557d15eae3376c26637d.nq.gz
│   ├── d87f56998175b91b21e7ee53ea806064fe0f78e1.nq.gz
│   ├── db4e6cc192059b5445fe2d0e8736a05d2d6b4eb2.nq.gz
│   ├── dff09a85ceb135ae405ef53df0b4901eda5c2b52.nq.gz
│   ├── e47e18f269a9a427ae2fb0268c66cec2e21fb578.nq.gz
│   ├── e52ef750e6178d7b6e54016095053816f2f0d783.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── efe83a3f8ceadd161df6d79de8ee48377ac5c720.nq.gz
│   ├── f11a1a7007abe457e9a4109ed516d5ac187d2ea4.nq.gz
│   ├── f1769f5ff3e4a798b190c7f28ff089b33c535c19.nq.gz
│   ├── f18cf379a312e2a26de18a123884607c5a143607.nq.gz
│   ├── f6caff23ee5012614068f7bd3da241adecdc075e.nq.gz
│   ├── fd6a35f7662b07dc9058a8ccc0a42e161ddbc6a8.nq.gz
│   └── ff774cdbb0ad27116295b34ea9f77248c2a1700d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── da55e27dbbc4c028874ab4f1e1057bd073480ba1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 97 files
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

[scikit-learn-contrib/scikit-learn-extra](https://github.com/scikit-learn-contrib/scikit-learn-extra)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
