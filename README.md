# Repolex Knowledge Graph of aio-libs/frozenlist

RDF knowledge graph data for [aio-libs/frozenlist](https://github.com/aio-libs/frozenlist), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/frozenlist
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd523c1768feb1763166c210f5f469fdbc31b741
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fd523c1768feb1763166c210f5f469fdbc31b741
│           └── chunk-001.nq.gz
├── blob
│   ├── 0002e68de860bb26978459e699845275aeb4f869.nq.gz
│   ├── 02c81f0c84cf6d1a627fe8637f3196753b0b20fb.nq.gz
│   ├── 03171e898bd11fb7f15bfa3bc5ad78fc231c9a1c.nq.gz
│   ├── 0c6b24b59da47bdf22f22b982e0cf6918c182ad2.nq.gz
│   ├── 0d6072d4ab99c79a2301292d53c3c0f696c6ff41.nq.gz
│   ├── 0de752e04d6009c130bb9bcf4fba4ec198839f98.nq.gz
│   ├── 0e9e6f3b3c59ed5b82dd17965e49159cf19851f0.nq.gz
│   ├── 0ea367f02a180d9e7f7a21de66d0b6bf870e7b24.nq.gz
│   ├── 1214ed64672243ea0c4796f685df39a49b105009.nq.gz
│   ├── 1296381c2e2d0e32701bd4e8a00574008088af35.nq.gz
│   ├── 14eb368bd8b1df2a67b346d3955f5279f468d81d.nq.gz
│   ├── 179ac91ff6d55ace4ac34cd0c7d3913c5d5c4630.nq.gz
│   ├── 19d48b1bcf9329b1118b4e519085a2845b488788.nq.gz
│   ├── 1ac9bdff44c49906d508d785faeacd57deb2fcfd.nq.gz
│   ├── 1e5cbfcccdd9d1206e03448a0768b9993a65fd23.nq.gz
│   ├── 1e60cec3f86c930591d51b1e3bd00ea6f46524c6.nq.gz
│   ├── 1ed99d6935ccc2783d73214021ef3c76e53ff2ee.nq.gz
│   ├── 210557503b50edf163d3ee62a9de129436617346.nq.gz
│   ├── 23d4cdf31f452936b9c9272a3fa9e1d6333b2068.nq.gz
│   ├── 2432bc5b1d38001ad28fa735fa5a3ecb5953a72a.nq.gz
│   ├── 243479fea39c3434a79f29ab5c54dab74908ff6d.nq.gz
│   ├── 2456a302996934c95119963f88011e5a9b4be3b3.nq.gz
│   ├── 24d1be9ddf09b9896c0423d0d1d78bec53bda1d0.nq.gz
│   ├── 25464c5c338904106fb943164325479a43ba312d.nq.gz
│   ├── 27904d9e5818cb5c6b6de7be02ecaad51b83e66d.nq.gz
│   ├── 2879ab2fdd3580dd4a1f12acccefd0b9bdc09cc9.nq.gz
│   ├── 2f7ce1818b7d46fdbf374fbe62fa3ab9444baefd.nq.gz
│   ├── 32b5ee7fd12d7ceb76fdaa54b0610e312f1cc045.nq.gz
│   ├── 3a5e34b20ec912b965541c8ce6fc1ee6775aa95d.nq.gz
│   ├── 3b85cbff515138661a47db11452cd0ab0391bf53.nq.gz
│   ├── 3b8d4bbd5a4021ae35920b628c0c437607792415.nq.gz
│   ├── 3c11b276db636bbb8265fa63c1abcdda9cfb8b8b.nq.gz
│   ├── 3c16a72ef1ebc2c777d1080337b6556c4c339f40.nq.gz
│   ├── 3e32d9ca71794c967d21f9c0fbd95078c0a0454e.nq.gz
│   ├── 4261a8c1b759ab1a278c9ea138cac4c87a06d664.nq.gz
│   ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
│   ├── 442eb9c03f5c91dbbacb4e45c069c66fac98ece2.nq.gz
│   ├── 4880cc2791198ef329ea3e6af2f93d2f8f85283c.nq.gz
│   ├── 4b971726b860ff745bfee6f90f7588b2253e83ac.nq.gz
│   ├── 4c67bd5ec1e1e67a92ec507bab9fc1c96627877d.nq.gz
│   ├── 4d21703c3160afbbbfdae12301978848465a1d8c.nq.gz
│   ├── 5697e45d94dcba59107bd0c3b8c6fe0e81683329.nq.gz
│   ├── 575aa82ef291558bc2b477ada57dea5f7e7741fd.nq.gz
│   ├── 5d594c3ca7e225d254e53c4e3aee4f185053bc41.nq.gz
│   ├── 5f567d23fac3f9c4bdec2a78ab68585ea72bd0ed.nq.gz
│   ├── 609da02ea570d58e6f425854464f65628c0cce97.nq.gz
│   ├── 6549a59fba551f2d9eb95aa7a13ff2c6fefdb027.nq.gz
│   ├── 68cd7c5ad52df22749a064b1b1dd749a129ce617.nq.gz
│   ├── 6c06a3de1378f3eed2139cd4c4fb4326058e750e.nq.gz
│   ├── 7082a2d5b9047bfc09589f387053e24ea490bc54.nq.gz
│   ├── 70e1010d42675fafcf8f06ee2fa4a56d90d564da.nq.gz
│   ├── 74ae436973392f8859ac010016afd2474a0540a6.nq.gz
│   ├── 7705d451d85354719f1d235ca14266d5489d7128.nq.gz
│   ├── 772964b67633aa2a47bb833ad2ab97f366777f08.nq.gz
│   ├── 7ad33e74d8c7bbc63c05980884b5705d2bfe8a94.nq.gz
│   ├── 7fbb51d4b6c3ed5b60e9d949de3502efe4ace4bc.nq.gz
│   ├── 82cb77f057c170d7ad1dabad8f112596859f0198.nq.gz
│   ├── 87c63f5bec5563c77fee81922c3d005042057c37.nq.gz
│   ├── 890d24903db2f7e9ec8264c947cf3c8d84232e24.nq.gz
│   ├── 8e4895e4993f43d2b881da5c9e3c01aa618cd36b.nq.gz
│   ├── 91656c472f597f146bc3f10e23682045569b1345.nq.gz
│   ├── 943d8ffd39788ec3cb0846c8c11351840b82ff0b.nq.gz
│   ├── 947ef2a54929be1c50cf5e645951cd8056d081ab.nq.gz
│   ├── 94e04c1cbd2e212a8b8699631ff8a26beee11c13.nq.gz
│   ├── 95bcb6bf3a3065c82ab2b8c5c1919ab600823501.nq.gz
│   ├── 97aeb7877d8a812f382bf03b7ae3122a03366bfc.nq.gz
│   ├── 983e333cfbae887529bda81c54d24307f07cd02f.nq.gz
│   ├── 9940dc56fb2c98a1c0eb3a6c134ad5bbf2b11851.nq.gz
│   ├── 9a436b37644af28e5af6b09d6c031cfa14628ace.nq.gz
│   ├── 9b3774e7c7aa75e61d28a62411c2a1d46c100193.nq.gz
│   ├── a3527c0aed1fc603dc98268c41ae999db4b3be1e.nq.gz
│   ├── a398826e5564bceef2d4600a8fd9df16903734a6.nq.gz
│   ├── aa6a88085bec315716d9b3a301734ada6857622f.nq.gz
│   ├── aa7198678b7dbaaedae41f51ea1c585a767c7e89.nq.gz
│   ├── aee8da80f0806a0215d24d9f84ff49716b1d0034.nq.gz
│   ├── ba89555b4cb66583f60751ebd440e440c895b162.nq.gz
│   ├── baee32442c53edc9eb7cac374132e500ecfc934a.nq.gz
│   ├── bb3509ace286b276436933010ad60cc2bf3a061a.nq.gz
│   ├── bcb491e8b603c04138f199b75c2b17b4af1fa6cb.nq.gz
│   ├── beda0f05190648a653a272dd82c01f9ccc049cec.nq.gz
│   ├── c0fffc250805fefe4b7865d104a00f7ee937566c.nq.gz
│   ├── c8d8f4d46000c1af124cf56447e3cdd5e9cf1d4f.nq.gz
│   ├── c96dc8611fe14af2d8d4677138d50704cab6b6c4.nq.gz
│   ├── ca3233ab0def82386b8602adfded3b20bd1c5f27.nq.gz
│   ├── cc3a2fc17487126ac6ab39bc2df08a1980e5c046.nq.gz
│   ├── ce0704159b5414a853484caf2137203116b1d2db.nq.gz
│   ├── ce86ecfaa5d0c58d45346413f3812b257e70f61d.nq.gz
│   ├── d00283dfc91c137c534c6bc1663be0ca38405269.nq.gz
│   ├── d08f824639523add746931f1b24b5d91949b3f48.nq.gz
│   ├── d4f315a89878c1ae5ac57e95654d16c1d2010194.nq.gz
│   ├── d6409a0dd82d0c0350c0faed16e26120efb5adef.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7362bc59c999d843e22b297e36dc9fbd1720f9a.nq.gz
│   ├── ea13c82ce0f1ecb131a6c5061036f4cce10e96b3.nq.gz
│   ├── edc6e1b2c675b2b1e70d84ca835fc5d29a2fcdd1.nq.gz
│   ├── f0413b8df561a9a49d8e0190fbca30dfc1f3b309.nq.gz
│   ├── f42760bed80721a42ae3fd1d98e94c604069efac.nq.gz
│   ├── f5642f79f21d872f010979dcf6f0c4a415acc19d.nq.gz
│   ├── f601b193dd278edcd18f5931043e34732d7c107c.nq.gz
│   ├── f65e188f95492174a3a73fce0048b8ccbee12477.nq.gz
│   └── ff03f1a1912423edfaead7f4656c5f10d995429d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fd523c1768feb1763166c210f5f469fdbc31b741.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 109 files
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

[aio-libs/frozenlist](https://github.com/aio-libs/frozenlist)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
