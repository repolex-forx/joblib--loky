# Repolex Knowledge Graph of joblib/loky

RDF knowledge graph data for [joblib/loky](https://github.com/joblib/loky), parsed by [repolex](https://repolex.ai).

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
rlex download joblib/loky
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 09f70d66b58962636c6a0adb8e5487d453ece859
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 09f70d66b58962636c6a0adb8e5487d453ece859
│           └── chunk-001.nq.gz
├── blob
│   ├── 0294eca92298c7f5b7eca956d9131748152545a7.nq.gz
│   ├── 0436e6da608851d217aa0922f89aec9e9551d25e.nq.gz
│   ├── 054e8ab5bb78a46ac366ef8bd894586b2bdb7772.nq.gz
│   ├── 0643f23db3eb22095849a5024caae17a272aaf25.nq.gz
│   ├── 08e0613b317dbdcaebc145ed5d9ff9fe3d14b065.nq.gz
│   ├── 14d929f3adea362911e3a16a7acf193526b4272b.nq.gz
│   ├── 1541d16edd5253b292b66c13f0a3704521ea6139.nq.gz
│   ├── 18db3e34db979240b4a4a943ea6931db3091321d.nq.gz
│   ├── 1c0ea0fe2e30095ec2c34f86869c9f12b56117e0.nq.gz
│   ├── 1ceaa01c70c6e835e7495b5783222f5601ae8b27.nq.gz
│   ├── 24fe9de0527ff44a8aa7aa804666c0ae4a762ed8.nq.gz
│   ├── 27beb878649fd253410fb1314c29dc42d4f070ca.nq.gz
│   ├── 27cb28f8a6dfa337a48d0deedd4014cc3c96519a.nq.gz
│   ├── 285eb1ebf425607139842b03cd4abed3e8b14a86.nq.gz
│   ├── 2bed2580d5bec6405341788db7d2699c7404f108.nq.gz
│   ├── 2e5170f44c0a277fbb4f671d91a174b536009eb3.nq.gz
│   ├── 2edf80257d53a854adc933f3312125c7284ec281.nq.gz
│   ├── 356255094b7647be8de6998a8752dd7807b25e10.nq.gz
│   ├── 37686a98e4c3f04f693e39c8f0ffd9950e22ab6d.nq.gz
│   ├── 3910f0eff22363de7a4ec9f1507dc4d6f2587baa.nq.gz
│   ├── 39283993a91af2d0089fe8ff5bf9125ae6d94aaa.nq.gz
│   ├── 3aadbb82c9199d7433f7df121e95a1e63752210a.nq.gz
│   ├── 44e3f57406b74ff6b7bc49f31ad54c942e26adb6.nq.gz
│   ├── 4b800ec07ff26af38174097a194e24413bf6fc2d.nq.gz
│   ├── 506d0ecba7c8951ddeaa05b48eb1bdadc8d5ff46.nq.gz
│   ├── 51640fce08a5f7e010f9e532bf6b21f99611d6fe.nq.gz
│   ├── 5388f8719067277b03f2dc2858f52114e32d1f7f.nq.gz
│   ├── 53aaee15f741f2e5dda6a379c89621a644b80b2b.nq.gz
│   ├── 5970f5a5a1a35767b109a64be526131291496613.nq.gz
│   ├── 5afd99b420fbc480ed5eb743333a687110a90e49.nq.gz
│   ├── 5c0edb0fc02e004d25389e25356e2c167f93d4b8.nq.gz
│   ├── 5d323cb238285121125623a5d92ebb02db3d0fdc.nq.gz
│   ├── 5d60df736efb8da6b0d19f4b2fa22c0cdc38182d.nq.gz
│   ├── 6084157ad8c3fe94dd6b0ad6430aa880d4cd3645.nq.gz
│   ├── 6a27c596d04923555a64ce7deed7d3c0287c516e.nq.gz
│   ├── 6e9f657d78882cd22eb20954e6bdab3029a276f1.nq.gz
│   ├── 71dda69fad1007352620e1532bbf2eba018df666.nq.gz
│   ├── 72dd9368377503b7a713df1d18b3a28f6c29d4fe.nq.gz
│   ├── 740bd171db0c0da1e0d7a23946bbd172322d709e.nq.gz
│   ├── 78458a9df1b67ca2bff0e46295bc0af103ecc42f.nq.gz
│   ├── 84338a1e5383e598a750286a6ca847c1a33c34a2.nq.gz
│   ├── 864064164271815d7917c8d289492a4df7aa4c39.nq.gz
│   ├── 86a03e522dbeea63d8b5872aa43e26b11e3d1b4a.nq.gz
│   ├── 89a0106941ff398844f23a965c5b755ca12eef97.nq.gz
│   ├── 8a48fc5bf119cd132f1aa1d1de5b72e28a2e7a4e.nq.gz
│   ├── 8cc689621e09bc482b5e6b69d15ffaca2f54a570.nq.gz
│   ├── 933c8a7d97739ff3c7d07c3dfa78b24ba015fd16.nq.gz
│   ├── 9747867a3a5c25be67a70911cded2147ecb3c537.nq.gz
│   ├── 997261481476c60702ca6ee6e7c6b8824b319838.nq.gz
│   ├── 9a6ef9d9770ee651bf4a0112da98257cb739836a.nq.gz
│   ├── 9ad7f9d0980508e7dec6a88d317c9d7118b698ac.nq.gz
│   ├── a4a7ab86410ac9f19d6c74cc5749c07448268436.nq.gz
│   ├── ad656642a403aaa8f52141645a36e3d5a648e568.nq.gz
│   ├── aea0e56c25d0d74e04788493058549a1399f8342.nq.gz
│   ├── af77d019ee405e09bd061aca8a78826c0ffcc90e.nq.gz
│   ├── b1e4590fccc812fcb98594c7b3ea07dd6831a65d.nq.gz
│   ├── b3ec0986b0f6b2e0678c817afde5e89e2c21436e.nq.gz
│   ├── b919e4715b89d363692abb32aa50386679d6427e.nq.gz
│   ├── ba87808613ac6eae74f56ca0f0c0fcc6c84f7c5a.nq.gz
│   ├── baf5cbec4ad47df30a432bf6ccd36a459f150d68.nq.gz
│   ├── bc81ecfcf9e7d5511eb1252e26e8181eff34bd9a.nq.gz
│   ├── bdeac652ff985fa8bce92f10a1b912426d388373.nq.gz
│   ├── cf84652d460d32153fb562acf7aa999b2feb1f36.nq.gz
│   ├── d339aa644599cf5728394200abdfa19a1256aa02.nq.gz
│   ├── d37bc29c77e095535a3ae0bb497b8dbf9f3ee2e3.nq.gz
│   ├── da0abc1e7fa18363e6342a3b67410f1429e6fa10.nq.gz
│   ├── dd6a7a8a5d2490390fd52eb7c0566285c100e2cc.nq.gz
│   ├── e1bfc8ae4fc12d8fb545f1319a9e64e432272271.nq.gz
│   ├── e2f4b599cdd3e5816ea3e1dd2d0c3f8478bbb820.nq.gz
│   ├── e3ac21f7d46482220dfc492a3b282b28e9da486b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e79569a243c5f6bedc49503ffd7b2441f84ba9da.nq.gz
│   ├── ea363a48b4d95455421ccddfe4b64a907dfa5ad5.nq.gz
│   ├── eab087fb4205c28ae11353ce682b1fd5bc0df2b7.nq.gz
│   ├── ebf74f0ce8ac69b0ddba63f9d4930d3ecc2577ac.nq.gz
│   ├── f29c5839b2751abc5895883c2e69e9fc0e2014ab.nq.gz
│   ├── f5aaae6e02235d3adfabf366f9e71348d873d5b6.nq.gz
│   ├── f5b7ca6918c882b007e47cfd8258d559de834a6f.nq.gz
│   └── fde2a28f73e35344621e5078ae6a908ccf158058.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 09f70d66b58962636c6a0adb8e5487d453ece859.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 87 files
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

[joblib/loky](https://github.com/joblib/loky)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
