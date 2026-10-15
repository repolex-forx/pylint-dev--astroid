# Repolex Knowledge Graph of pylint-dev/astroid

RDF knowledge graph data for [pylint-dev/astroid](https://github.com/pylint-dev/astroid), parsed by [repolex](https://repolex.ai).

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
rlex download pylint-dev/astroid
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1eef6fa803056e75e240ad8ddef382a25322ff68
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1eef6fa803056e75e240ad8ddef382a25322ff68
│           └── chunk-001.nq.gz
└── blob
    ├── 00199535c326ca352b55da77c89ff27e62768ae0.nq.gz
    ├── 013899cdfaefed31a45e4a79b14ef899262a8411.nq.gz
    ├── 01f99fa3d55108922ab7d50d4ba79ee75ebb3e41.nq.gz
    ├── 021aa9a28506d0e08a54e64ebab4335a06df9a37.nq.gz
    ├── 03e660f08e5dad7277a17251319d165a4c1729e2.nq.gz
    ├── 04591fd6cb914552c8dabd3662e89b935feb8884.nq.gz
    ├── 04d3709317fba4a23e5c765fd82a007c3d8c7dc0.nq.gz
    ├── 05528cb4b10cf25bda04244944cfed56bcf85650.nq.gz
    ├── 073135d2331e1186351e4093d2082412b3816403.nq.gz
    ├── 0bfb5a62b4f6c2c8cb1a6a865bc2d4b36ebfa64e.nq.gz
    ├── 0e479b199709e9e1b0fa18c0cc33a3e952ec59fe.nq.gz
    ├── 0f091dbb7abd2e0a6a4e08e771909355de77293a.nq.gz
    ├── 0f16a3b5ff4679dcd3592ba4c1c1e0a93bfec700.nq.gz
    ├── 0fdf6905a4adc04d96b4ba434fe3deebba5b77c9.nq.gz
    ├── 10776af361c2d65e5473ed417333b8dc6023755c.nq.gz
    ├── 11413476731c42ea30c3625a8db422514fa9e441.nq.gz
    ├── 11cd60871803c318814f13dbd77b1cb85593a31e.nq.gz
    ├── 11fbb4a22107c207d7067159b58ec2ee6e5f4a2c.nq.gz
    ├── 1307b2391a5a66fd0450b0a4310160fd5c234716.nq.gz
    ├── 143a8bfe3edab6613cbc0c4d0139083b6373f00a.nq.gz
    ├── 182e0fbee1eb56b02def2270ecaab5571f264f09.nq.gz
    ├── 191435dacc89cd103779f3003cbf4c819714b6f4.nq.gz
    ├── 1a886aa4f600903a11f0cc6bccd3f99116a874c9.nq.gz
    ├── 1afe6eb33ce59d2a067d4da718a9fd3181885478.nq.gz
    ├── 1c5698c099c39d52caa66f49ff818516a895beb8.nq.gz
    ├── 1d0b12b347d41dc1b60e9193260303a6565d24dc.nq.gz
    ├── 1de9bebcb57789f47351754e30c5c7c2b16bc7fe.nq.gz
    ├── 20b1703e2d528fa5e8784f0527cd38a3f7d55e65.nq.gz
    ├── 212bc011b5e07c2caf495d5ef97f159cfa84f662.nq.gz
    ├── 214f16624db67d3fe7f889464589ef4e51607be5.nq.gz
    ├── 22dbda8f434fb8ec4391021df8d65749a173ed99.nq.gz
    ├── 239499a6865416d8df5957b4d82fb2d44783525a.nq.gz
    ├── 24ab47327dff550e60c37e2293e5859f2949a1e0.nq.gz
    ├── 2538378216c6d32fe5e429a75cd6cab570c35af7.nq.gz
    ├── 263b0007ba5fee9bf8919bd550eaba3463261730.nq.gz
    ├── 26577e810a9b51944afe9106ba2ad54a8f98d333.nq.gz
    ├── 26cee629396dc2848444f14429818e40c142ec24.nq.gz
    ├── 280a725882a730b638bfd9834bc841b8a4b0b2ad.nq.gz
    ├── 28d021bdf0a714863b8471acf98fbe2b87e677cb.nq.gz
    ├── 28d0ccce8d13b835e745e85be0cc771539b2d7dd.nq.gz
    ├── 2accf6e74fb73f02009dc8519f4b2c2494ad70ba.nq.gz
    ├── 2b2deabafb37af3d3610713a606ef02e17c12d6d.nq.gz
    ├── 2b4b104d80ae6f98fa087af9a46b7f8c3565da0c.nq.gz
    ├── 2c2c81dd2912a095d9a0bdad0c40ce64e0ffe6e3.nq.gz
    ├── 2cfc6ca803d0fc48e8ac343a1788f6eae8d808fa.nq.gz
    ├── 2d922c57b91627c723327ba0846c1f40c5d0d3b8.nq.gz
    ├── 2e4563937be2b2b905d1c5e2498e3a9689a8679f.nq.gz
    ├── 2ee20a319b996a20475d61c35a5a8ccb9863e7eb.nq.gz
    ├── 2f58f1b5088d4748e08b34a0f7f2dbe5d8b33288.nq.gz
    ├── 2fe2c7f47051b83206c1b37b9e3d298f2ded98e7.nq.gz
    ├── 3031057e149f1e61f964b9a43cc1a19495b5ec0e.nq.gz
    ├── 304da8282210bfd36b27593b8d39c616af7a9d97.nq.gz
    ├── 317dc4d9852df72ba34e10a6f61d1838cbbd969e.nq.gz
    ├── 3197fc908a9ceb46990e7a94aa5244f07467aaf5.nq.gz
    ├── 332e2e7236c7c9624b57d2693cc9ecb15a71c068.nq.gz
    ├── 33ed117c143f625747d3f12bc64254e10ab4b94d.nq.gz
    ├── 34be6d8cc5effd4ee3879527fb86f1548fe00ae3.nq.gz
    ├── 35f7a65fc2ef8c447048d78a74ce93a237f8cdc6.nq.gz
    ├── 3715ff1b28353b67f6bb87bc2a28395f636a4f1c.nq.gz
    ├── 3781889b7cd802f771ebf2b92c3e475da163a098.nq.gz
    ├── 37db476a224096678053a2b4dea3026cb4be3634.nq.gz
    ├── 38306e34521617c1bc58c8c5079254fdf038a0d7.nq.gz
    ├── 390dcc8469113109bbe120a1a0ab04a07156c42f.nq.gz
    ├── 3941f197ecc42c58e91a9d37e558fc199930282d.nq.gz
    ├── 39cdf2ac4a4c6eba580628412b08178b901efaf6.nq.gz
    ├── 3a0033a2a19e45ac26301c52da175234bb3e0e8c.nq.gz
    ├── 3a95feb816c16d99d7162bbd76ae7ec4674112a2.nq.gz
    ├── 3d2b4b14efe535966493ee555dd7faa81063a251.nq.gz
    ├── 3d90f3624a670bc1a4c1626f43553d5a458bfb93.nq.gz
    ├── 3e8517176c88360597124c90fd0ccccd762294e8.nq.gz
    ├── 40845858b0d323f5d6d071100f5f60dc267c318a.nq.gz
    ├── 4468ccdf6bb5a2c63628ccd3a00dd2d710b1ecc1.nq.gz
    ├── 45956b3cd8424b5d8fe174406609b580fc81445f.nq.gz
    ├── 46a444e14697aae53c66e46c4630c0542fdadbe0.nq.gz
    ├── 4886218dcb6fdd3c527b979d05b089af9aa62798.nq.gz
    ├── 48b9412eaad7dc7068179568fa78aaa4e5ae0616.nq.gz
    ├── 48fdfdfbfe687dcf951e4ff8f396d5fccc407be0.nq.gz
    ├── 492695343fb10b4d96681b63c41d88e290e2d08c.nq.gz
    ├── 4965861277eb42d0ba549420b6344a55c29a28a2.nq.gz
    ├── 4a52b18e97bb3e8b7d1a573719fb6721610b7bdc.nq.gz
    ├── 4b238deacab8a0831ca33068f4cd88b8c06523a3.nq.gz
    ├── 4b7244ba001a3c7be05f59f737bc6a5664480ce4.nq.gz
    ├── 4b950e1a129e54635e0e98103ec298acb4449d64.nq.gz
    ├── 4cb89f809b38d9feed93b9253ed6f5f11a8bbfef.nq.gz
    ├── 4d47b1ebdddf8bf9a0fbe4ba0a653d240d5c4463.nq.gz
    ├── 4da82d140c6d26c93141ad6a2cb4b7e80990020e.nq.gz
    ├── 4efe1bda5cc5755e740c2286e31217838c46957f.nq.gz
    ├── 4f663fb34417fc24584d8899f6e411b984ef7bdc.nq.gz
    ├── 5055ec419410167807815002d3e2c8e99e880453.nq.gz
    ├── 5072c047cb2c5149821f18650c7112ca8b0e9336.nq.gz
    ├── 51db92a3c6f6abb46931119e906dacc6402d1343.nq.gz
    ├── 52ae7487712fcceb841f7ae851cc593b11cebbf7.nq.gz
    ├── 530edcc070c19214ee777913ed2dd3dd88fc3adb.nq.gz
    ├── 536c3ec9ebc7199a6e02b298cfd79a55fc349b32.nq.gz
    ├── 53b9c0fc3f37d546a2f8c1b8fedcf95de3f3331d.nq.gz
    ├── 5420ef902c0d6916c74d892172fad9c60875652a.nq.gz
    ├── 5447a864cda293a22586fa2ae7ca266a00fe2b9a.nq.gz
    ├── 5536e876f52ff022d45653bbe2af23b599bbf4ad.nq.gz
    ├── 55ae384b2d76169e89f95511af794f43344cf897.nq.gz
    ├── 57368cc5ca796544006df8c009adf0e050c2974e.nq.gz
    ├── 5739f6bb66c33ad7963c910ef4a1de459e09b395.nq.gz
    ├── 575d18b16ad1c1ed1489249f82c3bfc65d44d60f.nq.gz
    ├── 57fceede9777560ea2ffa4783732a70bba0ede14.nq.gz
    ├── 587765b5a7b05ebfb4a8c670406d0cdc61d4085a.nq.gz
    ├── 592bde5f7f501a79cec9b5295df13fe1d43ccc8a.nq.gz
    ├── 5a7ced28710e9f6d80c5d521a6b6a0969e86c639.nq.gz
    ├── 5cfd50ead7e7536ba5cf94a11d207105c527c25a.nq.gz
    ├── 5d28f61c1031b6e02522686772ab45e429a51b82.nq.gz
    ├── 5d2997cdf03141213e3454d3bfe36e0d26709ef3.nq.gz
    ├── 5f64c2e57c1a11d3c79909833e9b93c6d0b2ee99.nq.gz
    ├── 6358d4bad7925135b2a02f1203619f66aa665adf.nq.gz
    ├── 63d5a744643145c65444907dff657d3bc177aa48.nq.gz
    ├── 641f11ed8e7c527828e4e11dfd3d9526662299ba.nq.gz
    ├── 643085bc41b1abdef5a38fba0f1c2a52fac46e54.nq.gz
    ├── 64bd367e5d7566d05054293ce5c7c11d3ea54f40.nq.gz
    ├── 664b174c184f76b2c7c22d264b4a3aaa971ca315.nq.gz
    ├── 672a1d9d3e4d3baa4d3c9cfbb68a9897c713f822.nq.gz
    ├── 6744d431a56851be1723698cda94172d8c8116bb.nq.gz
    ├── 683aa919c33e88264fc86dcb95c044d200db13e1.nq.gz
    ├── 683cb72c204eb85c83e70df628306a38306386d4.nq.gz
    ├── 6856072e841af2a7b973bcef61ee4ef641da9243.nq.gz
    ├── 68f581025e2d11e8a0bd4b9640bb841bf356b01a.nq.gz
    ├── 695ec334df3dc79dac4e7d1f03dac1b3910af074.nq.gz
    ├── 6a452e6ae328b7c956438b6b9f0dcba1387fc77c.nq.gz
    ├── 6a6751612c3d1bc40f0b133c00d9a10a3d690e4f.nq.gz
    ├── 6a9f7e2db8f165daf763b1e4a4be2be32efa17c1.nq.gz
    ├── 6bde22f2e5309c7cc19d8bac9dcb312eabf8389f.nq.gz
    ├── 6bfc633b2b37b47347287aedcc12f91f5a733bc6.nq.gz
    ├── 6c2e7af74f14f5a71c31d3288d8a683da08e084c.nq.gz
    ├── 6d18f279eecf557a8ea5d2062192294c740200d9.nq.gz
    ├── 6d5e62ea1a710e08308682bd98fc075efbc4a417.nq.gz
    ├── 6dc4828986ea325ce981475d53891489df731d75.nq.gz
    ├── 6dd5e4eff96c0acc3a0a3f2ea930d8b95738e17f.nq.gz
    ├── 6e66c630f1b47dac623ef764616e9e032194deb6.nq.gz
    ├── 6eb1fde09d59ad66f69f7958dc0c495e7cb1b702.nq.gz
    ├── 6f2e8b2d89913849602e4a8beae74913596e18bc.nq.gz
    ├── 6fbcff414a681ceb18a429af44b8a853c9ff2750.nq.gz
    ├── 701aee9fafe0b937fd42712987001f92ed8356a5.nq.gz
    ├── 713e5591a98bd11765e9e01b3167e8013974161f.nq.gz
    ├── 72dca4d5e478bb1fba106b8999b16638b5af22a9.nq.gz
    ├── 7379706192ee2e0ed51b6a333a8865c7fae27ee9.nq.gz
    ├── 74b26b82caf5237de227f7b451201c2938883ea0.nq.gz
    ├── 75a352422eb36a0c9983a9f449782c5127168cc1.nq.gz
    ├── 75b5e3f24b51f0e975ccedb067b8d9977c780704.nq.gz
    ├── 7612079f11b2c20f3ad57689f47f1ce061145320.nq.gz
    ├── 770da04038748527a0066a5fdd45299541cddbe5.nq.gz
    ├── 77cac2dd06fa0712a4fc33e669621c4fdc65b1e3.nq.gz
    ├── 77cf0c5f3ae6d3ffb30376a10724e1a364926c27.nq.gz
    ├── 7976f2fba579c92bdb5db67c6e4d581ba660e28d.nq.gz
    ├── 7a2934d184e51f641486e9ae1c3c2179e1eeab21.nq.gz
    ├── 7d87166279a9e64e6b0bc24679c0909be7508a31.nq.gz
    ├── 7dc92129669a360f08f630891dc61a7aed91ed80.nq.gz
    ├── 7e324f4114e015b47e0fe74aac604b2d6b5dded1.nq.gz
    ├── 7fa453aaa41f0426bb81564dee318e164a22361c.nq.gz
    ├── 80710eddf43bf4faf774fded4a2620c8426d83f2.nq.gz
    ├── 824002d257073802574c2f512e3373206bc85a5e.nq.gz
    ├── 827a24d1e37e19bb99076d04749e807d680b6c51.nq.gz
    ├── 8342bd09f9f9bbe4e606425da226548f890fc781.nq.gz
    ├── 836715bed930fcc70c8cd12959e41eb40d74c84d.nq.gz
    ├── 8391e599716b05e698a643c2b4edd774a95c58c9.nq.gz
    ├── 847fc492d32464dfbf0631326abbc5e81ae2c3d5.nq.gz
    ├── 85f6513493214850bc0863394958fc14499369c2.nq.gz
    ├── 87364782e099b1000d09dcad63c9d0bfbf34fe0f.nq.gz
    ├── 885d4c541a6d3122a4d0a68deb96b31a14c3c578.nq.gz
    ├── 8892008d8f77a29b3bb039e9ad0fb6d41db49cef.nq.gz
    ├── 88ac0984388f5ca46e7db003a02eadaa3915e202.nq.gz
    ├── 88f9d955d19fc719a3f0b4a4e544731a4a75bef7.nq.gz
    ├── 8bbc46f57d44f97328116638436f0eff95f0ad5f.nq.gz
    ├── 8c9aeffd88b181827b82f27ca180018f5cb81092.nq.gz
    ├── 8cb562db21843eb0dfbd0b767281ef438e13008e.nq.gz
    ├── 8ec38ecd8aa0df51354332faeb6456cb4dd00b4a.nq.gz
    ├── 8f607c234c6e8447c3b201c84670dd1d1be26b73.nq.gz
    ├── 8f7de1e803e0301946729ded20ed064e971f06d1.nq.gz
    ├── 8fea68b7072a3b28e415c15fb630cc20442a1c7b.nq.gz
    ├── 90661b226a40306ad960fb5c8fbf2086e82d8fba.nq.gz
    ├── 90a40d6ee735a1cc09473a5038428e220471c0b4.nq.gz
    ├── 90c2042b11059e223756dce1815b51cd0e5b3ba2.nq.gz
    ├── 91a629882e6b699ee6240513f556a673e30d948c.nq.gz
    ├── 91a6c6f06d9b7cf2b39938c62ec10ed5b0855e06.nq.gz
    ├── 91a962de6e71eadc25e06b1f926a14519fefe473.nq.gz
    ├── 9284bf1a7f84be01dc4b6fd4bef4d8d2a4a4ba6d.nq.gz
    ├── 92d30b991b4d02f7ed94ec0617a08aa733cbc32b.nq.gz
    ├── 9442ab6a2c7b177e1d3ac88ac2a3872db35658a0.nq.gz
    ├── 95f3e23c7ab1937b5270eaad1d1ff08a5f5305a2.nq.gz
    ├── 977802c8b80ce70a5f36411e787fc8de8b7a9c02.nq.gz
    ├── 98da5dd632c1eb64be06b52fb740246550499980.nq.gz
    ├── 9c5fefb59b0fe5ec3535f0fa51bce2774675d9bd.nq.gz
    ├── 9d2e163caf516c97878a3861facde4b5c1774cf5.nq.gz
    ├── 9d35aa3a021c530730a2dad28c68ce90a583370a.nq.gz
    ├── 9d7e7b5b9ff5bd02c5eed162c8a4433ea3c5fbad.nq.gz
    ├── 9ddc377f397257565d245cb800f9373f51159134.nq.gz
    ├── a1576e83e4a2aac84643ccfbd9f6c72edca5af58.nq.gz
    ├── a17645a8dd696d13ddb4c5fee6a87477e2c964cb.nq.gz
    ├── a22162ff9b1d3d11b3d54fcaf3de04606bced0ce.nq.gz
    ├── a24c3d6b845c5b4d1ad1f81bff2d567dc7c6f47f.nq.gz
    ├── a3f6610ac5351f93e50f13c2eabec79bbb99c5e7.nq.gz
    ├── a40e9a88a4c456938edf7201ddb99e50aabee2a8.nq.gz
    └── a48b6e7d9ff74a0942da77a3f69f9176741f51dc.nq.gz

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

[pylint-dev/astroid](https://github.com/pylint-dev/astroid)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
