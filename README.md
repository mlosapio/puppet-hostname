**Deprecation Notice:** I'm in the process of revamping my puppet work, this repo is currently not up to date.

puppet-hostname
===========

[![Puppet Forge](https://img.shields.io/puppetforge/v/halyard/hostname.svg)](https://forge.puppetlabs.com/halyard/hostname)
[![MIT Licensed](http://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://tldrlegal.com/license/mit-license)
[![Build Status](https://img.shields.io/travis/com/halyard/puppet-hostname.svg)](https://travis-ci.com/halyard/puppet-hostname)

Module to set hostname for OSX

## Usage

In your hiera config:

```
hostname::hostname: foo
```

```puppet
include hostname
```

## Required Puppet Modules

* [boxen](https://github.com/halyard/puppet-boxen)
* [sudoers](https://github.com/halyard/puppet-sudoers)

