# Repolex Knowledge Graph of instructor-ai/instructor

RDF knowledge graph data for [instructor-ai/instructor](https://github.com/instructor-ai/instructor), parsed by [repolex](https://repolex.ai).

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
rlex download instructor-ai/instructor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 035c77b7b04dbbf70ae4457eb102038907b5a2a4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 035c77b7b04dbbf70ae4457eb102038907b5a2a4
│           └── chunk-001.nq.gz
└── blob
    ├── 0017f7287aedfc5430c31276c841685faabc1f75.nq.gz
    ├── 005c5e5a99d754f1fbb61607f9fd5e1eb12412db.nq.gz
    ├── 0124f26667c1cbb97289624dcf48a507991cd1a6.nq.gz
    ├── 020a1683ab0cb9c06270d5fadff9f1f662dd0a9a.nq.gz
    ├── 03175638f3aba2a4afb7b637cae068b28ae7e280.nq.gz
    ├── 035662b1682586ad126e0294df34eaf4f6e7772a.nq.gz
    ├── 038f4ba77aedd4ab57dbe5b563115fa768d3a23e.nq.gz
    ├── 044cf1d9340090881bc8d3c21127aa4e89dbd2bc.nq.gz
    ├── 045f289c57e571890f652eb386b190f5f9a9c3b6.nq.gz
    ├── 04a2961eb5278f80ebc5b01951b06c840d02fa16.nq.gz
    ├── 05b52b6039e2163fbd306bea297260ad6cf3e8b0.nq.gz
    ├── 05d53ad2c9bbf17b2c74b1ffaa5af056a8b161e5.nq.gz
    ├── 05e04309bd5b875da32f5639a1887c02083b4027.nq.gz
    ├── 05ef9e10f9faa6f6ba36aa957a94fc3142570837.nq.gz
    ├── 08c50fcd2f8ea7d1dbd9f231b78c56f0872fd301.nq.gz
    ├── 0918f6df0af89163f6f15fd6467a1b9d1f10a02a.nq.gz
    ├── 0972ba7d593a2306231181d29c34b6c393e5f89e.nq.gz
    ├── 09a8d23a7e9eddf644c57356c3b3243370a28861.nq.gz
    ├── 0a55fc60e7e8e38d48992a2185377f7cd0ae7b1a.nq.gz
    ├── 0b1f6bd065abf3e115cc1bc3a6bb8e2061467784.nq.gz
    ├── 0b55b1a254e02483054b980f772f168d9922fdb4.nq.gz
    ├── 0bf7d1e0adec364b4026cf375dcb25a5c6af407f.nq.gz
    ├── 0c52aa9bbed0fab1fa77a47ba8ee82439e88093b.nq.gz
    ├── 0c799531f04b64cb1d77818515583f0e2fd0e159.nq.gz
    ├── 0da4845650149a4ff7c844bc3da32e9dc61a6e31.nq.gz
    ├── 0de1c8795e988ea64d3024230b50cb6cf2ae036e.nq.gz
    ├── 0e0e26b7d319ed1c44f51628130ffb6dba3da970.nq.gz
    ├── 0e170ee4fbd65e7565479f499626b7cfb51f0ecf.nq.gz
    ├── 0e4c9d43577432ae8064090a80b29f2a088fe7e5.nq.gz
    ├── 0eb0aadab619f470288e1799790ca2e00643f1b9.nq.gz
    ├── 0ebed141b4fcc35950f254a87c2185dcc2e0a102.nq.gz
    ├── 1011d83258db889cb71846820ddf5cf04d262a60.nq.gz
    ├── 10674a896f598ef1e483d21cabbfe4b3abe55866.nq.gz
    ├── 10861e9ed3f67706b814bb3c3c72fb81db54edde.nq.gz
    ├── 10b1e07ed150541ad22cc121d79d733968213aaf.nq.gz
    ├── 11823549fad1e8b8094ed1f355447a70b53fc4bb.nq.gz
    ├── 11bb33e577a4d2cdb5477a3f4c5825825bfa9f76.nq.gz
    ├── 123e5d742f260ecf229c002f39a10f06478e4bb9.nq.gz
    ├── 12d58d46dd124e1f62e4721d9a53cdef60cba627.nq.gz
    ├── 12e7eb76b3ff2ee27b52057b97e5d3870787cad8.nq.gz
    ├── 12ee3458a288ca665a51fa91c641ad942ab0f361.nq.gz
    ├── 1310a1cdd37b285c775ca78dfa8a16babaa1bb9e.nq.gz
    ├── 14b9dbf537b50052231ea2d5e0ef3a761a503c50.nq.gz
    ├── 14c2c84912d624c97631ff2ba949a318638311c3.nq.gz
    ├── 14faf49a04e3e21fc871614d705226c53c90c615.nq.gz
    ├── 152db067a768a822bc848a2b553619d829429aac.nq.gz
    ├── 158dbb3906385eeda9ffc04e5390e524a8d7e06f.nq.gz
    ├── 15a7a64d85728ccf65e8b69a8db5abd380df99b4.nq.gz
    ├── 178c3a417f407a2661fba89eedebd170da651f32.nq.gz
    ├── 17eb07ca739b647961e373e0bca251e0160e2c5e.nq.gz
    ├── 18cda36947b85b2eebef6abd141dee571b3e196d.nq.gz
    ├── 19cfdcec86cf66ee41a36e2eb551fa4e2dad8449.nq.gz
    ├── 19f8dd79fe934427416a74f87af8ad775f31ca6c.nq.gz
    ├── 1a4af05a45bf02f98d6dfe0e55a78ba0136f46e7.nq.gz
    ├── 1b25d9ecacd7a152e27e9673eb3193f32a60bb83.nq.gz
    ├── 1b7c5a4b599dbb0d60b2d38b09d21923f25e7f81.nq.gz
    ├── 1bc7fdd1d3dbfc859287b25cc657393dd65e68b7.nq.gz
    ├── 1bcc394e6628cf7d376d74614ed4f31dd00c69fa.nq.gz
    ├── 1c329af6ae654d2544daa1912ca91d284a0223a1.nq.gz
    ├── 1d26a7422608fdbffca740cbe398f117584da801.nq.gz
    ├── 1d2aca919d349d56d9d15f71a252a2dafedf5ddd.nq.gz
    ├── 1d581aeb5e18378f615be9743d11555cc8a17456.nq.gz
    ├── 1d635f435aa03e8a8e4cdc65ef18f26d30f39d87.nq.gz
    ├── 1d7f8f49274d11cf285953f585e46f7a31fbdfb8.nq.gz
    ├── 1dbe2634ea988c91dd7ef9e97d9b6a45621fb5c9.nq.gz
    ├── 1e3e19066330c5a706ad0a9599301a035c5b518a.nq.gz
    ├── 1efa3616de5ae0eff30fb870ce09ef8d3911ed24.nq.gz
    ├── 1fb31665f6ec6a536c7731b8258958fdec6e8e1c.nq.gz
    ├── 1fb519383bd58da0f452e0e57c21d416bbde779c.nq.gz
    ├── 210c74dffb1e86f32751840d4e724b6c36c9eff5.nq.gz
    ├── 2194ebd585fe5cad8bf6573186a1c0bfe6e1d464.nq.gz
    ├── 23940130ab8504554c37627802cbf43d3fb9d183.nq.gz
    ├── 24d090418e695016a7d0cc0913125bbdb4c406cb.nq.gz
    ├── 24e9d05d030615f335264ef0746a616ce4f7a61c.nq.gz
    ├── 25903bf531a3ba89dd1f945df380f8472c18732a.nq.gz
    ├── 25dbc266d181da15dc5c0ee285813a717ced8917.nq.gz
    ├── 26278351422ba7fe459ba56326a5e0fe64e9dc3c.nq.gz
    ├── 26ca2d48329b4e2c67ee583b1c739bfbb02d550e.nq.gz
    ├── 272f9cc5b6c87e27938e3193ce781f6bff5413d2.nq.gz
    ├── 274b459ed58964e1cc0c4b2ec267cb3a0c3dd5a2.nq.gz
    ├── 275893476f55743508afa1469bc9aadfc71f0893.nq.gz
    ├── 27a9bf6195927f9bcbd359dc24d9b89891233d83.nq.gz
    ├── 286bdcfca4f478d928e588ffa75a9a8141115c4b.nq.gz
    ├── 29b4284c784dd31446d70b6dcb0d6c2cc066b91a.nq.gz
    ├── 29c2a2c9bf17ef7f65c6baf2aa2357f6fee0d012.nq.gz
    ├── 2ac99e5fa632360390519fac1d7984341e551cae.nq.gz
    ├── 2c5d5ecdf57913233b21713e0c24481b827eb659.nq.gz
    ├── 2d887c4f3cb40c75a4ddadc0e89a5bbe640dbbdf.nq.gz
    ├── 2ef5d04f75b53c66afe2de732e4d07ff36040be9.nq.gz
    ├── 2f4287d9e126b39687c4d9126585a8aecd6728a9.nq.gz
    ├── 2f696350c3cf1e1add7710840f911d6e9e94625e.nq.gz
    ├── 2f959cc1d4d974f928d80490c6c3c6c2e0d938ad.nq.gz
    ├── 2fae2aa84c1e0242a3b404a9c56127be134f17d4.nq.gz
    ├── 2fea09094468ee96a5750b21ff33bafcb9d2d89c.nq.gz
    ├── 308ad433afec3fb32aea6175b0bcf5470d9d5f82.nq.gz
    ├── 30cc22a1051490142183690f9fc3b8548487e315.nq.gz
    ├── 311345ad9d6ee8cce3e0efe03ceb9bea0f307141.nq.gz
    ├── 31b15b56203af16dccb1e3d96e862b2d87cc9121.nq.gz
    ├── 32080259cdb41044472353342eb93bdda1199ef7.nq.gz
    ├── 322911f8f4c852aab53a42c01c22bd0c484b6d1a.nq.gz
    ├── 322de5eca5d1c31d292a95d66fbada1c1a9a5395.nq.gz
    ├── 32bd91fb140e4519a7b22599259bcf1cf2af2b53.nq.gz
    ├── 33398f65f74c149f613d7a7c0521b2649c60a827.nq.gz
    ├── 33b5a080202b88668515cd095f987327441ab665.nq.gz
    ├── 351eebbef223fe75fc1c57beeca92e0d666e9857.nq.gz
    ├── 35d270ff5b9ace957b09db183d96ee4b43ef0bec.nq.gz
    ├── 35dafd1a15a898cdff7d742aab6e954e9907a272.nq.gz
    ├── 367099546399d420528823354528be03ac4c9268.nq.gz
    ├── 36c84a4b398d41d925f8d18ae98ef5cf844cd968.nq.gz
    ├── 3733060ef5be859cd6d90d6d4f1d3f6da9f00440.nq.gz
    ├── 37793d1a590889b69e43f8e7ab436fcbc057299a.nq.gz
    ├── 3828300a757e6b95fb725684158ab73b2c3eaa2c.nq.gz
    ├── 385614ef3b34f1265b2addac484e51a9b0f713ab.nq.gz
    ├── 38dd91b58f128a656270212565b55436ec2d27a1.nq.gz
    ├── 391eb7388d5c71ad6abd4fed7554b07933173135.nq.gz
    ├── 395658dd47aa98b8a135a71d3baf76cf6f37c399.nq.gz
    ├── 3a880ffb4367375699de56b11b5fb900b9c2645a.nq.gz
    ├── 3b54af0c8bb795cca7e44946a8b4167d19a20d39.nq.gz
    ├── 3c7569527fdf6407afe4cbe0bfc1d746ddb3756a.nq.gz
    ├── 3c7c0a56e2b382b57fde65423b6a02d725c30985.nq.gz
    ├── 3d69bb3186806869ee888da5a666adb3648fc13a.nq.gz
    ├── 3daae6ff07f5662b2064c2d10308092e3becf9c7.nq.gz
    ├── 3dc84e911c6bd0d3428a207d87321e9e2fa62a96.nq.gz
    ├── 3de7c7b85c8d7d2cf4f9acca04b9ca62e70b0e29.nq.gz
    ├── 3e53566a36c4ea419ecffa3ab366f42371e2c9c1.nq.gz
    ├── 3e6e6efa81fca65c154a6c56a97f4d9b60e2c603.nq.gz
    ├── 3f8937310ad6146012c3a362b05eab1f3ce94cbd.nq.gz
    ├── 3fe7851c7feffc4e570137513b17f3a4f0001bb1.nq.gz
    ├── 40559e8e1037985506afbd7babb40e975708db55.nq.gz
    ├── 40dc37c67d811ad76fc2953e1fc4cedef35fda91.nq.gz
    ├── 412a432cb990a4f411a0a128f9c9ec1033fd9562.nq.gz
    ├── 41906af0c98beaa5e9604bb6befcccebe4423ba9.nq.gz
    ├── 41bbe125377ae78543c7eaf867fad177b39e1e17.nq.gz
    ├── 42888721581c39973a8adf4a5484f85a2a7a126a.nq.gz
    ├── 42a3dfd3edf5f18f2a5ccc9942cb209e3e8f53ae.nq.gz
    ├── 433f49233b6bd03efe7ec86715ebf29fa39711ed.nq.gz
    ├── 436d8347f1541eeb10df900fc41ce0a0a2a46453.nq.gz
    ├── 44a5fb5c5fab997cf76d365e157ba479b7157784.nq.gz
    ├── 44b53186a9ea155dad0c75b533c4bef378929820.nq.gz
    ├── 454a3b25195491411e298c6a78a7c708608535c3.nq.gz
    ├── 45f1f479d85f7e0d993e686039583e496edcb24e.nq.gz
    ├── 46288794d9bf1f65d1480d892b1341dfff9c2715.nq.gz
    ├── 46755e807bab2dc33b3c119c318d6dd66cddd45d.nq.gz
    ├── 468622b43a0df665bf7c55c15da864af2b1eb375.nq.gz
    ├── 46a28e4ea5f54eef7397d5ca3e31aca93e3b72d4.nq.gz
    ├── 46e83f86be17da531276d116f045be32801ad1e4.nq.gz
    ├── 47cc7f75d3cb9c1b66a177ce5f4fd005e0f1d797.nq.gz
    ├── 4801872c48ce9ab5a2244ec5463018b14451e5ee.nq.gz
    ├── 488a45cc1fec3389f7bfc1bea9a0b437ebe2499d.nq.gz
    ├── 48e8a374a38180f5db206c02c614a3faf3d0cdaa.nq.gz
    ├── 492f7fde833225dd0bc19ede580df965abe33429.nq.gz
    ├── 494960a76165773462613ef1f6b27d319cd979c7.nq.gz
    ├── 499b4da95033e7e79cc3aa0c517d96d0dc857629.nq.gz
    ├── 4b86735d93b5bcc39fbdc0fc9c0729503316df85.nq.gz
    ├── 4c4a68b22477a19a0331045c015becdc08a57046.nq.gz
    ├── 4c59de961df1108d7c3e2fd0026c532caf1e9c57.nq.gz
    ├── 4c767aaaa7059e58442a4d15bf18b1239bc8c1a9.nq.gz
    ├── 4cc01938fff9ef6373c2f4d515551812c42fa902.nq.gz
    ├── 4cc0dcb44fda01894faf04db7ac644b54bd1a70f.nq.gz
    ├── 4d8ba37e9c40228bd94f0abe71df6d5d4c63ae47.nq.gz
    ├── 4dff0a8cfda288c2b1c6ca927d0ce3cbfa37242c.nq.gz
    ├── 50e7aba781408fd05a3056019f4088e5bb5b352b.nq.gz
    ├── 5121bbb7b1277007fbdb70f87fdff57e2741d36a.nq.gz
    ├── 517b3915a54d2ec5e887c73ea1825cc1e6477e98.nq.gz
    ├── 51f3abb1a455c0004f227688bd0c5baaba6fdd85.nq.gz
    ├── 52ebeee40a9e0da8f29b84dd57e1a0569ef8f3be.nq.gz
    ├── 534da22db57689d4bcc0497596389541a642b3d6.nq.gz
    ├── 5355e7ae74a57497db64f8a4db6d6d41b41b7da1.nq.gz
    ├── 53c3e0bfded675f6c7d3fb52c376dc36de923d66.nq.gz
    ├── 56884829ee00ca3b16cbbd5d7a9a130fab8f932a.nq.gz
    ├── 56be59cb71e775f03648202acb33c35d309e119f.nq.gz
    ├── 56eef0ba345cb83b32a877dee478ca494ac7387d.nq.gz
    ├── 58b1ea7119114094aec827c952faa281b37ddc52.nq.gz
    ├── 591fa7f89a7ce5e75f917ced07d8f80575e22426.nq.gz
    ├── 59307d09826227f5900067f400d4577cc5df3302.nq.gz
    ├── 59a545e22bfdc7525f0b6c42442f079dad9e1b20.nq.gz
    ├── 59dc718bf22b7dcab5768a972dee6867e1252a0e.nq.gz
    ├── 5af8be52c903f8af3b35529eb7972fa9f07d7f23.nq.gz
    ├── 5b44de0219ea03d2fb52d36cb19fd98af3fb358b.nq.gz
    ├── 5b81adfe72cbfb62b2a3088d64e9967e226297e7.nq.gz
    ├── 5c4539745dd3caeed1606103230a10d68a094e36.nq.gz
    ├── 5d06dc0b64bad045be4b1cc74bcb319171bf5be0.nq.gz
    ├── 5efa3effe27e0d742bac977783c19aaa06cd8668.nq.gz
    ├── 60511e70bd5ac7c1501f0c9a20977e3a7b683669.nq.gz
    ├── 60bad080fc3515763cb0ccf77bca824553e3b2a6.nq.gz
    ├── 60e9abb6c3e53250d48d9b5c38d23f2b8ddfe97a.nq.gz
    ├── 61b3ea00a5d469a7f30425ab386b76c03db13bd9.nq.gz
    ├── 623f6bdda5d12d92f32733dcf95f38c580f6fbe2.nq.gz
    ├── 625ac73bdd4e37ae681f970df21bba7580890b17.nq.gz
    ├── 646c155850fe4269b8a71854c177ac92139f04fb.nq.gz
    ├── 64864701279e3fd110249d13b3886e67d48d1443.nq.gz
    ├── 651dbc5a6fca0df3881125269532ba41e434479e.nq.gz
    ├── 652cd693abe341795405ca85eed14fa778ba8412.nq.gz
    ├── 6586d3d7a4b8e45f55839d9234a9de44b20c690e.nq.gz
    ├── 65ef8c004980b6ea8615ddc3cdb2f3b92b5cd707.nq.gz
    ├── 66b824985c39490bb51787d371735f33f4a5577b.nq.gz
    ├── 67486db70db5b49a4742f9929511ba83574cba80.nq.gz
    └── 676c098fd917b49a35335736e0e744f950c9da18.nq.gz

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

[instructor-ai/instructor](https://github.com/instructor-ai/instructor)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
