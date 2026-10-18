# Repolex Knowledge Graph of mwaskom/seaborn

RDF knowledge graph data for [mwaskom/seaborn](https://github.com/mwaskom/seaborn), parsed by [repolex](https://repolex.ai).

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
rlex download mwaskom/seaborn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c1cb287835852406691aed60ea0c62710f2c6b18
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c1cb287835852406691aed60ea0c62710f2c6b18
│           └── chunk-001.nq.gz
└── blob
    ├── 002c383a22de177340ebaae51d39b6118b06a6d1.nq.gz
    ├── 014cce8058d23cc7319655e84252302dd3bd00d8.nq.gz
    ├── 042013c14ca58f5c3ae0ede209ba6444c12e1f7b.nq.gz
    ├── 048443b0f8639e2e90a635c74e6202ae62e3ca8b.nq.gz
    ├── 065fc047988626f28e6cb0c08e882ce82b90661d.nq.gz
    ├── 068c8c76426822f4ea6e6210d2ecf325c95e9856.nq.gz
    ├── 0711463e824cdfb32dcb96c09bdf389de11b223f.nq.gz
    ├── 0a2e3c06d9b679444daf2c7082c18055861fba2c.nq.gz
    ├── 0a60a0663a72dec8d807aa17a78c0439058429a9.nq.gz
    ├── 0a7db6d6dcde9b549c33f1e35684bba2b851262d.nq.gz
    ├── 0b74bf4517ff83fed232e8a68fe9e9eb31f767fe.nq.gz
    ├── 0bfd51a8dfefee74ae9741a445462904d5345c90.nq.gz
    ├── 0c2fb7d4998ac6fcfd39bf79686c113f5481bb65.nq.gz
    ├── 0c6dfb10795e930f0f725d46e91fe9cd2db00b35.nq.gz
    ├── 0df9f4d16523248879bb1bc458e1e910d185668e.nq.gz
    ├── 0f775cf6512c789ee4201cc41ed5c5fcc389a500.nq.gz
    ├── 0fa2f23a5103b8b49d935a26845fb3fd8c1250b6.nq.gz
    ├── 0fbb350f3da43746d318004a862b20d019d1cfe2.nq.gz
    ├── 1043877f82538b422355bc7c55edfe4b1dafd638.nq.gz
    ├── 1145b96d4e0d1bb44ef97a5faabaa0b58b3733e8.nq.gz
    ├── 11657fef0e5ef14c04ef5cb6957194ed6f1672f5.nq.gz
    ├── 123e57f0a936e8e73c684dd647b9813da86a3f60.nq.gz
    ├── 13a8ab3f852f3dc3bfdcc5be7f9aa7bf9d19e6a4.nq.gz
    ├── 1405269edcdf349c2abf925de7a5dc97c72b66d1.nq.gz
    ├── 14c29059cf522eb935d03c4c5bdea9d4ea66bddf.nq.gz
    ├── 161d2af292343a48f4d08211fe9d50f594d44a3e.nq.gz
    ├── 179926e71789bb6a6891aa21d80ee38696f89236.nq.gz
    ├── 17c25c55fd896104aa0b75d4dc7db6f845358959.nq.gz
    ├── 17d333bc89b79d3b43310493456176e9c69fab4e.nq.gz
    ├── 18964723c466b0742727c990a4f2572ad1343593.nq.gz
    ├── 189e79046781d4e1229ab7e14966060852295a9c.nq.gz
    ├── 198072418e039f36b7f193edc783e61627277288.nq.gz
    ├── 1a2d0380dc449c18f71b727c0134862a674abda4.nq.gz
    ├── 1a75f1f7e19247fd051cd1ba151cbc054dd3e5d0.nq.gz
    ├── 1b7f04649c63c9524d08b0724289914be0ff104a.nq.gz
    ├── 1b80430ab3d5881c33187048b15d3cd771940952.nq.gz
    ├── 1c84b4ba10f9b9e9e1c07f29f32f92daf05915fe.nq.gz
    ├── 208206b86664f749596436cfd08f557dee136b7f.nq.gz
    ├── 20885effddc17880892dcd506dc08451a41e1338.nq.gz
    ├── 20f8a910e298d6dc84ea4efc7cffb7803b7ca81c.nq.gz
    ├── 217c8afa5d224a7fa072deae7c71914281a1ae2c.nq.gz
    ├── 21f5adc34d5f54a14ba3ed8c25f453700727ec52.nq.gz
    ├── 2358228ba5a32a5f99a35b3f67b1159f0f226ca3.nq.gz
    ├── 23a217228ff4876695fed920f3b8e7e1feda620e.nq.gz
    ├── 241b1742e0f624e5732fd87c5d1ccf95b8f868f4.nq.gz
    ├── 24efff3de84d7a53434f90108b58d6a6b8b4a28b.nq.gz
    ├── 269c8f4f9e9d38b3683b24630714acd80b1387d3.nq.gz
    ├── 287f441670881f0967f674cdec6d607af58029ef.nq.gz
    ├── 2ab210b6ffbf63f21ebee9a4a3d59dcbc94fcb57.nq.gz
    ├── 2ae2315412958ae329f008c6b2fe10d98472d69f.nq.gz
    ├── 2aed6830a6becc256352a7adcac1f10238d84b98.nq.gz
    ├── 2b46a00a039062e94645bbfeddfc099bf6a67902.nq.gz
    ├── 2baa27255bec291972faa2713898087a26be91ad.nq.gz
    ├── 2c0c48adff08c42c48120088542d74a6fcad7453.nq.gz
    ├── 2cf744416408ecfd4a92ec4dd030a106ef03c5b8.nq.gz
    ├── 2d73fe069415daa79fc867d5222f9ce7af0156cf.nq.gz
    ├── 2d9c92c44d5d1faa78bc28eb3283a80d92010ef2.nq.gz
    ├── 2e022db5d7a4a53b5ccc36dd4a3361a1fa453d8a.nq.gz
    ├── 2e34b9dd9cdffb5d82f56674fac4896de91a4d0a.nq.gz
    ├── 319ff79463c35cc7e878707097c6448739384ed8.nq.gz
    ├── 32a13a8c7dfc61cf7083c9379debae1cabd15cff.nq.gz
    ├── 32bb24529f92346af26219baed295b7488b77534.nq.gz
    ├── 3388a75763634a2e9c299e1a41ace26e5bc29d87.nq.gz
    ├── 347dd9b344c7fffba0bcb6dfd0e74df71a580105.nq.gz
    ├── 354c5938d81a8f3a833497b7f853ecebfa30f4dc.nq.gz
    ├── 35c74ae9bc8bec1816d7762eee4179ee1212f1cf.nq.gz
    ├── 368f6c50a6ebe4a9b96e67a6042b5d8509ca7e48.nq.gz
    ├── 36b0eff6265c4be2f0084098dfd9625d03d6cf74.nq.gz
    ├── 378044557f11013bf4645828f734a3acd152c88d.nq.gz
    ├── 37d33d64ec6b281760abdb25bd752a4ff30df903.nq.gz
    ├── 3875f70a636b312d9601de04e5805e14a2257d22.nq.gz
    ├── 398f4376256f6e26684ed2fb5254d11d0f5b5e01.nq.gz
    ├── 3ab6c3172b9d194c719468780e060c9dc9e18674.nq.gz
    ├── 3ad74429cc3dcdda50c92036050fb0cd686010e6.nq.gz
    ├── 3bda82c44f5a831fbb8ce14b8ff53456e2b50078.nq.gz
    ├── 3c61f2515e15255849764985284a00c93efe6a72.nq.gz
    ├── 3d0bf1d56bdc5c0e724c8eeb95200297884337cc.nq.gz
    ├── 3d7d91020621fe9632c5c9efdc4acffb0338ff08.nq.gz
    ├── 3d9571723965d84af19f99d8d5cf4aadf1427622.nq.gz
    ├── 3e1477a9bbec1cdc96709059f59a7a729bf21309.nq.gz
    ├── 3fb290c812f8de293c9731ecd6bc83ee88fd2239.nq.gz
    ├── 40346b02697d2fe58887ac8d00048a16b5b5c6e3.nq.gz
    ├── 40c63e35f481bbddec2142fae8a59042e7d4711a.nq.gz
    ├── 42ce7b75c92fb01a3f6ed17eea363f756b7da582.nq.gz
    ├── 4638939fab15695d0401ea36268bcab8e06a808b.nq.gz
    ├── 4679a75a95bc7739a05c1879dc5ccd4c1faef1cb.nq.gz
    ├── 46888db577ebbc37da47153b47349c3beddc7c6a.nq.gz
    ├── 48c531b7c04126beed9f4337f5f1a456c91cda0e.nq.gz
    ├── 491238c575b0a4237f8a4bca953727c7783012d1.nq.gz
    ├── 492f6a496ae6e2dd0572954968babcb4274886fc.nq.gz
    ├── 49688e6190eb6ee1af33e32cc911d027616a96c0.nq.gz
    ├── 49b5e8f129f7a85b6e3812e023fd2b1fa31ddac0.nq.gz
    ├── 49f7ae908642220923ee9920f256a6f0c2a17120.nq.gz
    ├── 4ae904590b700f78fde7d2809df9d013704fb263.nq.gz
    ├── 4b06364224efe302a6a5a40cf582a85f6ae9ef27.nq.gz
    ├── 4b9c6577c12ceab1b3a0fc410e3f3016013338dc.nq.gz
    ├── 4bb4cd61f2e6f2a2803d05ba1a04f52b5a51d95e.nq.gz
    ├── 4d9e9f916e68d6a3abc6e43a35e6431cc961560f.nq.gz
    ├── 4de9bef67dc1004eb3a7c1a0cb82969179fa796d.nq.gz
    ├── 4e2df91b49faf267b6af020a4ef4078ea3a28566.nq.gz
    ├── 4e96132b5285e97d4de5eba845b4b5ee2f973961.nq.gz
    ├── 502812af57f5fa2c7e8163c33f472b594f506c79.nq.gz
    ├── 5156bfe16f4f131a50994a235e3e3ab5a06a6f22.nq.gz
    ├── 536faa1ceb75995dff456edd5d8e21dacc86bbdb.nq.gz
    ├── 53af8c58a617b4a065ddb7281bb2a88c233f661b.nq.gz
    ├── 53ce82c01e4981cef3b47f8e8b35d998df886ec4.nq.gz
    ├── 548af1f199355e00e2b1956aa992a48ed61d090a.nq.gz
    ├── 560e2c6add5e8f902af818b88b5d58636c7f1cc5.nq.gz
    ├── 561d17da630a0d134ac373e91d2db3c28a0cbb08.nq.gz
    ├── 566ea49e3f34dffc919302f43f180fada62eb287.nq.gz
    ├── 57f1f71345ae273c98fdc9fb615ce0df82a5a68d.nq.gz
    ├── 582f284c87121fff1ba6c3039fb7408139a74366.nq.gz
    ├── 58d757c1acefc3c2ef6ecb8bec01c152ea08729d.nq.gz
    ├── 5a0a660d8ed534870a490c034cd3f1446b48a0ac.nq.gz
    ├── 5a12a1be860d8d6ba9db7ab012e9ce5897084171.nq.gz
    ├── 5add934904b2acd025663f6aec21c7ef8593813a.nq.gz
    ├── 5b82af2e1b8f17fbdf70959654f7a7e266f50583.nq.gz
    ├── 5c5dacac780e5cdef0cbf1fe78af2671a7ec3123.nq.gz
    ├── 5c8a1b75ce8ac5f579499ebd3440306d071a7f72.nq.gz
    ├── 5c9777732182b0a972dd970b7b16af63f0f652c3.nq.gz
    ├── 5f7f5b9f91a02dedc427a11872c750b5782ba2aa.nq.gz
    ├── 6013e4ea53952c12225461a01a24a5efa176050d.nq.gz
    ├── 6079b41dda5e3825fe0757acdbd57d147ce4c9db.nq.gz
    ├── 60db2e12c66936c51cb118100d0b904f7c1313a1.nq.gz
    ├── 61829ea1b15efdfaded61348d21d9c79bd350696.nq.gz
    ├── 61ab56981856d7e82820fac2e1ad67a0ee9a2c54.nq.gz
    ├── 61bae30f841a1a5880e5b6ef7836e018e002dfc1.nq.gz
    ├── 61fd08586617a92796f86a4af13d16be286308f7.nq.gz
    ├── 6443119c3ffad41baba1edc62c1424d1a7deaa8a.nq.gz
    ├── 65adf8e9f0a6eed8283e92a5ce343625198f2c61.nq.gz
    ├── 66d39661b9f31a093b109422cde8e1e246724afd.nq.gz
    ├── 670a525c5b55dd9e46e3c81f4b557c7994196010.nq.gz
    ├── 67a95bbfd01f567ca68511bf627a627dc56d7843.nq.gz
    ├── 684df77df96ca21275c76523987e00ba98893a08.nq.gz
    ├── 69e08c8914f22517e096220dbc94d54367031072.nq.gz
    ├── 6a37dec4ad53da7c458076403422b5bea3593e0a.nq.gz
    ├── 6fd88bb5fca1e625fbb682ebcd7c169a58f6fda6.nq.gz
    ├── 706e78b351d261d6877a3cf194d56feb1fbc4360.nq.gz
    ├── 70714aeef6587d90fd88e70977e7d18b047608e5.nq.gz
    ├── 710d00580836927a99045647981a85f5f89a2210.nq.gz
    ├── 7277ea38c3bac1aa1c118c0c68d9a9923e52deee.nq.gz
    ├── 73168b3edc11a92838559d4cc49be0d6b9092ab8.nq.gz
    ├── 743dfa4d0bd8d8d2676f7e6776f300bb28171038.nq.gz
    ├── 747ee8634e6208cbe27dacd5dca9bace944fdf7c.nq.gz
    ├── 74a21111f54f9107bd007153992e0bd0990899eb.nq.gz
    ├── 7514a6d13b7a373ff3c89ccbe06abec77442c0f2.nq.gz
    ├── 751a37508e43177411a63559742b2f304aa18464.nq.gz
    ├── 75bd4e7e611c3c3821d1849a3d4df1e78ba01ed5.nq.gz
    ├── 761d04c75c80f484b10e45b52a7d3388c44954ae.nq.gz
    ├── 7633d358091b02c581a652cad2572e1e0d00d10d.nq.gz
    ├── 7656654492aa5ce56d47cbe9cf923376ed714643.nq.gz
    ├── 78cfc1ef645b5ccbd82a5830a1dd298b1c1cb2d9.nq.gz
    ├── 7b5d4c194d9480eca1d5a5a8b61fba9d53a4e4d9.nq.gz
    ├── 7e8ab035eea974f5743debbd6cd99cf3542050be.nq.gz
    ├── 7ece386d6027428a70294f24d6dfe7ff864d977b.nq.gz
    ├── 7f460e6779eece4b579e64a0d9e2c8702a7fe78c.nq.gz
    ├── 809358e05b0a5add1e7bdb73289385489d1dfe15.nq.gz
    ├── 81cdcdb76a13900e639be51b8f2a738525f65cb3.nq.gz
    ├── 82ef6842f5c60cc7e32c242aac3e37ad38bd7b7b.nq.gz
    ├── 83084859b9ed2ea6ed10da1b790eedd1be713186.nq.gz
    ├── 83b0ef8289bf2b80d74180bfa6973912b57437d0.nq.gz
    ├── 83d8d2055def661701fecfcf91a52215ce38ed50.nq.gz
    ├── 8509812d4a31d21eaa8a0fb918ac9cd166d983ce.nq.gz
    ├── 86f5ad0986c90f85adb79a7964c3752d5d2d397b.nq.gz
    ├── 87f7d1a3f81cd5645b76fb92f483cc16698998c3.nq.gz
    ├── 8a6536285bbf8ad0b7a9eaca26f1fb76b2d4b9c4.nq.gz
    ├── 8c1f9d830705d0c4ebe2d6e5f20c8eb800423954.nq.gz
    ├── 8d1b9ff3ed525a570a347c61f807f8c8c92fb12d.nq.gz
    ├── 8d7a75fc9a946f5cdd2a215d4a026f76574fe295.nq.gz
    ├── 8e636956e088c62c4addbf6f98eeecf394850f2e.nq.gz
    ├── 8e7b77fbcf1b4368a6194e2ea2b9d29ce4d74cd1.nq.gz
    ├── 8f064e3d40f08b5089f0a298b5319ec73f2cef9f.nq.gz
    ├── 8ffed36cf2614a37fff29c86f16c45e72ed5f96c.nq.gz
    ├── 923b4ede8589a4ea20fef5977b679d1139201d39.nq.gz
    ├── 955efdae0a076098c8c387a374dfbb16ea3f46e7.nq.gz
    ├── 95f8cff1f75b0bbd7a038ad78f12c479fe4a6e02.nq.gz
    ├── 963bd94df0810335372616ad8a9118485cd6db3c.nq.gz
    ├── 97d207c6a1048fe3533f992a37d8b9eae94f8fda.nq.gz
    ├── 97d5e642423883a7f36b5bf36dec7d679405b5d7.nq.gz
    ├── 9930b6187cfb51fea010e34e81f521e054da44d8.nq.gz
    ├── 9ec81a4e5c6ae4eca0baad56b23a5cc1e21a9399.nq.gz
    ├── 9efd80406c778c7a5cfceaf5f34fa68d31de6b86.nq.gz
    ├── a1d3570a82b4da5858817e87c77c34144ec0f3cb.nq.gz
    ├── a1dd88e7c6eab2af7dcca6f73ee56da4fa22c116.nq.gz
    ├── a236b20f463189756dc074d51abc5d5441f1241b.nq.gz
    ├── a2a38710cb926f245220e606108057ab94b2bb62.nq.gz
    ├── a38b29fb72ce4537c997004a611bdb49376ed1f9.nq.gz
    ├── a4b96b43a7a8d84dd1f43190681229eb63f12755.nq.gz
    ├── a517f1b8b79483c5bc0374322d73d6affe2bdbda.nq.gz
    ├── a625707d71de011ab25bd40008d3ebac751d27f1.nq.gz
    ├── a64bb91c2549676d8556a7520598b248450363b7.nq.gz
    ├── a654e399f1c3cbbcf7dd77c60eb6753edffc0b5b.nq.gz
    ├── a89d76f52be2f89f3dfde9b326670dfb61191d02.nq.gz
    ├── a8d0da6634c4583de4efae90268ceb2f5de5c4b9.nq.gz
    ├── a8e5ee47b91f188bcc715c08f85816b328eb5cd2.nq.gz
    ├── a974607807e4bcc3898182270a11e17eed12b13e.nq.gz
    ├── a99706c38c1e71ca74b23c6240ad3fa2da8b701a.nq.gz
    └── a9bf7dc3d4bedc2faaac172f76f7c8a2a80b4870.nq.gz

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

[mwaskom/seaborn](https://github.com/mwaskom/seaborn)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
