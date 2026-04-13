# Repolex Knowledge Graph of dchest/pyblake2

RDF knowledge graph data for [dchest/pyblake2](https://github.com/dchest/pyblake2), parsed by [repolex](https://repolex.ai).

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
lexq download dchest/pyblake2
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6f2b787a7f5078290a52675e1f484df7a395ce93
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6f2b787a7f5078290a52675e1f484df7a395ce93.nq.gz
│   └── repolex
│       └── 6f2b787a7f5078290a52675e1f484df7a395ce93
│           └── chunk-001.nq.gz
├── blob
│   ├── 0004a98564871337db543fdca80a9ef40551f1b2.nq.gz
│   ├── 010dcbafe7c61d6dd897db31bef617da73006e66.nq.gz
│   ├── 08e88bfbca57cf4cc52120792c1b316db17143f1.nq.gz
│   ├── 099bc69d71fcdbd8757f7bcc2c5c46ec86df9661.nq.gz
│   ├── 0aba84d3f7576c25f860f797cbdef090c0683aed.nq.gz
│   ├── 156fe6a7afdacfd87fed5e51cebdcee7d59fe580.nq.gz
│   ├── 1e75af30c3bceaea98d041460259cd52ada389f5.nq.gz
│   ├── 22afde938287b28b5aeb8849d57e99248e54e4d3.nq.gz
│   ├── 25b50e99ad41b976b4a541f23ea6fad6583ff091.nq.gz
│   ├── 2797722b37b15e4e769e92b582c1baeea5e596ef.nq.gz
│   ├── 2bcd7382b9064a6ab243cab46a6a8633c6b05dec.nq.gz
│   ├── 334a07167631411826a681df079aaedb30b37864.nq.gz
│   ├── 3b736127c4dba1773f34584b9e949975219b8466.nq.gz
│   ├── 3e8b987f85f37b0ddf0fb1f2ffe03a0551bf2afd.nq.gz
│   ├── 42a13493512a6ac282f975f01be98ab475f78911.nq.gz
│   ├── 4ce2255409644fa34d9f5a3159baf3966d95be51.nq.gz
│   ├── 54bf0cdd6143ccb22f670ac360766a3fd41ea1c8.nq.gz
│   ├── 5884d62fe2559f39720a7249997d3e1dd5fb7b2e.nq.gz
│   ├── 6a2e39d153d1786d6c67a6c48cb897c6fb2c4319.nq.gz
│   ├── 6a4a894d2fdbbb3ad5cff576b6683a58e27c46cc.nq.gz
│   ├── 6af0208a4b56de2341e517d79c6557635e241d74.nq.gz
│   ├── 7470d928a215810fae08af0e52c3ea44bc4e1cc3.nq.gz
│   ├── 78fa8146fccd3279be602ed42e14315f359772ed.nq.gz
│   ├── 9d309e0017255f2b078c76b9f1b27548ef8c91e0.nq.gz
│   ├── b47f8bc4eb8ad07b837479d3a87016ab15d5369e.nq.gz
│   ├── b5a71aeb33e9cd5b2e1c09bcdb3e080011b80786.nq.gz
│   ├── b6e34f5f60ee95dea2e57a0996c5f8dd0f7d7673.nq.gz
│   ├── c386530baa35fdfce6b0caed4d75a7192c473050.nq.gz
│   ├── ccd8b7e70570e012edf077409c400a833d55fdec.nq.gz
│   ├── ce8ec0b6f7d4269ce0726226418b53363dd282b1.nq.gz
│   ├── d892b35137e4e729436259c652780c2985a8d1c8.nq.gz
│   ├── eadefa7a52800ef4cc7e1668ef2ff61c3ca55b9e.nq.gz
│   ├── ed3dcc15acaa6f7ccfdd7d1d2f2e32bd21aad2e4.nq.gz
│   ├── ee9d87568b7a68ae153407dffbc872e15bdae5f7.nq.gz
│   ├── eea416ef1ff70b0de0120168d0cf0c1bee99f2c0.nq.gz
│   ├── eeb144fad00e02f877c9457d71c05c8e01f824bc.nq.gz
│   ├── f37be432f1e3881343305153705dd8412cd56e3a.nq.gz
│   └── f63e45a9be3f580566d0b0771081bb7fcddeb3fe.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 6f2b787a7f5078290a52675e1f484df7a395ce93.nq.gz
├── filetree
│   └── 6f2b787a7f5078290a52675e1f484df7a395ce93.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 48 files
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

[dchest/pyblake2](https://github.com/dchest/pyblake2)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
