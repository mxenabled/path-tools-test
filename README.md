# path-pipeline-test

[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)

Current Version: 1.1.10<!-- x-release-version -->

## Usage:

_In build.gradle_

```groovy
implementation "com.github.mxenabled:path-pipeline-test:1.1.10" // x-release-version
```

## Releasing snapshot

1. Create a chore commit on the branch to be released (currently, only configured to work on master).

_Example:_

`git commit --allow-empty -m "chore: release 1.1.2-SNAPSHOT" -m "Release-As: 1.1.2-SNAPSHOT"`

2. Push branch
3. Merge release PR
