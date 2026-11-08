# Repolex Knowledge Graph of canonical/sdcore-nrf-operator

RDF knowledge graph data for [canonical/sdcore-nrf-operator](https://github.com/canonical/sdcore-nrf-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/sdcore-nrf-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 09413b5be74a693ce82258414a63f6732e48575f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 09413b5be74a693ce82258414a63f6732e48575f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0034e45a9c605e934abd1c157e4e2410e856b995.nq.gz
│   ├── 03cff9b9d5bc4dcb84c15789188c01f2f94b3967.nq.gz
│   ├── 07e10a08514124ce2ce63de2bd3fccecb89797e1.nq.gz
│   ├── 09d7ca9e1a9761bdda48188846a6e7ca8e70a1f2.nq.gz
│   ├── 0abdc5ccf0e8d19ec6d8185c690b63ad0a667ddd.nq.gz
│   ├── 0b680d508757e960bfc1e7190cc29509514d1562.nq.gz
│   ├── 0dc01605e03d64ab14aaa7b9fbb3ca5d54d6ac3d.nq.gz
│   ├── 0ff992b299b3f0224c0a4575fb68ea04de62af99.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 145cb6c5fc1807c1753ce7bfa4f7678e522c8cd4.nq.gz
│   ├── 1ba86db41cc11190517ebf1c9b8ba581fa222430.nq.gz
│   ├── 1cbf473f96458553b3171a8c8d25946513be8133.nq.gz
│   ├── 2055a28de90818ffa33b0a2ff4e1fdbd93eb1473.nq.gz
│   ├── 2e2ba639df0562bb86a186f26b42a85ad9bad7f4.nq.gz
│   ├── 3bcd8a9f726c1e7ff32172d0ed5d95ab6436a34c.nq.gz
│   ├── 46fdfb6ff31d8f845aa61ec8d9c441011982757c.nq.gz
│   ├── 4d394c33b8ea132a10ef09db97c9509d10e14fd1.nq.gz
│   ├── 50f15f49ef8517b55adf362d675a9aafc8cedb8f.nq.gz
│   ├── 5411236d6b63bc4bd54f36ff39cc6f7912a44507.nq.gz
│   ├── 547a7b609cfd5123018546f64124a4563ecbfca1.nq.gz
│   ├── 5777e267ba4ab099c59374d8ffa75d88f87b11df.nq.gz
│   ├── 6063f72f417271a6cba967b4e767ccd955d209b3.nq.gz
│   ├── 6443661344078679d5c7b3397e4c56a89cda0e2e.nq.gz
│   ├── 6956307e8f7be06ebc24c2dc27fad729b3f66513.nq.gz
│   ├── 7075acc5a13faa88dd76e3703ac8f4629b3b0a03.nq.gz
│   ├── 70dbde9401b3758654cde755d92813757f224bc6.nq.gz
│   ├── 77e43ed5a979d3fb97d0011532e19b7bad61d0bc.nq.gz
│   ├── 7bbbdf45bed96dd74d8c9566653b60262bd9277d.nq.gz
│   ├── 8622b83ced180dc9b502e1e9ed23b20ba6b62623.nq.gz
│   ├── 8d771e187ba4b2ced1b643c804548e5c014bab70.nq.gz
│   ├── 9bdec77ac5b29e31199d9f45b0a26f8714ffe787.nq.gz
│   ├── 9ca56a8830a92c94a3be6a6aeb3dfe77d9cd869b.nq.gz
│   ├── a0f89f59f0ef21b221efa8cb98ec436917dbb18c.nq.gz
│   ├── a30b84ece7248c5536127a235f73485cf31395a5.nq.gz
│   ├── a81c4625c094f11963e67c498ab3809ecb84c1f2.nq.gz
│   ├── bd418d4c38a2ac7224a9d96b73029764359b499a.nq.gz
│   ├── d01d3ec218c3341b0efcc04120cea0290c5f3ca3.nq.gz
│   ├── d242377efcdfd5427de179302d2ac6fa073dfd52.nq.gz
│   ├── d54e174965cd46628cb383227260a3687f776d53.nq.gz
│   ├── d7f24034da74ae7127e62ea8b2b933c5f361a76e.nq.gz
│   ├── da17889de25c0af8df87f111fc73519c3d9f71d1.nq.gz
│   ├── e2499dc77a61a7ecf9ead54e4dc73604be70aa12.nq.gz
│   ├── e2f1ec9875df03a76f26e0e90b7996db34cdf78b.nq.gz
│   ├── ee42655fe13dfe8a93d50501cfb7c0bf698f179c.nq.gz
│   ├── ef7465547ef55990d7d697ce23a053288cd2d3e3.nq.gz
│   ├── f0571dc2b05049fc3780efcdffbafae38febe7a8.nq.gz
│   ├── f54aec03a3d5d381ecc52df19fabbb3396289596.nq.gz
│   ├── f5dd6673bec4bf3819f79fc0814a0fa679508b41.nq.gz
│   └── f7bce81cc839302bf75083cd773ec891413b2f3e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 09413b5be74a693ce82258414a63f6732e48575f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[canonical/sdcore-nrf-operator](https://github.com/canonical/sdcore-nrf-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
