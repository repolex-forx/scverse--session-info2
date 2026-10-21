# Repolex Knowledge Graph of scverse/session-info2

RDF knowledge graph data for [scverse/session-info2](https://github.com/scverse/session-info2), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/session-info2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 528efcdc76d8064e97eef60c34b858ea37fb8307
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 528efcdc76d8064e97eef60c34b858ea37fb8307
│           └── chunk-001.nq.gz
├── blob
│   ├── 02154a862178ebffa9293701c3c5364082140cb6.nq.gz
│   ├── 13d7bd86a7e4db7216eb417bbb775b3000d6163a.nq.gz
│   ├── 148bd2af7bc80bff3b94ab3f4eb762bc86ebdd0a.nq.gz
│   ├── 15a13db4511332c27a869138fadd62696c650baf.nq.gz
│   ├── 1dfde1e7f7eca52706f3a29ab9adaa082797c1cb.nq.gz
│   ├── 24af307fc9532ba7d765a07ea0658fc9c00acb6e.nq.gz
│   ├── 25a8d829df84fd74b38203152a348c5b8a81faf8.nq.gz
│   ├── 2b0b50e7ec3088b8dd9f1ec9ad45b88d73168128.nq.gz
│   ├── 322793040792b8440f6bb6db6e29660b8e54b266.nq.gz
│   ├── 34740e91ec7c089eaeb5fba4d580ef7ba59481f1.nq.gz
│   ├── 3568e1a477faa659c998d8295d45411e2799e7d1.nq.gz
│   ├── 376af9826b935ec504cd918d5a45a90de82f9ad6.nq.gz
│   ├── 3889f29f2933a74188aa97a08c2eade0e8d35232.nq.gz
│   ├── 40d4087227d1809d4bf506fbf2286a35da9e8cde.nq.gz
│   ├── 452022f93e894f7f2615dbbbcc29999383960911.nq.gz
│   ├── 59c61dcb1f7fc44776d99519e0dcf41cfec0a6bd.nq.gz
│   ├── 5e519a8b3fef6d8728c672a0615d7e04c1e00944.nq.gz
│   ├── 5f7d071e04d7aaf0a42e7000c743780752b2baa4.nq.gz
│   ├── 66a3d1d977a1a12a8aafd315ca6dd1c3868c50df.nq.gz
│   ├── 683cc76045cfa854f14252ea207c9dea66b3d3ae.nq.gz
│   ├── 7189f08c0fa9d5d9cca0d3c3f4f45e1a31c56948.nq.gz
│   ├── 77c719ba435cb72da524d47c581aba0ccf25892b.nq.gz
│   ├── 7b5d7e4bc87ed4ca9e71891dc040b5993d628776.nq.gz
│   ├── 7c7e6e9ffaa4ab3ed43edfc22c9c798c2f26b357.nq.gz
│   ├── 81fda0f01c7d505d50658a1d25933df8ed4028b3.nq.gz
│   ├── 86bf96cbe6156d31641819c3fc89794960e08140.nq.gz
│   ├── 872b8e2a5cedf6ed81b4931521d5e9be0cf6d379.nq.gz
│   ├── 8a91991560cb339a1f1b80084dec9eca86785280.nq.gz
│   ├── 8c981b683f8eb459dc89b5ddfe5881a42eb30d41.nq.gz
│   ├── 95b9fba66fe918c8d4146cc72b8b392ef4c4bbbe.nq.gz
│   ├── a87abd9cb92275dd4b177daecb5060bef98cefc9.nq.gz
│   ├── bd394956b359995ea4b894f64a7ce1b545b820f8.nq.gz
│   ├── bf9467f2973d45fb402d89019ef1ba7483324f95.nq.gz
│   ├── c6adfe8b9b49e707447e8927d716004144c00f3e.nq.gz
│   ├── d0da0f10a3aa093c5f9cb63ace645900f78b3344.nq.gz
│   ├── d0dffb59db409aae76cfd75bd79d09ccf4c0318d.nq.gz
│   ├── d1c177e6e004032da42acaa27d56f39a51ad485d.nq.gz
│   ├── d374478d13a05986059ee14d4103c1bb31296fd6.nq.gz
│   ├── d4676f0e283a3e4e5a0fb973292ecb70af8e19b6.nq.gz
│   ├── d60b69563f069d375f4ac9d66b676b05d333233d.nq.gz
│   ├── d9bcaea764f5a0662d3de205dd9e0f9571ff256b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8e052139dcedeecd6b572f69f57e49c9b8ed09c.nq.gz
│   ├── eecf70db92ffde9c71d3533905092b6281ef02e4.nq.gz
│   ├── f0662be728310b405937edabf94a9d4f3af403af.nq.gz
│   ├── f09c28775b9af146c8feeae8a470831fcf78b70b.nq.gz
│   └── f6907897f6d63fbc90cb587087dd74430f8e7517.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 528efcdc76d8064e97eef60c34b858ea37fb8307.nq.gz
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

[scverse/session-info2](https://github.com/scverse/session-info2)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
