# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.0.2-alpha.1](https://github.com/thomvaill/log4brains/compare/v1.0.2-alpha.0...v1.0.2-alpha.1) (2024-10-29)


### Bug Fixes

* lerna publish on Node 18-20 ([0e78d47](https://github.com/thomvaill/log4brains/commit/0e78d473fed1b98be395e072f1193436858869f9))





## [1.0.2-alpha.0](https://github.com/thomvaill/log4brains/compare/v1.0.1...v1.0.2-alpha.0) (2024-10-29)


### Bug Fixes

* make Log4brains run on Node 18 and 20 ([58dcfff](https://github.com/thomvaill/log4brains/commit/58dcfffd7ceb706bef6d43838be5d0358ed0f51f))
* workaround for ERR_OSSL_EVP_UNSUPPORTED build issue ([#114](https://github.com/thomvaill/log4brains/issues/114)) ([8e93409](https://github.com/thomvaill/log4brains/commit/8e93409d95777d3036ad809982aa70a9f26d8dd6))





## [1.0.1](https://github.com/thomvaill/log4brains/compare/v1.0.0...v1.0.1) (2022-09-22)


### Bug Fixes

* ensure generated output works on s3 ([#84](https://github.com/thomvaill/log4brains/issues/84)) ([237bd1f](https://github.com/thomvaill/log4brains/commit/237bd1f5652704a076008c2d534f124f613b3641)), closes [#45](https://github.com/thomvaill/log4brains/issues/45)





# [1.0.0](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.13...v1.0.0) (2022-09-22)


### Reverts

* Revert "chore(release): publish v1.0.0" ([7f9852e](https://github.com/thomvaill/log4brains/commit/7f9852ea48842aae3d45ac7466a829532a2fb3ce))
* Revert "chore(release): publish v1.0.0" ([d89af64](https://github.com/thomvaill/log4brains/commit/d89af64b03d8eabbb5b660ba77eea800f991aa37))





# [1.0.0-beta.13](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.12...v1.0.0-beta.13) (2022-07-08)


### Bug Fixes

* nextjs incrementalCache usage fixed ([e5bb21d](https://github.com/thomvaill/log4brains/commit/e5bb21d09800b09b48df8d5c483c8c8a70f727f2))





# [1.0.0-beta.12](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.11...v1.0.0-beta.12) (2022-05-30)


### Bug Fixes

* **#74:** cheerio breaking change ([b021b42](https://github.com/thomvaill/log4brains/commit/b021b42385a115f6c1f6808a23b653d0efe3c20c)), closes [#74](https://github.com/thomvaill/log4brains/issues/74)
* **build:** fix build error with adding await to loadConfig ([ba0dcb5](https://github.com/thomvaill/log4brains/commit/ba0dcb5e63b377690b90c217ecea9809e83431d1))
* **web:** optional dependency sharp caused errors when missing ([73fe3e4](https://github.com/thomvaill/log4brains/commit/73fe3e4627a1edc83b8a6cd0542e7d009c8fd84d))





# [1.0.0-beta.11](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.10...v1.0.0-beta.11) (2021-04-30)


### Bug Fixes

* **cli:** print Next.js' stderr to improve debug ([8f88863](https://github.com/thomvaill/log4brains/commit/8f888634fd04c9ac5050be056eff98824d5996d4)), closes [#26](https://github.com/thomvaill/log4brains/issues/26)





# [1.0.0-beta.10](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.9...v1.0.0-beta.10) (2021-04-30)


### Bug Fixes

* **web:** caniuse-lite outdated warning ([7d61668](https://github.com/thomvaill/log4brains/commit/7d61668634d33cf4af5dfbff5bf8d529bb7a7c3f))





# [1.0.0-beta.9](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.8...v1.0.0-beta.9) (2021-04-29)


### Bug Fixes

* [#27](https://github.com/thomvaill/log4brains/issues/27) pin nextjs to a specific version ([320e1ba](https://github.com/thomvaill/log4brains/commit/320e1bac0c1d6942ae2bb00816693cce3ba1b122))





# [1.0.0-beta.8](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.7...v1.0.0-beta.8) (2021-01-20)


### Bug Fixes

* build issue with fsevents on macOS ([9f2a25c](https://github.com/thomvaill/log4brains/commit/9f2a25c25120754d07b2b98e36eab8cd3f888854))
* **init:** bad import ([e3b74be](https://github.com/thomvaill/log4brains/commit/e3b74be05964f8668610397cb62c15d519e581a3))
* **init:** sed behavior on macOS ([132ef7c](https://github.com/thomvaill/log4brains/commit/132ef7caad3eb3ab0b1b5cdd1d873f40dcae0ca7))





# [1.0.0-beta.7](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.6...v1.0.0-beta.7) (2021-01-19)


### Bug Fixes

* **init:** Typo in ADR template link ([c1629a4](https://github.com/thomvaill/log4brains/commit/c1629a4a692414642667749112b28943dedb3bd4))





# [1.0.0-beta.6](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.5...v1.0.0-beta.6) (2021-01-14)


### Bug Fixes

* **web:** update to react 17 to fix install bug in node 15 ([1a04aca](https://github.com/thomvaill/log4brains/commit/1a04aca75df66282e637a2dd12a93b3f9c061ce2))





# [1.0.0-beta.5](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.4...v1.0.0-beta.5) (2021-01-13)


### Features

* display the nb of generated ADRs ([9fecdab](https://github.com/thomvaill/log4brains/commit/9fecdab44fae0d1442f3bb00a336868becb6601f)), closes [#14](https://github.com/thomvaill/log4brains/issues/14)
* distribute as a global NPM package ([9551b68](https://github.com/thomvaill/log4brains/commit/9551b689ffbce82f5b6d2bb514f87bf3faa10e3e))


### BREAKING CHANGES

* installation procedure is now completely modified





# [1.0.0-beta.4](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.3...v1.0.0-beta.4) (2020-12-10)


### Bug Fixes

* **init:** typo ([de0c04c](https://github.com/thomvaill/log4brains/commit/de0c04c3bc0e13bf5723af26db43ab5dd2a68365))





# [1.0.0-beta.3](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.2...v1.0.0-beta.3) (2020-12-10)


### Bug Fixes

* **init:** use yesterday's date to create first ADRs ([d5783c8](https://github.com/thomvaill/log4brains/commit/d5783c8f695d257d93a4b6fdbdc309892b4d7352))





# [1.0.0-beta.2](https://github.com/thomvaill/log4brains/compare/v1.0.0-beta.1...v1.0.0-beta.2) (2020-12-10)


### Features

* **web:** "New ADR" button ([8bbb4d1](https://github.com/thomvaill/log4brains/commit/8bbb4d1409727ad195314b5e73664520708a15ce))
* **web:** an ADR badge for READMEs ([b61238f](https://github.com/thomvaill/log4brains/commit/b61238f7d96a537659a79ca4b8d190993e98c8f6))
* initial features ([03550dc](https://github.com/thomvaill/log4brains/commit/03550dc4435c7668d36b50ca5ae420fab94e4936))





# 1.0.0-beta.1 (2020-12-10)


### Features

* initial features ([03550dc](https://github.com/thomvaill/log4brains/commit/03550dc4435c7668d36b50ca5ae420fab94e4936))
