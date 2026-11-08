# Repolex Knowledge Graph of vllm-project/vllm-torchtpu

RDF knowledge graph data for [vllm-project/vllm-torchtpu](https://github.com/vllm-project/vllm-torchtpu), parsed by [repolex](https://repolex.ai).

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
rlex download vllm-project/vllm-torchtpu
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b08f10fdc6166ff3aa3306629fcaf5b133012cb2
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── b08f10fdc6166ff3aa3306629fcaf5b133012cb2
│           └── chunk-001.nq.gz
└── blob
    ├── 001cc9a037f3721b1aabfcafdc69b95cf0a57e1a.nq.gz
    ├── 004c226d22758445c079a905046e051de049c1ea.nq.gz
    ├── 00bdb17287bf927dd7b50f83f6a61de444569e71.nq.gz
    ├── 01c5d1fb99619a00879a96848dcc77be5d85a9b1.nq.gz
    ├── 01fb381aac5d4cbe7ec33da1a1c066434a85c325.nq.gz
    ├── 037f6f1f6c76ae48f97bacdc61b16d16d42834f3.nq.gz
    ├── 03ad0ae13f0955966c20f0f6127df8b4514d620c.nq.gz
    ├── 0741de00f8df7886546db96d52e4ddc0d6465128.nq.gz
    ├── 07bb37d24905c24f68a5809c3d414c42b071325e.nq.gz
    ├── 0849f51789bddc0a5396c5e97bfea61e016a0bee.nq.gz
    ├── 0929d460e03f237e5411669629111ceafd228017.nq.gz
    ├── 09589f34b4e7e73f22a245c1734029d437c0dcaf.nq.gz
    ├── 0a2669d7a25a137ae4164f2460f3c4db756c2e43.nq.gz
    ├── 0a52b8dfb9c9e281b9363ea41aefdf479e77866b.nq.gz
    ├── 0ac9fd781b0bf9d75e455e7fcdfb1c5133bf64c5.nq.gz
    ├── 0ad16ed2ebde291c6138eade9db3cb779681c7f2.nq.gz
    ├── 0b06fb6a937e0abc854d7bc6492a931f1e1b56fe.nq.gz
    ├── 0b5a46ca80784cba55152812312e64dcec48de6e.nq.gz
    ├── 0c6dfab7e3a4bf908661d43e8d8b1b176b35234d.nq.gz
    ├── 0ce2434fb76f2b28b6df2e78d800343b0872e1a4.nq.gz
    ├── 0d886a677b02e99210c1ddb1d0d2dfb4cc555c96.nq.gz
    ├── 0dc82f762f397cf57ba4fa127c0558b6d1630ab8.nq.gz
    ├── 0ec2d453ea5f9355cac59e78262940105b598603.nq.gz
    ├── 0ef2c3e50ca5a210300c49f2475e8c763f4dab36.nq.gz
    ├── 0f8323aa374fedbf0b9fab591be98cf4f229349e.nq.gz
    ├── 0fd2afb0410e24fda45ad45b04d417e6aa52484e.nq.gz
    ├── 103862f9f878b198cdb3dc3d5f1b605040684aed.nq.gz
    ├── 109179b816afc82f6d92c0d03351b208d2162e7c.nq.gz
    ├── 115c1b8e5d0b53262438084cad6b5adbdea20a75.nq.gz
    ├── 11b15e8237e4fb7f75c3ac5818077c65dbd37303.nq.gz
    ├── 11e559825125d20275a0bd8479ee08ad7952a773.nq.gz
    ├── 11f9d726d6aefb6fbd791feb1beeb1106e1f2c08.nq.gz
    ├── 12c62657754fc0e66e85b496b9b2c88b4ff8549b.nq.gz
    ├── 13a9a104a3043bcfcceeda3368c56cde44f38678.nq.gz
    ├── 1415e1da0fafbbbe33dc6f6bcf6b8236bff2655d.nq.gz
    ├── 14271fe2f9ccc5394a84219f232f19203031f434.nq.gz
    ├── 1460351290a6eeeac350fca64f66d48d053ad8de.nq.gz
    ├── 146b9273b08bc124b7a72d929ab7c114aaf541f9.nq.gz
    ├── 14cc7d5fb9e2ae599ffb2249ec14f7faa81c1b82.nq.gz
    ├── 14f71d91b8b92ef08f7d705b2be4b32f773d3f74.nq.gz
    ├── 16026fbfbc20afd393a5fd9e5de0e7ce967d5e6d.nq.gz
    ├── 1649fb882ddc5a0f30715358e6b65172795007a8.nq.gz
    ├── 167087b82d380c9b6accd07c0e0a7f27d1d14104.nq.gz
    ├── 16805781b953667a9fddf87220ba72dd98c2dca0.nq.gz
    ├── 168b7b3539f80ebd842b07669dc5ee61610a526c.nq.gz
    ├── 17abaa6c94c1ea12b660ffe8636e915a81f815aa.nq.gz
    ├── 184223354ef3714146dbd8a9876ed2107508a0f8.nq.gz
    ├── 18c305f13c02dc917d1b06af05aa136811edc0c6.nq.gz
    ├── 18e8429a48fcb98b38369422cc23f7a0f4c3766c.nq.gz
    ├── 1a2b611888fab2a8df608554131ecfcdd68b01a9.nq.gz
    ├── 1ab2c3e23d5d87811939ebe06c704836dbbd2d17.nq.gz
    ├── 1b3f2560789d6a511583322ef8b2879ebfa31552.nq.gz
    ├── 1b497b48744448c790a7e1bdd41763d98d3a9485.nq.gz
    ├── 1b752a77a90631a01afbba8d764d9042cde60081.nq.gz
    ├── 1bf335b5dfc9249e0f76dc3743d6794e1e9c59d7.nq.gz
    ├── 1c4c25494f532eed94cc9dc728e5d7e9546e8b23.nq.gz
    ├── 1c7824e7ebeab9d5b38e5ed1131effa26178f2ff.nq.gz
    ├── 1da2bc9e985edbfc746dfabf7cf973416170d14f.nq.gz
    ├── 1ef4328d80c334b90f6d93fe6d62901c74221d9b.nq.gz
    ├── 1f1611a0a1d238c27c10d39461387b55d1eb92db.nq.gz
    ├── 2057ea8e27de527ceb667400489504413746fb25.nq.gz
    ├── 217df91e804b428d1b6216bdade52dc50aaf9df4.nq.gz
    ├── 2284de5229ccf38e2f0a122cb580c5afdd01b0eb.nq.gz
    ├── 22c53276f0605394adda9abcf580b279804e8749.nq.gz
    ├── 23372da988707f071d5365da1fcb408e3c5d5b13.nq.gz
    ├── 23439f5d266501fbd0b00e2e59cee702748329f9.nq.gz
    ├── 23803d6b741ba1cdb551bda51c9837bc68b6b466.nq.gz
    ├── 23fe030a84e4e1f26c41eabb72164a66b52364fa.nq.gz
    ├── 24137566cc285a00b53366213720a94dff432f48.nq.gz
    ├── 2669d2d7bf0fe5d6a15006c3e28900e92b0fbeac.nq.gz
    ├── 272baffd2162ecdb1263f50372830ad6353c4fcc.nq.gz
    ├── 280381c2ee2a7a4abd7e2d47f10ad30761e6a2af.nq.gz
    ├── 2906a6f1bcfc78f0fb38f20318610171b38c8070.nq.gz
    ├── 2a46f3246ad04cb844a9f4d25de31ce46f7b065b.nq.gz
    ├── 2a5738da2097012012d11766f294f800d8339563.nq.gz
    ├── 2ae870bbe555cad616eec03daaeb8a66f3fded9d.nq.gz
    ├── 2b576bca2d80efef7a9cc2d81bf120c5e6d96ad8.nq.gz
    ├── 2c5aac030154997bee0208d129a579d5bfe4b6d0.nq.gz
    ├── 2d25dd2e32ef421f2af415dfef12efeaa241b2fd.nq.gz
    ├── 2db7538834ef1cfd4297cc576cb4110d5fb9f2ea.nq.gz
    ├── 2dde7753eb4276c01f916a7984dc4b12ae600cc6.nq.gz
    ├── 2ddfc500f38defd8382cd305b35a698c9ec92781.nq.gz
    ├── 2deeed142d6a8395bf53485b94e4e1e5d591889b.nq.gz
    ├── 2eb4cdf0239ca362c5b0e34121dc5e0ee46066bb.nq.gz
    ├── 2ec51a91a85cd7d59ae0c7e3d55554f3e9ba3801.nq.gz
    ├── 2f2171159d28fa416d3d4ff550d1dd5b030a5ec0.nq.gz
    ├── 2f4ede3575ff0421600602361cc497e9e39435ba.nq.gz
    ├── 2fbb6ff964718a7b4d661b9990310108fcbc11ee.nq.gz
    ├── 308f70caade44a071a96a2be65690527d350ea08.nq.gz
    ├── 3291804a9ef246ab2d96876ec1a7f2cd66135e19.nq.gz
    ├── 32c158ce13ae5841572ba14b4ffbb5ce51d0975e.nq.gz
    ├── 32c177641f419d7ae0130377f58467e36e4f8f1e.nq.gz
    ├── 33853fdcec0dfe868dca8ce4bb42f4f631d5f0cf.nq.gz
    ├── 33bdc175c532da38fbd08a31b66a62d8e7f9834f.nq.gz
    ├── 360415e9582226f392f6498eb3780ec8b557136b.nq.gz
    ├── 361e6f7c50b38945ee6207d8055e3af54cc88a72.nq.gz
    ├── 380543c38c67f65e1a153a598c435475beb93cb7.nq.gz
    ├── 3823350fd07478335dc13b44e7a0dad2e5fc53b6.nq.gz
    ├── 38cd08dc920a4c8bbe6100984344195ec201c1a5.nq.gz
    ├── 393ba0a894e66246fe29efd88cce0e4812c5fbed.nq.gz
    ├── 396fda4a925961f0f158e09438e2e291ae4c433b.nq.gz
    ├── 39746a2b4fab7235147a70b35c342d6eba9288cf.nq.gz
    ├── 39c22de476a92fe28e420d1353ea2c41e0048449.nq.gz
    ├── 3a29e29b511324e71abe4c3a29615894220eb6ce.nq.gz
    ├── 3a49cef108a3332192b8133616dd7efaa57fb80c.nq.gz
    ├── 3b5c2e509e6c73697587bf2365beb28ba4e9c462.nq.gz
    ├── 3baf50adde07af8cde94734c3410d9257f88f99f.nq.gz
    ├── 3bb8429aa963a553a59c62a16ecb95dd67a781b1.nq.gz
    ├── 3bbf4bda6d1469e53a024b3e78cc537e56e4d4dd.nq.gz
    ├── 3d6a8e9871cb496f6cc35d6a61f5690286ee4f99.nq.gz
    ├── 3ddd06e1d41a19108343961bb66c229fc4ea20c2.nq.gz
    ├── 3e76b735b1242d8ab382f24904cd93fb1595f42b.nq.gz
    ├── 3e9c69709b817f6b7104a4455d45bbdc7be55bc4.nq.gz
    ├── 3fa6c7094e1236230b7c68402a10f9b28a85af26.nq.gz
    ├── 41e795f7c8402d6802b19f19ac3462b3a839c8a5.nq.gz
    ├── 42a29e28ed7463dde448da97b0c3a41e4846d652.nq.gz
    ├── 42c11d512b45aa72ba6b3769c896eddfa1d20578.nq.gz
    ├── 439e7bb623c8bf14e5a76c39b3a3008a5610908d.nq.gz
    ├── 45e889bc5f9f02f799492c27c2a232a31633ecd4.nq.gz
    ├── 463d9611132bb25c748cd85178f7a57e7ca0735a.nq.gz
    ├── 464e3354d586a87a608b2c3004b986458019761a.nq.gz
    ├── 468d167c3493b8b80bb76c956822ade41580da40.nq.gz
    ├── 474ceac7af6ec0a3414de925343f595f8614bb7d.nq.gz
    ├── 47a22e5b630ac57060036aef236514e992096d61.nq.gz
    ├── 47e78abdbdb8bdbb4a6eff1369ed43914e2ab64b.nq.gz
    ├── 4806d0dc17ff5d6aff2931585c61730ea353c4e8.nq.gz
    ├── 48080fc04ced300a727372c583c5ecb0089c1806.nq.gz
    ├── 480a8e4f468cb4a2962940b749562a4d2071ba5a.nq.gz
    ├── 487c41b20beedaac2ed7cc697d93eb523c5432e2.nq.gz
    ├── 48972922cff56075029ab4f921a3793991ebe2cc.nq.gz
    ├── 48d0b9ca3c215fae9a16ad63bba68886d7ed7e9c.nq.gz
    ├── 48ffd8be1eef5a19ee302002277d2cef2379d874.nq.gz
    ├── 49ae34bb8ca009348fbdda7af5c8b24ecba90491.nq.gz
    ├── 4b00456e8dc55ca550cf1dd13b21aba0587c2f3e.nq.gz
    ├── 4b3393743510783a78328d44fcf20bfbd2534161.nq.gz
    ├── 4b7462cca15c1081b4be99f9b4f8e4c4ce5dc678.nq.gz
    ├── 4b8118506afa924e295aa0e23d86a5bc6c7bfc14.nq.gz
    ├── 4ba33be45c0894c6bf018c3a0e5d2235bfd1ee52.nq.gz
    ├── 4c45c990898f8774e1769917e3bd038bc49ac125.nq.gz
    ├── 4c75fb1cb91646591c3b5a8aecdf16e89c651bca.nq.gz
    ├── 4c7b3d189615479c8fcf2d2f5bdf1d4d029cd098.nq.gz
    ├── 4d06aa87e944e64488b58987370319b11c945f85.nq.gz
    ├── 4d42b4b6f590fb39a2ecbcc7e5a88f3f23711849.nq.gz
    ├── 4daa6e9f10be549658687a78645a706771b9f51b.nq.gz
    ├── 4dd857c6d5b635009de2ce31a20b5c1789a46366.nq.gz
    ├── 4e9f18e3aacdbe1cbafb2d91055dbab274631ddc.nq.gz
    ├── 4f9d91cf1d5cb4ec04198fa427147999ca34bc9d.nq.gz
    ├── 5005b2bcacfa5886d5743a7f691582efd466459a.nq.gz
    ├── 501716eefe6dab2e48c517b97aaed259f74ce61b.nq.gz
    ├── 51092f3f88e2a9d44031492d164e9d0f9b45e156.nq.gz
    ├── 51511aed30743929852b7e3eca14c0fd88aa02c9.nq.gz
    ├── 51641e5bf032a09534521345f178a54687265f90.nq.gz
    ├── 518cc8a6cb02707fae7ce65c2f2f459049804ec2.nq.gz
    ├── 51edf5bf245b599ef302c0f71441ca1e0c5a3f7e.nq.gz
    ├── 525e53e1b877c1050ca614ff13c36d667921499a.nq.gz
    ├── 52ecf9569be46616d8738e4ae06ce749a90b2f3b.nq.gz
    ├── 5306144799acf9b4288ca665b4419abbc9f6cac8.nq.gz
    ├── 533b1e5589f3682f8c62cfe68ade1694439e068b.nq.gz
    ├── 535a8dbd03379e17ca171cc084bda029cf5c0ae8.nq.gz
    ├── 53a30b1a147adbf5e34c385063ae1dce0c9eec4c.nq.gz
    ├── 5458d6dd237f668523bf251a2650ffa110354df4.nq.gz
    ├── 54deda244c4de9ce68f6391b38c54040c55b3143.nq.gz
    ├── 56cc876f9ec198c37895fdc43e5d6d80f34449c7.nq.gz
    ├── 574a67119c081e158a2918d373d8c1c80b4efd64.nq.gz
    ├── 5776969c89ca64e785de4280bc7a3c2d45e1d202.nq.gz
    ├── 58d482ea3866250ed5f1eb02fdf1da14377214c6.nq.gz
    ├── 58f41cc9829a9d78277a94af4bab03ecefac4597.nq.gz
    ├── 590d415d8454a418a59ada56cc83517029bcb4f2.nq.gz
    ├── 599000ea804bf25cb606f64f56735682aae54f9f.nq.gz
    ├── 59db812da0fb057130738d9231153c6719a36ef6.nq.gz
    ├── 59eb218eb60dd98ecad54e389901db528f88b538.nq.gz
    ├── 59ee897802db8925718b7c990f3a4e53227d1b3d.nq.gz
    ├── 5a34cfa58f6a6c4d3b5345345667c6f8562fd629.nq.gz
    ├── 5b5c8682d05f4d61dda73badf2e78e4108dc1270.nq.gz
    ├── 5b925c2b1f54f792dbdc0d8b918d2a9453126491.nq.gz
    ├── 5bc34d90564e993e23f220650835a584abb0862d.nq.gz
    ├── 5be1e3fdaae118c2d7b3492ef3a658737745729b.nq.gz
    ├── 5cdf8dabf303d28da03c4ae0f8c14974e208068f.nq.gz
    ├── 5ce75420d7b1369a12f3e4e1319634964a199b5d.nq.gz
    ├── 5e109e0a838d1e2464fb5e651f8518c52be0843a.nq.gz
    ├── 5e74358e513ae5bc5d9312bae3c927b789887c45.nq.gz
    ├── 5eb100bbb43c23dc715bcae547ee65f4d21cd893.nq.gz
    ├── 5f7c4f869a0736c7fec2442bdc22a83ce17b253d.nq.gz
    ├── 603edd96d2313f380ae7b3664209ffafd4dc1974.nq.gz
    ├── 613b69e85e98f3788ad7b92c4d747d0c7bc1e450.nq.gz
    ├── 647566d9172f4fe70d00b1df8e43326d0daa7ba3.nq.gz
    ├── 64dc983c71a502fc9a4585c3ece6314e7768c9b2.nq.gz
    ├── 663428217f91b1aaf96469be8401ac199705402a.nq.gz
    ├── 667cc8cc02978986726e79567fbe4f13482977bc.nq.gz
    ├── 6684442e8626ce4f6c59eccd493c43e557d2bc81.nq.gz
    ├── 670a868467a58c0ce4176125b07f3b4b8fecf2b4.nq.gz
    ├── 68565719e31a791eac5fdfa3157615d1aa35acc3.nq.gz
    ├── 692eacc7882f2acef9d4165cd748d83b8f83de50.nq.gz
    ├── 6a5b855d744bd79ff0c0e0f6e6ec0b1645f4195c.nq.gz
    ├── 6ac5733eaac5b238b5e1cf8f185c6f2bc03af45a.nq.gz
    ├── 6c239ccc359444b0fdcf7421c3cf75a4ac216328.nq.gz
    └── 6c7e8e5ac38c5afca3b6fb7de5d8fbd638058cd1.nq.gz

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

[vllm-project/vllm-torchtpu](https://github.com/vllm-project/vllm-torchtpu)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
