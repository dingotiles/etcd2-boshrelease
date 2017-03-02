# etcd2-boshrelease

This repository is a fork of https://github.com/cloudfoundry-incubator/etcd-release/ replacing `etcd` v2.2.0 with v2.3.8.

etcd-release itself does not yet have an upgrade plan in action to upgrade to v2.3.8 [[discussion](https://github.com/cloudfoundry-incubator/etcd-release/issues/31)]; so this is a handy fork that offers more recent etcd.

Albeit, this release has not passed thru the etcd-release CI pipeline. Differences in configuring/running etcd v2.3.8 over v2.2.0 might not have been caught before new releases of this project are cut.

## Versioning

This project will try to follow a versioning system that reflect's the released versions of etcd-release.

If etcd-release cuts v95, then this project will release v95.1. Any fixes or improvements from v95.1 will go into v95.2 and up.

## Instructions

All other instructions and readme can be found in the upstream project https://github.com/cloudfoundry-incubator/etcd-release
