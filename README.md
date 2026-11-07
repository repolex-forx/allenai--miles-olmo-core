# Repolex Knowledge Graph of allenai/miles-olmo-core

RDF knowledge graph data for [allenai/miles-olmo-core](https://github.com/allenai/miles-olmo-core), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/miles-olmo-core
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1be18d634c14753551961f1d44bd9065ba5b4c9a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1be18d634c14753551961f1d44bd9065ba5b4c9a
│           └── chunk-001.nq.gz
└── blob
    ├── 0077bdf650e0194c7dfcff9a05d8249a724e2006.nq.gz
    ├── 008608d85756421c6bad66c9dc7d7caa1a8312ea.nq.gz
    ├── 014b6a0948687242d8f6fafc85861de64758c98c.nq.gz
    ├── 0153d7ac2443ee0aa26cbd4e409368846d1ead37.nq.gz
    ├── 01ac61cb3758c101388a6c4563e8605ee6629b89.nq.gz
    ├── 01b43ad32af033e2a6bf35c4df2b46619745cd5c.nq.gz
    ├── 01f5122cd1a249f577b7e1976b31417d503aa343.nq.gz
    ├── 02a65a17572aa5be1c4c7cc3d824ddb9215a2068.nq.gz
    ├── 031fee9f631f5862e479afbf780b0ba869a0573c.nq.gz
    ├── 03920f488c53a00bea1364c97d50ac36cd44c14a.nq.gz
    ├── 040f8e8d459a7a3877cc4deea318b2631a5757fd.nq.gz
    ├── 041559305ec4911d60eb360e76e09ea8a2a7dccf.nq.gz
    ├── 042e3b355a163e2826678edc47cda10559879b25.nq.gz
    ├── 04d52d90b1fba6380360abe8f696e6613f8e1d9d.nq.gz
    ├── 05d9ce46bcb1e93080fef3993d2bea907b4349b3.nq.gz
    ├── 06fcc313d3d21b1d6c285d872a4fceabc550bde4.nq.gz
    ├── 0725b82bb37c2a79c29fe59baedea725202e6e12.nq.gz
    ├── 074e2caa30aa0fda7fc79698a06445e2eff1ecc0.nq.gz
    ├── 08792ebcf0beb677e2f96285fe0b3a2018ca4f1a.nq.gz
    ├── 08869555ab5a551b001b2215ef824adb85495c4b.nq.gz
    ├── 08b6669733123419397ecb50d7b9c74bdc8e64e7.nq.gz
    ├── 09358bebfadd17dc233896873ae7397a5d32c730.nq.gz
    ├── 09b7d9cab9edc23a3f9e09c66d56e7298ee7ab7e.nq.gz
    ├── 0a39a038b6675942107891f80a800985261396a6.nq.gz
    ├── 0a47c20e3f9dc68bd74b9cde5a0965d8b27d009c.nq.gz
    ├── 0ac208c739c23bf33b617f592ffefa71e3018a31.nq.gz
    ├── 0c2d4b57ddf4dedfa8cda1edb7eafd14645f9dc4.nq.gz
    ├── 0cceb87bb67784b1698f5a33bea69d92cf4f0ea6.nq.gz
    ├── 0cf2ffaece37637a07b77857def58c1b6996e40d.nq.gz
    ├── 0d20b2169f39b68a7e7746140858e1a1e8149cab.nq.gz
    ├── 0f2c90466553fbfd896c07ba98686ec00f3b1dd4.nq.gz
    ├── 0f7fe21c015e322c079f1895f1f05a8e52a854d5.nq.gz
    ├── 0fc3363013bce54e4d828285847660a27ba55edd.nq.gz
    ├── 100ff22a2156695336b4751a0b8c818c75022478.nq.gz
    ├── 1028a34d0241645a0e509a8e20fbb141e38cfa8a.nq.gz
    ├── 10e1fa0ccf8fa7643ae2d85b9b9ad35efb1f0580.nq.gz
    ├── 114a1a80c45513e74f7f22e316e65ebfeff7f1c0.nq.gz
    ├── 12b0af4bd78d15af481c263d0f9e723dba0e032d.nq.gz
    ├── 1394c1d93e0307ea1854bb2906202f6a108080c3.nq.gz
    ├── 149ee1b75120fd589db6d7dd02115a32325ededc.nq.gz
    ├── 14bd8d0e17da14f54ac4485e17870d40b1a16eba.nq.gz
    ├── 155f28686edeb53cd88f9d24b3d6c4f68780ba73.nq.gz
    ├── 1588dfbea7688cbbb9997d12303f5c49a404f710.nq.gz
    ├── 15cf13a3f357c25f0e290544e8a73dc9c0b2bb3f.nq.gz
    ├── 161dc7da5704137cadf14edfe9a192eee9072b6e.nq.gz
    ├── 1689717d4ee8c5ddc3d91f594b184c29be3301b0.nq.gz
    ├── 17240518ce7f81650b772da1662c351b0b875101.nq.gz
    ├── 18009a85e9630e168d0e9e479cba893507d3388c.nq.gz
    ├── 1807a2f9ec8135a3eb561b40edfb599c2656dead.nq.gz
    ├── 187f917d82dcd17f10b8d52d00c40bcab8d8f57c.nq.gz
    ├── 18bde2f0e929df2c52feece204604faae47d1327.nq.gz
    ├── 19598f04383c5b8d5402a0f0c160cceb9f56f176.nq.gz
    ├── 196f3a074b95598772a7590c87e5f89ac5e08895.nq.gz
    ├── 198aa85505d4d1b6381928e22e29503a6dbbe30b.nq.gz
    ├── 19995be42a32dda23a232620195615173277c36c.nq.gz
    ├── 19a972ad2cb1f2cd3037f5e9e63cb75bfedc120f.nq.gz
    ├── 1afd7ab0d4056c903d81fc5dd02c9241d823aff9.nq.gz
    ├── 1b3b797519214b3c6fb131f892bb261bcfc51f8c.nq.gz
    ├── 1c122bf16ebff47ba21e00b4e4dff63b6ce836e9.nq.gz
    ├── 1cd880fb5bfe2a3d77ddeee3aa1ce0544705b0f5.nq.gz
    ├── 1e113d0f6e2ad7eedf29513ef402507de93aaf7e.nq.gz
    ├── 1e597c6ec520a76636ed48c132b35b6b51001407.nq.gz
    ├── 1fb61c3cee809bb23ce98df7839ea038a46ce3d0.nq.gz
    ├── 1fdb1f60365b1805e1ef05a07213d1dd04220aba.nq.gz
    ├── 2047f5ffbe8fa8aeea84e556ce96a74382044e47.nq.gz
    ├── 20927d407be50a15e69e3c7170c66045f7468503.nq.gz
    ├── 209c132818b05f4b4ec982e609068bdfd3b09bd8.nq.gz
    ├── 20bfb6d675e2c2bb2e2997ae18ec13c58a72839b.nq.gz
    ├── 22056467aa33f2985c662e98c806581b18e66110.nq.gz
    ├── 223a2191cde96294ad3402f862b4b73e60bcc58f.nq.gz
    ├── 2347a00869679f2823de357e0a69ba90f8c2edd7.nq.gz
    ├── 243e184d2430bcc13a828c4000ad2f3a9d42325d.nq.gz
    ├── 247401550516b58e50f4dae4cddf8561b0e6a460.nq.gz
    ├── 24f0dc4c404a7c19cb8ca79bef49297f0cb89959.nq.gz
    ├── 26da0f1a3c0fb5e66b05dffdd1bdfe4d455c156c.nq.gz
    ├── 273fe84ef5a918e877aa4f80c04e7cf7ad0400aa.nq.gz
    ├── 276363a357eda6dbf87df8aee28b5bb41b384dea.nq.gz
    ├── 28b523caee501cdeca593b9204537c36b7294cee.nq.gz
    ├── 28df99a70205ba53f75493fd9d15cee4a05c7118.nq.gz
    ├── 291382d8f3ea21846db9d031bf44b1d0f5ba05f3.nq.gz
    ├── 29e879d1916d9be05d80d21d5f4ddf32e9eca4c0.nq.gz
    ├── 2a409fbf6c1266be8089b5024bc88ca255cbb1fa.nq.gz
    ├── 2a8a6ace891cf9639c1ee7b0ab439b57ce4af721.nq.gz
    ├── 2a91c4d7f6fb2094d8bf41065ea626f9784df420.nq.gz
    ├── 2a93071052652e9416d7fa533b287a9346c7664b.nq.gz
    ├── 2ae957a28794797921d58d1eca8c88a60e3dd0f5.nq.gz
    ├── 2ba7e6f6eb9bc9b212738d9319538c82c19c5aba.nq.gz
    ├── 2ca5a9e6a5b014d6746fd57665be1caf7b8cafc8.nq.gz
    ├── 2d42daeb0002fc7ab35e8d34332128099044f3d9.nq.gz
    ├── 2d43c62459125dcb149dcb86645debf0bc5fba9b.nq.gz
    ├── 2e2a820562f37fc4b5a49325c9829507f4a34938.nq.gz
    ├── 2e4b2fdf7f4fccb47789ff551f800173748c56fa.nq.gz
    ├── 2e8b5705ca2ecd2e56e3236b54d22156924d3490.nq.gz
    ├── 2e945981970f0545d7159b2e6c85eb07f379c4e4.nq.gz
    ├── 2ee9daab7158660c395132664c6969725c0f6a76.nq.gz
    ├── 2f85c2816e971c5d94971e90ba4fcc006d0292e1.nq.gz
    ├── 309a5522badbaec0c5c67cd4db52fe1fbfbe7e0f.nq.gz
    ├── 332451c59951759e55023c3c5d470e9e207689f1.nq.gz
    ├── 3439671dbeb8269c6f2fd985f8ca2a935cd39f93.nq.gz
    ├── 34a467fa4df1eb7aa548941d40fe5cb4999de585.nq.gz
    ├── 34b6763ac401f1ac0e31e0de59701e7068a3c1e1.nq.gz
    ├── 351cd21bbb5d0caf27ddf48efcd97bba5430d575.nq.gz
    ├── 3637303bdb41dd14cc2ff51ee5f9f5eb9b2990f8.nq.gz
    ├── 3682c1cf5503573054a39d5423b74a77751c13a9.nq.gz
    ├── 37be7799b9c8ff4780fddb5b7d3c743969a1f208.nq.gz
    ├── 37d1acf2cc7b8d1b9e48a1e737e18ee4fd48aec9.nq.gz
    ├── 381497f85c9de1943c1c12bcdf1fc1e45f969d5f.nq.gz
    ├── 3893175656a3d153305da7a2c6bf5dc4172069f3.nq.gz
    ├── 3941f5b262020b39ab21f39a0987a9794af173a1.nq.gz
    ├── 3973c24366dcc201a9939e517149960e29ee5b1e.nq.gz
    ├── 39c039bb5f3fb1aa90d68fead08e7b63d53b99bf.nq.gz
    ├── 3a0c4ea29d998c0e85ccfaeb3d536eafc55dae8a.nq.gz
    ├── 3a34cd95423cefd3e4d81c4efeb1c85e5a165523.nq.gz
    ├── 3a560c66b9a80296066320eb16bfebcb42433f09.nq.gz
    ├── 3ab27b7e284a4e4fd8eff2a00226e5d8e4bfd831.nq.gz
    ├── 3b4202f3424a3071604dad5706b834db85c46532.nq.gz
    ├── 3b5f5e529e815a81513ed206215705a20eaef9bc.nq.gz
    ├── 3b707677a9827bdbae28ecd38d5dfc66efd2f532.nq.gz
    ├── 3c7d1ad4b5d638f0d2554ff605ef9fbf8480db5c.nq.gz
    ├── 3ce803e6371ee4bdeab859d9a61f645ca08deb7b.nq.gz
    ├── 3daf1ab6055a0010d2a596d9d699b18cae47468d.nq.gz
    ├── 3dec23f64529c3e62662794e3c19ebe49d4bd06f.nq.gz
    ├── 3e0e2e16048932bfcd98a4b06d6de35b5229503d.nq.gz
    ├── 3e283d68096df9e58fe2127467ed590c5f881e07.nq.gz
    ├── 3f54f1eb35eea264eafc5d0b5199d3802f718fde.nq.gz
    ├── 3fab8b021bc7667c85500dcd089e190d0bbf8d95.nq.gz
    ├── 402b870c738ff3d67f5c61e90155cdf7a256a792.nq.gz
    ├── 4177537c03b78217b8400be380c6bc36aa930f5d.nq.gz
    ├── 4201227ca7be0ae445bd9d997499e34185c79de0.nq.gz
    ├── 423325160301be0495944c79589b953543ed8143.nq.gz
    ├── 42678e77ebdf3625a2ebe963d76cf4d9938c77aa.nq.gz
    ├── 44bd6916d80ab67a1441edbce8f8b10be5c0692b.nq.gz
    ├── 44ff86492e2ef2bd26149b77e02ce27053693488.nq.gz
    ├── 454b8427cd757f30dc7fdb9a325d19c399770417.nq.gz
    ├── 457889ff6d0f339ce9208d3932f87b8d07953f0c.nq.gz
    ├── 46142bbe0fe566a39c438d23d991ac883fa752ac.nq.gz
    ├── 4636e38f1abc2544b0258afaf95c6de25d34ff38.nq.gz
    ├── 4698e950bb7c0e195f52fc40b6988d9f08b220ea.nq.gz
    ├── 46a7fb8dce15dcfc49e326f08adbdb72c660218d.nq.gz
    ├── 4744db3db896fe9d8a25263f21dd3add6e4672e9.nq.gz
    ├── 4877015fd97b274135df13aa8ae017a5396d4d54.nq.gz
    ├── 48937ec283409eff73f7efafb0a13f39b50bf45f.nq.gz
    ├── 48c3af8af06728784db2fcbfcd7204e3d7ea7ac7.nq.gz
    ├── 493c92e12869ad0fb54b5e1b962d8f2c2fe9c5f2.nq.gz
    ├── 499a21a4d761a11517ee83167cc57fb00107d701.nq.gz
    ├── 49a48e1c15192e70178a26fb34ff1e08a6cd5fcd.nq.gz
    ├── 4a901d5a8d16050789ce57bf2d9a1999dd9dc6f5.nq.gz
    ├── 4b6bb81ec09b660dbaab6c7056bf8c523cbe4a71.nq.gz
    ├── 4ba5a4408da896a34edee4b789090e98022d9911.nq.gz
    ├── 4c11e373e756a852e5dcf99cb5d13f9743f90206.nq.gz
    ├── 4c9ef6cedbed85be4ce865f79d03e4ae5aaab47b.nq.gz
    ├── 4ca144e508db84a73ac9e040e19c541afd53cd32.nq.gz
    ├── 4cb72137418c0d9f6145a9d20b5dd582901f5571.nq.gz
    ├── 4ceb4f9233b0c3247eb3fa0ec72ab73aa4f6d196.nq.gz
    ├── 4d2722c760e672ff4a782ec941c7d4daa2433923.nq.gz
    ├── 4e11cc6557e7af301bf7e171336f4a647e065411.nq.gz
    ├── 4f21614729912952f8101355ac9204daa0eccbea.nq.gz
    ├── 4f7d8d5c68c5358f369295827d1e28f68d8b2d83.nq.gz
    ├── 4f9d32dcad074e400db6e8ac900fc081df9b2175.nq.gz
    ├── 4fa25c19fb1db260cc19b4c33e95332abefbc304.nq.gz
    ├── 502c5fa214cee5d7493e14c30c20928a8add0e30.nq.gz
    ├── 504225c94caed432cea7c38fcc3e6d39cf0924a5.nq.gz
    ├── 510d6a966c622df66da1d40095b12f0802fde7da.nq.gz
    ├── 526b6228561076dd0fe2f496232e4602f04fbaf9.nq.gz
    ├── 52abd9b017007560af0514f9f73ca8e93a456d8c.nq.gz
    ├── 53274aa6fc8bbbd220a77ca0012f2a5464d9edc5.nq.gz
    ├── 5399cdf68bde64a5728003bebaa340c757f389be.nq.gz
    ├── 5430a36f0048db983711cb0b73dbe034548e71c7.nq.gz
    ├── 54457833301041527fa0113c027b8e0497f919b9.nq.gz
    ├── 55ff1253dc570ad565a9ba1f2b18a1c44767aac1.nq.gz
    ├── 56ddbe55f5cab02438d75d3b3a67a9424b224881.nq.gz
    ├── 56fd7005b626f80c0c9736e89f9cb62813c2d185.nq.gz
    ├── 5772eae844e421f4e053721634df9e268bd07f71.nq.gz
    ├── 5775877b59eb66d8f3e7c83e44b0223df8a782a1.nq.gz
    ├── 58204900cd8544d4296e92044241817ff9ae0e83.nq.gz
    ├── 58219deeb25b4fce559b88e17741d67d86cee784.nq.gz
    ├── 58926adb3d8c0d05ce8098940ae8b812df2d936c.nq.gz
    ├── 594e78ec79ea8990f82a9add7b813a392d35a99c.nq.gz
    ├── 598a556be40a7eaca1955ce2f83ca63f17f328b2.nq.gz
    ├── 5ab021b5af3782894fda760edbcbde111edef90d.nq.gz
    ├── 5b2abaa707bc464b1eca564f74ee4c9502ee7a0b.nq.gz
    ├── 5b8c1e7b5c9d761ce6940ebc02e896e00fb8c6c3.nq.gz
    ├── 5be8343002850ca30dcde749e0573bf2e8ffa0d9.nq.gz
    ├── 5c990870d45e7fb2c21364d6136011c208185332.nq.gz
    ├── 5ca829567ec52a24f0644a6f184223b0950d49b1.nq.gz
    ├── 5cbfec29b4b38ca13d74c8581ee42315a5e399f3.nq.gz
    ├── 5d060b41b4ad9c2ca7a8d77078d0b31df98280e6.nq.gz
    ├── 5d35039f0a5eede4f220ce967326253ecc44197c.nq.gz
    ├── 5de540f12e97bb446455e64a76473817fa02f04e.nq.gz
    ├── 5e88a990a936dc1b79eb8fa6afb4496a2584fcd1.nq.gz
    ├── 5eabcc86a927dec1367a39fbbf9c5a5ca9ddb110.nq.gz
    ├── 5ecd58cca4a896eb0266f6ede8133dd87954506e.nq.gz
    ├── 5f0f492788d55a84fc8a325aaccf169d5a93cd3f.nq.gz
    ├── 5fcc34d02cac016c90495292d62877318c6c330f.nq.gz
    ├── 610f5ddefba26dbe9633df2bc21f9402caa22f10.nq.gz
    ├── 6181b38430185f30d6b996db4060fa54e26434e6.nq.gz
    ├── 6202e5eccfb8b3f16edaf3993ff1bdf5720a2680.nq.gz
    └── 62f107b819fa45bc4a4c69238f9fc0747e81c4f7.nq.gz

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

[allenai/miles-olmo-core](https://github.com/allenai/miles-olmo-core)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
