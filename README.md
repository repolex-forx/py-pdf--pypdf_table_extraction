# Repolex Knowledge Graph of py-pdf/pypdf_table_extraction

RDF knowledge graph data for [py-pdf/pypdf_table_extraction](https://github.com/py-pdf/pypdf_table_extraction), parsed by [repolex](https://repolex.ai).

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
rlex download py-pdf/pypdf_table_extraction
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3aa87032bf37d7a7e9a0d96c07e3151017168d47
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3aa87032bf37d7a7e9a0d96c07e3151017168d47
│           └── chunk-001.nq.gz
└── blob
    ├── 00e2da4049641934100d7cd0aee2a9cb3c9c869f.nq.gz
    ├── 011993a1e79bd8808db3a1a57bdc823dd284d292.nq.gz
    ├── 01722bbd7956587e413c36c524d42e4fbfbe7c8f.nq.gz
    ├── 01adffcdbd3c401d14604840956719854e27a6f2.nq.gz
    ├── 02780f78ae00d4306a7b56ca174571904d0fdbf5.nq.gz
    ├── 02d1e292f1c924518a1f1dcc2336a69730f7af2f.nq.gz
    ├── 044721cbc9390a7947f66a63c4f433ae3bd93fd3.nq.gz
    ├── 049449c3863c649ed96c02d8f8eac149a2d42157.nq.gz
    ├── 056f4da6c9b4e6ae0cd8c79b3fd0d3fcd73eefc5.nq.gz
    ├── 05af9a9bc2c1918c079f13b51eaaada3c7afb39f.nq.gz
    ├── 0634ca2de2a66a452ec380f1978bc65da7275f4f.nq.gz
    ├── 06684d8a4b5e4f0a3c694857d3683d77952531be.nq.gz
    ├── 0673aae24729423cc63839f01d02246f505761e1.nq.gz
    ├── 0693ca4104f0cf0491c8330ee25b26ccb19a5a53.nq.gz
    ├── 071efd9f5290f78e101c3067fff3b11bd08d52bb.nq.gz
    ├── 07e0acace723099d48558eca7f886edc48f92b8e.nq.gz
    ├── 0835c6716188e487edf9b409660e9c5343ce493b.nq.gz
    ├── 088f202a9602116403f89eb9ef0d25c536f99578.nq.gz
    ├── 089cc2b172f45b7a1def7cc313aa6315773f5297.nq.gz
    ├── 08d16230b7cdba0531dbfc955c41878e38ec4f91.nq.gz
    ├── 08e8d69e93166400cf53859adf790e0e231acee3.nq.gz
    ├── 08ed7263033314a10a0639bdf1465eb884722b8f.nq.gz
    ├── 097518aacf9601b35853912da1e6258e9c4250e1.nq.gz
    ├── 0a3f36c19906d57d1d636079c09bf58e7f52eecb.nq.gz
    ├── 0a7207b988c5736329e5a7de5cf186667c5ed92b.nq.gz
    ├── 0aae7b97c1c962edba6451f962f34ee86ed63391.nq.gz
    ├── 0b50733f776e7187ebe76f50abe28de6106ffc03.nq.gz
    ├── 0b9d854badde4ff4ddfd1f7f22ed67d41f07137d.nq.gz
    ├── 0b9eec66250895586b9aef0a0a33f119fbf2f9e9.nq.gz
    ├── 0c1fb641a6e5b168133ce3007a6e7c45aa467655.nq.gz
    ├── 0d3dced61e390dd281811df6fef21f9081d3701c.nq.gz
    ├── 0de01ef86de4af74ee9f2938d9c8cf99bc30b2fa.nq.gz
    ├── 0e0ada2352eabb63ef21fb186537ffcb945bfdad.nq.gz
    ├── 0e6837014b17c8afd9e8d3c0eb2e168426304d3e.nq.gz
    ├── 0fb7d4a3152a393c3a49691c17e6fc2348932120.nq.gz
    ├── 115c596aef888f0d111d1100b288026a3ebf0da7.nq.gz
    ├── 12e55bd9ccf452c14694c46d25cc223c2340f1e3.nq.gz
    ├── 1310156f0750c8e62fc15964c292a0c6f0fcd096.nq.gz
    ├── 1461d7341d9d22646758da544ba62526496d8437.nq.gz
    ├── 14e55a50fcb3e702a60dadeafe724de643dc67c5.nq.gz
    ├── 15011585e753eaafd6f6140a77125fab889fc843.nq.gz
    ├── 1504bbf4b88f9e17719becf429854c76d0556d8b.nq.gz
    ├── 1606cd288c239a5da0b71524199c512aec279437.nq.gz
    ├── 16fccc3cb25df3fdba31e779d0cd56fdf119226d.nq.gz
    ├── 172864672339b9a59b3b96eed966e945224c4d5f.nq.gz
    ├── 17ba812083045f1d62bfd5e9f4fce41df27a3ddb.nq.gz
    ├── 17bd403b3a076551202928eda5bb2509aeeb6327.nq.gz
    ├── 17d8a0d90f3140ebf89f836a7c2d22620cb795da.nq.gz
    ├── 17dea229b583a8d6448891e4a8c0561c390f1f06.nq.gz
    ├── 17df8c24fbd70e8a64b3e1139c685a43e3e470f8.nq.gz
    ├── 182ca5ae724996af6a5516ba4862a96b12627244.nq.gz
    ├── 192aa10b76de80320d43cc2bf15f5fefbdaa074b.nq.gz
    ├── 1939b001757084b5b71eee239a01a2aa6138bf7d.nq.gz
    ├── 19fff40c7b729026b26275453f2d774dc443e8d8.nq.gz
    ├── 1a43f84cab0e429e49ae269a609f9d61ab7bdaeb.nq.gz
    ├── 1a5a7b2a5a485ca0d16bd63394cf68f7f63f4458.nq.gz
    ├── 1a78e84a5546b568dce6564a463993a907a53aa6.nq.gz
    ├── 1ba2ecaa0365644ce95e60656ce6390ff1de9405.nq.gz
    ├── 1c41e7389134d8d13a334e05b716e348930444e2.nq.gz
    ├── 1cf81bcd89c6263c451fb01fb16733d363647fbf.nq.gz
    ├── 1e00bd397ecdf9d830a171237e4820dc4a4ed44c.nq.gz
    ├── 1eca2428bf95222bfa8569074dbcf40bb33848a2.nq.gz
    ├── 1f2cff03b382ff0ae0ab9d76951000c8becc72d5.nq.gz
    ├── 1f4b7b1b57781bd92f153fc518ba2c56de0f64cc.nq.gz
    ├── 200de4c0efd8d43296b7f879a5fbb2d8fb61b312.nq.gz
    ├── 20680bda43d38aa7dc96093c1980207e21875582.nq.gz
    ├── 21a15056466b8f49136e6faeae644acf1f06dea0.nq.gz
    ├── 228b5cfa58c59d2909ee67245eebcc3a81d59721.nq.gz
    ├── 2316c32811c5847981627725e9c7587105b5f7ca.nq.gz
    ├── 23ac85b884593807222114d781df43b9f0130730.nq.gz
    ├── 24afb34d3340241d6779cfaebc12ed0bd993a1c7.nq.gz
    ├── 260f5e011ea73a8bec94a878df124ad078afbc6d.nq.gz
    ├── 261d6f3c9bf3e508151320c1d9f1ba0508fa16d3.nq.gz
    ├── 26fce5dad991d03396cc957a5f7eaf38e049485e.nq.gz
    ├── 2967565ad32afe339c88d3c1328885786cf42ee6.nq.gz
    ├── 29983ff26c9ac83c23099c203151cf4991b10c01.nq.gz
    ├── 2acd52978c4abb7b3c6c76f81166ccc8d1e3f4db.nq.gz
    ├── 2ae43325d0c2cec656487b88de271ed91dc0b1bc.nq.gz
    ├── 2bd199fd7967d860da2c681c621a5ab29f3b0ba2.nq.gz
    ├── 2d01b5740daecf62e905c68b60a7122d450aaeba.nq.gz
    ├── 2dc79401c5d5f7aab486ae0665b95702e405ae92.nq.gz
    ├── 2dea01519e0e54635d7ae015d119e87443fea83d.nq.gz
    ├── 2f14f161675c1045764841a72d208df4cd6d8d2c.nq.gz
    ├── 3134e0f7f6fcdae01fb8f9affbb6b6ce3da538b4.nq.gz
    ├── 326a17cf8c95fefc32bbcbb704801da1cd75a86b.nq.gz
    ├── 326f39ec07b53e30fcfb2aa967bb95d5d0484b7f.nq.gz
    ├── 32f83dfc74c75ccced0e0d841e35eb4fb7162e63.nq.gz
    ├── 33d59600a228bbc962090f39b06ac4a6c69a5dbb.nq.gz
    ├── 3589dbd16223d2b7409dff22c366e259e198f2c8.nq.gz
    ├── 3739bf09c09ac4a35cb9a4ef84e598783d58450c.nq.gz
    ├── 3752173bc57d66f95f901e93000671a5bdf38128.nq.gz
    ├── 378fb1e037f9c530472335ee89ece021aee1343f.nq.gz
    ├── 384b496de03edd6eb6e17ca6c4419f3e3822f1ae.nq.gz
    ├── 3876ed3d2ec216dc6289189da96b0690e7d4e28d.nq.gz
    ├── 395e8344d0ff47d063e78e798b658c9bde960b8c.nq.gz
    ├── 39a8546ce0d8ece82a9b38509deb5497ee4549e2.nq.gz
    ├── 39bce841bf2f77576a216ee0087124146b0cc1d0.nq.gz
    ├── 39fb826d9d360519152c2b3f13a82325c424311c.nq.gz
    ├── 3a268a140d482b38b6fdc771f99c549acba392d0.nq.gz
    ├── 3ab038d1158ba1b321b1dea6e94b692522a84808.nq.gz
    ├── 3ab299b29182930ab2028eeccaec58fe2a77f84e.nq.gz
    ├── 3ad4b75af832dc82b297cda83a7e5375741d41c0.nq.gz
    ├── 3c23fd4e61151c353ffd68ce17e9f39659c62c2d.nq.gz
    ├── 3dfc2c777b5b3552ea60205bcd377e9358c04fbc.nq.gz
    ├── 3dfdd591ce81b154931fea72034754e2e6c9eef8.nq.gz
    ├── 3ed428eff9abdd229d8386ebfb86d51f85e6312b.nq.gz
    ├── 3f97754244077cbea8040c9896d4593ca206f279.nq.gz
    ├── 4013832229a1a61a23de3280ea8379d525bc1969.nq.gz
    ├── 40eb80879147b229529f3ef390b3c484863bfa06.nq.gz
    ├── 41a166e0efdbdaa0744c1d2af926a0c156f2afc4.nq.gz
    ├── 41f27617f8f241b0be00a5023045659434fb5fc3.nq.gz
    ├── 421824ba525bc33cc3417b8e71fd9a3bc8b97397.nq.gz
    ├── 422fad937561b12fdd35e6f02fa58ba16b5d40e0.nq.gz
    ├── 424b152ef7cae90f184379b4364cdf8352d87f91.nq.gz
    ├── 42683c84a833d3b36b6febe39412b651f4647eb9.nq.gz
    ├── 42921a972c204a63b5a5e8e1656728e93f2be4d5.nq.gz
    ├── 430e6982b194317918be5310d334b335c3b70caf.nq.gz
    ├── 431ca0a99d12fc2cb8a8ac86ddc3fc2699dd42f6.nq.gz
    ├── 45b3de3cfd8c55d5176e8d231ce239cca5783383.nq.gz
    ├── 461ed5b5ee9415db3483579f7bfcb740860d223b.nq.gz
    ├── 46b5f5a303f4da70b528a693cb4b6f328a051ef5.nq.gz
    ├── 46cd23620cf35a7c7b0116777be2cb9b3aa43677.nq.gz
    ├── 46cf9b6e39e87fa4915be4a05bfab5ef48a6ddb1.nq.gz
    ├── 46ec129c865fe83b928acb073e0b221a56394be8.nq.gz
    ├── 46f0af1fcb58cfbdd39cef2bac93cb3511f0479f.nq.gz
    ├── 47497d6788fee59c228d866b4f92df4d1d33f586.nq.gz
    ├── 47d764224e1d0057cafe52b2aa2e34d129679c00.nq.gz
    ├── 4846e94f5df5423c59ffa735326d31aed64799da.nq.gz
    ├── 491dd177a86a4a8ad4ced71616eff1d392da80d1.nq.gz
    ├── 4cd2ed48d32d772ca3ec826db3cf0a2054091e06.nq.gz
    ├── 4e1ac7500bef90448df62008c86c6e9c9b1b04ab.nq.gz
    ├── 4e9165b015d1d2aebbbdb58f4653afd0d2714110.nq.gz
    ├── 4f24b7fc882bda121f91f1d4cca9ff4a3c1f841e.nq.gz
    ├── 5049fdc69934a883d8813c0fd962a183b3d6b982.nq.gz
    ├── 50c30d65c813fd22ea7f9a340adcabb7f0c08662.nq.gz
    ├── 51163ee4d468672fe70b169e46081d7804f30e85.nq.gz
    ├── 5165312379b453b576cfef27c38908f5037f5835.nq.gz
    ├── 51ff6a31cfd98f1c29c3e315530352b96ecf2cb4.nq.gz
    ├── 5201c4e056c162b00c7bdc137f511b8914b61e99.nq.gz
    ├── 52498878ea623bc95445c5783d0ec3574fc16b3a.nq.gz
    ├── 529100e29f755c7749b6ff8af5a7bd9a0643e419.nq.gz
    ├── 52aeefba1a435332221bb12f6ff24c02aa8bbd75.nq.gz
    ├── 52e4e61140d1226f5ba80676d1973baa298d3b23.nq.gz
    ├── 533a16c5ff9aa2a2f7e3b019f37bda6120acf179.nq.gz
    ├── 53469d001c0c10f19777d1294d9e9312c84a2775.nq.gz
    ├── 53f41e91158f61604aa104a3d8c8eafd3068f40e.nq.gz
    ├── 549c35d22967e0c9f75bfdedd3f9094432acc803.nq.gz
    ├── 54eae2702c7a5c7e02525f914984fe0a20bb0b01.nq.gz
    ├── 55539eeaff9b2443f73cb334eb20810eb84c78d7.nq.gz
    ├── 555811c0710081fde5c2ed423da0b37e50db4f27.nq.gz
    ├── 5586083fb504fc47c94dabdec7b543a3e437be4d.nq.gz
    ├── 569e3a890c907f9d5688398e2e2c40dcceffa3a5.nq.gz
    ├── 5771af3917aa9388f81e3f315e966d8083b8e0cf.nq.gz
    ├── 584d3138697bd8a43aa8884a7a369399ddd2e7c2.nq.gz
    ├── 5956f7f3f71ac9396117e4bcfb8c7d155f6283ea.nq.gz
    ├── 595ad41cf14cc95894c6b8025aefc1879f1e52c9.nq.gz
    ├── 59ecff1d027d3e0ec5e6571db565927f8db65bd7.nq.gz
    ├── 5a3876ac9c393f20acdb996df8680336bb7f6df2.nq.gz
    ├── 5aea1b1a0c7652860d4dde96c5c9ad82657c7d69.nq.gz
    ├── 5b136c1a976c9401a36690c2d7b758468ccd551d.nq.gz
    ├── 5c306416b63e658a3caf04008e68373cf758673f.nq.gz
    ├── 5c55237e7698e697fa9f103be55de3575d496829.nq.gz
    ├── 5cab903153627cacc42161353c657f6742d094ce.nq.gz
    ├── 5cee89b30388529002f2acd406bf4bc819195694.nq.gz
    ├── 5df8c076500b57cc3e83a34f543c6595f5bdc444.nq.gz
    ├── 5e2af0e0be604c9eadc6402f43adbd7557d83dbf.nq.gz
    ├── 5ea87d88927b8ddb7d5a6854d7089ac94af40983.nq.gz
    ├── 5ea9bd533a28a2117061a65fc40f9b561f9ac41c.nq.gz
    ├── 5f844627592c764116386fc56d9558e60d14b91e.nq.gz
    ├── 60f5a882a83c9d22e738c4b7d98dd4478e585dad.nq.gz
    ├── 60f6e54078578db6055f3446ac4774ab8ec0d3bc.nq.gz
    ├── 610e5d09124a9bec33228143b13c6f0bdf3a08d2.nq.gz
    ├── 614424b9ab50e20497f359fe84d562b2c94fc0f1.nq.gz
    ├── 6204f9e17e350be139ac94135adfc56508b26a0e.nq.gz
    ├── 6233b8639e675e7f39dfae6d82b670a8e756139c.nq.gz
    ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
    ├── 634c112eca7c0fc54883baabfebc9769d4db3838.nq.gz
    ├── 64158f5fe832771803f2374c132a8cee50c10ef4.nq.gz
    ├── 644e26eb9c0be93ea27061eb38a955664ba6d1d6.nq.gz
    ├── 64df5e8c98b54478107c5bd4690e0dd25b93b5cc.nq.gz
    ├── 64edc999dc986e3eee59710f3ece6c787d73c85d.nq.gz
    ├── 650fe0661ceb7a595cdad64aaf7c825d32a19590.nq.gz
    ├── 6536521afd77f6a2008c9dfb7e487d6a3ef15958.nq.gz
    ├── 65fc6f5c67fdfc57430d8979983728be6dc078eb.nq.gz
    ├── 660d7a63bfc81597677684c6f0044c4a9c349492.nq.gz
    ├── 667243a182cf9a15ee234e77d9985b58c37a4817.nq.gz
    ├── 66ba8b9142efe63efc28e050cf59e494cd50952c.nq.gz
    ├── 66f2a214b297bb4b2b82000ba9a15d184a05bfd8.nq.gz
    ├── 6700d7d1ccfb201a0528ebfcd507bfa161af410a.nq.gz
    ├── 6765bbdaf4d77b7184795655d18284de7bb7390c.nq.gz
    ├── 676bd76927d1f07fc3e37343663cd8bdd811d7ea.nq.gz
    ├── 67b905f4accedf7c53fda3c52c1f44f33eeb187e.nq.gz
    ├── 685795468b0f0ba0f3d8b8ab7bdd22909e3a1062.nq.gz
    ├── 69f0b6660f67ba2dfc5369abe997f338fe1b0b53.nq.gz
    ├── 6a32444c811485eec6f4e273dfbf838965b54617.nq.gz
    ├── 6a81713446929b2d5e1bfa21d273a0227c4c2490.nq.gz
    ├── 6afe9c9bf295bdd257a7be28d5d3e46598ba0e9f.nq.gz
    └── 6bef46a101be77fa6011ae6d32f1f0b3661292ef.nq.gz

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

[py-pdf/pypdf_table_extraction](https://github.com/py-pdf/pypdf_table_extraction)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
