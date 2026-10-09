# Repolex Knowledge Graph of NousResearch/speculators

RDF knowledge graph data for [NousResearch/speculators](https://github.com/NousResearch/speculators), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/speculators
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dd6d7f93fd08d7b456f3b6313feb02fc4dd08d38
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dd6d7f93fd08d7b456f3b6313feb02fc4dd08d38
│           └── chunk-001.nq.gz
└── blob
    ├── 011972ec5e8afa8d3152170156c30e3f1f937f08.nq.gz
    ├── 0391e2a171cf94dd4e27e8ee5035c73777cfd153.nq.gz
    ├── 044e2d87d1badcbc44c6d36e3c9d2976d92a90d7.nq.gz
    ├── 052bf2452f91eb7883f371eb195dfae7c1aa7001.nq.gz
    ├── 0553750b9585638b4cc16fd8b7a22e7b48b868da.nq.gz
    ├── 05607f67b657ef67a64c70c4b7d1f1ae12c91be2.nq.gz
    ├── 05adec23e53bd4ab5e78391c833fcff9385b9eda.nq.gz
    ├── 076ba684c534ea29eb9b4d8bcde7e4e7ea0e4ccc.nq.gz
    ├── 0891818e6938427c78a0424a8d1bb92bf821e1a5.nq.gz
    ├── 090c7952ffa1a1dffbe48feaa4ab047872139eaf.nq.gz
    ├── 0a296faa19ea06e6d82c9be08d556fb8b1bdd79d.nq.gz
    ├── 0aae2969e511ad4b2095762f3b0ae105fbba9f59.nq.gz
    ├── 0b3fd4a8dca7504b02d6d9400e0e5f11a30be8e9.nq.gz
    ├── 0c551222330b826cfa3c8e5a29d035dbec3a7f58.nq.gz
    ├── 0d05337d1a36b8d8b2186db054bc9b06f2601227.nq.gz
    ├── 0d34de881ec396dd656f995cc00c1e4f459e87ed.nq.gz
    ├── 0d9b2b7b4acfb1a4917dbb9ec4e53407bf802a09.nq.gz
    ├── 0e48af7100ef0102cd174e9ef8b28a906ba36d8c.nq.gz
    ├── 0e504e3ab58a1a334c4425828c96b89fb6ec414f.nq.gz
    ├── 0eaa1d9b796dbf70f743f4791c0c24616b7106c2.nq.gz
    ├── 105a2f01db8fe129c323c51a3f9c6fee3a30d98f.nq.gz
    ├── 10e1c7d3e9a96cab2609aed436f16bc09a08411b.nq.gz
    ├── 1125543041cb343dcdfa0045d4aada5b81d181dd.nq.gz
    ├── 133f3bc53d6fe127b81b50d92d242c0a88f4722e.nq.gz
    ├── 14e7f0ca60ce3bd7402bca16218c3a0155dd8a93.nq.gz
    ├── 14f551a65e52a1c5fc221d2627d7a37364b3491a.nq.gz
    ├── 1529827a379e28fc07805a6149156fe73cba31b3.nq.gz
    ├── 15e65bc909d607c9c8a7f5022a85f9e32b5c12c9.nq.gz
    ├── 164de04eb98175a15e860d4678d0fdc2ccb0f91d.nq.gz
    ├── 16ff43ced5437dfa75f6b3a0b924045b9924547d.nq.gz
    ├── 1795b07db5b4fa2ff1eacea9db348519c5746ac2.nq.gz
    ├── 17a19d06cdbd6498a975c4828b6fb0b77d798d84.nq.gz
    ├── 1922e5b8b20ca74e550592c8f1d0c61d2dde4a99.nq.gz
    ├── 1aba38f67a2211cf5b09466d7b411206cb7223bf.nq.gz
    ├── 1b261b00896b5164a6824465ff8e99d8c7466681.nq.gz
    ├── 1b87aca305cf6ce03306ea81b9895b298d1dbd45.nq.gz
    ├── 1bd317e12089e5c83118ea9235475c9d7d9850dd.nq.gz
    ├── 1c927f05a54eceee4688763050c4e93f5400a588.nq.gz
    ├── 1faaa983739c64871aae3babe7264f19fe880b2f.nq.gz
    ├── 21758f811b23adf0b3966753a774b7ffb911e02a.nq.gz
    ├── 2208287f21e46fbf50da7bd26609e55c96646beb.nq.gz
    ├── 224dd0d8b7927b65d8bcd818c84a211496fd565a.nq.gz
    ├── 2377ad0528367e320c272cb4cd1dac89de1d2b82.nq.gz
    ├── 2403e5db49684bd074029e61159e6991eec2d00f.nq.gz
    ├── 246a24739fd26c0d4ff12eb65b9f297d957843ef.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 273a35e993e7184ea26542eb355f388a77aa6aa8.nq.gz
    ├── 299253bcf50fe889710ef7160038231690c6218b.nq.gz
    ├── 29b118162e220157eca99884a36a363735ca6172.nq.gz
    ├── 2ab74647c4d945a8397dde715d6adba5804bf5aa.nq.gz
    ├── 2d819b9be2ea549905aaf2751d75f5c4c6f2c509.nq.gz
    ├── 2e526f6d5113a642bbb58ae87b43be1e75167653.nq.gz
    ├── 2e88987ceb3650db7a08d2e0ec06b763aa7d3d5d.nq.gz
    ├── 31cf9e3a0757a5fbdf03efb7f20e2dc05bb926db.nq.gz
    ├── 34a187e40c50a08b54cf2a450a7bbbfec920b18e.nq.gz
    ├── 35aeb33e4f5b9044fc83ca2319fddfd0e7daac25.nq.gz
    ├── 36d8d6d2d11920102a0e320efe48e3bf5c5bbc9c.nq.gz
    ├── 37f9574109afda43a6feb02c1ccbe081e02cebc8.nq.gz
    ├── 38152d961a4855e26ac06aca01bbee4fdd86b535.nq.gz
    ├── 38e30ad5626b2feb9ede645cefbabe1f97b4d110.nq.gz
    ├── 3a92f39b66a62250f2a1ebec3da64c92ba83a563.nq.gz
    ├── 3becd762f3542557b2323efd35354b468558cab1.nq.gz
    ├── 3c68026ff21ae4fc9af1b7eaf2b5e6eedc34a75b.nq.gz
    ├── 3e2229188f277a5753ac18af77454bc3fd7105d2.nq.gz
    ├── 3fdc22abd3937b63d61fc428f73a43e257afcd60.nq.gz
    ├── 42719785341d91a692d55467824c9231dbcf8d24.nq.gz
    ├── 42823404c51675ef955ead5a214e490ba1a00df6.nq.gz
    ├── 43f19f0da9239f9ec55ccfc6d3516eb07169e0e9.nq.gz
    ├── 4467700a4c17abbae27959b540c1fb77bf32b8a3.nq.gz
    ├── 44a7f22c09bb2da398158458c6ad5bc445611737.nq.gz
    ├── 44f68e1a642f3d7d69b23c291f47048b92ac6733.nq.gz
    ├── 455d1df97c952faf1dc3943338f43a18581f8b4c.nq.gz
    ├── 45bfadc2d04d62f11d914750f525f839aa9b5418.nq.gz
    ├── 474ec1996433c056a7914ea065c4b02e5d2dfe81.nq.gz
    ├── 4797720f2f65c6aacb1981f16ef904dfeea60208.nq.gz
    ├── 48264682083a0dcde77802bfc1c1b54c6f3f929e.nq.gz
    ├── 4a9419236d5190a92e62fccb4380bf6e6ba36e20.nq.gz
    ├── 4b91d7386316ff569de32ee3ae2e0ea7dc47daff.nq.gz
    ├── 4d289f49dc75a57a6e283c7a7eb901144e68056f.nq.gz
    ├── 4dc21014bd93282b6fcd0cfdd832b827e8512e3c.nq.gz
    ├── 4e39ed9d848f68f0e34b11ecb4cdb06972b0a2c4.nq.gz
    ├── 4ff91826081ed6f2c0858ff3f045345a7ecd323c.nq.gz
    ├── 521637264a5d12912d91486dd0f889ef5ce2dd69.nq.gz
    ├── 535de4d9834273efec642d32d55c82795f11bc0c.nq.gz
    ├── 576aac7f0d679be7a1499a958db4751f6dbf2af7.nq.gz
    ├── 588f025f11004307a3bca0a699011ce2a3fbe413.nq.gz
    ├── 58a07a695c72939730a3516a100e0e58718887a4.nq.gz
    ├── 58cb69cdfac13e0f15491352cd8cf558535ca42b.nq.gz
    ├── 5912155c0a998a9bc64d2ede9d617f3a1bb8581e.nq.gz
    ├── 594434b8dd6502afc99535af4c3a9beb8e9a07bb.nq.gz
    ├── 5958dc01e1a73c91f937636f1a870e0dc89cbc33.nq.gz
    ├── 5bc3988c0119a342ae3eb02f79b560ea214ad738.nq.gz
    ├── 5c4624103efd565f0e4f37a484f7541756a181e1.nq.gz
    ├── 5c657b3f27ce50f5cf7a5ebf1b066f028083e97a.nq.gz
    ├── 5d76f1514ac13a82b221382e2cf68d96e1489dc6.nq.gz
    ├── 5f5d396f42354037e5c92f837de95caccbe5aec1.nq.gz
    ├── 631442074e5299b3c28f55381d11a009d3e1238e.nq.gz
    ├── 63831184a9f6e269fb5b0d9a2b438bff3e96bc9a.nq.gz
    ├── 6450cb9e2245731bc9c7eb76eb3b05c61b6b8714.nq.gz
    ├── 64e84d2583892c3d7b6b7573a43ac8768d8fa2c0.nq.gz
    ├── 6549444a9c2d8a741fae0db4b31db96d0f8c458e.nq.gz
    ├── 662d97a64c279496e25cf7874298b14cbaa3eff0.nq.gz
    ├── 675f2932d89d72840299ee528af7bcea696b1bcd.nq.gz
    ├── 676c9db234abfb77315d41fd77a98a5deb6859f8.nq.gz
    ├── 69ab284c4a0b71f6ae47f7612fe0d1b53cc0469d.nq.gz
    ├── 6ad4b0cb398ad4b607833b45c5bf041bd5270cfc.nq.gz
    ├── 6c2db5af26c3224e31ee62261227a6575d762c62.nq.gz
    ├── 6c4726a4946fccc963e06ace3bf2bf107a2fafe5.nq.gz
    ├── 6e72cc87fc0780821ac40a5d6d38ae11b8bbf584.nq.gz
    ├── 6edacdd336621254aad132b321802634f16e08a0.nq.gz
    ├── 707f5c3711f2bdb4db9b1164898a12b3b26205ff.nq.gz
    ├── 70c292c290ff10b43c3b14c4b7e70fd8ec789c25.nq.gz
    ├── 70d1ebe1966401b884fd46bf5b818e715a76d645.nq.gz
    ├── 70f0f7c4ac033e92675bb3b4f9a8a411726f4f53.nq.gz
    ├── 70fa96f6e79557a76f5f4f95e1d59d0d505f0361.nq.gz
    ├── 722e7c7b6ffa5e2d48852d5e06950f4b9cfb6066.nq.gz
    ├── 731e5cca3201d8c675eeb67f76ae893fb68d5e0e.nq.gz
    ├── 73ebacf3f8b59d9fca4113a10116cdfdf1e86663.nq.gz
    ├── 74ec131846af9aabc487048407d4d051cc36c4f7.nq.gz
    ├── 75d61f8cd54e15c35cbadf03dd159a83bd8b9103.nq.gz
    ├── 7685e1a24ef53cbc357ef5b2de8f35957dfccec1.nq.gz
    ├── 77f6d9d23da6a6ae319e0368cd104a7228f76b9a.nq.gz
    ├── 78ab2c57bd5ce376f8c2991c1f6fa507429a721d.nq.gz
    ├── 796450415cf4e0ad64f395d5aa652e0d4c45ea48.nq.gz
    ├── 79738bfb54b253bca5b26d9fff5e01e3b27700f4.nq.gz
    ├── 79c4a01079b1588dcfef76410151aa2ebb7ef867.nq.gz
    ├── 7d9164e1a876176816a26061809d30e0ef0b2b6c.nq.gz
    ├── 7dafb5b21c623719b697a248d3440dd38c52e036.nq.gz
    ├── 7e48906afd78a6b1959ede677b41984dc8796031.nq.gz
    ├── 7fe25078080d1baeb7d2353494cbdd0deb51152d.nq.gz
    ├── 80f26cd2e954a0fd4ebf3a057ea5b5f9d2f6c946.nq.gz
    ├── 8205e93f7e3aac36fdce4c8b2911ebbc2921d4ea.nq.gz
    ├── 82a3214d98d41c9d9e88816af1015dd0f7aa49ab.nq.gz
    ├── 830a5c2ce5681a69da106ce2539cadf0de34cdb1.nq.gz
    ├── 83cff3810d716fc29141824fac31426f97abe67c.nq.gz
    ├── 83f2062e4ae6ee4d451bd84849dd3517faeda87e.nq.gz
    ├── 8421f94107d9db482fd5fb74ec07a24d7ac47aa9.nq.gz
    ├── 852915462fed126c4f9db63e1be3549b74cb1d13.nq.gz
    ├── 8927583a0dd7b74474e86e648c05cba043e1a4ab.nq.gz
    ├── 89ef83c2021d76c55f98a980fb66d08698f96c0b.nq.gz
    ├── 8ab16606019b4e940e0ff09f90aae6e13eba8c5d.nq.gz
    ├── 8cc23fa87ad420f069f70a73fca3fa9f579e7138.nq.gz
    ├── 8dc41bf22f5f8576ecea979c03a8dac00d2e7ff9.nq.gz
    ├── 8e263d782fdb4602b2ef0b241ca3945858332cee.nq.gz
    ├── 9110117a82fc2bcfb1388287ff4974cecebab036.nq.gz
    ├── 92f724fc1b78d41512cbe4b01364d153418fc7d8.nq.gz
    ├── 9545e734ff7f4958be306ca89dc741ebb7ce4984.nq.gz
    ├── 9567e6a6c1c24758d6ac6ea8a7897b2d9f1b9512.nq.gz
    ├── 959a56bb90dfa6a2476b978df6062c87d0fcb6be.nq.gz
    ├── 980d959b1671d5c44c07285a5502092010d39392.nq.gz
    ├── 98a2537fe1eb118d97c36c3ac0b2ee37b1460644.nq.gz
    ├── 9a81106f536ed0989b902cc04e0e8214199c83a4.nq.gz
    ├── 9b730664e52ef2ebf3e5045cb2fa7ca166c042f1.nq.gz
    ├── 9c3fc78194893984165bfae152b2296b9af95131.nq.gz
    ├── 9de4f3c3378c437e8c23caa82699731eac094e9a.nq.gz
    ├── a024397e0f2bad345c5367804ba84cad4f202de7.nq.gz
    ├── a0ca43295cd35afe4e31489ab0f950048d61ce41.nq.gz
    ├── a14e907b408563a8febebdf5952283b774112b40.nq.gz
    ├── a2187cfa38798328c55d7ec3f87b990032935747.nq.gz
    ├── a31cfc13ae2d03e513da817c0906744d21c01495.nq.gz
    ├── a3d3c67e6c51a6e3c105e8cfaef51ce7b7014fe6.nq.gz
    ├── a41a914dfcd768f3e8a83ddffea636de663236ff.nq.gz
    ├── a4aa8645dc8397929f5542cba8963d64ee2edc71.nq.gz
    ├── a4b10237700408fe9388decc0382ae5d75be074c.nq.gz
    ├── a54444de8c513ecf5053820cdf2a848127c1593f.nq.gz
    ├── a59f29ab0160d1abfff3ce644feb7eecaa968645.nq.gz
    ├── a5dbfc6774414b82fe9187a6fb8a81574229e87c.nq.gz
    ├── a77ca82153a2eea789862f7a6eb8652b6b99e893.nq.gz
    ├── a7e7177c2f59fd76fa7347f69199915c45fa43dc.nq.gz
    ├── a8835786a8c2cb245948f86d8bfdb71dfcbecae8.nq.gz
    ├── aa4233966d53e598375c94add8af18fcb5fa9ab2.nq.gz
    ├── aa72d861387e8ddd37b081c93d2e79230a084513.nq.gz
    ├── ab7c7f356bc5abd7280e3592fa7be3d6b3cdb69b.nq.gz
    ├── ac75f7f3e0b690120801e6ea795cc3e9e9c960f5.nq.gz
    ├── ad83e2f36818cc81ffe68968c273067873b3f76b.nq.gz
    ├── ad995e1842b8d48af3a7bd055bb65d8c2986f1cb.nq.gz
    ├── adb9cc04be33c82e51ec74e11dbb3375b0aa9226.nq.gz
    ├── ae8c945015e1156f9c9c5cfa1c4ea7db40dc2d3c.nq.gz
    ├── aef4b3dab777c333a0701cb409314d9ae0ed2c49.nq.gz
    ├── af04c52223f492eead47f566cae3421213268c41.nq.gz
    ├── afa5e0c0cd00a1886da7bcc20a050b4fb0da5984.nq.gz
    ├── b0528e74c5a17fdbcaea2d6a2c4a031420ba2df1.nq.gz
    ├── b1a6f255d5e702c3736dbed110c9ff307e73ff2c.nq.gz
    ├── b35b9fe11975ac69b1b067ae19b8b01bce98876c.nq.gz
    ├── b5888f98a635c915dd6d9b4ca5d13420200757a2.nq.gz
    ├── b642bb1b664c91d8feedb1879b3c39fd8e72ea3e.nq.gz
    ├── b67f7df5fcb00242e7ca2d23743ad63270f5873a.nq.gz
    ├── b6e4ceba6d2e9d62f8ce85bf532100128b22be5e.nq.gz
    ├── b75b7aa5f11910c676f49abfbf8dcccd4e3160f9.nq.gz
    ├── b793e2cd8f87f35fbd12db00f8a02e0ab63631b3.nq.gz
    ├── ba5fa7aa9251f97925c75ff8edd399f4ae179258.nq.gz
    ├── c04a932329860479d6340195735307f4f9a7be2a.nq.gz
    ├── c08ee93f8403047c06cb0dadad11e55b2e751f0b.nq.gz
    ├── c09fbbb78149b2c4e7ac80edca35dd9b5a916c76.nq.gz
    ├── c0ec7ab364238577f78e07274f9be83840f354d0.nq.gz
    ├── c255f5937f241091cfbac3790ae6384a1d4b82a3.nq.gz
    ├── c444cbe880ef16e9a6684cbd9803858572770fb3.nq.gz
    └── c5b187ce520d3585979f1660b1afb89c64e482b3.nq.gz

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

[NousResearch/speculators](https://github.com/NousResearch/speculators)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
