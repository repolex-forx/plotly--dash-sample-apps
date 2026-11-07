# Repolex Knowledge Graph of plotly/dash-sample-apps

RDF knowledge graph data for [plotly/dash-sample-apps](https://github.com/plotly/dash-sample-apps), parsed by [repolex](https://repolex.ai).

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
rlex download plotly/dash-sample-apps
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ebabf377d3be3d08752d53dfd04d1a59d7d164f1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ebabf377d3be3d08752d53dfd04d1a59d7d164f1
│           └── chunk-001.nq.gz
└── blob
    ├── 00a8ec05e7309a68e42f6c55eaef75f5da535b02.nq.gz
    ├── 00acb46dc950ef286b4a0feb3aeaefa4f9961d7c.nq.gz
    ├── 00b474e9c7fb87ab0118a5ceaa3b48966afffad0.nq.gz
    ├── 00e0dc2a12303a836fd704f36db60bfd774548f6.nq.gz
    ├── 01e5f460c8b042024ca611b9ed23839d3ec154f5.nq.gz
    ├── 023b24015c8a22665f85b89b95880585fb3b73a3.nq.gz
    ├── 028fc85aa0fef8be0ca1b7ccdb7f3249f94223a0.nq.gz
    ├── 02aaa1b32d64abb35c29dc7bbbb0bc1a307c2ace.nq.gz
    ├── 031b8afbea299e2f5accd9386dac591f9a3362f8.nq.gz
    ├── 0320f44a101a62c6f0716b553961eed3a85bfd5f.nq.gz
    ├── 040cde17424f9bd58cec6360eb2d1ace958f0634.nq.gz
    ├── 04c2b72c692d5b6e0260a814cc32037a88ed31c7.nq.gz
    ├── 0615d8cbcf1f0c76ded21173ed7113eeb7664c5e.nq.gz
    ├── 072e3322225e64354bc9a7e6b9f4f6c9e46a9cc5.nq.gz
    ├── 084ec0f526fbb2b44978268fedcdaa06a4cb46d7.nq.gz
    ├── 08dd3530895f2614bb0f386532524fb063564334.nq.gz
    ├── 094299ea52572f966fdc92d07680ca19e7832b65.nq.gz
    ├── 0954827d50a1d6bbb7aa5eda07cbf69f3df76328.nq.gz
    ├── 0a0118740937f3776db9dde455bb8b519a764f66.nq.gz
    ├── 0a6c2133cb07465b6aa72144287a35d18b97f817.nq.gz
    ├── 0b0395cb7d9906348cea2d206313eebc18e6d955.nq.gz
    ├── 0b3d50f4899508956ccbf1d5b80aad46ac7cf236.nq.gz
    ├── 0b892823904bed5ab744a5e3c694bd984be3eb02.nq.gz
    ├── 0cacc3254d438da961096433b31eb9f7af26ba8e.nq.gz
    ├── 0d03c9eec8897e8a6a960bd2fac967de30b32abb.nq.gz
    ├── 0d9e6953507f76285de76e58578991e5abd3480f.nq.gz
    ├── 109636f3fcb3f27fe929caa5a35b04932c2db740.nq.gz
    ├── 11409dd6f12bc8bcdf62400860c85b7b1e7a7f48.nq.gz
    ├── 127aac894e1da912e3d8af8134c576963ec7caca.nq.gz
    ├── 15687469881913a180657a2b652b15b918c8e839.nq.gz
    ├── 168a5e18f1d163af3a6eba805815dcb8e758e1f7.nq.gz
    ├── 16ab6057805a67a7afdb13ddebcf9dfe54e54a65.nq.gz
    ├── 170396f0f8a484acaa69bbb369ef9379801caed1.nq.gz
    ├── 17387be770137fd327020ddc241133f5a5c52547.nq.gz
    ├── 177ac1b015cac41063decafcf80a97c350d32e22.nq.gz
    ├── 1788921cd4bb9c7b47761b9723bd27b8c1469ca1.nq.gz
    ├── 182743302e801adc1e8b2c151383f96866f6b0fd.nq.gz
    ├── 185428ae7924f1d12b294657f0cd7607bff1e752.nq.gz
    ├── 1878ea30562152d7c22ac75effc10e0fc2965175.nq.gz
    ├── 187b5fb012b6f32da7f33149b98f8c2560141ed2.nq.gz
    ├── 191ae70f0bf54898f6d5e20ba02eff6849f77dab.nq.gz
    ├── 192a1a56f2a4c2260e3f0ff976b039da8ad9c30e.nq.gz
    ├── 1976288ed176388a86aed12bf163c1a1186a029b.nq.gz
    ├── 19d60e85a85c5a77084762cba5a88a1a3a846422.nq.gz
    ├── 1a1fe2421ffef8fb9cc8f3706ff182999d1a0da0.nq.gz
    ├── 1a5ee9269e7fba1b006b54081cc281be08abbf32.nq.gz
    ├── 1a7dfc5b708c3bc90eec652cc8d6372a1ca70259.nq.gz
    ├── 1a97880031b3a1ea80a07cbe82ab65aecb51b3c9.nq.gz
    ├── 1b6fdc2cd27f174bfc0492dc39d7aef725ade096.nq.gz
    ├── 1de517266a96f8e4e5ed04067914bdb0d3bb0bdb.nq.gz
    ├── 1dfd89678bd15132abca09382d9fa4a2f774f6b6.nq.gz
    ├── 1f292951feb2373eedbc0f79c42bd19a734405d7.nq.gz
    ├── 1f6660731cdf8c1435ad45c8e0c037d266508822.nq.gz
    ├── 20e9a55230987a099aa84e008edde35a50103ee0.nq.gz
    ├── 213755d7d42d4df054a44f00ae1bbcf745e408ea.nq.gz
    ├── 21ceafdf9074fff6a5eec9916ec0ab41e9f07d3d.nq.gz
    ├── 21d62f83839e62980bb6e3be6e18ee5ba7b1afae.nq.gz
    ├── 2259f3f851404319573abe99b637e76dab417fa3.nq.gz
    ├── 23bc10bfa18af1723c00c98aacd55a2eb91f59db.nq.gz
    ├── 24df494f864fbe80df0fa0bc4410039f61a154c5.nq.gz
    ├── 25422dea56d57ddb0348275249baa2e731770760.nq.gz
    ├── 254b24eedf8dad7148571dd1c74e4251d2712573.nq.gz
    ├── 2564660a0f299033e585b6339edea23da861f6a2.nq.gz
    ├── 257b314f5fd25cbeb7257e1e2028d95ebd5f5b47.nq.gz
    ├── 2609ced2df817e3da248323e9458bd616af0017c.nq.gz
    ├── 26ad7dd25c4aa1ad08b61fae5d38e7f258b4aaea.nq.gz
    ├── 26ae9bd3fd822f6b1f8a178eb20a7119465ffc35.nq.gz
    ├── 26fbb7aeaeb53d3d76233416966bf8a2be3c5dc0.nq.gz
    ├── 26fd6e54ae0d6bfa2074e9ea3d3b730ceaa415c6.nq.gz
    ├── 270131a4f22d95c54a0cfd716321568b027320a4.nq.gz
    ├── 27392dc110bc40614a8e09e27d84355dbb73961c.nq.gz
    ├── 2847ce70018b79a758a6e35fffe29773a63fd00a.nq.gz
    ├── 293905474bffbf72f8977753da4793e93f41babd.nq.gz
    ├── 298d3ebba8ccfd45c3ce972c3be85d680ed04729.nq.gz
    ├── 29a4f0d282dc9b3811cf959a4d1a153e0bb396af.nq.gz
    ├── 29b0cd9b193df0471314a30586d13059e700a594.nq.gz
    ├── 2a48322ce2757850156160b7da04eeb13eabebf3.nq.gz
    ├── 2ad7efb11197f21a7fda73af51b1d8048d6e122b.nq.gz
    ├── 2b0feb806949fcd7dd96297f81e6e6eea120e9c7.nq.gz
    ├── 2b8860217d75989259baa3ddd7bb313db6bcb163.nq.gz
    ├── 2be89c75c94e27e57a844c40a4adfded260b674a.nq.gz
    ├── 2c44b8f987eeff065a7d8ec90e601c6dae77955a.nq.gz
    ├── 2cd5a735969690634b2bdd5d7aad4f7677111172.nq.gz
    ├── 2ce839b772780dae4f9efde898590f99d9498c86.nq.gz
    ├── 2d12d16004c0c6ae9fa34a5bbcd6a5233567f815.nq.gz
    ├── 2d1cb691c6eca019cefe52dba906146037404569.nq.gz
    ├── 2f6d17ff939bd6d14250c67cc4a98501576a6119.nq.gz
    ├── 2fb85142dc8572bc15ccca8d7b8d57beefcd9265.nq.gz
    ├── 3073ebd2e66121f2e5c238968096e403f5c9aa84.nq.gz
    ├── 30dc161dabd43edd0707a52a9648be9382d4f812.nq.gz
    ├── 324b7f7582665b1b333c763b2bfee077971b72b8.nq.gz
    ├── 32bdd33960c60d012fc71b5fd80a7ccc24d3b906.nq.gz
    ├── 3302b5be2ce6d245b5f60f49d225181ead5c0661.nq.gz
    ├── 34c1089e5959412588991b1a1ff49223b5afec77.nq.gz
    ├── 356b8390637cdd9a2345d81759f506630f24a256.nq.gz
    ├── 3598c5308f1ac32c41658d09b434051e6d88ec0d.nq.gz
    ├── 3606b996ebf98d0d121694c6959944fed16578a6.nq.gz
    ├── 361392da6ac80b88f619f6283cdc2a16173216cf.nq.gz
    ├── 3635758b052741aea0c9b5bcd004a1aa37e1893d.nq.gz
    ├── 367022b62876c35cf474ec60f42ff4ff87ea85d9.nq.gz
    ├── 36b9ec11451ed97aefe90bc668a713b75dbe077e.nq.gz
    ├── 371b4d142086f8f3ea62ecfaa7d00ae616fbb80a.nq.gz
    ├── 37a43ade8a5e1045c04bdf36299195969b2b785c.nq.gz
    ├── 37e9d481b9a385f5324b6f72298d212f3ae8d4db.nq.gz
    ├── 38371ebbf8c6119887533302aa6d60e5d453712f.nq.gz
    ├── 3938a289e7a5d9f42e4c2d0bae4c7cbde6698685.nq.gz
    ├── 395572ef66a0889842c3b878ce7d1f34e472e1ea.nq.gz
    ├── 3a0e2e8f0bf459656721243b69d73d467ca4ae4e.nq.gz
    ├── 3b1a652a193a2158d29d713f0ae1d157ad3aa35e.nq.gz
    ├── 3bd978ce03f5571ee2c0521d05c92bb27ef3f7b3.nq.gz
    ├── 3be6f656dae743beb7b365222ce68c5bd1ee3851.nq.gz
    ├── 3c6127378d811463c99f4555b7e636a61b16cec6.nq.gz
    ├── 3cb9829e636bb76df8ae11c20d35aaf7fd6eb04c.nq.gz
    ├── 3cdecd8723d5b6f13f1c7f90cf81bffeb3d84ef4.nq.gz
    ├── 3cfe8bed8d82db06df366f68ed71f1280ad2f082.nq.gz
    ├── 3d446bf5e99a465f3b4620ba2fb039173fa58be8.nq.gz
    ├── 3dd09ca51238d70b85161daa16a428183c253216.nq.gz
    ├── 3e42ae9772487dc4ecb9a6d36e6a438c1d7cac98.nq.gz
    ├── 3f6454afff773b89e9aaee165400517e1c589e81.nq.gz
    ├── 3fe4bd1b5b2d8529b8d63bdbebe2a7da9f13d9df.nq.gz
    ├── 4025636255d78c007d0b1d708bf257394d768e38.nq.gz
    ├── 402772fae781d88d71ec3a9322ad88db6f21d8f3.nq.gz
    ├── 40a0a23a903129c79cc3cebd2c6019939361630b.nq.gz
    ├── 4132b9d5dcf3cd3a54b2116c5355a290052b8059.nq.gz
    ├── 414270715c9811808b4c1d0e33f268e4a196fbf6.nq.gz
    ├── 41d676952052a90d6154fc7bc26b3dbac7fd7e4f.nq.gz
    ├── 41e8e8e6a68819d101a0aaa0c8325b987c8720a2.nq.gz
    ├── 41f87225e04e1c2818eea4aabae764e4546d8be5.nq.gz
    ├── 4221e5a4361ab431edd604bc5cd08471988f049a.nq.gz
    ├── 42bcdbe5606cfc75ccbee1cf13c0fc46b469a422.nq.gz
    ├── 42dd9505a0f29a7ddfa040d78567d4d7f0f90603.nq.gz
    ├── 4302199bfc66beb341345fbc390d83e6a0dc9b2b.nq.gz
    ├── 437f2f39992882b7665ea2aad7c1a1118b9f7e4a.nq.gz
    ├── 4446e8e08fee5421164abaa6d8bf48daca095672.nq.gz
    ├── 4449ecfa00777fd1896597bae720681128a0e21f.nq.gz
    ├── 44faaa97226870813ea6aecceafd31c11aa35e64.nq.gz
    ├── 44fbeec5038dd0893ebca3df9f5edb4ff305266c.nq.gz
    ├── 454576da30a680c5729e1d845bea52f9993b53f8.nq.gz
    ├── 459875da3da9d153156334dd4ebab3427a8c1422.nq.gz
    ├── 461100b4374031217699fe33e68f14482e0bce5d.nq.gz
    ├── 4808b15c06172302729b2dcc0ef7dc29b3d62c0d.nq.gz
    ├── 48570998b52929fca4fa1ed88c23906c97e3f8d4.nq.gz
    ├── 485f51f2c75908dc20353af9a6ecca0f3a134b9a.nq.gz
    ├── 48fd9b458b67d12da7c0d1ea35dbdc29d1c06de7.nq.gz
    ├── 496601dae3d7b0fa577b273aea3f1ed0c6e0be31.nq.gz
    ├── 4971eda45d5e067630caac956fdcfca2d7ddfe20.nq.gz
    ├── 4a372f2dedd4cac88c11f834690ab46c16bba2ab.nq.gz
    ├── 4a57224b30ab80abcf87dc2b46a7429b036aad58.nq.gz
    ├── 4a6cdfc74fabe8ecaa98d4521e41bbc32635bed0.nq.gz
    ├── 4a96ecf2f9961513d18d64101f48e3a4201d4968.nq.gz
    ├── 4afb571b54fedf25167fa2fa2d9b12fbd2a2bb66.nq.gz
    ├── 4b1432043205983dc658350f8a0453347fdf4df7.nq.gz
    ├── 4b965ab4fe5cda2d384e4dd816eb79fbc1f3f2a1.nq.gz
    ├── 4bfbe675263b236d0efe355fe12b3a10e632ca37.nq.gz
    ├── 4c6a226f57c6847bb80ae9122f82606ab816af7c.nq.gz
    ├── 4cba17814d5af1929a4f8284f9ace5d3fc31b0c3.nq.gz
    ├── 4cd6257a3ce95a03fade1106f69ad2ed56caba66.nq.gz
    ├── 4cea3a1e57621dd3ab11eb5ec9ff77d2847accc4.nq.gz
    ├── 4ea1360ee530039acd827dd581611adef231033f.nq.gz
    ├── 4ecac3bf641a506c505a93b1c794074a489841e1.nq.gz
    ├── 4ed90043ed8b5fe69baed1b073d6bee7f5a1fc89.nq.gz
    ├── 4f190bcb13c2b2a4450fcb722aa6a667768f706e.nq.gz
    ├── 4f2b1613e257a2d87797a2c9422c389c6221da46.nq.gz
    ├── 4f74a8c128268548354fc84d5eee9187d3ad51e1.nq.gz
    ├── 4ff943bf9fbfc86df668222a73116668ff634cf0.nq.gz
    ├── 513c949c6e81249ce30054dbc3d6d82a1818b560.nq.gz
    ├── 515120f875eebc492fb7c2dba10ba4926cabf85c.nq.gz
    ├── 51c24e5d348d00dd7d9190446dfbf976d0476a6e.nq.gz
    ├── 51f953f43197dc822d94718839f2117249303686.nq.gz
    ├── 537794415a365add9d33e34957d2c5027f2dc6f7.nq.gz
    ├── 540326222a9c7cfc109123a6748a84e16302a320.nq.gz
    ├── 550c4d198077c25de906e3b15dd73f8445f692cc.nq.gz
    ├── 553e6029f50d18d3aef60ca559f692a54eb3c31e.nq.gz
    ├── 55523d1e2dea929fb0d57003238bff9b19842aa5.nq.gz
    ├── 55ade34ea2bca4f63646cf2352d957703adabca2.nq.gz
    ├── 55fa190e87f25a297fb4c051da774dd26ab46d58.nq.gz
    ├── 57adc22129d7b1c47a406613e18e2cfdf16a72ff.nq.gz
    ├── 5a21df66a9ec5763f11090c560889bffcaf11266.nq.gz
    ├── 5a4dcb93e847eb0f4adb2b4b90ad3693f5b68571.nq.gz
    ├── 5b411146db1777646a93e16df39e171a7e87569f.nq.gz
    ├── 5b954b55f74c0759a130f5c927cb750f6e8043d4.nq.gz
    ├── 5d1e8882a89fd8d8b5f97f867c70c3157e9cc551.nq.gz
    ├── 5e2fa2b51308c47e08bf8c53c4b060a187385d53.nq.gz
    ├── 5e7e68cd415fb4ee5757dd8ad1d1fbab4d95b6c3.nq.gz
    ├── 5ec1de9559d45bfe9bff3269b93a3e7b76766694.nq.gz
    ├── 5f3e83ffd10a50dc36dffcd033b7312976de8c4f.nq.gz
    ├── 60fefea605c33d2f6333e51dcb6354146fc6cbe5.nq.gz
    ├── 61eaaa164270d7c317f646d49626453ff140b09c.nq.gz
    ├── 6249941b7aae2c283d3aab2e322482b16dc187de.nq.gz
    ├── 626d012fa0e6c2750a67de9ebf94d3022d17a015.nq.gz
    ├── 6314196c941978c1eb26462f352df0cb09905cd3.nq.gz
    ├── 63ac8c928424ba14e2fdb9ce95ae8c2f33a2cd19.nq.gz
    ├── 63ff595a39113de54d289d853dd937bb530816e0.nq.gz
    ├── 64b831d498b58d2f81e93f7109bc60d079c55c1e.nq.gz
    ├── 653483739976886b56b418f30f23c17361733ac6.nq.gz
    ├── 660a06d1610c6ee406cf4ff45098a6356c08249f.nq.gz
    ├── 662599a7bf8a5ba8782b4dc0b0e6c96987d203f2.nq.gz
    └── 670f14704bf572be57f8749e50e315b716d57577.nq.gz

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

[plotly/dash-sample-apps](https://github.com/plotly/dash-sample-apps)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
