# Changelog

All notable changes to this project will be documented in this file.
Each new release typically also includes the latest modulesync defaults.
These should not affect the functionality of the module.

## [v4.0.0](https://github.com/voxpupuli/puppet-make/tree/v4.0.0) (2021-05-18)

[Full Changelog](https://github.com/voxpupuli/puppet-make/compare/v3.0.0...v4.0.0)

**Breaking changes:**

- Drop EoL CentOS 6 support [\#54](https://github.com/voxpupuli/puppet-make/pull/54) ([bastelfreak](https://github.com/bastelfreak))
- Drop EoL Puppet 5 support [\#53](https://github.com/voxpupuli/puppet-make/pull/53) ([bastelfreak](https://github.com/bastelfreak))
- drop Ubuntu 14.04 support [\#43](https://github.com/voxpupuli/puppet-make/pull/43) ([bastelfreak](https://github.com/bastelfreak))

**Implemented enhancements:**

- Add Ubuntu 18.04/20.04 & CentOS 8 support [\#58](https://github.com/voxpupuli/puppet-make/pull/58) ([bastelfreak](https://github.com/bastelfreak))
- puppetlabs/stdlib: allow 7.x [\#57](https://github.com/voxpupuli/puppet-make/pull/57) ([bastelfreak](https://github.com/bastelfreak))
- Add datatypes + puppet-strings docs [\#56](https://github.com/voxpupuli/puppet-make/pull/56) ([bastelfreak](https://github.com/bastelfreak))
- Support Puppet 7 [\#51](https://github.com/voxpupuli/puppet-make/pull/51) ([mattock](https://github.com/mattock))

**Merged pull requests:**

- Enable acceptance tests [\#55](https://github.com/voxpupuli/puppet-make/pull/55) ([bastelfreak](https://github.com/bastelfreak))
- modulesync 3.0.0 & puppet-lint updates [\#48](https://github.com/voxpupuli/puppet-make/pull/48) ([bastelfreak](https://github.com/bastelfreak))
- update repo links to https [\#46](https://github.com/voxpupuli/puppet-make/pull/46) ([bastelfreak](https://github.com/bastelfreak))

## [v3.0.0](https://github.com/voxpupuli/puppet-make/tree/v3.0.0) (2019-07-29)

[Full Changelog](https://github.com/voxpupuli/puppet-make/compare/v2.1.1...v3.0.0)

**Breaking changes:**

- modulesync 2.7.0 and drop puppet 4 [\#40](https://github.com/voxpupuli/puppet-make/pull/40) ([bastelfreak](https://github.com/bastelfreak))

**Merged pull requests:**

- allow stdlib 6.x & release 3.0.0 [\#42](https://github.com/voxpupuli/puppet-make/pull/42) ([bastelfreak](https://github.com/bastelfreak))

## [v2.1.1](https://github.com/voxpupuli/puppet-make/tree/v2.1.1) (2018-10-03)

[Full Changelog](https://github.com/voxpupuli/puppet-make/compare/v2.1.0...v2.1.1)

**Merged pull requests:**

- modulesync 2.0.0 & allow puppet 6.x [\#35](https://github.com/voxpupuli/puppet-make/pull/35) ([bastelfreak](https://github.com/bastelfreak))
- allow puppetlabs/stdlib 5.x [\#33](https://github.com/voxpupuli/puppet-make/pull/33) ([bastelfreak](https://github.com/bastelfreak))

## [v2.1.0](https://github.com/voxpupuli/puppet-make/tree/v2.1.0) (2018-06-17)

[Full Changelog](https://github.com/voxpupuli/puppet-make/compare/v2.0.0...v2.1.0)

**Merged pull requests:**

- Remove docker nodesets [\#28](https://github.com/voxpupuli/puppet-make/pull/28) ([bastelfreak](https://github.com/bastelfreak))
- drop EOL OSs; fix puppet version range [\#27](https://github.com/voxpupuli/puppet-make/pull/27) ([bastelfreak](https://github.com/bastelfreak))
- drop EOL OSs; fix puppet version range [\#24](https://github.com/voxpupuli/puppet-make/pull/24) ([bastelfreak](https://github.com/bastelfreak))

## [v2.0.0](https://github.com/voxpupuli/puppet-make/tree/v2.0.0) (2017-11-13)

[Full Changelog](https://github.com/voxpupuli/puppet-make/compare/v1.1.0...v2.0.0)

**Implemented enhancements:**

- \[Issue \#15\] Uses stdlib ensure\_packages to avoid duplicate declaration errors [\#16](https://github.com/voxpupuli/puppet-make/pull/16) ([EmersonPrado](https://github.com/EmersonPrado))

**Closed issues:**

- Use stdlib ensure\_packages function to avoid duplicate declaration errors [\#15](https://github.com/voxpupuli/puppet-make/issues/15)

**Merged pull requests:**

- Fix github license detection [\#17](https://github.com/voxpupuli/puppet-make/pull/17) ([alexjfisher](https://github.com/alexjfisher))

## [v1.1.0](https://github.com/voxpupuli/puppet-make/tree/v1.1.0) (2017-01-13)

This is the last release with Puppet 3 support!
* Bump minimum version_requirement for Puppet

## 2016-11-27 Release 1.0.1
* Initial modulesync with voxpupuli (#4)

## 2016-11-17 Release 1.0.0
* simplify module: add parameters, remove params (igalic)
* remove dead code (ghoneycutt)
* simplify spec tests (ghoneycutt)
* move tests/ to examples (ghoneycutt)

## 2015-01-16 Release 0.0.5
* Fix a couple of deprecated rspec-puppet test cases
* Disable rspec-system and blacksmith
* Change metadata author as requested

## 2015-01-16 Release 0.0.4
* Fix many file modes that I broke in 0.0.3

## 2015-01-16 Release 0.0.3
* Assuming ownership of apparently abandoned module

## 2013-11-08 Release 0.0.2
* Releasing a cleaned-up version of this module
* Moved ownership over to Element84
* Added tests

## 2012-01-16 Release 0.0.1
* Initial release


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
