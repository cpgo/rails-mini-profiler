# Changelog

## [0.8.0](https://github.com/cpgo/rails-mini-profiler/compare/v0.7.3...v0.8.0) (2024-11-18)


### Features

* add copy button, fixes [#69](https://github.com/cpgo/rails-mini-profiler/issues/69) ([9a91a3f](https://github.com/cpgo/rails-mini-profiler/commit/9a91a3f70b35bc7bc96cb3a56116aa35c0d9d8a3))
* add request table filters, fixes [#53](https://github.com/cpgo/rails-mini-profiler/issues/53) ([#61](https://github.com/cpgo/rails-mini-profiler/issues/61)) ([2e86671](https://github.com/cpgo/rails-mini-profiler/commit/2e86671c58bf3a451c5a813495693aec782725c8))
* add sequel trace filtering ([#64](https://github.com/cpgo/rails-mini-profiler/issues/64)) ([007716e](https://github.com/cpgo/rails-mini-profiler/commit/007716e8279d39511b8652f05f3cbedc723d09bb))
* add support for older ruby versions, fixes [#48](https://github.com/cpgo/rails-mini-profiler/issues/48) ([#49](https://github.com/cpgo/rails-mini-profiler/issues/49)) ([97061c4](https://github.com/cpgo/rails-mini-profiler/commit/97061c478da59f02975d88e2883e4a0e3bad4ef5))
* add support for rails 6.0, fixes [#52](https://github.com/cpgo/rails-mini-profiler/issues/52) ([#51](https://github.com/cpgo/rails-mini-profiler/issues/51)) ([63371f6](https://github.com/cpgo/rails-mini-profiler/commit/63371f6558cb6009ff73a56a7f0e0fa3bccc46cd))
* add trace filtering, closes [#67](https://github.com/cpgo/rails-mini-profiler/issues/67) ([2722f92](https://github.com/cpgo/rails-mini-profiler/commit/2722f92b8c7dad14b89a64716b28dc6a960b0992))
* add webpacker support, see [#8](https://github.com/cpgo/rails-mini-profiler/issues/8) ([#39](https://github.com/cpgo/rails-mini-profiler/issues/39)) ([a0f17f3](https://github.com/cpgo/rails-mini-profiler/commit/a0f17f3088307474d7428fc8487c51fb2f0746cf))
* improve checkbox behaviour ([4ffe202](https://github.com/cpgo/rails-mini-profiler/commit/4ffe202149f48c73b20742094c84d310157baccf))
* serve assets locally, fixes [#17](https://github.com/cpgo/rails-mini-profiler/issues/17) ([6f62d55](https://github.com/cpgo/rails-mini-profiler/commit/6f62d5584f934e7e61fd0735c4ab00718f1be6c3))


### Bug Fixes

* add better support for api-only applications, fixes [#14](https://github.com/cpgo/rails-mini-profiler/issues/14) ([8745c57](https://github.com/cpgo/rails-mini-profiler/commit/8745c57f37218b24e097c1b1b323b7aeb52d03af))
* add charset to table definitions ([#150](https://github.com/cpgo/rails-mini-profiler/issues/150)) ([1dab8a8](https://github.com/cpgo/rails-mini-profiler/commit/1dab8a873ce2908af5f87039d300d85765a9cd29))
* authentication thread issue, fixes [#99](https://github.com/cpgo/rails-mini-profiler/issues/99) ([db62984](https://github.com/cpgo/rails-mini-profiler/commit/db62984cf306b94db4c97808f303b0d3959b4afd))
* badge enabled and config ([#44](https://github.com/cpgo/rails-mini-profiler/issues/44)) ([abf9487](https://github.com/cpgo/rails-mini-profiler/commit/abf948711dcb1d82cbc02f342c2997d4b3c2e6d4))
* cast json column to text on PostgreSQL ([#37](https://github.com/cpgo/rails-mini-profiler/issues/37)) ([76d6ec2](https://github.com/cpgo/rails-mini-profiler/commit/76d6ec209fb1f6a04e3e46e3c7d1f3c6ed369fdf))
* deprecated autoloading, fixes [#110](https://github.com/cpgo/rails-mini-profiler/issues/110) ([253a6e9](https://github.com/cpgo/rails-mini-profiler/commit/253a6e9384047b06910f5b439c4b1a7354bfcfaa))
* display milliseconds, matching given labels ([#127](https://github.com/cpgo/rails-mini-profiler/issues/127)) ([6f4e7b7](https://github.com/cpgo/rails-mini-profiler/commit/6f4e7b762e30a11b027cd3fcdbb799ae9707b4ec))
* do not profile actioncable and asset paths ([#65](https://github.com/cpgo/rails-mini-profiler/issues/65)) ([72a1b06](https://github.com/cpgo/rails-mini-profiler/commit/72a1b069b4fddedc81b40ce6b9528ea7b1852279))
* fixes [#1](https://github.com/cpgo/rails-mini-profiler/issues/1) ([851148c](https://github.com/cpgo/rails-mini-profiler/commit/851148cd445f3ebb335c350b3f9a301240cc2831))
* fixes [#6](https://github.com/cpgo/rails-mini-profiler/issues/6) ([537a2d3](https://github.com/cpgo/rails-mini-profiler/commit/537a2d32c991d8f1b75c4393f3d36078010e2585))
* handle non-sprockets apps, fixes [#55](https://github.com/cpgo/rails-mini-profiler/issues/55) ([#57](https://github.com/cpgo/rails-mini-profiler/issues/57)) ([a80dbad](https://github.com/cpgo/rails-mini-profiler/commit/a80dbad6505a5ad1ae8c737f80f586a3e5a7b10e))
* improve error handling for non-webpack setups ([9541976](https://github.com/cpgo/rails-mini-profiler/commit/954197601531bd9bd3704db2c6a463e69e5b5819))
* improve robustness when saving profiled requests, fixes [#86](https://github.com/cpgo/rails-mini-profiler/issues/86) ([#118](https://github.com/cpgo/rails-mini-profiler/issues/118)) ([8781898](https://github.com/cpgo/rails-mini-profiler/commit/87818981d6af08c56729695def04d7232c00bfcd))
* improve storage configuration and docs, fixes [#27](https://github.com/cpgo/rails-mini-profiler/issues/27) ([#28](https://github.com/cpgo/rails-mini-profiler/issues/28)) ([68f1869](https://github.com/cpgo/rails-mini-profiler/commit/68f18690b4f805f6826a5cacea60cd411089bc3e))
* limit vendor folder, fixes [#33](https://github.com/cpgo/rails-mini-profiler/issues/33) ([e9facf4](https://github.com/cpgo/rails-mini-profiler/commit/e9facf4c583a4742b162b9da177d443ef11adf08))
* no method error for flamegraph, fixes [#20](https://github.com/cpgo/rails-mini-profiler/issues/20) ([0cfc531](https://github.com/cpgo/rails-mini-profiler/commit/0cfc531865ffc3a0086dc4d8671c4ca766c89481))
* package flamegraph assets with the gem, fixes [#21](https://github.com/cpgo/rails-mini-profiler/issues/21) ([a4620c2](https://github.com/cpgo/rails-mini-profiler/commit/a4620c2d912f11fa7fefc6d2b5b36d97789479e3))
* production profiling authentication, fixes [#93](https://github.com/cpgo/rails-mini-profiler/issues/93) ([#98](https://github.com/cpgo/rails-mini-profiler/issues/98)) ([98f515b](https://github.com/cpgo/rails-mini-profiler/commit/98f515b8519b88cb2383b22e5cd5762ccf831cdb))
* response without body, see [#115](https://github.com/cpgo/rails-mini-profiler/issues/115) ([#116](https://github.com/cpgo/rails-mini-profiler/issues/116)) ([baad01f](https://github.com/cpgo/rails-mini-profiler/commit/baad01f4009a91353577c09c48a2a64b8e2b3227))
* revert internalize external assets ([8719c0b](https://github.com/cpgo/rails-mini-profiler/commit/8719c0b8bcb0babd42d322969fbbd5bbcdd9abeb))
* sanitize null bytes in request body ([#173](https://github.com/cpgo/rails-mini-profiler/issues/173)) ([12c8358](https://github.com/cpgo/rails-mini-profiler/commit/12c8358c2ced76084d38e750d750732417070e01))
* sanitize response body with null bytes ([#178](https://github.com/cpgo/rails-mini-profiler/issues/178)) ([98ee2e3](https://github.com/cpgo/rails-mini-profiler/commit/98ee2e3608562f0628b4653cc9f4b1b489544bc8))
* use event.duration directly ([7968965](https://github.com/cpgo/rails-mini-profiler/commit/7968965d3c234746d0de2c2b407fecfb524aa05d))


### Miscellaneous

* add bundler binstubs to remove bundle exec ([1c4178c](https://github.com/cpgo/rails-mini-profiler/commit/1c4178c76e94fa764e0f4d2bad81348a719f5d68))
* add dependabot ([76b09ec](https://github.com/cpgo/rails-mini-profiler/commit/76b09ec21653f9df799ca9b45b2a09d611be26a4))
* add javascript/css tooling ([b201e28](https://github.com/cpgo/rails-mini-profiler/commit/b201e28230627338e90a093b16bf02e6a59ee551))
* Add release workflow ([2c64b27](https://github.com/cpgo/rails-mini-profiler/commit/2c64b27eeb98d9a9bf28b4afbe4e7a5c736e4b2f))
* add speedscope update task ([a64119b](https://github.com/cpgo/rails-mini-profiler/commit/a64119b978a9806fa378cb958116fa909a107032))
* add upgrade notice to readme ([0898373](https://github.com/cpgo/rails-mini-profiler/commit/0898373e655bf5745a64bd38dd67c56731ec03a5))
* allow up-to-date pagy versions ([b6d7c62](https://github.com/cpgo/rails-mini-profiler/commit/b6d7c62459d6b95add831464ad3fefc997b8c239))
* bump version ([2602565](https://github.com/cpgo/rails-mini-profiler/commit/2602565a211bf169786f488376eb507a67623821))
* change coverage path ([eeb1891](https://github.com/cpgo/rails-mini-profiler/commit/eeb18914302763003fbc8c3bd0fae55d036e9215))
* cleanup gems and gemspec ([2a3f196](https://github.com/cpgo/rails-mini-profiler/commit/2a3f196938230ad6f10b03aa8e460b456bb03b10))
* fix api only note formatting ([36e71b3](https://github.com/cpgo/rails-mini-profiler/commit/36e71b3858c4d7c6d0556d8ec66617cdaec8e2b1))
* fix contributing ([da83e62](https://github.com/cpgo/rails-mini-profiler/commit/da83e62d7e44fab998b13f2682a070081731c7c3))
* fix release ([fb53e66](https://github.com/cpgo/rails-mini-profiler/commit/fb53e6646599039400926d22edd09cdfb4c2f398))
* fix rubocop issues ([272e9da](https://github.com/cpgo/rails-mini-profiler/commit/272e9dacb366b25abbd2c7041dccfe9d2c41eb1e))
* fix updating version file ([c70002c](https://github.com/cpgo/rails-mini-profiler/commit/c70002cb8bfe63259430053fcb0463a97be19223))
* fix version ([9452a87](https://github.com/cpgo/rails-mini-profiler/commit/9452a87b0143c2ce7d0e0c1320f1d17e847c3547))
* improve code documentation, fixes [#11](https://github.com/cpgo/rails-mini-profiler/issues/11) ([#24](https://github.com/cpgo/rails-mini-profiler/issues/24)) ([6029fbf](https://github.com/cpgo/rails-mini-profiler/commit/6029fbfba8a4fc374feb5cc302a495f9e9a1aabd))
* improve docs, small css tweaks ([176d06a](https://github.com/cpgo/rails-mini-profiler/commit/176d06ad082ceac70924a43afb945436a3033e54))
* Improve readme ([419322c](https://github.com/cpgo/rails-mini-profiler/commit/419322c128929917c6f53fa333008558ffef8911))
* improve trace list styling ([7c9e978](https://github.com/cpgo/rails-mini-profiler/commit/7c9e9780dfcbf4d8f821d52a67514a2925a808f1))
* internalize external assets, fixes [#17](https://github.com/cpgo/rails-mini-profiler/issues/17) ([d6b7aac](https://github.com/cpgo/rails-mini-profiler/commit/d6b7aac1057b0a40c1aba82d0934d2a2bdf591c5))
* **main:** release 0.7.1 ([#111](https://github.com/cpgo/rails-mini-profiler/issues/111)) ([a47f470](https://github.com/cpgo/rails-mini-profiler/commit/a47f4705fa8e55c1d9d6f4436903346b7c3da37f))
* **main:** release 0.7.2 ([#147](https://github.com/cpgo/rails-mini-profiler/issues/147)) ([9b4b322](https://github.com/cpgo/rails-mini-profiler/commit/9b4b32211f8164f6f41a26ede106c1954aed481f))
* **main:** release 0.7.3 ([#155](https://github.com/cpgo/rails-mini-profiler/issues/155)) ([46eccd6](https://github.com/cpgo/rails-mini-profiler/commit/46eccd66adb277466dd776d2fd9d8a4b75550597))
* make coverage optional ([e364337](https://github.com/cpgo/rails-mini-profiler/commit/e3643377373b92e73821e5574e365cd73df2e4fb))
* make Rails 7 default development version ([#129](https://github.com/cpgo/rails-mini-profiler/issues/129)) ([5e78c83](https://github.com/cpgo/rails-mini-profiler/commit/5e78c83cf6941d9f2ed9ccf7951a8ccea2c62510))
* modify gemspec ([b63e768](https://github.com/cpgo/rails-mini-profiler/commit/b63e768cff5f3670977468cc9d7483b5cd772283))
* modularize tracers ([#112](https://github.com/cpgo/rails-mini-profiler/issues/112)) ([add2ec4](https://github.com/cpgo/rails-mini-profiler/commit/add2ec4647609f442bc4c78b68524bfacf617738))
* optionally force using asset pipeline ([aedc218](https://github.com/cpgo/rails-mini-profiler/commit/aedc218a34a0b92bb7f1de386bb74877738500a4))
* post release 0.4.0 ([b856072](https://github.com/cpgo/rails-mini-profiler/commit/b85607271543bbafc6afd399f6a65657363d5adb))
* post-release .. ([80842e6](https://github.com/cpgo/rails-mini-profiler/commit/80842e6fb7038b31b770de113d766b2e97d1530d))
* post-release 0.6.0 ([9626672](https://github.com/cpgo/rails-mini-profiler/commit/9626672e9a86e5d335cc89263041ccb8db503c7a))
* post-release 0.7.0 ([da80f06](https://github.com/cpgo/rails-mini-profiler/commit/da80f06509303e12a9ea74e5befadd1274893302))
* post-release 0.7.1 ([82ecb6b](https://github.com/cpgo/rails-mini-profiler/commit/82ecb6b429f9b944dbc48596dc19578998149d9b))
* post-release 0.7.2 ([7a34f5d](https://github.com/cpgo/rails-mini-profiler/commit/7a34f5de1567bd63f984e7e9a962422bd29c7f0b))
* post-release 0.7.3 ([482b2b0](https://github.com/cpgo/rails-mini-profiler/commit/482b2b0f7cb24dc178283d62fcd266222af48c53))
* release 0.1.1 ([0cc2bdc](https://github.com/cpgo/rails-mini-profiler/commit/0cc2bdccf35943d9ca7ad7461aebadf6e841a746))
* release 0.1.2 ([#16](https://github.com/cpgo/rails-mini-profiler/issues/16)) ([e4e5317](https://github.com/cpgo/rails-mini-profiler/commit/e4e53172dbdb10a94c0dab3608643d1927d5ce97))
* release 0.1.3 ([#22](https://github.com/cpgo/rails-mini-profiler/issues/22)) ([6310cef](https://github.com/cpgo/rails-mini-profiler/commit/6310cef4ec9bb80b4f4db3cae0b87d101b1b8cd9))
* release 0.2.0 ([#25](https://github.com/cpgo/rails-mini-profiler/issues/25)) ([bba87a0](https://github.com/cpgo/rails-mini-profiler/commit/bba87a0d1b9fea799ac1ff2bd97e7b13e019dff8))
* release 0.2.1 ([#34](https://github.com/cpgo/rails-mini-profiler/issues/34)) ([2716c73](https://github.com/cpgo/rails-mini-profiler/commit/2716c73a896cf4b0d7b23d05407cbcb5de56aa2e))
* release 0.3.0 ([#40](https://github.com/cpgo/rails-mini-profiler/issues/40)) ([cb2a66f](https://github.com/cpgo/rails-mini-profiler/commit/cb2a66fc345dcbf30aa6716b7944088ca5654261))
* release 0.4.0 ([#50](https://github.com/cpgo/rails-mini-profiler/issues/50)) ([b837f59](https://github.com/cpgo/rails-mini-profiler/commit/b837f5983567016afdd4ac455070c21ea7547153))
* release 0.5.0 ([#62](https://github.com/cpgo/rails-mini-profiler/issues/62)) ([fa76b75](https://github.com/cpgo/rails-mini-profiler/commit/fa76b7594e934e3ec0b07f64c038cffa1b1630f8))
* release 0.6.0 ([72a0224](https://github.com/cpgo/rails-mini-profiler/commit/72a0224b9675bfe107bc7e2c97ab1f4054b4e724))
* release 0.7.0 ([6a2d838](https://github.com/cpgo/rails-mini-profiler/commit/6a2d8384cbafd8b3324da1c3bde951b202f6ba0a))
* remove built-in gemfile helper ([0e888c2](https://github.com/cpgo/rails-mini-profiler/commit/0e888c25ce8d2a5c048a85ddda35f49d3e1045bc))
* remove todo, update stale ([3e250ad](https://github.com/cpgo/rails-mini-profiler/commit/3e250ad3c1f8f5678f40ee3ff9fd957af4ec4ac5))
* request/response wrappers ([#117](https://github.com/cpgo/rails-mini-profiler/issues/117)) ([28def20](https://github.com/cpgo/rails-mini-profiler/commit/28def20213bbb534493b69ee4c8baeeb907354ff))
* small readme improvements ([feca1bf](https://github.com/cpgo/rails-mini-profiler/commit/feca1bfc7b2f438261b707470c3664686be1b6b4))
* try update package name ([40fd81b](https://github.com/cpgo/rails-mini-profiler/commit/40fd81b73620a18edfbe45aa2ad1c2c44fda1c02))
* update codelimate action ([6a86568](https://github.com/cpgo/rails-mini-profiler/commit/6a86568ed7edb4cda4126e36d93af44d71712cf0))
* update commitlint config ([7e45bba](https://github.com/cpgo/rails-mini-profiler/commit/7e45bba5b60a579822445025000ae9625c41e053))
* update contributing ([069f59f](https://github.com/cpgo/rails-mini-profiler/commit/069f59f51fae6898145265249f5ebc7e5f7437d8))
* update dependabot alerts ([e0ceb9b](https://github.com/cpgo/rails-mini-profiler/commit/e0ceb9bd926471705f2bb0239f9eebfd51968c2d))
* update FEATURE_REQUEST.md ([45f26bb](https://github.com/cpgo/rails-mini-profiler/commit/45f26bb26810c0dbd571f5c79370a4bd637e8137))
* update gemfile ([f8ca17a](https://github.com/cpgo/rails-mini-profiler/commit/f8ca17af8faa897dd76f64e1cfa6b3d957f55521))
* update gemspec ([98ead88](https://github.com/cpgo/rails-mini-profiler/commit/98ead8829fb754033f67e7e425329535590808ac))
* update gemspec ([b4dec89](https://github.com/cpgo/rails-mini-profiler/commit/b4dec89809801e0052a1c79fc956bbfc9acc91b4))
* update main workflow ([bbb861d](https://github.com/cpgo/rails-mini-profiler/commit/bbb861ddbe9f38f162e825ad61a16ff0697749dc))
* update node dependencies ([2196fc6](https://github.com/cpgo/rails-mini-profiler/commit/2196fc61857440ed954725e7ccc4e253bc76795e))
* Update PR workflow ([6c48234](https://github.com/cpgo/rails-mini-profiler/commit/6c48234f102f7778ff74a14a8650899a96f17da0))
* update readme ([b1cac7a](https://github.com/cpgo/rails-mini-profiler/commit/b1cac7a8339b72aee3ed9d4fd2e1559a61aaa8d3))
* Update readme ([bd323b1](https://github.com/cpgo/rails-mini-profiler/commit/bd323b197a6a4b6f945f9b2d4c6ea3406a067676))
* update readme to mention requiring stackprof ([#26](https://github.com/cpgo/rails-mini-profiler/issues/26)) ([9e41f4c](https://github.com/cpgo/rails-mini-profiler/commit/9e41f4cf36a0a7ca33a4ceacbc53fa74e8dc5df3))
* update release info ([2a12afd](https://github.com/cpgo/rails-mini-profiler/commit/2a12afd3d65183c9f90037279ae59464e3ef201c))
* update speedscope ([#174](https://github.com/cpgo/rails-mini-profiler/issues/174)) ([3352624](https://github.com/cpgo/rails-mini-profiler/commit/3352624668dd5e914c44c91971a29dd8b5b7f9b9))
* update stale.yml ([a8ef14e](https://github.com/cpgo/rails-mini-profiler/commit/a8ef14e028e031d2ac88132a21a6f3ef7f515a59))
* Update workflows ([675e6f1](https://github.com/cpgo/rails-mini-profiler/commit/675e6f1d416c3ef765f5b4b62da4194098ae5669))
* upgrade to stimulus 3.0 ([042c77b](https://github.com/cpgo/rails-mini-profiler/commit/042c77b0b254914121f79909c0baba56a40c3c25))

## [0.7.3](https://github.com/hschne/rails-mini-profiler/compare/v0.7.2...v0.7.3) (2022-10-23)


### Bug Fixes

* sanitize null bytes in request body ([#173](https://github.com/hschne/rails-mini-profiler/issues/173)) ([12c8358](https://github.com/hschne/rails-mini-profiler/commit/12c8358c2ced76084d38e750d750732417070e01))


### Miscellaneous

* post-release 0.7.2 ([7a34f5d](https://github.com/hschne/rails-mini-profiler/commit/7a34f5de1567bd63f984e7e9a962422bd29c7f0b))
* update speedscope ([#174](https://github.com/hschne/rails-mini-profiler/issues/174)) ([3352624](https://github.com/hschne/rails-mini-profiler/commit/3352624668dd5e914c44c91971a29dd8b5b7f9b9))

## [0.7.2](https://github.com/hschne/rails-mini-profiler/compare/v0.7.1...v0.7.2) (2022-06-13)


### Bug Fixes

* add charset to table definitions ([#150](https://github.com/hschne/rails-mini-profiler/issues/150)) ([1dab8a8](https://github.com/hschne/rails-mini-profiler/commit/1dab8a873ce2908af5f87039d300d85765a9cd29))
* display milliseconds, matching given labels ([#127](https://github.com/hschne/rails-mini-profiler/issues/127)) ([6f4e7b7](https://github.com/hschne/rails-mini-profiler/commit/6f4e7b762e30a11b027cd3fcdbb799ae9707b4ec))
* use event.duration directly ([7968965](https://github.com/hschne/rails-mini-profiler/commit/7968965d3c234746d0de2c2b407fecfb524aa05d))


### Miscellaneous

* add bundler binstubs to remove bundle exec ([1c4178c](https://github.com/hschne/rails-mini-profiler/commit/1c4178c76e94fa764e0f4d2bad81348a719f5d68))
* make Rails 7 default development version ([#129](https://github.com/hschne/rails-mini-profiler/issues/129)) ([5e78c83](https://github.com/hschne/rails-mini-profiler/commit/5e78c83cf6941d9f2ed9ccf7951a8ccea2c62510))
* post-release 0.7.1 ([82ecb6b](https://github.com/hschne/rails-mini-profiler/commit/82ecb6b429f9b944dbc48596dc19578998149d9b))
* remove built-in gemfile helper ([0e888c2](https://github.com/hschne/rails-mini-profiler/commit/0e888c25ce8d2a5c048a85ddda35f49d3e1045bc))
* update commitlint config ([7e45bba](https://github.com/hschne/rails-mini-profiler/commit/7e45bba5b60a579822445025000ae9625c41e053))

### [0.7.1](https://github.com/hschne/rails-mini-profiler/compare/v0.7.0...v0.7.1) (2022-01-30)


### Bug Fixes

* deprecated autoloading, fixes [#110](https://github.com/hschne/rails-mini-profiler/issues/110) ([253a6e9](https://github.com/hschne/rails-mini-profiler/commit/253a6e9384047b06910f5b439c4b1a7354bfcfaa))
* improve robustness when saving profiled requests, fixes [#86](https://github.com/hschne/rails-mini-profiler/issues/86) ([#118](https://github.com/hschne/rails-mini-profiler/issues/118)) ([8781898](https://github.com/hschne/rails-mini-profiler/commit/87818981d6af08c56729695def04d7232c00bfcd))
* response without body, see [#115](https://github.com/hschne/rails-mini-profiler/issues/115) ([#116](https://github.com/hschne/rails-mini-profiler/issues/116)) ([baad01f](https://github.com/hschne/rails-mini-profiler/commit/baad01f4009a91353577c09c48a2a64b8e2b3227))


### Miscellaneous

* fix contributing ([da83e62](https://github.com/hschne/rails-mini-profiler/commit/da83e62d7e44fab998b13f2682a070081731c7c3))
* fix updating version file ([c70002c](https://github.com/hschne/rails-mini-profiler/commit/c70002cb8bfe63259430053fcb0463a97be19223))
* fix version ([9452a87](https://github.com/hschne/rails-mini-profiler/commit/9452a87b0143c2ce7d0e0c1320f1d17e847c3547))
* modularize tracers ([#112](https://github.com/hschne/rails-mini-profiler/issues/112)) ([add2ec4](https://github.com/hschne/rails-mini-profiler/commit/add2ec4647609f442bc4c78b68524bfacf617738))
* post-release 0.7.0 ([da80f06](https://github.com/hschne/rails-mini-profiler/commit/da80f06509303e12a9ea74e5befadd1274893302))
* request/response wrappers ([#117](https://github.com/hschne/rails-mini-profiler/issues/117)) ([28def20](https://github.com/hschne/rails-mini-profiler/commit/28def20213bbb534493b69ee4c8baeeb907354ff))
* update release info ([2a12afd](https://github.com/hschne/rails-mini-profiler/commit/2a12afd3d65183c9f90037279ae59464e3ef201c))

## [0.7.0](https://www.github.com/hschne/rails-mini-profiler/compare/v0.6.0...v0.7.0) (2021-11-27)


### Features

* add trace filtering, closes [#67](https://www.github.com/hschne/rails-mini-profiler/issues/67) ([2722f92](https://www.github.com/hschne/rails-mini-profiler/commit/2722f92b8c7dad14b89a64716b28dc6a960b0992))


### Bug Fixes

* authentication thread issue, fixes [#99](https://www.github.com/hschne/rails-mini-profiler/issues/99) ([db62984](https://www.github.com/hschne/rails-mini-profiler/commit/db62984cf306b94db4c97808f303b0d3959b4afd))
* production profiling authentication, fixes [#93](https://www.github.com/hschne/rails-mini-profiler/issues/93) ([#98](https://www.github.com/hschne/rails-mini-profiler/issues/98)) ([98f515b](https://www.github.com/hschne/rails-mini-profiler/commit/98f515b8519b88cb2383b22e5cd5762ccf831cdb))

## [0.6.0](https://www.github.com/hschne/rails-mini-profiler/compare/v0.5.0...v0.6.0) (2021-10-10)


### Features

* add copy button, fixes [#69](https://www.github.com/hschne/rails-mini-profiler/issues/69) ([9a91a3f](https://www.github.com/hschne/rails-mini-profiler/commit/9a91a3f70b35bc7bc96cb3a56116aa35c0d9d8a3))


### Bug Fixes

* do not profile actioncable and asset paths ([#65](https://www.github.com/hschne/rails-mini-profiler/issues/65)) ([72a1b06](https://www.github.com/hschne/rails-mini-profiler/commit/72a1b069b4fddedc81b40ce6b9528ea7b1852279))

## [0.5.0](https://www.github.com/hschne/rails-mini-profiler/compare/v0.4.0...v0.5.0) (2021-09-12)


### Features

* add request table filters, fixes [#53](https://www.github.com/hschne/rails-mini-profiler/issues/53) ([#61](https://www.github.com/hschne/rails-mini-profiler/issues/61)) ([2e86671](https://www.github.com/hschne/rails-mini-profiler/commit/2e86671c58bf3a451c5a813495693aec782725c8))
* add sequel trace filtering ([#64](https://www.github.com/hschne/rails-mini-profiler/issues/64)) ([007716e](https://www.github.com/hschne/rails-mini-profiler/commit/007716e8279d39511b8652f05f3cbedc723d09bb))
* improve checkbox behaviour ([4ffe202](https://www.github.com/hschne/rails-mini-profiler/commit/4ffe202149f48c73b20742094c84d310157baccf))


### Bug Fixes

* handle non-sprockets apps, fixes [#55](https://www.github.com/hschne/rails-mini-profiler/issues/55) ([#57](https://www.github.com/hschne/rails-mini-profiler/issues/57)) ([a80dbad](https://www.github.com/hschne/rails-mini-profiler/commit/a80dbad6505a5ad1ae8c737f80f586a3e5a7b10e))

## [0.4.0](https://www.github.com/hschne/rails-mini-profiler/compare/v0.3.0...v0.4.0) (2021-08-28)


### Features

* add support for older ruby versions, fixes [#48](https://www.github.com/hschne/rails-mini-profiler/issues/48) ([#49](https://www.github.com/hschne/rails-mini-profiler/issues/49)) ([97061c4](https://www.github.com/hschne/rails-mini-profiler/commit/97061c478da59f02975d88e2883e4a0e3bad4ef5))
* add support for rails 6.0, fixes [#52](https://www.github.com/hschne/rails-mini-profiler/issues/52) ([#51](https://www.github.com/hschne/rails-mini-profiler/issues/51)) ([63371f6](https://www.github.com/hschne/rails-mini-profiler/commit/63371f6558cb6009ff73a56a7f0e0fa3bccc46cd))


### Bug Fixes

* badge enabled and config ([#44](https://www.github.com/hschne/rails-mini-profiler/issues/44)) ([abf9487](https://www.github.com/hschne/rails-mini-profiler/commit/abf948711dcb1d82cbc02f342c2997d4b3c2e6d4))
* improve error handling for non-webpack setups ([9541976](https://www.github.com/hschne/rails-mini-profiler/commit/954197601531bd9bd3704db2c6a463e69e5b5819))

## [0.3.0](https://www.github.com/hschne/rails-mini-profiler/compare/v0.2.1...v0.3.0) (2021-08-21)


### Features

* add webpacker support, see [#8](https://www.github.com/hschne/rails-mini-profiler/issues/8) ([#39](https://www.github.com/hschne/rails-mini-profiler/issues/39)) ([a0f17f3](https://www.github.com/hschne/rails-mini-profiler/commit/a0f17f3088307474d7428fc8487c51fb2f0746cf))


### Bug Fixes

* cast json column to text on PostgreSQL ([#37](https://www.github.com/hschne/rails-mini-profiler/issues/37)) ([76d6ec2](https://www.github.com/hschne/rails-mini-profiler/commit/76d6ec209fb1f6a04e3e46e3c7d1f3c6ed369fdf))

### [0.2.1](https://www.github.com/hschne/rails-mini-profiler/compare/v0.2.0...v0.2.1) (2021-08-12)


### Bug Fixes

* limit vendor folder, fixes [#33](https://www.github.com/hschne/rails-mini-profiler/issues/33) ([e9facf4](https://www.github.com/hschne/rails-mini-profiler/commit/e9facf4c583a4742b162b9da177d443ef11adf08))

## [0.2.0](https://www.github.com/hschne/rails-mini-profiler/compare/v0.1.3...v0.2.0) (2021-08-12)


### Features

* serve assets locally, fixes [#17](https://www.github.com/hschne/rails-mini-profiler/issues/17) ([6f62d55](https://www.github.com/hschne/rails-mini-profiler/commit/6f62d5584f934e7e61fd0735c4ab00718f1be6c3))


### Bug Fixes

* improve storage configuration and docs, fixes [#27](https://www.github.com/hschne/rails-mini-profiler/issues/27) ([#28](https://www.github.com/hschne/rails-mini-profiler/issues/28)) ([68f1869](https://www.github.com/hschne/rails-mini-profiler/commit/68f18690b4f805f6826a5cacea60cd411089bc3e))

### [0.1.3](https://www.github.com/hschne/rails-mini-profiler/compare/v0.1.2...v0.1.3) (2021-08-02)


### Bug Fixes

* revert internalize external assets ([8719c0b](https://www.github.com/hschne/rails-mini-profiler/commit/8719c0b8bcb0babd42d322969fbbd5bbcdd9abeb))

### [0.1.2](https://www.github.com/hschne/rails-mini-profiler/compare/v0.1.1...v0.1.2) (2021-08-02)


### Bug Fixes

* add better support for api-only applications, fixes [#14](https://www.github.com/hschne/rails-mini-profiler/issues/14) ([8745c57](https://www.github.com/hschne/rails-mini-profiler/commit/8745c57f37218b24e097c1b1b323b7aeb52d03af))
* no method error for flamegraph, fixes [#20](https://www.github.com/hschne/rails-mini-profiler/issues/20) ([0cfc531](https://www.github.com/hschne/rails-mini-profiler/commit/0cfc531865ffc3a0086dc4d8671c4ca766c89481))
* package flamegraph assets with the gem, fixes [#21](https://www.github.com/hschne/rails-mini-profiler/issues/21) ([a4620c2](https://www.github.com/hschne/rails-mini-profiler/commit/a4620c2d912f11fa7fefc6d2b5b36d97789479e3))

### [0.1.1](https://www.github.com/hschne/rails-mini-profiler/compare/v0.1.0...v0.1.1) (2021-07-31)


### Bug Fixes

* fixes [#1](https://www.github.com/hschne/rails-mini-profiler/issues/1) ([851148c](https://www.github.com/hschne/rails-mini-profiler/commit/851148cd445f3ebb335c350b3f9a301240cc2831))
* fixes [#6](https://www.github.com/hschne/rails-mini-profiler/issues/6) ([537a2d3](https://www.github.com/hschne/rails-mini-profiler/commit/537a2d32c991d8f1b75c4393f3d36078010e2585))
