# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- ## Unreleased
### :gear: Changed
### :rocket: Added
### :spider: Fixed
-->

## [0.11.0](https://github.com/cloudquery/cq-provider-sdk/compare/v0.10.11...v0.11.0) (2022-06-08)


### ⚠ BREAKING CHANGES

* IgnoreError Recursively for tables and columns (#323)

### Features

* IgnoreError Recursively for tables and columns ([#323](https://github.com/cloudquery/cq-provider-sdk/issues/323)) ([7212d98](https://github.com/cloudquery/cq-provider-sdk/commit/7212d98ade656f8881415cb41930537238e7fe55))
* Sleep helper ([#328](https://github.com/cloudquery/cq-provider-sdk/issues/328)) ([04459c5](https://github.com/cloudquery/cq-provider-sdk/commit/04459c5edacf9d4bcc2911f39155cb2daa83c3a1))

## [0.10.11](https://github.com/cloudquery/cq-provider-sdk/compare/v0.10.10...v0.10.11) (2022-06-07)


### Features

* Remove default value option from column ([#324](https://github.com/cloudquery/cq-provider-sdk/issues/324)) ([33a4353](https://github.com/cloudquery/cq-provider-sdk/commit/33a4353f89912e5bb8644797efc5aa24cc34e149)), closes [#298](https://github.com/cloudquery/cq-provider-sdk/issues/298)

## [0.10.10](https://github.com/cloudquery/cq-provider-sdk/compare/v0.10.9...v0.10.10) (2022-06-07)


### Features

* Always use BigInt ([#321](https://github.com/cloudquery/cq-provider-sdk/issues/321)) ([2033349](https://github.com/cloudquery/cq-provider-sdk/commit/2033349d3dfa07035ad3c37acba23e285a49c172))

## [0.10.9](https://github.com/cloudquery/cq-provider-sdk/compare/v0.10.8...v0.10.9) (2022-06-07)


### Bug Fixes

* Add missing SkipIgnoreInTest ([#319](https://github.com/cloudquery/cq-provider-sdk/issues/319)) ([b088a33](https://github.com/cloudquery/cq-provider-sdk/commit/b088a33aa119fd428f74bb86c83527e2a5d9eb8c))

## [0.10.8](https://github.com/cloudquery/cq-provider-sdk/compare/v0.10.7...v0.10.8) (2022-06-07)


### Bug Fixes

* Respect Multiplexer No Clients ([#313](https://github.com/cloudquery/cq-provider-sdk/issues/313)) ([c873426](https://github.com/cloudquery/cq-provider-sdk/commit/c8734261bb8c081e6f73415663f90a750e93100e))

### [0.10.7](https://github.com/cloudquery/cq-provider-sdk/compare/v0.10.6...v0.10.7) (2022-06-01)


### Features

* Add TestView helper function ([#305](https://github.com/cloudquery/cq-provider-sdk/issues/305)) ([c4381f5](https://github.com/cloudquery/cq-provider-sdk/commit/c4381f5bb97b4ed5d6dda0d60a4037f195d08dfe))

### [0.10.6](https://github.com/cloudquery/cq-provider-sdk/compare/v0.10.5...v0.10.6) (2022-06-01)


### Features

* Return full rlimit ([#301](https://github.com/cloudquery/cq-provider-sdk/issues/301)) ([99b8c5e](https://github.com/cloudquery/cq-provider-sdk/commit/99b8c5e1bf961a34055e96784bd926e96b666c4d))

### [0.10.5](https://github.com/cloudquery/cq-provider-sdk/compare/v0.10.4...v0.10.5) (2022-05-31)


### Bug Fixes

* **deps:** Update hashstructure ([#293](https://github.com/cloudquery/cq-provider-sdk/issues/293)) ([3deb3ab](https://github.com/cloudquery/cq-provider-sdk/commit/3deb3abd956bb217c795d1d3e0a08920f7682220))
* Null cq_id error ([#295](https://github.com/cloudquery/cq-provider-sdk/issues/295)) ([b41a56c](https://github.com/cloudquery/cq-provider-sdk/commit/b41a56ca781ae4560fad0ff0042d2d409af1e545))

### [0.10.4](https://github.com/cloudquery/cq-provider-sdk/compare/v0.10.3...v0.10.4) (2022-05-29)


### Features

* **stats:** Add heartbeat ([#237](https://github.com/cloudquery/cq-provider-sdk/issues/237)) ([e0f10e7](https://github.com/cloudquery/cq-provider-sdk/commit/e0f10e75669e390d3d93d9f6488fa7a1ad562b70))

### [0.10.3](https://github.com/cloudquery/cq-provider-sdk/compare/v0.10.2...v0.10.3) (2022-05-26)


### Features

* Implement Diagnostics.BySeverity filtering ([#288](https://github.com/cloudquery/cq-provider-sdk/issues/288)) ([75213de](https://github.com/cloudquery/cq-provider-sdk/commit/75213de41aceaa6607b479e822c18b8961772c5b))
* Sortable flatdiags ([#290](https://github.com/cloudquery/cq-provider-sdk/issues/290)) ([22a7afb](https://github.com/cloudquery/cq-provider-sdk/commit/22a7afb218b536da6f8d3844c6b8bacde4478329))

### [0.10.2](https://github.com/cloudquery/cq-provider-sdk/compare/v0.10.1...v0.10.2) (2022-05-25)


### Bug Fixes

* **testing:** Don't add ignored diagnostics to errors validation ([#283](https://github.com/cloudquery/cq-provider-sdk/issues/283)) ([370da1e](https://github.com/cloudquery/cq-provider-sdk/commit/370da1e8699b5da4920409c4029ec1e617ec3c86))

### [0.10.1](https://github.com/cloudquery/cq-provider-sdk/compare/v0.10.0...v0.10.1) (2022-05-24)


### Bug Fixes

* Upgrade cqproto protocol to v5 ([#285](https://github.com/cloudquery/cq-provider-sdk/issues/285)) ([7d14f65](https://github.com/cloudquery/cq-provider-sdk/commit/7d14f658aa06343be6726df831f398a2870c9353))

## [0.10.0](https://github.com/cloudquery/cq-provider-sdk/compare/v0.9.5...v0.10.0) (2022-05-24)


### ⚠ BREAKING CHANGES

* Migrations removal (#262)

### Features

* Migrations removal ([#262](https://github.com/cloudquery/cq-provider-sdk/issues/262)) ([82b8981](https://github.com/cloudquery/cq-provider-sdk/commit/82b8981c8757a4129dda1a1ae7abed65f1f2dc67))

### [0.9.5](https://github.com/cloudquery/cq-provider-sdk/compare/v0.9.4...v0.9.5) (2022-05-23)


### Bug Fixes

* Delete by cq_id before insertion ([#266](https://github.com/cloudquery/cq-provider-sdk/issues/266)) ([1f74be7](https://github.com/cloudquery/cq-provider-sdk/commit/1f74be7ade47872c3c9772059f651ac0c48ff8e5))
* Executor fixes ([#265](https://github.com/cloudquery/cq-provider-sdk/issues/265)) ([79f98ce](https://github.com/cloudquery/cq-provider-sdk/commit/79f98cef89e7c0c69dd29f746b3510fe03f99f60))

### [0.9.4](https://github.com/cloudquery/cq-provider-sdk/compare/v0.9.3...v0.9.4) (2022-05-17)


### Bug Fixes

* Added json marshaling for []*struct -> json ([#248](https://github.com/cloudquery/cq-provider-sdk/issues/248)) ([bcbc3fa](https://github.com/cloudquery/cq-provider-sdk/commit/bcbc3fa176ecee33c686f5b13a801a319e3948f7))
* Calculate goroutines with ulimit ([#256](https://github.com/cloudquery/cq-provider-sdk/issues/256)) ([5753765](https://github.com/cloudquery/cq-provider-sdk/commit/575376554835a41ce0a94562b29da3247ff2378f))
* **deps:** Update hashstructure ([#252](https://github.com/cloudquery/cq-provider-sdk/issues/252)) ([be60d74](https://github.com/cloudquery/cq-provider-sdk/commit/be60d7430a62f4b1d328c05b193ce55dd01c6fd1))
* Int64 to int automatic conversion added ([#242](https://github.com/cloudquery/cq-provider-sdk/issues/242)) ([4c80f07](https://github.com/cloudquery/cq-provider-sdk/commit/4c80f07e45033f2537bb4995225f40ec5533f270))
* Race condition ([#255](https://github.com/cloudquery/cq-provider-sdk/issues/255)) ([2f32536](https://github.com/cloudquery/cq-provider-sdk/commit/2f32536a5f6f60d330c5ede61304dccc98594a81))
* Revert "fix(deps): Update hashstructure ([#252](https://github.com/cloudquery/cq-provider-sdk/issues/252))" ([#260](https://github.com/cloudquery/cq-provider-sdk/issues/260)) ([8534e24](https://github.com/cloudquery/cq-provider-sdk/commit/8534e24236e53fd4d34238775c2a4414d85f4a9d))
* Use hashing FormatV1 ([#258](https://github.com/cloudquery/cq-provider-sdk/issues/258)) ([646daa5](https://github.com/cloudquery/cq-provider-sdk/commit/646daa57df21c5c06c498572f49d1c0294d6caf2))

## [v0.6.1] - 2022-01-03

### :gear: Changed
* plugins now support both version `3` and `2`

## [v0.6.0] - 2021-12-31

### :gear: Changed
* **Breaking Change**: changed `TestResource` API [#137](https://github.com/cloudquery/cq-provider-sdk/pull/137)
* `ConfigureProvider` now supports standard `hcl` byte stream
* `TableResolver` specify channel direction `type TableResolver func(ctx context.Context, meta ClientMeta, parent *Resource, res chan<- interface{}) error`


### :rocket: Added
* Added `SkipEmptyColumn` and `SkipEmptyRows` to `ResourceTestCase`
* If test fail it will print what are the missing columns as well.
* Added attribute `IgnoreInTests` to column API [#138](https://github.com/cloudquery/cq-provider-sdk/pull/137)
* `ConfigureProvider` now supports standard `hcl` byte streamq

## [v0.5.7]- 2021-12-20

### :gear: Changed
* Fix table and column name limit tests [#134](https://github.com/cloudquery/cq-provider-sdk/pull/134).

## [v0.5.6] - 2021-12-18

### :gear: Changed
* SDK e2e testing terraform apply now also logs [#130](https://github.com/cloudquery/cq-provider-sdk/pull/130).

### :rocket: Added
* Added new test for table and column name limits [#133](https://github.com/cloudquery/cq-provider-sdk/pull/133).

## [v0.5.5] - 2021-12-15

### :gear: Changed
* Added support for error interface for diagnostics [#128](https://github.com/cloudquery/cq-provider-sdk/pull/128).
* Improved doc generation to remove unused files [#127](https://github.com/cloudquery/cq-provider-sdk/pull/127) fixes [#116](https://github.com/cloudquery/cq-provider-sdk/issues/116).
* Added warning about file descriptor usage [#126](https://github.com/cloudquery/cq-provider-sdk/pull/126) fixes [cloudquery/cloudquery#285](https://github.com/cloudquery/cloudquery/issues/285).

## [v0.5.4] - 2021-12-09

### :spider: Fixed
* fixed bad execution error validation [#125](https://github.com/cloudquery/cq-provider-sdk/pull/125)

## [v0.5.3] - 2021-12-06

### :gear: Changed
* Updated SDK dependencies [#121](https://github.com/cloudquery/cq-provider-sdk/pull/121)
* Add column name to resolver errors [#114](https://github.com/cloudquery/cq-provider-sdk/issues/114)
* Improve plugin serve execution message [#117](https://github.com/cloudquery/cq-provider-sdk/issues/117)


## [v0.5.2] - 2021-11-23

### :rocket: Added
* Support IPAddressesResolver for TypeInetArray [#112](https://github.com/cloudquery/cq-provider-sdk/pull/112)
* []struct now can be parsed automatically to jsons [#109](https://github.com/cloudquery/cq-provider-sdk/issues/109)


## [v0.5.1] - 2021-11-01

### :rocket: Added
 * feat/implementation of parallel clients limit by @fdistorted in [#103](https://github.com/cloudquery/cq-provider-sdk/pull/103)
 * Support passing table meta information over cqproto [#107](https://github.com/cloudquery/cq-provider-sdk/pull/107)

## [v0.5.0] - 2021-10-21

### :rocket: Added
* Support diagnostics from fetch executions, allow providers to define custom diagnostic classifiers for errosr received from the fetch execution [#104](https://github.com/cloudquery/cq-provider-sdk/pull/104)
* Add more metadata sent on fetched resources completion, status, resource count and diagnostics [#104](https://github.com/cloudquery/cq-provider-sdk/pull/104)

## [v0.4.10] - 2021-10-18

Fix drop provider tables due to out of shared memory, a large number of tables exceeds the transaction memory limit of
usual database configurations [#105](https://github.com/cloudquery/cq-provider-sdk/pull/105)
    
## [v0.4.9] - 2021-10-07

### :spider: Fixed
* fixed missing stale filter `--disable-delete` in cloudquery [#102](https://github.com/cloudquery/cq-provider-sdk/pull/102)

## [v0.4.8] - 2021-10-05

### :spider: Fixed
* updated integration test validation, allowing at least 1 results [#101](https://github.com/cloudquery/cq-provider-sdk/pull/101)


## [v0.4.7] - 2021-09-23

### :rocket: Added
* Added support to remove stale data based on `last_updated` column that wasn't fetched in latest refresh, activate with `--disable-delete` in cloudquery [#95](https://github.com/cloudquery/cq-provider-sdk/pull/95)

### :gear: Changed
* Integration tesing should fail if provider has internal error [#98](https://github.com/cloudquery/cq-provider-sdk/pull/98)

### :spider: Fixed
* fixed default resolver for resource valus to be json for unknown types [#99](https://github.com/cloudquery/cq-provider-sdk/pull/99)

## [v0.4.6] - 2021-09-14

### :gear: Changed
* Debugging providers will print debug level by default. Trace enabled via env variable `CQ_PROVIDER_DEBUG_TRACE_LOG` [#93](https://github.com/cloudquery/cq-provider-sdk/pull/93)

## [v0.4.5] - 2021-09-14

### :rocket: Added
* Added support to close migrator connection [#92](https://github.com/cloudquery/cq-provider-sdk/pull/92)


## [v0.4.4] - 2021-09-13

### :spider: Fixed
* fix resource insert logging error, print syntax error SQL on failure [#89](https://github.com/cloudquery/cq-provider-sdk/pull/89)


## [v0.4.3] - 2021-09-06

### :rocket: Added
* Added support to fetch all resources with "*" [#87](https://github.com/cloudquery/cq-provider-sdk/pull/87)

### :gear: Changed
* Partial fetch flag enabled by default on configuration (cq init [provider]) creation for new providers [#87](https://github.com/cloudquery/cq-provider-sdk/pull/87)


## [v0.4.2] - 2021-09-04

### :spider: Fixed
* fix missing table name from partial fetch error [#85](https://github.com/cloudquery/cq-provider-sdk/issues/85)


## [v0.4.1] - 2021-09-02 

### :spider: Fixed
* fix missing database connection url set [#84](https://github.com/cloudquery/cq-provider-sdk/issues/84)


## [v0.4.0] - 2021-09-02

### :rocket: Added
* Added support for partial fetching [#60](https://github.com/cloudquery/cq-provider-sdk/pull/76)


## [v0.3.4] - 2021-08-25

### :spider: Fixed
* fix edge case of migration jumps [#78](https://github.com/cloudquery/cq-provider-sdk/issues/78)


### :rocket: Added
* Added support for provider migrations [#71](https://github.com/cloudquery/cq-provider-sdk/issues/71)

## [v0.3.2] - 2021-08-11

### :spider: Fixed
* Generate random cq_id if some primary keys are null [#63](https://github.com/cloudquery/cq-provider-sdk/issues/63) fixed in [#68](https://github.com/cloudquery/cq-provider-sdk/issues/63) 

### :rocket: Added
* Added support for common resolvers [#61](https://github.com/cloudquery/cq-provider-sdk/issues/61)
    *  IP Resolver
    * INET resolver
    * Mac resolver
    * UUID resolver
    * Datetime Resolver
    * Date Resolver
    * String Transformer
    * Int Transformer

## [v0.3.1] - 2021-07-30

### :spider: Fixed
* Return error on duplicate resources request fixes [#58](https://github.com/cloudquery/cq-provider-sdk/issues/58)
* Add better recovery from panic in resolvers, printing stack and errors in log [#55](https://github.com/cloudquery/cq-provider-sdk/issues/55)

## [v0.3.0] - 2021-07-28

### :rocket: Added

* Added a changelog :)
* Added support for user defined Primary Keys in [#41](https://github.com/cloudquery/cq-provider-sdk/pull/41)
* Added support to disable delete of data [#41](https://github.com/cloudquery/cq-provider-sdk/pull/41)
* Added meta field, meta information on the resource, for example: when resource updated last. [#41](https://github.com/cloudquery/cq-provider-sdk/pull/41)

### :gear: Changed
* Changed default insert in provider from Insert to Copy-From, this method improves insert performance [#48](https://github.com/cloudquery/cq-provider-sdk/pull/48)
* **Breaking Change**: default CloudQuery "id" from `id` to `cq_id` [#41](https://github.com/cloudquery/cq-provider-sdk/pull/41)

## [0.2.8] - 2021-07-15

Base version at which changelog was introduced.
