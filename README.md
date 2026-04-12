# Repolex Knowledge Graph of materialsproject/fireworks

RDF knowledge graph data for [materialsproject/fireworks](https://github.com/materialsproject/fireworks), parsed by [repolex](https://repolex.ai).

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
lexq download materialsproject/fireworks
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 7897db27c0dbb9769c3a57169f8722507e2878dc
│   │   │   └── chunk-001.nq.gz
│   │   └── a2b14e3f731dfcb61cfb43912db9116f062700a9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 7897db27c0dbb9769c3a57169f8722507e2878dc.nq.gz
│   │   └── a2b14e3f731dfcb61cfb43912db9116f062700a9.nq.gz
│   └── repolex
│       ├── 7897db27c0dbb9769c3a57169f8722507e2878dc
│       │   └── chunk-001.nq.gz
│       └── a2b14e3f731dfcb61cfb43912db9116f062700a9
│           └── chunk-001.nq.gz
└── blob
    ├── 0196d84ff83f8a2c32a05330a22f7e55cb78d221.nq.gz
    ├── 01a9ed72952ba2fe551e934ac9e13e7ca3d57f59.nq.gz
    ├── 02158cde496a218bd696f330edd931d6d5f86182.nq.gz
    ├── 02d78e3939edef2e36f65a8f42785a4129682ed0.nq.gz
    ├── 032e1969884eaeeb959c5070377bad3e2542051e.nq.gz
    ├── 03bd9afd7dbb970bb70e5e42e84b9df28dfc87ea.nq.gz
    ├── 048cff973981e8dd4ed8e73c4ca532ffcf02e1e8.nq.gz
    ├── 0537aa681ba290d32312cf9e7c061505e1c3a05d.nq.gz
    ├── 08cadd80f9589a31fc05197a4b3d178a5d78667a.nq.gz
    ├── 093e6e62f0812dcf8ec96de915da1e5e3bdb336c.nq.gz
    ├── 097895f8942668c336b200a533e9cc0b4155bb2c.nq.gz
    ├── 0bd61137c8f3fb2e7cb72bfbf519b7700f1f5d21.nq.gz
    ├── 0c90eb5672b04fc66edcc99f003e15fc638e279c.nq.gz
    ├── 0d09e5cad49b2125e437d35f592d9ec45640ed9f.nq.gz
    ├── 0e876956ee6c84da6190087a46121a65890d8912.nq.gz
    ├── 0f7ee92397c2c64a7b4230a5600b3bfda56e6f93.nq.gz
    ├── 103e8a669c70ef5056d3eb3abd327a37d523377b.nq.gz
    ├── 110289f2f4b5260ce04dd035408961f1e4f2785b.nq.gz
    ├── 1107a3f66ccdb55d1146f3d0e184be856dd9f68b.nq.gz
    ├── 113951200ded403f1adfb2b55686c22b635f55a4.nq.gz
    ├── 11518ef4dea3a185551dde553c6c9afb56ad006e.nq.gz
    ├── 120fdc570ddd8cea966c00efae9294e71d791a8b.nq.gz
    ├── 1305ad3042ee4f43363861efb28b346cff32b23a.nq.gz
    ├── 135fcdaa5d1d7f09824febb883505dca5d248eac.nq.gz
    ├── 1392a6915e6bafb42740446b333eb90fe800a5af.nq.gz
    ├── 142c6e43464af41e1bcefa1d8b80ae2af6f6b2b6.nq.gz
    ├── 14edff798ccb62521e06300c76018d7ac0cd0057.nq.gz
    ├── 15e27edb12ac25701ac0ac21b97b52bb4e45415e.nq.gz
    ├── 19e5a6457b6c1cc2f6e88bcd06ea500bb0f9eced.nq.gz
    ├── 1aa77d18c7060805f3eb2262c6aa2461a08fee6c.nq.gz
    ├── 1aaec16c1902b4c941b1fc90f65bc39374962143.nq.gz
    ├── 1b3bdad2ceffae91cee61b32f3295f9bbe646e48.nq.gz
    ├── 1bf05e81e4b7c7b60f0aad4f99de02a089004a4f.nq.gz
    ├── 1d99dde6253ae9ff95bac89f1fbf54954b470264.nq.gz
    ├── 1dcb17adfc62df3baa8fb12bba939a05e02ee1da.nq.gz
    ├── 1f49f6ab38abce05253a851d2b5698d8abebe99b.nq.gz
    ├── 1fa2e4e134ac52f346f3bd9487dd641fb5c7c199.nq.gz
    ├── 20791c32d7e93822b7d5417f9a9d985d439e6986.nq.gz
    ├── 208d4cd890c3183d946092ebe982738ade565061.nq.gz
    ├── 209d2f11b461f54474183a15b271accbc9498717.nq.gz
    ├── 20a6f5c0ce8a8fddd477e739ab13b230af41d2d5.nq.gz
    ├── 20c4814dcf0d3f437ee9a46f5957e3165aa5fb17.nq.gz
    ├── 20d4e79f3d07a0daad6be4792d5d1503a24a87d1.nq.gz
    ├── 20ecc4170aeff516fbaf58a63ece853b94f688a5.nq.gz
    ├── 213acb88b6d7478a28821fec3247bdc2bf7d0d51.nq.gz
    ├── 229165597292e0f97adc2c923a99ff07ec450909.nq.gz
    ├── 22cdfda652bcc8628aaf799dfbad588684a2a3a7.nq.gz
    ├── 233fdafe7235f96ab6fd569a0a54f5f16b57317b.nq.gz
    ├── 24bc73e7f51edb00f73d5cf222632c875dce6657.nq.gz
    ├── 2672a023e8fda1cb327adb3ab78b9b72295c86f6.nq.gz
    ├── 28649f82fcf4b37bfc520b7957aaceea354c93f3.nq.gz
    ├── 29fecc4b1cc3823de559835880b54e50357afac7.nq.gz
    ├── 2a940a7da7c14e6a36901e83306849ba7efad4d4.nq.gz
    ├── 2d53207fe3626f529a4b6fad937193c23137e513.nq.gz
    ├── 2d6e076a70fa2989e41a83b371e28d65d651eb33.nq.gz
    ├── 317fad0d79ac903d8bd786b215899601a55ca907.nq.gz
    ├── 320f6eb7973e41f3ae8b2d49b6aff782389e0a49.nq.gz
    ├── 32e356a6f9ef0f8efd3bae59ba747422edbc677a.nq.gz
    ├── 3343d662921261590c33bb505d054f1326833ea7.nq.gz
    ├── 3354dd3dc4653fdde907c6f4ed5201fc2f3f446d.nq.gz
    ├── 338c2641469a72aab35c894a2e04c6b65c0f1c52.nq.gz
    ├── 342342e4345d2a37fe77569f46e96dfea8729b42.nq.gz
    ├── 343fa5507b8e5fc011916b8b45ffd6851568418c.nq.gz
    ├── 354f30879f7374e7622b2105981aa1de848e8eb4.nq.gz
    ├── 3786039d4b93d02a421ef6acfece81b2aaed53ff.nq.gz
    ├── 38b73c7a71f2e891c8e62e5ccca757309f0bcf31.nq.gz
    ├── 38d14dbd93a09c324003f45e9963d607785ddf04.nq.gz
    ├── 3956cc252df8d1131856246078b7924318f68ee0.nq.gz
    ├── 3a11fff83a252ce81fe7a6354ccbd0be46809a69.nq.gz
    ├── 3a62d1cd75e5315bb30ded0fb275a4da65682b73.nq.gz
    ├── 3b7d2076d59959e59203ad709a65a9bfcaf6b357.nq.gz
    ├── 3bb805d26f0aba482255828b5e2388fd2c1aaf89.nq.gz
    ├── 3e16ee7530d63fc837b5c3b94f0ba1e5ddabb7b9.nq.gz
    ├── 3f1314dc69fa80f15d775aedf0b54222f075badd.nq.gz
    ├── 3f39fd7c55f82793b815577b20205ca6e6cc38e1.nq.gz
    ├── 3ffb565eeeee7db8df53220e570c0e53b69bd0b1.nq.gz
    ├── 406df8312f5f2a05c0d6887fe565de36f85af6cd.nq.gz
    ├── 40d41e2071b81da20fdc4e73242d2581186c0d7c.nq.gz
    ├── 41e9a8184aa287c5970cc8415e3c5a6310dc9f79.nq.gz
    ├── 424f268f8844967888071bdaf25ad0d5184ce8a8.nq.gz
    ├── 4316d7bdf8d7e891f8b25b767a6e029a70ad38c9.nq.gz
    ├── 45cc5a748b2edea0359e24da9dfc19b0126769e1.nq.gz
    ├── 45d1ecb77891795b0b957ebf075e7f2d1461a6a4.nq.gz
    ├── 45fdf33830123533459b17fbbf91735489fd6bd8.nq.gz
    ├── 4680775439a89228f20da781b7603a30c1941987.nq.gz
    ├── 46eca0ea0836a51853786bdf1cd10fd2553e0693.nq.gz
    ├── 47a7b06c748d253b058efcee78b7213a4f1b1a08.nq.gz
    ├── 48b6cffca7f5951ec84ec3bbad8a2382a5e6c3ef.nq.gz
    ├── 48bf4bae9650d5e9d782693365636837d184d23d.nq.gz
    ├── 48ff4e49fdb6b8416444f002e68f208f89b90f2c.nq.gz
    ├── 4973e83252e18d98a4c471e1e9afa4cdc1c60d3f.nq.gz
    ├── 4a21beeece83871ca4e18ca0933d27b75a29b7b6.nq.gz
    ├── 4b4b960dc0a3e67392720de99f1467278aecf8d8.nq.gz
    ├── 4bbe3672926de38638ac2782bf9c8e8754c491ef.nq.gz
    ├── 4c064a0489f471d92d1890bf5759de880be8a988.nq.gz
    ├── 4c1f49fb9e4be369c963ec64656e70ecd27f8e74.nq.gz
    ├── 4c2d95e725a50dc083a8a4684bdbdbbd1d8bac06.nq.gz
    ├── 4d7ff971d11e00e2e44163163f7e88d8a77759f9.nq.gz
    ├── 4d91bcf57de866a901a89a2a68c0f36af1114841.nq.gz
    ├── 4da15d7dcf200bc1462741becce5a536188fcd9e.nq.gz
    ├── 4dc6e9b6ec53cc16b94d521f96ea705053ae83b5.nq.gz
    ├── 4f2175fa14c0660cce6d6c652643febc666fc770.nq.gz
    ├── 4f2c10bb2b882e3d50c018609e23fbd2a76029ed.nq.gz
    ├── 4f41c81322d4fc73690b97b1b6345b1a5811b112.nq.gz
    ├── 50937333b99a5e168ac9e8292b22edd7e96c3e6a.nq.gz
    ├── 50fb0159c0e9ad9263c044c0756d2a5e0d9e9f12.nq.gz
    ├── 5266fb19ecb24d085a338bdace79a063326b1cff.nq.gz
    ├── 52d7b8f1c65be8ede8d025af21aeabce168de694.nq.gz
    ├── 53572d003d0e47458ae71f38c4e372466ae3752e.nq.gz
    ├── 53cfa1d26c57740e889cf2bfe8985935c5db0b52.nq.gz
    ├── 53d9c839599dbc4c0ba257554928c2090e3193ac.nq.gz
    ├── 557ed59a3144546e4b3893b69e89dc0825e69901.nq.gz
    ├── 55a3e38f5afd672444dbcf61fb5a471c57a92c4f.nq.gz
    ├── 566e00bdcd30178beab8ad5e46a1f580adf9f318.nq.gz
    ├── 56b2968bfa43b2380b43042fdec966dc0f80dcf5.nq.gz
    ├── 571f9d3cb08e9e70600f872bd7ff32df55839112.nq.gz
    ├── 5756c8cad8854722893dc70b9eb4bb0400343a39.nq.gz
    ├── 577fed5dede3837a5cdc687ca6ee74694ab2f763.nq.gz
    ├── 590d8711d6388b36933b43ad9e0ca45cd18c13b7.nq.gz
    ├── 594853a951862b5b471d465b8fe5850be817cccb.nq.gz
    ├── 5a57eaf3f15f10bb71c5a3d4efd1d0e22604effe.nq.gz
    ├── 5b55f32beaca186f84cca115514f02cddbd1bbd5.nq.gz
    ├── 5b9132180b6768079375893ad4db724bd8ea5e4a.nq.gz
    ├── 5c9aa45b8ed88888eed45b45839b4161356d5b19.nq.gz
    ├── 5dc743c60d622b99bae86a397086667d1dcfe1e7.nq.gz
    ├── 5ed0393bc2ca4f8aedb6a852b14888b86bed0bfa.nq.gz
    ├── 5f4290222d163919e35921b5dd6338569af3997d.nq.gz
    ├── 6031f991319e4a258c6aba6ad0512fd7b91fe5cb.nq.gz
    ├── 60709e2e91dee5c25c1459d2f63505550b9db143.nq.gz
    ├── 60828fe5c0b6e133f302ff44b562a0dfb687f0c5.nq.gz
    ├── 60bb516db4acb0b29dad6d139bea8dc5ce5b62e4.nq.gz
    ├── 617428423cc7d3b642d6f412e138457f10cad279.nq.gz
    ├── 61dc1194b4832a7aaeea2bd856e6464052f98f61.nq.gz
    ├── 61faf8cab23993bd3e1560bff0668bd628642330.nq.gz
    ├── 623b6a2585cd81edad701fee5d3b6fafa8fbdf0e.nq.gz
    ├── 62645c7630ae4a40506d9ac3d1216170cf74eb45.nq.gz
    ├── 63c48b634e386d0dc158dc65f4a918890df8cbbc.nq.gz
    ├── 63e595ecbfc5b24263fb1b8f6c99ed0907a2b7a6.nq.gz
    ├── 63e63bf7a711e94219b3dc01de3588a39f203c8f.nq.gz
    ├── 644d35e274fd64ddaf6d12af813e820c424176a9.nq.gz
    ├── 6574208c479237bd6a64de7f3656c67b7b827dee.nq.gz
    ├── 6601918a1e49d44fe7a0f86483c2676dd5d0f178.nq.gz
    ├── 67524e3fe923e37423403c358328310842fea935.nq.gz
    ├── 68a9b6352ee41de09445eb7efa700d1ec6c3a727.nq.gz
    ├── 692f06e4a0ee52cb02bb683a0e792b6b3bd5bf89.nq.gz
    ├── 6a794190c9500cd936f43ceb65134b81a49a3e92.nq.gz
    ├── 6a9850b32304c5ee32a6f057186bbd4ee27bfa97.nq.gz
    ├── 6b31b72d68ea43771e5f7cefda975afa89bea81d.nq.gz
    ├── 6c013ebad8193701c2d51a99eef0a2220e9a17b8.nq.gz
    ├── 6c709c529cabdff6fb41c3f6e58b2bc52ed29624.nq.gz
    ├── 6ca2a8b8a460200f2312caf488a13224159bd065.nq.gz
    ├── 6d223bc2f00533cba70ea15264210f200c74446b.nq.gz
    ├── 6dbfac8a21285b8dda22ad878c4d57b28d1f84ca.nq.gz
    ├── 6ebfc1daf5d922007d2579b4a9b0be8b11de669c.nq.gz
    ├── 6eeb3e189fc0219988d00e36bb520ea38d25a01e.nq.gz
    ├── 709ea2ac18b9a23596d8a1f5c81f333a74ee6ad4.nq.gz
    ├── 7107cec93a979b9a5f64843235a16651d563ce2d.nq.gz
    ├── 71d2df6711f304af602e91a0f8cc52b09d398bbd.nq.gz
    ├── 72d480a45d5303237d9e17bd10714e0bf22ab913.nq.gz
    ├── 73db1cf0c022261068c5ce92ee198ad2a52fe912.nq.gz
    ├── 7490cf36116ebc6ae6f4a94fec16e3875c2f58cf.nq.gz
    ├── 74c3d79c425cbf0ecfdb952841279a55a000be77.nq.gz
    ├── 753969fdae2e80416d86194320d3e4114f9ca8db.nq.gz
    ├── 7547637ce015700e7b07f58c577ee0ab2f0ab640.nq.gz
    ├── 755712893e761f4db21f275732091a0f839cd863.nq.gz
    ├── 772bea9ae8d0a4ecbe977a66e6bbd2e158dd7ec8.nq.gz
    ├── 77619b8167c96935779b25061dbf3df80b5a56c8.nq.gz
    ├── 7784606ec48622b41772d01ac9bed2591786d04d.nq.gz
    ├── 7863f38f178a69cfd809243ccc9121037e23ba62.nq.gz
    ├── 78e14bb4a1ee080ca01b92b20ed583941db04373.nq.gz
    ├── 79233b75c5def23c1c05eee80e96a9f38514a6e0.nq.gz
    ├── 794a878c474e5f3cce826cd9f679926b1e46edc2.nq.gz
    ├── 7b9e1ebe454aab050879e0b906a5268ee7415daf.nq.gz
    ├── 7c79c6a6bc9a128a2a8eaffbe49a4338625fdbc2.nq.gz
    ├── 7d1e4d54d6c293333eb638aa56feba7b62e15564.nq.gz
    ├── 7d4071ab7d3f6e6e0037da672fb7a3a5c553c99f.nq.gz
    ├── 7fb8cb2e607f726fba77e17e43ddc0778b6e3009.nq.gz
    ├── 7ff5c70979fe63a765cc2935cbd5891628a028c4.nq.gz
    ├── 800caa1074275f571c2fe5b8fc4936c08c56e77a.nq.gz
    ├── 81559ade7c532003e75a09d37e12a1df0bcf0d19.nq.gz
    ├── 83b9251734def68034cd0712a9b363855733649d.nq.gz
    ├── 8595ceb537a6623458b6a107da80e4f9c54930b1.nq.gz
    ├── 861ccd9dcb8de1d0cc91575a19e8a5b723a9609d.nq.gz
    ├── 873ba43cd72f3081a33cbaebba71e8be7a873750.nq.gz
    ├── 88f1068243f3115d9ca5789ba4a3f339407ce5c9.nq.gz
    ├── 893665fb31ae0c54a6497a8a544380bed1a52e0c.nq.gz
    ├── 89c72cdaf279c4a67b1536e07df9900fae0658b9.nq.gz
    ├── 8a05be00fdda516052832b15ea9605935b8a0f3e.nq.gz
    ├── 8a3ac46c085617fde0408b38eec8243292551455.nq.gz
    ├── 8b0f54e47e1d356dcf1496942a50e228e0f1ee14.nq.gz
    ├── 8b9fbe8909b70b6e70f55042b7535339614381a7.nq.gz
    ├── 8bc1297149e93b6b7f3a2a95cee2c92c6dd70333.nq.gz
    ├── 8c1748aab7a790d510fb3f42a8a8971d96efa79d.nq.gz
    └── 8dc43043e7aa5793b5ccb0fe8db44ae18109190d.nq.gz

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

[materialsproject/fireworks](https://github.com/materialsproject/fireworks)

---
*Parsed on 2026-04-12 by [repolex](https://repolex.ai)*
