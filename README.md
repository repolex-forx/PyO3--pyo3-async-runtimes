# Repolex Knowledge Graph of PyO3/pyo3-async-runtimes

RDF knowledge graph data for [PyO3/pyo3-async-runtimes](https://github.com/PyO3/pyo3-async-runtimes), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download PyO3/pyo3-async-runtimes
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 6320af5dcb62e5b4d1556fdb5ed81fb06a4fadf0
│   │   │   └── chunk-001.nq.gz
│   │   └── 74cd232b0606cd9e0dcab291bd10a8cadf69a1ed
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 6320af5dcb62e5b4d1556fdb5ed81fb06a4fadf0.nq.gz
│   │   └── 74cd232b0606cd9e0dcab291bd10a8cadf69a1ed.nq.gz
│   └── repolex
│       ├── 6320af5dcb62e5b4d1556fdb5ed81fb06a4fadf0
│       │   └── chunk-001.nq.gz
│       └── 74cd232b0606cd9e0dcab291bd10a8cadf69a1ed
│           └── chunk-001.nq.gz
├── blob
│   ├── 025eef2ea6b4a9c03445379bfff820c55099890f.nq.gz
│   ├── 0495866bb8f93ea1438c18fa223bcaf4fcd08786.nq.gz
│   ├── 08ecf2ef856d9dcf8aac748914882b1a2a517c8c.nq.gz
│   ├── 0c2aa01b6b96901fe8eaed0d7d1a1a6edfbf3efe.nq.gz
│   ├── 0db4128e42864267991507e20fad73e4283445f8.nq.gz
│   ├── 0e7cccb562e6dbd0c04912b8556c557a8e528f25.nq.gz
│   ├── 10477fcfb4fd7ef26975137bd210bca30b0df24f.nq.gz
│   ├── 139af7830ec1dc38186f2291987f020f5b9255c7.nq.gz
│   ├── 141bbb240efbcf8e8bc189056b29f41bccecd0ee.nq.gz
│   ├── 19c4269e17fd856a573b26f8e5096de89cdce03f.nq.gz
│   ├── 254d05776385ecee84a00325c07299fb58d03ee6.nq.gz
│   ├── 2bdd1f45276030b9137e1781b6d1535d116f06c4.nq.gz
│   ├── 2dc01cb65e1be5a6ac0d175f2c32cfa2b4606f30.nq.gz
│   ├── 30069d6dbcf908124acc2b1a9e08497acf6a527a.nq.gz
│   ├── 31581d689ef5bdd322a60d06d87a12087db013dd.nq.gz
│   ├── 32a0e211e8a48b5f66127395d405d6ca4a88af8e.nq.gz
│   ├── 32e7ea44e659977a8c9087a346c09fc9ed77a0ea.nq.gz
│   ├── 354609ff2f7de0b47c662801b81b9455674ce11e.nq.gz
│   ├── 38f5356b0fc7211e981f185ab85a0495068923a0.nq.gz
│   ├── 46050b2e51feb1ab3c59eccac5b1c51001583d98.nq.gz
│   ├── 46ad66edbfe02b86694c30f2719603d385d634ee.nq.gz
│   ├── 49b90e8f62ebffb5879a7a11a4617c8bbe662830.nq.gz
│   ├── 4ba596178de2a88ce29c508457a349e4cf90d58a.nq.gz
│   ├── 4e2196bde28a429804617d2e695bdc788b6af50a.nq.gz
│   ├── 5192ac046583dce2b93c6b98a0bd904efb8a2114.nq.gz
│   ├── 5fe553e4387c68d6a7631a867fb056740fbff7cd.nq.gz
│   ├── 60c83d7cefb0998a67270cb386afb4fffbf7133f.nq.gz
│   ├── 6121502aebbfc587acb2bf900fff3febe7feb2f0.nq.gz
│   ├── 678c4c8dc7fccc5918f321fb4f2ed2ca4830129b.nq.gz
│   ├── 67b7213ae319ea8c3bd8fd896b7f4e1580509121.nq.gz
│   ├── 68ad7bac6fa5df0d02a34c77e657c61c01649ada.nq.gz
│   ├── 70928bce111a303299f871143f1b044aa1564c88.nq.gz
│   ├── 750a74a8962352bedb9cc33d327f6c92cb8a1259.nq.gz
│   ├── 8094f6eabac64fc2c5b20442034630e7e9a60bf3.nq.gz
│   ├── 849ffaf01bcaced915929372335d58e075e8927c.nq.gz
│   ├── 93e6d4a92dabe6de836c8150a4f8466742239f77.nq.gz
│   ├── 9824eab806a861586da27fc1570a2910b9333c8c.nq.gz
│   ├── 9921c099c15d7f1950e80ddd9de0145bd63ce66f.nq.gz
│   ├── 994176409de6aedac04e8203300d1d1e1a982833.nq.gz
│   ├── 99486e90b52af1902690c405d255a24b073508bc.nq.gz
│   ├── 9989037569e18e46ec7488afb208e9c1cfc17278.nq.gz
│   ├── 9b01e5f103ae5e39cc46677b9f0582c0991b0a92.nq.gz
│   ├── 9ea8a4b62bff264254dd10d2356fa86ef5fd9a4a.nq.gz
│   ├── a576dfe1f9843a0a97b2a5950af5f6b83e50c72a.nq.gz
│   ├── a86875c89db839bbd28844a977795a3e4204bf19.nq.gz
│   ├── acb8fdf5ca653c5de4babe3c06b13cbf3b8cf41b.nq.gz
│   ├── afb31f7362afd4d87441a98371d6a1aac71727e1.nq.gz
│   ├── b3651f46c9ca90a9c778b7ea8082457581cd6b99.nq.gz
│   ├── b7469d2da61a1a4269293d9edf571e510200cab1.nq.gz
│   ├── bb2213710e5fbab8927f567d704847bccc004ad4.nq.gz
│   ├── bb9a5d874dcde9c43aee7b9eb01765fce106af38.nq.gz
│   ├── be544d806eb89853511bcefdbd1df6544996acfa.nq.gz
│   ├── c067d1fd1f07d3693f409a3a200cc4a4459e198a.nq.gz
│   ├── c06c62548beecdc0252751a08a4a90443cd47030.nq.gz
│   ├── c31fed46f140a7ec4ca3f02fd9423d1276d32dc3.nq.gz
│   ├── c75bc111fedd8d5aa30c33706caae4173e8588bf.nq.gz
│   ├── c82897745e7cbb72433b81bd2f95f5cdd2d0fa90.nq.gz
│   ├── c8dd311847396f9339d33f7b9196aa840d9fd772.nq.gz
│   ├── cc594b5db4ef02b428b2e04b18e64eccc188ccac.nq.gz
│   ├── cdd36a73b911ca36a93d1a239c844fc1ad2e2778.nq.gz
│   ├── cfd2c71a376cac49e0e861ec35ef6d8c4f3e2db5.nq.gz
│   ├── d076bd0e4e9e8873bb9c8006fe0be34d38a364f6.nq.gz
│   ├── d0ee8c8c290d011a141b479799086189c91de8d9.nq.gz
│   ├── d1fa72b74cb0e844efc0dc69c6832c84e2709c3c.nq.gz
│   ├── d2ca7602e63a31e6b3e31edfdb0a6c8b952c8848.nq.gz
│   ├── d7939e11b3e8006a700f65acdcd5ac26a54eea02.nq.gz
│   ├── d999e0aef4ad559b2f3745aa6abde567b23966bc.nq.gz
│   ├── da7f3dffbb30d5c159c493ab291207cc223a4e37.nq.gz
│   ├── dc1ceb0f353aad9254fb07c3f422113089d38173.nq.gz
│   ├── dc2655c8619724f4fd212347c03085dc88df0020.nq.gz
│   ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
│   ├── f19fdbf7f87a085fd524ef6c45d6f5387815d513.nq.gz
│   ├── f1bdbab5933d0f7c45c3dc83c14adda4c2108346.nq.gz
│   ├── fb2086e7d841c9eea1a081f280a8d9e1f3db136d.nq.gz
│   ├── fca31990733461b3937c74caaee2d623e9e6bcbc.nq.gz
│   └── fe0f92556df214591db6c933d71b00dcbe07c75b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 6320af5dcb62e5b4d1556fdb5ed81fb06a4fadf0.nq.gz
│   └── 74cd232b0606cd9e0dcab291bd10a8cadf69a1ed.nq.gz
├── filetree
│   ├── 6320af5dcb62e5b4d1556fdb5ed81fb06a4fadf0.nq.gz
│   └── 74cd232b0606cd9e0dcab291bd10a8cadf69a1ed.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 91 files
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

## Source repository

[PyO3/pyo3-async-runtimes](https://github.com/PyO3/pyo3-async-runtimes)

---
*Parsed on 2026-09-15 by [repolex](https://repolex.ai)*
