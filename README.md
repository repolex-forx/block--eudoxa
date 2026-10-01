# Repolex Knowledge Graph of block/eudoxa

RDF knowledge graph data for [block/eudoxa](https://github.com/block/eudoxa), parsed by [repolex](https://repolex.ai).

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
rlex download block/eudoxa
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cfad9a02ad3d6f1bdac669a2f26d05f9b48cc49f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── cfad9a02ad3d6f1bdac669a2f26d05f9b48cc49f.nq.gz
│   └── repolex
│       └── cfad9a02ad3d6f1bdac669a2f26d05f9b48cc49f
│           └── chunk-001.nq.gz
└── blob
    ├── 007cc970a54fba6c8d268e75b5b444d9693db09c.nq.gz
    ├── 011f7394696db08c8c907987fe1f51fcab3f16c9.nq.gz
    ├── 026ace9818d70b83cf6c55c9a73763ccf243f477.nq.gz
    ├── 0278984f0d003afa49d356f4e5320263ea6f3170.nq.gz
    ├── 02eacfe8b1e494c669e9f6d34a1addd97183ff2a.nq.gz
    ├── 03550d02f48e726f02436aa948fba436725dd07d.nq.gz
    ├── 03a62e81b725c78b95ca7639bcb8774f0482336e.nq.gz
    ├── 03fd429ac4c3baf0e42fca9d1596a5adef47262f.nq.gz
    ├── 040b70d7454618b7888441006d4d55b35ff4fe8c.nq.gz
    ├── 0452ec19bf717d880c45c47f704fa733a7a52b3b.nq.gz
    ├── 047590e1e5a0ed0288141e6e597e14caa355e04f.nq.gz
    ├── 04a8bcda4035c2a6326827e45f0c50751f4583ed.nq.gz
    ├── 057b579bade40d5ad5e7253d060d70c65cbc4247.nq.gz
    ├── 058b77155b8870aa1831b16991498c2949960497.nq.gz
    ├── 058ed71539084c6d4af65a91aed0056b791b2cc1.nq.gz
    ├── 0664b3f1d405ad3480cb2798ea3127a847093949.nq.gz
    ├── 08004ebc66f053a8f26bc202107d399b471d73ac.nq.gz
    ├── 0952aa8683e864bf5d7d5db78ec88275c2a842a2.nq.gz
    ├── 09ddc752d8ce4fa06e76c6253c8d2043b05e7dcb.nq.gz
    ├── 09f532157f32e8e92b2a8057653843e9888785a8.nq.gz
    ├── 0a3153aa2e8cfeac805a4b765d6d27e39a1513d0.nq.gz
    ├── 0b58c3002b3ec69f97c37a560d18c541efba9414.nq.gz
    ├── 0b93fe14668262ad6531098029e35ce18a6e295b.nq.gz
    ├── 0bfa7aa256e46f776bbc18ce9c0eda9f35aa4491.nq.gz
    ├── 0cb0c5a6b8c09f204fd33a677e928873bd8a34e5.nq.gz
    ├── 0dcade5a73a0843b0d97a4b6867967d314e82345.nq.gz
    ├── 0e8bcb6a562960b3b4a70488b3a9236e383553ab.nq.gz
    ├── 0eae986e33563d12fbbf4dc485f9e9456d43e7ea.nq.gz
    ├── 105f58f93175c8331c1fda54531b91b0a88b59cf.nq.gz
    ├── 11f51d03deb8613989e66f4c5cd680156c67515b.nq.gz
    ├── 122b1af2e3e35779a2e6b75fad78e7e510c952d7.nq.gz
    ├── 1230c31660da076673029e4723db746264546772.nq.gz
    ├── 130eb22e609f1abceef2597de0f399d8f1cf4a93.nq.gz
    ├── 1388c0df722c3617c3eeaf1de389560cc101346e.nq.gz
    ├── 1405bc6474f82354ac6d7977ca56d071d602e36a.nq.gz
    ├── 1421acc300c2b10303218ae87dc71a6a859bc612.nq.gz
    ├── 14ea21cb8282fa81ab61c9671c8ae59a6150c72f.nq.gz
    ├── 150578c4b09180ba11278da3dba8fd02ea3b0620.nq.gz
    ├── 15670406edc270502199d82c7e42a927984db148.nq.gz
    ├── 160e99e08aeb9638b46e1986f3e65c39429880ce.nq.gz
    ├── 16ecdfc57199ed6077b956f19b4d0b58c81f8e99.nq.gz
    ├── 17590f477df08c863b981eab8cf71ca25aea5438.nq.gz
    ├── 17a2514c875114fbb76fa626158030a94a80f45b.nq.gz
    ├── 17af9f284f3f51b88fe0b583af70d210845ce442.nq.gz
    ├── 17f795ca1e5de1661864b89cc46cad66a6ca1594.nq.gz
    ├── 18723f3ed8422a0f9c326eed410d6c1b2748c21b.nq.gz
    ├── 1914f9e9148e1c88c8dc9b044ed5d0511f4c5ad8.nq.gz
    ├── 194302028398ca8acef1dbc50d461556ec048647.nq.gz
    ├── 197d43bd1ea5b1418e1191ed44dd3c3c47c736f4.nq.gz
    ├── 19d8c11f84191019267d358d415762be97fdedb2.nq.gz
    ├── 1a2050aadd07705b1253a6cc4566fd2f03cad81c.nq.gz
    ├── 1cee8795687484dedd46194d6a8d36fb89c6c366.nq.gz
    ├── 1d6e12577b3e2c4398bd0b563d57a297647645d7.nq.gz
    ├── 1e43a7ba7254ec6bae427e0368f4c98591114747.nq.gz
    ├── 1e72faae0fe19fb2c6948094f761227f49bb7cbb.nq.gz
    ├── 1f56cfd62725c26f8468c3463969c8d27f20211c.nq.gz
    ├── 20678a90cea7ce8e8122c3627714f1dc0826b2e9.nq.gz
    ├── 20792e6526fe396077ad81abe18236a0af3e927f.nq.gz
    ├── 2148cb290bcea559319f0f84af26bde59bb51457.nq.gz
    ├── 21ec43c2bf876a64ec2f3b229b91bde19f160135.nq.gz
    ├── 225114a2f278868af44b86e33a8de807d351575b.nq.gz
    ├── 22598a45c21682f610633bd3ae30def2bbbcdd1e.nq.gz
    ├── 225e728536cd87a96a51daf00df89decb7a85b4d.nq.gz
    ├── 2364927811166263ea2dc9cd4c53e42dc37ad573.nq.gz
    ├── 23af2fb36d757cf2a6d964957ce211e9f6cee21b.nq.gz
    ├── 2435ec27599c9000d7f8a91ebf844813d7b9699d.nq.gz
    ├── 24588efc0fa1452ded02387cb149d7b11acf3ec3.nq.gz
    ├── 2607b5c7c2e96ad42b6b8a978c77af0adf2c6e4a.nq.gz
    ├── 2617020f44d67c696cf8f23bf1c984a65ed9f343.nq.gz
    ├── 2623dbd1693421206bb825e82e201a2820f52ef9.nq.gz
    ├── 26a4313879874561eead5df6dbe1971616b8e0d5.nq.gz
    ├── 29f46ff97f2b79033f73c123c340aeba5172a0c1.nq.gz
    ├── 2aac23bfcce48e6e8a7364d25470f980c033eb32.nq.gz
    ├── 2ac8a5e53e80e7a6045c10902608a5a36b93070a.nq.gz
    ├── 2ae5ae1eef0611cc2ab2797b9dd35d4d49395bfb.nq.gz
    ├── 2b0c6d6056ff482bc69d458de26494da22179422.nq.gz
    ├── 2b4877d2c3afc700c22991ea8992e00240dac1ba.nq.gz
    ├── 2ba183a2ca1018d8d1008e70c0e2eb4bb01a7cee.nq.gz
    ├── 2baf3f58bccbb859e5159c8df77b10bd5e32ef88.nq.gz
    ├── 2c4b1c10a785d7c9a0654c3f2dad40ecc8d8ba16.nq.gz
    ├── 2d4b98ab5cce30684207f3bc05cc8a0f55f09283.nq.gz
    ├── 2d8748f3fe5bf89ad7010e688f29b5f843ffc3cc.nq.gz
    ├── 2dfb967864297dcfbd0dcbc240e336cfa664bedf.nq.gz
    ├── 2e0cd4476f7877802b0d69087ade251f41f6e88d.nq.gz
    ├── 2e4f3c6994ccb246fdc6095fe157fba52fcde3d9.nq.gz
    ├── 2f4a2e8d77b3568f2fbb510562696e3f306a3bcb.nq.gz
    ├── 300aea6323162e6c539ab11e256d64e3c70dc150.nq.gz
    ├── 301d3bfb9655d841ba8d299f28f8724f1eb738bb.nq.gz
    ├── 302ed38481bb80b9333fd0b231dbf4172efa1889.nq.gz
    ├── 3057c7cb8c5fd6ac0e633e8b2c4a112b2c563e77.nq.gz
    ├── 3078a2b0701ed18aa41459402dfe53bf9a040edd.nq.gz
    ├── 3100c4bd1624208e92ca5d30627a35aa1d755aa0.nq.gz
    ├── 311c646e802410e30345d0ddba0fd9180a54a0fe.nq.gz
    ├── 3136f1a13c6b373b6583c64f67f7153518de8849.nq.gz
    ├── 314eb475c93000a6a8ce54c0800cad94d27c3e35.nq.gz
    ├── 31d50501bcd6dbd6e4f39b5949679f8859c64663.nq.gz
    ├── 32032599df239512dc8beea778ec40ddaf550161.nq.gz
    ├── 332dad2e3307fb0435439fb2f516d367fb6479f8.nq.gz
    ├── 332fa8c9c99e726a5246b1e316630e9c6e5a3101.nq.gz
    ├── 333e2a398f578c1584a7a096cc9fa4a3dcd6f6ac.nq.gz
    ├── 3401c0bd669424135b4fffffcadd195ccb29cffa.nq.gz
    ├── 3645be61ffa3abf08d455c30b3fbd22a0b53965f.nq.gz
    ├── 370d21935de4faa020dd7b9baac685db8ce731f9.nq.gz
    ├── 380cfff347607db123ac07b3cd924f7edfcfd3da.nq.gz
    ├── 382a983dc1dc2de500b76cce1cd75cf111553b6c.nq.gz
    ├── 38834479522ddfb1bc1c2cc3774d3a6edafac3bb.nq.gz
    ├── 38e0c01f0c2cde9701d232727a8a33d1da564201.nq.gz
    ├── 38f147e1a807ecd5e1ea600cc1a62b514464b630.nq.gz
    ├── 38fecb4e69784ef2a3aaacc44e82f8df34f0e6c5.nq.gz
    ├── 390cf40812491eeb3bda519611bbd6d4eae7174b.nq.gz
    ├── 3b2c67ed513650a9cf8435e86a809ff6a7aced89.nq.gz
    ├── 3b44517bc16470fb2d26241a2e16dad1f80077f1.nq.gz
    ├── 3c2c9dab06aa17050553c804fb98d37f7413f58e.nq.gz
    ├── 3cd9b186c464b5cf24d60fdb1fc53840633d702e.nq.gz
    ├── 3d2001477679fb576930734ad032af0b970f6afc.nq.gz
    ├── 3dd3382f95e6ff4d9bed6fd865fa1ad1b623f477.nq.gz
    ├── 3f56db9c4951ac96e04973d59109e75b919aa763.nq.gz
    ├── 3f771f614e97398c2c76fbb4a3c229f5ecb3cdb9.nq.gz
    ├── 4065e444360e6a7a91eac23d69b430b288853b92.nq.gz
    ├── 41186d5749e5d9f4a524c8f6cd8d9bd3ddd78359.nq.gz
    ├── 41a9f92d6a75f00b41f66efede7db9c770d058d3.nq.gz
    ├── 42d9fd615f496f4d586bfe0931edc7acecc82efd.nq.gz
    ├── 43315247f7082d66cf78e9ebc16e022ffc3985f1.nq.gz
    ├── 437010d2fc9a5740a5d93f70b25d4a2432873fa2.nq.gz
    ├── 4408b73f8ce7bc1cd5a513c88aeb68f3d049a248.nq.gz
    ├── 44775ce7cde54a726f682b3dd988ac4577bfd8aa.nq.gz
    ├── 449e334e731e3ce7925768fb4b15519dac2a74c4.nq.gz
    ├── 45fe983556e66150b3eeb7370eec9d3a2549f1dd.nq.gz
    ├── 472f025787b8557bb05177a97c4f134eb3faf2e6.nq.gz
    ├── 47c4931e1650509251b88c8cdc3bf4c4777b41a8.nq.gz
    ├── 47d47ed745d70108900e3662991682550e9cf4ed.nq.gz
    ├── 4856a088c40ff4202abb6c4267ab53dbd06eee19.nq.gz
    ├── 48f1f20fe5f1c5cd22a3ec4d4dc2e91e3b785213.nq.gz
    ├── 493ed438ed8635035917f58fe1938e7c7465367b.nq.gz
    ├── 49e1ac2cc7817377586658bdf1d92cf73ba60a93.nq.gz
    ├── 4afe34be080a55e70e7914a2fb73d60496a46355.nq.gz
    ├── 4ba32be501cec054592e3c348201893a5101260d.nq.gz
    ├── 4bbc6bdaf218966565c51dca548b30853e806b83.nq.gz
    ├── 4be107063b23ce3b368e0c3e553bfb62cee327f0.nq.gz
    ├── 4bea6b9ebc8069e3293aba749d040e5af03070da.nq.gz
    ├── 4c2486c8ec3f2440d2f59d4743765afa6fccbd16.nq.gz
    ├── 4cbe01e23a7f72295e7e650935891ef87cc0ae71.nq.gz
    ├── 4cc55400a2fad2b1fdc263da48629fc6e7c40be7.nq.gz
    ├── 4d64f5928f2e7cb9e69d5e85e755584db2594f4a.nq.gz
    ├── 4ee130c49056c26522c7ca8888cc87c1cdc1fc5d.nq.gz
    ├── 4f4f2d11711ecdba0b7f5e54dab55a785cc7236e.nq.gz
    ├── 50144701cc9f9ea1b9319597eb0eff16b9a9770f.nq.gz
    ├── 50e06287d2b919a6d764ed1bc30beadf117f3d46.nq.gz
    ├── 510aa856ec98aa67f66e69d3e6b63d89729d35c6.nq.gz
    ├── 519fda6ee0390d44d5ed902ffa3a3dfe9184e5ab.nq.gz
    ├── 51a860e99a57ddf84463ebcbaf5f8c8cc34d0a9c.nq.gz
    ├── 51e7a4d3cb87c8c3d09d8014f30f09bd250ff1e6.nq.gz
    ├── 524066a018a3074bfc153e5feb7fc950ada3827f.nq.gz
    ├── 534f4ab7cc06fa322f39e6ad2991d234d9854808.nq.gz
    ├── 53550033c4b37a1922a69a18b2138f0e0e8aa623.nq.gz
    ├── 5365e53affa794147c298f59499efe2108233f5a.nq.gz
    ├── 5377df975832ae7ad1aa558bdc256e9f1bd24bef.nq.gz
    ├── 543c212a64cc4741c4286251652f3db7f40bbeab.nq.gz
    ├── 54f3998f3acef6de4373f1046721c0b15f9afcb2.nq.gz
    ├── 54facb4847139483561fe544296a4385b8f05d6b.nq.gz
    ├── 5534d03ba70b3ab52aa6fb01fd87cc15d851153f.nq.gz
    ├── 555d200df04c76c396374c9552c96306de0ae4cd.nq.gz
    ├── 557bf4fa729848d32d5fd7a69da2fde6e5e5f80c.nq.gz
    ├── 5580fb8def1bd105dc8d068b3519877906893484.nq.gz
    ├── 571d733556c0db8118f6a48b8f3487f3c0e99606.nq.gz
    ├── 580e7775c440308fde21c9923e02f56cf2052a31.nq.gz
    ├── 58498491a1269d9f9cf8016cb47c3e1988cecc22.nq.gz
    ├── 585bb1458a142a4c3e5e2e194d12f5bd228a14a1.nq.gz
    ├── 59051d9b0234f8e2486d0495a0b78e791e8f7dc5.nq.gz
    ├── 591618c5acae1c476dd77ad75a54f9854bc82bd6.nq.gz
    ├── 598465f18578f03ff051336f9825842929be86a0.nq.gz
    ├── 5abbccfb8c0079f01bb7dad5a38de2d213a20652.nq.gz
    ├── 5af1cf3b6ebbe1748b5547997d7f812188090750.nq.gz
    ├── 5b373675790917ee51b6eb427ce78baa751be803.nq.gz
    ├── 5b474e3e188ea37abf3215870fa1799034054d11.nq.gz
    ├── 5c4db1cf5d660e747eaac5a299ac9c035af66e8e.nq.gz
    ├── 5d417827f035eaa8017fcf813c11311b99d2b7b6.nq.gz
    ├── 5d8f30c6711d5fbb5ad0a60a0620d2d4aa67219a.nq.gz
    ├── 5e3c928e347133705260dedc774c8898f01a4ea0.nq.gz
    ├── 5f8e805ac5d56ceebf3fa173523d20bddbf82abc.nq.gz
    ├── 6005a192c13c485bcab92d5a1dd96898b6840607.nq.gz
    ├── 605f5fa0f4a1331b7627896990ad91b6136c571a.nq.gz
    ├── 60e537c7f41f67deb456d05c6d162da8af8f9c05.nq.gz
    ├── 6133fcce0c7e5d277a7ca3ceaee6c13415a35e1a.nq.gz
    ├── 61c8aad88352f06087cb5c0a0dd0cbd8377e62fd.nq.gz
    ├── 625381b995add7da24099d5d9b91d98ad96b2496.nq.gz
    ├── 62783a058367ba19cab86ebfee9d689caef5dbcb.nq.gz
    ├── 62daed4aeac5acfbf00d876b9d3486bfd7d69897.nq.gz
    ├── 638846cafb726b1a091e47c3c4678698bf44ca86.nq.gz
    ├── 64217903302eb3d1185d3ec92beb91a252ecdafc.nq.gz
    ├── 64a8a24bec1828b5843859ec00bb95ade71d029d.nq.gz
    ├── 64e2ef859adbab79d83400074572ce71968c3f4a.nq.gz
    ├── 65082f11dcbab34f1136736e51cb3e62348db723.nq.gz
    ├── 656947319b5d344b04acc6be574754977341c4f2.nq.gz
    ├── 656e8fba4fc75a18f6c42498e1d0e10b5dab4223.nq.gz
    ├── 67a083e1aefbdc0b2b2c33c72b478bd220916323.nq.gz
    └── 67e4f7f323e4cd06103c686b5df29ccda4f6c13a.nq.gz

8 directories, 200 files
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

[block/eudoxa](https://github.com/block/eudoxa)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
