# buildsrc

A collection of build related shell scripts and recipes.

## Metadata

- Status: Under Development
- Type: Library
- Versioning: Semantic Versioning
- Documentation: This file, the source files, and the [wiki](https://www.github.com/brightcove/buildsrc)
- Maintainers: [CODEOWNERS](CODEOWNERS)
- Contact/Questions/Issues: [GitHub Issues](https://www.github.com/brightcove/buildsrc/issues)
- Contributions: Contributions are welcome.
  Open an Issue first for any non-trivial PR to verify the suitability of envisioned changes.

## Overview

This repository serves as a consolidated home for assorted build logic.
Initially this will entail this being the canonical representation for any
such scripts which can then be copied and pasted as needed into desired locations.
If warranted, a more automated means of updating the scripts will be provided.

Each script initially will be fairly self contained, so individual scripts should
include all their relevant documentation.

## Installation

Copypasta

###
This script depends on a few tools and variables. This tool depends on git being install and a prop files.

Define a properties file like so:
```
export PROP_FILE  := build.properties
```

build.properties needs the following variables defined in them:

```
VERSION=1.0.0-SNAPSHOT
REPO_URL=https://github.com/brightcove/buildsrc
```
