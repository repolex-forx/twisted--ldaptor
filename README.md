# Repolex Knowledge Graph of twisted/ldaptor

RDF knowledge graph data for [twisted/ldaptor](https://github.com/twisted/ldaptor), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/ldaptor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c3eaca5cdf1038a833743aed1ba86b55b4ee8c58
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c3eaca5cdf1038a833743aed1ba86b55b4ee8c58
│           └── chunk-001.nq.gz
├── blob
│   ├── 008239ca446f2c0e0b6b85f66e78af72784e8445.nq.gz
│   ├── 01c8cc3f0cd05dab9f4db0aa70fefe11e53c0b39.nq.gz
│   ├── 0521da1bec8ca3d922d6af7cd961c68442ea047d.nq.gz
│   ├── 0819015259697fd56c22083609f3bea3590f7582.nq.gz
│   ├── 0862bc459f566ed168b50d2dc87612f600dfa783.nq.gz
│   ├── 08aad546dd916532a5569a7b0435647e9f4eec88.nq.gz
│   ├── 08f156699a94f3323deabe4fcef0f26308770da6.nq.gz
│   ├── 08fe4df88b127ae71c4eb7da906b2c1746475650.nq.gz
│   ├── 0a63212a2f17738ac6485c752ab19013924648ed.nq.gz
│   ├── 0b95b61afb6d8c310018ac4e2a445ba5d258baa6.nq.gz
│   ├── 0c8b6864396ee68f1bd6a472c8328a59a008c621.nq.gz
│   ├── 10df81e61cb6fc368b9e4f64dfd02d5f99407ff5.nq.gz
│   ├── 1199455d509f3c59aa775cbfa000518bb17376d9.nq.gz
│   ├── 12081870aee80f1b3deb081d9fbc3a7d29b2c16a.nq.gz
│   ├── 1274bc3784de7760114618f6d858606be9b861a4.nq.gz
│   ├── 127c1b05735a258f0933460eb3d86f4d087a9e23.nq.gz
│   ├── 14d320b31ca6756c41552915b1b33d510d1570ce.nq.gz
│   ├── 1713c2b6c2ba98893062dd9cf5beea95c7063795.nq.gz
│   ├── 197d07d9d06dcda5d0964b1845f60cca16d92f77.nq.gz
│   ├── 1a0ac27ab0196492b43b46e760aed10eaeb13ea0.nq.gz
│   ├── 1a6076230e05c0d457f3998455b2ba244ef49537.nq.gz
│   ├── 1a765fc9f8a1032b0cc69f5d8e128b0fb83c95e0.nq.gz
│   ├── 1dbb196702fccb18ae3f2bf7586e60330416587e.nq.gz
│   ├── 1f7e500e5c4499c05a17e3df61307622530ef632.nq.gz
│   ├── 1fb96157f73ae571ca8098e0dbae0f26658f584c.nq.gz
│   ├── 2007086e8a1ebfdbce88f06d68fe8dae5834f755.nq.gz
│   ├── 2086d411c3c38b473874d2fef934ce54ba0596a4.nq.gz
│   ├── 22976caf4fc22ebb759699eb5ebf4451128b607c.nq.gz
│   ├── 23dc4454f2bea4ec2e7241a27932e922f595afba.nq.gz
│   ├── 25ea394b0120077e96596edc78d14f9068fdb4af.nq.gz
│   ├── 287bf8c79a0562dbe20fc23ca92af9077a59ae55.nq.gz
│   ├── 2948b9ad2658c5fff9358ab93f022fdc3fc01aaf.nq.gz
│   ├── 2c3f39cf3a5d849e00344597e53a5c64d3c5501e.nq.gz
│   ├── 2d084b403345408626247a5fc67d4ed607a9627e.nq.gz
│   ├── 2de3296a62f6a1e9c8fb00cda54e7469e21449cd.nq.gz
│   ├── 2ef6630edd326ff40eb375e02a60ba3d2dca4e63.nq.gz
│   ├── 2fe812cc3b044e89e93012ad191dd3b96bb32cc8.nq.gz
│   ├── 30430f072bd38ba43e1b29598c59d54c6523a29c.nq.gz
│   ├── 32688c7cf94679b2da68c6405adc0030b8fe6ca2.nq.gz
│   ├── 3644655adc3c12db1cb98e38653faf1ff7bd4343.nq.gz
│   ├── 390f18ac0ab236e5e0fdb2bed6186fe59fa0694b.nq.gz
│   ├── 391b72c2e8d08619513056108184ea6cb1f82ee9.nq.gz
│   ├── 3a3a1b1d62d70997fcef45cce3a11e3275d56c53.nq.gz
│   ├── 3a637cf06bade5ddf582507870737d736c32d1ea.nq.gz
│   ├── 3a9e9f73512a953728afb228a0a272f32a3b1924.nq.gz
│   ├── 3af0bfdc974ee92c39e3266eaddeaabdab6a2f07.nq.gz
│   ├── 3c9d1d9c96a580a0dfb8cfaa72fd5a62ae9d7eed.nq.gz
│   ├── 3d5c7b1c12d7f403321a7e4fd3c3823c18d076ef.nq.gz
│   ├── 3d8f6954c76d06f9d89e40ea20addad0ad7cad5b.nq.gz
│   ├── 3dff74d961b5b1ecb0cc35cb8b504d23f9f9ddcd.nq.gz
│   ├── 401a02f538ba48410e9ecfcfc26cb149158ff6bb.nq.gz
│   ├── 40410aa3d834fe14b75d3693b4c2e007f02ac091.nq.gz
│   ├── 42422c1a84c338baf2bfb0d8d41c7119d70922d6.nq.gz
│   ├── 45b0cfa68a2909df6753098ed7686d35b8b13537.nq.gz
│   ├── 45b75d931c867f826f7ded134f12a6771ea7186e.nq.gz
│   ├── 464dbe45823cc191784b07d539ff6565048c8fdd.nq.gz
│   ├── 4916ba9ee28ec3cb9a44e33cb865154b7f356583.nq.gz
│   ├── 4b8a5bb9133632c4711977fbb23b31fddddaa4fb.nq.gz
│   ├── 4c2cd9869cd519efa34f0e1cdeb3e1f1821ddb7f.nq.gz
│   ├── 4c6426d5b2b9827c637bf4bc3014b990fdff10f9.nq.gz
│   ├── 4e98523e9ee3b4b76faa8b4091ebf654934bbaab.nq.gz
│   ├── 4efa09d34a23ebe966721c5f1584f2ca9aa401db.nq.gz
│   ├── 5116e5c78fd532ef91df7b165181408525c939c7.nq.gz
│   ├── 523a0ea85b6ecbd72a653c85cc89c57d948f95e7.nq.gz
│   ├── 54661bc9593b18770b2e950f136eab8f79b61776.nq.gz
│   ├── 5868ed302d678c674cb2381338f5d6382b67bf66.nq.gz
│   ├── 5ad4ba3b743b667d245452363fa578533562c927.nq.gz
│   ├── 5b0201dc6ead1b83647ab13cf7eb3cd647e03c2e.nq.gz
│   ├── 5bb6417469a5281854cfb49f4aadfd2db8d5e7fd.nq.gz
│   ├── 6020438d9249d29532f4a086f12be603c5bff3d8.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 61ffdd4d05e4c0f6f34ca89c23c182bf9b643b85.nq.gz
│   ├── 634aec830125141ad7dca4ea9425dfe793b9346f.nq.gz
│   ├── 63b4511f2024494e1c637e05959eb384fe6f5bf5.nq.gz
│   ├── 6523727dc5a0019fd74614c0df565509d2244375.nq.gz
│   ├── 65af2aefe03cc0e4b711c6565498d7c326708be6.nq.gz
│   ├── 666fdfaff3ee22f72a81949e43731ee00f5fb8b2.nq.gz
│   ├── 6744df13a2e19fbcc546335a88253b83d7149380.nq.gz
│   ├── 6b81b2adeb77a5a9b64c3c2e9e28ac213195682c.nq.gz
│   ├── 6ce80f551c14cd166789ddd9e73943f5301581b5.nq.gz
│   ├── 6d4281f5f87b50d7237a85348ff98999e7ae84dc.nq.gz
│   ├── 6d84922c084b4b1d558687851b144b48f6f31e76.nq.gz
│   ├── 6e183a44ee05f6a47a33ed30b219751c3986de7b.nq.gz
│   ├── 6f1cc5f293277613331442de7b38726598335430.nq.gz
│   ├── 70911a0215ed124acd43220b8ec86d01c2e1d37f.nq.gz
│   ├── 70f597c00ba60d2eabc67d220692207ebdebdfc6.nq.gz
│   ├── 710b38240d966ee8aea8550c9baa149fd82455e4.nq.gz
│   ├── 71106845aee8082d3941fde9439efb2084fbba92.nq.gz
│   ├── 72a7ef0f1165898336836fc374a3a4dd5d8d19c9.nq.gz
│   ├── 785a1f00fddea669887222e60da4ac550486a97b.nq.gz
│   ├── 79e5f78e66cfd74ed8ff6c6b3c994a21ff745f52.nq.gz
│   ├── 7a5826aabbca40407c13ca2e1007a71eebaff52e.nq.gz
│   ├── 7a6abe1bd94add1d403996be72ede6d18d5deb27.nq.gz
│   ├── 7aa9bd355d3855c8eee07ce70d690f8874263448.nq.gz
│   ├── 7aaa310dd9b1604ba52c5d964226f6b95af68050.nq.gz
│   ├── 7aaea54ce5b0834709cb1fe191816188a6a44db2.nq.gz
│   ├── 7ac9bd7f6daa2bc8922fd683a39820e03a012693.nq.gz
│   ├── 7afd434339fd908b75df6a1e7bcf12a880ec5e1c.nq.gz
│   ├── 7d2dff0a2d1be15dc71ad139be5bc839e3e2b904.nq.gz
│   ├── 7eca6960083705daa21809a99620229a9f7bc7cf.nq.gz
│   ├── 7efa1afc1749a7d3044db7eb759b44161e08abb7.nq.gz
│   ├── 80611ad91a473856f07e5ff276d3506e7278c65b.nq.gz
│   ├── 80fc422f0ab29be6b958823475d443b14bb0e571.nq.gz
│   ├── 81ceac2293c463f366b952c4e9fa55bc07b6f05e.nq.gz
│   ├── 82bc5abff28d7e5523e728c42af2cea33b6608fa.nq.gz
│   ├── 8497a2a44aec9842e257044fe4cf9e6acf7836b1.nq.gz
│   ├── 87064e23235bc777793b737068a400cf60c4717c.nq.gz
│   ├── 87b2ffe704eef6868e582c3858be864f315c50b1.nq.gz
│   ├── 87f3c459b5db7539f134e2dd9a2cf3fd5b31bee1.nq.gz
│   ├── 8840af267beaa0f3dde836144266457682b9eedc.nq.gz
│   ├── 88ce9dca0e68bf346ffaf3bb47af86fd3fefd04e.nq.gz
│   ├── 8da9048cdffc87f628927e5bf58bd43c488c0217.nq.gz
│   ├── 8f6ae313e83dbed88a1f8f7c8fbe83172ce84030.nq.gz
│   ├── 90dae008f6ee194718a99e230e09cfedf9300d9c.nq.gz
│   ├── 927873a04cc306b04cff3752c35afd9760c70dd1.nq.gz
│   ├── 93bd4de995efc8bee64731537ae0dae2e87f755c.nq.gz
│   ├── 96fc85cb540f4ae98825253721f54c82c3a2ccc9.nq.gz
│   ├── 97d2520b13597f8a0033f4f349eafc0ba64adf11.nq.gz
│   ├── 983384a76c11ec3e78359e9c0ab5e561fcf8da2f.nq.gz
│   ├── 99297d4791f4ddc680ea3309093d677043b1cad0.nq.gz
│   ├── 992e8d2eb4d1d1062443a4adbcbfe13c59ba4c88.nq.gz
│   ├── 9b4d2ba27e3b6eb4708432b74d585c4bf6203559.nq.gz
│   ├── 9f067317ecc17f21fb1bb06e761811c2348c7242.nq.gz
│   ├── a0282d4002f49669a3d9bd794ee253a983037d1d.nq.gz
│   ├── a088f4733b529d9c37d7d218d111637d28ba9355.nq.gz
│   ├── a0f03ce44efaa97719c18845e8935e05c3d25d6b.nq.gz
│   ├── a17f92a220d48300f7d8bc232d2d6144f19bb217.nq.gz
│   ├── a33474c01c67f4bf8f8278a1e46769fa9d85ad44.nq.gz
│   ├── a66a162c13127a6388173bc7010e83471e63398f.nq.gz
│   ├── a85e95e7ad23ebf06ad1e637dd9e26629d14ee78.nq.gz
│   ├── a86f5446e9412476c11e7c70dfed5026ac74baae.nq.gz
│   ├── ad2bfacef5201e768c1d7195be44df10194c544e.nq.gz
│   ├── ad44252e75407a67429e7f78e451b25ab2cac281.nq.gz
│   ├── b1a6fb5f30285e263a47ea051f68da060dc8f049.nq.gz
│   ├── b5e93548cdd91132d3be690b8347725a036455e5.nq.gz
│   ├── b64dbff0b6f93d3514577d275b8465505b4681dd.nq.gz
│   ├── b9c2f56a3775e33890991acd616b551b4a9e991c.nq.gz
│   ├── ba7ce1145fcab49c7edcb91f2540976f4b26396a.nq.gz
│   ├── bdd8e6ed41af25258fd55f49445f8d400dc68e5d.nq.gz
│   ├── bdd9ae8b91dee7dba4a9805ef8c07a58f38c7e8c.nq.gz
│   ├── be2c5174837c6b7ff0f88a4a6f82a671cf81e944.nq.gz
│   ├── be86a2361c7c082fbd8cdfd2421d2ca778509d07.nq.gz
│   ├── c1610f861a6554a2859956952780a42c7fe7fb68.nq.gz
│   ├── c811bfd4ea27d7fbd075a8bbeded5f495656f58d.nq.gz
│   ├── c83b9e87428330bc065546d22466c37c09828877.nq.gz
│   ├── ca300a153002114aff2c2abc1b80a32b3b0fa8de.nq.gz
│   ├── cc7775e55bfb0f3df385bbd1a7267f214757cfde.nq.gz
│   ├── cdfb81e794fbf2aec4ba68a46b5fb45f507f6daa.nq.gz
│   ├── ce9b2042f9ad167080da5ba6a41853bc8388ea88.nq.gz
│   ├── d04614f109a6b73f02d7c9d5e3d47c234697466c.nq.gz
│   ├── d0a43bfab5a879bc1e376d315ea3d4865d24b457.nq.gz
│   ├── d25420eb5d1d2c6a8ef50e921f5e13c331720b4e.nq.gz
│   ├── d263fe493dbda611e56622887229f3e29f9e3f5e.nq.gz
│   ├── d366bb27ed13d5465fe7997298dd6ec7bba3a6ae.nq.gz
│   ├── d50edfe6d47c110627c56ebd88a4ef5fe4be1c82.nq.gz
│   ├── d87a6fbdbd13947063106538068b5d76a6295e31.nq.gz
│   ├── d96060b18797a38fb7c3c11fca77143cf8ff5001.nq.gz
│   ├── d9b408fce5fd4025882831ee32623c73cba2fe5b.nq.gz
│   ├── da42e42dd225893e0e44b1d958a06f6cfcd3b052.nq.gz
│   ├── db32dd9aa030fc1a4eaa2559ed0e937f3ba81c37.nq.gz
│   ├── db973044dfcff64708e44b1599b7993b5406555f.nq.gz
│   ├── dbc31abc03324ce9643e6c935cd6e9024e3cd67b.nq.gz
│   ├── dbeae4b023d957488f8b8cdeb628fb3f62051834.nq.gz
│   ├── dce56640788adde73894a901c8bbf8e7de6929ed.nq.gz
│   ├── df357cf57845a3d2135d7ed3fd1e9900363b0fec.nq.gz
│   ├── e091fcc0adb9b1fe0a814af223550bbf7dd4ba01.nq.gz
│   ├── e10fd549e687eecebb98e39fb13ee672356d8eff.nq.gz
│   ├── e39185dc355149b61568d37590472f1801814500.nq.gz
│   ├── e4a1ea2451680c12d758dde347c50fbae1642905.nq.gz
│   ├── e4a5c2452b850f88f6160a06d1da4ea090ed2925.nq.gz
│   ├── e5c76e674c54f008b73be009370853120aa0c8f6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a261c1a94d4d0ad4a9da526a6ac8a659f21dbf.nq.gz
│   ├── e772dfa3d351aaac279a6c99355203162a3731cf.nq.gz
│   ├── e97758f110f136e4f960695cacb94328b59510f2.nq.gz
│   ├── eb3ec0e1055f8a1e72185d93d66c605eac826300.nq.gz
│   ├── eb8b8a5aed1ae626e1e617ce336caf00a9b5ed10.nq.gz
│   ├── ec4a07516cfe90c20047db9f762ff37a729d0d36.nq.gz
│   ├── f0dc8c860ba639da2c17c232b09f3af825ac6872.nq.gz
│   ├── f137794da45fda778b3d9d7dc937836249fa7010.nq.gz
│   ├── f2590f6ffff61868382a41f094576bc190ad73ee.nq.gz
│   ├── f281b3ac11c1856044774d32e7cbb3bd77235623.nq.gz
│   ├── f3a264c98a2ee03375ae38080bd6e52dd562b91d.nq.gz
│   ├── f5181282ea607182d1a0b323a965cac08d45b592.nq.gz
│   ├── f7efdf611419ebaede1677d37778cc618108de01.nq.gz
│   ├── fb5474ee7892fff5a91f250ed38bde29573851cf.nq.gz
│   ├── fd2953e378a8b5ed54dbc2b9c61609dd4346e12d.nq.gz
│   └── fde1b29e45211f2083096dbb0037f5edd44b25fb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c3eaca5cdf1038a833743aed1ba86b55b4ee8c58.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 196 files
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

[twisted/ldaptor](https://github.com/twisted/ldaptor)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
