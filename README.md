# Repolex Knowledge Graph of rogpeppe/go-internal

RDF knowledge graph data for [rogpeppe/go-internal](https://github.com/rogpeppe/go-internal), parsed by [repolex](https://repolex.ai).

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
rlex download rogpeppe/go-internal
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 38c169d642f5e6ee08f0c90fe56b64c5ae2db19e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 38c169d642f5e6ee08f0c90fe56b64c5ae2db19e
│           └── chunk-001.nq.gz
└── blob
    ├── 010959f9f7a1413ae52fb7921899e78785af94a8.nq.gz
    ├── 0275ef7116d4e3ca4807724adecbc6c90da4e0a3.nq.gz
    ├── 027a8adac448859c84a9a353853b6717000e5967.nq.gz
    ├── 02aebad157b8d588aa0c7256f45139c03b658dde.nq.gz
    ├── 03fd8f4c71052ccff6d9e862e6b3ba3c0032810a.nq.gz
    ├── 047705e6865baa7c5da06905cdc63a314ffee885.nq.gz
    ├── 05612d64ad405ff80fc7b3a605ff78714d5c72bf.nq.gz
    ├── 057aa3c4e680d48baed2c8f617e20a62da01ba99.nq.gz
    ├── 05d9689ebda624de78563af839a8de73c3662280.nq.gz
    ├── 05f27c321a8ac977b9eb1297344eedcfa316b652.nq.gz
    ├── 06f2ce3cabca14b6783ed0cf6c1a20a417598fcb.nq.gz
    ├── 089d3827456a99ec374a894c7e5252d0abedfbaf.nq.gz
    ├── 0b3975cd19cf6cb422ae990725c336407aa5f387.nq.gz
    ├── 0d04f269d65071e5e4150c4d2eb3dd145aab6874.nq.gz
    ├── 112dabef144680a36fffa7eb5ad5aea2730a1430.nq.gz
    ├── 11c037ae4ceec3917a4c6b54f1c96e06085dacb8.nq.gz
    ├── 11f70dbb6819d325a41eaecd9c15d3a10305b072.nq.gz
    ├── 121132f6f7326b90cc12c6078995d159afb1dca8.nq.gz
    ├── 1484058fa74d6a525fb0ee159089ef3b216c7733.nq.gz
    ├── 158637c135b4d1f2957c121a5537b654fb699aa5.nq.gz
    ├── 15b33773cf5f5b065a3b1931d3d8ea7f5446f680.nq.gz
    ├── 172e056b3b4f591157ace8e1fbcaf4dcbc28fef0.nq.gz
    ├── 1748cafef3598a89bf839b8de4be51ae1a8502f1.nq.gz
    ├── 180a36c62016ba045f1829680e91182ac6d716a7.nq.gz
    ├── 1839218b5b256087ac152458dad5e1e3826cce95.nq.gz
    ├── 199d9c6e388a324397b1418afd49f7a5f884d16d.nq.gz
    ├── 1ad9596c61f4250b2a3a3353998f0fc7b4ef2bc9.nq.gz
    ├── 1de030b75c99ac714bc8960f4af11f753a3ca69d.nq.gz
    ├── 1ebf621e92163dea027edd404c36f4b02d36e226.nq.gz
    ├── 1ec2a47abb4e2cd91278149915aa84d5f9eff82f.nq.gz
    ├── 1fb0cfbf5094483e449f60083c21a2bb8ab2ab0e.nq.gz
    ├── 217b2fdc9f8db877dda17b5d15ad3e408424ad12.nq.gz
    ├── 21efffbff72bcc5b65bf5adace1f998afdf41486.nq.gz
    ├── 253bce1aae134a77c26c7da853ca1a6ff66467c6.nq.gz
    ├── 25a880ad007211c68f172b38ca7399625f5740e9.nq.gz
    ├── 26226d49e7241eb8128f5828aa192fb0b294d326.nq.gz
    ├── 289c00390eff0b6791b61d260d15dbe5dbb6b52f.nq.gz
    ├── 2920bbd664ef673224f0fabeaf28e22d185b67c3.nq.gz
    ├── 2a59f2167bf74ac6ee9d9f5fa943ba227dbe211d.nq.gz
    ├── 32b1d8f3f2d64ae5a3209a4d73ede56584cb6dd5.nq.gz
    ├── 396a8bafc24da25dda02507ad06508740e8634fe.nq.gz
    ├── 3ba71c99aa990efe60c2cfda3ed19899a8bdbcaa.nq.gz
    ├── 3c9a541f06da9a3c538327a673f70d9dd2efa86c.nq.gz
    ├── 3ed2d9fe01e1ac533c2df45db46245e32db81d51.nq.gz
    ├── 3fc99f71d518658ceafecc66807edbb03e2bed72.nq.gz
    ├── 3ff0c1f3f9c83d55998e407b99ce26205b1084ce.nq.gz
    ├── 4248e681ec55bdf94c9c7bd3194b06bd5fea04e7.nq.gz
    ├── 429969c3cbdefcc620850a740797f8bed8d316b3.nq.gz
    ├── 43b8e0e3c7c034d2acb7291b5b4928ea92a54913.nq.gz
    ├── 454c3a42c4017734e2406c9397c4b86dc44d438f.nq.gz
    ├── 457be905d8db5588aaf690b0ea54714928e93f32.nq.gz
    ├── 4802b139518e3e24bc7a428168707028540daea6.nq.gz
    ├── 49ea0f928825ac4339299665088d332ac9953476.nq.gz
    ├── 4a2dfc0c73393fa86acf948a486ed2db50c19cd6.nq.gz
    ├── 4b407d17950c1d22fd86d9ff682af6beeeca92b5.nq.gz
    ├── 4e0018f3877905ae1a82acfae4fd2e70173845ec.nq.gz
    ├── 4ef092e9567732192759f486a414491f93e88c73.nq.gz
    ├── 4f038373e140f6e687c02ac8d9c91ca8d749f80d.nq.gz
    ├── 4f3a388b35c35677dadc316855319b5820554342.nq.gz
    ├── 4f7fa76dc7e11b6d5cfcf3ebb1823ffa097814de.nq.gz
    ├── 4f81acb9b01bc210104844282aa45361f628bfcf.nq.gz
    ├── 4fcd69368a47291dedd69c420dc71be8a5117d53.nq.gz
    ├── 519f8a7be76250a10129d9169043b35eaef34f75.nq.gz
    ├── 51d8e7e1cfd3a65dd861cedde36881f52516aa81.nq.gz
    ├── 529723ab9875b4ba31a8e56c494784be87cbc477.nq.gz
    ├── 53a83d0c80cfc9110a8fe26ae13630fd65c14d3f.nq.gz
    ├── 55209809a2db72950d6d0ec2b9f9dacdff57207a.nq.gz
    ├── 577c626905d0b788456623acaf36cec6da31b6c7.nq.gz
    ├── 5838d32c44c7f1b1097227be7f17c6eca48ecfbf.nq.gz
    ├── 593ccd012145e5ecfe8ca22e6a589e43e8377398.nq.gz
    ├── 59a4ce42463239cb310dcbf6fef5d09cb3303e31.nq.gz
    ├── 5a3b4d6790eaafc87bbedb153a94f86ff811fa8a.nq.gz
    ├── 5beb54a721c3cbd6bdac9c7500a49aca795df008.nq.gz
    ├── 5dc145c4de47cd5db313f550e9f00ee237b7a243.nq.gz
    ├── 5f7a13aec36b747583cb6e5e20dc1f26e2693140.nq.gz
    ├── 61a30b95f4dce6100453167f7e157762b53482da.nq.gz
    ├── 61e63d22e55fa05f5d70d6ba9c83675c9b79c8b6.nq.gz
    ├── 62518915fe175893773923383d51bee0bfd63408.nq.gz
    ├── 63c508248fbff9ce6e7ca9defb380209943cbaf7.nq.gz
    ├── 64f97e7568569b5e0c371e864bad45cd9bbb3383.nq.gz
    ├── 69c13675081ceb886ac17936350bfcfc52584246.nq.gz
    ├── 6a4cc7f6ee1c21435af23aa1896e8940138a5c33.nq.gz
    ├── 6ea356f1ff05acbd8aee3e9de9b5564cb1537dd3.nq.gz
    ├── 7243a4665d249fe723a8b5245080673794d46dd2.nq.gz
    ├── 73efff8698531b5d7550327808c45d2a8794a845.nq.gz
    ├── 7426a29c1a6efca44692bdfb313b23560cae64f6.nq.gz
    ├── 755d796736dd8435628efa9ae3826a13637932df.nq.gz
    ├── 75c7812fc90c94bd030640896e21aff73b9de9e8.nq.gz
    ├── 764c27b2ae9c13bde6c36596fb8b1f8a5fbd48a2.nq.gz
    ├── 7832159cca6d70c407e0a8b69c462a40d9b1de8d.nq.gz
    ├── 78977be35614155100ec8aec3cfe1b8a1b437a8e.nq.gz
    ├── 78de04c3ddf2b5e8d21056c7a83df3a200f2552f.nq.gz
    ├── 78f6211496ee9a5faaeb90bfe06c371b2df51561.nq.gz
    ├── 79645bc299cb231774acca17ca35741981d2e480.nq.gz
    ├── 7b1b03790734fc0366bcabb404af8d75d9e2afad.nq.gz
    ├── 7bdd62bd9b439e6ceef26274bda8befaf053532f.nq.gz
    ├── 7c6ad8fb7e064b4fcf99fd55fd753bb639251b31.nq.gz
    ├── 7e6983b8cfc94845f8a49076477b8a8f1b2703df.nq.gz
    ├── 7eba3a126106b031c95a54a54a234446d3682a2a.nq.gz
    ├── 808ebe0b222923e9dec4c4ec9f79f3665665964f.nq.gz
    ├── 82e1a89675e7042aab6429990491e0e6f4ab6219.nq.gz
    ├── 855dd5a3eedd63e6b9e1abda0e231c90bbe54824.nq.gz
    ├── 8568048507860055c8c6a71260bc8a3fca407cb3.nq.gz
    ├── 8693c9d4adf87c3d5a8587fcbcca59593d3b0fa5.nq.gz
    ├── 86b1100d81031167711b3db8bc255ce34a28a048.nq.gz
    ├── 883ad167687cd860c3e4051c1f40ce0af5cbe315.nq.gz
    ├── 887564927ab233e8be93263cd2b4d35a46d9757e.nq.gz
    ├── 8aaf0cf792ef386da06680cf5ffb7731119b774b.nq.gz
    ├── 8bb4a3fc5bedc7571b7f295d7c5421ba6ac92333.nq.gz
    ├── 8dade61ff6cd82e058d0f073fceae0eacddb3a9a.nq.gz
    ├── 8e9626fcb199444a6994909eb98d914de6d16210.nq.gz
    ├── 8f1022b4398204a507bd5ce9e978bb91ff1759d4.nq.gz
    ├── 9169cf53d6ad09b2efa14ce4531b6093f0553921.nq.gz
    ├── 94928330afc1863e0390c99c2ee6abc09d65d73d.nq.gz
    ├── 961de4ef07872445e7489d53f4b0eb4548436b3b.nq.gz
    ├── 9760eb9230ecbec7cb9a09f0b290c197bd83e35a.nq.gz
    ├── 98e4e38f4aa3c0276e11e441fefe503068302456.nq.gz
    ├── 98f9191053bc3d970c7ef2c6f881e48e4f858ebc.nq.gz
    ├── 99e57ea833085716e5af2d2e757c1bb445a32610.nq.gz
    ├── 99fd8ebc2fff18afa6764b3e8c2a0fd26caa9241.nq.gz
    ├── 9a1a732ca9c46559d4b4edf394d9ce1174a2aca5.nq.gz
    ├── 9bd8bd7818e042c79c96b5690b66df08b0f7df52.nq.gz
    ├── 9e61cedb8f9f6e943c049a36eaa5fa885c07b45e.nq.gz
    ├── a0571b71d358eb297daa8acb77d4f3fa5ff8d371.nq.gz
    ├── a05e78574ee454a9998530a7d21b4faa72258ca7.nq.gz
    ├── a09a3d3caf25969408f4b40f78d96c3f6608ac5e.nq.gz
    ├── a0c3fdd21b5f5cc2ce45bb9dc0272e7123f61b18.nq.gz
    ├── a20b33cdf8c8f8e638f41fddaa5cd6b3481687e4.nq.gz
    ├── a2ce794b967521af86975f9fe86f280ac0bc0dd0.nq.gz
    ├── a4db433e6ec6a3e43aaacff5c6cf6582a367ef54.nq.gz
    ├── a55b86caf2661419d4fdbc44547477d19b1bb69c.nq.gz
    ├── a84692c7858d765f6c5698b3ab1b48cffbe77dab.nq.gz
    ├── a8edafb3c3b5aec036e4f34ede3532ad8e57f373.nq.gz
    ├── aa23111e6ea509f15a642c98088b666723e624d3.nq.gz
    ├── ab5759fcb2c7d6ab6622c6d9c2ff17ce46bf3162.nq.gz
    ├── ad55780155c0c897c963a6d7bb379d3bc8e3cec3.nq.gz
    ├── adaa229c6d241baf49489bc7ec31945e332f20d1.nq.gz
    ├── b138e658a930bdd859cc089f5bf7c524ae80aba8.nq.gz
    ├── b1b5720f079e5fffe52dd9634b4bd91afa66e132.nq.gz
    ├── b1b7b039a3c7bce04e14aa95ed36944761060448.nq.gz
    ├── b4070fd1979782f60b539558684e6db22d176349.nq.gz
    ├── b64d058d13eba498145f2b5a1dc0d1f807a128ec.nq.gz
    ├── b8fd4c6d52486b6a3494870f513c259c92ce22e4.nq.gz
    ├── bb34022e7ba58beb06b5736a2fb255c6ceadc776.nq.gz
    ├── bc79f6cd3d3b63701e08f1d58de8e6f79b541676.nq.gz
    ├── bcac6a50b65b9e75aed3e548d858876fc1e0dcd5.nq.gz
    ├── bcc9ac0ee05be68d394b452c58aad626383969a6.nq.gz
    ├── bd49d7408c97e8f08ca6412ac5d2347b3a5b6ce0.nq.gz
    ├── be49a2c8f0000b5f657ab30a84bcbc8e424f2f8c.nq.gz
    ├── bff1a660fd74db1ae19941053bec23277d224f1d.nq.gz
    ├── c05cecf0e974dd355ec428f7e403564d1da96336.nq.gz
    ├── c0ff0eaeb28ff6e3dc7faccdb8ed542a4df3dc19.nq.gz
    ├── c1d420873abf1cc490bfbde7c10a008d20fa5d4e.nq.gz
    ├── c21bca937938895d61b9e61a62e98ea517c22e5d.nq.gz
    ├── c31248cffd7de44d7b99e1bdec2d22a504eeff96.nq.gz
    ├── c33389bfb47fa2bf2ebea1a7ef495d225895a118.nq.gz
    ├── c4f0553ae716daa7223491d3569d7dc957104607.nq.gz
    ├── c56e36ca62412aae46a98f41f5a2d9ad5191fe8e.nq.gz
    ├── c8a1f4ad0ad5e8cf630a9d38f72ce28f1c1ed2fb.nq.gz
    ├── c8fc2976729ad89383eff48634c496e6bba5dd25.nq.gz
    ├── c94b3848a0e163a4d4220f0f39e00a390cd38c23.nq.gz
    ├── c99ee41fce9852f1a0249ce93179bd0e3e2e5094.nq.gz
    ├── ca03070d0560a27f224bc43b389a3e65935d926a.nq.gz
    ├── cc818696b6fdc72c577bfacf528259700c7357a4.nq.gz
    ├── cd113abe4bd54029e7d1e656f6be164f10be5f3a.nq.gz
    ├── ce1515b211cf89ef90b1c87b7a9f76687837ff18.nq.gz
    ├── ceab65b02ac17c1a90ffee24e38845b9c3d2912f.nq.gz
    ├── d0a070b43bc7cf50bd929c1c96908d5b747f6d24.nq.gz
    ├── d10524d0d81529948ce53059e4416e18d33704c1.nq.gz
    ├── d233a1f5b26da39370238d00ccc4f4084854d3f9.nq.gz
    ├── d2565b5d6ed3be271035cb4b28388e4e686609c8.nq.gz
    ├── d38aaf467783fe918e443e599f4d609981e7e14d.nq.gz
    ├── d69ce5ad9463f92d8fd0af841f726371fac24448.nq.gz
    ├── d7778d05de1884f88bcbdbbc13e30a26c86d43ba.nq.gz
    ├── d80ee7c9497ce72be680dd90e00eef6840bc94a0.nq.gz
    ├── d9b7da9e4b48671e91e004a6e994be809ef8fa7c.nq.gz
    ├── da713ca2da5f25d397b6bd6f949ef6a2fe6060c7.nq.gz
    ├── da9a46e4face362eb5d95872bccc2ecd4a7a5424.nq.gz
    ├── daf9930fd02abdb45783a5851c9e2ec3439427c2.nq.gz
    ├── dbed355348c41aa033e99cafa37a3ca1ec9cab56.nq.gz
    ├── dc7d34c11ef43cc076b5fd954943e81544b0cbdb.nq.gz
    ├── dd08b628b4bff6b11099669d45d81140e3859624.nq.gz
    ├── dd22770b36cbbea8ba199f7412d38e39b310125d.nq.gz
    ├── dfd92ab05f83fd5f867ec70980e94b116d833cb0.nq.gz
    ├── e1c02784c4e67a363baa6d9958c9d1064ae2c191.nq.gz
    ├── e1c15bd130d11763e60e62553998bf42c01b077d.nq.gz
    ├── e1cca27461ab1c6b68ebe20bd50a5dd04f2266dd.nq.gz
    ├── e2e74e13315b91deb74a2c34f106b43724c9b7cc.nq.gz
    ├── e3701bbc20b28ea217cd441ea506bd93c5c35221.nq.gz
    ├── e4a2d46b5a40f4929c5d68d83d5bd5c7d1817398.nq.gz
    ├── e4e01dcb8693570f47f0e591c8c8c3f2a6a1b63c.nq.gz
    ├── e5320ffea43f020d0d1b08c4e563a08e43f64bfd.nq.gz
    ├── e7d7ab58982962bd65cdd2bec193b6c00792a078.nq.gz
    ├── e9e0791f449b8e91011228ca73f9fc3619a4157f.nq.gz
    ├── eaaea979e9dc82285ab0f830cbc676295d0732d1.nq.gz
    ├── eaf5a1e911725f691363d6f34ff458ed8b65019e.nq.gz
    ├── eba11aab6e4ea13897934e523789c9abbad5bc05.nq.gz
    └── ee15b0089ca1003ef59f051b534057b49ca82e6c.nq.gz

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

[rogpeppe/go-internal](https://github.com/rogpeppe/go-internal)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
