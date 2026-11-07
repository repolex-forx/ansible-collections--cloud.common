# Repolex Knowledge Graph of ansible-collections/cloud.common

RDF knowledge graph data for [ansible-collections/cloud.common](https://github.com/ansible-collections/cloud.common), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/cloud.common
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 223144df28173a1c027256c1b20e0553764ab9d5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 223144df28173a1c027256c1b20e0553764ab9d5
│           └── chunk-001.nq.gz
├── blob
│   ├── 05012468b5930a91b1e3f7de4d1d8176ed9d4157.nq.gz
│   ├── 069ba44903419e399a77443f008903de53295ee7.nq.gz
│   ├── 0b7006b27acb61e79475359a98471e8a2eab238f.nq.gz
│   ├── 113fc5294c530ec429bef14781ffb5d182302969.nq.gz
│   ├── 1321384cc25086a3a7607c925f3563c7c809fcd9.nq.gz
│   ├── 152107c43a84c1c11379fa6e46210c6d629ffe8c.nq.gz
│   ├── 1a14f07544fac6d87aff6d18ec5252f7bb04ad7f.nq.gz
│   ├── 1e3d0b06c114fa6c9658971b2e24aaefcb20fff4.nq.gz
│   ├── 21b6b8c52622cf67b78b9195c62c201bd5d452eb.nq.gz
│   ├── 21ed48ed675b89fb2f726d87c1a616447b0357de.nq.gz
│   ├── 2975a6e97335f90f177b62984c9c93f9075654f5.nq.gz
│   ├── 29cc0b4f15bec2fa46f44ddd3f3f263b7ff1ec92.nq.gz
│   ├── 30093b55e2397d9767bfb47243438d0c1bbc43bc.nq.gz
│   ├── 3408e1b0f5fd1ada4bbd420495207ab53091be46.nq.gz
│   ├── 42a96af3f4edb97425d2bed9ea0171e731df20c2.nq.gz
│   ├── 45c6d9bb73aca31fffc394ea3a409e3ae3beba11.nq.gz
│   ├── 4c43575dfbe37e4d8ecad92a543a5356aaae99c9.nq.gz
│   ├── 4d69b0d014895dbfe5b013131c43f78d1301fd19.nq.gz
│   ├── 5e27470e6b203c5771f05ea54ea05861da154a96.nq.gz
│   ├── 79bad358071e08b2bcd17c725f4ca95d6da0c5b5.nq.gz
│   ├── 86227ab6e90eeaadc57c7b5865603480d65887d2.nq.gz
│   ├── 8db1dd9b2b41aa64e36c231798908c7b8d7681cc.nq.gz
│   ├── 98140c3b3342343663279e24dd31eb456c092e10.nq.gz
│   ├── 9891fad7ba9133bde93ec64e44910a539205bcae.nq.gz
│   ├── 98f6015a4dcf4ba78b921c8fa8bbf8dbd3b579b6.nq.gz
│   ├── a0726d24527809738e11231f8a7c68e892fb63e3.nq.gz
│   ├── a115a59bd1cb4a7623521e8f8573377a15997f63.nq.gz
│   ├── a3f6d29d1ef4ac9e9f5894b254c286705daf2fdc.nq.gz
│   ├── a442d23eac6902f8a0d3fed1a63f60ef00c9075f.nq.gz
│   ├── a4d1f6d7ae74da404c9fce25312ad1422665ad2f.nq.gz
│   ├── a51a2d40bcf6b52a72553eb5be49c0af24e05e95.nq.gz
│   ├── aab58c6a4e94b70bea40dd726d356b4eebd3960b.nq.gz
│   ├── acad2cba2a5f2eb80bae85d300b8b2329b719718.nq.gz
│   ├── c7fcb21f22dc7d52d5ded4df04e9581dfe70824c.nq.gz
│   ├── c9a0048f89afafd9c36eb6976b2a07bd0582a38d.nq.gz
│   ├── d0cc6d862f6f5fa6cc97ba015ca06c85c55d69e3.nq.gz
│   ├── d2f86e3cc167d573ec0a67a94cf28d1941a423f0.nq.gz
│   ├── d5b7ed56714573c3e15514c640b52589f1eaec28.nq.gz
│   ├── d95a025904e211f64b61bc0742ce481fa0f41c77.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7b94a256ccf517d8123d7ce005745c468d9e94a.nq.gz
│   ├── eabb5a9364b84494867e41c2638de37d050a295b.nq.gz
│   ├── eae1ce2a2d9136d6c1bd9e08b4cd47349dc8b064.nq.gz
│   ├── ebe9b0c2a09c96d687d8f7af9c83ac3ea85f07b3.nq.gz
│   ├── ecb7669dff8cd300400ef965c6ddac08ee5664ad.nq.gz
│   ├── eee856c705e105850be0cb2ecedc9e1420b25f30.nq.gz
│   ├── ef8832157c91c589173d08918a85935cf68bd9d1.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f5202379c43982101408b151bc5034e6e091564d.nq.gz
│   └── fc75a8e539cada489f2a55b12441659c884c643e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 223144df28173a1c027256c1b20e0553764ab9d5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 58 files
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

[ansible-collections/cloud.common](https://github.com/ansible-collections/cloud.common)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
