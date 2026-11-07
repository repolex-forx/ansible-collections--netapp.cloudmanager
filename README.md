# Repolex Knowledge Graph of ansible-collections/netapp.cloudmanager

RDF knowledge graph data for [ansible-collections/netapp.cloudmanager](https://github.com/ansible-collections/netapp.cloudmanager), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/netapp.cloudmanager
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 250596d19eba4c5d90257c80a2eeb3f9b3072cb5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 250596d19eba4c5d90257c80a2eeb3f9b3072cb5
│           └── chunk-001.nq.gz
├── blob
│   ├── 01a001e9ac15ddfb7d3fdef427a4fa211295ad07.nq.gz
│   ├── 01fb9b9208121692ea3ed16a987818662c5eea69.nq.gz
│   ├── 026d62163061e2c0b820bfbb1eb4550bd250cc9e.nq.gz
│   ├── 02dd405202fa76f60b31fd2bc93991456ef960d1.nq.gz
│   ├── 0dd5745e7d4d3132e8100cd1098a4f855dc21014.nq.gz
│   ├── 0e9dd6390d8dce6c2d8f1ad5fcc8cb17697bbf8c.nq.gz
│   ├── 10384a2b276cf00b4facd8b368f206a87dbdf38b.nq.gz
│   ├── 15f75f2233ca7f4ce25ef16087bf8f6c1642808d.nq.gz
│   ├── 169c9049e650b96f7f21a452725d1bd0bda32205.nq.gz
│   ├── 16ea910ec3fb0e21ee2bce81d153f43a5259a910.nq.gz
│   ├── 17e1435ebce2111a00255b41dda8fd595f69e3cd.nq.gz
│   ├── 183a0e1496af9f48c2b246f1b2acc9961514e9fd.nq.gz
│   ├── 1ce27541ab1d9a9d11a341181298aec655bcec71.nq.gz
│   ├── 1cfac82a45b0c0f38e0f51d28ea3905c0e0c9782.nq.gz
│   ├── 22bfaa25aba04320efd445772ba0560fc574c159.nq.gz
│   ├── 287e843b19c58c95553ca4635685f84b5e6edc16.nq.gz
│   ├── 28e61171d1a63d0ad9732cf278d0ebc722ab5a15.nq.gz
│   ├── 299e13ecfb7146f87ca1ba2033346535e9c66f6b.nq.gz
│   ├── 2bb42546d0752ae451dc09c7ced8c6e84283f12b.nq.gz
│   ├── 2e37eb799c205db721c7d0508188d1ca85aa46b8.nq.gz
│   ├── 2e5aea7fd8fb1b3ce32fa2317d5ec8492632e697.nq.gz
│   ├── 2e7814624f0a019c7fe5be8e12fc364ae6d83132.nq.gz
│   ├── 2f028197597131d1f0f53743f9976a2d076f9e41.nq.gz
│   ├── 320552cb35fa54e927a22d681732e2c8b6bf37b2.nq.gz
│   ├── 3222dc7c52a579c8c9a76452feb1265157e6a52d.nq.gz
│   ├── 33295e409720b790da3ed5bb27a6d9bd392939f4.nq.gz
│   ├── 353e00e2da6dd3f0becc5ea5b6ab778c631e1964.nq.gz
│   ├── 37a93a291cba0c118f960084d5141998e7636c08.nq.gz
│   ├── 37cfe5d5728b25970fe4188d29709b6cc5078665.nq.gz
│   ├── 3a9207105d21515dfe958e53ade9564e9a8623be.nq.gz
│   ├── 3e5dd752227b047f11a867007d7f891b04f85934.nq.gz
│   ├── 42dfc1b9449f1a29664e5467ef81ed9b1e34f38c.nq.gz
│   ├── 4543db29229e9cf890c51b0cad4f4a2f07cf39e1.nq.gz
│   ├── 466fb8373afbaa5f0912540ad19836ed48666bf3.nq.gz
│   ├── 484081daa3e8cfd9ea02adaafe1b10e2ea9c4c33.nq.gz
│   ├── 494e17c3d6b885eb7291aa605099fe09d4610274.nq.gz
│   ├── 49e8e697e0c5e084e1fd006c3eddddf59bce31ac.nq.gz
│   ├── 4aeae19164616e7ac1dd9c6596cdd0891fd00a6e.nq.gz
│   ├── 51ee7719fc5b15d0e7d091822396c4dbedb4beb9.nq.gz
│   ├── 5320ef4cfb8d8671d227045f6eb9ca0a887b2df0.nq.gz
│   ├── 546ebfe7a23b08ef2004165106807568e999a9ce.nq.gz
│   ├── 58750c3aaaa566910c083da3437ea51220e9711c.nq.gz
│   ├── 5affedcdb24b34785de33b5dc2b2e221b7175458.nq.gz
│   ├── 5d9a08a85b2988ad8d5b58ec6cfaad87a2e208db.nq.gz
│   ├── 62c898c577f905061ef8257f6d1e4e32db816ea9.nq.gz
│   ├── 6336f1adc16012cac2ea7935e24d2428792f3469.nq.gz
│   ├── 6443fa3c9aeaf090d83ddb30f8f570673a26217e.nq.gz
│   ├── 6541cf7cf0727c4d67993100c4d2224c736da0a6.nq.gz
│   ├── 6b4b660a0627a7e4d86ac70d8e522d86796d52f0.nq.gz
│   ├── 6d63f830439c104fd3109ca0ba7e86ee954bf199.nq.gz
│   ├── 6e390396762f51a6449ddd63aa78f7376097eadd.nq.gz
│   ├── 6f1d30a32b52e62ee5533140a3f1cc65cf9fe39d.nq.gz
│   ├── 75058f80ce935791e05899612f79c1e8d58d9d0b.nq.gz
│   ├── 76807bb1ce0a02bff87eb0e960d269f3c1b53bdf.nq.gz
│   ├── 76f26a264e31ec235e4b1de73e5db5697e935779.nq.gz
│   ├── 8166ccf7ff9a44896706df045dc882747dafca8a.nq.gz
│   ├── 88c25079f8c22e6e94b393df7200d4e65682a7a1.nq.gz
│   ├── 89e10a81b77f2ba38e444e2b12dae8c3b0f8d8a5.nq.gz
│   ├── 8a76456de23d2602aa04491f0a9c198d49174566.nq.gz
│   ├── 8d5494695bde30205ab2311d87b19ad1774ca575.nq.gz
│   ├── 8e757b989e5533fb0567ab5f848d2b05479f3efa.nq.gz
│   ├── 8f970c8ee4ed56f2e43fdec5cb86a3a6d13733c8.nq.gz
│   ├── 912933ddee518b2ef1e70d71b3ef1cd0778da187.nq.gz
│   ├── 91960adfa592a5284d4beffeff3796ed9e78a228.nq.gz
│   ├── 91ee46370c74c93c7f297b9027f0cddc1e05f5af.nq.gz
│   ├── 929ad60dadf955bd21d391be6869542a42b8cdcc.nq.gz
│   ├── 934231d71f4eb9d5374a2ec2acf9fd6645a9bc6f.nq.gz
│   ├── 94a9ed024d3859793618152ea559a168bbcbb5e2.nq.gz
│   ├── 9533d5f91341611a28346a35e53625ba5601291b.nq.gz
│   ├── 97194540aff7efc214d3d69d0374ce504167da3b.nq.gz
│   ├── 9d11894899e86f3656f4c708b42e98ea8e817df8.nq.gz
│   ├── 9def7ad2cbaf46f6340d74c929a1217005f0efb1.nq.gz
│   ├── 9f9a98f5868da619cd64d05404f215d4b5fb02a7.nq.gz
│   ├── a4ffd6b1e9449f4c2c822394ad17c94c50922137.nq.gz
│   ├── aa73f205a7bee716cdbc55fd1acf1a2937c537c2.nq.gz
│   ├── ad211b139716c2e7d6e0eeac106767f918e6b33e.nq.gz
│   ├── adb0ea1cb84645cb8b396faac905aadb6146575a.nq.gz
│   ├── adb6c3d5184b01ca52ebe00aa4c29f4a53b7d71c.nq.gz
│   ├── af0b39ae9deed88e14deb36f9adc167b6fd406b4.nq.gz
│   ├── b08225316fcfb0f76a34331aa5864d5b0e8a674a.nq.gz
│   ├── b19e33b49cae11abf8a1514e98c555a299c4fff5.nq.gz
│   ├── b416774176160415a70d4bd155d778919219e8f7.nq.gz
│   ├── b4a1f59f7135b74c8032590c6e707028c1a290dd.nq.gz
│   ├── b4f9980611765d8ea06e418515e073dd36c6e50f.nq.gz
│   ├── b55a9bc0dad9955651885b632e551cc7c9d8b4fb.nq.gz
│   ├── b7d0e1bc9b2619e4be661c2e73f04c6290afcd7a.nq.gz
│   ├── b815ba7003abc5821cfc03acb34de3bd5f09e46a.nq.gz
│   ├── ba82e9e0d987be98f5aadbe5053315bc0f3643e6.nq.gz
│   ├── bdb3a1c8ba963cd6a3e2ead63bd465292f749308.nq.gz
│   ├── bea686f4c7c403ac9f69bb196e8341b5ab2fb45e.nq.gz
│   ├── c6dc8ce07649c9764e1cd89bae2464fc53ea2928.nq.gz
│   ├── c7a1c8a40716d44787129084d97af19fa53e856f.nq.gz
│   ├── ca13f3a6f5ba44a04aed15b34d75ec1c5591ab49.nq.gz
│   ├── ca5e328ebff3bfa636725c0c0228dcdd22c201ee.nq.gz
│   ├── cbc0dcaf05fa5e99d76928747ea681fc9f6a49e0.nq.gz
│   ├── cbdf64f134ebfdc71ac8a171cef24c87abd4048a.nq.gz
│   ├── ccd3e01c0218faa207ee1a6eb1fb2acc1960f21d.nq.gz
│   ├── cd8bf84a3d9a93377f6ae8ca26c44e8550c6e9da.nq.gz
│   ├── cee1e439cd13c6f248532a256eff3ef778bd1c74.nq.gz
│   ├── cfb6b42890b1502acd20f7b4d4430f225531f2c0.nq.gz
│   ├── d0ffb959e715b82c6152f5d33c6a14f038f28fd4.nq.gz
│   ├── d4a27011f265ee895efca9e5672f7d53ae88681a.nq.gz
│   ├── d6cbc19e010869a5312462ac43d95d513ebe9ca9.nq.gz
│   ├── d7cb99bc8803eab01ca742ec3901c141a81640d5.nq.gz
│   ├── d8345a0c9e19480143813eea3b015558e99a47a2.nq.gz
│   ├── d8c5c1005c4133eb2c652814f6757c0eadc82b61.nq.gz
│   ├── d986b09911ddee0a25a64fff8e0ff9935ce89111.nq.gz
│   ├── e05522215211516c25e573da02fe27494d74132b.nq.gz
│   ├── e1643c9754e66341f1b8e934b3548b3dd9df14ba.nq.gz
│   ├── e176f9574be8ba67aa9bdcd423502c7c07e2b727.nq.gz
│   ├── e36f3ffb68cd279e3dbcdec17b71c9ca2106ea36.nq.gz
│   ├── e3dc685d4efad746deebc90020a614e2e673d791.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8fb7cdbd79185006714ae357c857805a72bd443.nq.gz
│   ├── e9c67085db2766e594e40c6910880f90e996b69e.nq.gz
│   ├── ee352e74955110c4ea75ccda492baf6249f54f9f.nq.gz
│   ├── eebbe7fb88abc8eb9b146c20e75901cd8d8be54f.nq.gz
│   ├── efea39c22583dd8b48c0d8a8d537c8af7c6a9a81.nq.gz
│   ├── f06f7e78d6847fcf3f721d6769fc363f3fad111d.nq.gz
│   ├── f8bfbeb99b0146ced2cbc95e3f9f532d6e2b0e1d.nq.gz
│   ├── f8ca958f35a9ef372a38be4fc8a8d253bb266070.nq.gz
│   └── fda73b90fa39a1ce3ebce98018fb354c3b0df89b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 250596d19eba4c5d90257c80a2eeb3f9b3072cb5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 130 files
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

[ansible-collections/netapp.cloudmanager](https://github.com/ansible-collections/netapp.cloudmanager)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
