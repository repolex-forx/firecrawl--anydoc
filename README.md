# Repolex Knowledge Graph of firecrawl/anydoc

RDF knowledge graph data for [firecrawl/anydoc](https://github.com/firecrawl/anydoc), parsed by [repolex](https://repolex.ai).

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
rlex download firecrawl/anydoc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 08bcbc22efc80ca87c684a55b258adaed351748d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 42bf1c5ecdde9eb0d96d6bd75a9e6698cf93b14c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7df4b2e4213c033cfb8e94abc57ab88bb1e9b48c
│   │   │   └── chunk-001.nq.gz
│   │   ├── bf3d33e61731580d1ee1c6a85e56093d715a21a6
│   │   │   └── chunk-001.nq.gz
│   │   ├── c9d4eee742f66dd79c45e02c93f75996e671c2c4
│   │   │   └── chunk-001.nq.gz
│   │   └── e754e1d33a1a540ebc9226e36f11d3f401852c9e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 7df4b2e4213c033cfb8e94abc57ab88bb1e9b48c.nq.gz
│   │   └── e754e1d33a1a540ebc9226e36f11d3f401852c9e.nq.gz
│   └── repolex
│       ├── 7df4b2e4213c033cfb8e94abc57ab88bb1e9b48c
│       │   └── chunk-001.nq.gz
│       └── e754e1d33a1a540ebc9226e36f11d3f401852c9e
│           └── chunk-001.nq.gz
└── blob
    ├── 010dfe7154941395ebfa88f7bbde659f04ebcbef.nq.gz
    ├── 013cd4173669528f1a65a621a0202bf35f30d4d6.nq.gz
    ├── 01985472247ade809d290e8ef9bce61c30a62d98.nq.gz
    ├── 01df83a7a2b951fd4a93aac73090a852898b2fcd.nq.gz
    ├── 03395066ca56e4cbe88413f294e76a97303e7272.nq.gz
    ├── 04471ec66ef52433fb6a1e3c5ed1cec41f370f32.nq.gz
    ├── 04ed82f8b50e4430351a6e530377bdcecc0b80e8.nq.gz
    ├── 051c5ac43447b9364f16171407abc44330cdcc6c.nq.gz
    ├── 052f51e63241e7aa32268e7445ce602bf0992891.nq.gz
    ├── 053f1f3ee0f4d8e7112819d2cb9b1d677b80231f.nq.gz
    ├── 05af975ef78d78cfd5fe341d99fac70657007c17.nq.gz
    ├── 071281ba38e3c04565c6ee92d1e662c3bbb559f9.nq.gz
    ├── 0748c1ff03a4715876e5c6fcb2de9a7003c98da2.nq.gz
    ├── 085a2c5f1e37d638eb9e33816c4425f8bfb5de09.nq.gz
    ├── 095c10e085a33fa114b96c139b311a90996caae1.nq.gz
    ├── 09c73f9b534bbc141f7e8ac052492dc2a484ca12.nq.gz
    ├── 09c8896ef1f9ee800a7aec442965e93fec5dfaa5.nq.gz
    ├── 0a7b19a4df5dce1459648b68ffd01e0395cd5aeb.nq.gz
    ├── 0b84ede280d0863bec3bf146e6034406aad33b4e.nq.gz
    ├── 0bd455c652f97474b833af208e88559578204315.nq.gz
    ├── 0be2ba2b19a602bd767116a3b03387a1263a19d4.nq.gz
    ├── 0beb02380564d215780a50bd6d95258bcd13c76d.nq.gz
    ├── 0c245e3c29420d8c6f022a0355718fc17f5265e2.nq.gz
    ├── 0c416c67b3500a1c698e3821ceb99b157f38381b.nq.gz
    ├── 0c4a42f768f531f8bc570603495c6da923a76635.nq.gz
    ├── 0c60a2ba4e64340fce3cc6d097f1a8d6f39bbfa8.nq.gz
    ├── 0c84956015ece7afd4c55176bed80e93bf6e4f4e.nq.gz
    ├── 0cdbf432ab1d88ae5e171b7cdc138553a303077d.nq.gz
    ├── 0d4f6a4bc526a7f9a38d40257743971c4e63ec8a.nq.gz
    ├── 0d556258d33ebbd320db260b4795ed302c668c9c.nq.gz
    ├── 0dca9eb1e9166862c6e61d3ff46076a263252056.nq.gz
    ├── 0e32e5ccc890b90c5ea3c55d0018b22e895ac01b.nq.gz
    ├── 0f1b01002b079d101cc8ccc17a3b1fab5d84068e.nq.gz
    ├── 1002d827c96b4fd4cd8315ae07c2fe7cb8c56ac9.nq.gz
    ├── 1027a60ad003b7ed09915cee42c3de99bed063a5.nq.gz
    ├── 10b94c9afcc8e795742b1905b2987ccdab8fd2af.nq.gz
    ├── 12a82742bc1951adbc27e7873be9e9941614940a.nq.gz
    ├── 1328d44ab4dd521237558be36fe2062b64e8c195.nq.gz
    ├── 1461e3389484b390a2eefda8c8901a3bcec3b15b.nq.gz
    ├── 15fe68a4d4d6998764c3a9cabcf88ede04dc017c.nq.gz
    ├── 163a4fba8216d63bc73e9ee844e12bcff6c30a06.nq.gz
    ├── 169bb8ab713301301374f44e812c88a51280beae.nq.gz
    ├── 170005fa858e1d14363ecc01abb28d9dd5829b2e.nq.gz
    ├── 1829a5e91a5825b14a1ac987baee472c5ba800fa.nq.gz
    ├── 1884a0b1177348b0fd8fa0003cd5dfd55a619049.nq.gz
    ├── 1921ebca2d3c1d3e5055a18ed2a85fe8b3f6774b.nq.gz
    ├── 192e9e9d702c8026c2b2055f1aa0536f3fff8d94.nq.gz
    ├── 19b70798cf0f27d65c7434a03f80f0bd2898e2f1.nq.gz
    ├── 19dadbad3d3360e157f0c547d07b10b44727c431.nq.gz
    ├── 1c1601ff0aa6be6d758a0230192419f73196e212.nq.gz
    ├── 1c7780d0980d372d209f142f255c09ec690c8274.nq.gz
    ├── 1cc7e92ef21a9f8225565a95139b4a7c63c17a1c.nq.gz
    ├── 1cd661714d07b6ea2c0eb260ef8a1d9237248766.nq.gz
    ├── 1e0b433e91394093bde1682779fbd6a8fc1da79a.nq.gz
    ├── 21552bf702b4f0478ff459765e9465a3d9656ff8.nq.gz
    ├── 215f752a50d0bb02c755a021a4c6eb8f198ba027.nq.gz
    ├── 21dfef57c927d9d2c3d305b56c74c030d2d3abc2.nq.gz
    ├── 225f32e26f510c44dc5efac085046d7f29b4c63a.nq.gz
    ├── 226446b20ff2f794d401d2eb9d572ecb8144a0cd.nq.gz
    ├── 24db32e105ce8c11f945df4c80fb9eabe2c298d1.nq.gz
    ├── 24e620c0d873ba38e72089618acbe48e9848272c.nq.gz
    ├── 24fc6caa9ec8f4a9b0e1d6bf9d7d61888263067c.nq.gz
    ├── 25f997c2ccccc298053d9e69225bd36d3e0bbd68.nq.gz
    ├── 25feb15a543d549affdd64c81ba3d124300b3c7e.nq.gz
    ├── 26296c9a337befb9e73372d6dc270350a837f36a.nq.gz
    ├── 26608f793d9294583900808b12c5f7dabcaac67e.nq.gz
    ├── 26719ef3b7228f81e0ffa8369cf75276bcffcfa5.nq.gz
    ├── 277c97aa098df87c538dd2b91b8411cc251124c8.nq.gz
    ├── 27ceba0ac6fb721e46ce043bbc1b98b4b7ce23b7.nq.gz
    ├── 28488fdc350b70d78e04bc90f92ebdb2cac0abab.nq.gz
    ├── 287ae6d4904c56ed82f47f69bfc45fed343d7f39.nq.gz
    ├── 2886b1a968c87c3480970820a0dff91d280a1492.nq.gz
    ├── 2908b61f179e29ff8a8a9b94ef2345a3eb89033c.nq.gz
    ├── 29421becc00e0bc7a2bf0234ecbab26925e6ab52.nq.gz
    ├── 295d8a257b37ca5e5cc973d8a525bbe685b30239.nq.gz
    ├── 29c5a785bbaf3dd8b306b174661158d3e07b027c.nq.gz
    ├── 2a334b7223a6cb08db7382df5a009e68971a1efe.nq.gz
    ├── 2a799b2910c4f4c1caea5cab683914953fa89d94.nq.gz
    ├── 2ad6db3732d9f82047789749dc323b777fb6d155.nq.gz
    ├── 2b2ab1d933d21cdd3df37072d1fe59455e38c78a.nq.gz
    ├── 2bbe6a499568dc2ce1d8ff0364c0a25a59f971b2.nq.gz
    ├── 2c0f1a8f5faf2fb9bee366abff7995e5db09ff04.nq.gz
    ├── 2c7d6c3283864508f24bd00c2f0f924536df872c.nq.gz
    ├── 2cf6b4bffacd9e9f345d84c841c2b81d670d0d3f.nq.gz
    ├── 2db5c17b28aaf3cbac8d7eb09674b7b187cf48c4.nq.gz
    ├── 2e0e4e37e2fa689ab43d04ebc0ff28d3a5a0126c.nq.gz
    ├── 3058e872bb24376e90f002d24ee6c206027917f1.nq.gz
    ├── 3094e67dbfceaa73c95b778217693728bb3481b9.nq.gz
    ├── 32ec189a6a480f3b41e10ed42cc88c20007b6543.nq.gz
    ├── 32ff65d8dff1cb9e461395084e71a006ac332fe7.nq.gz
    ├── 33009eb15365ec4763fd59ba61b8ef31af166c6a.nq.gz
    ├── 34b98901421f68df0bbc4ccd9b00bed4a9a3a7f8.nq.gz
    ├── 34e95c2f95b8c61f47f66f1b495315236ed94291.nq.gz
    ├── 35f148157c501939343443b3cc9ad66ec15848f0.nq.gz
    ├── 37c8a678ac4d6d39511e9c71e22ee4f53749c3e1.nq.gz
    ├── 3a7590b69307c38c57d9873ded90178cc391ca1e.nq.gz
    ├── 3b10040a3dc942d5dd237b15f3d860ff823fbe24.nq.gz
    ├── 3b8c12c2fee96c94d573c9e26af2a8d98f12bc08.nq.gz
    ├── 3bf2f066ecbe9a4120c2b33e1e665872427d283d.nq.gz
    ├── 3df709dda0e33c02d07fb80e9d66b1d495f4d796.nq.gz
    ├── 3ea88145cf5ef173cef20b2dbe5b1c508d62f247.nq.gz
    ├── 401617af4fe7b9eaa44335f7719e0b2020986e27.nq.gz
    ├── 401f392f7d794e8286178589b06eb1bea2aaec93.nq.gz
    ├── 406ef425707260d09801c0434a1e9229b9d60653.nq.gz
    ├── 42af1d8cbf76a534f6fd592b43011e215d85c077.nq.gz
    ├── 42f16cacc6ae8cbf31dd358dd58ad16493413479.nq.gz
    ├── 430296407da0ec7ed1c2f994e42baa6ed60a9cdd.nq.gz
    ├── 438ab8728b1e8a8a3dc7e9580d37498c6a55d99a.nq.gz
    ├── 44906f251a15b5dff85c088bf5256740f4699b3e.nq.gz
    ├── 44dba2b51f49edcddd32809e4dfb86e8d3ec7294.nq.gz
    ├── 450cb86b5e7753a2691a3ec3832308d858b64b0d.nq.gz
    ├── 4523ace90a5d2ba483fb9d88e13e70843d333d23.nq.gz
    ├── 45d72f1a4d81067dd9a3e0f3247fc6b84c67b303.nq.gz
    ├── 4764bce119d3e668e83c0203e5b0f37e08de4c86.nq.gz
    ├── 477a1adc4da57f8f516ca301eda1f4166ad1235a.nq.gz
    ├── 48e42fb4f771b5e01499b4c20e2ee97715aca916.nq.gz
    ├── 49542a950060e11ad0a40e6caf4212e7f230a686.nq.gz
    ├── 4ab25a71e7684239062cedfb4c1f62193f71b533.nq.gz
    ├── 4adc8a7044d761fa55f5ec25d90b79051bbe3573.nq.gz
    ├── 4b9715a245b7b7e0d6ad3d33492701c0eb4ee898.nq.gz
    ├── 4bda27eb9aa438c965461aa1cb308f9409332c95.nq.gz
    ├── 4bf777cc388904fc5e62f26d7480284c724fd917.nq.gz
    ├── 4c07eb9a5b4dc768bcada8794880de2aee5db99b.nq.gz
    ├── 4c1a37ab3566c930ab520a7b434204e965055163.nq.gz
    ├── 4ca94c584a3487ba11e4d83e191a1d39e2375e42.nq.gz
    ├── 4decb484e9c6071ea8aca6d3989b505c2ec2bb27.nq.gz
    ├── 4e6fbdb0d2d83388312b7c30e57557c0d6bde71c.nq.gz
    ├── 4f1eb833531849a67fa589d551bef65d57eb9731.nq.gz
    ├── 4f2a0674ff96f7a741f6d423a438c03c77d3bf62.nq.gz
    ├── 4f592d69d59f404582806201ebea9765269f8871.nq.gz
    ├── 4f65ad999006462a7b03947f7625ea69734c45b5.nq.gz
    ├── 4fcd0ccfceb9e53ac64bdaf7d797dbc88f7b048d.nq.gz
    ├── 5050a02964161375b3b8ad907fc4bc4e61fe3e44.nq.gz
    ├── 5096bffff7a5324b40bd37ca8bb9b871f4f0898e.nq.gz
    ├── 50dfca7470f82bcd9e096de5714d2f64399b94fe.nq.gz
    ├── 516b83ad70c8e97f78400a27a02eeae754d73e08.nq.gz
    ├── 5263150f86c2a01e0efb9016b0aec72e6ece6288.nq.gz
    ├── 5277e469fbf842d2a6edb9f0f220ca6aed5c0a68.nq.gz
    ├── 541e928e5154b91446988442a7efe8e95a34e93b.nq.gz
    ├── 557e1d2d75ff02713e77852ad8aaa34c667c409b.nq.gz
    ├── 55efb50f50b3611a71a117b6e493081956c0a545.nq.gz
    ├── 560f0c4a01cfbe878ca54fd2575f82da6d62a8db.nq.gz
    ├── 58399e33197b1d01445a7d7a3bdfba3f81664916.nq.gz
    ├── 58f53ae8777631488ae5efeedddaa16071df00c6.nq.gz
    ├── 5923db7b6274efb4634fa16606b97a02fb35b674.nq.gz
    ├── 59f9f8ee31535d064790565b56fa9b8f29cb85dc.nq.gz
    ├── 5a018ee9ddea654e232ffbc7104ffe9267354659.nq.gz
    ├── 5a710a5bf0ab8bd9f034aa027ecdddc48ad405e2.nq.gz
    ├── 5b2a63138792038f69d4e77d470b4a73071d6a60.nq.gz
    ├── 5c1558cc15ecfbdd2fe67290293410140e30ef17.nq.gz
    ├── 5cd52bc73a68aaad3fd22a8f7b7a92eace2f1cc9.nq.gz
    ├── 5cee4785a0db6d756020c695776d94139876aeba.nq.gz
    ├── 5d4618b8dca64b2263244387da38cf518886a7fd.nq.gz
    ├── 5d7cd34cfd1909bd320840a2daf402010b23dfcf.nq.gz
    ├── 5defd39c8759a29f67ac002ede6b19fdc8346563.nq.gz
    ├── 5df92ad38905fa25211e08bbc26ec91aa581849a.nq.gz
    ├── 5e66bd3da60dcb16ee0a3823cc02c3e25fbaa9e3.nq.gz
    ├── 5edc539cd7ec24ef3e7e0b5895bbb8fd0db99784.nq.gz
    ├── 5ee84694bbb11945b63301e751f5a801baeae61c.nq.gz
    ├── 5efbf637123de97276c57ef6b661df3e7dd18247.nq.gz
    ├── 5f32060fa4137ae9344731a474897d0b9e8d6cbd.nq.gz
    ├── 5f3beedfdacda9185f920e125b825798b496259d.nq.gz
    ├── 5f3ea59bbabdee69c73460e4dc10fce1dfe724a8.nq.gz
    ├── 606b4d25654fe2098e073278a3da2179b5e305c4.nq.gz
    ├── 61ba4f8f3b5c7ba6616aab64e9c055e49e471c58.nq.gz
    ├── 61d2cd3ab91f69eb5f5904d1b92873dc2abb6dfa.nq.gz
    ├── 61f7f60c6de9daa16818e91ac847358863af9630.nq.gz
    ├── 62f9b5d01af090b3bf8aa76f6034cd8ed11b8300.nq.gz
    ├── 631e05aafb16f9858c39797fcdbcfbbdbde3a2b4.nq.gz
    ├── 635c76b3f2c919bd25df3c672df0ecc701651431.nq.gz
    ├── 63b700033a949d8cd721caf6d2c051ee10d4f983.nq.gz
    ├── 6419b4a95334daf726cffe50bca5c53e560879c8.nq.gz
    ├── 6424f04394324a6aca2200bbd303e2d1399526c7.nq.gz
    ├── 655b643e8b6d48e9108ae569c67c88ffbee8fda5.nq.gz
    ├── 656e915c4830ecf367d32c75629b865f2d03801a.nq.gz
    ├── 66a2b61fd7030ea7fe7c7e784c99fd628c3517b3.nq.gz
    ├── 66d48c1f8df3aa42aebb02a55c8820cfdf604820.nq.gz
    ├── 679c45b0b27160d7c4b83dfdab1f1c6b8b6b03b0.nq.gz
    ├── 67a4c63832ae6630c9f4bb8063b47d351e016648.nq.gz
    ├── 67e000e5e6fd8aa4be44aeacfa94bdd6721b8f05.nq.gz
    ├── 6815a85444203d85f738468139f40d41fdac7191.nq.gz
    ├── 6832155820deed58f9cefb6472cf5085859848ab.nq.gz
    ├── 6898bb6ab4d375435dba72874f830dfaa609aeb2.nq.gz
    ├── 68f15860f7b79e940168b78c91da5786754f4918.nq.gz
    ├── 69d5ab1f2001a25e07b8848e2ad891607b2589ad.nq.gz
    ├── 69dc74d32e744596106c937346408610e44e4445.nq.gz
    ├── 6a19b3e2b30fd4c7708ff91ec47f3f0da9d0ef5e.nq.gz
    ├── 6bb48e2aa66484e9dff91ea7b295447937dbc443.nq.gz
    ├── 6c68b666b63315ec7cb4997a1fcaeb48c22c2e5d.nq.gz
    └── 6c8b6171b9001f3f841971be9f5887d9f155282a.nq.gz

14 directories, 200 files
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

[firecrawl/anydoc](https://github.com/firecrawl/anydoc)

---
*Parsed on 2026-09-26 by [repolex](https://repolex.ai)*
