# Repolex Knowledge Graph of crossterm-rs/crossterm

RDF knowledge graph data for [crossterm-rs/crossterm](https://github.com/crossterm-rs/crossterm), parsed by [repolex](https://repolex.ai).

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
lexq download crossterm-rs/crossterm
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 36d95b26a26e64b0f8c12edfe11f410a6d56a812
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 36d95b26a26e64b0f8c12edfe11f410a6d56a812.nq.gz
│   └── repolex
│       └── 36d95b26a26e64b0f8c12edfe11f410a6d56a812
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d50a65649c10e3736157e0338ebd49185c118d.nq.gz
│   ├── 00e88ee5069bf9cd3578de60c426ce70e18e2d0b.nq.gz
│   ├── 025db73d27b576138036a7ea5b58a9c3d28008ee.nq.gz
│   ├── 02ce9e283ee6b87051b27b7e16868d9eef3d566b.nq.gz
│   ├── 034b54ad69e4d6482f8c13c0615c411b688a8e67.nq.gz
│   ├── 0a04fc5fbc6308c9021fd7356369eac4d59597f8.nq.gz
│   ├── 0b4afbf0cc43f73d76521e6073295cf9a303f6cd.nq.gz
│   ├── 1623740a74bf4e40987338542ce64e0352b5b4a9.nq.gz
│   ├── 1b1c448d813f3c58cd8a0a8ce2a1ab3b66790d57.nq.gz
│   ├── 1c55f3b801ae307ca8e1b6231f6a9005d1664e86.nq.gz
│   ├── 1db95a210d982c217fff6ea93b8fe5326ac01ea1.nq.gz
│   ├── 1e838fc65385e230debea482e4da394430f1ef18.nq.gz
│   ├── 20b6405f030151a71a95d769b6b3ef62db56cf2d.nq.gz
│   ├── 2106ca0cc5bf09073efc4da7fc148372c2005e44.nq.gz
│   ├── 22f989b4dd9dcd846c0ca9f800d3c222ab1f098e.nq.gz
│   ├── 24796dc4506c43c80a7b2cf5e48ccf3134b6add5.nq.gz
│   ├── 29377438f7ae04eb1710545748f242c27d832b5e.nq.gz
│   ├── 39ebe0dbef8d1f1b5f6f0ede7085453b5a0c9aa4.nq.gz
│   ├── 3aebc1f8ef1f52595d636d65c5b20cc0e4b37dc5.nq.gz
│   ├── 41c3797dd9ebdc751273ee5d0554f58d76b7e9d0.nq.gz
│   ├── 473421207ecf8442d410b556276189c645a77459.nq.gz
│   ├── 47ded98594abcd396d684948655472f268cc52a0.nq.gz
│   ├── 47f35666895f6875c43743f07df5c037b0f03129.nq.gz
│   ├── 4fba674e15ad7c2e9ea1894e22e5bd39c4b3d84d.nq.gz
│   ├── 50a797e2013fe126c54a3886613284009ee36244.nq.gz
│   ├── 575346d48826a3fd02988847c1e471a2bcfeb869.nq.gz
│   ├── 5a5427620ee0e1c39db943259d9a27fc2373ca7f.nq.gz
│   ├── 5a710b4abd4f2a106f52b1054eac8ca469d53367.nq.gz
│   ├── 5eb1c7317283390a7ad3f419553b1a1a0fe85480.nq.gz
│   ├── 6696b18795be1669742d15e3439775ace5ca6ef7.nq.gz
│   ├── 6c067528c728e1a5b92acb92693b75e8860cf39e.nq.gz
│   ├── 6cea39ce1e4c9aad80a37f184ad337b3bb564246.nq.gz
│   ├── 6d19e0c5ca0ada021bb7852b2429618f92fc5ee0.nq.gz
│   ├── 6e99bb6665a2cfde27a9134a88987559b7dbdd6d.nq.gz
│   ├── 7585238efedfc33acdd9494b0269951aaf3909ec.nq.gz
│   ├── 75913112d71d128febbea1e928e9419f47c0757f.nq.gz
│   ├── 7cd7d6eec7e99750f601d6e1be98aaa559634759.nq.gz
│   ├── 810bad38c08b16cfe0fccd450f15be37d175e735.nq.gz
│   ├── 82e695a32b4cf62fb93dbc5c6fc906092c816ac4.nq.gz
│   ├── 83dea3edc5586dcb784be3891a2f339d1d808625.nq.gz
│   ├── 84d9bf76bb4e5fde6d9991061a3656f51dea2549.nq.gz
│   ├── 85770e23b8de06a0059cd8b4d4c12d8f0f85a510.nq.gz
│   ├── 87ea92d4cd18617b7b325fcbca1b47a93e0347ec.nq.gz
│   ├── 8b02a7fcef9fa4f7b7c5782e85ac25de76643235.nq.gz
│   ├── 8fda30b64f442e043bf7116c5e860d6e3a8d2d36.nq.gz
│   ├── 933310bf9838fee250bafc529e670291a71cbfbd.nq.gz
│   ├── 96818291d72fe1b5e5a29e769a58308206d49a19.nq.gz
│   ├── 97677ecf6fce2ee5a78d29ec060c343d1d9637dd.nq.gz
│   ├── 9ad10d563483c96e69c56a1255616e664701318a.nq.gz
│   ├── 9dde47d0e98e42ba18bb68ff4331e848ec105581.nq.gz
│   ├── 9ec582bf4b06e1a31c14e0c488c856e600c3b7fa.nq.gz
│   ├── a30063dbe91bb39e4a010d98688b32d8e58c6530.nq.gz
│   ├── a64161eeb700f63f92e7cff80052d6b1bc9ef2e8.nq.gz
│   ├── aaf74fe21af5ddf762b38dd7e3657f879b02e8e2.nq.gz
│   ├── abd54495e32b1621345c8942ad5de02e6ed1d46a.nq.gz
│   ├── ac2b2e295a821918ab95879fd67fdb621fc5579b.nq.gz
│   ├── b4a40b19887c068b9adbced3fdc73b13c970e4a8.nq.gz
│   ├── baff266c67cbd0e90f3a3d7ad2c0bc9ecdee124f.nq.gz
│   ├── bd79307351ad9e3179df7371d7ac56524b0c696f.nq.gz
│   ├── c18a6877e6ba3ef8fdb865c25500711b08c3f859.nq.gz
│   ├── c9884ec3c02b9ba13957649912eb609e0be8f28e.nq.gz
│   ├── cd71fab8c239a388d40693953ae4375f24003890.nq.gz
│   ├── cd7abce2b995c808449f573715ec2800fdd403b3.nq.gz
│   ├── ce523c6378bc31d5fbad790ed8e60058322982c1.nq.gz
│   ├── d2f57f607a788d5560018ea85177461d94b927ec.nq.gz
│   ├── d34ac457ea4505c675de5fd2a89b31f241c3bbd0.nq.gz
│   ├── d405ae821818ffbbda04e7a09d9ca977c2477680.nq.gz
│   ├── d584b4c98e195b1a59a3efa58e09618986d3458b.nq.gz
│   ├── d99d4e2785499fe80c69a7f288d4866d077f0951.nq.gz
│   ├── df960ab2093c8e1c82e62fe3ceb5a3ea73df7ef1.nq.gz
│   ├── e53bd31eacb70e973cb150f01c4707d6a4041ed4.nq.gz
│   ├── e74dceae690f32efb9903321dcf541c742fd2181.nq.gz
│   ├── e8f9007039917b5e2db7d5e180efe92b26695537.nq.gz
│   ├── ed60c9d8cdf62074c0321f2c2aa71453cc790ae1.nq.gz
│   ├── f266d28dcc907f7bf27d6a9fe4899c89bbe6a3b6.nq.gz
│   ├── f4ada1569b9d4d5b9c86a76a3f12d02fa6cfe58e.nq.gz
│   ├── f4bc72d331218a80fd621c97961765e28f8a215d.nq.gz
│   ├── f5e48b77db12f414308d5e00942c104809f85bbb.nq.gz
│   ├── f7a5134d34cd7caff1000becc7232feeb8fc1336.nq.gz
│   ├── fa40cc5027773d0e2f825ac955237d1ae289debf.nq.gz
│   ├── fc2f6f14473bbac5a29ef5337889be6e7b60a483.nq.gz
│   ├── fcb12da5c4265fece31e991ec3bed3d6dca7735d.nq.gz
│   └── fec881f0d534c108121e9d86ed64b279fd336b9f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 36d95b26a26e64b0f8c12edfe11f410a6d56a812.nq.gz
├── filetree
│   └── 36d95b26a26e64b0f8c12edfe11f410a6d56a812.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 93 files
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

[crossterm-rs/crossterm](https://github.com/crossterm-rs/crossterm)

---
*Parsed on 2026-04-23 by [repolex](https://repolex.ai)*
