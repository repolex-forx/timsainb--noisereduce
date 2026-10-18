# Repolex Knowledge Graph of timsainb/noisereduce

RDF knowledge graph data for [timsainb/noisereduce](https://github.com/timsainb/noisereduce), parsed by [repolex](https://repolex.ai).

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
rlex download timsainb/noisereduce
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 51c85343d6fe7695f7641f96b6a8f9e7e66be59b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 51c85343d6fe7695f7641f96b6a8f9e7e66be59b
│           └── chunk-001.nq.gz
├── blob
│   ├── 003f484ff69d4b676ad79c167656fd243c308dc7.nq.gz
│   ├── 066d46595fbdd9a3f5fdc8f5f8b79d4c04b6791a.nq.gz
│   ├── 15bb8f73acf740fdde677f707e2a65cce51fe0d7.nq.gz
│   ├── 1b0646533a51b28ce60e98b088375e76a7b9a2b8.nq.gz
│   ├── 27ec6f60ce00a0e835113deba6ee227dbf132a10.nq.gz
│   ├── 2a1bca2ca5107b066da3db472e281e7267a5b703.nq.gz
│   ├── 2bc7ddc5e995d2fe57b389277e0bb230b292473d.nq.gz
│   ├── 2d162f36724fe7e2f1d1e8cedbe8af567dcdd21d.nq.gz
│   ├── 3a990aa2f56a956189a1ccf2e6587f1ab1998141.nq.gz
│   ├── 49b9f24bfd5549b08f35f48828b20d963bf46d56.nq.gz
│   ├── 51b53f93a93dc82e700b57c318a45d999250e342.nq.gz
│   ├── 61c1e982965fb49517f572276e8671e354ecdaa6.nq.gz
│   ├── 61ed9c699691ceb34bfdf3bee9390daa8a85b46b.nq.gz
│   ├── 64dd4ef63ec28a089bf79e5a45883d9a9b15338a.nq.gz
│   ├── 71e6de574736dedb87fea2b81be1a3fc27ac7aea.nq.gz
│   ├── 72028979dbe9f0b489440a0543e71fa4f8a2500d.nq.gz
│   ├── 761130538a7ac98cf28f07301809dc45d6fc5555.nq.gz
│   ├── 7f056ed825ad8dbc88f6b0872fe3d3bb79bde754.nq.gz
│   ├── 84bcb8f7a3c31a4c026212617a9bb4649efc756a.nq.gz
│   ├── 850cce8ec624d010dbbe48aa81bb0e2b4def9089.nq.gz
│   ├── 95503d302dc981ae1fd02ca2f75f44e36b9185f5.nq.gz
│   ├── a3f6d1c15395aec29babd0339d0a24dcde9d5ac2.nq.gz
│   ├── b05cd5531b4e0d2232219cd25945ac80a66950c6.nq.gz
│   ├── b4a12675828dceb6e6270f9439cdf98ea28ea96d.nq.gz
│   ├── b4f71c3a293b7c30dbb94afd6f3e58997b55ceef.nq.gz
│   ├── c19df3cf3a45113c401ce2f5378a6ccb2eaeb7fc.nq.gz
│   ├── c32fbd859bf4cc4f5e2e65690c00889b54683af7.nq.gz
│   ├── cc4d396e1be65f4b4b98b5c0683af052b628e84c.nq.gz
│   ├── cc5bce747b5f8ebcca432e88a664929625099932.nq.gz
│   ├── d0ac4a7252c9cf9c057ca5b9659acba6b4bffa6f.nq.gz
│   ├── d32a0c74bcbb5336d88eff10550660871004e1ad.nq.gz
│   ├── d7c9832ff3c60eeb0b764a3b8d40fa4dad2cfee5.nq.gz
│   ├── dc97d45a399c112c76e80cdd8c73cfebaf3ef6ad.nq.gz
│   ├── dda7dc39fcb1acb2eaf75900335e271e795ebbee.nq.gz
│   ├── e38ecd168aada6ca8868039307fec39bd34fcc95.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f1b535b02d33781c5cdca4b40a2e2766d446c2c7.nq.gz
│   ├── f3d669b9f77da82b0a64c42ce9e4e8b8a0578713.nq.gz
│   ├── f570a6cd44bc9bb8119871ff18357b9848fa6e97.nq.gz
│   ├── fcad3d5b09db198810d358faf7a4b7c3cba3d76d.nq.gz
│   ├── fd007288ccbbb896bef67c000a25f2b83ed3dc7f.nq.gz
│   └── fff68f89ccf8c8c5694550122639bb36fff77bba.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 51c85343d6fe7695f7641f96b6a8f9e7e66be59b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[timsainb/noisereduce](https://github.com/timsainb/noisereduce)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
