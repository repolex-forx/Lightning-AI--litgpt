# Repolex Knowledge Graph of Lightning-AI/litgpt

RDF knowledge graph data for [Lightning-AI/litgpt](https://github.com/Lightning-AI/litgpt), parsed by [repolex](https://repolex.ai).

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
rlex download Lightning-AI/litgpt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 18c931c15c2398621d35371a12d2b1785e855bb6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 18c931c15c2398621d35371a12d2b1785e855bb6
│           └── chunk-001.nq.gz
└── blob
    ├── 02c1e0b356a6259687872ede694822804fcc9e07.nq.gz
    ├── 02f211ee1af568b53678ff05848a51cbe73e0c06.nq.gz
    ├── 0372c612fdd95d1218b3caf1ee1648e24ffebc2d.nq.gz
    ├── 03d342787f97a654826764ae9e0fd784dfead282.nq.gz
    ├── 03d867cd8e3d781b38931872538e194ae4f4bba2.nq.gz
    ├── 03ec91fea6e0fef7c2c0d062b2e4371c48629ed0.nq.gz
    ├── 04e0de3049f1e7383e9a920da6cfdbbbc3427445.nq.gz
    ├── 0539ea745314286255dd89f580ba73a6d83e5d2f.nq.gz
    ├── 074a12eececc74057a7d29eab0cb1a017f08cd3b.nq.gz
    ├── 09bfb1d52ac52234d6053864e4f15e5675c5faff.nq.gz
    ├── 0a2f72eb97dec54712f282cf80e9a25ccf9d5412.nq.gz
    ├── 0bfc1acc92812e062517fc6e6d5a06bc6d44c5ac.nq.gz
    ├── 0c30b94c4206260c0ca3b44d9db31f0b38ba43e9.nq.gz
    ├── 0cd128ce1438f535282011b01728cacebd975b2e.nq.gz
    ├── 0d4dbac624bed590096070887f07b220a210eab9.nq.gz
    ├── 0dbc5b2420cdab46ffb60ac5da32a0e91d892fcb.nq.gz
    ├── 0e93fe7308a165b280c824f93fd6434a3a66e0ea.nq.gz
    ├── 0fdb7412f725451e8a9d9fc4d2c96aa967244020.nq.gz
    ├── 10caecc3e07de37f7ca32ee13a2ec657db9786c5.nq.gz
    ├── 111215d8a2fb154515d2bc4bb433e7b2fd5c3f25.nq.gz
    ├── 12f7f4394eb656dfbd365aee80f092c5e820c266.nq.gz
    ├── 16d613d274f013bc2f41df8948a9b761883428bf.nq.gz
    ├── 1a2889b09c0a09100033ebf23cd5359db8ad64f8.nq.gz
    ├── 1a578c916ba25577f297acfdb8f41d3dcb0e76a9.nq.gz
    ├── 1b22fa6392d3723b22d0e022246c1fa219c45bfe.nq.gz
    ├── 1d420a42e58c76849ea9899bcddbd4b22ec0cfc1.nq.gz
    ├── 1fd2d2eda8e3aa0d3efd7db1ffdae240f9225663.nq.gz
    ├── 222ff940e49c0b635884f94be9c38eb802879ecc.nq.gz
    ├── 231a3d6e9769bd4d167c9223d63e6db22e878942.nq.gz
    ├── 2461fb1836ff7d45ff0cef9a0b1b4f1a0d1a10e4.nq.gz
    ├── 266c1800e8e0851134db22e652137c0d61700250.nq.gz
    ├── 29940c8e8e5f8c75c96fce00e284307d23eb2a7e.nq.gz
    ├── 2ae443e01d7afd6b285b49451378277ef064a8bb.nq.gz
    ├── 2b0d55a8b916841d7530b370800fb6bdfe6d506b.nq.gz
    ├── 2c8458f02b5c6035f1aff054a6eee93f04a68572.nq.gz
    ├── 2e7f82ff2f568eea1fcd0f54c00fe08becd8ff34.nq.gz
    ├── 2f2df266a8d1342cb77295c387c33aee9d69e64b.nq.gz
    ├── 3088987bd9fea22eadfd36f2053010c0530a476f.nq.gz
    ├── 32eb1c2f3afdc190b838354adabc4753c4213152.nq.gz
    ├── 34c9e4b665492aa3693282f5c3b14654d1ea54c1.nq.gz
    ├── 34e8c8afe297a49d7de31e9f4afd40cb2550454e.nq.gz
    ├── 35cf0bcb9ad1b1917f50b98412b4bfccb241fe29.nq.gz
    ├── 3612e2ff0b0923c5fcebe9f9514fa5479f81782b.nq.gz
    ├── 361cfcdc73488df72b1791c021a737272b9e05fb.nq.gz
    ├── 36b320d23e2d10aa57fc3feb06961e2b65661e58.nq.gz
    ├── 383688c43d122c54b2a85e084bf04fdf896f7eb3.nq.gz
    ├── 38b41f711dcfa05a8ee7769bb4a12cfeefd16937.nq.gz
    ├── 398594ae3d5d6eaafc89e20b2833c877205b7044.nq.gz
    ├── 3a7d17d5e555b24421ad96f36368a7004859e7cb.nq.gz
    ├── 3aa79c3202a235fced0e639f978ee21c41d5c663.nq.gz
    ├── 3ab20de7b011f190e621549ed2f01180883247ea.nq.gz
    ├── 3ad35bfe40afc4e631727fb2a48f2df493a12d7a.nq.gz
    ├── 3c3b67c721e16bbec16d006972036430efe1b2f2.nq.gz
    ├── 3dcf5b7a9b199691044b481db6c6a55332f47acd.nq.gz
    ├── 3e2f8daa1fcc1dcb6b9932dba1bee9c40eebe20f.nq.gz
    ├── 3e5b5a562757a010e5a139885bf34a7f9aa58e25.nq.gz
    ├── 3ee3903737750fc9dec4da4af4e9e2d099496a58.nq.gz
    ├── 40acd8fba621fa8f9c75b2bfce7b7637490a1784.nq.gz
    ├── 414c1d71c7877f136ffa4804c27bac563cd04670.nq.gz
    ├── 4180d9972308c76b57133c2d4b011a5834b1e814.nq.gz
    ├── 4182bb602b26fefbd82af943156b90cd49b98403.nq.gz
    ├── 41cbf56c5a95345fd6312503d09ae96e6cae3df2.nq.gz
    ├── 43c6c034b90e0ab2a5c78ec216551dc586654b81.nq.gz
    ├── 46ba75b3841266db26f5ca48aa463eb227df5472.nq.gz
    ├── 47cecd233ac9e14f98943364d1030b91017a24f6.nq.gz
    ├── 48e0c0031da33ae48430f4f442b0384a25249ca9.nq.gz
    ├── 49410286afc26376297fc1bb7d69ff0d0c083f3d.nq.gz
    ├── 4a2cbba528f82d26f18f8d431b9f5847f33095c3.nq.gz
    ├── 4a8e87bd2a5fddd5e1a085e141297ddaa02ba50f.nq.gz
    ├── 4aee8c5bb6a3eabb8a6abc18689fc59296aa03fa.nq.gz
    ├── 4d20187a8c05ba90f05cf9a2f6eed47383295288.nq.gz
    ├── 4d59ed1edf9f3cf5263bb332ef2772d7319c394f.nq.gz
    ├── 4dea30bac9497b0bfe08898a4107ea808d09c59f.nq.gz
    ├── 4e0a5e9207b21c7dc07961a36f770f2384d9ee4e.nq.gz
    ├── 4ed960a4de49da05db89b2c4de9b8c9d48b34b25.nq.gz
    ├── 4f7b737d19a9c1baba8e0b00cb2011c5d350a04a.nq.gz
    ├── 5079f398ee8f2058f49eca391eeb6b0252a9146d.nq.gz
    ├── 50a812c74be01d28968076d6803362879d385adf.nq.gz
    ├── 50b8db33a0407a6af2bb9cd708ba483095a0d960.nq.gz
    ├── 51e56801f861a0cf0cf5a19c57c8c2f4f1d75422.nq.gz
    ├── 51f33155c724cab9f24140deb839a26a5b1c3a7f.nq.gz
    ├── 529e5f13de8c87d3c7bbee4d3cdc52f04f2da224.nq.gz
    ├── 52f9a7698bd96856c7c9ddce90e53b0e7c44c4f2.nq.gz
    ├── 53b24c2bdb20b4c298e3f9747e563a314d838d9e.nq.gz
    ├── 541860ab5b6b93b8ae49b95ef0d811f1e1176200.nq.gz
    ├── 5442f9c5e75e41d0e507c8df627d912109332410.nq.gz
    ├── 55f85089015c4b5b2dd5a6545e0931d3c82b28d5.nq.gz
    ├── 5a11db161af0118fbf7abcbaea614c282d9cb9c2.nq.gz
    ├── 5b555cee43325083d857718a410d020dddb22296.nq.gz
    ├── 5b899bfe7e4e44e03e1975bed84276db18e76c79.nq.gz
    ├── 5c51e06c4d34b1ad682368a98b75323abce3bba6.nq.gz
    ├── 5cc10192e8c03af475a11088798ec0fb6e1926c9.nq.gz
    ├── 5d040f4d09b3e3cf73b176e1e6d9c0ad09088bd6.nq.gz
    ├── 5f9788ebf06942002916450811ded80ecef51dd7.nq.gz
    ├── 6182f24d5489ddc1945e5a58b84e16d96b001321.nq.gz
    ├── 629314340c1d77d8c083de3006d3de6fea763919.nq.gz
    ├── 64f9f6bf21cb4832bebefc469726d72064d9caac.nq.gz
    ├── 65e797e6623a57465f11aa94e0fb33c436628766.nq.gz
    ├── 66eea1097eb43d64e4d728493dc0bda51d5e9fbc.nq.gz
    ├── 67705fe0806f1648c3e9b5f024d535b1016c0f60.nq.gz
    ├── 6851c910bdcd24fa2e1ce4835231099e563c86f1.nq.gz
    ├── 689e2fda8ead5e45c8c1c0b67d25f6327dfd4870.nq.gz
    ├── 68a62038151736a9a1d9d13e1475188b2cd10a64.nq.gz
    ├── 68af7780081527dbfebe852526e8ca63c049ee04.nq.gz
    ├── 68b8a5d1fb2f9d914bf4b2d2a032d84901cbb0a2.nq.gz
    ├── 6afe31f855872c6004bc4ce16ef962facf7ed01f.nq.gz
    ├── 6c5c55959d795a203054e2858940305d17225238.nq.gz
    ├── 704dd4afcbde25c3528a7731e0628fdfda9bbccf.nq.gz
    ├── 70560026f3525dfa38fbccaba551cb68cfca2c64.nq.gz
    ├── 713cbaf2e78725c417dff2acabce506141ead5e0.nq.gz
    ├── 724d3ca734ee392ade477503d6c260139dbe07a3.nq.gz
    ├── 72de327e7c028954ccc2f6567073ab61606a8d45.nq.gz
    ├── 76844261205d7c792e3aa74c70ffcf31b9d272a8.nq.gz
    ├── 76906f3d74f0c47bd5b1ee4f77b5e4e6aa9219d4.nq.gz
    ├── 77245b0314b34691acfcb5aa5dc539eae93779ac.nq.gz
    ├── 782d3d435c1488f1c2566787d6101bdbb0111504.nq.gz
    ├── 78558cce8095d3a8ead0aeb544b89fd54c3d21e1.nq.gz
    ├── 7c1d511e2cc482ca48a82c048e13c196bdcb5a74.nq.gz
    ├── 7d3dfd4f5f5e4ae0ef62ded03100d3b1143dc8c2.nq.gz
    ├── 7e5f90c149e36c912545a0d2c5aac6ee590367ff.nq.gz
    ├── 7eb022930bb0cac04e1f37ad0537eefc8f3d5f98.nq.gz
    ├── 7fc96f7e55908d03f1a58260b1418ff37f8fb383.nq.gz
    ├── 7fe57009c9c2cdc54de1e3acf2c4288ed35841ae.nq.gz
    ├── 8560924c33662b8da94bf9543fb695db969278a5.nq.gz
    ├── 8591e9044e97c9729ed342f69eaf269a965d9dd6.nq.gz
    ├── 87ef3c52db9a0c6aa96e283e4d29626f5c70f113.nq.gz
    ├── 8d0cf21d5ee8bad22bfb793a8c22c7f4ccd5b36a.nq.gz
    ├── 8e17000c4dea6563b905c26924bcdf507c385565.nq.gz
    ├── 8e9f04fbf9f368d9375a0d42b2ce0aa0736b35e1.nq.gz
    ├── 90180a31086ace0f57a8c15aba1aa13fdad4ba83.nq.gz
    ├── 910537707abacb0e62405cd84543f1e25f6a547e.nq.gz
    ├── 9287e40af67c68648ad7d0f2aedffaa534c6712a.nq.gz
    ├── 92cfa2f8e81d78157dae5af48a26acdcf3d67d71.nq.gz
    ├── 92d2a4b25f880a91b5a2363a446a5a92aec7b2f9.nq.gz
    ├── 941ccb0d506ac9909f62846f1f2a1aead26131c4.nq.gz
    ├── 95b52423f7cdc3c4450f71126a8a9159c39ccee0.nq.gz
    ├── 95dca762d22a147059b5df7aac995835476b5579.nq.gz
    ├── 9647b5f51022b551d129a0fb80de2184bd64d1d2.nq.gz
    ├── 969e4745678cc38b77a3450366ddbf2cde98c07c.nq.gz
    ├── 96e9c56eb01f8871777bae9ff8eda7f31a25e67d.nq.gz
    ├── 975894aaa39f55322ad442935e473a6b44720350.nq.gz
    ├── 97cb3e4dab72f4978ddcbfe6fbbef6228d9a8529.nq.gz
    ├── 98166717bc19d206c2bad60064c7c66d81b32618.nq.gz
    ├── 9e036e7bf9c71d6ef53b0dbafba8ffea08604a86.nq.gz
    ├── 9eb80de2a6d2446200ce8c9a7d8c9fa658341e7f.nq.gz
    ├── a016615d734793473a672f40a606f91d58a31413.nq.gz
    ├── a02c74b932c18cb63abba3cc990481738c068f87.nq.gz
    ├── a0ef54df8b1dee038cb04825e262327e99bf3eb9.nq.gz
    ├── a13bc32ddc8a2dcfc2dda365b6099a79fb0978aa.nq.gz
    ├── a16c05f869c1c405791282f46cb89632e2f0cddb.nq.gz
    ├── a287357e944ef7924b45116c0fa31e9bbcf7a8ec.nq.gz
    ├── a2aab52f9b0ce4ebec962ab03110e2d698b1ee3d.nq.gz
    ├── a682fbac51bbe39ab536efd8c5e0b018faaf687e.nq.gz
    ├── a838ff22a6924679536a84e1b7396964a6ea31d4.nq.gz
    ├── a8e4cbf6be49d765c966e3fca69e730fddb00c41.nq.gz
    ├── abcbcf1ee6fe1be2ec72eca8a0ad7341488175ff.nq.gz
    ├── ae10780826063240c98881bc2e6903713d399b4e.nq.gz
    ├── af813eb08d0e88bcd07235b18d86ff47295e606b.nq.gz
    ├── afde080c9aa0afaeebd2e72778de3776d7ff90c2.nq.gz
    ├── b40183dc974fc9acdeb6db667be81fb48668c252.nq.gz
    ├── b53f757821e082a6fe107d34b10bdba58d32874e.nq.gz
    ├── b58a08ac03b5d55808417221cbfdc6d351f59920.nq.gz
    ├── b61b3fa6988f39a794f8d0b5e568bb8013982a8e.nq.gz
    ├── b6e3b9ad6dbef9f33516aa69f95f54f1fbef090d.nq.gz
    ├── b8c8f915cb2650bcbdc595d14e52345a88fa82b0.nq.gz
    ├── b97a5863de9d494208d8022063eefc7834da9156.nq.gz
    ├── bd782b4e088f479fe3979a76cba425add2acd6bb.nq.gz
    ├── bd7b3b4f3fe117dd8978b5dc2e792e3dded03d01.nq.gz
    ├── bdba7eeac7e0d055b9e760c511e3452863afb7a2.nq.gz
    ├── be7f72e376b2f864f46d6ffda1708826a8e502d4.nq.gz
    ├── be82ce74d2e5f2f611dcf91d79362a0e3aab8703.nq.gz
    ├── bf21f6adf73c97b3d5cce274e3aaecd582aa8c5e.nq.gz
    ├── bfce4fe137b7e8f1e67df74b44fb8fb127ee7b5b.nq.gz
    ├── c02ee5b2fd8e78ebee5fb7d2d01a3ad74f980693.nq.gz
    ├── c1cb44ec04245b1ad5c45a66cdee851ff3d91208.nq.gz
    ├── c49467db1b1b2b6f9f005469192d79087cacd290.nq.gz
    ├── c4bb1bb11f58c14ef5922aa7f9e8c5a401c0f916.nq.gz
    ├── c640b5cac5ea635959153a3c659b86935633deb9.nq.gz
    ├── c8698207ba8581d1767fa2a212d1041ae3676372.nq.gz
    ├── c8afcf1708465a528b259f0f72a746c01a0d869f.nq.gz
    ├── c98ff0a83d453a461ef59ecb9c86df59ea2ee859.nq.gz
    ├── cace23dfbdc752a1a4b1ac82a45f319e9b16808b.nq.gz
    ├── ccd63782293338b5941bcf2764d0999464c8cc58.nq.gz
    ├── cd79ea053bca87603b3e5c2397d0428d6b2e7d18.nq.gz
    ├── d0e2b876b020b56d576536c55a0f38389470fa3e.nq.gz
    ├── d14000eaa91659aa848c51733bc8ba2a9af2ded1.nq.gz
    ├── d1c966b03f2e71f32b059ee392bffcc63ef1a7ad.nq.gz
    ├── d1d0d995427b7b3a12336dba5533b5035e1688c3.nq.gz
    ├── d372ce1e367dba3246ef981d7bb138d68a5bade7.nq.gz
    ├── d3894a4c297f4fbb16af31fe87d5627d0e51d390.nq.gz
    ├── d4129612ab459ffada22764aa3dbf33713caf04f.nq.gz
    ├── d469a57e81e11d62d1ceada92e6267d9500b06fd.nq.gz
    ├── d638cddd28195cda0a64f5d5e54df03af4929650.nq.gz
    ├── d74a6cb78770766d3b5460fd2ede8375c4bfa34e.nq.gz
    ├── d74d4c8710adcb374413674ce4f0b4a1626bcd1f.nq.gz
    ├── d85abbec6d368f5128b13571c9ba9efb687d9e42.nq.gz
    ├── ddb9eea5f494c7ad6004c5df7d7796c19c44d268.nq.gz
    └── df4ab2b5a5deb2c9cd1d6584d06f1d8f3a857c09.nq.gz

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

[Lightning-AI/litgpt](https://github.com/Lightning-AI/litgpt)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
