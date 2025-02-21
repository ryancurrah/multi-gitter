# Changelog

## [0.32.0](https://www.github.com/lindell/multi-gitter/compare/v0.31.1...v0.32.0) (2021-08-12)


### Features

* added --config to status command ([#174](https://www.github.com/lindell/multi-gitter/issues/174)) ([8c52c93](https://www.github.com/lindell/multi-gitter/commit/8c52c931df5fe786a9b9c26e77aebe50241f8391))

### [0.31.1](https://www.github.com/lindell/multi-gitter/compare/v0.31.0...v0.31.1) (2021-08-12)


### Bug Fixes

* added support for GitLab subgroups with --project ([#171](https://www.github.com/lindell/multi-gitter/issues/171)) ([25b5d54](https://www.github.com/lindell/multi-gitter/commit/25b5d543056909fdb1a937118989f06dd4902f80))

## [0.31.0](https://www.github.com/lindell/multi-gitter/compare/v0.30.0...v0.31.0) (2021-08-08)


### Features

* interactive mode  ([#167](https://www.github.com/lindell/multi-gitter/issues/167)) ([7351520](https://www.github.com/lindell/multi-gitter/commit/73515206bc7201b28e0e1faef7e1009b3e5a34f9))

## [0.30.0](https://www.github.com/lindell/multi-gitter/compare/v0.29.2...v0.30.0) (2021-08-01)


### Features

* moved to built in completion command in cobra 1.2.x ([#163](https://www.github.com/lindell/multi-gitter/issues/163)) ([81a7187](https://www.github.com/lindell/multi-gitter/commit/81a7187fce1ab76e6d87bdeee02b268fdb21320b))


### Dependencies

* update module github.com/google/go-github/v36 to v37 ([213a1c6](https://www.github.com/lindell/multi-gitter/commit/213a1c6cc603cec49f889ffe52dd50d22f33ab44))
* update module github.com/xanzy/go-gitlab to v0.50.1 ([cac5518](https://www.github.com/lindell/multi-gitter/commit/cac5518094e4cc82bf2ad6d47c42a593f3031034))

### [0.29.2](https://www.github.com/lindell/multi-gitter/compare/v0.29.1...v0.29.2) (2021-07-01)


### Bug Fixes

* push hooks no longer run with cmd-git implementation ([#159](https://www.github.com/lindell/multi-gitter/issues/159)) ([7360c0d](https://www.github.com/lindell/multi-gitter/commit/7360c0d14b83be627325d0b4ea95177e71c2a565))


### Dependencies

* update golang.org/x/oauth2 commit hash to a41e5a7 ([234ce36](https://www.github.com/lindell/multi-gitter/commit/234ce36753e5eec8d73700a4b65e4ee8ad0773a7))
* update module github.com/go-git/go-git/v5 to v5.4.2 ([016f54d](https://www.github.com/lindell/multi-gitter/commit/016f54d39a8df80558b7c46880a7dfabd16c7e28))
* update module github.com/google/go-github/v35 to v36 ([#162](https://www.github.com/lindell/multi-gitter/issues/162)) ([893d9ea](https://www.github.com/lindell/multi-gitter/commit/893d9eae5dd5f8abcf6c00cb233957aea532d1c2))

### [0.29.1](https://www.github.com/lindell/multi-gitter/compare/v0.29.0...v0.29.1) (2021-06-28)


### Bug Fixes

* commit hooks no longer run with cmd-git implementation ([#157](https://www.github.com/lindell/multi-gitter/issues/157)) ([ba12d08](https://www.github.com/lindell/multi-gitter/commit/ba12d08fee2e8cc0ef8015a1761afde747a2622c))
* downgraded go-diff to fix diff formating ([#156](https://www.github.com/lindell/multi-gitter/issues/156)) ([6ef43a8](https://www.github.com/lindell/multi-gitter/commit/6ef43a847f14d5b81745e9978732eebda5bf8ca9))

## [0.29.0](https://www.github.com/lindell/multi-gitter/compare/v0.28.0...v0.29.0) (2021-06-20)


### Features

* added configuration options through config files ([#150](https://www.github.com/lindell/multi-gitter/issues/150)) ([f38a7ad](https://www.github.com/lindell/multi-gitter/commit/f38a7ad3ffc9f6aaef60913a6a08006b5b672a93))


### Bug Fixes

* made sure any tokens output in the logs are now censored ([#143](https://www.github.com/lindell/multi-gitter/issues/143)) ([0e5cee7](https://www.github.com/lindell/multi-gitter/commit/0e5cee7ecd6dde23d21869058cc383e83b232703))

## [0.28.0](https://www.github.com/lindell/multi-gitter/compare/v0.27.0...v0.28.0) (2021-06-16)


### Features

* added --git-type flag ([cb4701e](https://www.github.com/lindell/multi-gitter/commit/cb4701eb90b98bf585b1a8835368c4cd8f0e0095))

## [0.27.0](https://www.github.com/lindell/multi-gitter/compare/v0.26.1...v0.27.0) (2021-06-14)


### Features

* added fork mode ([#128](https://www.github.com/lindell/multi-gitter/issues/128)) ([f9e7827](https://www.github.com/lindell/multi-gitter/commit/f9e78273440642be662686912b89ff38123bacf7))


### Miscellaneous

* improved logging and added stack trace if --log-level=trace is used ([#138](https://www.github.com/lindell/multi-gitter/issues/138)) ([abccc5f](https://www.github.com/lindell/multi-gitter/commit/abccc5f28ba22e3b2b99d6d3ee1c513a213caea7))

### [0.26.1](https://www.github.com/lindell/multi-gitter/compare/v0.26.0...v0.26.1) (2021-06-09)


### Bug Fixes

* made remove branch on merge the default behaviour for GitLab merge ([#135](https://www.github.com/lindell/multi-gitter/issues/135)) ([9cc5983](https://www.github.com/lindell/multi-gitter/commit/9cc5983407c3b5be4a42c55dbd7c4b03f54d3f23))

## [0.26.0](https://www.github.com/lindell/multi-gitter/compare/v0.25.6...v0.26.0) (2021-06-08)


### Features

* added --include-subgroups flag ([#131](https://www.github.com/lindell/multi-gitter/issues/131)) ([eff19a4](https://www.github.com/lindell/multi-gitter/commit/eff19a4b23030487fa9a3e64553443d2a8fb3133))


### Bug Fixes

* improved error messages for common problems with the script ([de9e525](https://www.github.com/lindell/multi-gitter/commit/de9e5259d2bd900abf72c56f40a76f223cbfffd0))

### [0.25.6](https://www.github.com/lindell/multi-gitter/compare/v0.25.5...v0.25.6) (2021-06-05)


### Bug Fixes

* fixed skip-pr flag description ([#127](https://www.github.com/lindell/multi-gitter/issues/127)) ([1c4e2ac](https://www.github.com/lindell/multi-gitter/commit/1c4e2acec3fee563eb3cfa7391f63ffd5fc1d61e))
* typo where archived should be achieved ([#125](https://www.github.com/lindell/multi-gitter/issues/125)) ([5373ea8](https://www.github.com/lindell/multi-gitter/commit/5373ea8fd37e39ce1eb8edbb860af85faa47e370))

### [0.25.5](https://www.github.com/lindell/multi-gitter/compare/v0.25.4...v0.25.5) (2021-06-01)


### Dependencies

* update golang.org/x/oauth2 commit hash to f6687ab ([cab768a](https://www.github.com/lindell/multi-gitter/commit/cab768a1a6bf93b8f113b0b7221db7a4bab375cd))
* update module github.com/go-git/go-git/v5 to v5.4.1 ([fe45f2e](https://www.github.com/lindell/multi-gitter/commit/fe45f2e9ad2031ae4f436271e4a072101ba80805))

### [0.25.4](https://www.github.com/lindell/multi-gitter/compare/v0.25.3...v0.25.4) (2021-05-16)


### Bug Fixes

* make sure gitignore is used ([#119](https://www.github.com/lindell/multi-gitter/issues/119)) ([f33dee9](https://www.github.com/lindell/multi-gitter/commit/f33dee9a7acd798ab6ad0a7255351c50c9bd456e))

### [0.25.3](https://www.github.com/lindell/multi-gitter/compare/v0.25.2...v0.25.3) (2021-05-11)


### Bug Fixes

* added panic recover on a run repo basis ([#114](https://www.github.com/lindell/multi-gitter/issues/114)) ([6d44adf](https://www.github.com/lindell/multi-gitter/commit/6d44adf5ddbf3783bc4a2224c35a923ab599e7c6))


### Dependencies

* update module github.com/sergi/go-diff to v1.2.0 ([#116](https://www.github.com/lindell/multi-gitter/issues/116)) ([0273abe](https://www.github.com/lindell/multi-gitter/commit/0273abeba104e2ce522b4a97b1498341ad9e41d6))

### [0.25.2](https://www.github.com/lindell/multi-gitter/compare/v0.25.1...v0.25.2) (2021-05-11)


### Bug Fixes

* skip running git diff if debug or lower is not set ([#113](https://www.github.com/lindell/multi-gitter/issues/113)) ([5189374](https://www.github.com/lindell/multi-gitter/commit/51893745153e7825339f7398e844bf6d53404cc8))


### Dependencies

* update module github.com/google/go-github/v33 to v35 ([#110](https://www.github.com/lindell/multi-gitter/issues/110)) ([b6c8667](https://www.github.com/lindell/multi-gitter/commit/b6c8667f1ca48c62b1ec1703f8afa1664dfeca95))

### [0.25.1](https://www.github.com/lindell/multi-gitter/compare/v0.25.0...v0.25.1) (2021-05-01)


### Dependencies

* update golang.org/x/oauth2 commit hash to 81ed05c ([#107](https://www.github.com/lindell/multi-gitter/issues/107)) ([b529c3f](https://www.github.com/lindell/multi-gitter/commit/b529c3f113ccda92ee0981c48b0c26c74facb142))
* update module github.com/go-git/go-git/v5 to v5.3.0 ([905dbdb](https://www.github.com/lindell/multi-gitter/commit/905dbdbfa5b420ee985bed2ff58cfb2399b051b7))
* update module github.com/xanzy/go-gitlab to v0.49.0 ([#109](https://www.github.com/lindell/multi-gitter/issues/109)) ([597d8b4](https://www.github.com/lindell/multi-gitter/commit/597d8b41751b0cf90bc4743fc367ed72487ae35f))

## [0.25.0](https://www.github.com/lindell/multi-gitter/compare/v0.24.2...v0.25.0) (2021-04-25)


### Features

* added Gitea support ([#105](https://www.github.com/lindell/multi-gitter/issues/105)) ([0f89791](https://www.github.com/lindell/multi-gitter/commit/0f89791d62fe32f0d2a98f0b735782898976e3f7))

### [0.24.2](https://www.github.com/lindell/multi-gitter/compare/v0.24.1...v0.24.2) (2021-04-01)


### Dependencies

* update golang.org/x/oauth2 commit hash to 22b0ada ([#92](https://www.github.com/lindell/multi-gitter/issues/92)) ([335eee3](https://www.github.com/lindell/multi-gitter/commit/335eee37c02c54fa7d006ff0aab837b424f7d514))
* update module github.com/google/go-github/v33 to v34 ([#93](https://www.github.com/lindell/multi-gitter/issues/93)) ([03d3278](https://www.github.com/lindell/multi-gitter/commit/03d327835bb7a99362e0b13224200a41d068a642))

### [0.24.1](https://www.github.com/lindell/multi-gitter/compare/v0.24.0...v0.24.1) (2021-03-31)


### Bug Fixes

* fixed windows filepaths ([#89](https://www.github.com/lindell/multi-gitter/issues/89)) ([cb38fc0](https://www.github.com/lindell/multi-gitter/commit/cb38fc08a084dd7b5b05717b852e9804d52e1720))

## [0.24.0](https://www.github.com/lindell/multi-gitter/compare/v0.23.1...v0.24.0) (2021-03-30)


### Features

* added static flag completion for enums ([#87](https://www.github.com/lindell/multi-gitter/issues/87)) ([586dd61](https://www.github.com/lindell/multi-gitter/commit/586dd616418affe1838b4ecfb5714458ffcafd0b))

### [0.23.1](https://www.github.com/lindell/multi-gitter/compare/v0.23.0...v0.23.1) (2021-03-30)


### Bug Fixes

* fixed brew test command ([fc243e8](https://www.github.com/lindell/multi-gitter/commit/fc243e8d7d94c9b1793eb7299a893ba2ba14794c))

## [0.23.0](https://www.github.com/lindell/multi-gitter/compare/v0.22.1...v0.23.0) (2021-03-30)


### Features

* added GitHub autocompletion ([#84](https://www.github.com/lindell/multi-gitter/issues/84)) ([5fee0c4](https://www.github.com/lindell/multi-gitter/commit/5fee0c4b88e802a8be4168f802b79a1701afd3a6))

### [0.22.1](https://www.github.com/lindell/multi-gitter/compare/v0.22.0...v0.22.1) (2021-03-12)


### Dependencies

* update module github.com/google/go-github/v32 to v33 ([#82](https://www.github.com/lindell/multi-gitter/issues/82)) ([1c48de3](https://www.github.com/lindell/multi-gitter/commit/1c48de3a81a64cbac6481b3260bdc3512e98a34f))
* update module github.com/sirupsen/logrus to v1.8.1 ([31dad70](https://www.github.com/lindell/multi-gitter/commit/31dad70383ab5c6d742e393ad97c32c610f85c2b))
* update module github.com/xanzy/go-gitlab to v0.46.0 ([f0a3503](https://www.github.com/lindell/multi-gitter/commit/f0a350323dcee32acf20265b5ebcedce2f1531b9))
* update module github.com/xanzy/go-gitlab to v0.47.0 ([92a18a3](https://www.github.com/lindell/multi-gitter/commit/92a18a3fd27136b5a46c2de423c109d28ad9da71))

## [0.22.0](https://www.github.com/lindell/multi-gitter/compare/v0.21.1...v0.22.0) (2021-03-03)


### Features

* added skip-pr flag ([#80](https://www.github.com/lindell/multi-gitter/issues/80)) ([c4b85ea](https://www.github.com/lindell/multi-gitter/commit/c4b85ea5606a361b13b0a6308f3cfea776f954ad))


### Dependencies

* update module github.com/sirupsen/logrus to v1.8.0 ([8c132b4](https://www.github.com/lindell/multi-gitter/commit/8c132b410baef2812a5525727147eb11f939a870))
* update module github.com/xanzy/go-gitlab to v0.45.0 ([9e1bc9a](https://www.github.com/lindell/multi-gitter/commit/9e1bc9a163f151fddba8f24f44934111d7e9b810))

### [0.21.1](https://www.github.com/lindell/multi-gitter/compare/v0.21.0...v0.21.1) (2021-02-19)


### Bug Fixes

* fixed license file in release ([506084f](https://www.github.com/lindell/multi-gitter/commit/506084fd8b17f42a3311524bc0dbcc29ce39c50b))

## [0.21.0](https://www.github.com/lindell/multi-gitter/compare/v0.20.5...v0.21.0) (2021-02-19)


### Features

* added shell completion command ([c5782a2](https://www.github.com/lindell/multi-gitter/commit/c5782a2e377ecfc071c82c1db0a775e45215a0cc))

### [0.20.5](https://www.github.com/lindell/multi-gitter/compare/v0.20.4...v0.20.5) (2021-02-19)


### Miscellaneous

* moved brew release to Formula folder ([d1ae864](https://www.github.com/lindell/multi-gitter/commit/d1ae8644cd2a4e6138b3f23d23e792509ff7b3ef))

### [0.20.4](https://www.github.com/lindell/multi-gitter/compare/v0.20.3...v0.20.4) (2021-02-19)


### Miscellaneous

* removed brew download strategy ([6c35be5](https://www.github.com/lindell/multi-gitter/commit/6c35be50c14dff82363931bd12ade4de204103c1))

### [0.20.3](https://www.github.com/lindell/multi-gitter/compare/v0.20.2...v0.20.3) (2021-02-19)


### Bug Fixes

* fixed homebrew release ([dece0d8](https://www.github.com/lindell/multi-gitter/commit/dece0d8ad5e40c20be37eeb9db42dcdfd9eaf4d4))

### [0.20.2](https://www.github.com/lindell/multi-gitter/compare/v0.20.1...v0.20.2) (2021-02-19)


### Miscellaneous

* added brew install ([#73](https://www.github.com/lindell/multi-gitter/issues/73)) ([3f56a4a](https://www.github.com/lindell/multi-gitter/commit/3f56a4aefe6a984b781e2e5792b929ea6b6962e3))
* improved the base-url description ([5e7ec24](https://www.github.com/lindell/multi-gitter/commit/5e7ec248b5dee732fc276d7c40a62a8c4fb76c1c))

### [0.20.1](https://www.github.com/lindell/multi-gitter/compare/v0.20.0...v0.20.1) (2021-02-17)


### Miscellaneous

* updated to go 1.16 ([c8fa961](https://www.github.com/lindell/multi-gitter/commit/c8fa96154f2925ea724bf9ff0a74027dfc0a9286))

## [0.20.0](https://www.github.com/lindell/multi-gitter/compare/v0.19.1...v0.20.0) (2021-02-16)


### Features

* **gitlab:** option to change base-url for gitlab ([#69](https://www.github.com/lindell/multi-gitter/issues/69)) ([147ebe6](https://www.github.com/lindell/multi-gitter/commit/147ebe67d2902850f06c7575bbe8e43b0372eccd))


### Dependencies

* update module spf13/cobra to v1.1.3 ([7a32bb6](https://www.github.com/lindell/multi-gitter/commit/7a32bb615e0969aa41618885023d797ea101cf5b))
* update module xanzy/go-gitlab to v0.44.0 ([53f834b](https://www.github.com/lindell/multi-gitter/commit/53f834b29f9e801a9fa5d8416ad18b22635ab058))

### [0.19.1](https://www.github.com/lindell/multi-gitter/compare/v0.19.0...v0.19.1) (2021-02-02)


### Dependencies

* update golang.org/x/oauth2 commit hash to f9ce19e ([#66](https://www.github.com/lindell/multi-gitter/issues/66)) ([64d9095](https://www.github.com/lindell/multi-gitter/commit/64d90952856fdfd0517cf03bb752603c708ff6b9))
* update module xanzy/go-gitlab to v0.43.0 ([1a44511](https://www.github.com/lindell/multi-gitter/commit/1a44511a7cb27aefb3e0e6d8e4309e3fc78f4756))

## [0.19.0](https://www.github.com/lindell/multi-gitter/compare/v0.18.0...v0.19.0) (2021-01-21)


### Features

* added --merge-type flag ([#64](https://www.github.com/lindell/multi-gitter/issues/64)) ([dd18402](https://www.github.com/lindell/multi-gitter/commit/dd18402365c0f41440bd580497cbd12e0738bc7e))

## [0.18.0](https://www.github.com/lindell/multi-gitter/compare/v0.17.0...v0.18.0) (2021-01-20)


### Features

* added --fetch-depth flag ([#62](https://www.github.com/lindell/multi-gitter/issues/62)) ([5cdb723](https://www.github.com/lindell/multi-gitter/commit/5cdb72334f151c4950ffd9763b8ee760dbc3f8a5))

## [0.17.0](https://www.github.com/lindell/multi-gitter/compare/v0.16.4...v0.17.0) (2021-01-20)


### Features

* added links to printed prs ([#58](https://www.github.com/lindell/multi-gitter/issues/58)) ([cd76c61](https://www.github.com/lindell/multi-gitter/commit/cd76c6143a9b008f6be08748b77f7c8acc36aaf9))


### Bug Fixes

* added the number of created pull requests ([#56](https://www.github.com/lindell/multi-gitter/issues/56)) ([d432430](https://www.github.com/lindell/multi-gitter/commit/d4324307441ffc74002e1cb4f5c08b83f45a2781))

### [0.16.4](https://www.github.com/lindell/multi-gitter/compare/v0.16.3...v0.16.4) (2021-01-16)


### Bug Fixes

* multi-gitter does now only fetch the base and head branch ([b272644](https://www.github.com/lindell/multi-gitter/commit/b272644355d9291c23de8f028a3132de5a5eb99e))


### Dependencies

* update module stretchr/testify to v1.7.0 ([0a06a24](https://www.github.com/lindell/multi-gitter/commit/0a06a247d93d34986504608d1ff437aa17869d53))

### [0.16.3](https://www.github.com/lindell/multi-gitter/compare/v0.16.2...v0.16.3) (2021-01-15)


### Bug Fixes

* fixed presentation of repos with existing repo ([ac8027b](https://www.github.com/lindell/multi-gitter/commit/ac8027b3cf6c8df46ae3c4e2b79891c14962f7bc))

### [0.16.2](https://www.github.com/lindell/multi-gitter/compare/v0.16.1...v0.16.2) (2021-01-14)


### Bug Fixes

* fixed bug where base branch was left empty ([64d5e22](https://www.github.com/lindell/multi-gitter/commit/64d5e225e631f8b3a0dac3fc3145f0168dacba70))


### Dependencies

* update golang.org/x/oauth2 commit hash to d3ed898 ([feea168](https://www.github.com/lindell/multi-gitter/commit/feea168f7a2d44d9fe08c8b1a995dfc5b213f7ce))

### [0.16.1](https://www.github.com/lindell/multi-gitter/compare/v0.16.0...v0.16.1) (2021-01-12)


### Dependencies

* update module xanzy/go-gitlab to v0.41.0 ([f713ee2](https://www.github.com/lindell/multi-gitter/commit/f713ee227b1013d3e2f293fa4d50dbdbbf980b17))
* update module xanzy/go-gitlab to v0.42.0 ([fd8e373](https://www.github.com/lindell/multi-gitter/commit/fd8e3737e9db7348cf271adab5d6a958e1a794f4))

## [0.16.0](https://www.github.com/lindell/multi-gitter/compare/v0.15.3...v0.16.0) (2020-12-18)


### Features

* added base-branch flag ([8c04b8d](https://www.github.com/lindell/multi-gitter/commit/8c04b8d241f66ec8def92baf8ae27a39a24abcff))


### Dependencies

* update module xanzy/go-gitlab to v0.40.2 ([ce33ff5](https://www.github.com/lindell/multi-gitter/commit/ce33ff5e69a9d984199c0f00e0b8c57ef6bfbc93))

### [0.15.3](https://www.github.com/lindell/multi-gitter/compare/v0.15.2...v0.15.3) (2020-12-08)


### Dependencies

* update golang.org/x/oauth2 commit hash to 08078c5 ([8b94c50](https://www.github.com/lindell/multi-gitter/commit/8b94c50acf0df6c5af2a9b4e81a7aea296575bc8))
* update golang.org/x/oauth2 commit hash to 9317641 ([242cdd0](https://www.github.com/lindell/multi-gitter/commit/242cdd09b5c62813336059f8ac73cf662bc4f71e))

### [0.15.2](https://www.github.com/lindell/multi-gitter/compare/v0.15.1...v0.15.2) (2020-12-03)


### Miscellaneous

* bump github.com/xanzy/go-gitlab from 0.40.0 to 0.40.1 ([550f302](https://www.github.com/lindell/multi-gitter/commit/550f302b23ac1301e84994846766c95d2011fb6e))


### Dependencies

* update golang.org/x/oauth2 commit hash to 0b49973 ([ee02a57](https://www.github.com/lindell/multi-gitter/commit/ee02a57a4512e9e8b29770ec610974ad5ecdf7d2))

### [0.15.1](https://www.github.com/lindell/multi-gitter/compare/v0.15.0...v0.15.1) (2020-12-02)


### Bug Fixes

* corrected the name of the REPOSITORY env var ([9b87070](https://www.github.com/lindell/multi-gitter/commit/9b8707096a85d1106045fb79d13b87c5fe8b99de))


### Miscellaneous

* bump github.com/xanzy/go-gitlab from 0.39.0 to 0.40.0 ([e65e1a8](https://www.github.com/lindell/multi-gitter/commit/e65e1a8a480202e81a3b2488d0c0d350fa3f265d))
