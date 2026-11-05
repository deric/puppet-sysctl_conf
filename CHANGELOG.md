# Changelog

## Release 2.0.0 [2026-11-05]

 - Drop support for Debian 10 and Ubuntu 18.04
 - Add support for Debian 13 and Ubuntu 24.04
 - Allow Puppet 9 (`>= 7.0.0 < 10.0.0`)
 - Allow `puppet-augeasproviders_core` < 6.0.0 and `puppet-augeasproviders_sysctl` < 5.0.0
 - PDK update to 3.4.0 (templates 3.5.1)
 - CI: test against Ruby 3.2 and 3.3 with Puppet 8, drop Ruby 2.7 and 3.1 (#9)

[Full Changelog](https://github.com/deric/puppet-sysctl_conf/compare/v1.0.0...v2.0.0)

## Release 1.0.0 [2023-06-25]

 - PDK update
 - Drop Puppet 6
 - Test agains ruby 3.2

[Full Changelog](https://github.com/deric/puppet-sysctl_conf/compare/v0.4.0...v1.0.0)


## Release 0.4.0 [2023-06-22]

 - Use `puppet-augeasproviders_core` and `puppet-augeasproviders_sysctl` dependecies instead of `herculesteam-augeasproviders_core` and `herculesteam-augeasproviders_sysctl` (#7)
 - Don't quote integers

[Full Changelog](https://github.com/deric/puppet-sysctl_conf/compare/v0.3.0...v0.4.0)

## Release 0.3.0 [2022-05-05]

 - Allow passing values as `Integer` (#3, [#5](https://github.com/deric/puppet-sysctl_conf/pull/5))

[Full Changelog](https://github.com/deric/puppet-sysctl_conf/compare/v0.2.1...v0.3.0)

## Release 0.2.1

 - Allow newer augeas dependencies
 - Updated supported systems

## Release 0.2.0

 - Include default merge options (#2)

## Release 0.1.1

 - Use semantic version formatting for module dependencies (#1)

## Release 0.1.0

**Features**

  Initial version

**Bugfixes**

**Known Issues**
