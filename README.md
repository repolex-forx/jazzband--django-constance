# Repolex Knowledge Graph of jazzband/django-constance

RDF knowledge graph data for [jazzband/django-constance](https://github.com/jazzband/django-constance), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-constance
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d77bace84e73ccd747d87ef53f08e19609d484d9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d77bace84e73ccd747d87ef53f08e19609d484d9
│           └── chunk-001.nq.gz
├── blob
│   ├── 0525ebc77ffd984aa22c5f38ac16d859a1e5b38d.nq.gz
│   ├── 07a47565834d71ec09f962c8d291ff6ab9fd75cd.nq.gz
│   ├── 083932c6e256bd6ff810ee536465e727eb0091d0.nq.gz
│   ├── 0ac1999beec240d067e4e006b18d0d7f2fc81f08.nq.gz
│   ├── 0add4627431b37e743f20d82608b9c90f9d83da5.nq.gz
│   ├── 0c34dad4bc8bac23b3092d537cf3a2b7301ecb83.nq.gz
│   ├── 0ea7766351874cd125f11bbc8d5dfb6e0a2bae02.nq.gz
│   ├── 0ece168a80c0f733cf240478333673fea813824e.nq.gz
│   ├── 10ea0b7f1405bc6436a9281e7d4e011446eece9e.nq.gz
│   ├── 116a64f8e8e3db8d735d86975749500a9e56a77a.nq.gz
│   ├── 116e58e52e5da05ae357b5b54270d19764dd3015.nq.gz
│   ├── 13bdcb01a8beeef3245f318fadbc7d6f2cdf36a7.nq.gz
│   ├── 1ad203474bfa9cc9f31b624022a804c5851f37d7.nq.gz
│   ├── 1cea2558a4cbfba69950361052b23c62e020bf3a.nq.gz
│   ├── 1da42e83606b36fc8d3e799d240302b101b39f8c.nq.gz
│   ├── 1db0230899b58307b5936660fac594e196f16a95.nq.gz
│   ├── 1eaeb7d5092cee0e455657744ce87ba99dc6d669.nq.gz
│   ├── 215ede72ba0f0d9753c88e491cad61264e625ccc.nq.gz
│   ├── 2271795a753de280a74ba972817070dd869173f6.nq.gz
│   ├── 23ea485caf52b08e9edefe05b666b38de52c6f31.nq.gz
│   ├── 2549e71e4eb24676d634f3c42ce5fbcea3753023.nq.gz
│   ├── 2551233aaaaf0a6d0e4df620234664f1e1bd5124.nq.gz
│   ├── 26795000ed07e23075ed3ac4f38d66b833c64651.nq.gz
│   ├── 2a6ac9d1fdd95e0967a37eca06ae6ded5ff3b1bf.nq.gz
│   ├── 2f3b93610d47b2e66bdf688ad7473a05cdf3aa76.nq.gz
│   ├── 2f73cb13942a9ecf11014d188e13be78ed931a60.nq.gz
│   ├── 2fa88bcc94a859946315f80f88497d48e169a75e.nq.gz
│   ├── 32bb24529f92346af26219baed295b7488b77534.nq.gz
│   ├── 32bf7aa1297be010372e623371db1a3fb3713305.nq.gz
│   ├── 3a3da33d7b7ac191f2066a122648c9e30e5ff395.nq.gz
│   ├── 3b209714c8784676b00b5a2d741ed0fb6b3d3588.nq.gz
│   ├── 3cd6ddc0e7ccbe986a8c02037f151c27ce41f353.nq.gz
│   ├── 3f7e0f82263bca0af4871479407d2d08aa317c24.nq.gz
│   ├── 3f90697dc0071ca4d4cd222f9ce752eb26ceaff0.nq.gz
│   ├── 4208588504deba0ef553e24b8a5914a7cd608115.nq.gz
│   ├── 428f7a750fc8f06bcd16bc9a77e9dde310ba4683.nq.gz
│   ├── 43b2b886180b32733f8f85c7da12628b882c2fc0.nq.gz
│   ├── 44cc39ca7767ae38fe15b67d3afa35fb1bf3aab1.nq.gz
│   ├── 44fdbed41865491d743e003ffbb82c783572a031.nq.gz
│   ├── 461e188fa8867dd6654995f922d12ab4dcea7ec7.nq.gz
│   ├── 47348bb6dd6f7c4344bd405a60ea0b9d857cee02.nq.gz
│   ├── 4835fa1324cd07d2d073474d98e0dfc1abd9b876.nq.gz
│   ├── 48c306cf393f5dd755f19f51fac3b9fce1d7bfeb.nq.gz
│   ├── 4975b99c783a6054b2f0b437ca2a740a95aec7f6.nq.gz
│   ├── 4a55b35d2c8fbb6c97762f27ec96fd8005fc13c0.nq.gz
│   ├── 4c9010077e4c79177133f60f34ddbb80297eb5bb.nq.gz
│   ├── 4fcc9ec326f3024ea7d8a5519183bb2062c3b8b6.nq.gz
│   ├── 515fd488d0a6839103b7fd3b74a7bdbd221c0f9d.nq.gz
│   ├── 51fb54f8d7c5d43b06cc661960dec157eb88497c.nq.gz
│   ├── 531426c2514bbabadd0e313f95d2388fd8e162bc.nq.gz
│   ├── 53d94a13120a637c803aeb568c4e0825222f2bfd.nq.gz
│   ├── 53fc6d13e80dda98adcb2f2af45551c0ee072559.nq.gz
│   ├── 55a6b6c0d3f0518ed8970c636f6fecf3139d9928.nq.gz
│   ├── 59dfa18525f5fc609127be973da013f553da094c.nq.gz
│   ├── 5b240aabf6ef304f221dcfe6941bc7a277d659a4.nq.gz
│   ├── 5b6f98e111fb262bdae4600e3dff950667e20932.nq.gz
│   ├── 5bb98fb1e3d82ec24fb8806d6d0232475c3111a6.nq.gz
│   ├── 5f9dffa8ce2a3acab7562ebfa33f20f15954519e.nq.gz
│   ├── 64a79ad012d4bc7c5d6d84b365443e8259a1a7d1.nq.gz
│   ├── 651ec8386c484152a38e86d838dac79850013074.nq.gz
│   ├── 67e7674455d1598375d8bef0cb59e97dc8f443f6.nq.gz
│   ├── 69e0fe949f79ddb73ea3b5ce3152952aba7454f0.nq.gz
│   ├── 6c5906d1cd061dff54de8b533942893de34efc9e.nq.gz
│   ├── 6dbcb8ac6f02e46b75e65cc26fb6cce64bff0cd1.nq.gz
│   ├── 6f3e6630f12aea9befe9286da0f1fdd480508096.nq.gz
│   ├── 6ffc7b0823570ccb3758c58be62348fceceadcf0.nq.gz
│   ├── 705ab1ee780c5bb1616399f985cc542a11f31a5f.nq.gz
│   ├── 723bec9e5ef497746631cb4ad6715db20e40a69c.nq.gz
│   ├── 74ea9eeb5725deb6951e1ce2e17b5f495a5b20a2.nq.gz
│   ├── 779300cba502e125e2271f93c9f77e2caea18b39.nq.gz
│   ├── 77e378fcaf4452c329de03fd8a54e8fed7e3a98c.nq.gz
│   ├── 7804a6256fe919222a59c018ed94eefe29a359e1.nq.gz
│   ├── 79af6d08d7d0ad408e75cc68422a0c1d20689e16.nq.gz
│   ├── 7cb2bc1c934a89129ad73a092318fd36a26f16ad.nq.gz
│   ├── 8ea5536735fd68b616ae246d68530e7119980431.nq.gz
│   ├── 905a71c11aa2fca247eb76619d56f254cafabb94.nq.gz
│   ├── 9328c5222dedafa14ef5cfcb89c6d1a3e24877b8.nq.gz
│   ├── 96a17c445de0f1e97cd3df94af0f005c8562db5f.nq.gz
│   ├── 97e5d971ccbc32ba309be0c486e0104f595291a3.nq.gz
│   ├── 9c029236bffb87e74c6e68c231562a7b235fef1a.nq.gz
│   ├── 9c8d3588dd7e062ef3f7add9e683bea85cd98ed4.nq.gz
│   ├── 9ca09a97f8d8e4046eeb561f6695e2fa007f2489.nq.gz
│   ├── 9cc7030b37cd8a4064f5c502dbcd837db0fe27d7.nq.gz
│   ├── a0d65980fd11bcbf397dc61f6225c159ad5c8c52.nq.gz
│   ├── a3b3e5274122e3604686408c9978cf0dd977538e.nq.gz
│   ├── a8df5eabb14b8ce3b6012bc7dc77d9a2b10dc33e.nq.gz
│   ├── a9d29b21dd3db3ea25e95918e75d484a2625a89b.nq.gz
│   ├── a9f2fd0412042830bae6c8f543d677b72a6c3905.nq.gz
│   ├── afe1640b624fd2fae1eee904157c7bfc9ee298fd.nq.gz
│   ├── b09d964f5b1edb852f7fc7f70651520db89f93e1.nq.gz
│   ├── b218533f700ee39a816a86c87ce720a8b1141398.nq.gz
│   ├── b61d237c70743466efacefefd4bb0ae4780e15d0.nq.gz
│   ├── b6b4b2c3ea27bb17f3628cbf23993bb142fc7649.nq.gz
│   ├── b6bb58343f4b13c08c47b74ec4ebe19fddaff6b3.nq.gz
│   ├── b751b826520612766b85105f02e20b35557da5fe.nq.gz
│   ├── b75c9e3b70cfdaf9c44acc826e8dd02602f175c5.nq.gz
│   ├── bc6cfab3199d40037a16df39fd752e26bbdad516.nq.gz
│   ├── bced38c02ff37923aa0e7430322774be3503b927.nq.gz
│   ├── bd1b2e558f531d37898e65aefcd303a9c769b118.nq.gz
│   ├── be4ffc4d67df4274f61858cd3dd3681c3af44c95.nq.gz
│   ├── c46f2eb8284ce18d0924272b29e283b232d171e7.nq.gz
│   ├── c6c36b7b2ee8faa374a51e092bf355d666e7a2e2.nq.gz
│   ├── ccfdf80b0e8b7ffa235143d31587404a45795eba.nq.gz
│   ├── d250c66d246732a83cdf75cee155105b0a23942f.nq.gz
│   ├── d414bc3f7bfedb4eeee7efa215a43997ef71ba97.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d621d3ba2f0c185c8d187fd528d1bb0a803d377a.nq.gz
│   ├── e3a45c4f4d227a1ca5269d61c4462c807558c97b.nq.gz
│   ├── e495a804b76d3913c2a93cbf96aa0f0b87ff03c1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee7bed80cdf9a2a3daee9352a02e4cba04249e53.nq.gz
│   ├── f4aee7880d1006db0ca009c4b354cf92109e2f51.nq.gz
│   ├── f645fbce1c933883e4ff6a389931717d42add468.nq.gz
│   └── f975613ed8bb03f5bfc82b306355b335b6e1e154.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d77bace84e73ccd747d87ef53f08e19609d484d9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 122 files
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

[jazzband/django-constance](https://github.com/jazzband/django-constance)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
