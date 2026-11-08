# Repolex Knowledge Graph of zenml-io/gpudoctor

RDF knowledge graph data for [zenml-io/gpudoctor](https://github.com/zenml-io/gpudoctor), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/gpudoctor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 858554cd75af56c489b7afcd47a87eb5d2a5940f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 858554cd75af56c489b7afcd47a87eb5d2a5940f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0166277ef77288c5a428fb0d950f095f8b0d5c39.nq.gz
│   ├── 037c18adea6687762baaff74378d7f74da1e69d0.nq.gz
│   ├── 068e4bf85db445be35b039afdc8e88a0c38d7d84.nq.gz
│   ├── 0aacba5182608fafed31a583ce8bc52e16da10b9.nq.gz
│   ├── 0d1091aa24ce14ec6b42d6ac89be62f3e761d925.nq.gz
│   ├── 1039d0532dd8f0e94561ec77b388ad44b1b69a5c.nq.gz
│   ├── 103b3d5f26defbdfd885d4135ff0f0adcd546e5a.nq.gz
│   ├── 152006df795c1502b9a00b6cda7401a1c77feeb7.nq.gz
│   ├── 16c550772a7e09a9ea498e6c7cd01d44b6e7c4a0.nq.gz
│   ├── 17c523ef1d8aa70feafaea79fcf5d52f06fa2527.nq.gz
│   ├── 1a5968eaaec4e6d2c812c047cec1691fffa12e21.nq.gz
│   ├── 1ff50cfc6be49d7b30e1f7e4699be484c243914a.nq.gz
│   ├── 20f33a19038ab92a55a03a4bc6e3eb8adb5588d8.nq.gz
│   ├── 239a40fbabccae41d7e6cb1a25baa1e7aefa9ca6.nq.gz
│   ├── 2646801ae862704549bb368e33ce60c724cf907a.nq.gz
│   ├── 281e06ef2d508d5860751468711a208fa0799028.nq.gz
│   ├── 29bdee7a5615d1412a2b8412967acc158b132eab.nq.gz
│   ├── 2bb1b96df3630d5e918d6cfb07d72d0abb045673.nq.gz
│   ├── 2f552c1dbd6b6bfc186f083f9de80b68e98821dc.nq.gz
│   ├── 317927d7ccc47e5dd74a03fb70265a514b8494e8.nq.gz
│   ├── 31fb3d5a6834070569410bc8e42435769b706300.nq.gz
│   ├── 35074783cc465dbc108a6fb1d70bb843aebf7a69.nq.gz
│   ├── 3747cb684f7ba5cdcd1167d4d53fcb3b5e738768.nq.gz
│   ├── 39ea3152eb36892aeef0b57e789befff8c087259.nq.gz
│   ├── 3e47ca888211e9663146fbd147eb071a080af113.nq.gz
│   ├── 4021bd8702e04752cb5f341c1e8298f2dacd38c7.nq.gz
│   ├── 40eec7e44f69faefc68956c91d06ced2fdd45fef.nq.gz
│   ├── 44bf45749f248d2f1fe8f1d2194f23a1db07c412.nq.gz
│   ├── 481140e97f75ee37a8840717e2f385d46ee5a9e3.nq.gz
│   ├── 4cf325e088091855b53666d57bc375ed9f9858c3.nq.gz
│   ├── 4f11a03dc6cc37f2b5105c08f2e7b24c603ab2f4.nq.gz
│   ├── 509f994f06c4fc1587f08197769ef432938cad4c.nq.gz
│   ├── 577c3545378e3330efd80c7953b087e42a72fdb1.nq.gz
│   ├── 592c162e31e44ff02c6569808148f37cc0dc11fa.nq.gz
│   ├── 5c8aa89584a614b1258e853309d7bf576dd53a25.nq.gz
│   ├── 6022554455789054d08f5cf8e99a6d6730ceab35.nq.gz
│   ├── 681a5c87aaf2238742d2d1871f5fc45f8953ffc9.nq.gz
│   ├── 6b98454a043a985ab58d3130910e9c7e66defcb4.nq.gz
│   ├── 6fbfa29e0663680577f7042f0453a96cd57f2ec1.nq.gz
│   ├── 723b705a23373842db758a6864b20cac1353abb7.nq.gz
│   ├── 73e984460876b63f768015b47d443b3215c3d05f.nq.gz
│   ├── 743200b4a386a9eb4e2b809c73372acd73825f18.nq.gz
│   ├── 74af318c5898e64c67ed7a4c966f3d715c48d2a9.nq.gz
│   ├── 76e9ef4d34bfc26d862dc602dc56162668df16f7.nq.gz
│   ├── 77cc09ef619726150bb3cb213a5034947afe382b.nq.gz
│   ├── 7a09b0b9ced68409bf39e83a458106e739bb93f1.nq.gz
│   ├── 7c5338bda03ce7bc9e30f7557f3279b608da28a4.nq.gz
│   ├── 842d6470a3bab608a74b5bda7d23bfb41828910a.nq.gz
│   ├── 8acd5bca4bcbf3a37d9ebe7eb4f3e2e64a463e44.nq.gz
│   ├── 8d10c6c7d5078a72d1fc6d7b6c1e71443f6fad16.nq.gz
│   ├── 9121e34051f87eb9853781a3d95fd32611f36529.nq.gz
│   ├── 930c07779218086787b03266bbb6d156af169eaa.nq.gz
│   ├── 94ddd1cc415f76571c3a429d58e80d97e0206865.nq.gz
│   ├── 9902fbbab0115b2f820ab423ff4163336cd27faf.nq.gz
│   ├── 9ae290d74070a24835943fdedfe95dff81f9057a.nq.gz
│   ├── a0c6f1e5306bc951cdb1577ae52e0aa8c3dd2760.nq.gz
│   ├── a4fbf0d85974015c5e3a4101281f4dc127c2268c.nq.gz
│   ├── ab437ea4860646216310e48e2c32771ac525391a.nq.gz
│   ├── afde90515730529df6faeb2841a04cb3e1050104.nq.gz
│   ├── b596d08d9b17cfeddd1ba318a2041668c4c233a9.nq.gz
│   ├── b89e6bf1316c114b0caae9ca40f1fd96a920cc8a.nq.gz
│   ├── bc17016386081c72f4a39a5f539a52de598f7286.nq.gz
│   ├── bc736292ee3e50dd481ecff542b52c611901dae5.nq.gz
│   ├── bed1434d6f40de237555dd6f60244d537b34cf7d.nq.gz
│   ├── bf80fd5a44ac172413c37c3a7b2bb28a33453111.nq.gz
│   ├── bfe577340c9880e76f05a87d048231161d11780c.nq.gz
│   ├── c2cc61bf1c550f91f0efef953964ef7e56dd5d39.nq.gz
│   ├── c912f2df246f52db4daa2099fdede9d6d731ce8a.nq.gz
│   ├── cab6fe91a83b9b16a9628191fd1b9fe02b52fa88.nq.gz
│   ├── cbd69ed6e416f2165446fc3196a06f7e206a5b95.nq.gz
│   ├── cc6508f66d4fab366755afe4a7fb92d98d950719.nq.gz
│   ├── cf16facb8fcb41ff120ee43983d9ea2dcbed53a1.nq.gz
│   ├── cf6e164ef94e5389bf9b10d54326d182b884accd.nq.gz
│   ├── d1240e74c85441fcea070c31d4991817255a1f0e.nq.gz
│   ├── d14fc9d7ecfa313b3cb69be125033bb7c3c8b1cf.nq.gz
│   ├── d7af5ba854672f8ff6504ec29739a2ffed9be0d8.nq.gz
│   ├── d96d4f0ef699fd5398634b69fcdddceda4ad9778.nq.gz
│   ├── dce7b11c4efffd1374198a3d66a861898a215ee1.nq.gz
│   ├── dec72be5146704cf528881687257c4dbb3281de4.nq.gz
│   ├── df33c12f37d63289020376783ac55ce496879553.nq.gz
│   ├── e770557829f2922277088a696f02ea8f9a51c859.nq.gz
│   ├── ea4e9d80482326e78aab4fb624c5c94917174d6d.nq.gz
│   ├── ed4d0217e774195fd8abfa65a5a8e2d430d4a38f.nq.gz
│   ├── edb6affaecb3011530688aac5fda166c5acc2a5c.nq.gz
│   ├── eeb539eb87a3c182656f538cc3b6c7ab3a3a51fa.nq.gz
│   ├── ef08b282ef0150ddfa165fd8bec00d862c53b349.nq.gz
│   ├── ef4ddcf35b940150a5b277f52ac7e73613af6e2b.nq.gz
│   ├── f0839093636ea8f2151b761e80973dd43ff20830.nq.gz
│   ├── f08acd01af013d9ab5627a77902113361552989f.nq.gz
│   ├── f6dd2cc2bac13b694f4516b1706e13e3f5d5747b.nq.gz
│   ├── f8991ea279d412573690f43efc8b1a2790ce9a24.nq.gz
│   ├── fc9cebb781e21acc2a2ccc82354ff49d3816e1a5.nq.gz
│   ├── fe97fd19fc3647689f12f2ddcf7489aa6625637a.nq.gz
│   └── ff9c02d53630383568f8cf202f0ccd309a332e17.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 858554cd75af56c489b7afcd47a87eb5d2a5940f.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 101 files
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

[zenml-io/gpudoctor](https://github.com/zenml-io/gpudoctor)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
