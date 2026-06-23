# psiphon-builder

Automated binary builds for Psiphon's tunnel core.

This repository periodically monitors the upstream Psiphon Tunnel Core source code and automatically produces precompiled binaries for multiple operating systems and architectures.

## What this repository does

* Tracks upstream changes from `Psiphon-Labs/psiphon-tunnel-core`
* Automatically builds binaries using GitHub Actions
* Publishes binaries as GitHub Releases
* Supports Linux, Windows, and macOS
* Supports x86_64 and ARM64 architectures

## Release Naming

Each release corresponds to a specific upstream commit and is named using the upstream commit SHA:

```text
upstream-<commit-sha>
```

This makes every build reproducible and traceable to the exact source revision used.

## Disclaimer

This is an unofficial community-maintained build repository.

All source code belongs to the Psiphon project and its respective contributors. This repository only automates compilation and distribution of binaries generated from the upstream source code.

Upstream source:

https://github.com/Psiphon-Labs/psiphon-tunnel-core
