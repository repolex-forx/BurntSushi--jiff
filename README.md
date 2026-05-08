# Repolex Knowledge Graph of BurntSushi/jiff

RDF knowledge graph data for [BurntSushi/jiff](https://github.com/BurntSushi/jiff), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download BurntSushi/jiff
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 939549520e6004b051b02c8b5f74973b833f3670
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 939549520e6004b051b02c8b5f74973b833f3670.nq.gz
│   └── repolex
│       └── 939549520e6004b051b02c8b5f74973b833f3670
│           └── chunk-001.nq.gz
└── blob
    ├── 01b9451daf6bf518584fc18797a884a646f6aeeb.nq.gz
    ├── 020e886b57d517925b24e06cc8675281389ab697.nq.gz
    ├── 028061da3bbcbc70958f4e1d2d58f68e5be14f30.nq.gz
    ├── 02a020f3fba84fac609ad3139be33358a0e5b58f.nq.gz
    ├── 03a5c9ad22e984a9cf567907f8da0e7917d2c7be.nq.gz
    ├── 0507afc9cab9e1fa9cb906393358f849ab1f68f5.nq.gz
    ├── 059fd2bb463d7bd2585c4e5dbe590b56f658f13b.nq.gz
    ├── 05e1f57b07351bd3e8679931b4a4b58e557008c3.nq.gz
    ├── 083a3c858a85a3e74cd905d98c50f87714efcb16.nq.gz
    ├── 0c732f7612cd7471cbbef7366f478bc64df12f7b.nq.gz
    ├── 0ced5c48c3da568c1fd29efc32879e022a8ab4c0.nq.gz
    ├── 103ad6df3a59fba3bdbcc93f64de0f8a88ef7e57.nq.gz
    ├── 110aecb780ce8b19c6fa0886182c523eae9d7537.nq.gz
    ├── 1273a7328cc4e1786437b331c27e2cbfa9f3c084.nq.gz
    ├── 159f41b93ba7e9b6e9646be3f73f9f244e146a68.nq.gz
    ├── 16811b58e861671743a09d9dc4aa059f2ecc21c1.nq.gz
    ├── 171f27e3fc6e90a8c5841bb07c60482a27757d77.nq.gz
    ├── 17285ea3b7edf7394addea17651b143cc1a24787.nq.gz
    ├── 17e957e0ff2e065cf22482511864d5967f4a086e.nq.gz
    ├── 187895f1334ac96d7cf21fe70d991b75f08068c7.nq.gz
    ├── 192cdd6885df66a4e627bf31b4c6a5c1d9547586.nq.gz
    ├── 1c24bc887ebe03942de5bd0fff52fad0c5d2667f.nq.gz
    ├── 1c83d6751e7003630851d54437f4787276be3973.nq.gz
    ├── 1c8c618ddef5b12fedb90f850325db918bede7b6.nq.gz
    ├── 1ce90b4e244859a99b577466f6ea36bc474a0998.nq.gz
    ├── 1f2319f59fc58b6527c18d878125988d6d4829a2.nq.gz
    ├── 1f29b7bd1a1f3f4fd3254790889914c10ea902ab.nq.gz
    ├── 20119d62cbef0f5aa6f7874935954f98b100ab6b.nq.gz
    ├── 20e80f30ed7b41a0bdc3c70f0cc9e35fbde06e66.nq.gz
    ├── 21bda6619a71292c34a56628e7d4728bf7163d8b.nq.gz
    ├── 2331bec86b3ba3d1468a96ec0612344e8c7dbfba.nq.gz
    ├── 2345a56ff8dfb06ad9f117d3360bb9106ce57d8e.nq.gz
    ├── 23978d23c31b9bd2d65c166abf25ec0a58b0b8e1.nq.gz
    ├── 23cc9b4b50249bc1b523a06961175f57baec53ee.nq.gz
    ├── 258bf3972b66f5b4c8df4aeb58caae5585aae421.nq.gz
    ├── 259e92c6e22a01d26100a949b7535cdcaa087ecb.nq.gz
    ├── 269413971cf033a502abfee0056d1c54a065f1bd.nq.gz
    ├── 27e30d889f8ce241979b8b08e88fe28adba0ed80.nq.gz
    ├── 2869fec98f72fbe4b7ea36d5128ee1650cb34370.nq.gz
    ├── 2935da58219fb78e0bd7e46a0b0ba2aa04ce6613.nq.gz
    ├── 2a03ca6e861eeccee38487948c27b933e4da36f8.nq.gz
    ├── 2b283c167388d71ec76b5bd483a8f9464c41424c.nq.gz
    ├── 2c393ddb574155e64600e3862df1993ecd1beb60.nq.gz
    ├── 2dfe72e813a6792c71572c411b38ddeaa071b465.nq.gz
    ├── 2e063f0f7ff2ee489e03a728c20c4f5954dc35fa.nq.gz
    ├── 2f8c76ed94505727e090fff9e6dd7af935373379.nq.gz
    ├── 30e8ceeb466e99cb58375e0d44d02d75008b4b74.nq.gz
    ├── 31e9ac5dbded8ffacf2a16183e84549671513c72.nq.gz
    ├── 31f7061371910ad42e4310b7a646ba1a98b6cba4.nq.gz
    ├── 3306274b4ece706c508d32c826b1ea1af84bcf63.nq.gz
    ├── 33744679321e36e2f5392e74fab47a83050498d2.nq.gz
    ├── 35931d8a5fb99c43fdd3575143937461c32b39d3.nq.gz
    ├── 35c0089024b2060391ac7295e21c1873f8223e43.nq.gz
    ├── 35e9553302af000a9294744e87fb303f348318f2.nq.gz
    ├── 365092c34d08ac99993cab68d108820e75c06237.nq.gz
    ├── 36597e271e55b0602e41432de8b57eb2cc7d49cf.nq.gz
    ├── 378d1b68303aed820a4f58d6fb11cb784241c7a4.nq.gz
    ├── 3796cbf936ce2d961b61de05eee36cdd78e51810.nq.gz
    ├── 391679d29e4a6a53e5bdf63b9b03d0a32827209e.nq.gz
    ├── 3a6240e76b4156784ac5e114084237776124da09.nq.gz
    ├── 3a6347020c8d756d5d8f25bd5c314c64922e3323.nq.gz
    ├── 3a6534cfcb93d0ff5988bf98c872eebc4040ec74.nq.gz
    ├── 3adb8e1bf7c6ec51f1c100538799271d7d7a6e6f.nq.gz
    ├── 3b0a5dc09c1e16357459ddc9182a50f360f3cdba.nq.gz
    ├── 3d63946f5ae16a8f79fed54b3ed3cfd91d69c1ce.nq.gz
    ├── 3da0be3aeda45b2de70b2419bbafbe95fad45fe7.nq.gz
    ├── 40919a1effe4ee28900d990224ebff11041ad503.nq.gz
    ├── 414a69d681e783c57317e1fb4d4485a00e7ab100.nq.gz
    ├── 41b639e7cea146a9b9052eaf982909368953a94a.nq.gz
    ├── 41bf25bc5bd69ae63450deb03a2a84ab36d67823.nq.gz
    ├── 442ff3317f042b5635494ea5e648500b4e2654b7.nq.gz
    ├── 4464f7e42129dd30d30335c8949087b3321c1071.nq.gz
    ├── 4515fd37a8c424b55c819de4a990d1a4ccda7f3f.nq.gz
    ├── 468793d02553ce30408bc43aa234cf70bfaf617d.nq.gz
    ├── 47987314659260328b67ccd730f7b27340f184c4.nq.gz
    ├── 488785dbcdd810f4dcd230d327f608366eb499b5.nq.gz
    ├── 4a61aa8b18ff4074d0421b0ed468108ec6f03648.nq.gz
    ├── 4aa9c82af62c48af4d8418e6092a8e033092cdbd.nq.gz
    ├── 4da2274b33acd20b2596ed63a927fe73d6eb1e3e.nq.gz
    ├── 4e3a06c42ab4c7b30d969941547f148145c1fcd7.nq.gz
    ├── 4e783872e837d7abb7b8dedc8aa6b9648145f4ee.nq.gz
    ├── 5103bd9c48ca2e57f07f1b8e8fadd9fd7a51b4e9.nq.gz
    ├── 51ecb0b73f452d00509b173a9a33179c69eaa1c8.nq.gz
    ├── 52b0358832a6986c2c4139f9562b44b985afb401.nq.gz
    ├── 52c157ce2cd90b4c5f208032f3c346694e4135cc.nq.gz
    ├── 5475aadef69b9caf471eb3582e636bd9a381849c.nq.gz
    ├── 558ae6fa60d5aeae35b43d7233b2bde7e2b943e5.nq.gz
    ├── 55f5f98ec543e69cac853c4b4cbc101faa074cb9.nq.gz
    ├── 56c8ce5a28420927314630ea30e56b4e54b909b7.nq.gz
    ├── 57b36eee20d9edbc2e8ef368078e2c5a309d2d55.nq.gz
    ├── 5d9d84a05c6a8fbc398653e6acfbbb2f335a9616.nq.gz
    ├── 6189db46c98d25e43a9b3a36062406fe06b35a14.nq.gz
    ├── 6219e7dc2f3ed965dbb41f5ceba922e89c24dcec.nq.gz
    ├── 62d3c25c8c5fd776ded502ac6b641676c1cffe5d.nq.gz
    ├── 6478d0edb7d8d88e7b4a7cd50a9b536892ca620f.nq.gz
    ├── 64f38af3a49ed4dbb9aa9049f0481b54b083144a.nq.gz
    ├── 65a5b0c720dad151ffdcba3dbe91c8bd638845c6.nq.gz
    ├── 6777934d72da9159b27b2e91c7b05b01179c524e.nq.gz
    ├── 68a49daad8ff7e35068f2b7a97d643aab440eaec.nq.gz
    ├── 6a1cc28a208e242bd7ca5cf2d5df7eccc7d15e5a.nq.gz
    ├── 6a21b7acf0d31f28a12800eb26be9bc6b04a839f.nq.gz
    ├── 6b5a51d7faba23e72df3d93715aea4a969dc799a.nq.gz
    ├── 6dc38451ab2de3546989d96c0ce865bc383ea357.nq.gz
    ├── 6ebfe073a3a86dbfa24e2d80e543387647ac0b2d.nq.gz
    ├── 73cbb2215997e6987100e1ca3bb1ed43d68868e4.nq.gz
    ├── 758272d3d9cf98a9eccf0b8c619c07b5b1e0ee8b.nq.gz
    ├── 761f0aeff6bc92ffda3b5617a22fea00c2ea3ce4.nq.gz
    ├── 771a3ae029b1c425be1b9282423cda77d3744fd0.nq.gz
    ├── 787a3d529615924f68123130ca76d334367c5851.nq.gz
    ├── 7896538303bd368e15f38f9b34f5fb8c94e3f443.nq.gz
    ├── 78ec5fd32d5597a5726f859a8b9fbea01c28c773.nq.gz
    ├── 7aba387b49cd5cf08dd6959e18c92813c9e94161.nq.gz
    ├── 7b0256a0746814e6b2e59c3cdcd49246f75afba0.nq.gz
    ├── 7b7dfa42fbbca348e47e8c15f9ad2a91419646c6.nq.gz
    ├── 7cd1e6661d13776168ba9cdfdd798311d80ca551.nq.gz
    ├── 7e504184b01bc96976d181d14a8704ece2f71b55.nq.gz
    ├── 7e876c9d3cb429caa79b3e529a1e3337aab74638.nq.gz
    ├── 7e8c6ace2105fedb851327e6e39bb4463b362644.nq.gz
    ├── 7f21189a6c4cd471bd65720e9a3904966245986e.nq.gz
    ├── 816ecb932398e11469d8aebd5a10b85bbc77300c.nq.gz
    ├── 83a35fe341d800566faf268781ae4142973b94ea.nq.gz
    ├── 8434689fb6f0acb11bb58ff8b7e54a07a485a233.nq.gz
    ├── 845b103f5dc102ebfdeec064a9a11ccb28f49054.nq.gz
    ├── 84c12572f69c79e7844fdfec0f34ef998303fd26.nq.gz
    ├── 86cf9d04630d306e9032105dca46277401aef86b.nq.gz
    ├── 8718a4a3c52d91a9dd76cbac4db8d7add862151d.nq.gz
    ├── 87af4a49a738843bb58f36cce3b4868a01740697.nq.gz
    ├── 88462058d715c63bb59d144ac0d7f4be1f7fca47.nq.gz
    ├── 88ab55e9478349be8994ccb29703eea9f2ca2c87.nq.gz
    ├── 890076475fb085db17c87d68e64730e8de63371b.nq.gz
    ├── 891f4d4012e9bb86923bf26e558707a32a823863.nq.gz
    ├── 8b3d46a57d754e80973b0f6a1a6995b1e8f5acd3.nq.gz
    ├── 8b41d54603167e4c0d3fbfa876abe37dc1dd576e.nq.gz
    ├── 8b5878daa761c8d263e8c257ae07f0af3743bcbf.nq.gz
    ├── 8ba5b42f35eb21af99f127e375bf4ef04909db48.nq.gz
    ├── 8d0a89b096bf2744a7fefa084424ada7734edd1f.nq.gz
    ├── 8df890d5a0d11fd9ed5c6b2f97f9b979ad2149eb.nq.gz
    ├── 8fd9253d3a5b797a5e5a37282505758e371b8f08.nq.gz
    ├── 8fec9350756642e93469e6d228ce67cc4a4e108f.nq.gz
    ├── 8ffa20d607ee52258addc496950503a9cd482264.nq.gz
    ├── 91558be0c2bf903b2364215ba26d5227d6126508.nq.gz
    ├── 9247c1d004634c11d8a080d319f40806286e5c04.nq.gz
    ├── 9253c4254d2eb3578338e8250b062e0f50c3997e.nq.gz
    ├── 93f4d77344bb3d9a29195830ca108b362ddc1ed5.nq.gz
    ├── 96bb51dd8a3f4bece1052b593876838e2a1484b8.nq.gz
    ├── 981238560ad8c859070495975106d3814e068df2.nq.gz
    ├── 986119be2fff093e6407fe963b2ce551def4c373.nq.gz
    ├── 98e8b72ee0af30cbdb2ec77d24cd9a0e273c109c.nq.gz
    ├── 99d11b735636c16fafe73f76bcce6ec94d13ba80.nq.gz
    ├── 9a34f1147d2a383435c8ab633ae83dea399e4c9e.nq.gz
    ├── 9a59379b4d61cd36d00f091ab5b40eaf14da3d0a.nq.gz
    ├── 9b3b72bd60f515217b7ed0d2699c483a47f1da87.nq.gz
    ├── 9ba44acfcadb0d70d4efcf077ac06aae51a92505.nq.gz
    ├── 9c336586a33135f21d1f78b3607074a37b38e178.nq.gz
    ├── 9c36116721e8a7acc5588c9164adb55cfa58899f.nq.gz
    ├── 9db34b711d79f98087578e6ac28025d81d88f24b.nq.gz
    ├── 9e85c4cf2c50fe5bfe8aa51e152e71b3361ac366.nq.gz
    ├── a038c664a60fa3b6995e3f39b305fd0adbdc8919.nq.gz
    ├── a1dcea14de9cfb95311ebe94e8a1096c27800941.nq.gz
    ├── a22ba4fa06d4443cecda06ed4591a8439a2ba17f.nq.gz
    ├── a2c809fb6d1e247acec60ccc254a562ff56cbe52.nq.gz
    ├── a31dc54a3cc51547bee02db7f8253be06b38b958.nq.gz
    ├── a3968aee5a180b079c3f14cafc60026001d7d50f.nq.gz
    ├── a443ad00468741cf03bf1aeca726dc1b727cbef1.nq.gz
    ├── a577a248755c62ef343c62de6eaa6833cd51717b.nq.gz
    ├── a5efa019d0a36e16ccbcc4b1a985b6f7538eed1a.nq.gz
    ├── a66e2d28ea2bc90255cc57ea1313892995edf757.nq.gz
    ├── a70c187003aab47fb853ee2f108b0139435055ef.nq.gz
    ├── a83abe3797cdb3842cdbcbca76e43c3873104574.nq.gz
    ├── a8b9ab1992257d721ad627b14f535c3d4b020888.nq.gz
    ├── a8d9d455518f245899a696cc8525ff548b83cd29.nq.gz
    ├── a9c79d455f75ee716aff18f3d593b96df0c18068.nq.gz
    ├── aa37a218b97e5f6ad37a74a62b50727279a5e460.nq.gz
    ├── ab99ad52d4606319e4d6d22dfeeef2735fe95192.nq.gz
    ├── abb5fe4fbcb592ba5d5bbaf118284a3d01f3841e.nq.gz
    ├── aebd5191ccec13ccf39821a97ba6ae488b2197cb.nq.gz
    ├── b0eb6c79fe9536abfea8ab7305ab0d082c1b3ccb.nq.gz
    ├── b0fe1743a78fb1befd80f6252f4e293a1132b52c.nq.gz
    ├── b11b40f18b19cbed29c928a1c94ab159516abb58.nq.gz
    ├── b27612437a24c7fa58990952e3bf5aed473e73e8.nq.gz
    ├── b38883564facfaa78da3643fc25543fa30785ad6.nq.gz
    ├── b5207d658a2cd84686fe953ed99080b02b600a3f.nq.gz
    ├── b73de91426164da968330ebbc1aa6ced5f1d4fd8.nq.gz
    ├── b751d7bf7c18b00b655e7a7710a85654f60b505b.nq.gz
    ├── b84e3db44a04d4e23328a1d73ec14e0079e94534.nq.gz
    ├── b8bf283555eec063eaa40ca47492f25ce9d78e46.nq.gz
    ├── ba21246e2b56c892969b279ffaf0c9e2d98c7614.nq.gz
    ├── bae17702e4388ccb9b91fb9ff7e645f65a2978da.nq.gz
    ├── baf0ab27e3af609a0e340a4035bfd47041581ba4.nq.gz
    ├── bb9c20a094e41b7632d63bcff20c0b4b95e80777.nq.gz
    ├── bd27c4d2d594c9d7182a142e4fa9e0b49b3b6b35.nq.gz
    ├── bd4e0d97a88cc11da36c193162b0080cc3cc19f2.nq.gz
    ├── bf1e7bf19bfc67154370db53c719a78f0f6866d8.nq.gz
    ├── c0904e523412bd9b54a467254927575c804a3603.nq.gz
    ├── c160fa2be58b31228367ef98da3cc5ae27e2d305.nq.gz
    ├── c1c8a8f4f7340df7a75fdc0e42eb140313e03f9c.nq.gz
    └── c25ba5c9750e6c2be231d53fce0a9ae60618f8b8.nq.gz

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

## Source repository

[BurntSushi/jiff](https://github.com/BurntSushi/jiff)

---
*Parsed on 2026-05-08 by [repolex](https://repolex.ai)*
