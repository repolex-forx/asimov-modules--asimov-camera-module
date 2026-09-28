# Repolex Knowledge Graph of asimov-modules/asimov-camera-module

RDF knowledge graph data for [asimov-modules/asimov-camera-module](https://github.com/asimov-modules/asimov-camera-module), parsed by [repolex](https://repolex.ai).

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
rlex download asimov-modules/asimov-camera-module
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6518502fff8aadc64933017031025052d3093341
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6518502fff8aadc64933017031025052d3093341.nq.gz
│   └── repolex
│       └── 6518502fff8aadc64933017031025052d3093341
│           └── chunk-001.nq.gz
├── blob
│   ├── 0448a675f298d920eba199ef7c72cfb701f12e12.nq.gz
│   ├── 0a1ddf0de2c1e0caef9af6fa4b3e97b895f72314.nq.gz
│   ├── 0faf320ab61483f47f7040f2f4132d61b2b0e756.nq.gz
│   ├── 10b359dd05935c73efb064470f9ecda90f6d28aa.nq.gz
│   ├── 23398a962e5a8e7a8ef402e90db0654d13c469c7.nq.gz
│   ├── 234473bfd3254e262c5227fb682ed22629b2cb2c.nq.gz
│   ├── 298489affd3cf628f19ed14edf73f281b23f84a9.nq.gz
│   ├── 36c903e679cb80eae39369c5ae9e1c21c79493d3.nq.gz
│   ├── 3bc7a82b1baa3ecbda0d4001f322806efccf4d28.nq.gz
│   ├── 3d38970fd2a8a1323d753b4a058f46388953e1fe.nq.gz
│   ├── 3f12bfd5f06b69c56ef8c44459bffa1818d74ee9.nq.gz
│   ├── 4fe51dbf66fa8562e8b50ccb25ef1d5c5b889711.nq.gz
│   ├── 512a06f8cc558b0e4dbfdbaeb5fddf89f452317c.nq.gz
│   ├── 558ac6acba6631e06d42918d67294f79e4f66951.nq.gz
│   ├── 60b79e68d5638c8c145ce4c3f5e19d96f07c8f62.nq.gz
│   ├── 624a611549a5a8f1c378ba631ff06e41e9e0abed.nq.gz
│   ├── 63eff4addb9c9deca60d37ad3b651e7eb7f9ce71.nq.gz
│   ├── 645a0a2ea6fa3e09226ae7052969807408e77955.nq.gz
│   ├── 64b83f8244ccbc7ef539512a458d95f5f098a1d8.nq.gz
│   ├── 6b8f487f1f5236374b87a2f5899f985228cd5947.nq.gz
│   ├── 79d132922ac9133c2126bd9c7f52ca511d0ea118.nq.gz
│   ├── 7d5136efeb2efc60dd752606cb8cabdc22decae4.nq.gz
│   ├── 7f07ae3990bd80af064c7d4e5f160ab872cc59fb.nq.gz
│   ├── 7ff9b2f49c08e090f2e7e6339cf964e83ee3e905.nq.gz
│   ├── 8361fe21af45a65a3ead7cede90cea2992ab15d1.nq.gz
│   ├── 8c29d3eca35f22e5752316a7af6a39d98ac8c2cf.nq.gz
│   ├── 98db550908bb73c01575d35f2241d1fc7a60270e.nq.gz
│   ├── 9fe50de16e59d550235aa6d7d15ee12ddf054414.nq.gz
│   ├── a04e39a4936ed178f8231219ceb15cb82931176d.nq.gz
│   ├── a3bc67872ecc6d35eedfc17e8b6fcad9f794c3ed.nq.gz
│   ├── a4b6a065822b9d305c2ccfb3d54afa1d452800de.nq.gz
│   ├── a79f18aa1deb67a3a54df39dedcf9c92d8791ca2.nq.gz
│   ├── abd3ff0a1b3e6ca9eeb0e29b69ce354cdec8f333.nq.gz
│   ├── af9908b08f4b33c32a0080af73f53bc0fa0cdce4.nq.gz
│   ├── bcab45af15a0f1b0166daf8cbf18b17cd8649277.nq.gz
│   ├── cee9a659ccfe788a3d6675155715c2cf3c3e346d.nq.gz
│   ├── cf42f6893594e2f8be2b722de51123d65e4d61c4.nq.gz
│   ├── d0127e51849dcf1f93a4895e03a3127c7409da96.nq.gz
│   ├── d02399eca759ae5aa685eb5d1bd3e5ea3c3fd966.nq.gz
│   ├── e3e57a8ce4ccbf74759a6df8fa4a3980ff1c9209.nq.gz
│   ├── e6203bce6ab9a31677ec65e3cc41928d7960f3b0.nq.gz
│   ├── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
│   ├── fb3f4161e075934893666d7c53f722120b911f97.nq.gz
│   └── fed481d93150d9dbbd357e49acea2363ca5fc1e8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 6518502fff8aadc64933017031025052d3093341.nq.gz
├── filetree
│   └── 6518502fff8aadc64933017031025052d3093341.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 54 files
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

[asimov-modules/asimov-camera-module](https://github.com/asimov-modules/asimov-camera-module)

---
*Parsed on 2026-09-28 by [repolex](https://repolex.ai)*
