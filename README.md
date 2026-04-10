# Repolex Knowledge Graph of mochajs/mocha

RDF knowledge graph data for [mochajs/mocha](https://github.com/mochajs/mocha), parsed by [repolex](https://repolex.ai).

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
lexq download mochajs/mocha
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 640f08a20d535f7860605b2fe4c54ee1b97cec86
│   │   │   └── chunk-001.nq.gz
│   │   └── 6cb27100c9a50c17a205803d343a2c369656f0ee
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 640f08a20d535f7860605b2fe4c54ee1b97cec86.nq.gz
│   │   └── 6cb27100c9a50c17a205803d343a2c369656f0ee.nq.gz
│   └── repolex
│       ├── 640f08a20d535f7860605b2fe4c54ee1b97cec86
│       │   └── chunk-001.nq.gz
│       └── 6cb27100c9a50c17a205803d343a2c369656f0ee
│           └── chunk-001.nq.gz
└── blob
    ├── 007f8943957f648c13e830bce1df2ce018ec367b.nq.gz
    ├── 00d99fdd7de862f0321c9f545a41e8ca5e0aedd4.nq.gz
    ├── 01385e1fcbd2c88c0ef722fca8c972057eb7527c.nq.gz
    ├── 01a9723277eb3db75c1ade64f0561e5d55e6c5da.nq.gz
    ├── 020e86e6893cd77f146eb4b6b3e3c0348d2a178f.nq.gz
    ├── 024f02519f5d2d78e99fff1202c03b95b0c47536.nq.gz
    ├── 026c876b5e6ec5fbfb216b21655926b5a17779a4.nq.gz
    ├── 031ad74a44918c0ab185d8b04284ce9f125f6010.nq.gz
    ├── 037111097bd8c3613ea1d41e8216ecb5965efa0f.nq.gz
    ├── 0414c11bc4f71fb0e7a93aea4e027039fe0ff3e1.nq.gz
    ├── 0419b441dfb3aaa1af3432187f6f03071eec1554.nq.gz
    ├── 045cc7591ba4550f12670e403dde54b58b5a20ed.nq.gz
    ├── 04801c1946fe302c224275fe4bf0cf5baae31e57.nq.gz
    ├── 0541b4c9dce3d38e178c99844546e62dfc2c4baf.nq.gz
    ├── 054a6ef7cbf3ff50f406e8e4e6b7d34b7fbd3f01.nq.gz
    ├── 059da3c39025be49ef3df118d7a517a5b9076ebf.nq.gz
    ├── 06f774503db2262c47d9bf9ed6e08aee2dfa3676.nq.gz
    ├── 077c75edb3c2aa5b58fe47ecb06a65f6e7ba003c.nq.gz
    ├── 0847d71321cbd2e72dcd535212a7c311b5456c87.nq.gz
    ├── 085978ef79ed87356c15f3216e9badc8917d7e55.nq.gz
    ├── 085e09bdc273fb66090b4cf9f452f09447bbd0b7.nq.gz
    ├── 0939d084ec6974f16e49e26386c5441344716ed4.nq.gz
    ├── 09a3ca5363e9b1e39b1e3916ad63a92a7adfd640.nq.gz
    ├── 0a5e5eb90067af0b06aa8efa3c43081223ea7bb3.nq.gz
    ├── 0a62b743223a205265e86f30f69032e8a665add3.nq.gz
    ├── 0a99babdc5f6e069ad9cff9795bda14746c76e29.nq.gz
    ├── 0aa1409e6a3974d1ebe18c281b24611ca78859cc.nq.gz
    ├── 0ac3a9e8d587829ab2052d45cc03beffef711aa7.nq.gz
    ├── 0b390cbf437ffab83966dfe2d1a25493ed0950e4.nq.gz
    ├── 0bd0c07c4ce02f2e07e3d9e641506faaf63202b3.nq.gz
    ├── 0c9ae4bfeca2a3cc2b2223160795c5e01872377f.nq.gz
    ├── 0d1411a79b47affa6aa866c53cc3862a15724600.nq.gz
    ├── 0df926cae7ff61224d3fb60cd098700d1b25f010.nq.gz
    ├── 0e3bc04afb1be236cf3ae2f5fc7006203ad1e288.nq.gz
    ├── 0e74abf606870480791171a3893dd043abe3e4ac.nq.gz
    ├── 0e9fec396fc486826dc8d9d4ac82206cffd0d747.nq.gz
    ├── 0eb48fb6f877d66b8712d6a132f9b573e67fa3ce.nq.gz
    ├── 0f22b6cf028dfd85021af016b9023d3b646d39e3.nq.gz
    ├── 0fa82096ecd84e528607da537ae8ad3271882d20.nq.gz
    ├── 0fb57dcb9d296d60c2ee84565fe59b3c44e5218f.nq.gz
    ├── 100d49aeb16603cf74fbf4b6c406a19e8f37edab.nq.gz
    ├── 1019808760f9a4a8608a849a3802ef58c916b480.nq.gz
    ├── 1071a461464d10ef992aeeb433c60ed17038d053.nq.gz
    ├── 10993214756a957fedb6d11bdbc2559b98df484d.nq.gz
    ├── 109997b297b0045fcdb1142e91222938614e5ae6.nq.gz
    ├── 10ebdb5473d722f4a769589d751395a1c2a277d0.nq.gz
    ├── 11ad7eadadfb1987716e01356824d2fbc8af4e72.nq.gz
    ├── 12582b231a3801ae72ef48dfc3dc7590339133cc.nq.gz
    ├── 1267942b7210d4ec8c1fc8786f7f426d635b8466.nq.gz
    ├── 13ad1f562bf8e4cb92cdb234bde2dcd7ec10ac18.nq.gz
    ├── 13ec97178ff93cfdec3b530fc2093d5378d8b035.nq.gz
    ├── 14346bf54ff00fe805520bbae84d403ec8ff7d1e.nq.gz
    ├── 14642c1e6b562accd1fc9b8aa09bd599689c6eb3.nq.gz
    ├── 1499ccdc6a91a6c8eca21f120f079de1ee7a811b.nq.gz
    ├── 16156b4b126157328fb0f6a63ce87cdced20d6b7.nq.gz
    ├── 1635a3ee3600dcffb62f515f7db6ffcc1f96b3b2.nq.gz
    ├── 167098148eae5bd7f5953c02e7609da39ca17ec5.nq.gz
    ├── 167ecc7b0cbe0381efc891e812ab08f705bd7ddf.nq.gz
    ├── 1797eb4e82311d326b8c3794e69af24e6944a2d4.nq.gz
    ├── 17a0e62f6119cfd32fb75f5b72b15b3f03239e1c.nq.gz
    ├── 18574574b8f0530663f3f182c45f865582cda337.nq.gz
    ├── 18eb7421bd3aa97230c4ca5232e95faff61a2283.nq.gz
    ├── 193ad3bf614c5a0d74000092008d346368036dcd.nq.gz
    ├── 197e27081096993b061c5e775e55a670ada36417.nq.gz
    ├── 199e9714aca58623e86fc5786813832c5173d204.nq.gz
    ├── 19a04f6777a82e00452e3384d1559dd954ff8f65.nq.gz
    ├── 19bfb86409e6f57587825b6f33e1deceb6760369.nq.gz
    ├── 19d0181906230d7be104e68ed080c240c4c193ce.nq.gz
    ├── 19d5724709c94e2b86897e8e1578dd6dedfd6cbd.nq.gz
    ├── 1a0dacdf43657b94e30e337b17f3e3599ee0b4bc.nq.gz
    ├── 1a4348dd28619c72c3d6b22f50608f447c0f2f64.nq.gz
    ├── 1a4707705f1b892f9dad2a669fc9887efaaa73a2.nq.gz
    ├── 1abdf879caa29b8416911d3f105afadb4109bb67.nq.gz
    ├── 1ae39ebb27d0313927e9efdccbaa771e8636ef22.nq.gz
    ├── 1b031334b1f853a70a9e0e4eeac56bf3389dda35.nq.gz
    ├── 1b34d1acf9d3b4f67888d4cf1296c768059a5be2.nq.gz
    ├── 1bbc2b19f95c4b809f5eb0c0fa91fdd30fbe4359.nq.gz
    ├── 1ceeb7719200115d7bb5c15d4578b18f35307fe3.nq.gz
    ├── 1d2ad0818643903153b2f7663edacf8f0ee7324a.nq.gz
    ├── 1e3937bb2e421457ab3734bf1c93e3f785864340.nq.gz
    ├── 1fe612007c89346695c8802c752d3d58916763dd.nq.gz
    ├── 202b375472087f7193a64740758389462599a404.nq.gz
    ├── 20345330e03caf5613e38569266e48864d5a4994.nq.gz
    ├── 2053a4b14f5ec08a1eb257949ac00b8a72aa32e1.nq.gz
    ├── 20f1e16463afc24b45c62308675489d6daf4a863.nq.gz
    ├── 2107533f9856f524112832b668d8f514ba365967.nq.gz
    ├── 2147afb77e28655475cb067f8e14752d858e9853.nq.gz
    ├── 2151aea65126e55ae3653a0e1f5b3fb18c2d5a25.nq.gz
    ├── 22942b2dc113d5c128c1e54a59e5feefbd5ca26f.nq.gz
    ├── 22b8eddd96663dbe5093ffd0b5539ebf1a446147.nq.gz
    ├── 22db1d5ed90971c23827e46cab7a9b88690fb468.nq.gz
    ├── 231fa907ec206f6b87b9d28a706e8ec816f17c32.nq.gz
    ├── 232645bc4b7d7bf52793be23bd40f009eb64383f.nq.gz
    ├── 23a45920d11be5914d6f65523ee02a62916b916a.nq.gz
    ├── 249f49a56699d21ce8a563d90917d1e4ddc1aa5c.nq.gz
    ├── 24b44557d9dd7f2e58ba4f8919eefd167eaf9c8d.nq.gz
    ├── 24db0b98d0d82b26f793922fbcfd50aecc5cecd4.nq.gz
    ├── 251a58b0fdc8677fdd4f7fe3e5e10d8bbf39c18f.nq.gz
    ├── 2530eec7832861f74eeae530ecf593e69ceb4b59.nq.gz
    ├── 258d49b4df827d2073b1b448fd1adbd0904d69df.nq.gz
    ├── 259c81af2d433ff469ceeab6eeaa9959e6c6dd40.nq.gz
    ├── 2626c9c04fb8e7d14367ea40018c55921627a31a.nq.gz
    ├── 27291cce17488c0ec1f02cac216468fd144cc858.nq.gz
    ├── 279d442c296bcc4480b96c7c94305400349e2635.nq.gz
    ├── 2860eef0bb04b3e3c3ec3eb905fac4c131a99aa9.nq.gz
    ├── 28abfb706c494171538055904850e7f8e1e3d5f0.nq.gz
    ├── 28d4a3c58685aca11ed477bc2155c8871dc7717d.nq.gz
    ├── 294d6dd5dd0c14620204b17f2b60533f4341b5a1.nq.gz
    ├── 298b3dae71af6e0e8f3035a1b0a8be5da7eac869.nq.gz
    ├── 2a79a39237ef6959d0c48d138958ec1cb0ad3ae1.nq.gz
    ├── 2af17af5917cb8022dc0dd678bf8c2a7d4398989.nq.gz
    ├── 2b265757a9b91b552a7d3a9019371f02bce33094.nq.gz
    ├── 2b4b70a0f4cacd6a8fa75793b3885a6d7fa82bf7.nq.gz
    ├── 2c65c9483693c0273d244b66434f59ac9ee1ecb2.nq.gz
    ├── 2c8f18d17aaf783182dfedeccb2b3d5136acc0f4.nq.gz
    ├── 2dc0756c31eb00b7545ac5c7654d0f1489de4827.nq.gz
    ├── 2e1f55e6a354f8466c8066ca3fa956c8a1946542.nq.gz
    ├── 2eba317744e5bc1c9d995cc5e9f31d821d868fd0.nq.gz
    ├── 2ee2ccd08955f424554c4a1dafe64cdf9c54dee2.nq.gz
    ├── 2ef817001bba12ecb37c0e2fdb1835da60c59889.nq.gz
    ├── 2f1d01c700fdc2b4af2432b12e198c3198d50725.nq.gz
    ├── 2f204a0b74364dcfc79f7c075b9e640a1434014a.nq.gz
    ├── 2f4dd5216dedd99cfa18b3da31a158b96a2fdb13.nq.gz
    ├── 2f4f8d56b137944c066a34cd35c3ef80bb7b3a92.nq.gz
    ├── 2f76a6fdada29cc1386116070b96b7d1bda7375f.nq.gz
    ├── 2f9b6074af2f066bf444b0363756daf550ffb68f.nq.gz
    ├── 2fd39d76ebc137fa41dda61d04c545683b2a8a71.nq.gz
    ├── 2ff4e1880f3822d7db0820e81f31ad1c5759822f.nq.gz
    ├── 301e72a8914af4bf3dd77383777a17120488b026.nq.gz
    ├── 314f3e6dff9191459b66695ba24ad63e1dd96163.nq.gz
    ├── 314fbdf2fdc6d4cf05325c87c1d77f614ddae9ba.nq.gz
    ├── 31a5639c6f07ffc3a8f25ef24d501841353d5642.nq.gz
    ├── 3224d47abd1922e33a856cf31fc65a5be1892993.nq.gz
    ├── 32ac8db53ac4affc5cfcfa239869c1fc70b0a3c2.nq.gz
    ├── 32b3332b97ae80c0845c0245818bd3a9d2006d15.nq.gz
    ├── 33043fa6b7d84fb901db9dd72d197b7e8ac599ea.nq.gz
    ├── 33084a081e044a3021fc33889da1a2ac051b65c9.nq.gz
    ├── 336a29bf599d356a698975fbac665ea05fca4970.nq.gz
    ├── 337d628991f044204f656a42bbf79ddf881d7ae7.nq.gz
    ├── 33c7089245f318157758474ccdc29d3872b2cd76.nq.gz
    ├── 3402dec93a16b04b60829d61f97d0e780fa878e0.nq.gz
    ├── 3415811caa2a1b2959cf1d591c3e16ce083c4c4c.nq.gz
    ├── 34268c4efe92877c60691afddbe28e3cc1dec657.nq.gz
    ├── 3463761f3a709888ec311341af8ee9142bf50a78.nq.gz
    ├── 3502b22a7303b750b95fe178ddb8403915af402b.nq.gz
    ├── 35d336d4ff45d065e93ce1b4609c1304ef0ae0ca.nq.gz
    ├── 362078b0a5a9332f9f2f831b23d025bd1b7c8ada.nq.gz
    ├── 36f0dd336df700e2aebe38486c938bb8af75cb85.nq.gz
    ├── 372cefbd9fca3361dbfe6775fd2fd108fe04db5d.nq.gz
    ├── 37988002f6f2846334e4331453b3259f2649a609.nq.gz
    ├── 38193eba4de36d5066726c6cb5b7844aafe0b53a.nq.gz
    ├── 3832a5e930248fc392794195088e7feae21b21e3.nq.gz
    ├── 3881f9329a9cb21e5658f280f820675f53568bde.nq.gz
    ├── 3924ac4082f505aee541a46164cc0fdcdb682cc8.nq.gz
    ├── 39323f3567ebd321f78e29afae15657172d32803.nq.gz
    ├── 399dc48a65bd770208801a427ea6858742949324.nq.gz
    ├── 3ad304bb86a31cbac69e48447c92fc2814b9701c.nq.gz
    ├── 3c63ec372590d1c1fbfa4c1403062c0b893e5bdb.nq.gz
    ├── 3c953972d1d113cc17807db8517ffb5e4ce5f537.nq.gz
    ├── 3d6d6a1f394b80067e0f05049b00b2fbf2ee11a7.nq.gz
    ├── 3d6f57737a53c61b94912081b28e79b69df5e720.nq.gz
    ├── 3d81c151034f1f7c2b84d3ba8affc8a6ee7250ca.nq.gz
    ├── 3d8b143e056a0ccde3db5b3bfcb5ac7736a0c7cb.nq.gz
    ├── 3da435c5aed63aa6fc29e8cd18e7e41d7f20fe18.nq.gz
    ├── 3dbc1ca591c0557e35b6004aeba250e6a70b56e3.nq.gz
    ├── 3e0a2f775c39fd373a01dd5ec7135185bb3caf33.nq.gz
    ├── 3f2dca46793d94e63c5d12012f2875adcc7296ac.nq.gz
    ├── 3f86af9d92e91539e4d81413aa24400ef7f86c5d.nq.gz
    ├── 3f8915acfac1624c9355ec9f6f34f10f2a435dd2.nq.gz
    ├── 3feb65963ae53ea1b07816366a82fe13b4873e74.nq.gz
    ├── 402cd66c97d6afa0a512d1228fc64629bca7a3fa.nq.gz
    ├── 40a1ab43c5641c569951f2bb6c8509df86606c4e.nq.gz
    ├── 41191e4291bf68258623c456c8993875f3b2e4aa.nq.gz
    ├── 412895c87cd76213b7638f109d3b3a6df7627b97.nq.gz
    ├── 41563b112927f545c47b583340fc2bd6ebca4bb4.nq.gz
    ├── 421bd859f5b5a2518a1a57891ba324677710acca.nq.gz
    ├── 429f73371df43f6ede8562872e69a3fd68988be2.nq.gz
    ├── 42ad37d8e1883a196ffc5235826ce3c2d59d3c23.nq.gz
    ├── 42e0585575e6b9a2566ee188a2a8335ad35df4ec.nq.gz
    ├── 432f018939cd50933e60b1f4b47d168ade3fb521.nq.gz
    ├── 43ad64422438540f339454a54b5be3747b45e40a.nq.gz
    ├── 43f53bbda8880bd7d66e9a9678dc4585213361f5.nq.gz
    ├── 441038198402f161c1ceb3b85914df5a61158b14.nq.gz
    ├── 441622bdb9f8add37dbfca370a1b5ed2f747986b.nq.gz
    ├── 442ad9321f0dbb0cc6c3a6c1b4e6ee425c8e6c48.nq.gz
    ├── 4469621abb8cdb69b21835f359ac8c1cb716ea8c.nq.gz
    ├── 44b800aba85d041e56a7517e3e70dd561718fd8a.nq.gz
    ├── 44bfd1567796976609e37fe891e6af2329378ada.nq.gz
    ├── 4589bf1db8f5c16e167c93ebbad5c5fe69ea67c7.nq.gz
    ├── 458e882df22e35f8130c1a022096ac5bf8c64593.nq.gz
    ├── 45ba68a2606a034a4edd1c97cc53a4ae675abafe.nq.gz
    ├── 46500098b2c2fec6da64e2735027b115d048755c.nq.gz
    ├── 465c86497b417fd9d1952a9771ef78241477b44c.nq.gz
    └── 46b1cc7e13a4e641bca265027eb7752c3f6e7745.nq.gz

10 directories, 200 files
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

[mochajs/mocha](https://github.com/mochajs/mocha)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
