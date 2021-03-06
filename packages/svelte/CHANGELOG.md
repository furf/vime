# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 5.0.18 (2020-12-21)


### Bug Fixes

* **angular:** revert changes in 5.0.17 ([e56912c](https://github.com/vime-js/vime/commit/e56912c66d0e26ca0cb438660b8ab3246314903e))





## 5.0.17 (2020-12-21)


### Bug Fixes

* **angular:** keep ngcc script in dist ([69df28c](https://github.com/vime-js/vime/commit/69df28c1ab6cc39993b86284d3aaf712f33c0287))





## 5.0.16 (2020-12-21)


### Bug Fixes

* **angular:** add for support angular 9/10 ([1d251f1](https://github.com/vime-js/vime/commit/1d251f1efb25f2f4879b849a15e73289393b1393)), closes [#124](https://github.com/vime-js/vime/issues/124)





## 5.0.15 (2020-12-21)

**Note:** Version bump only for package @vime/svelte





## 5.0.14 (2020-12-21)


### Bug Fixes

* **angular:** not working in production ([d7d42a4](https://github.com/vime-js/vime/commit/d7d42a46eb1373b22b2c9ab3abd0f3ab40a26ef5)), closes [#124](https://github.com/vime-js/vime/issues/124)





## 5.0.13 (2020-12-20)

**Note:** Version bump only for package @vime/svelte





## 5.0.12 (2020-12-20)

### Bug Fixes

* hls/dash provider connection not being established ([70b5e055](https://github.com/vime-js/vime/commit/70b5e055eab8aef28a9804fd3d49ca8e2ddf6a06))
* handle youtube falling back to an unstarted state after loading ([a6c3923b](https://github.com/vime-js/vime/commit/a6c3923b4d3dbf5073eeebab586301eeb530f7d1))



## 5.0.11 (2020-12-20)

### Bug Fixes

* youtube widget referrer parameter causes CORS issues ([1b6f0235](https://github.com/vime-js/vime/commit/1b6f0235fb96b02bedab5fc80cf3cf7909bf24aa))
* vimeo not hiding controls ([24a21223](https://github.com/vime-js/vime/commit/24a212236272678592017db4b64ab6ff258be2b6))




## 5.0.10 (2020-12-20)


### Bug Fixes

* avoid accidentally rendering two iframes ([a880a4e](https://github.com/vime-js/vime/commit/a880a4e36b6562b3044e7b24db399599e1fab8d9))
* embedded media (youtube/vimeo/dailymotion) not updating view type ([ef660a4](https://github.com/vime-js/vime/commit/ef660a4402a3f4d9494c96cd297e7902062f16da))


## 5.0.9 (2020-12-20)


### Bug Fixes

* file provider not setting current time when updated ([98890b9](https://github.com/vime-js/vime/commit/98890b966cac1b638c68011e028dab6c60f079f7))





## 5.0.8 (2020-12-18)


### Bug Fixes

* embed component should not load undefined `embedSrc` ([4ff11ae](https://github.com/vime-js/vime/commit/4ff11aefd68fcacdfc0a2cfecf833de9cc44f9ad))





## 5.0.7 (2020-12-18)


### Bug Fixes

* dont attempt to load youtube/dailymotion/vimeo video if `videoId` is undefined ([5acb6c7](https://github.com/vime-js/vime/commit/5acb6c7c38382010a67efc3c6f3c47010e2f6d87))





## 5.0.6 (2020-12-18)


### Bug Fixes

* **angular:** unpack dist into root package ([6be7076](https://github.com/vime-js/vime/commit/6be70767a15b8a508a949f5d916633c9574db1e7))





## 5.0.5 (2020-12-17)


### Bug Fixes

* duplicate settings in default ui ([150a8e0](https://github.com/vime-js/vime/commit/150a8e07c4eb7dbfbb9bab3195b5cc1201605c94))





## 5.0.4 (2020-12-17)

**Note:** Version bump only for package @vime/svelte





## 5.0.3 (2020-12-17)


### Bug Fixes

* adapter calls throw if called too early ([a57d68c](https://github.com/vime-js/vime/commit/a57d68c95bbad27af090f207deaa864bb2c53431))





## 5.0.2 (2020-12-17)


### Bug Fixes

* **react:** split dom/wc props ([f906522](https://github.com/vime-js/vime/commit/f9065226aaff6afd1da2d3a439b3bf8d75f1e459))





## 5.0.1 (2020-12-17)


### Bug Fixes

* **react:** pass className and style to render function ([45136c1](https://github.com/vime-js/vime/commit/45136c1dab4359590f4f43dd3b17d536ba133fb2))





# 5.0.0 (2020-12-17)


### Features

* v5 ([933347b](https://github.com/vime-js/vime/commit/933347b5fd2a38b74ef6e3f7d6a779c4b0f0d0c3))


### BREAKING CHANGES

* see #126 for a breakdown on what's new/changed.





## [4.7.3](https://github.com/vime-js/vime/compare/v4.7.2...v4.7.3) (2020-11-17)

**Note:** Version bump only for package @vime/svelte





## [4.7.2](https://github.com/vime-js/vime/compare/v4.7.1...v4.7.2) (2020-11-17)

**Note:** Version bump only for package @vime/svelte





## [4.7.1](https://github.com/vime-js/vime/compare/v4.7.0...v4.7.1) (2020-11-16)

**Note:** Version bump only for package @vime/svelte





# [4.7.0](https://github.com/vime-js/vime/compare/v4.6.0...v4.7.0) (2020-11-16)


### Bug Fixes

* **svelte:** could not resolve lib file ([2c4c850](https://github.com/vime-js/vime/commit/2c4c850969d7beb920be7790f1d8a56387611cd6)), closes [#110](https://github.com/vime-js/vime/issues/110)





# [4.6.0](https://github.com/vime-js/vime/compare/v4.5.0...v4.6.0) (2020-11-10)

**Note:** Version bump only for package @vime/svelte





# [4.5.0](https://github.com/vime-js/vime/compare/v4.4.0...v4.5.0) (2020-11-10)

**Note:** Version bump only for package @vime/svelte





# [4.4.0](https://github.com/vime-js/vime/compare/v4.3.3...v4.4.0) (2020-11-09)


### Features

* allow dynamically changing the current provider ([4a7a43d](https://github.com/vime-js/vime/commit/4a7a43d284e989f468800093662581221419d324))
* new `vime-playground` component for testing and playing with vime ([6ab4ec2](https://github.com/vime-js/vime/commit/6ab4ec2741e0af10eccaffaad8596a9df2e66b05))





## [4.3.3](https://github.com/vime-js/vime/compare/v4.3.2...v4.3.3) (2020-11-06)

**Note:** Version bump only for package @vime/svelte





## [4.3.2](https://github.com/vime-js/vime/compare/v4.3.1...v4.3.2) (2020-11-05)

**Note:** Version bump only for package @vime/svelte





## [4.3.1](https://github.com/vime-js/vime/compare/v4.3.0...v4.3.1) (2020-11-04)

**Note:** Version bump only for package @vime/svelte





# [4.3.0](https://github.com/vime-js/vime/compare/v4.2.0...v4.3.0) (2020-11-04)


### Features

* fresh output targets for all frameworks with treeshaking support + ([a4f21dc](https://github.com/vime-js/vime/commit/a4f21dcf889a6d156238e2e937e25a37fe005fb3)), closes [#82](https://github.com/vime-js/vime/issues/82) [#88](https://github.com/vime-js/vime/issues/88) [#71](https://github.com/vime-js/vime/issues/71) [#92](https://github.com/vime-js/vime/issues/92)





# [4.2.0](https://github.com/vime-js/vime/compare/v4.1.3...v4.2.0) (2020-10-02)

**Note:** Version bump only for package @vime/svelte





## [4.1.3](https://github.com/vime-js/vime/compare/v4.1.2...v4.1.3) (2020-10-01)

**Note:** Version bump only for package @vime/svelte





## [4.1.2](https://github.com/vime-js/vime/compare/v4.1.1...v4.1.2) (2020-09-26)

**Note:** Version bump only for package @vime/svelte





## [4.1.1](https://github.com/vime-js/vime/compare/v4.1.0...v4.1.1) (2020-09-25)


### Bug Fixes

* **svelte:** raw svelte files missing in package ([62f67b0](https://github.com/vime-js/vime/commit/62f67b0de182806774ae9157c6240b16c170a67a))





# [4.1.0](https://github.com/vime-js/vime/compare/v4.0.2...v4.1.0) (2020-09-23)

**Note:** Version bump only for package @vime/svelte





## [4.0.2](https://github.com/vime-js/vime/compare/v4.0.1...v4.0.2) (2020-09-22)

**Note:** Version bump only for package @vime/svelte





## [4.0.1](https://github.com/vime-js/vime/compare/v4.0.0...v4.0.1) (2020-09-21)

**Note:** Version bump only for package @vime/svelte





# [4.0.0](https://github.com/vime-js/vime/compare/v3.2.2...v4.0.0) (2020-09-20)

**Note:** Version bump only for package @vime/svelte





## [3.2.2](https://github.com/vime-js/vime/compare/v3.2.1...v3.2.2) (2020-09-17)


### Bug Fixes

* update vime description ([625f14a](https://github.com/vime-js/vime/commit/625f14ae3d0fbdd830fc6a33d035898da9ee3552))





## [3.2.1](https://github.com/vime-js/vime/compare/v3.2.0...v3.2.1) (2020-09-14)

**Note:** Version bump only for package @vime/svelte





# [3.2.0](https://github.com/vime-js/vime/compare/v3.1.0...v3.2.0) (2020-09-14)

**Note:** Version bump only for package @vime/svelte





# [3.1.0](https://github.com/vime-js/vime/compare/v3.0.2...v3.1.0) (2020-09-11)

**Note:** Version bump only for package @vime/svelte





## [3.0.2](https://github.com/vime-js/vime/compare/v3.0.1...v3.0.2) (2020-09-11)

**Note:** Version bump only for package @vime/svelte





## [3.0.1](https://github.com/vime-js/vime/compare/v3.0.0...v3.0.1) (2020-09-10)

**Note:** Version bump only for package @vime/svelte





# 3.0.0 (2020-09-10)


### Bug Fixes

* **svelte:** should import player store from dist ([6edd51b](https://github.com/vime-js/vime/commit/6edd51b43f0c5a4bbe7ca305b78237a082b96453))
* clean up changelogs ([093bcde](https://github.com/vime-js/vime/commit/093bcdec9baea44d46ec217dcdc51c4236eb255b))
* cleanup internals and integrations ([5e21c3b](https://github.com/vime-js/vime/commit/5e21c3b936e7e81fcfd60bb8b14e8f185b701039))
* include auto-gen code for libraries in git ([8bb7cf4](https://github.com/vime-js/vime/commit/8bb7cf4f655f67d2c5838a4f0c1ffb4390eaa8f2))
* packages should use @vime/core@^2 ([9703777](https://github.com/vime-js/vime/commit/9703777d9f1d6dec8f6db7ffb4010f96b0a7d421))
* type error thrown when ui root not found ([b638607](https://github.com/vime-js/vime/commit/b6386077a0266d7ecb6b5049271b45a69cc67f83))
* **core/default-controls:** no scrim on desktop video when using light theme ([1ee8dc0](https://github.com/vime-js/vime/commit/1ee8dc03990a6ec9750d3f46eedb863c1e14ac8a))


### Features

* simplify control/icon styling ([7b9aaf6](https://github.com/vime-js/vime/commit/7b9aaf68890b560aad31f6b941082e46f9700930))
* skeleton loading animation ([5afb198](https://github.com/vime-js/vime/commit/5afb19856a8d918200df7a334593b29800358485))
* **providers/file:** watch source elements for changes and call load ([a4e0165](https://github.com/vime-js/vime/commit/a4e0165ee7b323e75694ae44eb52237eb4331c86))
* **svelte:** all new svelte bindings ([acfb943](https://github.com/vime-js/vime/commit/acfb943d12ebabe176dbd5785ea0a3a2b39cc758))
* **svelte:** new usePlayer helper ([f19823b](https://github.com/vime-js/vime/commit/f19823b80b6d3c2dadfd9ad7ba64ea7826fee0d7))
* improve all framework integrations ([3eb4de7](https://github.com/vime-js/vime/commit/3eb4de767c803e3631e7304d2266b9276ec2ecdc))
* new svelte store option ([e49f6f8](https://github.com/vime-js/vime/commit/e49f6f8e1e7e3fd3d521116fc20f641d8a233d6a))


### BREAKING CHANGES

* export changes listed below.

- `PlayerProp` is now a type (union of strings) and not enum.
- `PlayerEvent` is now a type (union of strings) and not enum.
- `useInternalPlayerContext` has been removed from `@vime/react`.
- `useInternalPlayerStore` has been removed from `@vime/svelte`.
- Providers dispatch changes in a separate event (`vProviderChange`).
- Scheduler has been removed and merged in a simpler form into the `Player`.
- The `mounted` and `destroyed` props have been replaced with `attached`.
