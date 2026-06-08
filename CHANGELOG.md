# Changelog

## [0.5.10](https://github.com/sporkd/mise-completions-sync/compare/v0.5.9...v0.5.10) (2026-06-08)


### Features

* add new tools ([#40](https://github.com/sporkd/mise-completions-sync/issues/40)) ([4617152](https://github.com/sporkd/mise-completions-sync/commit/461715210f3123aac1ec2471ecb334c0d232808a))
* add prek completion support ([#48](https://github.com/sporkd/mise-completions-sync/issues/48)) ([b2bb8a9](https://github.com/sporkd/mise-completions-sync/commit/b2bb8a982e35c8bf5d08ad3cf15538fa2d9c2510)), closes [#36](https://github.com/sporkd/mise-completions-sync/issues/36)
* add release infrastructure and expand registry ([#5](https://github.com/sporkd/mise-completions-sync/issues/5)) ([e36dd40](https://github.com/sporkd/mise-completions-sync/commit/e36dd4046be63cd8b72ed1697601907e473bda4a))
* add self-completion subcommand (closes [#75](https://github.com/sporkd/mise-completions-sync/issues/75)) ([#94](https://github.com/sporkd/mise-completions-sync/issues/94)) ([8521f7c](https://github.com/sporkd/mise-completions-sync/commit/8521f7c1f50605085ff3c852469dbe4dc9169a57))
* add support for tree-sitter ([#77](https://github.com/sporkd/mise-completions-sync/issues/77)) ([afd6605](https://github.com/sporkd/mise-completions-sync/commit/afd660584746e717fdaab9aa7238ce2e571ab305))
* add support for usage ([#84](https://github.com/sporkd/mise-completions-sync/issues/84)) ([4de608d](https://github.com/sporkd/mise-completions-sync/commit/4de608df1bed21bb11c58f7539d933d9e2490ca6))
* add talosctl ([#95](https://github.com/sporkd/mise-completions-sync/issues/95)) ([a43f446](https://github.com/sporkd/mise-completions-sync/commit/a43f446f137f76690837bd0e17a040e9f9107d4d))
* add worktrees directory to gitignore ([#15](https://github.com/sporkd/mise-completions-sync/issues/15)) ([c43f8ae](https://github.com/sporkd/mise-completions-sync/commit/c43f8aee52cc323ae6a75305ff13c18025a10c44))
* allow overriding output dirs with ENV vars ([#52](https://github.com/sporkd/mise-completions-sync/issues/52)) ([fc423c9](https://github.com/sporkd/mise-completions-sync/commit/fc423c9bd3c610efc69bf97032eaeacb8a047536))
* **docs:** convert from mdBook to MkDocs with Material theme ([#18](https://github.com/sporkd/mise-completions-sync/issues/18)) ([1075920](https://github.com/sporkd/mise-completions-sync/commit/1075920b4285c1373a74aafcd5dafbb0fc50beb1))
* **docs:** enhance tool documentation with metadata and status tracking ([#23](https://github.com/sporkd/mise-completions-sync/issues/23)) ([8159951](https://github.com/sporkd/mise-completions-sync/commit/81599513a5e3f689e6b52d09ed0530ecc7dd68bb))
* initial implementation of mise-completions-sync ([818b760](https://github.com/sporkd/mise-completions-sync/commit/818b760da1cc10b19e2fe72a4b7a970988103b4b))
* **registry:** pattern-based format with schema versioning ([#17](https://github.com/sporkd/mise-completions-sync/issues/17)) ([e7e72cc](https://github.com/sporkd/mise-completions-sync/commit/e7e72cc86fe1a6ee508dfda625156443d3b3967b))
* support tools from alternative backends ([#41](https://github.com/sporkd/mise-completions-sync/issues/41)) ([6e39bc0](https://github.com/sporkd/mise-completions-sync/commit/6e39bc08bf30cf8aba8124591b0f957d10fb4b17))
* **sync-with-flags:** Allow flags --global --local --current ([e0549e0](https://github.com/sporkd/mise-completions-sync/commit/e0549e036998cc2742de4ba6de6f7c77ae0ce482))


### Bug Fixes

* bundle dependency and registry updates from recent merges ([#59](https://github.com/sporkd/mise-completions-sync/issues/59)) ([98e9409](https://github.com/sporkd/mise-completions-sync/commit/98e9409a7df5d32810ad0d41e58fb046a6926567))
* **ci:** chain release workflows and always bump patch ([#9](https://github.com/sporkd/mise-completions-sync/issues/9)) ([415f670](https://github.com/sporkd/mise-completions-sync/commit/415f670336f716cfe30c65a3e4174d9e1c15c71d))
* **ci:** remove auto-generation of tools docs from workflow ([#28](https://github.com/sporkd/mise-completions-sync/issues/28)) ([9cdc1af](https://github.com/sporkd/mise-completions-sync/commit/9cdc1afe9a5c0fb1d0d3b6054fb9b7d131a58ae2))
* **ci:** remove auto-generation of tools docs from workflow ([#29](https://github.com/sporkd/mise-completions-sync/issues/29)) ([25d873b](https://github.com/sporkd/mise-completions-sync/commit/25d873b7ea502e9f3cb21a0e21120b88e906060b))
* **ci:** restore x86_64-unknown-linux-musl release binary ([#90](https://github.com/sporkd/mise-completions-sync/issues/90)) ([0dccee5](https://github.com/sporkd/mise-completions-sync/commit/0dccee5f90df29ac58825515596ed72028f5f449)), closes [#89](https://github.com/sporkd/mise-completions-sync/issues/89)
* correct hook configuration instructions ([f7ae9f7](https://github.com/sporkd/mise-completions-sync/commit/f7ae9f7fa4d3be90d4a6acf9fd2e92c5f5f16ace))
* **deps:** update rust crate dirs to v6 ([#2](https://github.com/sporkd/mise-completions-sync/issues/2)) ([d507a8c](https://github.com/sporkd/mise-completions-sync/commit/d507a8c10d7a51d283ce841f1beca70d1d2e1780))
* **deps:** update rust crate toml to 0.9 ([#1](https://github.com/sporkd/mise-completions-sync/issues/1)) ([612da68](https://github.com/sporkd/mise-completions-sync/commit/612da6830ce19d9d04fcf0cb3c4f139ca21a5113))
* **deps:** update rust crate toml to v1 ([#35](https://github.com/sporkd/mise-completions-sync/issues/35)) ([ea3241f](https://github.com/sporkd/mise-completions-sync/commit/ea3241fa003e8c5a60b0c70d07e22cb9f9de8239))
* **docs:** trigger rebuild on CHANGELOG changes and include in site ([#24](https://github.com/sporkd/mise-completions-sync/issues/24)) ([d1a5bd1](https://github.com/sporkd/mise-completions-sync/commit/d1a5bd1695f9a2d44b8e151475051b9df4918086))
* **generate-registry:** migrate from mise registry.toml to API endpoint ([#42](https://github.com/sporkd/mise-completions-sync/issues/42)) ([329a9b9](https://github.com/sporkd/mise-completions-sync/commit/329a9b97754df3e264ea9d47ce11bbe21a02406e))
* merge duplicate tests module in sync.rs ([#82](https://github.com/sporkd/mise-completions-sync/issues/82)) ([c469875](https://github.com/sporkd/mise-completions-sync/commit/c4698753d03a5216e3e7efa34c1bf3c107affe72))
* **registry:** remove fzf and zoxide (closes [#78](https://github.com/sporkd/mise-completions-sync/issues/78)) ([#96](https://github.com/sporkd/mise-completions-sync/issues/96)) ([8f3f1d2](https://github.com/sporkd/mise-completions-sync/commit/8f3f1d2471691472c898821e89b4286ca2f4b21c))
* **registry:** remove mkcert (closes [#50](https://github.com/sporkd/mise-completions-sync/issues/50)) ([#61](https://github.com/sporkd/mise-completions-sync/issues/61)) ([b588589](https://github.com/sporkd/mise-completions-sync/commit/b588589f06c413028438ec9faf367879f29c223b))
* **registry:** remove tools without completion support ([#14](https://github.com/sporkd/mise-completions-sync/issues/14)) ([7f3a0b5](https://github.com/sporkd/mise-completions-sync/commit/7f3a0b57bc084eebac2bba345bcaa892965c1165))
* **registry:** remove tools without completion support ([#21](https://github.com/sporkd/mise-completions-sync/issues/21)) ([4d5e7ba](https://github.com/sporkd/mise-completions-sync/commit/4d5e7ba585cd80b0b70eabc4890909999318295d))
* remove gcloud from registry ([#32](https://github.com/sporkd/mise-completions-sync/issues/32)) ([#33](https://github.com/sporkd/mise-completions-sync/issues/33)) ([fa296f6](https://github.com/sporkd/mise-completions-sync/commit/fa296f69e5812a0e83c081ec7431d02282681662))
* remove unused json import in generate-registry ([#47](https://github.com/sporkd/mise-completions-sync/issues/47)) ([d3e7c29](https://github.com/sporkd/mise-completions-sync/commit/d3e7c29a63751b203108bfa12884156ff5a03b5d))
* rename installed binary to misecompsync (closes [#79](https://github.com/sporkd/mise-completions-sync/issues/79)) ([#81](https://github.com/sporkd/mise-completions-sync/issues/81)) ([bd235ff](https://github.com/sporkd/mise-completions-sync/commit/bd235ffd075f86c6cc19ed0b011265a6d07612f9))
* **scripts:** handle missing mise in CI gracefully ([#26](https://github.com/sporkd/mise-completions-sync/issues/26)) ([70651da](https://github.com/sporkd/mise-completions-sync/commit/70651daf251e6248f6ff58812fb21f0dcd7c451c))
* use standard pattern for lefthook (closes [#86](https://github.com/sporkd/mise-completions-sync/issues/86)) ([#91](https://github.com/sporkd/mise-completions-sync/issues/91)) ([48b5a51](https://github.com/sporkd/mise-completions-sync/commit/48b5a5175f1d3e840a66a230a52338a987461f26))
* wrap completion commands with mise x for tool availability ([#12](https://github.com/sporkd/mise-completions-sync/issues/12)) ([32f58c5](https://github.com/sporkd/mise-completions-sync/commit/32f58c509744f7e91c4c805c6e69caf322418616))


### Miscellaneous Chores

* adapt CI and release configs for fork (develop branch) ([fbdd944](https://github.com/sporkd/mise-completions-sync/commit/fbdd944f6734bde016e36a5e1f49694b16d679f3))
* add MIT license file and attribution ([5fd151a](https://github.com/sporkd/mise-completions-sync/commit/5fd151afc2462fbccb846a93c4b60ec5d214c2b1))
* **deps:** update actions/checkout action to v6 ([#46](https://github.com/sporkd/mise-completions-sync/issues/46)) ([95608aa](https://github.com/sporkd/mise-completions-sync/commit/95608aab8eebc53976fd8fc842dc9781ebce29e0))
* **deps:** update actions/checkout action to v6 ([#7](https://github.com/sporkd/mise-completions-sync/issues/7)) ([5116fd7](https://github.com/sporkd/mise-completions-sync/commit/5116fd7528efd6e2c4ef039f7d2307dc208fd617))
* **deps:** update actions/deploy-pages action to v5 ([#37](https://github.com/sporkd/mise-completions-sync/issues/37)) ([d6ac839](https://github.com/sporkd/mise-completions-sync/commit/d6ac839dcfc5e9b52e75604123439f62e4becc11))
* **deps:** update actions/upload-pages-artifact action to v4 ([#8](https://github.com/sporkd/mise-completions-sync/issues/8)) ([c6b10c6](https://github.com/sporkd/mise-completions-sync/commit/c6b10c64f86f32acb4e04ab65a81060b8f48b80e))
* **deps:** update actions/upload-pages-artifact action to v5 ([#53](https://github.com/sporkd/mise-completions-sync/issues/53)) ([1c5d7c2](https://github.com/sporkd/mise-completions-sync/commit/1c5d7c28c7a64fa23e7157a4ab9b7f56830555a6))
* **deps:** update amannn/action-semantic-pull-request action to v6 ([#66](https://github.com/sporkd/mise-completions-sync/issues/66)) ([be5454f](https://github.com/sporkd/mise-completions-sync/commit/be5454f69cd32758b59275e990e5228b3af65c27))
* **deps:** update astral-sh/setup-uv action to v7 ([#11](https://github.com/sporkd/mise-completions-sync/issues/11)) ([fff3fed](https://github.com/sporkd/mise-completions-sync/commit/fff3fed7544247e00d5047b10cefbb416da8360f))
* **deps:** update astral-sh/setup-uv action to v8 ([#56](https://github.com/sporkd/mise-completions-sync/issues/56)) ([5e3256a](https://github.com/sporkd/mise-completions-sync/commit/5e3256a15876c3cda478a9a3e5fe010565309211))
* **deps:** update googleapis/release-please-action action to v5 ([#58](https://github.com/sporkd/mise-completions-sync/issues/58)) ([6759694](https://github.com/sporkd/mise-completions-sync/commit/6759694605d7ef629e705fb3bdb6e3f76db53b18))
* **deps:** update houseabsolute/actions-rust-cross action to v1 ([#57](https://github.com/sporkd/mise-completions-sync/issues/57)) ([39263f1](https://github.com/sporkd/mise-completions-sync/commit/39263f1178b87becb966d5aa8a50d1c2c3b20686))
* **deps:** update rust crate serde_json to v1.0.150 ([#87](https://github.com/sporkd/mise-completions-sync/issues/87)) ([2581de9](https://github.com/sporkd/mise-completions-sync/commit/2581de9137a55930358c7779a07d98122cf86d0a))
* **deps:** update rust dependencies ([#71](https://github.com/sporkd/mise-completions-sync/issues/71)) ([ba67f02](https://github.com/sporkd/mise-completions-sync/commit/ba67f02946eeb1815daa8d54e6b27d2dcd9964fe))
* **deps:** update softprops/action-gh-release action to v3 ([#51](https://github.com/sporkd/mise-completions-sync/issues/51)) ([f0ef251](https://github.com/sporkd/mise-completions-sync/commit/f0ef251c8617592084bfe1a3366a2ebe65ded492))
* **main:** release 0.2.0 ([#6](https://github.com/sporkd/mise-completions-sync/issues/6)) ([a1cf4ac](https://github.com/sporkd/mise-completions-sync/commit/a1cf4acc12796294b6d90ecf59e48e4c85bccf4e))
* **main:** release 0.2.1 ([#10](https://github.com/sporkd/mise-completions-sync/issues/10)) ([64bed79](https://github.com/sporkd/mise-completions-sync/commit/64bed791e823bf640bdf73f5f1c77a40f6a77fdd))
* **main:** release 0.2.2 ([#13](https://github.com/sporkd/mise-completions-sync/issues/13)) ([ddb0111](https://github.com/sporkd/mise-completions-sync/commit/ddb01110700c368b0ad0f1a26e17335bd7642ed3))
* **main:** release 0.3.0 ([#16](https://github.com/sporkd/mise-completions-sync/issues/16)) ([4a61812](https://github.com/sporkd/mise-completions-sync/commit/4a61812ea060494c7ad88378c49488751bd5834f))
* **main:** release 0.4.0 ([#22](https://github.com/sporkd/mise-completions-sync/issues/22)) ([14597c0](https://github.com/sporkd/mise-completions-sync/commit/14597c071369609039e49a51f88949a896eb3c17))
* **main:** release 0.4.1 ([#25](https://github.com/sporkd/mise-completions-sync/issues/25)) ([4e0ee2f](https://github.com/sporkd/mise-completions-sync/commit/4e0ee2f66a043756d802f69cebe5801bad2da182))
* **main:** release 0.4.2 ([#27](https://github.com/sporkd/mise-completions-sync/issues/27)) ([51b5fdf](https://github.com/sporkd/mise-completions-sync/commit/51b5fdf30c0c09d3234c850a03720d44264a43db))
* **main:** release 0.4.3 ([#30](https://github.com/sporkd/mise-completions-sync/issues/30)) ([89c3220](https://github.com/sporkd/mise-completions-sync/commit/89c3220fe807d6f1d45a55a98994fcbf1ff4cf6e))
* **main:** release 0.4.4 ([#34](https://github.com/sporkd/mise-completions-sync/issues/34)) ([369c297](https://github.com/sporkd/mise-completions-sync/commit/369c29725ebd2334e701bfbb9f4566499ee1eb61))
* **main:** release 0.5.0 ([#44](https://github.com/sporkd/mise-completions-sync/issues/44)) ([a8ee595](https://github.com/sporkd/mise-completions-sync/commit/a8ee5958ea16dcbf839d188719ea7665269b44c0))
* **main:** release 0.5.1 ([#60](https://github.com/sporkd/mise-completions-sync/issues/60)) ([78d192b](https://github.com/sporkd/mise-completions-sync/commit/78d192b8f206455b4ae681f94ec577db2ea17fdb))
* **main:** release 0.5.2 ([#65](https://github.com/sporkd/mise-completions-sync/issues/65)) ([7085602](https://github.com/sporkd/mise-completions-sync/commit/708560249fdb1d26ac53fc81d7ce63183257ba65))
* **main:** release 0.5.3 ([#68](https://github.com/sporkd/mise-completions-sync/issues/68)) ([f4e0b86](https://github.com/sporkd/mise-completions-sync/commit/f4e0b8625dfe1c3a6f026b463813cb7d698df5b2))
* **main:** release 0.5.4 ([#70](https://github.com/sporkd/mise-completions-sync/issues/70)) ([47b8811](https://github.com/sporkd/mise-completions-sync/commit/47b881185d7158aac68ba24d8f36d6a74c8355a0))
* **main:** release 0.5.5 ([#72](https://github.com/sporkd/mise-completions-sync/issues/72)) ([8c6023a](https://github.com/sporkd/mise-completions-sync/commit/8c6023ae25b3941b36e20e4f37861ae00fd7ebb0))
* **main:** release 0.5.6 ([#74](https://github.com/sporkd/mise-completions-sync/issues/74)) ([164863a](https://github.com/sporkd/mise-completions-sync/commit/164863a559eee86b7120465fd04e189cd6c63688))
* **main:** release 0.5.7 ([#80](https://github.com/sporkd/mise-completions-sync/issues/80)) ([d185cd0](https://github.com/sporkd/mise-completions-sync/commit/d185cd01d9f06f94ca953506776bb8bf4036a7dc))
* **main:** release 0.5.8 ([#92](https://github.com/sporkd/mise-completions-sync/issues/92)) ([080c1d4](https://github.com/sporkd/mise-completions-sync/commit/080c1d4423f1b6ca1177271f731ac50937867da0))
* **main:** release 0.5.9 ([#97](https://github.com/sporkd/mise-completions-sync/issues/97)) ([3d6a9d7](https://github.com/sporkd/mise-completions-sync/commit/3d6a9d70b05ea6e58768df4ae0a6d1c109f2a9db))


### Documentation Updates

* add getting started guide to README ([#20](https://github.com/sporkd/mise-completions-sync/issues/20)) ([3e0a61f](https://github.com/sporkd/mise-completions-sync/commit/3e0a61f7f80d0c89cdb759b7c20c4d90b2de11d5))
* add one-liner for hook setup ([65b2ebf](https://github.com/sporkd/mise-completions-sync/commit/65b2ebf7c5009a17fe11a9844001defb310a0218))
* apply All Tuner Labs corporate MkDocs style ([#31](https://github.com/sporkd/mise-completions-sync/issues/31)) ([5988071](https://github.com/sporkd/mise-completions-sync/commit/5988071f86dcbcd21dec8a12cb3045da2bb6c11d))
* reorganize site structure for better user experience ([#19](https://github.com/sporkd/mise-completions-sync/issues/19)) ([7dfcdea](https://github.com/sporkd/mise-completions-sync/commit/7dfcdea28b1a806046e89ae828e04fb50ab91c39))
* standardize README to alltuner brand structure ([#73](https://github.com/sporkd/mise-completions-sync/issues/73)) ([2057074](https://github.com/sporkd/mise-completions-sync/commit/2057074e75141b738aadb3cd323a01ef60856999))


### CI/CD Changes

* Add Claude Code GitHub Workflow ([#4](https://github.com/sporkd/mise-completions-sync/issues/4)) ([9b3afa6](https://github.com/sporkd/mise-completions-sync/commit/9b3afa6efd5e0fe616b9a806c5b60021db57dc48))
* align PR title check with org canonical workflow ([#67](https://github.com/sporkd/mise-completions-sync/issues/67)) ([73a1093](https://github.com/sporkd/mise-completions-sync/commit/73a10931a2c97106d5a8471be262606a9df4d714))
* validate PR titles as conventional commits ([#64](https://github.com/sporkd/mise-completions-sync/issues/64)) ([f27297d](https://github.com/sporkd/mise-completions-sync/commit/f27297def7e61488e24f54ea6f5814a475f43528))


### Build System

* track Cargo.lock so release builds with --locked succeed ([#69](https://github.com/sporkd/mise-completions-sync/issues/69)) ([78a9a78](https://github.com/sporkd/mise-completions-sync/commit/78a9a7852b46e707b5ae95d6d92628d0bfb52f38))
* update pre-commit hooks and registry ([#38](https://github.com/sporkd/mise-completions-sync/issues/38)) ([c22634e](https://github.com/sporkd/mise-completions-sync/commit/c22634e65c5c68c013cf44216ec5494088c6248a))

## [0.5.9](https://github.com/alltuner/mise-completions-sync/compare/v0.5.8...v0.5.9) (2026-05-27)


### Bug Fixes

* **registry:** remove fzf and zoxide (closes [#78](https://github.com/alltuner/mise-completions-sync/issues/78)) ([#96](https://github.com/alltuner/mise-completions-sync/issues/96)) ([8f3f1d2](https://github.com/alltuner/mise-completions-sync/commit/8f3f1d2471691472c898821e89b4286ca2f4b21c))

## [0.5.8](https://github.com/alltuner/mise-completions-sync/compare/v0.5.7...v0.5.8) (2026-05-27)


### Features

* add self-completion subcommand (closes [#75](https://github.com/alltuner/mise-completions-sync/issues/75)) ([#94](https://github.com/alltuner/mise-completions-sync/issues/94)) ([8521f7c](https://github.com/alltuner/mise-completions-sync/commit/8521f7c1f50605085ff3c852469dbe4dc9169a57))
* add talosctl ([#95](https://github.com/alltuner/mise-completions-sync/issues/95)) ([a43f446](https://github.com/alltuner/mise-completions-sync/commit/a43f446f137f76690837bd0e17a040e9f9107d4d))


### Bug Fixes

* **ci:** restore x86_64-unknown-linux-musl release binary ([#90](https://github.com/alltuner/mise-completions-sync/issues/90)) ([0dccee5](https://github.com/alltuner/mise-completions-sync/commit/0dccee5f90df29ac58825515596ed72028f5f449)), closes [#89](https://github.com/alltuner/mise-completions-sync/issues/89)
* use standard pattern for lefthook (closes [#86](https://github.com/alltuner/mise-completions-sync/issues/86)) ([#91](https://github.com/alltuner/mise-completions-sync/issues/91)) ([48b5a51](https://github.com/alltuner/mise-completions-sync/commit/48b5a5175f1d3e840a66a230a52338a987461f26))


### Miscellaneous Chores

* **deps:** update rust crate serde_json to v1.0.150 ([#87](https://github.com/alltuner/mise-completions-sync/issues/87)) ([2581de9](https://github.com/alltuner/mise-completions-sync/commit/2581de9137a55930358c7779a07d98122cf86d0a))

## [0.5.7](https://github.com/alltuner/mise-completions-sync/compare/v0.5.6...v0.5.7) (2026-05-12)


### Features

* add support for tree-sitter ([#77](https://github.com/alltuner/mise-completions-sync/issues/77)) ([afd6605](https://github.com/alltuner/mise-completions-sync/commit/afd660584746e717fdaab9aa7238ce2e571ab305))
* allow overriding output dirs with ENV vars ([#52](https://github.com/alltuner/mise-completions-sync/issues/52)) ([fc423c9](https://github.com/alltuner/mise-completions-sync/commit/fc423c9bd3c610efc69bf97032eaeacb8a047536))
* support tools from alternative backends ([#41](https://github.com/alltuner/mise-completions-sync/issues/41)) ([6e39bc0](https://github.com/alltuner/mise-completions-sync/commit/6e39bc08bf30cf8aba8124591b0f957d10fb4b17))


### Bug Fixes

* merge duplicate tests module in sync.rs ([#82](https://github.com/alltuner/mise-completions-sync/issues/82)) ([c469875](https://github.com/alltuner/mise-completions-sync/commit/c4698753d03a5216e3e7efa34c1bf3c107affe72))
* rename installed binary to misecompsync (closes [#79](https://github.com/alltuner/mise-completions-sync/issues/79)) ([#81](https://github.com/alltuner/mise-completions-sync/issues/81)) ([bd235ff](https://github.com/alltuner/mise-completions-sync/commit/bd235ffd075f86c6cc19ed0b011265a6d07612f9))

## [0.5.6](https://github.com/alltuner/mise-completions-sync/compare/v0.5.5...v0.5.6) (2026-05-04)


### Documentation Updates

* standardize README to alltuner brand structure ([#73](https://github.com/alltuner/mise-completions-sync/issues/73)) ([2057074](https://github.com/alltuner/mise-completions-sync/commit/2057074e75141b738aadb3cd323a01ef60856999))

## [0.5.5](https://github.com/alltuner/mise-completions-sync/compare/v0.5.4...v0.5.5) (2026-05-03)


### Miscellaneous Chores

* **deps:** update rust dependencies ([#71](https://github.com/alltuner/mise-completions-sync/issues/71)) ([ba67f02](https://github.com/alltuner/mise-completions-sync/commit/ba67f02946eeb1815daa8d54e6b27d2dcd9964fe))

## [0.5.4](https://github.com/alltuner/mise-completions-sync/compare/v0.5.3...v0.5.4) (2026-05-03)


### Build System

* track Cargo.lock so release builds with --locked succeed ([#69](https://github.com/alltuner/mise-completions-sync/issues/69)) ([78a9a78](https://github.com/alltuner/mise-completions-sync/commit/78a9a7852b46e707b5ae95d6d92628d0bfb52f38))

## [0.5.3](https://github.com/alltuner/mise-completions-sync/compare/v0.5.2...v0.5.3) (2026-05-03)


### CI/CD Changes

* align PR title check with org canonical workflow ([#67](https://github.com/alltuner/mise-completions-sync/issues/67)) ([73a1093](https://github.com/alltuner/mise-completions-sync/commit/73a10931a2c97106d5a8471be262606a9df4d714))

## [0.5.2](https://github.com/alltuner/mise-completions-sync/compare/v0.5.1...v0.5.2) (2026-05-03)


### Miscellaneous Chores

* **deps:** update amannn/action-semantic-pull-request action to v6 ([#66](https://github.com/alltuner/mise-completions-sync/issues/66)) ([be5454f](https://github.com/alltuner/mise-completions-sync/commit/be5454f69cd32758b59275e990e5228b3af65c27))


### CI/CD Changes

* validate PR titles as conventional commits ([#64](https://github.com/alltuner/mise-completions-sync/issues/64)) ([f27297d](https://github.com/alltuner/mise-completions-sync/commit/f27297def7e61488e24f54ea6f5814a475f43528))

## [0.5.1](https://github.com/alltuner/mise-completions-sync/compare/v0.5.0...v0.5.1) (2026-05-02)


### Bug Fixes

* bundle dependency and registry updates from recent merges ([#59](https://github.com/alltuner/mise-completions-sync/issues/59)) ([98e9409](https://github.com/alltuner/mise-completions-sync/commit/98e9409a7df5d32810ad0d41e58fb046a6926567))
* **registry:** remove mkcert (closes [#50](https://github.com/alltuner/mise-completions-sync/issues/50)) ([#61](https://github.com/alltuner/mise-completions-sync/issues/61)) ([b588589](https://github.com/alltuner/mise-completions-sync/commit/b588589f06c413028438ec9faf367879f29c223b))

## [0.5.0](https://github.com/alltuner/mise-completions-sync/compare/v0.4.4...v0.5.0) (2026-04-01)


### Features

* add new tools ([#40](https://github.com/alltuner/mise-completions-sync/issues/40)) ([4617152](https://github.com/alltuner/mise-completions-sync/commit/461715210f3123aac1ec2471ecb334c0d232808a))
* add prek completion support ([#48](https://github.com/alltuner/mise-completions-sync/issues/48)) ([b2bb8a9](https://github.com/alltuner/mise-completions-sync/commit/b2bb8a982e35c8bf5d08ad3cf15538fa2d9c2510)), closes [#36](https://github.com/alltuner/mise-completions-sync/issues/36)


### Bug Fixes

* **deps:** update rust crate toml to v1 ([#35](https://github.com/alltuner/mise-completions-sync/issues/35)) ([ea3241f](https://github.com/alltuner/mise-completions-sync/commit/ea3241fa003e8c5a60b0c70d07e22cb9f9de8239))
* **generate-registry:** migrate from mise registry.toml to API endpoint ([#42](https://github.com/alltuner/mise-completions-sync/issues/42)) ([329a9b9](https://github.com/alltuner/mise-completions-sync/commit/329a9b97754df3e264ea9d47ce11bbe21a02406e))
* remove unused json import in generate-registry ([#47](https://github.com/alltuner/mise-completions-sync/issues/47)) ([d3e7c29](https://github.com/alltuner/mise-completions-sync/commit/d3e7c29a63751b203108bfa12884156ff5a03b5d))

## [0.4.4](https://github.com/alltuner/mise-completions-sync/compare/v0.4.3...v0.4.4) (2026-02-11)


### Bug Fixes

* remove gcloud from registry ([#32](https://github.com/alltuner/mise-completions-sync/issues/32)) ([#33](https://github.com/alltuner/mise-completions-sync/issues/33)) ([fa296f6](https://github.com/alltuner/mise-completions-sync/commit/fa296f69e5812a0e83c081ec7431d02282681662))

## [0.4.3](https://github.com/alltuner/mise-completions-sync/compare/v0.4.2...v0.4.3) (2026-01-16)


### Bug Fixes

* **ci:** remove auto-generation of tools docs from workflow ([#29](https://github.com/alltuner/mise-completions-sync/issues/29)) ([25d873b](https://github.com/alltuner/mise-completions-sync/commit/25d873b7ea502e9f3cb21a0e21120b88e906060b))

## [0.4.2](https://github.com/alltuner/mise-completions-sync/compare/v0.4.1...v0.4.2) (2026-01-15)


### Bug Fixes

* **ci:** remove auto-generation of tools docs from workflow ([#28](https://github.com/alltuner/mise-completions-sync/issues/28)) ([9cdc1af](https://github.com/alltuner/mise-completions-sync/commit/9cdc1afe9a5c0fb1d0d3b6054fb9b7d131a58ae2))
* **scripts:** handle missing mise in CI gracefully ([#26](https://github.com/alltuner/mise-completions-sync/issues/26)) ([70651da](https://github.com/alltuner/mise-completions-sync/commit/70651daf251e6248f6ff58812fb21f0dcd7c451c))

## [0.4.1](https://github.com/alltuner/mise-completions-sync/compare/v0.4.0...v0.4.1) (2026-01-15)


### Bug Fixes

* **docs:** trigger rebuild on CHANGELOG changes and include in site ([#24](https://github.com/alltuner/mise-completions-sync/issues/24)) ([d1a5bd1](https://github.com/alltuner/mise-completions-sync/commit/d1a5bd1695f9a2d44b8e151475051b9df4918086))

## [0.4.0](https://github.com/alltuner/mise-completions-sync/compare/v0.3.0...v0.4.0) (2026-01-15)


### Features

* **docs:** enhance tool documentation with metadata and status tracking ([#23](https://github.com/alltuner/mise-completions-sync/issues/23)) ([8159951](https://github.com/alltuner/mise-completions-sync/commit/81599513a5e3f689e6b52d09ed0530ecc7dd68bb))


### Bug Fixes

* **registry:** remove tools without completion support ([#21](https://github.com/alltuner/mise-completions-sync/issues/21)) ([4d5e7ba](https://github.com/alltuner/mise-completions-sync/commit/4d5e7ba585cd80b0b70eabc4890909999318295d))

## [0.3.0](https://github.com/alltuner/mise-completions-sync/compare/v0.2.2...v0.3.0) (2026-01-15)


### Features

* add worktrees directory to gitignore ([#15](https://github.com/alltuner/mise-completions-sync/issues/15)) ([c43f8ae](https://github.com/alltuner/mise-completions-sync/commit/c43f8aee52cc323ae6a75305ff13c18025a10c44))
* **docs:** convert from mdBook to MkDocs with Material theme ([#18](https://github.com/alltuner/mise-completions-sync/issues/18)) ([1075920](https://github.com/alltuner/mise-completions-sync/commit/1075920b4285c1373a74aafcd5dafbb0fc50beb1))
* **registry:** pattern-based format with schema versioning ([#17](https://github.com/alltuner/mise-completions-sync/issues/17)) ([e7e72cc](https://github.com/alltuner/mise-completions-sync/commit/e7e72cc86fe1a6ee508dfda625156443d3b3967b))

## [0.2.2](https://github.com/alltuner/mise-completions-sync/compare/v0.2.1...v0.2.2) (2026-01-15)


### Bug Fixes

* **registry:** remove tools without completion support ([#14](https://github.com/alltuner/mise-completions-sync/issues/14)) ([7f3a0b5](https://github.com/alltuner/mise-completions-sync/commit/7f3a0b57bc084eebac2bba345bcaa892965c1165))
* wrap completion commands with mise x for tool availability ([#12](https://github.com/alltuner/mise-completions-sync/issues/12)) ([32f58c5](https://github.com/alltuner/mise-completions-sync/commit/32f58c509744f7e91c4c805c6e69caf322418616))

## [0.2.1](https://github.com/alltuner/mise-completions-sync/compare/v0.2.0...v0.2.1) (2026-01-15)


### Bug Fixes

* **ci:** chain release workflows and always bump patch ([#9](https://github.com/alltuner/mise-completions-sync/issues/9)) ([415f670](https://github.com/alltuner/mise-completions-sync/commit/415f670336f716cfe30c65a3e4174d9e1c15c71d))

## [0.2.0](https://github.com/alltuner/mise-completions-sync/compare/v0.1.0...v0.2.0) (2026-01-15)


### Features

* add release infrastructure and expand registry ([#5](https://github.com/alltuner/mise-completions-sync/issues/5)) ([e36dd40](https://github.com/alltuner/mise-completions-sync/commit/e36dd4046be63cd8b72ed1697601907e473bda4a))
