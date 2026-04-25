# Repolex Knowledge Graph of apache/airflow

RDF knowledge graph data for [apache/airflow](https://github.com/apache/airflow), parsed by [repolex](https://repolex.ai).

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
lexq download apache/airflow
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0eb7862730c68d25ebbabf1988d66d50dd988bb0
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0eb7862730c68d25ebbabf1988d66d50dd988bb0.nq.gz
│   └── repolex
│       └── 0eb7862730c68d25ebbabf1988d66d50dd988bb0
│           └── chunk-001.nq.gz
└── blob
    ├── 000b986185c889ed6de6093cbcaea66d24f7bd6b.nq.gz
    ├── 0012cdfa65740f3f55e100f584bc2404b3f96453.nq.gz
    ├── 0188c0b60f352cd6277a976d07b56551978fb9a6.nq.gz
    ├── 01ae3939c49bfd7c8c1086c69775c098dca2485e.nq.gz
    ├── 01db1aa7cb567c506f4d6161a35368e3eb6dfd64.nq.gz
    ├── 01e01dd05fe9695f90c545242f590bc57130b864.nq.gz
    ├── 03ecc669b358f2264db3be7dbea356c665b5ae0a.nq.gz
    ├── 0498d21d030ca9a74ff0161f8e1f84403ef9f562.nq.gz
    ├── 04b0d7f7135c29045a667175718181548696b23a.nq.gz
    ├── 04be0d9fb0e77393dfdbd9af6ad2fccedafaa188.nq.gz
    ├── 0543cdee2da06d4f6de39b1fbddf1ad712a0e959.nq.gz
    ├── 05985961b59a6969ebc3af9cf8df55679ac6785f.nq.gz
    ├── 05dceac20a1fe067166154f90881c0f6d55b24eb.nq.gz
    ├── 06a83e3768baa994009392df64461c507e6b3af5.nq.gz
    ├── 06de4e8661cb74316ddb8d9eaef11282cc3eaad3.nq.gz
    ├── 0777defe24fdef331fb1c7bb528fefc8e8f42664.nq.gz
    ├── 08e5ed3bda39d3e81e11187dbb813670b7c4e668.nq.gz
    ├── 08fcf5c93de1d0eeca9244d7bcefb78d2f7eee73.nq.gz
    ├── 0ae22efb3baafef80e268437997d7283249d8e7a.nq.gz
    ├── 0b8ad2f4796a1cf88cd1a13fb8e0453fc294f0f7.nq.gz
    ├── 0bc7cbe9af4d9b55c835898c7c173d4252355037.nq.gz
    ├── 0c1178779c80dc55303ea1b4adaa016075c76ba3.nq.gz
    ├── 0c418b56746d824c2d98f37af03cc0b209cd7415.nq.gz
    ├── 0cc23b90b084f3fbea91cde4afc409e5f344bf31.nq.gz
    ├── 0dacaf23e1651e79fd12a7809c631bab1a54db3e.nq.gz
    ├── 0dd2c394d4e2fe7c89f7b01c2e3a385195b5d6ab.nq.gz
    ├── 0ddbf987bf822c5f5c5550940e8f4e86c85d5b2e.nq.gz
    ├── 0de5aa53cd3abbe7fda45ca062cab80e279e5f50.nq.gz
    ├── 0e0ccdf9bc96dd976583a1617f57da2933a36699.nq.gz
    ├── 0e156deb5f61d18f9e2ec5da4f6a8c94a5b4fb41.nq.gz
    ├── 0e6e13dc2f0202d824c20c882bfeee36e9c9d630.nq.gz
    ├── 0ec143573ab4485658690b7ce50a5bddc1b132a7.nq.gz
    ├── 0ed9bdbb0d2dcc54271f25a33026cab988c72ae1.nq.gz
    ├── 0f0cd6344c384afa0dc050ce868dabd55dd4cf65.nq.gz
    ├── 0f23aab333636f4a2a0501eaee9e36e79a03cb11.nq.gz
    ├── 0f6f5da5df352769af22200565f9d79c0a6fa4e3.nq.gz
    ├── 0f9df43a020a45429263f95fbc87ed02cb7ea8cc.nq.gz
    ├── 0fc63dade02c8babf5fd2a2ac88612bb27a91384.nq.gz
    ├── 0ff4d058142353707cb1e86cd676b937d562ad77.nq.gz
    ├── 102f67825775bd5ea589c9a663fcc61b914ac5c6.nq.gz
    ├── 10bc0384ebb479a75c8a87fccaab16db1a9df757.nq.gz
    ├── 111dfd473f704b056b4509764ce57011f19d9734.nq.gz
    ├── 119df99a7cc19b786040afad2dfca3123eb88683.nq.gz
    ├── 11c24fe36cfd8a4ef7cdd2affd0bebf0d5844ca9.nq.gz
    ├── 124c18c70f5a2afac88570d83864fa759273b04b.nq.gz
    ├── 1386d6de1f824b2bee95428392c24a497b3521bc.nq.gz
    ├── 139e451c14975adbebe5f9f86aa92a389cea0a59.nq.gz
    ├── 13b49f908df8947b5b8297faa9f7a33dc166466a.nq.gz
    ├── 14149281bb3782ea1a27569ab5d1780937e6fc57.nq.gz
    ├── 145892c12617fe412bdead6fa4d3f3f9c82bc5d7.nq.gz
    ├── 148101b72f3c7f10b3494a7c4686315522c668df.nq.gz
    ├── 156ada8e9071492fffe7ef2b14a595cb12cdb678.nq.gz
    ├── 15d23d9fa6586936d56843463726fdb5692e5f06.nq.gz
    ├── 166a6ded314ca4aa7ee6338aae808584d3d51ed6.nq.gz
    ├── 16948d41e5c9eb84f0a3f861f2dcc72b01b04e66.nq.gz
    ├── 1715d008aada72f3157e7de8b68a026d1efee42c.nq.gz
    ├── 17b8188ed0708b26a690026de642135f57eb688c.nq.gz
    ├── 17ee68f09cca9d2bcaf42b04f46f32e0a273467e.nq.gz
    ├── 1889b868f708aaaa9a29a3ef2613c8436b8de384.nq.gz
    ├── 18d723c005a4860a403bae2088d0de70b2596074.nq.gz
    ├── 19901aebf3de84e85256013272990ad46cab56ca.nq.gz
    ├── 19ba93fe743a50cadbfdda32fd3c18b4dc9d89cf.nq.gz
    ├── 19fc2b45af7363677aaf5ad76f9754697f8d30b8.nq.gz
    ├── 1a2312f4147cf6458a780cfc302459887b8d8382.nq.gz
    ├── 1a3d7353c5a800203b807d764729d6d875a9ff8c.nq.gz
    ├── 1b572769fd2822ea256af455109b0a784f2b7298.nq.gz
    ├── 1cb51e53795af9f484f921517285a660b82f70eb.nq.gz
    ├── 1cdd0e5e481ab10836645299db16c3603c77ff95.nq.gz
    ├── 1d487e845ca458ccca4699e8066d4e6a4ae382e9.nq.gz
    ├── 1e4c038497d01f5d9363cb18ee95d8acfe57922c.nq.gz
    ├── 1ff803198b1768422cb1b5506b714363383a8477.nq.gz
    ├── 212570142dd7a148ca807220e9b435802ec56859.nq.gz
    ├── 2134a44641c5222c71cf882a9e9b116430bdedb9.nq.gz
    ├── 213ceacc408aea21a977e55f6a4d69d37d1ccef4.nq.gz
    ├── 21ddb89af084472c1fb60b444a23d5c1eacad672.nq.gz
    ├── 22312083d8257c08b4ac088093a26edb6d5571a2.nq.gz
    ├── 225d24f0d85f02a4e592f95643f9f7e337c02099.nq.gz
    ├── 2260e7b0e4f86050d1b0a6266c55b9ae589a5299.nq.gz
    ├── 246e8084c037325be8e5a925bd1d8a30e1c60cab.nq.gz
    ├── 24fa2e4013464125ff9d9d8ad2ee434638626905.nq.gz
    ├── 259648709dcacb395749b0876f9e089bdad8d154.nq.gz
    ├── 259fe825837a613a389b9e9f46966fb8145f16fd.nq.gz
    ├── 281ed51bf61e3e7c10800c067ab68d278c9274e0.nq.gz
    ├── 282f9fdfc6e890e9e024425d58e6b331084e3c88.nq.gz
    ├── 2834ad45568568209729db92277b108d0ac319c9.nq.gz
    ├── 28977db0d00b4d664b3335e3c7e3603ff7514117.nq.gz
    ├── 289f64ff6b78071e3b6398a81e96ccbb0f0c48e5.nq.gz
    ├── 2a1f1c1f0dde5b0330be3a4101cd8010a7d45fc6.nq.gz
    ├── 2ac511bb1037847fa207e2fa57bc922169faf21e.nq.gz
    ├── 2b11d91363697315228ceb5c6e52021c98397de6.nq.gz
    ├── 2b21459ff930100afc487291fb3cd8852c8b61db.nq.gz
    ├── 2c5a462cc90e89c88a67eca8555bc69672e4b7f0.nq.gz
    ├── 2da7cdda082752e79db6432d703b900f3b1011e7.nq.gz
    ├── 2dacd6c5db312fb03430b08fb5c99ac61f284719.nq.gz
    ├── 2e6d4269fa71cd32a0111a33e578fdf21e700b21.nq.gz
    ├── 2ece718e8454914996fa6ff881a5fb7c2d6700bc.nq.gz
    ├── 2fa2541865ee5a2901cc33d9eaeaaa89d6f42613.nq.gz
    ├── 2fbd516e3f94a674ce49f5d4bafb919736474fa2.nq.gz
    ├── 2fce0194c9d5a27fc23f064831366ace90819ac9.nq.gz
    ├── 302c355bacddd240dc2a83630069c483d4cd3028.nq.gz
    ├── 30e1d4738cce5d752572bdd1f04947292eebbec6.nq.gz
    ├── 312251f8d22cd4916ecefe8100ce39a5a5016e75.nq.gz
    ├── 3146cd6cfb4ba2b9a8348301684db18b7b4761a4.nq.gz
    ├── 31ce110413e314ee9b1f1dbc7fbd6f941b67adec.nq.gz
    ├── 3422b07c20c13bec37b050e8e7bac49ad9287869.nq.gz
    ├── 34fb7538c2b46dea514bfd7dab8a41a5d5371c77.nq.gz
    ├── 352755e4057e7a1f7e7a24c91f805e59fb0e5b8d.nq.gz
    ├── 36755de744d77a287bc87974f81a19bc1ac35b84.nq.gz
    ├── 3727903c9e52c323816b0970f32a62e1b76dd5c4.nq.gz
    ├── 37d59f0d34c5ed39b3c67e00a688548d6be81abb.nq.gz
    ├── 37d885dfc4de36e1daba7f4f47e323c7d757fa5f.nq.gz
    ├── 37f9a4c6c8584208825164979e2b9c6eaf2a1642.nq.gz
    ├── 38ee9000af0fa162229e9269d4d8996987dbf6ec.nq.gz
    ├── 39214288e880596a81846f188f2b77aeb26bc823.nq.gz
    ├── 3b0214a06357ea772ced7870618a67c3c1786519.nq.gz
    ├── 3bc5a06d0d2d67fa52445b6fa795b80cadb9077d.nq.gz
    ├── 3cec13a16fecc533712ff958d2c52800b718c911.nq.gz
    ├── 3d5c7a42b248ad6c665b4118a7a9f4d62a7cbd35.nq.gz
    ├── 3daa6e2b7df5abeb3c932a782b2a85ae023e7fb2.nq.gz
    ├── 3e7d2db6f328ea03477841a42f04e446cc555da5.nq.gz
    ├── 3eced28895a3582a7a8c476ad835a8616dc36b3e.nq.gz
    ├── 40e1b362e8e70279adcd19006dcf7fcf5fa603d2.nq.gz
    ├── 414b52fe5b43db22ea66a1cef9268844a2579a8c.nq.gz
    ├── 41cca00e839f4c111115c2779ee91b7fb69b9129.nq.gz
    ├── 43180cc1318b40436b68d620e095c62bd4c0a0a8.nq.gz
    ├── 4343cb3213184b5a36f5a6116abd3340d29aac28.nq.gz
    ├── 44214535034ea9ec69884053dad385f0063f42b5.nq.gz
    ├── 443d3960fc57f7b8e2eee370f0df90420f1cf59d.nq.gz
    ├── 448effb630c2f2082d58cba50105e6758adeb519.nq.gz
    ├── 4517a8a0b6a6ed0615cacc2084e50384e57f8d24.nq.gz
    ├── 45f7fba9cce15e73208c7ee081394d0e064e0ab7.nq.gz
    ├── 463d63a967fbed338e50e262552c1013c0da4e64.nq.gz
    ├── 4760be2a6220cf545129b233e20574f2a7bb630e.nq.gz
    ├── 476ee1fb77d829994f5f551b0afed5c3c44fbc7b.nq.gz
    ├── 47de416077a2dd0a4049128b6e06c97c4b097403.nq.gz
    ├── 4a1dfb620aa87b790969554d8674dd1580828a8f.nq.gz
    ├── 4a21eccbbad657de37602bc0cccb202df3e04148.nq.gz
    ├── 4a64749140c64c83fe3a9df18ddadd260cb9dd71.nq.gz
    ├── 4aa4cd260a0a391578a006b8d08c7e8bee3afbbc.nq.gz
    ├── 4b232fa1aea18a67a0fd2478cd7b1481001fc024.nq.gz
    ├── 4b2ba8f4619827db5e4e0d460659e08acb47109d.nq.gz
    ├── 4cc6bc450823af50153454e93abb234a77199051.nq.gz
    ├── 4d601e1dc1521cc49622f37000478c71c3f42182.nq.gz
    ├── 4e19ce0fcef113ba7718e030d954ed6300647794.nq.gz
    ├── 4e9bb9bdc7363783bd81165381c3a95a30f6bfa9.nq.gz
    ├── 4f887c1cb36d717d16abf29703f6895092f874a8.nq.gz
    ├── 50785d7362d7af075daf172e8416648ba560531f.nq.gz
    ├── 50b05ff4618ceec060143dfc7931fc46198941e9.nq.gz
    ├── 5167a7a7b1a7a602853c05e756f384ad6557bfd5.nq.gz
    ├── 51c382561b94e734716095665a0711aa56d6dacf.nq.gz
    ├── 51eef0cd3c9e00b8e8f4f6fa68d68f477a844f84.nq.gz
    ├── 531235f93ef61c2d61f8b08c352decc563829782.nq.gz
    ├── 53175481294f30db862a3ad5d1e7b21cfad0f89b.nq.gz
    ├── 5422aa3dd8da6026e64caf508a589eb750b58c93.nq.gz
    ├── 5455fb5c5137e112f9c6e784ae0f761b3a9ee3f5.nq.gz
    ├── 54f84c876eea7e96b67045a38bc90e0090ad9dc9.nq.gz
    ├── 5526604a6936e7ab3951a601e63f6107281cdecf.nq.gz
    ├── 55469c2007027b9c3a9130329ce8343ceb825f15.nq.gz
    ├── 5644304d5500bb3bd707d036598d24e53908a734.nq.gz
    ├── 57994fa2fe8609912919a5570eb614670cc85eec.nq.gz
    ├── 57f9aeaaea927d1155cbe8d0fb5eb3ebeda03e7c.nq.gz
    ├── 582fbc69a205475aeeff1fe384c5ff077e36819f.nq.gz
    ├── 586844fd8ca18ef03e11e3152450933f0d845da9.nq.gz
    ├── 58ee461f81098b151dea9414445e6f1418b52464.nq.gz
    ├── 59b9a25d40e6841958dfcc34c1f4831f3b47d5c3.nq.gz
    ├── 5a593a6a6e571f78fd5b46cc81d5d7395d9eefa4.nq.gz
    ├── 5ca58e436908cb84457299dd4704ad1bd6737022.nq.gz
    ├── 5d758a76b0ca9b3f5e377559a9b591dfab3a3455.nq.gz
    ├── 5e2a28db0782fd143ffbced33dd85d7d58360ef8.nq.gz
    ├── 5e3fa97f0663fcc81fb7f2194d62b4cd5acdcc06.nq.gz
    ├── 61092ed0c7849fc9c221c5d5463c62734937ffed.nq.gz
    ├── 61135953cb4cc22c387311557454e9d3be8f636e.nq.gz
    ├── 6274d5ee865281fdc33f35df919ea86daecf3baf.nq.gz
    ├── 629adfa9079643d9989ffe46a8415b7df8d829c4.nq.gz
    ├── 62af9db9b02eb0a4d561d122429923ee2a78ed33.nq.gz
    ├── 64cae86db6b8a3c472c1607d68ebcde43b099d31.nq.gz
    ├── 653a9c0fd1fcd4849217ce831ff7143eda8f6c9b.nq.gz
    ├── 653e15ba4fa3e022a272d99f3898c2fb89d62c52.nq.gz
    ├── 65a2edd74a08e797618ea58daaec18d0203c7698.nq.gz
    ├── 6623b1ca0ea8303851ecc4dc069b81754c4c3c89.nq.gz
    ├── 662b3b873d4beeae8056e281cd5e1197ce24a4c4.nq.gz
    ├── 66b4c60c207161a8f2c40cd19c5d3c68873b4f2f.nq.gz
    ├── 6752bdb283504e9466a22b51fae36b27df11dfd9.nq.gz
    ├── 67d160580becc8dcbd1ef1d28c300c5d2410f98a.nq.gz
    ├── 68856f8732ab40e68a56edfd3805ab0e0b81fde1.nq.gz
    ├── 6887fa906b6fc3c4cee60982145d8acbfaef02d5.nq.gz
    ├── 68ff62dff8b2479ef9e96699c4a008f4caabc027.nq.gz
    ├── 6910b66ee1f774141dba1430a1ac25c55bf09b23.nq.gz
    ├── 69dccd08a15eb2dba68dd6d529900b4403ffbabb.nq.gz
    ├── 6a29982ceee4785fd8947d66a6f3de0b91dc5707.nq.gz
    ├── 6a775384ffbeb899b18f08af9fc35b613c597203.nq.gz
    ├── 6a9e6cfd50a396db0fd23f2d4ab0eb04db599c56.nq.gz
    ├── 6b1599871485800a9e9df41720fb91ef1e254991.nq.gz
    ├── 6bb71ff2a7da543e20a926db31860f33c3f828d3.nq.gz
    ├── 6c84fcd001d69d229fd1665ea3f67a1265bf7c29.nq.gz
    ├── 6cdfad526ff0bcbbf9c2c6f216cb5b8db533ef8c.nq.gz
    └── 6cea26fcce134aad4a75609eba9856b2a75e9742.nq.gz

8 directories, 200 files
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

[apache/airflow](https://github.com/apache/airflow)

---
*Parsed on 2026-04-25 by [repolex](https://repolex.ai)*
