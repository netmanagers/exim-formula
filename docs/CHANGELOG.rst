
Changelog
=========

`0.7.0 <https://github.com/saltstack-formulas/exim-formula/compare/v0.6.1...v0.7.0>`_ (2020-05-08)
------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **libtofs:** “files_switch” mess up the variable exported by “map.jinja” [skip ci] (\ `c7cbd5c <https://github.com/saltstack-formulas/exim-formula/commit/c7cbd5c773c155a64f25aa7d7298862a3c4ad494>`_\ )
* **release.config.js:** use full commit hash in commit link [skip ci] (\ `8356de8 <https://github.com/saltstack-formulas/exim-formula/commit/8356de82dc9aec66e25dd5a0a30f7ea933be3db7>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile:** restrict ``train`` gem version until upstream fix [skip ci] (\ `bdb1196 <https://github.com/saltstack-formulas/exim-formula/commit/bdb11961c18f61dc1d54880f12e7a5a89a58d50c>`_\ )
* **gemfile.lock:** add to repo with updated ``Gemfile`` [skip ci] (\ `7e1a0c1 <https://github.com/saltstack-formulas/exim-formula/commit/7e1a0c19aaabc38539ddd819d0735228dc3b4506>`_\ )
* **kitchen:** avoid using bootstrap for ``master`` instances [skip ci] (\ `b40fa5f <https://github.com/saltstack-formulas/exim-formula/commit/b40fa5fc387e6b79349082a76dbeda1bb3bbd044>`_\ )
* **kitchen:** use ``debian-10-master-py3`` instead of ``develop`` [skip ci] (\ `c9fa91a <https://github.com/saltstack-formulas/exim-formula/commit/c9fa91a656989de080d5b5b4156fcf74a3446d37>`_\ )
* **kitchen:** use ``develop`` image until ``master`` is ready (\ ``amazonlinux``\ ) [skip ci] (\ `edca139 <https://github.com/saltstack-formulas/exim-formula/commit/edca1399abc9c8858b434f41a1a7909c946fa366>`_\ )
* **kitchen+travis:** remove ``master-py2-arch-base-latest`` [skip ci] (\ `88b504b <https://github.com/saltstack-formulas/exim-formula/commit/88b504b7b3318b0277637fdf95ac5d7d7eb180e9>`_\ )
* **kitchen+travis:** upgrade matrix after ``2019.2.2`` release [skip ci] (\ `ef89686 <https://github.com/saltstack-formulas/exim-formula/commit/ef8968607a2007f33094712fbb206227513ff733>`_\ )
* **travis:** apply changes from build config validation [skip ci] (\ `00b5f30 <https://github.com/saltstack-formulas/exim-formula/commit/00b5f307a3b71e3d8e983b522f85b46132472cb8>`_\ )
* **travis:** opt-in to ``dpl v2`` to complete build config validation [skip ci] (\ `bebca43 <https://github.com/saltstack-formulas/exim-formula/commit/bebca43d482282366ceed95410670d87e791135e>`_\ )
* **travis:** quote pathspecs used with ``git ls-files`` [skip ci] (\ `00fc26f <https://github.com/saltstack-formulas/exim-formula/commit/00fc26f73ef9c1b50c6cb2bc19873e24dc9e248b>`_\ )
* **travis:** run ``shellcheck`` during lint job [skip ci] (\ `c2f403b <https://github.com/saltstack-formulas/exim-formula/commit/c2f403b881bda1f32583f3c24b37446688dffd46>`_\ )
* **travis:** update ``salt-lint`` config for ``v0.0.10`` [skip ci] (\ `7cb4790 <https://github.com/saltstack-formulas/exim-formula/commit/7cb4790564f3a8856a1de49289bbddf1a7112896>`_\ )
* **travis:** use ``major.minor`` for ``semantic-release`` version [skip ci] (\ `29ab6b3 <https://github.com/saltstack-formulas/exim-formula/commit/29ab6b328e8fef16445157e488f149a512b29b7d>`_\ )
* **travis:** use build config validation (beta) [skip ci] (\ `5eb57e3 <https://github.com/saltstack-formulas/exim-formula/commit/5eb57e3700c820f7b0bb5125c5699c3b4ed413e0>`_\ )
* **workflows/commitlint:** add to repo [skip ci] (\ `c07995c <https://github.com/saltstack-formulas/exim-formula/commit/c07995c3cdf6717e166051684e39dcaa46d3a91f>`_\ )

Documentation
^^^^^^^^^^^^^


* **contributing:** remove to use org-level file instead [skip ci] (\ `b0994c9 <https://github.com/saltstack-formulas/exim-formula/commit/b0994c9112d0d2c332452d88e556a777dd7225e2>`_\ )
* **readme:** update link to ``CONTRIBUTING`` [skip ci] (\ `96b07dd <https://github.com/saltstack-formulas/exim-formula/commit/96b07dd6e75b0b486a3bc7fd14fd1dda06ce5b84>`_\ )

Features
^^^^^^^^


* **config:** allow to manage config files under CONFDIR (\ `fd6debd <https://github.com/saltstack-formulas/exim-formula/commit/fd6debd529838eeb58bd954247cbd46b0d81254c>`_\ ), closes `#17 <https://github.com/saltstack-formulas/exim-formula/issues/17>`_

Performance Improvements
^^^^^^^^^^^^^^^^^^^^^^^^


* **travis:** improve ``salt-lint`` invocation [skip ci] (\ `b4a8f6a <https://github.com/saltstack-formulas/exim-formula/commit/b4a8f6a334600d8e4a4a4cf5756c213aacb3f87d>`_\ )

`0.6.1 <https://github.com/saltstack-formulas/exim-formula/compare/v0.6.0...v0.6.1>`_ (2019-10-12)
------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **rubocop:** add fixes using ``rubocop --safe-auto-correct`` (\ ` <https://github.com/saltstack-formulas/exim-formula/commit/d7ffc2c>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/exim-formula/commit/efef553>`_\ )
* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/exim-formula/commit/6030d81>`_\ )
* **travis:** merge ``rubocop`` linter into main ``lint`` job (\ ` <https://github.com/saltstack-formulas/exim-formula/commit/5da375b>`_\ )

`0.6.0 <https://github.com/saltstack-formulas/exim-formula/compare/v0.5.0...v0.6.0>`_ (2019-10-08)
------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **pillar:** accept 'true'/True/true for booleans in pillars (\ `afe3e70 <https://github.com/saltstack-formulas/exim-formula/commit/afe3e70>`_\ )
* **pillar:** some config values can be treated as lists (\ `481966d <https://github.com/saltstack-formulas/exim-formula/commit/481966d>`_\ )

`0.5.0 <https://github.com/saltstack-formulas/exim-formula/compare/v0.4.0...v0.5.0>`_ (2019-10-05)
------------------------------------------------------------------------------------------------------

Code Refactoring
^^^^^^^^^^^^^^^^


* **pillars:** extract default values to pillars (\ `72299cc <https://github.com/saltstack-formulas/exim-formula/commit/72299cc>`_\ )

Features
^^^^^^^^


* **tofs:** add TOFS pattern (\ `7222790 <https://github.com/saltstack-formulas/exim-formula/commit/7222790>`_\ )

`0.4.0 <https://github.com/saltstack-formulas/exim-formula/compare/v0.3.0...v0.4.0>`_ (2019-10-04)
------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **states:** add missing require sls (\ `726df07 <https://github.com/saltstack-formulas/exim-formula/commit/726df07>`_\ )
* **states:** re-generate Exim aliases DB after update (\ `6a0aecf <https://github.com/saltstack-formulas/exim-formula/commit/6a0aecf>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** install required packages to bootstrapped ``opensuse`` [skip ci] (\ `63a132e <https://github.com/saltstack-formulas/exim-formula/commit/63a132e>`_\ )
* **kitchen:** use bootstrapped ``opensuse`` images until ``2019.2.2`` [skip ci] (\ `f1efdc9 <https://github.com/saltstack-formulas/exim-formula/commit/f1efdc9>`_\ )
* **platform:** add ``arch-base-latest`` (commented out for now) [skip ci] (\ `89918b2 <https://github.com/saltstack-formulas/exim-formula/commit/89918b2>`_\ )

Features
^^^^^^^^


* **states:** add exim.mailname and exim.aliases states (\ `68bb801 <https://github.com/saltstack-formulas/exim-formula/commit/68bb801>`_\ )

Performance Improvements
^^^^^^^^^^^^^^^^^^^^^^^^


* **states:** reuse already fetched pillars (\ `c466c86 <https://github.com/saltstack-formulas/exim-formula/commit/c466c86>`_\ )

Tests
^^^^^


* **inspec:** check that smtp port is opened (\ `a6418d3 <https://github.com/saltstack-formulas/exim-formula/commit/a6418d3>`_\ )

`0.3.0 <https://github.com/saltstack-formulas/exim-formula/compare/v0.2.1...v0.3.0>`_ (2019-09-25)
------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **map:** sync map.jinja with template-formula (\ `5ddd1c9 <https://github.com/saltstack-formulas/exim-formula/commit/5ddd1c9>`_\ )

`0.2.1 <https://github.com/saltstack-formulas/exim-formula/compare/v0.2.0...v0.2.1>`_ (2019-09-23)
------------------------------------------------------------------------------------------------------

Code Refactoring
^^^^^^^^^^^^^^^^


* **states:** split exim metastate in .package/.config/.service (\ `a947ba9 <https://github.com/saltstack-formulas/exim-formula/commit/a947ba9>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** change ``log_level`` to ``debug`` instead of ``info`` (\ `56d9573 <https://github.com/saltstack-formulas/exim-formula/commit/56d9573>`_\ )

`0.2.0 <https://github.com/saltstack-formulas/exim-formula/compare/v0.1.0...v0.2.0>`_ (2019-09-19)
------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **inspec:** remove not supported platforms (\ `2e2de5e <https://github.com/saltstack-formulas/exim-formula/commit/2e2de5e>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** add Kitchen tests (\ `a5e936d <https://github.com/saltstack-formulas/exim-formula/commit/a5e936d>`_\ )
* **travis:** reduce test matrix (\ `a136c60 <https://github.com/saltstack-formulas/exim-formula/commit/a136c60>`_\ )

Documentation
^^^^^^^^^^^^^


* **fix:** fix formula description (\ `04cb323 <https://github.com/saltstack-formulas/exim-formula/commit/04cb323>`_\ )
* **pillar:** update link to Debian documentation (\ `2cd96e4 <https://github.com/saltstack-formulas/exim-formula/commit/2cd96e4>`_\ )

Features
^^^^^^^^


* **semantic-release:** add semantic-release (\ `d00a7bf <https://github.com/saltstack-formulas/exim-formula/commit/d00a7bf>`_\ )

Styles
^^^^^^


* **yaml:** fix yaml linter warning (\ `3a219ab <https://github.com/saltstack-formulas/exim-formula/commit/3a219ab>`_\ )
