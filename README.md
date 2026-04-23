# Repolex Knowledge Graph of palantir/tslint

RDF knowledge graph data for [palantir/tslint](https://github.com/palantir/tslint), parsed by [repolex](https://repolex.ai).

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
lexq download palantir/tslint
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 10fc233b2555044b145c9bbd9f602d43e8df2216
│   │   │   └── chunk-001.nq.gz
│   │   └── 899d5bae422fe431c081db6a2fd4b234f9dd68ee
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   ├── 10fc233b2555044b145c9bbd9f602d43e8df2216.nq.gz
│   │   └── 899d5bae422fe431c081db6a2fd4b234f9dd68ee.nq.gz
│   └── repolex
│       └── 10fc233b2555044b145c9bbd9f602d43e8df2216
│           └── chunk-001.nq.gz
└── blob
    ├── 00129f28feee76a75b3ea6fe9e37d775a8aa8614.nq.gz
    ├── 0020050d45667a178b260b4960029d4fc0598a5f.nq.gz
    ├── 0020f452799a428c15bdf6179f47fdbedef34591.nq.gz
    ├── 002387991210ad1d73a17580c5e85ee5130176e3.nq.gz
    ├── 00290a5ba84f6337c7001a03dbe3940325c40e9d.nq.gz
    ├── 0054f9f24ab8d2adb3e00f683fb86d65f0afa121.nq.gz
    ├── 00acde02843d077e0333142f6e694cdd263d952e.nq.gz
    ├── 00c61285f4c55cdc106781aeed234d50eae8f7f3.nq.gz
    ├── 00ce946e7d1fda0de1f803776a012a084fbfbe23.nq.gz
    ├── 00d7c9624e972de99490a5dd93b21c9b49fdc52e.nq.gz
    ├── 00e9e4ba0e993bae6858c79e26bc62ecee6494f7.nq.gz
    ├── 011989a45379314b53bf9488d89aba40e7188d9a.nq.gz
    ├── 014f7127c4477d8ed87677e4373c64eeefc29ec4.nq.gz
    ├── 01c8d924d1e9264c639cd0e0fef53fcaf1e974be.nq.gz
    ├── 01da4cc9d8aa71d4a964240e89cfea18a42b3e90.nq.gz
    ├── 01f7ab6fe2a8028ec1ae37f242e090678d8a19da.nq.gz
    ├── 0202a35c2fdefe6a08e226979a2d7117f253aa7f.nq.gz
    ├── 0203b8cf994bd91115f14c09d0f1b8d895ea7ada.nq.gz
    ├── 022378bebd62bd0062a6fac48919354352dadf65.nq.gz
    ├── 0228263638759ce840e6051851055c8d997853e6.nq.gz
    ├── 023f18619471c0e54740b5279c4b93c580466d72.nq.gz
    ├── 02b95774ec7a9ced74d17ec526d7b1ff1db2646f.nq.gz
    ├── 02e43ab164d8ac8d5e9109178ef63bb4c90fe7c9.nq.gz
    ├── 02ee82b050351ff38fff27f238aef77749078b6e.nq.gz
    ├── 02f4ec676fadd208d35dcc95103dcecac756a07b.nq.gz
    ├── 02f84aefcd8f84c61a5f68892df205fb52ece5a7.nq.gz
    ├── 030ddb8c92b0707a97e13d3ae9712e951f69a845.nq.gz
    ├── 03499cbf3ee8ac4dd2d93da9e7a38405f518659b.nq.gz
    ├── 036e856a37e2397a4caf1b6aeff6c73059d54445.nq.gz
    ├── 039afeb2d7d196dad28b7c96b3546893145653ab.nq.gz
    ├── 03debafdccb44f391ac96c396618ee667ea67220.nq.gz
    ├── 03efd7542d705d8c78fdd11972d1daf74b6469ac.nq.gz
    ├── 0424780d9f4030cfd038d4816d01803a35ee853f.nq.gz
    ├── 042bc2f9ac4f9dc83615f2e2c395f361a38363e3.nq.gz
    ├── 04dd3ffb80dba960dfb071433a9d517afca448de.nq.gz
    ├── 052d90c45eb0f1f0da973c4d02cfaf042c3b3f11.nq.gz
    ├── 053c27dc3512853dae4261be687aa2a2929a04e1.nq.gz
    ├── 0547e0b20135dd0e3af9502c8f4ceca6d999267d.nq.gz
    ├── 05767a6a9fc82798d52e5a5389c6655926f535ee.nq.gz
    ├── 0579e31d3890a4095fa9e02bc826fd7aece7451e.nq.gz
    ├── 05a93c60f2a9d68aee1a8c2994082923afe0a6a1.nq.gz
    ├── 05e34955935257f90505b1526bfac68e0dd344dc.nq.gz
    ├── 0660ca94379019ef5cc254daf68a61cd803e22f8.nq.gz
    ├── 067259a15fe0e982e10a54e2c8bd1bf40a3c3f4d.nq.gz
    ├── 06798ae55fe42448b5cd8d4637de45b54535d38c.nq.gz
    ├── 069c73ca1689c0ee284c5981863759be92d09bcb.nq.gz
    ├── 071feec991493682bad479b3f4a1d5d7d7f5911c.nq.gz
    ├── 07c3390abf62b4f3f02cbfe2d7994fd7f06ee62f.nq.gz
    ├── 07c97a9338acef5b5d4d5d65fe7102e30510608a.nq.gz
    ├── 07f54d1fc56b3d7d74c52d802e22e3b623e424a2.nq.gz
    ├── 089ddf9c2b106ab958bbb97d55e14ddc6cf14d40.nq.gz
    ├── 08a0d1815f828f8e50f734f68999393a0d9e1526.nq.gz
    ├── 08b740b4692417ff890423d9674e89c46d66a4c4.nq.gz
    ├── 08e15a52b3657f36e38e796bf8947d7d807ee8ed.nq.gz
    ├── 0916bc3d9cedef72b79aac2083819e2f58e368ea.nq.gz
    ├── 095aa7b0de4d8df5b5ab836f7123ee87cfee2854.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 09a5057a7cfea04c69b25d3219c4bc2b8940ebf2.nq.gz
    ├── 09c46892473cf0a7d3182802ce8f0fd5ac3be413.nq.gz
    ├── 0a36db5f45a8cec19fe1188f0d346fc0bd980f47.nq.gz
    ├── 0a47ae0c5d3e1eef32a47f9d8d591d1be6c900fd.nq.gz
    ├── 0a5ce13be838771cc3fb1b69e7a4812fbc1b343f.nq.gz
    ├── 0a612cdcda69f2b989f36f9d46756d11108701a5.nq.gz
    ├── 0a9a788390944c55a723492b37d0781f1043377a.nq.gz
    ├── 0afeee9475b17d5618d9da728772c5872bd6ab99.nq.gz
    ├── 0b0cad78dd20bf4399107d65b74e77fd35968cdb.nq.gz
    ├── 0b574aa2cf69fba6cab84a14949d25a987513523.nq.gz
    ├── 0b67f4b744d38d7bdcd083b68aa52c8e2eb33db0.nq.gz
    ├── 0b75885e6e8cb0006554141200df64bffc10cc8c.nq.gz
    ├── 0b957d11b67a4fdb260b167e03f4b5d23bb4b8dd.nq.gz
    ├── 0bac9d592326462d8bb16a9da6da9aef52c25969.nq.gz
    ├── 0bf15bf9b69c933cf5db58cda8d74a49dd37f2f4.nq.gz
    ├── 0c173f913a5d4f9a2cce622f8e473fb6377bc6f0.nq.gz
    ├── 0c499ed2f39aca1ea2e8a03f7bcd73f42703e65f.nq.gz
    ├── 0c58de97be736997ff1dfcc8c3a528a27e433588.nq.gz
    ├── 0c85e06a62c9211456398b62bc170d6eb5f0d73d.nq.gz
    ├── 0cb99adb0640799917602e225a9b806e75df2ce4.nq.gz
    ├── 0cefd09ec541dcdf2744abfbde2b2cc8488772db.nq.gz
    ├── 0cf866328da7e61b4ee6b6ce607135732ff35963.nq.gz
    ├── 0cffd8366f025c3c63171e3fe5f270cdc935c515.nq.gz
    ├── 0d58d115f70f14c1fb8251b6a15bf950b7d9e147.nq.gz
    ├── 0d832bda1cfc55f2ecf73d73f2955ace17c9d53b.nq.gz
    ├── 0de031bfd5c08268ea343b18e4b8055aea8029fd.nq.gz
    ├── 0df7a88aef8a7a64948bebe79b0f51cf069ec95c.nq.gz
    ├── 0e2e8805467217cad4ed781260dbd114673ceb25.nq.gz
    ├── 0e35ccdd33c9babf162f882be6f27388305f8f8c.nq.gz
    ├── 0e6bca2440408b04dffe91349e50cc43eedd64cc.nq.gz
    ├── 0f5151a0b4e096f20fb44e934c77cc7f97d23d8e.nq.gz
    ├── 0f7a1c0711960a2044f6b6e1a4d09ff6d5d75530.nq.gz
    ├── 0f7b7f3a67c9530ddc1bb2a5ef4719996ab040e8.nq.gz
    ├── 0fd3584d109082988694dfe6204e1dd8a5c92e4e.nq.gz
    ├── 1036cc4572a197e6ba496a474237c34c2e1a724e.nq.gz
    ├── 103785c3dda89bdd6c3b51704bc1b61245949fc8.nq.gz
    ├── 109ef9699e311ddbb58ad28b8f3c080a6d1f6003.nq.gz
    ├── 10b347a8c1cf42d3089134bf994cc21183be73f6.nq.gz
    ├── 10bab6aa4ea6fdc9eada9a421b78829680a3574d.nq.gz
    ├── 111c4986bbf62346a16d8c49edfd1c688c4940bc.nq.gz
    ├── 11248792999ab6e96f7431794ff8b78b60563c4f.nq.gz
    ├── 1168a0b3915fac1ec982968f64fa60e41a46419f.nq.gz
    ├── 1180e92e0053edc1a1d0099d87768de5519cef07.nq.gz
    ├── 118242a8843ebfddcf4e2124cfa30a57fd6fb3aa.nq.gz
    ├── 119e8e98967358f6172d79285ebfd45cecc912a3.nq.gz
    ├── 11a4550a30f73fafe27a52bd2fd7b311d9918015.nq.gz
    ├── 11a5c88920331e5643e71521b33d721061e546d3.nq.gz
    ├── 11b341b29efbf8e53f4f1e6edaef18bc0e26a3ca.nq.gz
    ├── 11d12816d90a79db810461dbe2a0adddac0b84f4.nq.gz
    ├── 11f06b692b3c8d1eba8b33ffa3f5292f2d3e8d01.nq.gz
    ├── 11f0dc4cc9d7db5406bd1af079ff26e917d74472.nq.gz
    ├── 120511571fb11578950b496bd7c06071e4a1eac7.nq.gz
    ├── 1223a2e0983e0fcec1cf4d444e1135b0cd868143.nq.gz
    ├── 12bb8af725dfb7c46ba95f406b1cf500ee4ac5df.nq.gz
    ├── 12be3968c412aec3bb1baa4bd4b30443d67aaa01.nq.gz
    ├── 12cabc47ee2334581e7d17a7c723743e7f34ea7f.nq.gz
    ├── 12fee4bce0a5c46b0f9be05a6e4449f8838c2be1.nq.gz
    ├── 12ff9344f46e4a1c4387936fa0d046566f09bccc.nq.gz
    ├── 13090928064d823d9f346d0da8833326e0dbc16b.nq.gz
    ├── 1314ce66811fc571ae67ba67b78e91958cd533c5.nq.gz
    ├── 1322aff7aee2ade32b5eb0fbb7bf46f15e05854d.nq.gz
    ├── 134cf191511f029f853f38bcbb502d5b643399ee.nq.gz
    ├── 1353ddea57bac24702d1607a6c1bdae39d61bc73.nq.gz
    ├── 138f6d73841ccfb61e0236258bde3838a28715f8.nq.gz
    ├── 139d0955e117f4f0ae2de21b9ad3076be145d701.nq.gz
    ├── 13a8cc71812a1d10e2ebc5e6eef6e81b41c4e3f2.nq.gz
    ├── 13bb2c09867cfdb409a975d5c85d48a7359b03e9.nq.gz
    ├── 13ce3e0dab096b22c9e35f0cfeb395c3f7a05ecd.nq.gz
    ├── 140ce62845434fd953d80f371c8dc949e3ef010f.nq.gz
    ├── 1429fd39fcf76f9acc27c6431c6057f5c200418d.nq.gz
    ├── 145062f8c24b00ea546be99f6ca00fbd1655ee03.nq.gz
    ├── 14c15f76ae8db6cbf2de6b8e598b6bd1c6db15ea.nq.gz
    ├── 151dfb6e5f46cb2c364004fe9b1c45e95c93d732.nq.gz
    ├── 153f37560a78881f0a2eae18d679b61ef785205e.nq.gz
    ├── 154c2788a3fc926a6b2c66d1c5f4538f3ec506ad.nq.gz
    ├── 15593c2829e889702f5625bec0ea7fec024238fd.nq.gz
    ├── 158547c24cdbc8937f006d681457d463d2845882.nq.gz
    ├── 15ec7d1ccf0a59c92f8ca2c0d82f8cf485796b6e.nq.gz
    ├── 165c6526ab4a0ef27e4ac52db401939ef785f5e0.nq.gz
    ├── 16bbbfb20523803abacf35e0a79a8645140feda7.nq.gz
    ├── 16d3985926b0099937b6d1378cae04726388c78a.nq.gz
    ├── 16e11a81288e8f48a90d984bc199a17e9283d49f.nq.gz
    ├── 17076d212465efac0f68f8534399327dde3ca82c.nq.gz
    ├── 17726c9bc0c7ba9908c0cfd659a31e8ccdb77204.nq.gz
    ├── 178758b47cae214bf0b95f5f4c25ca174c1cadc4.nq.gz
    ├── 179c3b9e47f9d24d6ed341f1197749473678bd92.nq.gz
    ├── 17b5070c1041cd4eb6e2ec6735f82a0cd32ec42c.nq.gz
    ├── 181f3d936e14146ee2e7ae1589480c4c0debf9e8.nq.gz
    ├── 1845d7c88846bccf65da1825b27a6ec35374e239.nq.gz
    ├── 184d460643199fc1b446f6da7af4d0e3cc227002.nq.gz
    ├── 18605baac0f1c0e1174e80131059cf03721f166d.nq.gz
    ├── 1884be1467d933bd14e14deac8bab5c37dda5e28.nq.gz
    ├── 18b04c56bcf41218c306680c5c79022131146633.nq.gz
    ├── 18bfde2eeb4982dab17b7bd1808191e57b005b05.nq.gz
    ├── 190049a66b7714ac858f1c8c7784e71ca4bbd3a2.nq.gz
    ├── 1964b3ca4d5feaa7f9b2de2d54ac58631aef6376.nq.gz
    ├── 19bc9c36cb735fa2dad37b860886b43720a711e8.nq.gz
    ├── 19d847e828f29856a0bf6884e5b600a547405fd1.nq.gz
    ├── 19f10164332a0fdf150a4bd565ba5b40bb58f932.nq.gz
    ├── 19f39bb99b008913ff78132021b0cdb0b82b3983.nq.gz
    ├── 1a124dddf176dfc92232201d76c55ee199e39238.nq.gz
    ├── 1a8a2180dc16d85b00a18540c5d53376f44c8013.nq.gz
    ├── 1a939a8745880ed7cdcf7777eff79b4497d48d3d.nq.gz
    ├── 1aa03fb4f2f335c184a80c1e785ee09c0c13772e.nq.gz
    ├── 1ab7bbe5114b642b4a56fa8e9705227766c5b652.nq.gz
    ├── 1ab9dce63441190664661e6b828f27c7b96e0fdd.nq.gz
    ├── 1ae5c8d663c17c5062069cef3a10d8af70ec6572.nq.gz
    ├── 1aea24abe6f2bf27111ce8d2d569b772f6dd0a76.nq.gz
    ├── 1b0a1511e2ad11a56aa69178e1d5e38e9067ba26.nq.gz
    ├── 1b70d5ca5998f3dd969b5db9516ba9424f1ac15a.nq.gz
    ├── 1b743e18ad90c30bd3a7d6a71da0f8d94d846850.nq.gz
    ├── 1b97b9d01fd3594d4a4d47b14257f3bd3f5d17b7.nq.gz
    ├── 1cc3bc85ee919089d55ebb786edb324fd643975b.nq.gz
    ├── 1cf7610e342d706dac8c34fb2a7a352c840f9fd1.nq.gz
    ├── 1d10e4a290c7b44b47495cd25ac250d6005e6037.nq.gz
    ├── 1d4b26afa23ff90b3013b3ca461f8db396424dd2.nq.gz
    ├── 1d518fd824fc3429897e7364c856750b0fc93beb.nq.gz
    ├── 1d5be8412a358071c9457c701b69d836c52ac385.nq.gz
    ├── 1d9bf38d79d166598a8884cb5e9b06a5c0d858c1.nq.gz
    ├── 1dd62de83ba4acd118b2137e694ad1b64130b35f.nq.gz
    ├── 1de4119c0144279f4c4b2aa14958399dc136d7c1.nq.gz
    ├── 1de4897d42214c8a409f193871edc9aba48a77e8.nq.gz
    ├── 1e1cb6b69406efb92805b28483d1440c3d227b3a.nq.gz
    ├── 1e4bf06a30773a401e06883d4354f2f93cfadd90.nq.gz
    ├── 1e5ab6769e1920f3cf16bc21ed654549b4e749c4.nq.gz
    ├── 1e78b77b079f629f9c2832e1823674212de3737b.nq.gz
    ├── 1e974841c1f0ba2cc3f3e1c014b9161e24f1901e.nq.gz
    ├── 1e9d2f692a2e01d8544541de3d5aa807a2d51325.nq.gz
    ├── 1ea892b632696b5bd4fce0e2595f38eafc04c7da.nq.gz
    ├── 1ed6848f696673bd4713ef9a7141f02e0ab72ac9.nq.gz
    ├── 1edebe3976f504cf00788e318baec50b0c46637d.nq.gz
    ├── 1ededeaf0ba356d3bd451fd1a85866f033913a26.nq.gz
    ├── 1f0ba96f559f01651beb43cc9ce8b4b29d4a74c9.nq.gz
    ├── 1f1fef5fc8503af02754318d60e3bd864107b15d.nq.gz
    ├── 1f33caa5d7ba638d29b618b1514d5c74f481ea54.nq.gz
    ├── 1f3e7e25eb0344cb239360ffd258ad84f81a3a1d.nq.gz
    └── 1f88a5a75a2c10fcb574041cbf8c022031478a2a.nq.gz

9 directories, 200 files
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

[palantir/tslint](https://github.com/palantir/tslint)

---
*Parsed on 2026-04-23 by [repolex](https://repolex.ai)*
