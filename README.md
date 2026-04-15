# Repolex Knowledge Graph of sverweij/dependency-cruiser

RDF knowledge graph data for [sverweij/dependency-cruiser](https://github.com/sverweij/dependency-cruiser), parsed by [repolex](https://repolex.ai).

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
lexq download sverweij/dependency-cruiser
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
└── aggregate
    └── ast
        ├── 00c3f4c5944f53a3fe399d6c9df394f071afe564
        │   └── chunk-001.nq.gz
        ├── 02d9f53d7b9e1a51f5a389ce920f9a89c53b5744
        │   └── chunk-001.nq.gz
        ├── 03d3d4b320a5de81c27f5e0905aff4a6c4076893
        │   └── chunk-001.nq.gz
        ├── 06205f38f448462d6f3f8919d57adb10315b1850
        │   └── chunk-001.nq.gz
        ├── 07762ebc7dcd2f46d68302003fd06b69f54d0946
        │   └── chunk-001.nq.gz
        ├── 07b8c60e3d5fc593721aa6278aa6462287eb343f
        │   └── chunk-001.nq.gz
        ├── 092cf86c27da54ca335c9ab04f8ec50ee1956b76
        │   └── chunk-001.nq.gz
        ├── 0b07cb71e059b5cea7856643d89fcea91b8df717
        │   └── chunk-001.nq.gz
        ├── 0b3e89dbf031b795e58025e8fbe913e8bc28e540
        │   └── chunk-001.nq.gz
        ├── 0d70164f14e15c7b9c6809e99c7b0302ef76d4f5
        │   └── chunk-001.nq.gz
        ├── 0e5a8314037161d0ea41f130239968c71b1a2566
        │   └── chunk-001.nq.gz
        ├── 0f564e95ccec7ce71d6c8e94d7b77eaa27eff912
        │   └── chunk-001.nq.gz
        ├── 10aecc6b0eadabd669d45089497190b8cba27ff9
        │   └── chunk-001.nq.gz
        ├── 11045fabd41ec8012eb5221b49a62787ffc82db0
        │   └── chunk-001.nq.gz
        ├── 1775912020ac6055dfdba0bf5051823d435c8f4d
        │   └── chunk-001.nq.gz
        ├── 179b9694d843c29fdc29513cea3b78cd6d92bd49
        │   └── chunk-001.nq.gz
        ├── 1a2d0210154b0466fdafaaf4c4e29cd942381432
        │   └── chunk-001.nq.gz
        ├── 1b16d6840758066afa55171e7777b75d636582e4
        │   └── chunk-001.nq.gz
        ├── 1cd25c2f2073207ab1dfeb8fee277d5cd5513828
        │   └── chunk-001.nq.gz
        ├── 1f818238e0a283d9be80615d62a0fc081d80c99a
        │   └── chunk-001.nq.gz
        ├── 1fa7740c1fbcb4abaa94c10bf3f90e81c8a5adac
        │   └── chunk-001.nq.gz
        ├── 220e0a36013c80e866d77ec42a87d90a3ea4f131
        │   └── chunk-001.nq.gz
        ├── 240b50599e5526ada2574839593ea2d497f82452
        │   └── chunk-001.nq.gz
        ├── 26dac1191e95905bc36a24f71b71117f9432aebc
        │   └── chunk-001.nq.gz
        ├── 2709dd4f71e481d3f1e3c3e12e5a7376fe2cbb62
        │   └── chunk-001.nq.gz
        ├── 27af4f7b106c8ebd85d3f99a7fb56de7f7e0da5e
        │   └── chunk-001.nq.gz
        ├── 2836fc0dd86787ee80bbb35cbbd8c8f10d6cba35
        │   └── chunk-001.nq.gz
        ├── 28ca365c3da9d5fa9438fb5c08e8bfd624bb5474
        │   └── chunk-001.nq.gz
        ├── 2a7e7ce89e8599f117c4041ed0d6d6eb67f4b647
        │   └── chunk-001.nq.gz
        ├── 2b449ef9a945c049f71ea2a698ab468928cafe6e
        │   └── chunk-001.nq.gz
        ├── 2b639e36e365483a5f9e96bd38bad7677798e62a
        │   └── chunk-001.nq.gz
        ├── 2bac1c20327ba53627494d44160e34d764a469ee
        │   └── chunk-001.nq.gz
        ├── 2de9a463df2c202a0b9c32f901dec5b98c54bdc6
        │   └── chunk-001.nq.gz
        ├── 2e47fe98ded5b3fd993bc455fe8bd03360a6db67
        │   └── chunk-001.nq.gz
        ├── 2e6036b2a47c402afbb43f7e969eb4a22b8328e7
        │   └── chunk-001.nq.gz
        ├── 2f9967d0f58e054ba649810951eef46a5a098d51
        │   └── chunk-001.nq.gz
        ├── 31ddc75313568e527a8ad07d354b05e2f4eafae5
        │   └── chunk-001.nq.gz
        ├── 3278c78bba286877efcde8ca6b5e24aba22b522b
        │   └── chunk-001.nq.gz
        ├── 33f13d0c028830d4f2e50743dba994bd067be196
        │   └── chunk-001.nq.gz
        ├── 34beb97cf25643bc363c045514bc34c658aba2bb
        │   └── chunk-001.nq.gz
        ├── 35d721bc3bc9315f98fbb335c28e634e1932332e
        │   └── chunk-001.nq.gz
        ├── 36e6154690bd4af2443226cb9b3f947d0d7f7e9c
        │   └── chunk-001.nq.gz
        ├── 374ec33f375133f37031062fe07bdc6b9a5b658c
        │   └── chunk-001.nq.gz
        ├── 3986915224b83d99134bdd1c6cf8b553b745f2f9
        │   └── chunk-001.nq.gz
        ├── 3a6af7d2932520848d2033002f75fd441690f8b8
        │   └── chunk-001.nq.gz
        ├── 3b2c6178827afe187759c4cc264dc982a0ac216c
        │   └── chunk-001.nq.gz
        ├── 3b3fe52db1e84f0da1725ded9c8cec247dd7f23d
        │   └── chunk-001.nq.gz
        ├── 3d13a152fdc5769122941fb415755828b0ae7708
        │   └── chunk-001.nq.gz
        ├── 3d5b2b46b2fd2d5c9fd3a023ebbfb66fe71ecaa2
        │   └── chunk-001.nq.gz
        ├── 40876e2fa82ab1ceb4d1db2bca195ea989542f0d
        │   └── chunk-001.nq.gz
        ├── 4157070e76287e7d59bda54d5ebac18db49248df
        │   └── chunk-001.nq.gz
        ├── 41ccc69b481936fed88487b636e02b83537b019e
        │   └── chunk-001.nq.gz
        ├── 41dbeb4eb2a5e53c35d6f522f051a0cb1fc50f42
        │   └── chunk-001.nq.gz
        ├── 41e01debeb6fda303ea6b8f6a5ab13db43137332
        │   └── chunk-001.nq.gz
        ├── 41fab2885d3f681169e119b1af84bce9009651a7
        │   └── chunk-001.nq.gz
        ├── 44a6fb559d36a60b4b35f28a62160e127774bb46
        │   └── chunk-001.nq.gz
        ├── 471a5077c47e4d8758b1bb049a1175fe80bb1edb
        │   └── chunk-001.nq.gz
        ├── 485e93fdd37493ea3e6d72d2f27bdb93708da7fb
        │   └── chunk-001.nq.gz
        ├── 48dcb5cae9952da8fbe15fa9768bcbac24ac2ef5
        │   └── chunk-001.nq.gz
        ├── 491355ecb26042ac9930b9541ad5a1bffaf36eb4
        │   └── chunk-001.nq.gz
        ├── 49a73af5167f49d04aa6035819880d7176550260
        │   └── chunk-001.nq.gz
        ├── 4a1febf426e17b23ecfe2dc07aa8b6f9e3d7889c
        │   └── chunk-001.nq.gz
        ├── 4a7b3079d2f98e71a862055ccaa6a74a11fd69a3
        │   └── chunk-001.nq.gz
        ├── 4ab5b93b741156f0425e4d3de522bfcca89abd0e
        │   └── chunk-001.nq.gz
        ├── 4bce7f8e59892c25b10f5a2454ee405955e8145c
        │   └── chunk-001.nq.gz
        ├── 4cdd00b8c426e7b6c0c67514c1db6ea04bacbb15
        │   └── chunk-001.nq.gz
        ├── 4eb336b8ce8a59afca01b5479146643c9a01ad7d
        │   └── chunk-001.nq.gz
        ├── 50a8604f326ec4e78c4f7fb407fd04dedd12154d
        │   └── chunk-001.nq.gz
        ├── 53aced3a83a139c94a3586bab0e33891f89dbaac
        │   └── chunk-001.nq.gz
        ├── 53b0e3ef048e3837793327fc73d5aaabeda3d10f
        │   └── chunk-001.nq.gz
        ├── 588af8d95c35d986f40c4c3fde1f4aa89b52c4f5
        │   └── chunk-001.nq.gz
        ├── 58ffa24cd5deacfa44ea7a7642827a2da225332c
        │   └── chunk-001.nq.gz
        ├── 59635efb4a9e707a7e2bdf702f72f8dd2f5d587d
        │   └── chunk-001.nq.gz
        ├── 5b7ab56fa20c92d6d8d69d2a37cad3954ab2828e
        │   └── chunk-001.nq.gz
        ├── 5bfd07e4aab0d08a0ec2d2728f4a7d8eec9a3f52
        │   └── chunk-001.nq.gz
        ├── 5c1a6b7e23d2b3106fa9147603da0ee069b61c73
        │   └── chunk-001.nq.gz
        ├── 5d1ea5190bff5351c20ad834e0087d974e98173c
        │   └── chunk-001.nq.gz
        ├── 5e1b739ed7cc999ac2d197fc71958ea3a71722b8
        │   └── chunk-001.nq.gz
        ├── 5ea4235882bca75e447dc7947914a3e828a67f0a
        │   └── chunk-001.nq.gz
        ├── 5f9357aba04516a890d39ba9493634f0929801f1
        │   └── chunk-001.nq.gz
        ├── 5fdadcb43a8bfaaece45f31af2daf8e713840679
        │   └── chunk-001.nq.gz
        ├── 6085d0e01a63e5128710161e547d5c899e13a926
        │   └── chunk-001.nq.gz
        ├── 63724947e1e1671519c65f60b968a7a1ffdfc504
        │   └── chunk-001.nq.gz
        ├── 6b7dac83dbd7f10ac22ee973eaa7007092ddf6de
        │   └── chunk-001.nq.gz
        ├── 6efad49baf8619d5f45c57f145abe892539208c8
        │   └── chunk-001.nq.gz
        ├── 71f96958cbaeb58f64df6935e032becd22f26e05
        │   └── chunk-001.nq.gz
        ├── 730d42a09268a8588207dba520d0cdbd494ff70a
        │   └── chunk-001.nq.gz
        ├── 7382028418d1b83f7127735be0ec0d53b2171e67
        │   └── chunk-001.nq.gz
        ├── 7393a69290d837709595b2cf05faa61d1b1428b8
        │   └── chunk-001.nq.gz
        ├── 74788e4654e4207449f48dc7e5ccf913428ef805
        │   └── chunk-001.nq.gz
        ├── 75d2b986be99ac13e9a7b401e6fd8ea82f032819
        │   └── chunk-001.nq.gz
        ├── 7789bbba030b8938570c8f0c3ad3760a3dd560f6
        │   └── chunk-001.nq.gz
        ├── 7828aeeeaaf63d891e19c299d8839948389a228c
        │   └── chunk-001.nq.gz
        ├── 79feaf41d3dee7232f7282e4124134b84099e5d4
        │   └── chunk-001.nq.gz
        ├── 7aaa8ab7a625453ba8707ebd0a3fe238fb9a6902
        │   └── chunk-001.nq.gz
        ├── 7b4f233581770a30311df0a05f61e29a515d1fe6
        │   └── chunk-001.nq.gz
        ├── 7c3a79e1584326124be3f028d346e5f768df66a5
        │   └── chunk-001.nq.gz
        ├── 7c4adad62d0b370c3d9cba0f52be06d9380f0da6
        │   └── chunk-001.nq.gz
        ├── 7cb21dd8d4e926ea483e46012dc124261f8e609d
        │   └── chunk-001.nq.gz
        ├── 7dd0cd41c7940a4a158978bb590396e0d999f3c6
        │   └── chunk-001.nq.gz
        ├── 7e4bd613eca0ba2940ac18d118c61384716bbc5b
        │   └── chunk-001.nq.gz
        ├── 809a804c3e0e3d78d2fd633628c549619824f229
        │   └── chunk-001.nq.gz
        ├── 82670c86b706f293352f262d1d2f97e9b60e5b38
        │   └── chunk-001.nq.gz
        ├── 827ddb0147ead5998726535e4408eee1dadde8b9
        │   └── chunk-001.nq.gz
        ├── 841d2400b9f733132476ed77a26e993ee499c231
        │   └── chunk-001.nq.gz
        ├── 86fe7bd0fbbe7c35072be246a3d3b43182bb67c2
        │   └── chunk-001.nq.gz
        ├── 882aebacf07d098dcd5ca6a982ebe040fdb12c67
        │   └── chunk-001.nq.gz
        ├── 885a153c47dc5f28c19aab4e40a0a7cd2588e795
        │   └── chunk-001.nq.gz
        ├── 88d819a01545b7eaec2930f5c14c1c2bb3414c0d
        │   └── chunk-001.nq.gz
        ├── 8a52b07a2e868fc72c6019b7b2a08df5df34d576
        │   └── chunk-001.nq.gz
        ├── 8a701ee148e9dff5debbf5da88ed5fc1c7b79116
        │   └── chunk-001.nq.gz
        ├── 8b2d11df5d4612360d8c4f7487e9aa2badb63057
        │   └── chunk-001.nq.gz
        ├── 8b37fe3228054513eb43440e49f1bb2f97615a65
        │   └── chunk-001.nq.gz
        ├── 8c55ad89290341a2947441fdabebaad5ca41e782
        │   └── chunk-001.nq.gz
        ├── 8dd30a3cdd38b475085d35157455d3318fdb1839
        │   └── chunk-001.nq.gz
        ├── 8dff805a275e0c56a4afc8e3be2a27ad3c6fa2ec
        │   └── chunk-001.nq.gz
        ├── 8e74e8513ba25b340ec5474289daec4a78f52dce
        │   └── chunk-001.nq.gz
        ├── 8e9a6cdccce614d16ab13e8aec0c17b7589b38a1
        │   └── chunk-001.nq.gz
        ├── 8fbf027294df9ec4edff28a79684822c81803d6a
        │   └── chunk-001.nq.gz
        ├── 92d4c336f37a90fb4bfa83780ec1318769310297
        │   └── chunk-001.nq.gz
        ├── 93d4d5c8f64ed4c5a478d25ea30b2ee909f5baee
        │   └── chunk-001.nq.gz
        ├── 97941d03bb6515f0360f782048ee39ea3c04cd1e
        │   └── chunk-001.nq.gz
        ├── 98ec40e48edafdc7844a8909f1817058e3ab326b
        │   └── chunk-001.nq.gz
        ├── 9a0f9f9312ee93bad434d4f0e78c1075299f1169
        │   └── chunk-001.nq.gz
        ├── 9a523b4e16ceafb9a410875fe780462b5a6c052b
        │   └── chunk-001.nq.gz
        ├── 9a96ff4c7cd9fb64be5b44cfb91a25a28b638f1e
        │   └── chunk-001.nq.gz
        ├── 9c15ddbdd72947025e2d41c4894def4a420ed9e9
        │   └── chunk-001.nq.gz
        ├── 9c4115a7ccd36dcf407a57b378a36dff6b79ae05
        │   └── chunk-001.nq.gz
        ├── 9c5c47ffb978f705cf789d0806a9c7c7ef861329
        │   └── chunk-001.nq.gz
        ├── 9d8a12912a7ced3e03b153d38c33c2ca8c16d00f
        │   └── chunk-001.nq.gz
        ├── 9e32b2b7d6ec0150b40dba58dddf45d8f3980fb4
        │   └── chunk-001.nq.gz
        ├── a319401a93712e115e75820d2c54d7b276466f02
        │   └── chunk-001.nq.gz
        ├── a4063bcf7b8839a768bd41e2af347af5897fee4f
        │   └── chunk-001.nq.gz
        ├── a64ca14693e27289fc75262d425fb73e979f18df
        │   └── chunk-001.nq.gz
        ├── a6e846f54c860bea00457b682e46415f26ff3ef0
        │   └── chunk-001.nq.gz
        ├── a84ffdd0ca8810331d612bc4cc2c7cfeb1b212f0
        │   └── chunk-001.nq.gz
        ├── a8515159fcbd0ec89de45b97126bf4fdaff5952f
        │   └── chunk-001.nq.gz
        ├── a95d058fff1322efebc4d51a417bfe493c072ed4
        │   └── chunk-001.nq.gz
        ├── a967043b5029692fac104d78193492d420a04037
        │   └── chunk-001.nq.gz
        ├── aa34bfa3dc35024dc63aafe17425b5762acd8082
        │   └── chunk-001.nq.gz
        ├── ab361c0dd3c06f8abd469899b74f74ed9855f5f2
        │   └── chunk-001.nq.gz
        ├── acf349238d7f66f37ad1e66622286296748380f8
        │   └── chunk-001.nq.gz
        ├── ad209e3bc733c2faa22e44909fe0add0c294f6b6
        │   └── chunk-001.nq.gz
        ├── afbf5e038dd0908bf341590400cd947c728f8e74
        │   └── chunk-001.nq.gz
        ├── affc816713aa5d958178bb64efd08657a9b3341b
        │   └── chunk-001.nq.gz
        ├── b1c13ef483665cda0d8dee657d321f61a4005f15
        │   └── chunk-001.nq.gz
        ├── b2c8997f4cb49e961672d5169f334e297c11e237
        │   └── chunk-001.nq.gz
        ├── b2fd66e96df4f24fa0a2d6427207f078baf4fe2a
        │   └── chunk-001.nq.gz
        ├── b42ce69626a21ea595ccc63e45cc33c834f3f65f
        │   └── chunk-001.nq.gz
        ├── b4c66e6e2431a913b06748db3636834f1151ab3b
        │   └── chunk-001.nq.gz
        ├── b4f7e25d5ffd8b2ff100d57efbdd2038e91000ef
        │   └── chunk-001.nq.gz
        ├── b519289f6b248e2b684382306190c2fed7222ce7
        │   └── chunk-001.nq.gz
        ├── b574d88959fbd596e10c5b0b08ebdcece0a55860
        │   └── chunk-001.nq.gz
        ├── b68c4ca1f9d0a9cf427aad22a354b44de7342c96
        │   └── chunk-001.nq.gz
        ├── b9ce49162d0fd3990262815236a2f41440324dd9
        │   └── chunk-001.nq.gz
        ├── bace6f2d513b43cf110d803f6395e70f8908c4be
        │   └── chunk-001.nq.gz
        ├── bae695c3b94738d4994274ff03e5b2deb780f0bb
        │   └── chunk-001.nq.gz
        ├── bf70a1dc85a9b52a774c6b80de6289c42b6ee15d
        │   └── chunk-001.nq.gz
        ├── bf7a96184a37b80dda45aab7b3721fc910c5b4d6
        │   └── chunk-001.nq.gz
        ├── c049a316f4d1413f400257331208e9cfb7e5fb50
        │   └── chunk-001.nq.gz
        ├── c3076baa640b82155098b4944411da7e828c224e
        │   └── chunk-001.nq.gz
        ├── c48aca959c9c9c1b1068c6d85cd4ed368de10d27
        │   └── chunk-001.nq.gz
        ├── c4c1201636c0297b74d8ecb10ef9963656dd173f
        │   └── chunk-001.nq.gz
        ├── c50626c3a854d8ba0c001e145a75a16722a4066a
        │   └── chunk-001.nq.gz
        ├── c63937dcf4983a52146f3e6c616e567cfc0d661e
        │   └── chunk-001.nq.gz
        ├── c760dcb5ed35806cf7a6ef95127607d5bef30853
        │   └── chunk-001.nq.gz
        ├── c9ed5f1122150e997d6bb029342a0f3229966159
        │   └── chunk-001.nq.gz
        ├── cd5590d7e16cbc6ca21a048a889651d3271c3789
        │   └── chunk-001.nq.gz
        ├── cd60a0710aa9ac8cf6801493f8642c66ae7c6ce9
        │   └── chunk-001.nq.gz
        ├── ce8c0da27c6c7faebde1d33a5f7c4fde7bfddb80
        │   └── chunk-001.nq.gz
        ├── cefbca321ce319e40c766a9abd697e20a7bb4ff8
        │   └── chunk-001.nq.gz
        ├── d2716c9c53ea301bd500c22df13fd604f11a0d3e
        │   └── chunk-001.nq.gz
        ├── d2817d19fab8632d0960dcfef6fbd16a64de21ea
        │   └── chunk-001.nq.gz
        ├── d3b9ce28f4266648b9f97ba4ae014afcdcde308a
        │   └── chunk-001.nq.gz
        ├── d49884ef3a21fc0a1435459700d886107b0c465a
        │   └── chunk-001.nq.gz
        ├── d4ab17728eafdd50a7a4588e9b91d77585badd33
        │   └── chunk-001.nq.gz
        ├── d5897e6693d58ea413761edb60b074d166887e9e
        │   └── chunk-001.nq.gz
        ├── d6303c2eb1b2bb640d28cdc8289a08dedbae1b84
        │   └── chunk-001.nq.gz
        ├── d756248ece22c5e6117e6ecab71e4b802d2a1ace
        │   └── chunk-001.nq.gz
        ├── d7fdedaca728ec7ad163bb9ca346502ffb09f8ce
        │   └── chunk-001.nq.gz
        ├── d85e0cd19364f054aefc3b84e3f3cc08344974cd
        │   └── chunk-001.nq.gz
        ├── d88487ea34fa444f5b8a071b2a2f68ee19baed13
        │   └── chunk-001.nq.gz
        ├── da9b8d5542e502e9285466a48a16307681dd4792
        │   └── chunk-001.nq.gz
        ├── dc4ecb9bea9bc14c5512a0aa84d91e599ca12c8a
        │   └── chunk-001.nq.gz
        ├── dcc97e17cb8b3456002c6132ac79f8817c580f3b
        │   └── chunk-001.nq.gz
        ├── dd2f0ff9422c1be119cde51bb76d54ffb0261a02
        │   └── chunk-001.nq.gz
        ├── ddcd6c147fa768cc9f6ed5f9d47d3c2ae8beafd2
        │   └── chunk-001.nq.gz
        ├── df0267d40746178f143768c2e5ed2d1cfc3ab9b3
        │   └── chunk-001.nq.gz
        ├── e0b3366eb9e3b76e86d510b3672eb335f5cd8478
        │   └── chunk-001.nq.gz
        ├── e366da8a73cf5cb01cea5572798cd4a080000fcc
        │   └── chunk-001.nq.gz
        ├── e6aaafe21760222e2753548fc9ec65ee5ac3ae18
        │   └── chunk-001.nq.gz
        ├── e6c737f18363fa6fe729bf86d3a4747e4a189c96
        │   └── chunk-001.nq.gz
        ├── e6f50a2a9b895e7c3fcdbc82f4647b2919fbbf82
        │   └── chunk-001.nq.gz
        ├── e87d98fd333d0b30b0627802c3022186b91bd7cb
        │   └── chunk-001.nq.gz
        ├── ea28022ed05a53a37dfd44d853844f3f30c159fb
        │   └── chunk-001.nq.gz
        ├── ea58d1e3fe1694e7352ed40c21424fb2a5a6c60b
        │   └── chunk-001.nq.gz
        ├── ecb2408e9a997ec369d5660bfdc229c97c5f6867
        │   └── chunk-001.nq.gz
        ├── ecf205822ddb415a91ec2cd5a99aaee13e526750
        │   └── chunk-001.nq.gz
        ├── ee547daf8da0e647babd6211f1c15b542aa441c5
        │   └── chunk-001.nq.gz
        └── ef97732883816fe243d3a2dfac407bc21808cfee
            └── chunk-001.nq.gz

203 directories, 200 files
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

[sverweij/dependency-cruiser](https://github.com/sverweij/dependency-cruiser)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
