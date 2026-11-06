# Repolex Knowledge Graph of h5py/h5py

RDF knowledge graph data for [h5py/h5py](https://github.com/h5py/h5py), parsed by [repolex](https://repolex.ai).

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
rlex download h5py/h5py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f5918a1cf81cfac6656c77083f0d255fd985f625
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f5918a1cf81cfac6656c77083f0d255fd985f625
│           └── chunk-001.nq.gz
└── blob
    ├── 0023eeed98f9f16a76d3a874720a3ba52c490cba.nq.gz
    ├── 0094597471fe45004811687126ba3e486f84cb58.nq.gz
    ├── 02a3f0906e0b021efdfd99fd62784d248628651c.nq.gz
    ├── 0301fedba195f5b776e6b216dc9e7ab148510915.nq.gz
    ├── 030e62307024728c1844f703c78e10fa9d9bf0a6.nq.gz
    ├── 043c4934da4a50e7b72274b14f9068179461a803.nq.gz
    ├── 04d48d32a758275b4f4cc2395600a033d28b75f9.nq.gz
    ├── 05579ff193f58edcc56672dd217b7cb59c63613d.nq.gz
    ├── 05d410aa488d76f38ca596cab9d8bed4669f9087.nq.gz
    ├── 061d4cea9c8daee917ba1449dd777a11a9782bc0.nq.gz
    ├── 06b2f58de0dc4beeb268986e4f4228c8a48f5260.nq.gz
    ├── 070f83057c872f240c23d48c17b2c48181af1ff5.nq.gz
    ├── 0804d62796ba069088acab188c247f5b9db54ce1.nq.gz
    ├── 0833cadd552b6825b8bf53de5b11a25163a19857.nq.gz
    ├── 08a13363c22608abf8ee8c2ba5ec00036c1d36df.nq.gz
    ├── 097b6066b2b146c53c0316e2f067c7e522a9de2c.nq.gz
    ├── 0a4252024d354957085344a20462aa963157b527.nq.gz
    ├── 0b7f62a43618e474505aa047cdee72d243ffabb7.nq.gz
    ├── 0c849159793b59f2d1aaff6bde3429b728a4bd7e.nq.gz
    ├── 0cf4c9f36b85f13a866ef20c32e1142eb3c3b254.nq.gz
    ├── 0dce8d8acda31e72201857a438d7867b583274fe.nq.gz
    ├── 0efb07383282bd300031509fe5ba2e1f7bac0ccb.nq.gz
    ├── 0f627b193c8c201a36bfc860135c40da0d0206b2.nq.gz
    ├── 10bc2a9c2c146de385d510135be1cba99e8a73bb.nq.gz
    ├── 11b06b1c703880dc91673655fdedabed5eeb4be8.nq.gz
    ├── 136c93e911fb15cfc077a93b1efeb38301bd646a.nq.gz
    ├── 1385f3f666ac2c236eaa1aa24f2ca35c53371cfc.nq.gz
    ├── 142e54548e0d78ed8f7f9c7561e76500afd562a4.nq.gz
    ├── 14574b499803f1e1fed1993bdf4c23ad27656c12.nq.gz
    ├── 14ab6b861d6f522823a75a24c5d613a9dccb0971.nq.gz
    ├── 15dfc918e0316186007b7f7fa2da00bbd5712706.nq.gz
    ├── 15e27f8fe451573c2bfd57f36e92f19c3c7098e0.nq.gz
    ├── 17ff89b63ea04cc624df67c17bb98ef364f813f7.nq.gz
    ├── 1b0ef11909065633977a383f76256bf6e81b7866.nq.gz
    ├── 1b419a8c2c6c906c2cc907ddd17e4b4edb6793fa.nq.gz
    ├── 1d49873f2d99aa547a695ba2733bcfe068e3fdec.nq.gz
    ├── 1d5f2a2348205b93101684b7601046983e261b7f.nq.gz
    ├── 1ec6cf6ed820571f3f28b69fb87cd491ed1554a0.nq.gz
    ├── 1fe32c9c50a83c3a79d055cc7257a69bfc6b1ae8.nq.gz
    ├── 219608ad36f6a7d296a8324bff0ce2b0e3c0bb81.nq.gz
    ├── 224499dce6037a77c44b1fd69218179e840f2a1d.nq.gz
    ├── 22d4ad0b45c092a26fd9bed6ab4ffd333bbc2cc1.nq.gz
    ├── 2401d3b058b3d248f142657212cff53f29334985.nq.gz
    ├── 246e34f9d231c9c15376866bf226a9243d8bed43.nq.gz
    ├── 26403d883ed73a6235e3fcf625d32416387f72d3.nq.gz
    ├── 2814f9dc399dd33d526e88739878e185cc00fff6.nq.gz
    ├── 28ca56277f0c598235b91158fc8f99755997fb0e.nq.gz
    ├── 2922ee71445b4cfd22df9af3b515eaa9a6b4aed8.nq.gz
    ├── 298db24dcaebb88b561cda7fb93045e683c349bd.nq.gz
    ├── 29d41745e36c159a1fac9f468eca3be60308fd77.nq.gz
    ├── 29ec1fcd572db6ef0fe138e7a988dce8911c0d0c.nq.gz
    ├── 2aa362cb43f0c4c63bcd7be0eac2b8244e56d33b.nq.gz
    ├── 2c07cff463dba3b9a1b57b1ca664ad89e1168778.nq.gz
    ├── 2c4730bce141757926b041b7a1d9109018852360.nq.gz
    ├── 2c8ded3f9f559f2b873ca0279ad60b3560f569f0.nq.gz
    ├── 2d07acacf489ae1dd86c6b68d19c9cf4f5aa967a.nq.gz
    ├── 2dbd9e84a7718ce85a1d631e0da7a30a51313d20.nq.gz
    ├── 2e26c69d687f3a32aef1f1861893d93d57d55f42.nq.gz
    ├── 2e822d6885e946d1591c48147d8820061ec16a51.nq.gz
    ├── 2fc4f16f95223c74a1567feac4070dd7d54d9afc.nq.gz
    ├── 30e889c13d91435ccdab77d7feb1f7e15c31cdc9.nq.gz
    ├── 32f12195e79db2af3c40db2668da2e9ebdffd2e8.nq.gz
    ├── 33379fd37e99096e56a5eaa1267cf271387fe8bf.nq.gz
    ├── 33e2b31007897987f0bf197058072434c1982d2c.nq.gz
    ├── 364a56b81a544ad7245ec85aa74a2e32678d92a1.nq.gz
    ├── 36bdfd6954aaacd2cf7301854323f99de8cc052f.nq.gz
    ├── 36ebf8c0f84aeaf850c4dc27cca0a95d7960c7da.nq.gz
    ├── 37291ba5a6416b47693524188ff33c2377949d5e.nq.gz
    ├── 3794d838df696858e2c00e94fcbf7e0ccdce68aa.nq.gz
    ├── 39aef470d16da20fda9b0a57e45fe438b74f0852.nq.gz
    ├── 3aa83c80f65b3baedf1b098a3a92d98de32b9bbd.nq.gz
    ├── 3b789f44d16c03b7142ee2a20824a5f25906f446.nq.gz
    ├── 3c5d558e6c75c76359b93a32f3f7d2eb76a08b86.nq.gz
    ├── 3d854df91f71937dce6d54e4dc447d9e5ffbab60.nq.gz
    ├── 3e45b55a3bfcb99ad3bb7c5ee08486c74a9152ad.nq.gz
    ├── 3e6b21181f262e917e0d778cfe632991395f6a88.nq.gz
    ├── 4095cff067e1b7c1e7e654a5e668affe3fc67300.nq.gz
    ├── 41b7a54cb264e0573cd57f5a23069d93d95f0308.nq.gz
    ├── 41cf84d3647838aae518d19e0d8042fb3a488e30.nq.gz
    ├── 42b483c1a865e344eca6f9abe29bee58986fc6b2.nq.gz
    ├── 451962b2c651c38a92c74558d58a56533501ba52.nq.gz
    ├── 4631dd843d0d475e5ec1b8a9ed630c273d68761e.nq.gz
    ├── 48bcee22aaed722a2477e6bf526c9e329d70238a.nq.gz
    ├── 492e828ad3a50fee5e1fb4def32d78b03369a602.nq.gz
    ├── 4a3585ef2851f833f5210004fd9d162494fed81a.nq.gz
    ├── 4b0aa46caacaae566aa62723ed61f5a78d40cd8b.nq.gz
    ├── 4c3b84027c6f0af56fc583704c1ed50fd0c95795.nq.gz
    ├── 4de6aad761792c005052d39100746db13cfa89d0.nq.gz
    ├── 4e03580043ee9d3cce52c95e34f626b60c3dc739.nq.gz
    ├── 4e196d46f3746d45d4e74db7294ab73634a6a3df.nq.gz
    ├── 4ea8dab872ca621e40461b0915c613254954744f.nq.gz
    ├── 4eb1a032af0cac1177535092f50686ec1b4f011b.nq.gz
    ├── 4eec52e42e217d08e8dbb694e445967afbb53ae5.nq.gz
    ├── 4ffbe1d1c448c3e24fb745767b268eff398ade8d.nq.gz
    ├── 50a7fb63c026ee87a02a20b744925616543266bc.nq.gz
    ├── 511872e323a1e06623460894a2cd6112a885d334.nq.gz
    ├── 52d1805d2c3fb56d88ba152166bc30ca8c54b298.nq.gz
    ├── 54126de23c56fdafc8ed5baebfd8da6f1ccdcf8c.nq.gz
    ├── 547e19f83e8432f62b50f6d87d9a9b997362b2b0.nq.gz
    ├── 54b79c4f4a6953c6235fccbd10b156152337e151.nq.gz
    ├── 559ce8f4380f494f0d34fde86ea0317499a9106f.nq.gz
    ├── 55bcf77aaabd2814b33e9e91d62abf8071f8fa96.nq.gz
    ├── 576e5d7b2543ec00f3cabae52a8a8ccadba6293f.nq.gz
    ├── 586f4193756b82b621377ae1cd732cb9af52f747.nq.gz
    ├── 5b3f9cff7b11962d68777e08ce5a3df5d0d09605.nq.gz
    ├── 5b55226cd77af75d87d0607aadfbe7ee6cc4999a.nq.gz
    ├── 5c3f268b37099f7250ede547219c95cea0f71ac1.nq.gz
    ├── 5c947776078efea3ec12b9d19e78edd022490572.nq.gz
    ├── 5ccd0d57b9ae4583cb3ae8a1eae09522e6fb21e8.nq.gz
    ├── 5d51a397556fd6f145c661e202755c3a66d0241c.nq.gz
    ├── 5e6e95a975a90f99a34b6444fbb31ff896f782cd.nq.gz
    ├── 5ebc462ba69f1a7bf3282ef52cdaa32495815eb5.nq.gz
    ├── 618b9774e9815772d9e1c4a8fb460bc3be295bc4.nq.gz
    ├── 62b888c7a40c1bb5a495bb6a0c3b4c51231f3ed0.nq.gz
    ├── 63db640d0d6edc6d1d941c317e7d92eefb859d03.nq.gz
    ├── 63df29585e58925d94f7b50c795d9efcf92754d5.nq.gz
    ├── 63ec0982c2e7f10869ac7246fa862a0bd02892f5.nq.gz
    ├── 64b17a08a95089260bd204dbbd8171cb4e96badd.nq.gz
    ├── 66583bc563aa507209304077cb0f32a3cd3707f5.nq.gz
    ├── 67c2b95a1483e68186c367d919f3a6c890af57e3.nq.gz
    ├── 6944f90b8c6916c160ca048c86f6cfc9204bf3fa.nq.gz
    ├── 6b76f9319d42106755614c8ad949aa1134c3db62.nq.gz
    ├── 6d40cb9655cbbaf98572d63993fdd797a7abd75c.nq.gz
    ├── 6d6e0001e8853652f9ddb3778c964a5c694ba65d.nq.gz
    ├── 6e4e29bb2fa8b24fe6801cad6d3ea20e87890a8f.nq.gz
    ├── 6ea33d163d3d828ab0c887a8d7341d9f2a9c5380.nq.gz
    ├── 6f218a57078f1da9198e583eea675b3e3e14beff.nq.gz
    ├── 6f60a325496b0426c36d24dadf12ace7d67ff088.nq.gz
    ├── 6fc021bb26203856ddd4d86dea8d082d493afea9.nq.gz
    ├── 7525fb384678be710bbb7fcdc2be929b4c86153c.nq.gz
    ├── 758bd5203029c659142f6d596862a0d70201c178.nq.gz
    ├── 763f03097a70b764ad8540607588e7207bc75d00.nq.gz
    ├── 76c712a07522a576a1133092bcf6badc54dd8aa4.nq.gz
    ├── 76ec9de5402234a85f421955896e02c874c030ab.nq.gz
    ├── 770ef45574405a2e3272fedad9e3babf47023162.nq.gz
    ├── 772ce13335cc7e0fb4073cbfa320a98730f99547.nq.gz
    ├── 77719ea60df2caf19b19546e471457274757aaa8.nq.gz
    ├── 77da0dcb3fb12afc596dc2c10b8c64aefcdaaadf.nq.gz
    ├── 77ebad4afd8f89f24591f4f2751006c77e984251.nq.gz
    ├── 79dca11b1cb1cfcbd2841b95a6571a963f5743ad.nq.gz
    ├── 7a24883e19635532a9ab6a78b1ca732e05d0366e.nq.gz
    ├── 7ac819b7e62f8317ffd2702a3466003ea2d31844.nq.gz
    ├── 7af6cb8817014e445a6a83017265325dfbae398e.nq.gz
    ├── 7d6655b7b6e9a9c0f29450dd7ec0ba43db6a1e65.nq.gz
    ├── 7d96034dd8a9fdcfcc7d76a0c5244df7adf56b7e.nq.gz
    ├── 7e13365231569d4e33659b0c2b208f4b099539a5.nq.gz
    ├── 7eca787edc4c897b19ccd629d7d3a3ab4a88ff58.nq.gz
    ├── 80233e3118bd01a10bff697ca1d709f55fa06407.nq.gz
    ├── 80a64aa787564cc0811beb628b5b1482d74a2af6.nq.gz
    ├── 817e7b99e6cad1b4daa7ab5128850134a3ff13d1.nq.gz
    ├── 825bb0ef7787b10f0e3570b5274118d8ea0db1c2.nq.gz
    ├── 82a31d3bc12ab7a364016643b3771c93b7c20e4a.nq.gz
    ├── 839af789480b4135892a23403fc9045490d62466.nq.gz
    ├── 83b00d0dc11c449e0d281757476959b60cfa626a.nq.gz
    ├── 88c1d37641f928010af2d9e0b6dc343eccf0d25f.nq.gz
    ├── 891d043c11325abc1221fee24b1f5fd73575092f.nq.gz
    ├── 89859c4ddea246ef7881c7d06fd811bca862f61d.nq.gz
    ├── 8b38c278a3936bafc1694c1362f90af12a3f2ec4.nq.gz
    ├── 8b7028116310d41f0f5cd702ee5c2294807294ac.nq.gz
    ├── 8c37b7999d0d23be4a7120261c58588a976afa5f.nq.gz
    ├── 8d75fcd1dfbfa1f7279d5788d84f5346c97ccc67.nq.gz
    ├── 8dd2bebd55ff530673d1d773f6573b778fd28f84.nq.gz
    ├── 90bc8f560608a03c78a15bbb3d34038faba90f75.nq.gz
    ├── 9127f7c64834d0e339a5cd93b2f7d14345723451.nq.gz
    ├── 9183510c55b067e81e7c9ac3e7b794c3991308b5.nq.gz
    ├── 91b2f8db1feb14fc7b7cce9eb75065eeba9d1166.nq.gz
    ├── 9261978974dc35d615d6eece87ff3c55707847e9.nq.gz
    ├── 926415b2dcc68c941952902e755e08c2be1a00fb.nq.gz
    ├── 931ee419aa55a0ba2b8399b90e7537765338e780.nq.gz
    ├── 9476328e1e03782ddaf93cbb4db5a30865dee9f8.nq.gz
    ├── 94916f68b6c58ac405d70142a795da5546b9f051.nq.gz
    ├── 94e5fd41840025963e1170d1f3b62ea57e8ca602.nq.gz
    ├── 983afcd38eee4e9532c4bdf974a861e3c5e10a54.nq.gz
    ├── 98585a3b00567ca9be7eabfd2deb9bf796855beb.nq.gz
    ├── 98df831d1c020f81049357b67a868d32d7a90669.nq.gz
    ├── 991578aa033cf03cd17bcdd57ec1083995f51f39.nq.gz
    ├── 99b9d72e6338992150abdff586278f717a1ed9fc.nq.gz
    ├── 99d926e92546bc00e39bfd47aa38fa5c3d760b52.nq.gz
    ├── 99eccdece1a6164ebaa78d3ff2c70ababeff941d.nq.gz
    ├── 9a75725b5c1f2646cabfe940ecfd120a79b50956.nq.gz
    ├── 9a9d5d3063e97fcac8413a9cd4be9bdd3c510c81.nq.gz
    ├── 9b270814b15fee4d79110dfdf16e0c7e42c07a3e.nq.gz
    ├── 9b3eed401028776a32a03d7823a395da0def8a12.nq.gz
    ├── 9c93c8a4337d0f0f23f60ea23439e6f37899e5b3.nq.gz
    ├── 9d317582cf4d6e0dfd2d0dc389306f0be6404331.nq.gz
    ├── 9da009abb14586b841eec26bdd31ad0eb29c1ef3.nq.gz
    ├── 9e00dabe7dc48472eff7b3f9494f3ca4505640aa.nq.gz
    ├── 9e0d5974bc1af33ae8777a8faf1e053c4c84d6a2.nq.gz
    ├── 9ef557f8a0c733883bea97fff73bcdd194cff70f.nq.gz
    ├── 9f2f482c1bdcc7fe4930c79c0d65be5e84d4fbdf.nq.gz
    ├── 9f98568d74797a8b54252314dfde273726a970df.nq.gz
    ├── a05788b0f868e2e1a9001163eb05bc880f9f1b08.nq.gz
    ├── a0aeb374418398246fe0bc82d59907293e01e3a7.nq.gz
    ├── a15ed238931b4014618c99e694cf8b210a804685.nq.gz
    ├── a30dc0d07709077f8b29ae01c33b78ff02902f7d.nq.gz
    ├── a359e8278964b67aba8af91c58cd3ac45c8c1e53.nq.gz
    ├── a4d4dca4578ae2d73a9cea822203232d29508d35.nq.gz
    └── a6bdccd92f344917e7d63c075ea449c00f4be4bd.nq.gz

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

[h5py/h5py](https://github.com/h5py/h5py)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
