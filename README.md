# pally-automation-enclave-deploy

This repository is the public Tinfoil config and release repo for the Pally
automation enclave.

It intentionally contains release-tagged deployment metadata only:

- `tinfoil-config.yml` pinned to an exact private GHCR image digest
- Git tags and GitHub releases consumed by Tinfoil
- measured deployment artifacts attached to each release

Source code and image builds live in the private repo:

- `Get-Pally/pally-automation-enclave`
