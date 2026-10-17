# Repolex Knowledge Graph of dry-python/returns

RDF knowledge graph data for [dry-python/returns](https://github.com/dry-python/returns), parsed by [repolex](https://repolex.ai).

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
rlex download dry-python/returns
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c60e1d8c51dee62efc2a7159946aab8c2393bc0e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c60e1d8c51dee62efc2a7159946aab8c2393bc0e
│           └── chunk-001.nq.gz
└── blob
    ├── 0044002dcca981b6110b400ddb7fa0903196bb7b.nq.gz
    ├── 00ea2bb64baea29f02eb09b3986560809c813062.nq.gz
    ├── 01517e34f823b7d9daa18235dc60d9b98e1981ee.nq.gz
    ├── 017034ccd41c8320af7286ade596d2139c1afb10.nq.gz
    ├── 01c79389c87ae20209e2610e562725e290562355.nq.gz
    ├── 01c806feade2df1304ef8eac5fb529edfbba0998.nq.gz
    ├── 0203887a695fd3a124a36359a6c092c9ca0ed27a.nq.gz
    ├── 04911f550d998707733e9063b6a59a457711b120.nq.gz
    ├── 0613f1f5c06d9b51bc49b564c283994211016e06.nq.gz
    ├── 06c670f59a17f4528071fd6b8a30bc4f2ab165d0.nq.gz
    ├── 076fcb349e5051119133ac1d8700a1f4eb8d93fe.nq.gz
    ├── 0778a3311ea47799fe7463a030feb85cff646ee7.nq.gz
    ├── 077b290b60058563282592b8d36b3e7851736a27.nq.gz
    ├── 08257477b8947cab6ce37926201b766fa9f7e6ff.nq.gz
    ├── 090939d242885a550ad051f2b91fb4f90ac25042.nq.gz
    ├── 095680cefedcc1fddc5c31a7493c64a6407d69dc.nq.gz
    ├── 0ad153a2d1a58ffe23630162dc4fea8edf619f22.nq.gz
    ├── 0aec48d8ba0f73b58920ae337c3963fba8d1150d.nq.gz
    ├── 0c17c4213228b3682c099fd4bcb304379df5e93f.nq.gz
    ├── 0c57bfc45ee4f85e8765fa9ae6d332045f4762d9.nq.gz
    ├── 0ca297b8a5c85b9e8799bb3355b2053cd30efaf5.nq.gz
    ├── 0ccf9ee55506764f66b0a9eb102af3a21670418c.nq.gz
    ├── 0d21847df75c401753752191b27618c204d26ab1.nq.gz
    ├── 0d70c24babb2bccb26ce6da9ca974d82df30e7c1.nq.gz
    ├── 0d7772eb5ce76c33a540120b793d1f9332172437.nq.gz
    ├── 0e0403279e6b92aef707b4a0db3939d2498edd60.nq.gz
    ├── 0e25b4534f36e2d8ba347e584cc745acc22a127b.nq.gz
    ├── 0f97e0675fb91ed61e60248727dab8f9f182e096.nq.gz
    ├── 1012358acea7b998177ad3e3a424081d55357b47.nq.gz
    ├── 11331ddd54e46ba0b2309a1bcb544c8841041615.nq.gz
    ├── 116b3e7173a22a623ebbfcf5853b9c12d1678d10.nq.gz
    ├── 120c4d0df2a6e71fb90885e9df08edfabd914f7b.nq.gz
    ├── 121869b5535726f56f2fdedffad5b49f86ca6936.nq.gz
    ├── 124dc0a5be9bf6bb10d8ef20e6863f2d58f426d9.nq.gz
    ├── 12a2890735607f8c1a501a9459a7e6d9f77eaa6f.nq.gz
    ├── 1378d1b8639867ee96dce2e3db740dadeb5613ec.nq.gz
    ├── 144b21b09d3dc93deedf9b7e1e87ae09ca7f6745.nq.gz
    ├── 1467aceada544a0a0f6a63917dfaa1cbcafacb99.nq.gz
    ├── 14ad5a06c7dd25bfdc6b05e546650b5e0e0165d9.nq.gz
    ├── 14f280a69d1bdf97e089e383d75fdccfca985275.nq.gz
    ├── 15c07c0d0620fd07e16d0b23bce0a677366df816.nq.gz
    ├── 15ec568996ae72fa16059d3218cb934764c24286.nq.gz
    ├── 169d3654ade7e7384409b350a8291494f512bc94.nq.gz
    ├── 18fea0267beb8e7f01f36baba7d86aa5a83b1eab.nq.gz
    ├── 19a0adcf68dff7559491a6a2422161fbdaa8cb53.nq.gz
    ├── 1a4af932cba9ca3b8846cc823ca5084aa16c1ac2.nq.gz
    ├── 1ab7bf1f45989a95eeb5ff2f506e4c3b8d0ba46d.nq.gz
    ├── 1b3c2ec769c681d81080817eba50f9536785c967.nq.gz
    ├── 1b8bf6620b8824e37c90c9d5dd1d8d336f6bd5bb.nq.gz
    ├── 1bf4967d886b24aa41964ea19f3e51e2fd61dcd0.nq.gz
    ├── 1d71e722180ae27aab930ae5f922c865de8bb9ff.nq.gz
    ├── 1dd2d7a6803143d97da8124f5e8c0d7f39c33675.nq.gz
    ├── 1e76f61afc1b8df3f631f91b0d14614df1acd9c8.nq.gz
    ├── 1ef734ba3004d4d04f16d0674019cf7ada80d6b3.nq.gz
    ├── 213abc12efb7e9df8e6feb8e9bcba8918b0dbba6.nq.gz
    ├── 21a65d013f048af785b131f8d653b17d9c6e4547.nq.gz
    ├── 21d0bd23b8250904cbdba4e6e98a8bba65c9d26c.nq.gz
    ├── 21d4981ff7cc7358834507df4c9c70daf1bccecb.nq.gz
    ├── 23dc5ee3e723a62c8fa366714a059b4332665ce0.nq.gz
    ├── 246802b198896af34819ed54ac648ca111cfd82f.nq.gz
    ├── 25e9e4e1093aaaad991dd93d09b396bed9fffc26.nq.gz
    ├── 25f155eacf85e49664f25e9003ba83ad167076d6.nq.gz
    ├── 263bbf072129ff7571c1e1694e49407fba690a13.nq.gz
    ├── 263f25501477f7f16b5d363550132a086d73773f.nq.gz
    ├── 26e8e25844d57966efb91fa1b596d76762f617ff.nq.gz
    ├── 28328303c211c2c01d373c7722aa7237fe1bd429.nq.gz
    ├── 2848a79400efc172649b389d119f3a939f5a7bb6.nq.gz
    ├── 28961d35a407504e2aa0cbddb9b6148355ee739a.nq.gz
    ├── 29dc4439065bccb4bd5de72a0255616312b6f9cd.nq.gz
    ├── 29e9fd330aac1dd6d44aba2b4ae113594b9d6d41.nq.gz
    ├── 2a7618d1d55421deed292af7b0163c70553880c9.nq.gz
    ├── 2a79d83f8c620a7c67d64dff6084ef0b2f199122.nq.gz
    ├── 2aadc0b0567b1cba9b458a59e2301674c9a9165d.nq.gz
    ├── 2b269adca309250c2b877fcdf607f13b4648f643.nq.gz
    ├── 2bf74b430a4e0311e6d9410a695783522fa22711.nq.gz
    ├── 2cb30d7cacd790ca37b5f4b87692f6d704e078e8.nq.gz
    ├── 2db090f05ecce6d6b1aa94f8c87581e78bb3224a.nq.gz
    ├── 2e4103487e95499e521da0d87e02ee01dfb04968.nq.gz
    ├── 2f0e429f20d558964024e3f8439fd9e9eeb62054.nq.gz
    ├── 2fa87d89dab85afa82ad1deff5b0b4c2e88f2a1f.nq.gz
    ├── 2fabdb549314374f4ff77968d07f10c4477ac36e.nq.gz
    ├── 30993104ea0ae9f4332a23a0dcddfe9429e98eed.nq.gz
    ├── 30bad5231fd925a214b7369b61784338204f5e85.nq.gz
    ├── 3173a4764a3f774f7793ac4d1940c965a2766468.nq.gz
    ├── 31a262b594be7062c46e20e9cbec3e39f872f38d.nq.gz
    ├── 324f0ca9d228e4a94ca02dbad71c80f38c5f6306.nq.gz
    ├── 32c8a7f89ac38dac70eed41da2f4677c170b23d4.nq.gz
    ├── 335485a27337d218ddeded3abadac072d7964595.nq.gz
    ├── 34da693bf068b891e3575da2137b3f07478cf2d3.nq.gz
    ├── 34fad9e766b24f66b57adf98d2ded83f1079cc6c.nq.gz
    ├── 35dfcb2e8cbd3784c3f98e92d499c8e860af9eed.nq.gz
    ├── 363d15a7e6f1616a54ff67602cbdea22012dbf36.nq.gz
    ├── 373fc2f21bc40c8b2e63e5be62583d46484a3a2e.nq.gz
    ├── 3753708c8648042c0e20da54fc038b19f7ada3dc.nq.gz
    ├── 3866f38916231f4448129eab0284d43e10df0403.nq.gz
    ├── 388ebc10d2e07f2d4c069a6345db25ccfc39e5a9.nq.gz
    ├── 3908e84b1dd9f8494c359ce80dd6fe7d921f51ac.nq.gz
    ├── 3915d84afe4ad46b436d532d40de989b99361f28.nq.gz
    ├── 392a2f950528e0fd349f6e5ad28cc2c839d3e8cc.nq.gz
    ├── 393df245889c0f2164bcb33255d050370fa89a7e.nq.gz
    ├── 39a9fbb9de384760dd6ece0daee132051bcdbba2.nq.gz
    ├── 3ad36fba5ac7d372415d1015be71133eceb482b1.nq.gz
    ├── 3b94eadd19a4d234a7808e3365e1f989eb61332d.nq.gz
    ├── 3be2963070506a5cdf78db6e52905e9f71ab7120.nq.gz
    ├── 3ccdd179303fc57c9b069ce0cf31b7e4b96655ac.nq.gz
    ├── 3d0e742f3880de07ff5b6343fa618b46aed59d04.nq.gz
    ├── 3d78d8ef9ca533b1f8082d8773935e3626f2bdc7.nq.gz
    ├── 3daa7b4ab9d63f5ba47780ddfbf22b8568b86566.nq.gz
    ├── 3e0f0455057482d1088119d84a8d93052d4a7aa0.nq.gz
    ├── 4078b51db939c81aba2e95059ee4237d7fab5866.nq.gz
    ├── 40bbdc928b9fbec74a84eb6dba5d4182be1d3fd5.nq.gz
    ├── 41eb379d6150a9fd78c50a6276d4302a7d3e38f5.nq.gz
    ├── 41ef4df5cc9b28e46c4e1c2f47147729cda20c47.nq.gz
    ├── 44b260f16dfe19b12b73a67dc08ac20066d6bb61.nq.gz
    ├── 453ae43045945b24395da25d1ed0e6a621aac679.nq.gz
    ├── 454f0e0f4e526b2d68cfcfba2c03fce349cb74ac.nq.gz
    ├── 456d0f2da972cf80c179ff7c437a2f000bccd7d0.nq.gz
    ├── 45c00c262e7294ee0cce31a1f14c90d53e209d57.nq.gz
    ├── 465ff2112d17660f365c72f8d2fcdb89eb5129ae.nq.gz
    ├── 46c1b4c6f90cb67abb53f64fb818d49a79844faf.nq.gz
    ├── 4709de49f4de7915e8ee0190dd8e3aed803134c5.nq.gz
    ├── 492624659cb5dcd8eae8277d8ddac9a8315b395e.nq.gz
    ├── 4adf1369db029b281ee59c3f761bd3f788747bc9.nq.gz
    ├── 4afbe8f5691b8be44984a8b7cf02df90c51486ce.nq.gz
    ├── 4b021b2dd20d805b1fffa23f911f88a2c5442983.nq.gz
    ├── 4ba688ffe340dd7289ca6628052223265c2c138f.nq.gz
    ├── 4bfcaf55672b78556ecd833534ab0671b94b50a6.nq.gz
    ├── 4c72b8b1fcb84ab5cb1ceacf2cbf71e1de180479.nq.gz
    ├── 4cf4990a3c6db4dfade4b31d9721a340bf66cbaa.nq.gz
    ├── 4d1fca14c8cb3efea80c01ca9f8bc4d8c4947a90.nq.gz
    ├── 4db603f841eec6e1590f5ad3ad24269907a4c091.nq.gz
    ├── 4e87d4717e03d49234a628a8e887a534d6a11c88.nq.gz
    ├── 4eed7286f0ab8f913b33db40ab5f418e57fbdf21.nq.gz
    ├── 4ef1fc17e9bc2fdfe5bb0ba539f88fcbb32e8ee4.nq.gz
    ├── 4f357645b62b7828feac5d70ed25e4d1518d92dd.nq.gz
    ├── 503b1ecab064c229b6e823287d6ea35a4e4312cd.nq.gz
    ├── 50722c63c38f59ab025d77e50b85cc8f70802ab8.nq.gz
    ├── 520404e6811fc2bda4f660e64eb4bd7c89c007b7.nq.gz
    ├── 5357b5c16b6033e30659eea12eb108c50457459e.nq.gz
    ├── 5415d0eb97e2fd8fda298e5887e5ff4bd7cea28b.nq.gz
    ├── 54c6eb2939444f27a838f12c05ba2a63762211ec.nq.gz
    ├── 54c83d2063a35eef9f424a703b00d52887082077.nq.gz
    ├── 55f75b4c95ce4c7bb308e2cf7709a58e6d8ae365.nq.gz
    ├── 5641fd427bb9ecdbbb317485e9835ce212ef5b58.nq.gz
    ├── 564f3d30506aa4297e35adb59da7d7f7de64dbcf.nq.gz
    ├── 57bf4a07fdfa9b6682dce27a0449b880057f72ce.nq.gz
    ├── 57e989fa858bd3491b9e9d5f0508d406fb10a803.nq.gz
    ├── 57ff789a8a903e236f47f232bbf06037824d3524.nq.gz
    ├── 583103e87a1f3e33b34259553fc49e4f03b2dd71.nq.gz
    ├── 5895096c90bd35cd017f4a9d92dd108cfdbdbafa.nq.gz
    ├── 5924c2517ae357857f9ece481402831b9658b5ef.nq.gz
    ├── 594122a2a143f243c5a6f143a62b5a75ceb02b67.nq.gz
    ├── 599955d698f7a51e757071de3e11c8045e37e348.nq.gz
    ├── 5a3564b9b1b14180c895f233c8f5ab5d7a09825c.nq.gz
    ├── 5a3f568e0d5f0f4640ab6f42aeedcd1b755ae45e.nq.gz
    ├── 5b7341c2f6837958df2746ec45675d4a9c42fcca.nq.gz
    ├── 5bc89a093d76e5b7b8aca3109b34b11977c63257.nq.gz
    ├── 5f0bfbf7fc19b573bbf14e68659a0e08017de255.nq.gz
    ├── 5f3aaa55ebc231e5419d3f2d7e266b6131d9a673.nq.gz
    ├── 5fbaac9c306ce2ca88e859d7f0bd0f3bb264c9ea.nq.gz
    ├── 5fd6d268d9cb8e9fa305d00dc888374a2d758e90.nq.gz
    ├── 5ff5aa8fff80b2de647b1e9b1432e0c5832d9c91.nq.gz
    ├── 603c4dd2886c2b6bf03893163c0ef55ab1f2074a.nq.gz
    ├── 61156190f19a13912f835f2da2c81fd748e1b983.nq.gz
    ├── 636060351881126fa0b7f58a729311ad8c66210e.nq.gz
    ├── 641ff5d141719d219e63c3c5fbe72fbeea45b28c.nq.gz
    ├── 648c9ecb4fa001bbb8673d84a2193feae75ba428.nq.gz
    ├── 64aeb57b34fb512533e099a741b64d75fd88411e.nq.gz
    ├── 64c3f21f8976500b9c03e28f3ca17a89b5380ecc.nq.gz
    ├── 6537f066f7649f557cd102d54b1bbb8c16bc5809.nq.gz
    ├── 65e2b297a9244f3451cf92a20527c7f35d716136.nq.gz
    ├── 664e8b9c7a362a3e7bb6bd19935ad47f90a894f7.nq.gz
    ├── 665cfa2ae54f1b8a3bbb1c4aed3d62e7acdd1ccd.nq.gz
    ├── 666d1f769f65199d711e61a959032edc1cef72f2.nq.gz
    ├── 6742c67cadf50f7c3818987ee3a66ec3df6931b6.nq.gz
    ├── 6930a91e4693d690353b1a83fdf10dee5ec67cdd.nq.gz
    ├── 69313b8d023688662666fbaeb83d7a7a17de43b0.nq.gz
    ├── 697722589a96a7ca19586d74b3182f2dd147db09.nq.gz
    ├── 69a4461de46d3e9108842630ead00c08b7bef127.nq.gz
    ├── 69deadbfaa24f38a21acb544a8865d9d4591556f.nq.gz
    ├── 6a906801bdfe527261c85b793ef068ccc0fe87fc.nq.gz
    ├── 6ae070d55d7729e136d9af2d01e0a84e6410676e.nq.gz
    ├── 6b23060b2c1c066804546b389c6a3ee4097f1dba.nq.gz
    ├── 6b537fb5e24545e8fa8f4fa770b530a1af87949b.nq.gz
    ├── 6b596bbbe418153e51fe61a806e18d16ae4a18a9.nq.gz
    ├── 6b9b2fd27f9aac935d611a9bf2994244490b035c.nq.gz
    ├── 6cae0d726694f44fe3d8f950a0ffcb217f22e022.nq.gz
    ├── 6cccfc76eccf1362470e2f8307a1c1a52a4cff84.nq.gz
    ├── 6cedbd9afe0c0f66d9ab10831f0544284fc13da5.nq.gz
    ├── 6dd515eb0498884da2fdae41246ffeaae8755c9a.nq.gz
    ├── 6dda4b9a3d94d5f6017b2a745d7b116ce0a27c38.nq.gz
    ├── 6ed73bdd9bd7786548135e32399166f41ec2780a.nq.gz
    ├── 6f1c9fd66d4d7987bf05043d1b9f5d269d218d45.nq.gz
    ├── 6f5be6aaeb2f8f04fcd1846d54ef0fea094f09ad.nq.gz
    ├── 6fe264bc871cfd9f30a375a0347510422d675f94.nq.gz
    ├── 7010639c084c04a15ae7eb5a72b34b80b6b10ded.nq.gz
    ├── 701e72574c663aec7dcc61babb2a7c057049d598.nq.gz
    └── 7024bd567cbf12f2d5149fc29c577e2a671a2add.nq.gz

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

[dry-python/returns](https://github.com/dry-python/returns)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
