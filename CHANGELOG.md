# Changelog

## 1.0.0 (2026-11-21)


### ⚠ BREAKING CHANGES

* **app:** read config.json from next to the executable
* **core:** remove the built-in default rules
* **app:** remove the --dump and --redaction-test modes

### Features

* add catch-all rule and never capture shell or own windows ([c5cdab1](https://github.com/sxvan/open-timesheet/commit/c5cdab1f433d9dcd6db1955595933edd8d206793))
* add log-only rule mode and rename non_work to other ([d0b8248](https://github.com/sxvan/open-timesheet/commit/d0b82488938b206fcbd273bda25ec7858f97a263))
* add M1 monitoring with events table ([e7f7eeb](https://github.com/sxvan/open-timesheet/commit/e7f7eeb2ccc8f1c91c0841b2af9a71f9f65135b6))
* add M3 allowlisted per-window capture and per-monitor compositing ([351de3e](https://github.com/sxvan/open-timesheet/commit/351de3ea4e04d44dc5fd2474a64200ab78c167f5))
* add M4 per-window images, dedupe, captures tables and retention ([19a5555](https://github.com/sxvan/open-timesheet/commit/19a55554b5b474c13eb5184df92a1e75f193ecbc))
* add M5 tray application, pause, autostart and single-file publish ([767ad55](https://github.com/sxvan/open-timesheet/commit/767ad5584e04f30c50a89695180421dc2ea730ba))
* add OCR-based secret redaction with heuristic detector ([0a982b9](https://github.com/sxvan/open-timesheet/commit/0a982b9ceb363a65b76c0453d5f65ad5cb4719a6))
* **app:** drive trigger engine from monitor signals and log capture decisions ([fc9c797](https://github.com/sxvan/open-timesheet/commit/fc9c797f5045f435803112749cb81994c4979198))
* **app:** read config.json from next to the executable ([55a9c79](https://github.com/sxvan/open-timesheet/commit/55a9c793e9b9e9d9c492790dc72496dc10514bda))
* **core:** add capture trigger state machine with tests ([131651a](https://github.com/sxvan/open-timesheet/commit/131651a4f4c3e5fd1af1fe4af36670781a918c9e))
* **core:** add region math, capture planner, compositor and redaction types ([7cd32cb](https://github.com/sxvan/open-timesheet/commit/7cd32cb1a7c548c256089be5bd6707d5c434635e))
* **core:** detect more provider token formats ([71abff1](https://github.com/sxvan/open-timesheet/commit/71abff1aca4fbe00bac0b5b36a096e55d7cbe319))
* **core:** find passwords from context and drop the Laya experiment ([1d96d0a](https://github.com/sxvan/open-timesheet/commit/1d96d0a1df0a5337debb718bc0b7b1ad7e8bf522))
* keep scrubbed screen text as its own storage layer ([252e47b](https://github.com/sxvan/open-timesheet/commit/252e47b54d9d3ccd36e911a2042060144470d911))
* make URL query stripping opt-in and document the layers ([5d85a8b](https://github.com/sxvan/open-timesheet/commit/5d85a8b26d4d89867e1dcaaca35a6195775ad12d))
* **prototype:** add M0 per-window capture console app ([30da48b](https://github.com/sxvan/open-timesheet/commit/30da48b97d51c341e0ac739628ea1a50573bb9db))
* skip captures while a password field has focus ([6137c96](https://github.com/sxvan/open-timesheet/commit/6137c96519aff32accb644f521afc975e03a5ce5))
* **storage:** scale saved images down to a configurable maximum size ([8c8b437](https://github.com/sxvan/open-timesheet/commit/8c8b43703b2017982d91a0528d8e5aced437b914))
* store scrubbed OCR text and redact window titles ([ec00a46](https://github.com/sxvan/open-timesheet/commit/ec00a4668aecc36a3851ccbcf5a24492d49c942a))


### Bug Fixes

* **core:** label coalesced captures as window_switch when one was involved ([c936ca4](https://github.com/sxvan/open-timesheet/commit/c936ca46279db6da3c1552a9d1a82bfe34d8d86f))
* **core:** stop redacting ordinary prose that mentions passwords ([2f16b9a](https://github.com/sxvan/open-timesheet/commit/2f16b9aad4d3489693ad6de04ce0091328cb8a28))
* stop invisible overlays from blacking out captured windows ([aa97057](https://github.com/sxvan/open-timesheet/commit/aa9705702a91f73a783e1bbb5675e0ac90f3fd6d))
* stop invisible overlays from blacking out captured windows ([b9e9bdb](https://github.com/sxvan/open-timesheet/commit/b9e9bdb547c1b3ec2ceb882b2c1651df9df0dc3d))
* **windows:** place redaction boxes exactly on the recognized words ([81de0ba](https://github.com/sxvan/open-timesheet/commit/81de0baaf8fbf419643340f13d4806724685de89))


### Code Refactoring

* **app:** remove the --dump and --redaction-test modes ([dbb230c](https://github.com/sxvan/open-timesheet/commit/dbb230c09e71b17aee0b76813c860ef607f13368))
* **core:** remove the built-in default rules ([c73c88e](https://github.com/sxvan/open-timesheet/commit/c73c88e13f69cc77809485dea9ddaaf5f1ce2b47))
