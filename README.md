# Repolex Knowledge Graph of huggingface/optimum

RDF knowledge graph data for [huggingface/optimum](https://github.com/huggingface/optimum), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/optimum
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0df84f23884f7c5b6cc76c0bdc9597edd306034f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0df84f23884f7c5b6cc76c0bdc9597edd306034f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0087ac0dea8ebc55e89f44fc83ff021affd9586b.nq.gz
│   ├── 00edb5036addd8cb4152a79e3dd1e21a2f71456e.nq.gz
│   ├── 0426d1a2b43ec997d935f28075be53c59900920b.nq.gz
│   ├── 127e6676cd7fea9814cf993f70f45a63a9d503e4.nq.gz
│   ├── 1592868ba0dd25260cf7c5024430cfc6e3e63d70.nq.gz
│   ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
│   ├── 1614a32fa8f2ebbf384a3df0b6002305acc8f3b6.nq.gz
│   ├── 167aef30b10b0e08a4c7c84ca5ada83aaf1dab72.nq.gz
│   ├── 1ae8a552b14ab05cdabaa5e0031b199aea56b966.nq.gz
│   ├── 1c25f787d70f83671d4a71cf96e24c35541b91b1.nq.gz
│   ├── 1e0a647c1b533632547fc7407ef42ea7c51523e1.nq.gz
│   ├── 1ffa21de255fa618e276dd635e36277f1ad0bc57.nq.gz
│   ├── 23609e692f57e5d3f39a5199310ed53aed8cfcc4.nq.gz
│   ├── 24310feeac6329228269ddba2a9e55d270b4f42b.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26522affe148f678ce7f0af5ea71d33252e4dc63.nq.gz
│   ├── 2969c616e6121a895d359a4e5417b67b1eeb5a65.nq.gz
│   ├── 29a2600799eef22067edcc2242784d8f74ec54b3.nq.gz
│   ├── 2a5bc7ab1d3a56da92058f9de224b2c17c35f160.nq.gz
│   ├── 2bb5222fe34c91f564b4f8c88a84e84f357bfd5c.nq.gz
│   ├── 309a9dde848be73342e47f01c337c8718570c370.nq.gz
│   ├── 319613935ecfaef6d19562464d88fd3e452c5475.nq.gz
│   ├── 34ff8b160dc75a3520b35186f3685c08e84494b9.nq.gz
│   ├── 350ef09be7f1d8b7dca6b88202571fdb5349954f.nq.gz
│   ├── 37340136691921b506e04dd433df9d523391fd47.nq.gz
│   ├── 3998192378af528ae96a2e11fa481ada0fd219d7.nq.gz
│   ├── 3aaa7fe6c697b5c9ad20c3a74a6d0b14fc00c30a.nq.gz
│   ├── 3acbd959268496d73e0324a8968d565b896935e6.nq.gz
│   ├── 422bb55d92ea14c40015c4085d1b24af967a370c.nq.gz
│   ├── 474ae7f7eefdaeae29ad9baea6542137b8c76ed6.nq.gz
│   ├── 47d50b57a38e2ce6d69d936ee5e7c2b48ca73f41.nq.gz
│   ├── 4aa6887b9903086a1271b58372613844ecce0d59.nq.gz
│   ├── 4cb23fc9da4f627fdf5955be58b9e98d44a4c69e.nq.gz
│   ├── 4cc355ab5022bda55e1e4f393ce0dddc36edc863.nq.gz
│   ├── 4dae5262d5a0282544e3d8e4ca1a3ec8c19f007d.nq.gz
│   ├── 4e9d73a366ab91dfb77c5c103b0661ed6a9caa8b.nq.gz
│   ├── 4f4e10b8cb76476bbee518c213e74332b9475a07.nq.gz
│   ├── 4f856451fba1d9797f67a29ca2b86501d7d7401d.nq.gz
│   ├── 4f9666cd14689f61693eb6abc3b7e76b809ea149.nq.gz
│   ├── 4fb08fd17d9d39e64e8b22f381d0f6fcf2b8d684.nq.gz
│   ├── 521dde8be835ea5b3495b36a81e44da720184cdb.nq.gz
│   ├── 5284383f7c9f17bdb10b033a731315903c58bdd4.nq.gz
│   ├── 52d44b5a148f96cfeaeb3df83e76cb20d0346929.nq.gz
│   ├── 571248c2d454e66ecc731129b08bb835f5711573.nq.gz
│   ├── 5a3a3188c73320c39cf90152f27fc37d72d1c34e.nq.gz
│   ├── 5c60828b71b51b3bf056a62ceee0ebca66418239.nq.gz
│   ├── 5ffbf861c4b616a4d9212ae1c30a0770b9cfe986.nq.gz
│   ├── 62a4cff11b67336806ae846d2aefafea984b614e.nq.gz
│   ├── 62d5894dacfde9e9877d5b2d1b5c697a031fba4a.nq.gz
│   ├── 6362d66db3168cf0c8f96425a936d19cfeb530eb.nq.gz
│   ├── 6434b74b8e4245d3d1c016a4a52d0104e5eb1f8b.nq.gz
│   ├── 683a87e069711c53416de1b91c22439a2c126bfb.nq.gz
│   ├── 688fba5d4114f1b930570319cd90508afbc9bfe4.nq.gz
│   ├── 6a7cfa84ae160e083facd2d67a0ffb7464e34f47.nq.gz
│   ├── 6c136479905c8052b312a4addd4406eb5180a8dd.nq.gz
│   ├── 6c92d367aa48f0b4f391b6490b09b72c7ef8b419.nq.gz
│   ├── 6d8c708d506bdff51f09a4a27db281c8d5db3db9.nq.gz
│   ├── 6f8d8ecb5a974513632f8dda01dd3309c2a4b760.nq.gz
│   ├── 701badd4d59edb0affe2f75ef4fdf7572f02c40b.nq.gz
│   ├── 70d2ee1dcbf1c897ac3d969cf361aeeaeee541a9.nq.gz
│   ├── 71de5663c79012f114db9ef480bfc0ef6688cb6a.nq.gz
│   ├── 72aaf0123cf3fe0dda7bafae1c207823bfe2750e.nq.gz
│   ├── 74ee549f8e498e7f0511553a715fbf806c047bc0.nq.gz
│   ├── 77c4fd62a5e22a9380fa100818c31e5227e76b45.nq.gz
│   ├── 7991c7cee6e09c00b898241cc2bfac607a094505.nq.gz
│   ├── 7b290ad2d956a4f32af45e047c1d26347f3e61f8.nq.gz
│   ├── 7d6d99d69d6b245b20b2af0dd980193c4e5deedc.nq.gz
│   ├── 80d36b67d270f0deac627cca9ea22c2a3733d0a7.nq.gz
│   ├── 84acccf80b9d0a2e8d8224128fec3afd90979091.nq.gz
│   ├── 8694e16f749c1c8d47d615d46c69b600e9025186.nq.gz
│   ├── 88dea2859325b95f45d73e76ec5389cfcc30f8ca.nq.gz
│   ├── 8911d1a13cd9d75d3faf96945daf28c25687a3cf.nq.gz
│   ├── 8a01c74c2784270b907c29b584a5fcf16386ea3d.nq.gz
│   ├── 8e22051013f2cb19ec94e2591402ff51d8636199.nq.gz
│   ├── 8e4d32514cc6b417be14dee4a6f78129494d7b8b.nq.gz
│   ├── 8eb73f181c97fa92876083730da6beefae9dc3d0.nq.gz
│   ├── 8f8df0f7bd07b125a264fcccf91544411d841566.nq.gz
│   ├── 9185fd8b68f89c1a1edb1d69fa579871c3171309.nq.gz
│   ├── 92b509454ba4ab40b1e237ed03854dc9329087d8.nq.gz
│   ├── 958f91ec385cbb0d9285e8145ea9b07e714d3068.nq.gz
│   ├── 9937089844ac1c9d41b08a2867a0c7dca880f7ef.nq.gz
│   ├── 9a0c27bfd5e4a7d2e94b9162f2466ee7242e337c.nq.gz
│   ├── 9f5ffc45c444b65db58d8d49d9c9c3ca89c8eb36.nq.gz
│   ├── a1710eb26b00541b989d697873e80f10ca3b2877.nq.gz
│   ├── a2e7f3732df8626f6dba29af59509536c3ef5932.nq.gz
│   ├── a857718c622e353abec4d127a7545d25829fe420.nq.gz
│   ├── a923892e63064952363fb21b1d0d91e011938ccd.nq.gz
│   ├── aa0d78581deb40d76dcc45ac6380e1b6e38ef0fe.nq.gz
│   ├── af5e586afdd326e9dafd934a92689b00ef40a807.nq.gz
│   ├── b006096a82d364b5d2d4cb1f6d8f626599ecde6c.nq.gz
│   ├── bb9077e3a9fe115f3c119fe5f36149a80bac3576.nq.gz
│   ├── bcf6d6e6e6a697ec84a7edd9a61c0d4e8050ff7c.nq.gz
│   ├── c0de90e8e6426b84e77ca9f8f757c2ca71ff8c28.nq.gz
│   ├── c1fffbd8ecf11ed9a0858078feab19993f10b2fa.nq.gz
│   ├── c4b2f44efe876f61d63ba4c5e5373e7f1dab57db.nq.gz
│   ├── c5cca71ca096757adb5d552c57364d28dea2c4f3.nq.gz
│   ├── c7d22bee9c50d3cc0e847bec876ab88294f4df62.nq.gz
│   ├── c8cf94944d64db2917cd20dbe741de8a479d66f5.nq.gz
│   ├── c9319e4a4051cb306d385de4c17ab01f0b3b92f7.nq.gz
│   ├── c9976ec3fd7fc428b4df441b07f23809b7b2392a.nq.gz
│   ├── cbf6aad66923cd64a2b06a2bd94a8e91f47bb1c1.nq.gz
│   ├── d323083f0dcabec87f2455805b5f88454d9b79b1.nq.gz
│   ├── d42b0d82a5eeb8321d9eae78b34bd46b38b09fa6.nq.gz
│   ├── d4751b9ff015115519b54f7f905c436a19d9fd09.nq.gz
│   ├── d61bbf51b10911ba541ad7b1133bb0e2279d5d79.nq.gz
│   ├── dae5b5d633a1f8f7f0ef6b9a908a56bb972af73f.nq.gz
│   ├── dcb42f083621c0bd930e20230244eacdef4a553c.nq.gz
│   ├── dd59c89ab5cc6161c46a9ebf0714a6ec2f9a56b3.nq.gz
│   ├── e176ffaf8e639e2c41351223e65626a74b0e343c.nq.gz
│   ├── e1d61206284e2367a6f200f9261fd9a5f77a287a.nq.gz
│   ├── e32b305fa309cb9c14f26ca9f41118d70fbcb41a.nq.gz
│   ├── e37691220917562e44b2268181a4f30050a94aa5.nq.gz
│   ├── e468882c46cc629861f78ce1fa77098a9204f874.nq.gz
│   ├── e6fdf0b6773266e602eadea7c6e1edb220c363d3.nq.gz
│   ├── e7467eb7bd466a3d11b3bfa4b0888052c2c05b5a.nq.gz
│   ├── eb8cc9b2942a4d66f8975d13e99be4b6d6c5dc34.nq.gz
│   ├── ef35fb33d063775a1af5545e34bc90fe9ca2dd9b.nq.gz
│   ├── f1dd1f6f8f68dc8a62f7a0d52a5740f20d0ebc52.nq.gz
│   ├── f3d67defdd8c1aa3ca00f7560e80be653d721a42.nq.gz
│   ├── f429aba994c0842b1145869426005f32708b3c47.nq.gz
│   ├── f78583c27d5dd96fba5dae2cf9e87e29bf782307.nq.gz
│   ├── f8f996aa8e991fae072d7cb33a477cd8ccb54049.nq.gz
│   ├── f91e1ea2afd1f792f3fcc09acf254f4fb5e2c669.nq.gz
│   ├── fab0d72ba0276ad1e41424b6fd503b3144f0c13f.nq.gz
│   └── fe64a2303a69576fd8936ef0b9e1670b45f05fb8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0df84f23884f7c5b6cc76c0bdc9597edd306034f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 133 files
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

[huggingface/optimum](https://github.com/huggingface/optimum)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
