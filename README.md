# Repolex Knowledge Graph of pytest-dev/blog.pytest.org

RDF knowledge graph data for [pytest-dev/blog.pytest.org](https://github.com/pytest-dev/blog.pytest.org), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/blog.pytest.org
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eefcfa65348b5e3ad8f4eb5371075fa5ca0de216
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eefcfa65348b5e3ad8f4eb5371075fa5ca0de216
│           └── chunk-001.nq.gz
├── blob
│   ├── 042208d3f5c0b15e6ba9f608c9e6a7f32f837d34.nq.gz
│   ├── 096ff11ca1d179db7db2a860d540b93ff9d2b13b.nq.gz
│   ├── 10cd05be7d1a4fb823902f2cfdc5906c0ca344b0.nq.gz
│   ├── 1413fc609ab6f21774de0cb7e01360095584f65b.nq.gz
│   ├── 192eabb98aa76be76e25944b46d773bf4100aa65.nq.gz
│   ├── 1fb256167daa8e42a94b176cb743ea02b5054931.nq.gz
│   ├── 1fca1620fcdaf60566b57d31ca538b459ef76afe.nq.gz
│   ├── 292a2c963636a745bb8fd68b1d56f53955b0abeb.nq.gz
│   ├── 2d35b64b940b49510f4986bc2373a54720f2b17c.nq.gz
│   ├── 39dd7aa7eb2bd0432a8ec6ab4af17c2a619ff884.nq.gz
│   ├── 3e4bc8a8db3bab1949b90138e49991ed79750b34.nq.gz
│   ├── 4e3b1df670ef5162372c866e0cc9480ea13ef5e6.nq.gz
│   ├── 57eadc030ea86ea65a3747c27dfa3ef334f8f79a.nq.gz
│   ├── 58c7f373796ddaf9a581baf105661242c8a6c620.nq.gz
│   ├── 5a109390e0f845eadccedd213effd4bb3caeb1dd.nq.gz
│   ├── 5f12a935a8c7f7776218dce93a264b5f1ab9076d.nq.gz
│   ├── 60061c472016f65cf3363ef784c78f2a9ff56568.nq.gz
│   ├── 64539b54c3751a6d9adb44c8e3a45ba5a73b77f0.nq.gz
│   ├── 6523d3a1b31811de7b291a13020c8fa567c99bc6.nq.gz
│   ├── 66dfe81cdede64c5eeb153b391d7fd9e95fa7824.nq.gz
│   ├── 67b75dd5e0b3deb4eadb195e952ad1abd1f0a815.nq.gz
│   ├── 6a34fe5c9f7e4a258b0f4ed2cf2efb021dcfbcb2.nq.gz
│   ├── 6e5f29a3127afec7e35029bce3aaee9a897d418a.nq.gz
│   ├── 721c0207f830a8b8fd7d51fef6c27d52ad78ef1f.nq.gz
│   ├── 7cbb4f92498c33b0bdb19fdd1a8fa11dda30d4b4.nq.gz
│   ├── 7e9b14d4719e2ee243d24e0e5067ef66cf524ee5.nq.gz
│   ├── 8a8c993834670ef1be426219d55092b57080f08f.nq.gz
│   ├── 94fb5490a2ed10b2c69a4a567a4fd2e4f706d841.nq.gz
│   ├── 95c0553a4c4c67dbf1d60915be672c78ecba4eca.nq.gz
│   ├── 95c3909ab3b63cec209120b76d0b8ac718af5f55.nq.gz
│   ├── 961fac7fcea435d143d000c675eb0ef11f5013e5.nq.gz
│   ├── 98b3427daea92420b2829eb6aa89dc8681a52eed.nq.gz
│   ├── 9e612858f802245ddcbf59788a0db942224bab35.nq.gz
│   ├── 9ecca7d6a5e7ee5dddb1d4bc4a182483a3abf4a2.nq.gz
│   ├── a149cebbf00a0b54bc2b02f044f4e06458510359.nq.gz
│   ├── ad614d4601eac74adf48aefc00ff39ecca10d741.nq.gz
│   ├── ada44cfac1a40f6414249f97ed5c6d557c20a076.nq.gz
│   ├── b93a4953fff68df523aa7656497ee339d6026d64.nq.gz
│   ├── ca4615f47efeed28e43ed0587e6477cab1947217.nq.gz
│   ├── ce013625030ba8dba906f756967f9e9ca394464a.nq.gz
│   ├── d68a51fee5260618fcea50ce2d8a92119c0a51ac.nq.gz
│   ├── d9b609b24a9a0a29003c78dcee4d4e9ffc2868cc.nq.gz
│   ├── ddf5dde81b3c9835e99c2254a01564a80658a60a.nq.gz
│   ├── deeb330c4afb53fa3992249a2d88c461a1620edd.nq.gz
│   ├── e2fd0a548063576787767e253d5be1d50fc50e67.nq.gz
│   ├── e32059234dedc74413e641946879fd6ce3e01f13.nq.gz
│   ├── e8064a694ca8eff0f2167d29ad13609f9a99a46e.nq.gz
│   ├── e9cc2ae6e316c3a4f47342c3b2c6e9b0da8697a8.nq.gz
│   ├── ec90b8e649087f6c477c3573429bf15f2c8462c3.nq.gz
│   ├── f4759938320b582f8a16de207b7d19412327e2f0.nq.gz
│   └── ffb888f16ffd77d8044d832b383c0fb47cbbd0d2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── eefcfa65348b5e3ad8f4eb5371075fa5ca0de216.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[pytest-dev/blog.pytest.org](https://github.com/pytest-dev/blog.pytest.org)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
