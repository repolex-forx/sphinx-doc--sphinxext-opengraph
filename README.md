# Repolex Knowledge Graph of sphinx-doc/sphinxext-opengraph

RDF knowledge graph data for [sphinx-doc/sphinxext-opengraph](https://github.com/sphinx-doc/sphinxext-opengraph), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-doc/sphinxext-opengraph
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 95cf8a8c30c301343f8347c5d72a97030e007f34
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 95cf8a8c30c301343f8347c5d72a97030e007f34
│           └── chunk-001.nq.gz
├── blob
│   ├── 0164b3dd26c32e1b7b3e31819457d07673e2578d.nq.gz
│   ├── 01788274892ebf5bf33069fc29979584b913f7f5.nq.gz
│   ├── 02d67bf582ee5405853bb92527876357133c4eec.nq.gz
│   ├── 0d013bf97ce311399da0eb81534a66694d654e09.nq.gz
│   ├── 11c84011559ec00b28af845490fca71b8b45e40b.nq.gz
│   ├── 12be2c2ea1ad9b008ce925a308822a2239a6fbdd.nq.gz
│   ├── 1475e0a98053b7dc3fe308496772fea28d39f7b9.nq.gz
│   ├── 19c6aa49a67b480a13344ac58cccf88fc4b03c82.nq.gz
│   ├── 19dd97598972dd499638641f798902b1dc631d1f.nq.gz
│   ├── 19f55831837576686cafcc490dd62abaa814b4f9.nq.gz
│   ├── 1b8372b260d1bcce17e91cf8043ab6f581010103.nq.gz
│   ├── 200d0503ef3015872fe57390e0cbaa9ef642d714.nq.gz
│   ├── 2376c2c65158830ab3fb5ad819dbe01ffb27868c.nq.gz
│   ├── 2483fcdb5258b05408021b5d6a0b62949bddc859.nq.gz
│   ├── 2bd3512713071205575bc4e01eb18f1127f2c755.nq.gz
│   ├── 2e8bec9cee077ea3bab477bd6d141fecb397ddca.nq.gz
│   ├── 315e34197ed6a370b3ea6838b503766f710c3aeb.nq.gz
│   ├── 325020e7e5222f2aadb480e5db3ca5fdbdd4aa16.nq.gz
│   ├── 34108cf22325aa87b9e53a908ae6c920e0b6080b.nq.gz
│   ├── 3868bc87e9a38485cb31d6bfe1a1290e1daa27dd.nq.gz
│   ├── 41467c31b5943dea71d26ddbbb6841f8902b0b89.nq.gz
│   ├── 414a72f51a127ddfd183e674fcb8e4f9d1ca5483.nq.gz
│   ├── 4572e5aaea21afcb2d889e2315538929bd2c6077.nq.gz
│   ├── 4ab4b86b611d267924aad407e58a4364321a5799.nq.gz
│   ├── 4c45ca5fa7c633fcebf8d23373ceadd0e3aee781.nq.gz
│   ├── 4f7058ddccc07a5614d33e1866f8d0b5ce9e6c95.nq.gz
│   ├── 54b7be1dddb677d79929e2791f03967398d63af4.nq.gz
│   ├── 58c1f39db83ab5197bc7ad278a24263ba365cdf5.nq.gz
│   ├── 5ac3a3fe2af270b5a90ed60f9a5a7ac59eb12221.nq.gz
│   ├── 634fe79194f8958a69e1934c3b1e6a5bfa489622.nq.gz
│   ├── 64023d386b33e666e3713a0b46fa6ea6caadee16.nq.gz
│   ├── 66a67ab15d970d4618e9a51697ccbf83e46646e3.nq.gz
│   ├── 6a43ab1033a64d66dbbcf1024962aa0fd18eb697.nq.gz
│   ├── 6c1f2a6b967f679fe4dbe4ed6a9ed19527cdee49.nq.gz
│   ├── 6c838c27833a8e0446ad1268ff7e21934837fcde.nq.gz
│   ├── 6da03d9bb4bef765ebffbfb78d7623b6e763489f.nq.gz
│   ├── 71b595744c18226485a09252195d34ede63fd494.nq.gz
│   ├── 7511bdca682e62249e7f56d157bae9b10ec6901f.nq.gz
│   ├── 7f018e6fd5b3555870d320a274aa9e340cf2149a.nq.gz
│   ├── 82fdc83979f431822e2d5ea3ec6adaa6e0dbc960.nq.gz
│   ├── 9534b018135ed7d5caed6298980c55e8b1d2ec82.nq.gz
│   ├── 956cc69cd48fd8723f0b6d32f1a12ca06881f560.nq.gz
│   ├── 9b593af670f4c28e82ef45814415b5f9aa5263d2.nq.gz
│   ├── 9d43e505f7410d1c527a135799bb43893be07137.nq.gz
│   ├── a032a90bab2e318b22c2ac3fe24d0b674213180c.nq.gz
│   ├── a33871d3ce1c6ed69a300618d1632865915cbcd3.nq.gz
│   ├── a6ea7bf98b0a301af08664ab64c06004bc70cce7.nq.gz
│   ├── aac2e9a180a577634434da110444bf5ba2dcd53c.nq.gz
│   ├── aee4444c44a5221f689bf2cb2f84ca8771bd7e5b.nq.gz
│   ├── b4bdde6338dc2e009b183f097c7d5949d67ed805.nq.gz
│   ├── b70f8c871af195260921963904d00d75c19ec8a6.nq.gz
│   ├── b9112fbb2d27d759d6297580978699bf3099798e.nq.gz
│   ├── b9eb77f8e0fa2ac72d8ecc3ed34f27d5b1ce5cf3.nq.gz
│   ├── bc5bb2ca106d30c73c086f7cf05f1c74f7cbb4a3.nq.gz
│   ├── bd32e0d753443cd65062721f271861b4debfefc6.nq.gz
│   ├── c75ed6cf745ced01370d43c61fa7baaba17106f4.nq.gz
│   ├── c7804354bfb38e8266e50191bb8299421882b713.nq.gz
│   ├── c83e8b1af1719f01a47cbfe3bdd238d895227d3a.nq.gz
│   ├── cf1aaf762bd97f32a2dff2c82d031914dc2b0716.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d19d0afcde812bf7441bb0470f03c8cbfa54d181.nq.gz
│   ├── d40a353473954b86233e3a4f725dac5414c895b8.nq.gz
│   ├── da9bc41c9952c887855297b8cec359de3e997937.nq.gz
│   ├── dfa6705122ee017ea7342132b7350236708942e2.nq.gz
│   ├── e3516fd8e5ef1be7daa50d13afa721d25f2488cd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee6f9ac6b2c975bb79dce16bf058077a85472b74.nq.gz
│   ├── efec434c5b336a48688648b6288fef2d539d5b8f.nq.gz
│   ├── f1fc1828fc89680ea7d21d684adea2bb83850b78.nq.gz
│   └── fbe7b89577d61265b076ede1a59e9bd47e99af64.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 95cf8a8c30c301343f8347c5d72a97030e007f34.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[sphinx-doc/sphinxext-opengraph](https://github.com/sphinx-doc/sphinxext-opengraph)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
