# Repolex Knowledge Graph of aaugustin/websockets

RDF knowledge graph data for [aaugustin/websockets](https://github.com/aaugustin/websockets), parsed by [repolex](https://repolex.ai).

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
rlex download aaugustin/websockets
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bc17da4841b32dafdc036c0a35f7ccd2fc5d9b23
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bc17da4841b32dafdc036c0a35f7ccd2fc5d9b23
│           └── chunk-001.nq.gz
└── blob
    ├── 006aab673cda3bb1cc7b2295fd85b00d85b4b479.nq.gz
    ├── 00bce2cc6bb19fa280a6ef2b3481403e6f6ba74f.nq.gz
    ├── 01909bdb1c0c51879eca40460c6b188a331baa9b.nq.gz
    ├── 01dd5b168e4876292e7fe7547b8314b8b7032d9d.nq.gz
    ├── 0211615d14ea0c9aaad052b6dee3d6857c1e78fe.nq.gz
    ├── 0252894b76b3c182a34d6ec02a8990cb6d0238ec.nq.gz
    ├── 02838b98a5335322daad566de9c0d9d0843fc49a.nq.gz
    ├── 030049f81520b2abd727979a0f2f6af436940664.nq.gz
    ├── 035834a893302fa6b5cf0f656820a7270c6bbf9d.nq.gz
    ├── 044ed60431f65839650dd043c037df712812e884.nq.gz
    ├── 0458706458855d9fa48dae9b3d0eca001ebe3c7c.nq.gz
    ├── 04a7466fa24b057e04e2f867ab3cbbf15539dc7f.nq.gz
    ├── 04b4739c69ed584a932796cbf689c1c70a8fc8a1.nq.gz
    ├── 05beeb26f001f4ac649892d335c343446bec9e45.nq.gz
    ├── 05c629bc91ac5cf6680fc3ffe1df71e0b19dc0e5.nq.gz
    ├── 07b675b175f9406c4d53694c4564ab501eb601fd.nq.gz
    ├── 085f7cfb8316815f7fedd8ce83be98c3567de426.nq.gz
    ├── 0959e8fdb797ce1fdcb7eef91ff865a4edb26164.nq.gz
    ├── 098f1471774d01d53fc294d0ea67a580f599f175.nq.gz
    ├── 0a1a66613289612269641e97dd9fe60e4cab2dcf.nq.gz
    ├── 0a3b8703d568a951119da2630fb387fb9fb83854.nq.gz
    ├── 0a9818d2930c50f638ade86a2f16fafd254a13dd.nq.gz
    ├── 0d210fc64f34b5ee0b37acbb5ec794f94d7d1e7b.nq.gz
    ├── 0de2f67072c9e6c04af48ad3c14d3e5c87419079.nq.gz
    ├── 0e45a9f8578a1a4633e88836a124fd87bc099d78.nq.gz
    ├── 100671db594e91fece286d97c2e51e5ab95c7d3f.nq.gz
    ├── 1044769627011bfa2831f4f9c34946da697e0b8d.nq.gz
    ├── 10896fe9377ddeb9877ec9e18e9e78c217f14438.nq.gz
    ├── 10cea8ac3566f63a830a6f49e55c5d8fe72a7f10.nq.gz
    ├── 11a452d55ca76f6678846ed8cb9c2cf34b676fd7.nq.gz
    ├── 12b38ed06d5e925772d4d2b48397f6f07b07b264.nq.gz
    ├── 130ec7bfd46a46acba2bc298446ae1b69e360b67.nq.gz
    ├── 13ae36c08e9d7fffc5e58a4c82f3989a1617077f.nq.gz
    ├── 14774b465e97f655dbcaa60d97c8a9aa72e7d51b.nq.gz
    ├── 1509a3549d7b810d0da558f6b29ee9bfa1c77921.nq.gz
    ├── 15b70a3727b2eb3202fc87173ad2fc8b742cf72c.nq.gz
    ├── 15d49228c5d03c0965e094052d2cd2485521b272.nq.gz
    ├── 16c00c1b9501b253e3e58fc18436cf9045917d12.nq.gz
    ├── 175b20c589ded2c7c824a4484de9b7cf4e9367ef.nq.gz
    ├── 17fe8b9ad66dddb2f698b7e32fed77def8dc87d0.nq.gz
    ├── 18b37456e1a58f35e277aa807d9d1dcb2edccc6e.nq.gz
    ├── 18c0e2a1151f184cfbcab07101534882175ff5e9.nq.gz
    ├── 19805c30d3afa7f412c326c611f12f82dea7c80c.nq.gz
    ├── 1accba49ecc4bac11a17edbf1e92b57e02d89801.nq.gz
    ├── 1acf048bafb3fdbca5a588bb7b6c3d5a82cc184e.nq.gz
    ├── 1ae95a7cd5884c6aa2ee5357a15f637849d6d9a5.nq.gz
    ├── 1bf15e25769d1d38535634b57aedcf47bc5763a6.nq.gz
    ├── 1ca70bdc001c3d4ad0ea352537a1f380d20f4024.nq.gz
    ├── 1dd96b541198db4f7ff23c6dcb044116f24cb85e.nq.gz
    ├── 1e9539da2bb784d4d26e86dd410058916e453e3c.nq.gz
    ├── 1f26df715df433ba43d9f17e8d6926b3dd4aeccd.nq.gz
    ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
    ├── 21369b0e76ef6a8f1c18e9725ed898d867c1bcb5.nq.gz
    ├── 219879678eb3afcff7612f524aab1bc675f300d1.nq.gz
    ├── 21aad6e0261b9849926faf19193332c86e0e6176.nq.gz
    ├── 226f74a3a053df1ffeba4d5231dd5b075facb431.nq.gz
    ├── 23345962e9a35fe2082f2dd9a13a5fef354b47aa.nq.gz
    ├── 24fb74b4e6ede2843df9dccd858e03f2e3c0d9c1.nq.gz
    ├── 25750c1f4b94a4a57dbd59f70042aac49ae4a21d.nq.gz
    ├── 25a1b1ef5212dc96e6ec357891747e9f67ae5656.nq.gz
    ├── 26bed7ec9e79abb6ce8c899ce12be92df69094b8.nq.gz
    ├── 27abcdabd890af8cb23a1abafbac3b59f34cdb39.nq.gz
    ├── 27f0baf6e457f41eea2da6094a368817d5c001d2.nq.gz
    ├── 291bf1fb6d0e27973327041a69a6a7c039eb3389.nq.gz
    ├── 293e41a29891c9fa6065d96153569af07b37bd31.nq.gz
    ├── 2980a97b428f5f1d7fce99f37f13851358cc117a.nq.gz
    ├── 29a2525b4e73b788f773682ce0b88e13eafc6e26.nq.gz
    ├── 2a722058741be23f9edf683d58bb51907af2b244.nq.gz
    ├── 2aaf248ba5ad3e49ee39981b2147963d2cc7247b.nq.gz
    ├── 2bdab94645f60badc81a0cdbc7d42efc65725809.nq.gz
    ├── 2c5bae5c1ffbe53aae660ea8c9598deac1e7a653.nq.gz
    ├── 2cca34fcbb49cceccde7b7e3b33962e7f4455ff2.nq.gz
    ├── 2d1ed4a2c098577bbf34c012a2a8f309326a5a84.nq.gz
    ├── 2d2e692e8d252a1d296b1f3f862f69bdf340b863.nq.gz
    ├── 2e35818f675d5a1a7b6a84e4561bec032180c1d6.nq.gz
    ├── 2f05ddc225577125ac018702cfe4de55a1aacd71.nq.gz
    ├── 2f3342aa51482b27a68c40db5566450a3e6421c1.nq.gz
    ├── 2f73e2f8753bdf1f9bb3a9503cf3c27b44c70e76.nq.gz
    ├── 2fdc59f0fdae4d28fdcf18b6f9edf8d62ad22f01.nq.gz
    ├── 3152f174ed2a8c771233047375f762ab55dd2997.nq.gz
    ├── 317dc4d9852df72ba34e10a6f61d1838cbbd969e.nq.gz
    ├── 336d9b51453d5a600977497f7fc2328dec92ca8b.nq.gz
    ├── 3417124758a9a889de4845fbd821cb5381b396d4.nq.gz
    ├── 343e7125efad5929e187fab4afa79797c0905fa0.nq.gz
    ├── 34a470661c903cecb4a5333d4c521173a05957d8.nq.gz
    ├── 34f16404c71c5b42e9cfbb7fa59a757cd943b9f6.nq.gz
    ├── 357eb4cba1fbf7b441733e89748c0eab3612a948.nq.gz
    ├── 3614fbd1ce2c9714ac998b5c74cef033202e58af.nq.gz
    ├── 36346977aaf2c282ef4b46cfeb63879a282cd1cf.nq.gz
    ├── 36e855029d705e72d44428bda6e8cb6d3dd317ed.nq.gz
    ├── 37d892a28b447e243262757c225204a48d60286e.nq.gz
    ├── 384caf0a2c16228ed01c911ebfc751109377a297.nq.gz
    ├── 393e0215cd85151a06226e42c74aef117873ee81.nq.gz
    ├── 393fc8e2ea7d1490b528c540c5f272e4797df818.nq.gz
    ├── 3a7a0db49ee94a31fb5e270c6817ea676cb5b200.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3c23eb877ce58afdfa0729e83a858eb26926ca97.nq.gz
    ├── 3c62b704383856770e9f2cf1e74818ba4fa6a760.nq.gz
    ├── 3cd7464b263c9d99be069f2a0b3f454e89daa693.nq.gz
    ├── 3f6f7dd90e065bd1271348a50732d2750b1573cc.nq.gz
    ├── 42100fade9b2ab8abcfd6bb3876befca893affdf.nq.gz
    ├── 426b6f38625c7069b71c25030cea9a037be58808.nq.gz
    ├── 44d89e00b48e59a6f317c547d179a1c96ec16077.nq.gz
    ├── 45b1bb573a551eff27726507dba17cc5f820eda3.nq.gz
    ├── 47db986b745e92e8d29714ddf4c08a3cd3e71ca6.nq.gz
    ├── 4b0190c79fd9aaeb63b54a69a277e4c248b14acb.nq.gz
    ├── 4b3ad9b13722f48827fa1751b91920db84a69d45.nq.gz
    ├── 4b47db1ba56797f86b9403fed1035ee99874c1f5.nq.gz
    ├── 4d2b2ad9952d801190015f0f763c27db35bd7eae.nq.gz
    ├── 4d40f97c44eee138d00c163d24bdfb317a8bd5af.nq.gz
    ├── 4e6ff952bda5ce229e2005d45d032803c420e030.nq.gz
    ├── 4e843daab34f865b012ec41408c2804b6ddce9a5.nq.gz
    ├── 4f34c06284890ca871a26e0796f041092405fa7a.nq.gz
    ├── 51bfd982be7bac755c318376e79b6f7d3dfd91ee.nq.gz
    ├── 524fb35f832eba51a76b876bfba8b1a9a86db6fa.nq.gz
    ├── 5290072ed28c6b804295c6028e300e958d515fc2.nq.gz
    ├── 5333f9a259933455d2c339596adea1dca64dd7bc.nq.gz
    ├── 546f70a6f9f2ea12d3112bd13fc164e6481c79c2.nq.gz
    ├── 55a9977ca4005a94b5b833df6efb39ded822f61e.nq.gz
    ├── 56c98196acf6a7d8399caec8cced954cb2b9f68d.nq.gz
    ├── 56e2621141a06c14e3fe6db0a57cc5ddd4c01c6e.nq.gz
    ├── 579ba87f8e1dd03111bac7f6a5a45726eb51a17e.nq.gz
    ├── 57b4854b8c7915053db3ff350e1c691035e9dfd1.nq.gz
    ├── 58f61af0dd478f402b24ce87e0440b59cc646678.nq.gz
    ├── 59920a3f2f4a53eac8e2b107970358fff0fcd68e.nq.gz
    ├── 59a51b6e33810bc0bc34b7d2ea6e47b0fd8be78b.nq.gz
    ├── 59e0cea0f4393082668833c7a488eb87576a732d.nq.gz
    ├── 5a73226a85ccb3170e8a375a92ef4e2243c92769.nq.gz
    ├── 5b585dcbb5a8f1dcdcd754a476abf23121c958ab.nq.gz
    ├── 5c0ea05f2b9d3201923482975f04fd00323dfde3.nq.gz
    ├── 5c5ca1bd297e53afd03c1c471d9cc6b2543f7dfd.nq.gz
    ├── 5cd673d979526361b5bf01b315b14edb19e56150.nq.gz
    ├── 5d61ece22a75a759aed8e52af280eca28d35d6bf.nq.gz
    ├── 5e78e34479224d0332b165badd67a8933e0c73db.nq.gz
    ├── 5ea89c28480ee0984c7928d01ef3a1583ec7b102.nq.gz
    ├── 62010f454db38490abc6d42ba78c405b2e22d57e.nq.gz
    ├── 6202fb14a0ea9fd296918647d818c3e5dd76d30e.nq.gz
    ├── 62ba9d843ffc665cfdf1b3678fb0d02603de1e5b.nq.gz
    ├── 6348271867d4625cec188b34001b41d922b9ead4.nq.gz
    ├── 64334f20fb31c05a7f8fbc724931313bbe23bcb5.nq.gz
    ├── 64494b78780415090fcf2dc9e0ca3d897f7ec2e7.nq.gz
    ├── 64a393d534979f85d7365f9006380ce66af8a5c3.nq.gz
    ├── 6596c9f32f860cc6a78fda8c8f8afbfed57b9f68.nq.gz
    ├── 661ae64fc47962d7a6d0428a23c193e7c73517df.nq.gz
    ├── 67aa0086d54f3dd0fd230b6ff6fb68bf502e9b09.nq.gz
    ├── 68f2eec6cd0155cdcc79049cccb65a5cd974ce90.nq.gz
    ├── 6906720a49d3a83b92b3386ebe57aed2f2e488bb.nq.gz
    ├── 697b02e90aa4b0e89b373bbcae61282722bdb7ac.nq.gz
    ├── 69bfd5e7c74a8bff0621a345f273f69b39bb263a.nq.gz
    ├── 69cd37aeb785f1d106564b7d2619d8291076c026.nq.gz
    ├── 6a54d0b6caeb5288cf4248c1b4c7d299deee8a00.nq.gz
    ├── 6a7157c010720733ca42d363cd810c354bf9d221.nq.gz
    ├── 6cbdc9c79f784a538f6470cdd0bca3af53c2c258.nq.gz
    ├── 6dc827f72d70f1e63a542ecfc7764d43a8a7cd47.nq.gz
    ├── 6e3918ccae60e096d8ac491c653911f85abbce22.nq.gz
    ├── 6e4518497c80e89e5ddd8a8b4208638041c4aa59.nq.gz
    ├── 6ecd175f87be054d8b4ae04e910d688f2a0d340c.nq.gz
    ├── 6fd2d4e6e69783435f339608a3c1676aa12cacc1.nq.gz
    ├── 70df9151b264b4e434ef6783f02245c5c641da4c.nq.gz
    ├── 71ad86909e44af12d80a9edce979499164f7e445.nq.gz
    ├── 72ac12a0fa4891341ed3259ee0066240ed0d1476.nq.gz
    ├── 72f5d6bea43b1f075f2a75bae6b1970a0ae5234b.nq.gz
    ├── 749d9d482d2f01563c0226f96042b03b3b3521c7.nq.gz
    ├── 7547b6abc33f3d2abe96e4fd15228d4b5101fac3.nq.gz
    ├── 756ad03b6522647ca131487ff837850c31befbab.nq.gz
    ├── 76a664d91b12dead5d4fc196a62095172986fc17.nq.gz
    ├── 76ce9c2d7a554b113ad06adfd82ec9eecf4b327b.nq.gz
    ├── 76da1c2fb1aaa723d31c769eee5a78768aa26aba.nq.gz
    ├── 7736105c546c9e5456c3345659daf808740d9f08.nq.gz
    ├── 77a4fd1d85ebc29efb3f0b0e0a0e636b06fda6fc.nq.gz
    ├── 78a5ab7bd12f64da441a81b284a065873af85836.nq.gz
    ├── 7b6ca58dfb6d2b74a4dbec8c606c0889d7e56e77.nq.gz
    ├── 7c022066fd01b9eb7287428817dab928e36cda39.nq.gz
    ├── 7c4ed2f3e0a84255c16ac03a98a08aec51850048.nq.gz
    ├── 7ca1d9cdd35b8417f104e3690bfbe1dba911ea1f.nq.gz
    ├── 7d2da781f26c06ec733c78f0221f0bd4fefe5727.nq.gz
    ├── 7d5447ac9d9960cbf2f03358ed2b7a2719bf71b9.nq.gz
    ├── 7e21e7d47a653d0771de13bb8fd0e7f9188a4968.nq.gz
    ├── 7ea3a5e5fbda3c57267692270ac30fe9d01200b5.nq.gz
    ├── 800f48f7354e5086b4a31b8e12886d4024b7c3dd.nq.gz
    ├── 80f80d51b115134c79329b69f02c47e3906e0f59.nq.gz
    ├── 815e7a419880fe4706345892438c3b03253cb942.nq.gz
    ├── 816afc54159fadcd11927b0e9650a38aff734623.nq.gz
    ├── 821576020ee8ad2984226b1a7115c1ad9b5f669b.nq.gz
    ├── 831d476dd50fbc693548c6f45c29f581363d8483.nq.gz
    ├── 841dccaa47eec230f1e3f6bdc09d1d49b9a93fc4.nq.gz
    ├── 84c3167583727707591d187ff475d68e900b9c19.nq.gz
    ├── 86a1c22ec7a717b1a2c362b8a84aac276cf9df00.nq.gz
    ├── 87201c9e4acec0b9217b4c7a102eea29d3cb04c2.nq.gz
    ├── 87d96ab59ba98a8bed145e413e504c91e202729a.nq.gz
    ├── 87e66f64ed7607daa0c2ecfa37a94c92042092cd.nq.gz
    ├── 880ef4a2acb42bcf13a3f9aa532970160db14ec4.nq.gz
    ├── 88c273b2a0585e3d217bbe3f5e191075b65ca3d1.nq.gz
    ├── 88ec174767c99267a6f2ef289e222ad38051c907.nq.gz
    ├── 8961cbdc266f0fdb516d04320bccb31140a985df.nq.gz
    ├── 8a285e92e5680235e7196d234b92fb383eb564eb.nq.gz
    ├── 8a4981f5f36fadbeb2d5999e3eddfc166f288d6b.nq.gz
    └── 8b3c6a47283eb0ba38819219d44b7b9df634fea7.nq.gz

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

[aaugustin/websockets](https://github.com/aaugustin/websockets)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
