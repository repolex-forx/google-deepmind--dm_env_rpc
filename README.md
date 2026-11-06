# Repolex Knowledge Graph of google-deepmind/dm_env_rpc

RDF knowledge graph data for [google-deepmind/dm_env_rpc](https://github.com/google-deepmind/dm_env_rpc), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/dm_env_rpc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7037e319d7a7cc5b0c89fd9caf8488af6898e07c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7037e319d7a7cc5b0c89fd9caf8488af6898e07c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0233e5494322b68dda1a8c9d12198b50c9ecc41c.nq.gz
│   ├── 07731daf0c8ebcec0c16a0e069d654bfbd19adc3.nq.gz
│   ├── 09d69aa0265f31acd6a5db1bb950474f44311ee9.nq.gz
│   ├── 0dfe25e4ff6952aacc327cbbe4a43228b0b4f61b.nq.gz
│   ├── 0eac52466a9852eba29fffe955c8d364cef299d7.nq.gz
│   ├── 0ec1ecc1f2a0220137198845109552a31cdaad60.nq.gz
│   ├── 1303cf870ff688dd964d977c8efd7f48afe7700e.nq.gz
│   ├── 1838bb51b814bb196c1f543b05eaec92805aabf9.nq.gz
│   ├── 19b2c51e0128c9684b2455834b7bcf74f488dee0.nq.gz
│   ├── 1d7bf08578391f5479d91a2fbd4c1d1e1b827637.nq.gz
│   ├── 2719e93aaa3420ebeac4da88af2e93f719dcff09.nq.gz
│   ├── 2989d1f4eeddc323894d3efe2b9b1167383cb0a1.nq.gz
│   ├── 2dab64e421d705a2664028b58a3b23944eef72af.nq.gz
│   ├── 31b8e01806066ad492673969d34d068aa53482e9.nq.gz
│   ├── 3646dccb09c2cf86fef6bdd3565731ce8b70f7cd.nq.gz
│   ├── 38ff82f26a71457e5a0024e2b922f3ed8d2ca282.nq.gz
│   ├── 43cd79c5bfca2d488cfdeeaa8b065d98809fa5da.nq.gz
│   ├── 44e2868f1867f9d7d3a390a7bafcab698394bdad.nq.gz
│   ├── 45d92bb61ec837dc02a04cdec8da83e88f5c5b82.nq.gz
│   ├── 46be88b1423de6c8c21b382c85a00a46ef0cfd37.nq.gz
│   ├── 495c54eb18d91dbcf7a9ee393ced93bb9457c7d1.nq.gz
│   ├── 52251bd4902b39da3d1bdfa70b3e11572b237b4d.nq.gz
│   ├── 59f48cd79fe92c42283ea5a5740075175a6186a9.nq.gz
│   ├── 5df57119c90b43032905e67f3154ae51d4a7b799.nq.gz
│   ├── 5f2f9b69522c532245d6b623852af8d1045b8905.nq.gz
│   ├── 6094cff96dd2c55830e590e0f7cf5614092212b7.nq.gz
│   ├── 66f0c455521bbbef138ba6d40a5775d5df65d8b3.nq.gz
│   ├── 6a03920da6c2c26884a7098cc35cc65424655768.nq.gz
│   ├── 6cd0d60a9883ae7c4c417b847374df8ff3e7bd6b.nq.gz
│   ├── 73cec28e4c68448e9d2307f18769af81f9d4218f.nq.gz
│   ├── 7d801d9076b6c9680fae3393e8da08640e615453.nq.gz
│   ├── 7e849f6d7e28015970263d8e9574e6dcd263218c.nq.gz
│   ├── 838bbcfc56a8dfaf3bfadc1b167279c3fdc9f3e9.nq.gz
│   ├── 8408161fb911fe89dfbab622d12b4ffcedddd084.nq.gz
│   ├── 842a62b76670ca4a3fcb099514b0adfe7ed80e9a.nq.gz
│   ├── 88b032526c049c38b085ec26bf7b51fdf797147f.nq.gz
│   ├── 8a43c795eebac631a9d3164cb9f7b10770769eab.nq.gz
│   ├── 8b3a4d0e7778c25d764657e1bd93a7d64e731df5.nq.gz
│   ├── 8b4969c4c1950b32f3b55ac3a6d2e1ff7e2d8051.nq.gz
│   ├── 8f741054978f4ce61ee77482b35b467bef2d8f29.nq.gz
│   ├── 909528a5eae6f1e8c358adbfe53a6762b2da8463.nq.gz
│   ├── 986db071ca1d956e7bdf841e0d7950eec01c2ac5.nq.gz
│   ├── a3ab10dac6635581b5cb7ac9a9f0e9de529c4d84.nq.gz
│   ├── aff7a8b994d13e62a0664d7b75d959aa37dcd9e8.nq.gz
│   ├── b159e524235cfb0f5bb1eefee9a4af772df0f6c9.nq.gz
│   ├── b9affd068f73e315939c0dc7ae64dcf0870b182d.nq.gz
│   ├── ba84e83295e44e2dc45388ec8aa8c8f71e6adae4.nq.gz
│   ├── c31fd1f8016583293b1ad9ffd00d3d46510bb144.nq.gz
│   ├── c859fc0fc2be2bfd8f983770e0bf34421596e42b.nq.gz
│   ├── cfd41b0d2ad8031ebad12b97251ffe2b43c57b5a.nq.gz
│   ├── d57ec76468055cf6ae971027e674d12b4c9ae4a5.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── ea14b7c87fada9e42217a6db3db6d203ecba935c.nq.gz
│   ├── eaf7e01d5211dad01b711795a3b41565e77f4ce5.nq.gz
│   ├── edb239be2b2c7ab705fc62053be5dcb0c2e7af5f.nq.gz
│   ├── ef8164d986af91a9ae698098c742c54354f46613.nq.gz
│   ├── efc20f7e10a6ae1394e30fa408a6cd6e9b14ad91.nq.gz
│   ├── f410ec13b924ff8061934f13281afe473aec4560.nq.gz
│   ├── f6f40ab77580aac78166837e3f9267de1e05633d.nq.gz
│   ├── f6fcda1d8bb99b7a7ad8343f1b38de976432981e.nq.gz
│   ├── fbadeda8c023dccd0ef0fc9dfc6708050e7ecc36.nq.gz
│   └── fc9c02e7e81b1441dbe8e7fae79efac3ca72a9b7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7037e319d7a7cc5b0c89fd9caf8488af6898e07c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[google-deepmind/dm_env_rpc](https://github.com/google-deepmind/dm_env_rpc)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
