# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.4.1] - 2024-05-16
### :sparkles: New Features
- [`4c69281`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/4c692814d16d40a1829dd5db1fdd28da34def1e1) - s3_key_prefix attribute for cloudtrail *(PR [#26](https://github.com/clouddrove/terraform-aws-cloudtrail/pull/26) by [@h1manshu98](https://github.com/h1manshu98))*
- [`96d1337`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/96d13371e40d6c2c1bc6c500362feed7e0b8216e) - Add automerge github shared workflow *(PR [#27](https://github.com/clouddrove/terraform-aws-cloudtrail/pull/27) by [@vaibhav7797](https://github.com/vaibhav7797))*
- [`2ba5e13`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/2ba5e1369129ee8f999b6b4650ca42a2a0053df3) - updated example path and readme paramters *(commit by [@VishwajitNagulkar](https://github.com/VishwajitNagulkar))*

### :bug: Bug Fixes
- [`6ab6f6f`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/6ab6f6f9a8d1a460c7b197c1d79c5ca8f11629ea) - fixed cloudtrail log group creation issue *(PR [#30](https://github.com/clouddrove/terraform-aws-cloudtrail/pull/30) by [@nileshgadgi](https://github.com/nileshgadgi))*

### :memo: Documentation Changes
- [`6d45226`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/6d452269e154aaef69987ac9fa16ec085c4eb741) - update CHANGELOG.md for 1.4.0 *(commit by [@clouddrove-ci](https://github.com/clouddrove-ci))*


## [1.4.0] - 2023-07-19
### :sparkles: New Features
- [`fbdd962`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/fbdd962bdd32cb3e9c585bcf6a40ec45bebb0da5) - add changelog.yml file and use shared-workflows *(commit by [@theprashantyadav](https://github.com/theprashantyadav))*
- [`c3bc36c`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/c3bc36cea431a02087b7d5de12465b90319b72bc) - added dependabot.yml *(commit by [@theprashantyadav](https://github.com/theprashantyadav))*
- [`74a9932`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/74a993255238361fb61421e83e6467dae0c483ca) - auto changelog action added *(commit by [@theprashantyadav](https://github.com/theprashantyadav))*
- [`31ec785`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/31ec78548ae4b2e4e1f849b4f5effc716b846b24) - add deepsource & added assignees,reviewer in dependabot *(commit by [@Tanveer143s](https://github.com/Tanveer143s))*
- [`4da6474`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/4da64740536f8d1ff21be39cb7f5f3f933df9dfa) - dynamic values and fixed main file *(commit by [@anmolnagpal](https://github.com/anmolnagpal))*

### :bug: Bug Fixes
- [`a2a5a9b`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/a2a5a9bf615061fd9f2956efd5c96fc55ad0b9d5) - update s3 for label and data for name *(commit by [@nileshgadgi](https://github.com/nileshgadgi))*
- [`dd0c134`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/dd0c134f492d98e744144e205906483d29165e00) - update local variables *(commit by [@nileshgadgi](https://github.com/nileshgadgi))*
- [`3730c0f`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/3730c0f63aec0078a8521cadebc8f7f9ba5f7667) - pass direct value in name and env of bucket in examlpe *(commit by [@nileshgadgi](https://github.com/nileshgadgi))*


## [1.3.0] - 2022-02-22
### :bug: Bug Fixes
- [`66ed839`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/66ed839f98b3743b89561e530a85ae7aa89e328c) - update README.md .

## [1.0.1] - 2022-05-13
### :bug: Bug Fixes
- [`7ac1ceb`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/7ac1cebf7c5b651918c392cdb936aca74d1de405) - use terraform letast version


## [0.15.0] - 2021-10-16
### :bug: Bug Fixes
- [`1c2adf6`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/1c2adf613f8343a1b7cc4af3c59a61db797e6fe5) - github-action Update,update-license


## [0.14.0] - 2021-05-15
### :sparkles: New Features
- [`2be3a30`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/2be3a30f56ba82bb6344e93b44346dbb354b0f65) - enabled multi region deployment
- [`c63350d`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/c63350dcfd77036aea553c95ced761bb8f61d490) - added Support for 0.15
- [`d970727`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/d9707272e41744191068c9f8fbd9112bc005d578) - add logs group

## [0.13.0] - 2020-10-26
### :sparkles: New Features
- [`0057601`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/0057601cd6780d4b18066769073abc2beaf69725) - add event_selector as a varible
- [`a3fcfb2`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/a3fcfb28cc3de32f6dc6da883bdab1995d7902e6) - add group arn
- [`f2f6133`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/f2f613389b731f8cfdf8bf4b64c2090a846953fa) - is_multi_region_trail var default for true
- [`2be3a30`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/2be3a30f56ba82bb6344e93b44346dbb354b0f65) - enabled multi region deployment
- [`c63350d`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/c63350dcfd77036aea553c95ced761bb8f61d490) - added Support for 0.15


## [0.12.5] - 2020-10-05
### :bug: Bug Fixes
- [`acd9fd8`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/acd9fd8db6cff43256a6374e0b95dafef06a9fc4) - updated and upgraded
- [`4ab05da`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/4ab05da4933040697012068e5435fa5594e9503d) - upgrade terraform version to 0.13.0 and add pipelines

### :sparkles: New Features
- [`0057601`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/0057601cd6780d4b18066769073abc2beaf69725) - add event_selector as a varible
- [`a3fcfb2`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/a3fcfb28cc3de32f6dc6da883bdab1995d7902e6) - add group arn
- [`f2f6133`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/f2f613389b731f8cfdf8bf4b64c2090a846953fa) - is_multi_region_trail var default for true
- [`2be3a30`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/2be3a30f56ba82bb6344e93b44346dbb354b0f65) - enabled multi region deployment
- [`d970727`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/d9707272e41744191068c9f8fbd9112bc005d578) - add logs group


## [0.12.4] - 2020-05-24
### :bug: Bug Fixes
- [`ff43849`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/ff438494fa606cdb97aa7a4689f58caec25c246f) - update log roup arn
- [`cdbadc8`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/cdbadc82b013a17a565798a277e6ef08ada48202) - updated and upgraded

### :sparkles: New Features
- [`43494ed`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/43494edce1dd3110561322aa754ce298c1235eb9) - Revert "update log roup arn"
- [`0057601`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/0057601cd6780d4b18066769073abc2beaf69725) - add event_selector as a varible
- [`2be3a30`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/2be3a30f56ba82bb6344e93b44346dbb354b0f65) - enabled multi region deployment
- [`d970727`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/d9707272e41744191068c9f8fbd9112bc005d578) - add logs group


## [0.12.3] - 2020-04-25
### :bug: Bug Fixes
- [`ff43849`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/ff438494fa606cdb97aa7a4689f58caec25c246f) - update log roup arn

### :sparkles: New Features
- [`0057601`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/0057601cd6780d4b18066769073abc2beaf69725) - add event_selector as a varible
- [`f2f6133`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/f2f613389b731f8cfdf8bf4b64c2090a846953fa) -is_multi_region_trail var default for true
- [`2fa6a3b`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/2fa6a3bb1eca0a987aedd5c3b26e0effe55767d7) -small correction

## [0.12.2] - 2019-09-25
### :bug: Bug Fixes
- [`e1f33f5`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/e1f33f575fac069c2b559af580294982a940e1a5) - fix labels managedby variables
- [`ff43849`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/ff438494fa606cdb97aa7a4689f58caec25c246f) - update log roup arn

### :sparkles: New Features
- [`0057601`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/0057601cd6780d4b18066769073abc2beaf69725) - add event_selector as a varible
- [`f2f6133`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/f2f613389b731f8cfdf8bf4b64c2090a846953fa) - is_multi_region_trail var default for true

## [0.12.1] - 2019-09-05
### :bug: Bug Fixes
- [`2ff2702`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/2ff27020bd7c3b3c86e2d6f0f13edb5eb3cb7964) - change output syntax
- [`73c1e39`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/73c1e39fa4919ed916744f1d8a61fd8acb2b6a10) - bug fix
- [`ba9b774`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/ba9b7748d53ab7dad719d7c2362ac5fb64b038cd) - update log roup arn

### :sparkles: New Features
- [`0057601`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/0057601cd6780d4b18066769073abc2beaf69725) - add event_selector as a varible
- [`a3fcfb2`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/a3fcfb28cc3de32f6dc6da883bdab1995d7902e6) - add group arn


## [0.12.0] - 2019-08-12
### :bug: Bug Fixes
- [`2ff2702`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/2ff27020bd7c3b3c86e2d6f0f13edb5eb3cb7964) - change output syntax
- [`e1f33f5`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/e1f33f575fac069c2b559af580294982a940e1a5) - fix labels managedby variables
- [`ff43849`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/ff438494fa606cdb97aa7a4689f58caec25c246f) - update log roup arn

### :sparkles: New Features
- [`0057601`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/0057601cd6780d4b18066769073abc2beaf69725) - add event_selector as a varible


## [0.11.0] - 2019-08-12
### :bug: Bug Fixes
- [`ff43849`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/ff438494fa606cdb97aa7a4689f58caec25c246f) - update log roup arn
- [`43494ed`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/43494edce1dd3110561322aa754ce298c1235eb9) - Revert "update log roup arn"

### :sparkles: New Features
- [`0057601`](https://github.com/clouddrove/terraform-aws-cloudtrail/commit/0057601cd6780d4b18066769073abc2beaf69725) - add event_selector as a varible


[0.11.0]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/0.11.0...master
[0.12.0]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/0.12.0...master
[0.12.1]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/0.12.1...master
[0.12.2]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/0.12.2...master
[0.12.3]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/0.12.3...master
[0.12.4]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/0.12.4...master
[0.12.5]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/0.12.5...master
[0.13.0]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/0.13.0...master
[0.14.0]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/0.14.0...master
[0.15.0]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/0.15.0...master
[1.0.1]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/1.0.1...master
[1.3.0]:  https://github.com/clouddrove/terraform-aws-cloudtrail/releases/tag/1.3.0
[1.4.0]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/1.3.0...1.4.0
[1.4.1]: https://github.com/clouddrove/terraform-aws-cloudtrail/compare/1.4.0...1.4.1
