# Repolex Knowledge Graph of beetbox/beets

RDF knowledge graph data for [beetbox/beets](https://github.com/beetbox/beets), parsed by [repolex](https://repolex.ai).

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
rlex download beetbox/beets
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 18967aad9d36ca29fe2a370c3eca9beae3b46749
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 18967aad9d36ca29fe2a370c3eca9beae3b46749
│           └── chunk-001.nq.gz
└── blob
    ├── 001c2768c660ee0db89081e6f90e110008295677.nq.gz
    ├── 007cfe494edbf25be266eeaac9eb660733f91279.nq.gz
    ├── 0104d8d6d624625583ff5ad5f9a58db298ab2648.nq.gz
    ├── 0109940138664cab17141cfb0311904213a1cdbf.nq.gz
    ├── 022be19ba82d89481a963e83c2844a6dcf5307f9.nq.gz
    ├── 02e368dc188af4ced013088e6f1c75e443d1f856.nq.gz
    ├── 03d7d5b24e15f05be1456d96de01743e34a8d88b.nq.gz
    ├── 0416b9596ed46cf55bd5ee97e21ca091d6f398f5.nq.gz
    ├── 04559588e42b4fa50d57672ef7aeda12878b59f6.nq.gz
    ├── 0600d09d0dbc105c794486883bfb5fa9d69c3168.nq.gz
    ├── 0695e9ff844466bd895a93ae8dbb6d68c317e122.nq.gz
    ├── 07909a62dfbe48dc5855c4bb23be03526c177b8d.nq.gz
    ├── 0834828488b4c974a00a8547adeebe6740693872.nq.gz
    ├── 083c6c2e0fe5d54c52ab1e0f049a04426bd5a51d.nq.gz
    ├── 08724d514f2fbe56e3c0791fc0e4e6f56184419f.nq.gz
    ├── 08cd1c186441329aec907354b74b6f7df46ad44e.nq.gz
    ├── 098aef17ea2082649a34b4d1ed52b4a5986a47c7.nq.gz
    ├── 09ade3edd3d35ab1acd5177a7626bd3778d0f45c.nq.gz
    ├── 0ace5b89bf4e1dba5db123cdc58193c22c2d5d71.nq.gz
    ├── 0b92a7f1e4e33f8b7a614b5bcd9200bf9c79434b.nq.gz
    ├── 0cb70bc15fb945dad9c631c23ab0924371ba3824.nq.gz
    ├── 0d3a310e7d6b31d2a4fedef0d3af4a619211a464.nq.gz
    ├── 0dc4f0c5e8cbd4a08f88f0ae646d91632a7d591e.nq.gz
    ├── 10689987532f6ddf34069d204507921e04b5da43.nq.gz
    ├── 119d2d137dcd98d17e364af0a3ac9c8546e7135e.nq.gz
    ├── 12678a4d9ff6f46790b3c37a1c0496562085d763.nq.gz
    ├── 128f95ce64e5be26976fa685b48d7197dc57ec77.nq.gz
    ├── 135bf6a86891d18b6ec09bef073662e59ef5975d.nq.gz
    ├── 13856e094a1ebe5e7be39bc2598c6df72dbca9af.nq.gz
    ├── 138965b22535b088b1105db6e9e46ea9cabd9215.nq.gz
    ├── 138c0e599f94c10fca0e14c2e3f8d7191d4b2f45.nq.gz
    ├── 13b459ec79c290a75f6bf21af4cb4b08891ab505.nq.gz
    ├── 14556fcfbca36c4392ad92b83a4101d94c98ed05.nq.gz
    ├── 14892ec18c7187a438bbebafe32574fad4d122e0.nq.gz
    ├── 150ab0bad874507f6f74beb5659982758fc6b4e0.nq.gz
    ├── 151e381db9acc33f9142291d90c5c9edf16ddf95.nq.gz
    ├── 15e1304990c35852758c450ad45fc512a15352b1.nq.gz
    ├── 160ce25660c0722cc24bdeff9dd3ce86ee4d4432.nq.gz
    ├── 1648d070a380838f2355226a100f5c61bfa35247.nq.gz
    ├── 1673c9d54609839a9bfd3b52f5a9b11a9b19ed1f.nq.gz
    ├── 1698bbe66ea1a48e2d652915b0250da5fa661137.nq.gz
    ├── 16da2f483e79dfca7267a0801c22132f3a97835f.nq.gz
    ├── 1826f136a90f1fb755a3843f994fca1ca1feaa88.nq.gz
    ├── 184f7d57f24b4a07491c4bd3941709245ee3bf24.nq.gz
    ├── 1904c6799ff28100339bdf673605c03424ff91ba.nq.gz
    ├── 19f8a28e9ca4fa89efdd9775e1e6c20a8b085c1b.nq.gz
    ├── 1a89c9a993da2323ec68052932737134344d5e3a.nq.gz
    ├── 1b5d9857c8d43b3f9882e772406209f814619fbc.nq.gz
    ├── 1c1275543575b508b3f032e42ff562f0ccbacedf.nq.gz
    ├── 1cc11693ea9b5f1ebaa0801106a4116f9cb71ba6.nq.gz
    ├── 1dd023231475ec46ce79445184fb22d7d91e48ef.nq.gz
    ├── 1f041cc9dcd2e7ac8fd11f4377c2e42bcf2cf32e.nq.gz
    ├── 1f043665979e75712144c49a53064699a7d39761.nq.gz
    ├── 1fc37dd2e10d689a36c3ecbcd4e35b457be46679.nq.gz
    ├── 20aa42782a5aec8710666d7c7716eca45a6332ea.nq.gz
    ├── 20bc38b0fd4cc279c0e43b078896957df0914d2c.nq.gz
    ├── 2158978f3e0e5543727650324f4ecc4ac165bae5.nq.gz
    ├── 217c95781b4f9b775da0bed141ff5796e2c031e8.nq.gz
    ├── 21835ca3d55c0cfb70d5c606ba20d9d07d7486fe.nq.gz
    ├── 21b774120537e29ed54eec6add78cb06b2e62498.nq.gz
    ├── 21e826d0eac0276f5cbc67fde3830dd5ffc0ac06.nq.gz
    ├── 229bfa01e7ea6686371d1b93b2b3fa7bc6e25855.nq.gz
    ├── 238706eee6117ad7aa52d8cb5cc90525a6650afd.nq.gz
    ├── 23c594d0914f6720731961c5b79202e7498dc574.nq.gz
    ├── 242bb63985faacfba2028bc184513d8ba60f1152.nq.gz
    ├── 243c03740c74a58f87f90690b17355f49c652c67.nq.gz
    ├── 24b92de79412b267860f43330b7b06f4388e3479.nq.gz
    ├── 251d88c9d140a21c2ed1f43996e36308ba9d21a3.nq.gz
    ├── 25a84bf84e74872e362c4b0d87f82b3e42f99877.nq.gz
    ├── 26f4d3eca120223ba79ab4dea8972c9cccea41c8.nq.gz
    ├── 272b64103752b0c399edfb788271539411e4e7d3.nq.gz
    ├── 274455fc7ab77e797d46f73649ab72a2d1fea03a.nq.gz
    ├── 276b069e3d12934a8a55b476b0450b1d8c74854a.nq.gz
    ├── 2778c9fba4ac79fd58ddaa0b121dc77635f3354b.nq.gz
    ├── 27f39a8d75db1d23f884c09502594a4105938890.nq.gz
    ├── 288f4b0e413eee9e4dc5898c0514823a91dfbd63.nq.gz
    ├── 29231410123603c1cb2ba8bb7af449161b15277a.nq.gz
    ├── 29708350861fad00c59b54e3f05eedfbaaddf8b8.nq.gz
    ├── 29720b92230951efff618eefe046df6e6c17720d.nq.gz
    ├── 29f5de5310f799d5f17514d280f32d4cab82f9cd.nq.gz
    ├── 2aca3b5fd77d3c8cbc3232e1bec4d44e44013175.nq.gz
    ├── 2b306cc13e8cdf9592b1b5a6f45c4201c2dd3861.nq.gz
    ├── 2b69aa49cdfdf2cdd85ec16a1ec7b89f2cc9be11.nq.gz
    ├── 2baf086fd1b37cfca08e8b8fec4b299d7ae1ceb4.nq.gz
    ├── 2ca7fc8345a403b8da381c4719a9f66f56b98d4f.nq.gz
    ├── 2dcf97b5d8d4a3658da0fe8445309745867ac9d1.nq.gz
    ├── 2dd05a25f36fdb36175afc0fa4f8b19fcfa356b5.nq.gz
    ├── 2e4f6e03b2306ec2fc31d9e06d7d281d3a66d715.nq.gz
    ├── 2ec831e328c8dec15994a9e0a2daa7944958c973.nq.gz
    ├── 2f3dbe0416f28e9a188a9535bba3af6fdd15027c.nq.gz
    ├── 2fb362c2fe05ee4ab33a5b05a2776c22e6554eb3.nq.gz
    ├── 31b9850ad60c038e077783c575b74dc3521cccf0.nq.gz
    ├── 31d2bf64f15fd95abf85f67139d6d987366a89e5.nq.gz
    ├── 3259e9279c3c6fe7d3bc5b6707b781f831891f43.nq.gz
    ├── 329e2b1ebe5fd5253ccad5a0acac3ee2704c74aa.nq.gz
    ├── 332ee72ee403195f314ce98e1901d7a45a215068.nq.gz
    ├── 338597d39f44562115541622b0dd7abb62063934.nq.gz
    ├── 3522ae8416e8898c5d0c5fb74bb1c79c436bd94f.nq.gz
    ├── 365af66ddfa6803dde56218aa0537285bcc5029f.nq.gz
    ├── 365dd1db05ad0ce4e775f362c07affcce4deb70a.nq.gz
    ├── 367ffeeafd68d839d03aba713c64a93606e8fcee.nq.gz
    ├── 37b84c57e3b37f336a9aed95c833dad1726e9057.nq.gz
    ├── 380d8999670ec4cd818d86a7dafa15bfc889ddab.nq.gz
    ├── 3a208024a1e60c5283872d43aa09a9980eca95e3.nq.gz
    ├── 3b6292e32df6494bca8782c8795627babe575f50.nq.gz
    ├── 3b88551b4cc174f9f67aa4e4fe93339b1ea7bc94.nq.gz
    ├── 3bb3875a4fabcb1d1275f1ba8ca43f00ddc97c6c.nq.gz
    ├── 3bf491e16b499378888133dce9355fee9914df5f.nq.gz
    ├── 3c3853e4096dddb6e91f69f0c78d28678e08628a.nq.gz
    ├── 3ca9b999085160d475b32213173b597cc2d9a5e2.nq.gz
    ├── 3cc79ecdd5eb6dd13c819cb53b0a445889052764.nq.gz
    ├── 3cde8a289314889d70b5a3e760bc5e6d1db49a69.nq.gz
    ├── 3d6c541f722c4bb5f8f2d1f4785560a66b0006a8.nq.gz
    ├── 3dd7d5798007cf78c061f0213d191da888ee4c97.nq.gz
    ├── 3debf25ec2afdd45a36a5a880d8d4dd3f41726d4.nq.gz
    ├── 3f17dece9fdcc926c8ca55c16fc197ee1a4f3b51.nq.gz
    ├── 3f2d22ffb1f44b9169a1d491f4315afa8d1d1632.nq.gz
    ├── 402db620b7f24e53e950859e31acc20d6cbadd68.nq.gz
    ├── 40512049d3907f30da057977e09285d38cf41504.nq.gz
    ├── 407baad370a6611111489c682e339cc4400dfccd.nq.gz
    ├── 4122421107d37e014dc9937c1dc58ea6f5300ca7.nq.gz
    ├── 41af1695394accf3de415ffc6bf418ee82cdc65d.nq.gz
    ├── 41fea5df217e7311c53dd4a510ccdf3fa26a62c3.nq.gz
    ├── 428e26c28940521e1faf79007cd008c6bb25e9a8.nq.gz
    ├── 436612ce0c95c6b49106f11240fb892db8dd3e5b.nq.gz
    ├── 44103b89e3a8d5bbbb2178c7c145b770076fbf02.nq.gz
    ├── 460cc8ea83293770e642eb0c0174cc9ffbd5b38a.nq.gz
    ├── 4657183ecdf416419121cac776d1f6849abbf725.nq.gz
    ├── 47642b878bd5b137207318fa07b5f54c233c9d26.nq.gz
    ├── 484a9ca8a8d452fc5590d41cfb3442901fbcd8d7.nq.gz
    ├── 4852448e2767ac1895f52cbb0d5a00ef6bce757d.nq.gz
    ├── 48597dc0428b017496aa55be3c232874c1e3e625.nq.gz
    ├── 485c9f0bb8cd28427572ba7834be52f5fee37854.nq.gz
    ├── 48f62294fcadbafb0d1cd433084b05116b766ad3.nq.gz
    ├── 493cf284e0600043f4a23ef3cffca8afe7422234.nq.gz
    ├── 496eadc08412e465cad10fc1f19feca1c5fc39f9.nq.gz
    ├── 499c5064170a92a64388da0a1d18793635107e98.nq.gz
    ├── 4a03f02f739f6b965bef018e126c491f191cb9b5.nq.gz
    ├── 4a65a8827b11d01a0663e614d31c8d3a94eb91d4.nq.gz
    ├── 4a845d5595633e3681bf9d1c2ef6e0bf6957163c.nq.gz
    ├── 4b84f5a662b16c9a190393d5f8fbf4dfa164b463.nq.gz
    ├── 4ca0d300f9d49da8c9c30598809939c7a851c72d.nq.gz
    ├── 4cbceb3c97977747977423c92b2e39e7f7a7d192.nq.gz
    ├── 4cdd143ef40497f0afe807130e6df1b06fd2636c.nq.gz
    ├── 4d35cfa7689e36b9cb32a98b40453a4077f370bf.nq.gz
    ├── 4d677989fec55f8310a74861ceb48ba931eb5194.nq.gz
    ├── 4d7a3b9fc264440599dab1ec0d5c53f31439b884.nq.gz
    ├── 4dee3f7bf34b4d85d82ce4b1927a272168955fd6.nq.gz
    ├── 4e7cb68dd4d39b4838ff654418ce0387a7e7d493.nq.gz
    ├── 4e96e6601041851c9f1fa0f0cec447e0fb450e3b.nq.gz
    ├── 4eaab05d3afaddaf0f93af062a272bcdad25c602.nq.gz
    ├── 5002cd55bfbba783488ef7234782ed12e3d7b6ab.nq.gz
    ├── 52319bbb21efcace90a9d44dfa6e7613a28a2b90.nq.gz
    ├── 5246f2bc7f4f1da81660137b449c6e8f912bc103.nq.gz
    ├── 52514cb7355242bca59cba1909a17f3544c24ae5.nq.gz
    ├── 52979188b404f497fe7a3abfc02394e680d66c70.nq.gz
    ├── 52e3297f05b57cc5565f1b8429f2fac7124ea562.nq.gz
    ├── 542ca4b22c9891260c42f4c4f3543ffce2307ee8.nq.gz
    ├── 5451e082c66e3f0edffd315380bf7d74caf14db1.nq.gz
    ├── 54e1d71eb8474999106eec67423308c4e245f686.nq.gz
    ├── 5579c07d3d304e835502e43e88e1a3cb0e64c413.nq.gz
    ├── 558b92aa64e60f4bfddd27ca7314f65ac1b0354e.nq.gz
    ├── 55c649e53a4705c0d02d8f803a65280e49794eef.nq.gz
    ├── 55edf061d6bb70fce0120a6590133e0b2d5e68d7.nq.gz
    ├── 565f1734850341177f450992bd40caeb6555ae88.nq.gz
    ├── 56a0f956caa1f0f399bfc034c6588270f7ebea3c.nq.gz
    ├── 57704bc2b12407e35363bf3d4c125a87ef72f820.nq.gz
    ├── 57e2505877c61aab2431d9dca9e414ec412fb42e.nq.gz
    ├── 581e4d886a4bf790b8d06b41db2bda2b440d32c9.nq.gz
    ├── 585af84c2691ea3227f6eb4f8b94fe13d9944faf.nq.gz
    ├── 595139042d2803627c03ea09d5764eacfa0b8e5e.nq.gz
    ├── 5a76e6efbe469334f31a60f73a29ae0ec0ba4136.nq.gz
    ├── 5ab2891c9a1ab185254db595d67871ba232f62dc.nq.gz
    ├── 5bb14c47da684a54ceda5dc5175701ed11fdc6c6.nq.gz
    ├── 5c572dfd78a558d67081983720de05fd2ca76702.nq.gz
    ├── 5c78be5b7f4e183cd67f4572afb2b38d52416b7b.nq.gz
    ├── 5cc70bc745b3c4f2165bf4864ac91c635db33c8b.nq.gz
    ├── 5cd66d24583603a8e9a81ed6931217fce7fa73b2.nq.gz
    ├── 5d0f06f3649fbdc1fdcf81fc8a0c73660870ebd6.nq.gz
    ├── 5d6fb252e40f001763c357f72c10bea04f90db50.nq.gz
    ├── 5df6fbee204265ee0c382ec6acfa5a657d1c00d9.nq.gz
    ├── 5e0f20695bc53c555262d067193b854fa5fc73ef.nq.gz
    ├── 5ecb800f9d482f6bb50f12f739812e42ee982da6.nq.gz
    ├── 5f0fdda38765097d74af99fe345f0860a59ec060.nq.gz
    ├── 5f1e29d6cf782273d40ec09989982cfa227eb145.nq.gz
    ├── 5fa53d829c1b205dc2de1344e9c535263246df65.nq.gz
    ├── 5fce65627d69c68bbc5ba9312dd4a2cd1b2d828f.nq.gz
    ├── 60277ee0749c7f7e5f052369545bd13a8c6bbc94.nq.gz
    ├── 6055e1a18457b6c853b98f62e364704d3ad99e78.nq.gz
    ├── 609c7afd2e41e46d4764a77b8603aae8f74d5caf.nq.gz
    ├── 622b92dfe4477381fecb5416e5dac1f5872be0ad.nq.gz
    ├── 63d64fae4b4a33608b3b4069f54244785a6368b7.nq.gz
    ├── 640e651c53f7687df70ee60d68a3ae20c1587e4f.nq.gz
    ├── 64a1c09fc85d0babe768f2e19d01ff6f7e331ece.nq.gz
    ├── 65540f1bc91c0f199c2ef7ed03d292456d915f17.nq.gz
    ├── 65687c687a9594a456f7952ba6f56181b8fc9332.nq.gz
    ├── 65fdf575c63486d3ea6067255a9fb345d5a08a93.nq.gz
    └── 664dc42df3d4c4d51f4f441d5e139e4bb21dc8e3.nq.gz

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

[beetbox/beets](https://github.com/beetbox/beets)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
