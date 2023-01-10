# path-pipeline-test

[![Release](https://jitpack.io/v/mxenabled/path-tools.svg)](https://jitpack.io/p/mxenabled/path-tools)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)

Current Version: 1.1.2<!-- x-release-please-version -->

## Usage:

_In build.gradle_

<!-- x-release-please-start-version -->
```groovy
implementation "com.github.mxenabled:path-pipeline-test:1.1.2"
```
<!-- x-release-please-end -->

## Releasing snapshot

1. Create a chore commit on the branch to be released (currently, only configured to work on master).

_Example:_

`git commit --allow-empty -m "chore: release 1.1.2-SNAPSHOT" -m "Release-As: 1.1.2-SNAPSHOT"`

2. Push branch
3. Merge release PR
