# Repolex Knowledge Graph of chroma-core/chroma

RDF knowledge graph data for [chroma-core/chroma](https://github.com/chroma-core/chroma), parsed by [repolex](https://repolex.ai).

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
rlex download chroma-core/chroma
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd725c5cd3b2919dc733cca517ecb4062286cb16
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fd725c5cd3b2919dc733cca517ecb4062286cb16
│           └── chunk-001.nq.gz
└── blob
    ├── 0099ba152e5565cad6aeb8e9a4a58338fedc92e2.nq.gz
    ├── 019c07247b766f71520d84bcbbc703d5b9246e96.nq.gz
    ├── 01b49360b2498b98031995bbfca3627157fd20d8.nq.gz
    ├── 022a0836ff91f0a137f0bdaeb2cf370e54f18f99.nq.gz
    ├── 02a66f5b757493d879a54ffe228fd441fad00e88.nq.gz
    ├── 046347dd183d4be3c4b0eb4e1fdb7926e933af80.nq.gz
    ├── 04c97c5aac638485879b70d3f134658a4697bf33.nq.gz
    ├── 0503ce8984e350c0e80cfa91e9714ab0af74475e.nq.gz
    ├── 054107b639ff3b1799cc31cc9e3c0fa5f4858a5c.nq.gz
    ├── 0577bd343cc186be6930dedb28fd3dbaca49b811.nq.gz
    ├── 05e726d1b4201bc8c7716d2b058279676582e8c0.nq.gz
    ├── 06c742cf3919e74e3dcbcad1760f82b390e09f97.nq.gz
    ├── 06d83d9d84789ef3ce2d7e967d9eed4d2b3cae33.nq.gz
    ├── 06fd6373962517664b4e597fbc98da67d3adcf0d.nq.gz
    ├── 076b1e4b7ea3002a8f3b0e9aca1082e01b8912a6.nq.gz
    ├── 087326777aaa85bc61d3f9a76a77a031d35a8c75.nq.gz
    ├── 08c2bec8f2a5f1e1eaa80599a4ea849be07bd5d6.nq.gz
    ├── 08ef086a8ad81307f93b656ce4a605dc625deac7.nq.gz
    ├── 0af6002b5affeca26a36cbc43c99b4b1102abd43.nq.gz
    ├── 0b39a7baf8f09ab43329b5d979752311226f0cea.nq.gz
    ├── 0be81efd32e75dbc5cbda13ff6a4575abfd77dc4.nq.gz
    ├── 0c27137d8af59631569126d373f971138b724302.nq.gz
    ├── 0c8aac01c8c06fb8be8bcc49ec7d0a75729b2b9d.nq.gz
    ├── 0c9335c4ad58db89eb7879f8a8efca7d902bc118.nq.gz
    ├── 0d952957a7315cf3cc5aeaf5e35e59e9b7698147.nq.gz
    ├── 0e8a0eb36f4ca2c939201c0d54b5d82a1ea34778.nq.gz
    ├── 0e905d4802ddb96de6179495799be7cf9bdd4b76.nq.gz
    ├── 0ec77b5f893c8536ceb5ecda528473cf7ea3f907.nq.gz
    ├── 0f077f98ae58d23f37ec6fafd08ca0e39a0c0682.nq.gz
    ├── 0f16838cad2739ac7f215561e6bd00cad283a5b4.nq.gz
    ├── 0fbcc65f7c8795bd8fffb777133724a7ca348aee.nq.gz
    ├── 0fd3e87b95967f8ebed3ddc1425d7cc604e82581.nq.gz
    ├── 0ffa0e9fd64ddc6077a0568358dc84c7585a1c8c.nq.gz
    ├── 1029a04db0963fc1e6bcddfc428b5c89000df2d0.nq.gz
    ├── 10e9e1205bb6d31cb29cea89d62460ce6a1bee29.nq.gz
    ├── 13cf0f9c6c89c09d8985d8ca7bb486800a183431.nq.gz
    ├── 141f24058334496206f181ad4cbc9dc2ebb4ec46.nq.gz
    ├── 14bf06834255dada67107c2a9ceb512115a6a051.nq.gz
    ├── 151f99a9678e0e9279623bf7b12a42a2c25846f5.nq.gz
    ├── 15b391edb6eb56f7da7c4a7973b9f9165c002e21.nq.gz
    ├── 16926448e81a1e0254d37484fdf0d4adca05428c.nq.gz
    ├── 16c7c58c9b09cdd8ca90522a9560ecc24105779a.nq.gz
    ├── 16e71c9df6632ec7a234860c898ee6ef44b79117.nq.gz
    ├── 187c4274fe96b78087b2efa64f45535c20cf4bc1.nq.gz
    ├── 19180e21e698eb3c25ce5c655fccb218d27874ef.nq.gz
    ├── 1a45fb1af361701cc2f5eeab8bc44a3b0ee8c5e9.nq.gz
    ├── 1a5af2a330d156df03d58455a6aa9af533ae6477.nq.gz
    ├── 1a6690ffd6a94b4d6a4a4a7cb195fd644e47a66e.nq.gz
    ├── 1b64bcf94c46a71349b11dee2d4f13e8c49f24a0.nq.gz
    ├── 1b83653346250be3bf74b40f7a9e965466e1ba69.nq.gz
    ├── 1be3cf362d0afb44eadc36150ed34802cf6d40d7.nq.gz
    ├── 1c39c4181d7ab71217188a4778a634debc84b51a.nq.gz
    ├── 1c8504f0580997bbf713337ed2ab24552003f984.nq.gz
    ├── 1ca59c63596964bc37783c54d39b9236c640b823.nq.gz
    ├── 1ca7e8c85811316216c50e006e6e1cd981e79a86.nq.gz
    ├── 1d09e2dc6b6f70a5a2fc3320504b6d2d9d7a5ee5.nq.gz
    ├── 1d5f85cba83aa48eefe9160a548da33f5ab26d65.nq.gz
    ├── 1d9b9d9fb3f68d631daa67bb2b322b98592edfb0.nq.gz
    ├── 1dd54eea165fd51fdac045fe63e2f8abbca1c672.nq.gz
    ├── 1dfc6d65e9c39d5ca3492dcc27f267fb32909216.nq.gz
    ├── 1e5625c0e58737c1fff7a60d496cea2ac2a825c7.nq.gz
    ├── 21014be9c59e6ac64c52e1b8e8cd24085629ab8b.nq.gz
    ├── 21b97990c35cb5112a1fb48a8d4a9578fc325fe5.nq.gz
    ├── 21ea332fe7b50939bc88cc33bd07971e7ad79b7c.nq.gz
    ├── 22544f1948f02e645bdbb28f837602c95f9d280c.nq.gz
    ├── 226bd407a034c1f7a15abaa53e5b27c81c86a2ae.nq.gz
    ├── 23d809cf88beb635381677a32482586300ed2968.nq.gz
    ├── 24c68e8ecbfec1f6bb49d1e17c384fadfd5ce0a9.nq.gz
    ├── 25156659bb56e7b721df05cf1464e6f29af75209.nq.gz
    ├── 25281c88595d78f20630b068e782de8343f92af9.nq.gz
    ├── 25b6beca7a7e6f57deec88c98d85d84e0533e4d3.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 268c10007b61bf397ba2fabe242d56e11c94763f.nq.gz
    ├── 26ca0703c5b5f881826847f009801aaa075ec1a5.nq.gz
    ├── 2756c3b98c70fa2c3b2ae204635abf7ad355077a.nq.gz
    ├── 28aaa75fc2a312778fc0fdc009f1be2a99d30a30.nq.gz
    ├── 2a322099a0d4447c41f869a94865b7f9ee8a0df1.nq.gz
    ├── 2a999211289a415ed822c2842d8e2adabdf5b673.nq.gz
    ├── 2b1714cc4d73630efd3425ecba8c8f6571a4c206.nq.gz
    ├── 2c52e3931c65d48abfcce76d7915473eed60ee4f.nq.gz
    ├── 2c5a12cd0a32eb12cc85cdcea8635b503fbca10a.nq.gz
    ├── 2d87083daeafadfae12065b1abe27833d4beb48c.nq.gz
    ├── 2d894685300d15f754a87ebbcd71246acfc44a78.nq.gz
    ├── 2dc4fa261ae8be9234d0c9063cdf4d274c82b5fe.nq.gz
    ├── 2dd970ff58253fa9dc3908d3f7514cd63566f251.nq.gz
    ├── 2e7c5417425e40d4ac64e5bf8a28a3ce0b99f675.nq.gz
    ├── 305e502cb004ab943add38050c272debfaf5e1bb.nq.gz
    ├── 30bbdb7cfba9953fe84b7f2d3e0ba7bcae8d33df.nq.gz
    ├── 30dedff38494f025432ea0cf785d81c1bb556d80.nq.gz
    ├── 311148dc04948bdc95e8f59244902af0a97a551c.nq.gz
    ├── 31db429e842febfcf616ae78b5b00082146a3bdb.nq.gz
    ├── 32b05883e66913349932da03488938d19388ca79.nq.gz
    ├── 32ed84de48bb0f75cfc2bb3c09ed6d28dd8ace73.nq.gz
    ├── 330411fd7334c9a6535a30411a88baf4e2ca2536.nq.gz
    ├── 349064a25210bb489d30affb4a82c2e60bfdf430.nq.gz
    ├── 34a6c798351df9f2b6ab5e210f2f5fd0a90255d9.nq.gz
    ├── 35cab052bbbee4fd5237e0aa814e71d5ca3a0d8c.nq.gz
    ├── 361cdf4c77ec99a3f274be70ed3adaaf730c7e91.nq.gz
    ├── 36f84c02ab5332fe856db4a9312a365a32d96c0d.nq.gz
    ├── 36faec10e4d34a3eda32da890194540038f81553.nq.gz
    ├── 376234e4574d0e60613d5076c979df6995a6e60e.nq.gz
    ├── 3828532279c89fdf6640374d2b75db69d1dbadca.nq.gz
    ├── 38bb41fae188b2179e594ab1adb361c9443caad6.nq.gz
    ├── 38f1140dc24d9cfe856f2b921b2b8abc2f1332db.nq.gz
    ├── 38f37660976df6cf68ad76be3d826c1002c66496.nq.gz
    ├── 3b1b193ebe344c16449baa8de1762036a8b7f8f1.nq.gz
    ├── 3b5352afd3674807987b189ff59e275d574731b3.nq.gz
    ├── 3bba086b065ed2402d162aa8717210127f638d33.nq.gz
    ├── 3c668de90d2026f3f3564769314f0f49a2995bfa.nq.gz
    ├── 3dc776064220a403e21c504a5fa2d55d7cd4997a.nq.gz
    ├── 3e2ca24c927f424f5aaeba3facc19aa13673e53f.nq.gz
    ├── 3e508e805f6226e761acad1250b36f464620384e.nq.gz
    ├── 3e91dfbef761d8aaacf854daeb3178cf8ba8a3fa.nq.gz
    ├── 3e987e5bce3d899aed2459fe5f0cfbe1f99a0376.nq.gz
    ├── 3ed0e02842340df9fa9e0158f21300f739012edd.nq.gz
    ├── 3f2b89f2bd54f4808426374ca4037e6a23cf2ab3.nq.gz
    ├── 3fe1cb6af193080f5864c34d7dcb61d0a64230fe.nq.gz
    ├── 3ffcb37f0c1530c7103b4c2a6f30c114f5276e09.nq.gz
    ├── 4084121cd6e81416ccd8c75ee988e522d06ebd24.nq.gz
    ├── 40870b52bac96855bf1610f6901ded6fe811a0e9.nq.gz
    ├── 40d086a1031c11c0f9a11705829c389949393426.nq.gz
    ├── 40f430e6edecb4d0e0eb3927e47df04390125f33.nq.gz
    ├── 411d8f0835b9291492500f433b1975b9acf60c4e.nq.gz
    ├── 41b879e538be0202eef340198a42a7b790ada4a0.nq.gz
    ├── 42fd7817dfb0ecf9d178d46424294302dcf3b886.nq.gz
    ├── 43372bf97a8f13939189e081a1c851d23fd5c1f1.nq.gz
    ├── 43595a54f9b8a0fa4ff6ef2a1139cdca1f896fa5.nq.gz
    ├── 44e9038ed4a44fdedae3a1121c1ce695af098826.nq.gz
    ├── 45016a928b890cb58eba438b036043435c34bcf0.nq.gz
    ├── 450941f80fa3edc27ffb8f4376a891381e937f3d.nq.gz
    ├── 4524d549f8416881ca6d8c6b6b2f0b487d1facf0.nq.gz
    ├── 45ee743a48a4099201f79c22d68143170876f2fb.nq.gz
    ├── 45fbfd90b972823e2d06aaa1738f964bb6499f7c.nq.gz
    ├── 46113da79217e93b4bc0040ceecc2b36ba5a12c3.nq.gz
    ├── 46cbb7c6e6d85f7a0ca7777b5dfb0ce4de645cdd.nq.gz
    ├── 46cc8990bde409b3082b24eab575c1d84f854f08.nq.gz
    ├── 4733e261ffcb93921132d41ced01a9c12fe93f4e.nq.gz
    ├── 47b1c370f1f5afae484d588a0ca8c74b57668ac4.nq.gz
    ├── 493e99758bfc952d5d7039433b8d3fd1d2164e3c.nq.gz
    ├── 4a46ef2f4b22137e12a4e172d4c8906907918947.nq.gz
    ├── 4bc3f62e6a9a0ffd1ad88a98426c805160cbaf1a.nq.gz
    ├── 4bca123a5bb76735bfc29be143b7aaa3e46232a1.nq.gz
    ├── 4bfa8767a7cfc48186069ea22f915cd373d1c5e1.nq.gz
    ├── 4cc7a371085a3b04e35780db21684e644d12355c.nq.gz
    ├── 4d8ac1de3f28a95e3857e5bd5d16d1c9a78551ec.nq.gz
    ├── 4f07b234ae93c26618a398c7cc1add0882a82b87.nq.gz
    ├── 50244db5d986962815e272aa36e7f338928c2914.nq.gz
    ├── 505e390243daefbc98a6ef4b432b8a98b4f5c513.nq.gz
    ├── 506e57055fe667cca2ec63dea3879d8e29a9833f.nq.gz
    ├── 512ae65fa912109968ac72f92df3f942c2d285e5.nq.gz
    ├── 5131fc0daeef1abb5c599804a53bbb1cd95a8632.nq.gz
    ├── 527278dfa379388b7f4dc43831de01d75b83f924.nq.gz
    ├── 52a01fe1ee9b4424b8a16647b7cdb2c6531ff7d9.nq.gz
    ├── 538193b5926b2b20ebe313e370f17b146042e9cb.nq.gz
    ├── 538560861a602b89aa02c2de54e87c005350237f.nq.gz
    ├── 53e9b2c55057eb746ac06d2ca78e1cb964fcf7de.nq.gz
    ├── 53f5c702c0648449c3916ed2d15f5cd6aff1cfd2.nq.gz
    ├── 543a14bc534e289bd1ce558cfb938a27d5643e93.nq.gz
    ├── 55b996d784c32941f3cfac868e9dc26732816a28.nq.gz
    ├── 56f49fc15e2570e7a4296c1205e2462686c730b5.nq.gz
    ├── 579f8c55ad62297e709bd16faa73ee61fab8d8e4.nq.gz
    ├── 57da3597733de69ff405855316f025e5521ee680.nq.gz
    ├── 58245a91171b5d4045adbefeed61799326d1ce92.nq.gz
    ├── 584947a6c71b90603241a011b656ed3c0e39be17.nq.gz
    ├── 584fb2b41c27417f95abbefb4aa93e5c8efd1e61.nq.gz
    ├── 58a4d3e7d85dd94c3c608544b8ad4a67b4bca7c3.nq.gz
    ├── 58efaa00eb9d03e3c716115fff9cf8644c8419c4.nq.gz
    ├── 599092aafb901fd587f9002f0a2af8ef7312b844.nq.gz
    ├── 5a3e44279da34271d26b730ff841e0a9b3eefc4d.nq.gz
    ├── 5a84cd23f54dd18d50739a7d5ba4aaf164dee802.nq.gz
    ├── 5b4160e20c21b100af05430763aaaf80c7d95220.nq.gz
    ├── 5bb0e7299c5e9b140b04c54b1447c5168f196ef7.nq.gz
    ├── 5bb857faca9c2975b694dd31b5a2842a3ea53a8c.nq.gz
    ├── 5c264edb2222086c081c4b2d5d95becb77d5681c.nq.gz
    ├── 5c4f117b4fcdc709a2b6e44bfee224a6ae0404f6.nq.gz
    ├── 5cd7d08c7f07f993db4de31b86027caf4f638bfd.nq.gz
    ├── 5cf6cf08fbda723d46c9720a9277b1df0892b200.nq.gz
    ├── 5e44ddc26bba08f3849748b0bdd8ae6e146e5eef.nq.gz
    ├── 5f3f8029d89042c8593d7dc5618273d2305984e7.nq.gz
    ├── 5f71243ad50bcc5e361590cf2daea53dd0e73926.nq.gz
    ├── 6107ce9fca3639d63ccd1b404827afb10d6d09d7.nq.gz
    ├── 614b4141e0c06954887a0525c7b737b4ac33de94.nq.gz
    ├── 61c35f0552bec61532aa5ef6a8c4c369fa49f358.nq.gz
    ├── 61d7978b525afce89211d1c12c1fe9dc365d9707.nq.gz
    ├── 61f7c91ab234149a3cd65191cf0a7fbfdfbc5994.nq.gz
    ├── 61fe7f507e7d53df64c41938286437130e86a0c4.nq.gz
    ├── 626899e36d9eb0c787ed8d5baf956a2dc1e16576.nq.gz
    ├── 6271ccb37e893e37a0c2b662c7cc4f12a2d7d906.nq.gz
    ├── 632181ae9e78d866c7cfecc8b91bfd56911510ca.nq.gz
    ├── 6334b8774250d53143c4f52bbb3c37a61d5c36ad.nq.gz
    ├── 64a7a0c84f49c2f19179d39015984ea5f78b1cde.nq.gz
    ├── 64dca60243614a2fbe5d01160c3f0f1ebd9766da.nq.gz
    ├── 64f01e4869b73d9c7d42e94b40994f1ebe456c93.nq.gz
    ├── 6619df468e0c05a8013eadc8d2e0bb4598003403.nq.gz
    ├── 661d0756f2ea0875fcfc21cb16f94818c25ffb1b.nq.gz
    ├── 668b3821094be00f537ae253658d1e8271d30676.nq.gz
    ├── 66af698513b5d17825e114e99b0db77fb12ac37b.nq.gz
    └── 67004080c0f33fb607d2b337a3a9802c5eaf3249.nq.gz

7 directories, 200 files
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

[chroma-core/chroma](https://github.com/chroma-core/chroma)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
