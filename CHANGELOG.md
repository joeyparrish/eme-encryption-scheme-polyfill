# Changelog


### [1.0.1](https://github.com/joeyparrish/eme-encryption-scheme-polyfill/compare/v1.0.0...v1.0.1) (2022-03-03)


### Bug Fixes

* Check if McEncryptionSchemePolyfill is installed ([#17](https://github.com/joeyparrish/eme-encryption-scheme-polyfill/issues/17)) ([cd12df6](https://github.com/joeyparrish/eme-encryption-scheme-polyfill/commit/cd12df6b5053a58f29ceda423582618ad06ecc27)), closes [#16](https://github.com/joeyparrish/eme-encryption-scheme-polyfill/issues/16)
* **deps:** Update all dependencies ([#32](https://github.com/joeyparrish/eme-encryption-scheme-polyfill/issues/32)) ([761dece](https://github.com/joeyparrish/eme-encryption-scheme-polyfill/commit/761deceb36e28063ebf25077af10fea9a848901e))
* Support browsers with clear MCap but no encrypted MCap ([#18](https://github.com/joeyparrish/eme-encryption-scheme-polyfill/issues/18)) ([7191c50](https://github.com/joeyparrish/eme-encryption-scheme-polyfill/commit/7191c509f5d038eee2ed82fdef955fe25ce699b8))

## 2.0.3 (2021-04-19)

Bugfixes:
  - Fix MCap polyfill for browsers that support MCap but not the
    encryption-related parts of the MCap API.


## 2.0.2 (2021-02-05)

Bugfixes:
  - Fix infinite recursion when the MCap part of the polyfill is installed
    twice.
  - Fix exception when MCap returns a supported==false on encrypted content.


## 2.0.1 (2020-02-21)

Bugfixes:
  - Fix exception thrown on some legacy Edge versions


## 2.0.0 (2019-12-12)

Features:
  - Added support for polyfilling MediaCapabilities, too
    - https://github.com/w3c/media-capabilities/issues/100


## 1.0.3 (2019-12-05)

Bugfixes:
  - Update cbcs-recommended to cbcs-1-9 to keep up with spec changes


## 1.0.2 (2019-12-02)

Bugfixes:
  - Fix infinite recursion when the polyfill is installed twice.


## 1.0.1 (2019-11-22)

Bugfixes:
  - Fix RequireJS support
  - Workaround babel translation bug that resulted in undefined return value
  - Fix errors in Closure Compiler with strictest settings

Features:
  - Added a demo / manual testing page
    - https://google.github.io/eme-encryption-scheme-polyfill/demo/


## 1.0.0 (2019-11-18)

First public release.
