# Repolex Knowledge Graph of bytecodealliance/rustix

RDF knowledge graph data for [bytecodealliance/rustix](https://github.com/bytecodealliance/rustix), parsed by [repolex](https://repolex.ai).

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
rlex download bytecodealliance/rustix
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c4caf5caaa7e93828a2e4a4cdba1dd0171e45717
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── c4caf5caaa7e93828a2e4a4cdba1dd0171e45717.nq.gz
│   └── repolex
│       └── c4caf5caaa7e93828a2e4a4cdba1dd0171e45717
│           └── chunk-001.nq.gz
└── blob
    ├── 000ec8baf67cb379196d22ea9b8041f6df7fd489.nq.gz
    ├── 0051b068851a3ccd025c96bb8c43fd195f256a7c.nq.gz
    ├── 027ad09e3d798463017d474026b8cf2410ce70c2.nq.gz
    ├── 028dc697de5520e89f948573160c926066f38bff.nq.gz
    ├── 02d6287aac44e992ab85548d5eb3a90c542d3713.nq.gz
    ├── 02f389497a1e8d287f374a061f4d0a2c39e6b3ca.nq.gz
    ├── 0343e18c3a9b2aa416a8efd13dd49ab2c4409c97.nq.gz
    ├── 034b026187c383a749c66638a476331f06c329cd.nq.gz
    ├── 03d753d1dea35b37fa651a44fb844c39dac5e362.nq.gz
    ├── 05394f55d5b7649d6ee4327b91b1899190ef549f.nq.gz
    ├── 065251b70013e27a112e3a00ccbf9fb7bbe4b1c4.nq.gz
    ├── 073b6b12045067cc16394f20b76c29173d13bd81.nq.gz
    ├── 07c3a3d959a56489beeac13bd09be11b3d6c9fc0.nq.gz
    ├── 08f04646c014233f3096301cf10c7ce9e343dda4.nq.gz
    ├── 08f4bacc9bbfdd2903f587d5abf513e93e3793a5.nq.gz
    ├── 093129dbb6a4954bf4ae2c16af953df7a7fc8abe.nq.gz
    ├── 0955f7683b1679f8b39daf723ed5c0870259c415.nq.gz
    ├── 0989430d9671a2844e5623ba3a814b7b6705bcb0.nq.gz
    ├── 099ffe1b8ec8f93c0a02fbd6e5f3db40ee3cc342.nq.gz
    ├── 0a0e1d16c787ae696085e84ca61950130508c4ba.nq.gz
    ├── 0a26c534c3cd25747497893039f55db6aec2f477.nq.gz
    ├── 0a8541461d1fb44b7171a49d502dd4e9b5f6c079.nq.gz
    ├── 0ad4db5eb63803cefc572aa281e34e2ee7c02681.nq.gz
    ├── 0b48649ce4bbe9131fe7956bff3ede6d5f725d57.nq.gz
    ├── 0c900921e163cd7f08d536ab3806b0eccfb805f9.nq.gz
    ├── 0dbdb945e4135d9a30f043dafe06cd94bfdfa41d.nq.gz
    ├── 0e004f3d2565b16eb54af9cbaf3ef1c4bab7d85f.nq.gz
    ├── 0e0969103291ae920e96f6e68a927bf05a332c70.nq.gz
    ├── 0e8a7b36fb2e4e95825cead2e96edb500da4a988.nq.gz
    ├── 0f87ea459acb8ea53e2306fe6307402505e4fc62.nq.gz
    ├── 0f953d7f767738e219481e3385236da6f2e82afa.nq.gz
    ├── 0ff960f730b6562f8ed332a69a00bb010fe12de4.nq.gz
    ├── 105749ed946f6d49aac035ca660900efb95ac61a.nq.gz
    ├── 11c0576078cc224c0860dd06609172627b929c06.nq.gz
    ├── 11edb19b30c1b94ec1c992cdf95bac6a818fd3cb.nq.gz
    ├── 124ca51af742a4b945cceaffdf108e278b81447b.nq.gz
    ├── 126f9155ef2282ba484639134cf1e6c3b952c684.nq.gz
    ├── 128d3b59a5301bea982ca90becf80566d2d9e039.nq.gz
    ├── 12da57eccbfcf54f75b826a7a733b9949d998a3c.nq.gz
    ├── 12fa450e8ca7875789a2f628ec5e5219aa72ee86.nq.gz
    ├── 13b502a3474cb8ca892b1d3b9994270aa7905667.nq.gz
    ├── 13e5c24ff0fbbfcc5eca36c6f0aa2534a3ea384d.nq.gz
    ├── 1410d512871620d1bc6b8cad3ddca0d9250bfa93.nq.gz
    ├── 166275627d3d6d7dd4ff8d7821948068a8ff2af1.nq.gz
    ├── 1677ece453350cc628aa19315fe0e44488aebb47.nq.gz
    ├── 169954f23992520031e7fb12cacb25fecb4528f3.nq.gz
    ├── 1699ffa991a55da3d3575b16da7ab8dea7b58296.nq.gz
    ├── 16bd550a6f7fb62e871e292be0fa7a32ec281449.nq.gz
    ├── 16e0dda125c6302c318abcf511d6f44ffde4d67d.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 1736d9da85e1d07d615702716d1207984b6735da.nq.gz
    ├── 17b280959900d47fc24ab32a22819449ddf7cb3f.nq.gz
    ├── 18da4ebb593b0b3ba21e418f83e42ef487d77e73.nq.gz
    ├── 19510cf991da02a51a0188500ed8189f1b8f1dba.nq.gz
    ├── 195898ecdff9b37f669c25ea45c2c8eefebc0bd5.nq.gz
    ├── 1be215e0fb4a850a136db7d1c8a994ed4eb0e634.nq.gz
    ├── 1c7bdb46a56b8f96b0e182e578390c216442d0c6.nq.gz
    ├── 1cb1fc93a0d7daee56090ee3edeef7816cf60d40.nq.gz
    ├── 1d1a4852d9d8eaa761a7ec1cc69bf52568674211.nq.gz
    ├── 1d2e74b37b2adb71466e9f0896dd016f406eb1a0.nq.gz
    ├── 1e00030c19d12d59b70ab9263aa6c8ac20c5534c.nq.gz
    ├── 1e0181a991f8618df72ecc81ca3c9e173176ce5b.nq.gz
    ├── 1fc2ef81f840e1a73b62900588139824a3b01da6.nq.gz
    ├── 201362625162f97317a44252df26d30a0b7ec394.nq.gz
    ├── 22945566ae97a72c5f876f17bcb78997c11c977b.nq.gz
    ├── 234d90339509b6cccddb1c8ab73f0ad60e67f01e.nq.gz
    ├── 234e9933a3568716a226d5206b730354085d1788.nq.gz
    ├── 24d55302754602f095107069f3f301bf2d04e68d.nq.gz
    ├── 265a3c17435bf7ef1f611e03e1255f4ae9875d4e.nq.gz
    ├── 267c99d511f67f3eea07d3ad30d365d1e11485f6.nq.gz
    ├── 26d1de427158e1e4899b4c712c09a62cf93c2798.nq.gz
    ├── 276a775f7199ef35f3cec7f75104f97583574938.nq.gz
    ├── 284ba2f1010185f6fdf518e273b1b17369bca8c5.nq.gz
    ├── 28bc94eb049121de4f4efd7bc2d3643d90d741d6.nq.gz
    ├── 29227f969162ee84abda30e5d1eb20cd6fa5ba34.nq.gz
    ├── 29dfc22722eb1b94c51575a8552f6bb85455727c.nq.gz
    ├── 2a3cf56488150d4fa81a3d0c433fd1b1d3e3589b.nq.gz
    ├── 2c02b5bd7e448ad1ebf33a34cc5e3058da3aa1ea.nq.gz
    ├── 2cb2fe78a4ff11f1d603c8f3c05b7b6d9a42a32a.nq.gz
    ├── 2da16128667ba1aa48840c40eadad28cbe490c5a.nq.gz
    ├── 2dc32c5f3766b7c21090745e807e83908fb22da9.nq.gz
    ├── 2e502fdb378797887f3a588d1588ab0b7fe8d481.nq.gz
    ├── 2e9a228fac6798f90bc865f1a8b472b0e2d64a98.nq.gz
    ├── 2fd0fcb0da0b424fa196afbb7cfd4ab11456b3a1.nq.gz
    ├── 30473b7083424d5bfc510f4baa44c9a20cf7e472.nq.gz
    ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
    ├── 3238b3a3275a3dd5a825b0f2922f916a197154ef.nq.gz
    ├── 3262d01f6c45c2b956c29293f201c2038a44acb7.nq.gz
    ├── 32ff0288e8e31cec4bd5a9df8fecd3e8fbb35090.nq.gz
    ├── 3328a5febfbfe43a9b4f43d498f1cfbfdd21b01e.nq.gz
    ├── 338f4548e0d4adbac72eabef4d54af5f966c94cb.nq.gz
    ├── 33bc9cac17c27058d3ae31fdf48c537fba7a5f1b.nq.gz
    ├── 33bf07cf5ef5b2996b76904fca5e0e83d2840879.nq.gz
    ├── 3513b9cb35734dd840996b5cded145e51c94ede0.nq.gz
    ├── 355137732ca868d58d97832f2dfb57aed6423af3.nq.gz
    ├── 356e85cad223d0246a61e4a3cbc70154316ffb36.nq.gz
    ├── 3584c5b39f8613d10c980d138f1be16d9ff1f711.nq.gz
    ├── 365f0160430a09e6cacddb77f9ce6f0c594248fe.nq.gz
    ├── 36edd4c0c0f6a84f86003928ad33d5cad4452568.nq.gz
    ├── 370f2468fb8f79ec4e4b941b4bd21950bd43b5ab.nq.gz
    ├── 3827a2f99bdfdb384491345e00c4310108a5df82.nq.gz
    ├── 39aecb8f798d4edac2077453c315a348193f24f1.nq.gz
    ├── 3b348221a2635d8586c8b9ac5768152b90061dcd.nq.gz
    ├── 3c133d3807f3887d5d3889334fa123b7db57d1ec.nq.gz
    ├── 3c4c3896b0ee18637632f629bbe97cac1c59e19b.nq.gz
    ├── 3c67f2c339222032d02510b34a018407a5223ea0.nq.gz
    ├── 3d0711811d11f9cfb45389473c8560a084fabfb8.nq.gz
    ├── 3d4693fe1a8d1715bc54851324283feb575b0a73.nq.gz
    ├── 3d5e963d700f80f83cc0e558a09394eae0cc3259.nq.gz
    ├── 3ded514ff856fabfa60b4e5d550a9a17923cb542.nq.gz
    ├── 3e553b30d81b41b9bb9d3ce69e555c2ed03df6e5.nq.gz
    ├── 3fbb55e8815fd750e30c791fa75e7e03e0f9aa58.nq.gz
    ├── 40476bd12e85549053d6d17b274a84b19ebbb60f.nq.gz
    ├── 4066da31c9e08b0c1ded43737933711486c2fa2e.nq.gz
    ├── 411030119cbcbe06e12ae5e018015076a9c916e4.nq.gz
    ├── 42ad21177fb49cc9cc51cb7be7954d7ad4b3e957.nq.gz
    ├── 4303be925cdcf0048fe38baea53cc51bc8c3f0d8.nq.gz
    ├── 4317154fc7509296dc389b1b71edab7382686cc7.nq.gz
    ├── 451cecc29f19dddf9bb563ac21a37d4fd321f272.nq.gz
    ├── 46690b57f8f0856bd0a48947ce43ed256343e774.nq.gz
    ├── 46ab07ebd593071a73ea91491af6d5dd8944b340.nq.gz
    ├── 46cde2f8732b11ad50c4e831ecadddd720d9d3c7.nq.gz
    ├── 4771ddafa88f93acc8c229744cc2e61a97f7ddbc.nq.gz
    ├── 4873885760d442d1af2bd58342a4084113c7f39f.nq.gz
    ├── 488e08f02428f0896fd2f986e61435779dbae6cd.nq.gz
    ├── 49a5f854d32fa8cd720a324775549847f91c4e8c.nq.gz
    ├── 49aaf43e6819bdb4c420570949c5d0e3ef4633c2.nq.gz
    ├── 4a30bdc86122bb8a8abb9d47f92d799a24857390.nq.gz
    ├── 4aac5f24a585f1d3fb35d3cc2dddb1e90a217d29.nq.gz
    ├── 4ab910e868cbd5afdd8e041cf7f86d9f630823d1.nq.gz
    ├── 4b0d29f5bf8634c49d4b8cf9b40c878cf37e49b1.nq.gz
    ├── 4b14be38a020b5e12df6cb798c0ddd868afdf16b.nq.gz
    ├── 4b67f2c5b0399f3efd50e6d2a3bc4504aed28163.nq.gz
    ├── 4ddf6df5fac9694a673f0df640d1767b62e783bc.nq.gz
    ├── 4f9e52aff997a40eae0696863392af11a05d48c2.nq.gz
    ├── 4fa1d1ccfc87f6fc3dccec47986bd42693744018.nq.gz
    ├── 527f5fe9499d3f5445d7f0010abbe1e6048efbab.nq.gz
    ├── 533f97325902939273b7db536a6cbd0df8744f5c.nq.gz
    ├── 5362504ff2fb6e5a8da730bdf5d61556a15a62a7.nq.gz
    ├── 537059492351e2d7e855bfcfb821594f5160e68c.nq.gz
    ├── 54872f52aa3027d6898363720d299cff2f0c0edb.nq.gz
    ├── 548b74ed2304979798777d577761321812ebf4f1.nq.gz
    ├── 560dfc13630b750c2f2e8a98395427a342b3d282.nq.gz
    ├── 57a8d2697df66a4f21bb392e9f94592a7a26f27b.nq.gz
    ├── 57f52f0f8f427b8e429cfa68e9098d5c52e8f0f7.nq.gz
    ├── 581dcc97a01b912bf1cfda8fe30c91b920e38203.nq.gz
    ├── 58a969d158758ad009df166c3618d2df608aec0f.nq.gz
    ├── 58b8cc14557317dbbcdc7f0a2f5a634961373f9e.nq.gz
    ├── 59f19b38f38076ab4b23d6d082d2949d59620f31.nq.gz
    ├── 5b6e2f813d107010ab5b44ce29399ef4b5f9fd40.nq.gz
    ├── 5c8622fa309e32f9ffb67fa87168d5d6a835fb14.nq.gz
    ├── 5d6e14f17aae6908d2e3ba153d857a9eb5794444.nq.gz
    ├── 5dbd7cbb8c6d416a7a35fc5581963e5d054febc2.nq.gz
    ├── 5e5530a39795706b9dc13d45b03e468d407f3649.nq.gz
    ├── 5e836a9ab7d7034d95aad3126edf869564fae2bc.nq.gz
    ├── 5e93c352d0f922c39436e9f25fa469b577531ac5.nq.gz
    ├── 5eeff953f4c1431cbe3c98972728693fdd1cd124.nq.gz
    ├── 5f8c48ec7d6adf36c4227e8f9742929bfa56086d.nq.gz
    ├── 605de25388cc79f3f2386292648b221d3337b820.nq.gz
    ├── 6096e76d2b548b36dcb8dc0d8ce34a8dfdb216c8.nq.gz
    ├── 61cd3f47d55b4043ae033bac0482e47afe887038.nq.gz
    ├── 627716d858fedf4cc28a1f4390d4df92c6b606e7.nq.gz
    ├── 6366d7cc1a68019bbf172a71f42218d6fd25531b.nq.gz
    ├── 638782f049cc8a684886bb12ea71b8442c3d37fa.nq.gz
    ├── 63edf7f6d848887aa689276438549da6361f0faf.nq.gz
    ├── 6642fee656b70aa580b414c7b7820dcd79e8baea.nq.gz
    ├── 67f41f5b3fd0ea40f18bde96a6f2af7ecbb743e1.nq.gz
    ├── 68b7d2be89d5740734c626ad1e77ab3ee81d285e.nq.gz
    ├── 68ea140a64f6b31b65a418a8df177b258db3b66f.nq.gz
    ├── 69af9a3d4056313c78876c94b82254f585a32ac4.nq.gz
    ├── 6a27845ceaa617c1bf3b0ca9ecb9cc46cc73a0db.nq.gz
    ├── 6a4152038271f990db38523f839c4b7b82e465f2.nq.gz
    ├── 6b43883241fb7b7ab13205b8c91a75210b32e73e.nq.gz
    ├── 6b4992ad2c40a899810ec947e10d5b9f7e517f5c.nq.gz
    ├── 6b64b730d466e760ea54a705b55441b32f049721.nq.gz
    ├── 6b6ea955570a949ab066ee9ecfd226c3d2e20dff.nq.gz
    ├── 6bb93b5386862339c636d52adb127481a1eb0425.nq.gz
    ├── 6bc9443d77fd92e086bf13f7071b562837115445.nq.gz
    ├── 6c6c96d7f8d235d46789e2efa9856c5f0c96b789.nq.gz
    ├── 6c86a8f2acac273c9ab79d46a76210ce6e7a137e.nq.gz
    ├── 6ca74d4d034f537879ece0489095c1bbd59a651f.nq.gz
    ├── 6d105c089811ed152fc0a7f9c01e588111990dbc.nq.gz
    ├── 6d437f5949ee34f21bc5b1dcb9cb3b9184926808.nq.gz
    ├── 6dbbdaf7e3a8fb4db8ab3b527097548a8f79ff4e.nq.gz
    ├── 6e49771f0f3e1ae692fc15372784e11925a25d77.nq.gz
    ├── 6ec816be173c4d0f8948c6839d436eeefeeb13c5.nq.gz
    ├── 6f3d21a6812aad57679040a8ca456a80a2b2a17c.nq.gz
    ├── 6f4fb3f537d154768878020bbbb7fc2897956066.nq.gz
    ├── 6f7d24f5abc4a1b1604911a154eea8c76888892d.nq.gz
    ├── 6fc69240a32f1f6e8b73e1406bc8d7689853d5f5.nq.gz
    ├── 70204aef8bf873335b34a2be5e8183ed9c74d823.nq.gz
    ├── 706bcb8cb206c0cc868dcc6779ca4d49df8317c4.nq.gz
    ├── 70c690530908c45a2f2295ed2c1e77b3be16c887.nq.gz
    ├── 7138b57133e34500d9ee43626ab4dee7ab8ae97a.nq.gz
    ├── 71b0bb785978a78a809a2a3402e86ccd6fce2733.nq.gz
    ├── 71bc8b0abf3f7e406fe8f052637ed70ae1c765a4.nq.gz
    └── 7220295b683bb9adf35f6d2f42b63d0ab5e2b0fd.nq.gz

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

[bytecodealliance/rustix](https://github.com/bytecodealliance/rustix)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
