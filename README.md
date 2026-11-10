# Repolex Knowledge Graph of smithy-lang/smithy-typescript

RDF knowledge graph data for [smithy-lang/smithy-typescript](https://github.com/smithy-lang/smithy-typescript), parsed by [repolex](https://repolex.ai).

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
rlex download smithy-lang/smithy-typescript
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd1d44eb6b90c2cfde82946656d7a2019d1bd3fb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fd1d44eb6b90c2cfde82946656d7a2019d1bd3fb
│           └── chunk-001.nq.gz
└── blob
    ├── 00319a4bf3dca1fd6fb8e8e91febbc6ebcf50cc6.nq.gz
    ├── 0067c1f1a44f6b4abe8b6290da9605728e9e219d.nq.gz
    ├── 013547694e77180187c922a8c7fcd386a1b38ae4.nq.gz
    ├── 020df425ecb2743e58e95dd8d521dbc2c0576629.nq.gz
    ├── 025f1e1e3b50204e7414c836b287eaafe89ec4ad.nq.gz
    ├── 02dcd241ff8e93abcfbf67b69304bfaa544c85b4.nq.gz
    ├── 02de81a8a5e34eb3703b26bed2c766d503c90fd8.nq.gz
    ├── 041636e7e78830b52156de84b5cfe3b719d25e75.nq.gz
    ├── 04b75c4fef70ba8ca6be113d0d823d416d53c9f9.nq.gz
    ├── 04f3aff75bea99fef8bbfb185fe27ab7a77e6ca7.nq.gz
    ├── 05be9b67d8916ba7bf60c376bfaaeec749700d1b.nq.gz
    ├── 063a09d5fbf6b107d62ed276621addcd1ab9cb6e.nq.gz
    ├── 068ddf020ec0bf0d086fe85db83c19bb91315b80.nq.gz
    ├── 07b2c581f1f05ae4b0c1ca59e0dc7526b71214d9.nq.gz
    ├── 07d65e0838af2f048fa1ecf483b5def7d7edf3d9.nq.gz
    ├── 07fed9802b9a2223a97d6d109022330d0c7d25d9.nq.gz
    ├── 08114d5309b53ec5ee0b3724d816cc718a09b2cc.nq.gz
    ├── 08b9211318ce44d7bc914a6980de59fe7fb9d592.nq.gz
    ├── 08eb4403309c3e4a1037976ee0838292f8caaac3.nq.gz
    ├── 097dd5034ce639012df40a943dfb81bc9baf4696.nq.gz
    ├── 09c54efbab32933296e4f652feb04aec9364a024.nq.gz
    ├── 09fc3d2a945ca6d937030d7eaf2118abda16815a.nq.gz
    ├── 0a037cbe9d73a12ca9004dff01c83f6ce9d43ba0.nq.gz
    ├── 0a4174f80d23beef7a5b4dcf3fa4e55d68022600.nq.gz
    ├── 0abad43c0b80cbc5dcc37d0f7c7e0c8097d06a99.nq.gz
    ├── 0aed0ca96993d9077934cd119bfe352757733295.nq.gz
    ├── 0ba4109601d705c9c39a1969085b8a8e5047d693.nq.gz
    ├── 0c80ecc90e49e936e45e6d7a7f88ab4501435d30.nq.gz
    ├── 0cfe4c9577dc3f69d3bfa974c29c96cc64a8c9c9.nq.gz
    ├── 0e6d2f7632d7b9130b5b6950fb957ce2db102f6e.nq.gz
    ├── 0f0f6d2e07640258a36ebe49f092bf37dfb1fff3.nq.gz
    ├── 0f90edcaea45bd07f1fd042de11a07b418210c97.nq.gz
    ├── 10fd485141d0ca8226c94c56731c2d3443eda705.nq.gz
    ├── 1118422cfb9faf274bd60a42b00d4df03b69bcae.nq.gz
    ├── 136a2179abfd5e8e3d40e21b00e89b7dc63fd351.nq.gz
    ├── 1481ff60b5c18b2086dc8c5aa89232b647060c50.nq.gz
    ├── 14eed9b16906f89740e4feb133da164a40ca76b2.nq.gz
    ├── 15cd2412e53d6c46f2b409d9e9c4341cb5553501.nq.gz
    ├── 1621a7e86d4e18b59eb1920e87c321d45bf0bc3e.nq.gz
    ├── 16a90b2c22104c24727123df79264648d32bdbbb.nq.gz
    ├── 176c4b1cffdb6b0b5809151d50b6465d442d4329.nq.gz
    ├── 18055a931b48eba8ffd66adbcc36227b786d0237.nq.gz
    ├── 18476b99a10f6e96fa906a498fb37bc4ee187edd.nq.gz
    ├── 186e88a4af2411e512a1da429d64308c5afc23b0.nq.gz
    ├── 1a9cb5b768427fa08f8b432b6fc885cf6a6063f9.nq.gz
    ├── 1acbc9e8e4a67fb8e4111104d816679886ebd173.nq.gz
    ├── 1b43f7829f991da4aac08b1cf094362eba09e4b7.nq.gz
    ├── 1c2a0fb99f525986b65d9052147784e0098a2284.nq.gz
    ├── 1cd35ebc7d28ec6332ab01da59243d38c38e4526.nq.gz
    ├── 1f7f3be43989cac95f9b3823a9d3cd1618723356.nq.gz
    ├── 21771d2c7997c13d5567dd59991f67524af3840f.nq.gz
    ├── 226e7e12c6c89952cf79ea4d32bfd0000f7710c5.nq.gz
    ├── 22db7a551fe9936e97765b3ba22590a779dc9a93.nq.gz
    ├── 237a4754562bcb756ef775aca2d605dbe5f6b14a.nq.gz
    ├── 24cd34cddb8d0e764f22e15a57ae81aa0db305fe.nq.gz
    ├── 25409462dd47ef07b9298bc60336610405ff183d.nq.gz
    ├── 256a9313b6ed7ededb12c5cfd31564f053ea1807.nq.gz
    ├── 25b02c3ee718f8fc816cc3bc269fa26ae6037817.nq.gz
    ├── 262bdd5b251d56580176d396e78f0d48c986f5e0.nq.gz
    ├── 263a444f602a2518e4ed915ad3d0c247cda9428b.nq.gz
    ├── 296a7f69cab0892bd55f20f837bfdaa61782e22b.nq.gz
    ├── 29a5b7d807c78f9b543ea31f9cc39c30476fac07.nq.gz
    ├── 2a113b752133a4c84fdc472f0aaac65c3bfb8300.nq.gz
    ├── 2b828218dd99712ea5152eb8d962c4db964d913c.nq.gz
    ├── 2c05f1c0efbc587f6a92e059e7866ea76ee1d998.nq.gz
    ├── 2c9a136dd268d05e5d1b199df15ba515c44f1141.nq.gz
    ├── 2ce445d5a8bc97d80bb1496d80f7458c803347ef.nq.gz
    ├── 2d344afb61750383515e29389ebe28b28af3b980.nq.gz
    ├── 2d900414a01681f1068cec1aaea7eeee2a59f6de.nq.gz
    ├── 2dec22ad9f400cf699be16f493434b7e315493ee.nq.gz
    ├── 2ef82a24e081b0c90c873249842674d0fad804a0.nq.gz
    ├── 2f62c267614d47b3e8de93227762cb127e08e7cd.nq.gz
    ├── 305ea9455ed7229181055c64a5893a4cd10bd1d0.nq.gz
    ├── 30ef95954e44858ba4a88e109b8167d9f7f0bf59.nq.gz
    ├── 316d925d5388f89bcafd3e5935dcfc0abde9cd2b.nq.gz
    ├── 31c36848787fbdd1d77c66ffd47aac420c97f7b0.nq.gz
    ├── 31f8682ce70358a185df0c2369cfeb3374ea854b.nq.gz
    ├── 323edc769f2fd827d13a448ebf933565c33fb491.nq.gz
    ├── 331c1a632617956f7bd7d9704d0695e95c17740d.nq.gz
    ├── 33976721d4ed32195f8ab9c72ba2f8654ce99eee.nq.gz
    ├── 3418822a806718c4374e3d77deb1d4b0f042f520.nq.gz
    ├── 354618ed902406ac64321120349833747903a4df.nq.gz
    ├── 35f61c5a5458a92c10f4d539d12c35c591058cb5.nq.gz
    ├── 36b2566d0d0b4a0eecb3f8de42abf207973b7c72.nq.gz
    ├── 36d1b38bbab04471f7169fcf56e7105c6216f502.nq.gz
    ├── 37622da2aa26434ef864c95357852464e94ffe84.nq.gz
    ├── 37a7ab5be9165fd9f0cbf94384086cb10a028a40.nq.gz
    ├── 38663381216f7ca6bce9f832af908223e6917650.nq.gz
    ├── 396924cc7e4ea9c20fc4c1ed4ba31f61e0d5a495.nq.gz
    ├── 39db2072208a926f38568830bf353529bba01dc6.nq.gz
    ├── 3af9f9efed6d774392bbb08984a1fc09d7938de3.nq.gz
    ├── 3bc9a17ac77340dbfe9d52e6afcbc4835e30b414.nq.gz
    ├── 3c35276b804c9e477b322d01e43014ac3d2c7aee.nq.gz
    ├── 3c5b610ccffbeb14ac4a595583dcc0ceed8cad0b.nq.gz
    ├── 3cc4570de32792a1499af324299f80e1d210647f.nq.gz
    ├── 3d1714c9806efcfb0087bc6e9cfc379e579829e5.nq.gz
    ├── 3d202c62994ac3d2cf2fb8ccbab624ead9e436f1.nq.gz
    ├── 3e5d97d9d8470606d5a376dfdfb054bbda3a2a65.nq.gz
    ├── 40b3f7a553cc88760ac7be352d919358da1ccbef.nq.gz
    ├── 420a2e6f2eeece7a38d9a11891e2dc60fb82ff4e.nq.gz
    ├── 428b8fafa6dec36f618b20ebbe5601e8a8757bf5.nq.gz
    ├── 42a34e851faba223bf5143e13f75b2c08fd545a2.nq.gz
    ├── 42b4fdf10e3aaeb6f3df07a0a38ea02fabfa2106.nq.gz
    ├── 435d9f036f7c15194d9db5e670c100a2d9ebed4e.nq.gz
    ├── 43b304eebf597b371a098099b1ceb5ebaa11a1f9.nq.gz
    ├── 441e64feec6c9a588046a19bf7b9308d2dccc4a6.nq.gz
    ├── 447ba92d5bbb89aea1bca11fc074fb66da2f0360.nq.gz
    ├── 4481dcced5f9bbc05af9dc24b61a62debf388dee.nq.gz
    ├── 44a2577f45d914c53cb9a40630d0c56313c7d183.nq.gz
    ├── 45309ecffb31d48b10667f7122c7d77524b389da.nq.gz
    ├── 4561d693ea0b6cd0eee074a35256685a2319c8af.nq.gz
    ├── 46e51bd4c53b1517b80674e9a2be433691ce8b95.nq.gz
    ├── 4724535f96e7aad16fba0cd7c5da50217621cf44.nq.gz
    ├── 473084d9e49a3302d87d684e4a274b4ac24a5c84.nq.gz
    ├── 47c25b5fb51c57ba1c5d4825d926cb08548241f5.nq.gz
    ├── 47d1abfa9850146c18051375e2a8bfb8dbd05aa6.nq.gz
    ├── 48245003c2c6cc7feecf12ba33bc90af16105c8a.nq.gz
    ├── 48405d0daae8f581b97e88a26d603435e7ca05c6.nq.gz
    ├── 48d290c5a934424dd0669ee2b339c963abf35f18.nq.gz
    ├── 49052dccff161ac46fe8099bb6f2b09a6fb14912.nq.gz
    ├── 49286f9335accdf332c92525b56c8d0fe1634e0b.nq.gz
    ├── 493d39d9beda8fabc67691c72cb7a8b6de79b587.nq.gz
    ├── 49a4f710146ebb20be9c27df7e256eda9cd07316.nq.gz
    ├── 4b54bc5656c288291e146fde9ec4189a66c64939.nq.gz
    ├── 4b91e3b6eb64765373b58df29a77482dea0a3d0a.nq.gz
    ├── 4b97e8ca277fd926bc16354ecae4dc887ddcba3d.nq.gz
    ├── 4be3e2a776380a3682c9a6ddd3e4c1ddceddb5a3.nq.gz
    ├── 4c275a6375bcc8362ca5793f036e6f7d5c07867d.nq.gz
    ├── 4c686b6227f4e72f2e7dd1053927f95d06ac16d7.nq.gz
    ├── 4ce15a44faf99d5572bbe52cf7d0c3b7ce1b95be.nq.gz
    ├── 4da97d908971c18dfc5321effae77193f4a9ba69.nq.gz
    ├── 4dfb1bf0fd659fd851b045cfed56248205f741ea.nq.gz
    ├── 4e13b503dbb54f329ed22126b6c35961bd820ba6.nq.gz
    ├── 4e46707824a5839103e8f15338ec5a099b565d7d.nq.gz
    ├── 4e9581e3f4969d1c44269471012b421f40bce53b.nq.gz
    ├── 4f5706001167a608b41e3d28c7d0c4c1ae258d1b.nq.gz
    ├── 4f5982fbf8bd10ecdeed59b04ad06299aa5a7eb4.nq.gz
    ├── 4fce6aeb0a2eb612b13b199b0512309ab260499a.nq.gz
    ├── 50f2516e80be1803241ba37e67548c648bfbae3c.nq.gz
    ├── 51179f4ec3b80b4c5dcfb16c4e14e67b5f095c7c.nq.gz
    ├── 515ade55c69762149137ba4fd3d502638cdd61e9.nq.gz
    ├── 51c35e22669059de72ab8b370df47c2fa88638e4.nq.gz
    ├── 5211f70ae9a8935b18f4d985dde95c8792ff41bd.nq.gz
    ├── 524508edee54959ad07ba7503b8b6ab2af57152d.nq.gz
    ├── 5298b29fa4eb4871e30f46368c8ee01669b441a2.nq.gz
    ├── 539e70c527f02dc9797705284628f150b72a0b77.nq.gz
    ├── 53c50d3be62f38c9c8c50962f2371b8c89e91723.nq.gz
    ├── 53e1de4905aa19693a6d9287247ef5275249755c.nq.gz
    ├── 54187f6eaa69831406f8e4b072b8c83fbcc76979.nq.gz
    ├── 552b2995f1427056e3fc2465b00c74bce08313c3.nq.gz
    ├── 55c1da563c5d9429def6ee99af2cb6bcc7df03bf.nq.gz
    ├── 55d999b6a0d5fe99920d2fa4752ead4bb6e4f952.nq.gz
    ├── 55e2a7c158db2ea984c724bfc6c75fcf64e76d8a.nq.gz
    ├── 570cce545fffe58c1f6bec251221a80e0069701a.nq.gz
    ├── 5802db1ac64a8ac9f59fc9f034b868b5ce070d7a.nq.gz
    ├── 589324918163652dbbd94a84c8525ea168e25b83.nq.gz
    ├── 58d43b59940256aebbb05cd19e3da04074fb5421.nq.gz
    ├── 593d869e9bb5d50d6bdfb8adcc171b6578429f0b.nq.gz
    ├── 59626d1fbed2adda65c95da7f5c648c713c726fb.nq.gz
    ├── 59dd262b070d974e0ea347e0619186632dc8ae7f.nq.gz
    ├── 5a7ec9009629dbb8800620f7388b355804005848.nq.gz
    ├── 5a84d465364d714622fd06e1f0cdc5480c3c8ebd.nq.gz
    ├── 5aa2102e686e2d43861b114ec96d98c305f56724.nq.gz
    ├── 5b507247061b9cc5692c60876aee153cb6201c9c.nq.gz
    ├── 5b824382ff5df540d765149dc7328ae3b347fb83.nq.gz
    ├── 5c6defaab9b6e2e673579b0d415baf8c693ff33e.nq.gz
    ├── 5cccae901ae11a93bd8c894476ab917e37a94df3.nq.gz
    ├── 5d002e0f85a54f1ce5482f9e39f34dc56ae7e7e8.nq.gz
    ├── 5de3dc239249f579463571f46ed9f644d852ce3e.nq.gz
    ├── 5df6eb5e5cccd5fbd4edefa1538ae65c6d9f1a90.nq.gz
    ├── 5e7ecc5d8fa52eff4ca78c12e0f7288a14e977a0.nq.gz
    ├── 5f0342f47b722e812980c14f3e114707895ce6de.nq.gz
    ├── 5f8cf775927252f37552fe4728b2e5c942ca81a9.nq.gz
    ├── 61113d0a83b976a36eafd5aaefda98f58d168529.nq.gz
    ├── 61411e4ba0a3c52a9cb51066d31b8a8f56900b92.nq.gz
    ├── 615087259ddd5bdd75f9b22dc514261b5419ad12.nq.gz
    ├── 61799c0f4decdd9f3c46d3afe9a30c04628368f8.nq.gz
    ├── 61a778c553228df415291d5e7ce72d172ce8af11.nq.gz
    ├── 62248060bb177fcf9ee09334f16de59601534b13.nq.gz
    ├── 622fc6dba95272d12303f98d7c9e5f68c74fcd87.nq.gz
    ├── 62b0d67b7ad349b558eec3de15297f692fbdf8a8.nq.gz
    ├── 63616ad89bc539ad48d248b5036f517e8778caa0.nq.gz
    ├── 63deb0ef7b190d55c5549af70c90e4815e4b215e.nq.gz
    ├── 63e692397df77059aa5da7377d0260664c820975.nq.gz
    ├── 64215c5f68f018761eb991e5fd9301808a888123.nq.gz
    ├── 6453676dca631ddc4d62d622e26e0b8ac3b26db1.nq.gz
    ├── 66062b93abb7b61e133b7eaa723503685a6a0a28.nq.gz
    ├── 67064abe849854097fe305cbc023bc06891f0b16.nq.gz
    ├── 672ea47cb0549d226e6f6a299b7d113740dc506d.nq.gz
    ├── 67ff5becf32957234d7e8b436c4ef1f02d471614.nq.gz
    ├── 68bb14ad7fd9bac9b02d0b8a6cdf31c66daf45b5.nq.gz
    ├── 68d62be0fab611eb51519c972ff64c46eb460b54.nq.gz
    ├── 692ba3600dd4027a9efcc01e3951c146cdaba76d.nq.gz
    ├── 6949707030ee23c6cfcbbe401345cb5aa05a1d73.nq.gz
    ├── 695469be9b30d6f349a28ec5f8dd7020ce526d68.nq.gz
    ├── 6b064ded65a718831a5148e24097ddc55642d97c.nq.gz
    ├── 6b9aac5b09d1ba9c1a7f5ded5e57567693177b6b.nq.gz
    └── 6bb09d840300206faa7a97bcab83ef800f59cd26.nq.gz

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

[smithy-lang/smithy-typescript](https://github.com/smithy-lang/smithy-typescript)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
