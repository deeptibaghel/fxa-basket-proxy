<a name="1.106.0"></a>
# [1.106.0](https://github.com/mozilla/fxa-basket-proxy/compare/v1.100.0...v1.106.0) (2018-02-21)


### Bug Fixes

* **node:** use node 6.12.3 (#51) r=@vladikoff ([c78f69d](https://github.com/mozilla/fxa-basket-proxy/commit/c78f69d))

### chore

* **deps:** update deps, fix nsp (#52) r=@philbooth ([4307e25](https://github.com/mozilla/fxa-basket-proxy/commit/4307e25)), closes [(#52](https://github.com/(/issues/52)



<a name="1.100.0"></a>
# [1.100.0](https://github.com/mozilla/fxa-basket-proxy/compare/v1.99.0...v1.100.0) (2017-11-15)


### Bug Fixes

* **node:** use node 6.12.0 (#50) r=@vladikoff ([0c005eb](https://github.com/mozilla/fxa-basket-proxy/commit/0c005eb))
* **travis:** run tests with 6 and 8 (#49) ([1579354](https://github.com/mozilla/fxa-basket-proxy/commit/1579354))



<a name="1.99.0"></a>
# [1.99.0](https://github.com/mozilla/fxa-basket-proxy/compare/v1.98.0...v1.99.0) (2017-10-31)


### Features

* **events:** Add ability to discard events after a certain timestamp. (#48); r=philbooth ([39d19ee](https://github.com/mozilla/fxa-basket-proxy/commit/39d19ee))



<a name="1.98.0"></a>
# [1.98.0](https://github.com/mozilla/fxa-basket-proxy/compare/v1.97.0...v1.98.0) (2017-10-26)


### chore

* **docker:** Update to node v6.11.5 for security fix ([0ec3ab9](https://github.com/mozilla/fxa-basket-proxy/commit/0ec3ab9))



<a name="1.97.0"></a>
# [1.97.0](https://github.com/mozilla/fxa-basket-proxy/compare/v1.96.0...v1.97.0) (2017-10-03)


### chore

* **deps:** update dependencies (#46) r=vladikoff ([47c486b](https://github.com/mozilla/fxa-basket-proxy/commit/47c486b))



<a name="1.96.0"></a>
# [1.96.0](https://github.com/mozilla/fxa-basket-proxy/compare/v1.95.0...v1.96.0) (2017-09-19)


### chore

* **style:** ES6-ify ./lib/events/index.js ([35c6bd9](https://github.com/mozilla/fxa-basket-proxy/commit/35c6bd9))

### Features

* **events:** Add ability to selectively disable SQS events. ([3f6adfb](https://github.com/mozilla/fxa-basket-proxy/commit/3f6adfb))



<a name="1.95.0"></a>
# [1.95.0](https://github.com/mozilla/fxa-basket-proxy/compare/v1.92.0...v1.95.0) (2017-09-06)


### Features

* **campaigns:** Add additional newsletter campaigns ([3bbeda7](https://github.com/mozilla/fxa-basket-proxy/commit/3bbeda7))



<a name="1.92.0"></a>
# [1.92.0](https://github.com/mozilla/fxa-basket-proxy/compare/v1.91.0...v1.92.0) (2017-07-26)


### Features

* **sqs:** look for `marketingOptIn` on 'verified' events (#41) r=vladikoff ([df6bddd](https://github.com/mozilla/fxa-basket-proxy/commit/df6bddd)), closes [#40](https://github.com/mozilla/fxa-basket-proxy/issues/40)



<a name="1.91.0"></a>
# [1.91.0](https://github.com/mozilla/fxa-basket-proxy/compare/v1.75.0...v1.91.0) (2017-07-17)


### Bug Fixes

* **tests:** make tests work in node 4 and 6 ([e917f6e](https://github.com/mozilla/fxa-basket-proxy/commit/e917f6e)), closes [#38](https://github.com/mozilla/fxa-basket-proxy/issues/38)



<a name="1.75.0"></a>
# [1.75.0](https://github.com/mozilla/fxa-basket-proxy/compare/v0.74.0...v1.75.0) (2017-05-24)


### chore

* **version:** bump from v0.74.0 to v1.74.0 ([cc7dfd4](https://github.com/mozilla/fxa-basket-proxy/commit/cc7dfd4))



<a name="0.74.0"></a>
# [0.74.0](https://github.com/mozilla/fxa-basket-proxy/compare/v0.73.0...v0.74.0) (2017-05-24)


### Bug Fixes

* **version:** use cwd and env var to get version (#34) r=vladikoff ([1f7e8b0](https://github.com/mozilla/fxa-basket-proxy/commit/1f7e8b0))

### chore

* **config:** Add environment config options ([231eced](https://github.com/mozilla/fxa-basket-proxy/commit/231eced))
* **docker:** Use official node image & update to Node.js v4.8.2 (#36) r=vladikoff ([1054164](https://github.com/mozilla/fxa-basket-proxy/commit/1054164))
* **docs:** update to node 4 ([c2a4d3b](https://github.com/mozilla/fxa-basket-proxy/commit/c2a4d3b))

### Features

* **docker:** add custom feature branch (#37) r=jrgm ([827c041](https://github.com/mozilla/fxa-basket-proxy/commit/827c041))
* **docker:** Shrink Docker image size ([00f3e70](https://github.com/mozilla/fxa-basket-proxy/commit/00f3e70))



<a name="0.73.0"></a>
# [0.73.0](https://github.com/mozilla/fxa-basket-proxy/compare/v0.71.0...v0.73.0) (2016-11-02)


### Bug Fixes

* **basket:** Always send a source_url param to /subscribe ([7e88cdb](https://github.com/mozilla/fxa-basket-proxy/commit/7e88cdb))



<a name="0.71.0"></a>
# [0.71.0](https://github.com/mozilla/fxa-basket-proxy/compare/v0.64.0...v0.71.0) (2016-10-05)


### Bug Fixes

* **test:** Allow NODE_ENV=test when running the tests. ([2ee82c7](https://github.com/mozilla/fxa-basket-proxy/commit/2ee82c7))

### chore

* **deps:** Downgrade some deps for node 0.10 compatibility ([5f0878a](https://github.com/mozilla/fxa-basket-proxy/commit/5f0878a))
* **deps:** Update dependencies to latest versions. ([5f1f293](https://github.com/mozilla/fxa-basket-proxy/commit/5f1f293))

### Features

* **docker:** Add CloudOps Dockerfile & CircleCI build instructions ([726494b](https://github.com/mozilla/fxa-basket-proxy/commit/726494b))



<a name="0.64.0"></a>
# [0.64.0](https://github.com/mozilla/fxa-basket-proxy/compare/v0.63.0...v0.64.0) (2016-06-22)


### Bug Fixes

* **index:** remove unused callback ([ce858ef](https://github.com/mozilla/fxa-basket-proxy/commit/ce858ef))

### Features

* **events:** Simplify logic for utm_campaign auto-subscription. ([350bfd4](https://github.com/mozilla/fxa-basket-proxy/commit/350bfd4))



<a name="0.63.0"></a>
# [0.63.0](https://github.com/mozilla/fxa-basket-proxy/compare/v0.62.0...v0.63.0) (2016-06-02)


### Bug Fixes

* **logging:** run tests at INFO log level, fixes #25 ([1de2c93](https://github.com/mozilla/fxa-basket-proxy/commit/1de2c93)), closes [#25](https://github.com/mozilla/fxa-basket-proxy/issues/25)

### chore

* **events:** Promisify the event-handling machinery. ([654f62b](https://github.com/mozilla/fxa-basket-proxy/commit/654f62b))

### Features

* **events:** Flip subscription flags in response to certain utm_* params. ([7aa4ac7](https://github.com/mozilla/fxa-basket-proxy/commit/7aa4ac7))
* **events:** Forward metrics context from events to /fxa-activity ([836725a](https://github.com/mozilla/fxa-basket-proxy/commit/836725a))
* **metrics:** Send a `source_url` with utm params where possible. ([abf8031](https://github.com/mozilla/fxa-basket-proxy/commit/abf8031))



<a name="0.62.0"></a>
# [0.62.0](https://github.com/mozilla/fxa-basket-proxy/compare/v0.59.0...v0.62.0) (2016-05-23)


### chore

* **mozlog:** update to mozlog 2.0.4 ([4bb5a24](https://github.com/mozilla/fxa-basket-proxy/commit/4bb5a24))
* **travis:** stop running travis on node@0.12 ([8bada17](https://github.com/mozilla/fxa-basket-proxy/commit/8bada17))



<a name="0.59.0"></a>
# [0.59.0](https://github.com/mozilla/fxa-basket-proxy/compare/v0.56.1...v0.59.0) (2016-03-29)


### Bug Fixes

* **errors:** move common error handling into a basket.proxy() method ([21ff37f](https://github.com/mozilla/fxa-basket-proxy/commit/21ff37f))

### Features

* **sms:** add /subscribe_sms route ([575b848](https://github.com/mozilla/fxa-basket-proxy/commit/575b848)), closes [#21](https://github.com/mozilla/fxa-basket-proxy/issues/21)



<a name="0.56.1"></a>
## [0.56.1](https://github.com/mozilla/fxa-basket-proxy/compare/v0.56.0...v0.56.1) (2016-02-22)


### Bug Fixes

* **version:** a script to record git version info during rpm build ([c0e242d](https://github.com/mozilla/fxa-basket-proxy/commit/c0e242d))



<a name="0.56.0"></a>
# [0.56.0](https://github.com/mozilla/fxa-basket-proxy/compare/v0.50.0...v0.56.0) (2016-02-10)


### chore

* **deps:** Update dependencies ([d21fdab](https://github.com/mozilla/fxa-basket-proxy/commit/d21fdab))



<a name="0.50.0"></a>
# 0.50.0 (2015-11-18)


### Features

* **email:** explicitly fetch email address from profile data ([3cb5b31](https://github.com/mozilla/fxa-basket-proxy/commit/3cb5b31))



<a name="0.48.0"></a>
# 0.48.0 (2015-10-26)




