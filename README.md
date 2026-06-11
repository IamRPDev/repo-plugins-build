# Plugins Builder 🏗️

This repository is the automated **Builder** for **Plugins**.

## Ecosystem Role
Part of the [Kodi Build Hub](https://github.com/IamRPDev/kodi-build). This repo hosts its own releases locally.

## Build Structure
The build process strictly follows this standardized structure:
- **Source**: Upstream code is checked out into `./source/repo-plugins/`.
- **Output**: Compiled binaries are organized into `./compiled/<os>/<version>/`.
- **Artifacts**: Final files use the naming convention `repo-plugins-<os>-<version>-<branch>.[zip|tar.gz]`.

## Live Status
- **Piers (master)**: [![Piers Status](https://github.com/IamRPDev/repo-plugins-build/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/IamRPDev/repo-plugins-build/actions)
- **Omega**: [![Omega Status](https://github.com/IamRPDev/repo-plugins-build/actions/workflows/build.yml/badge.svg?branch=Omega)](https://github.com/IamRPDev/repo-plugins-build/actions)

---
*Back to [Kodi Build Hub](https://github.com/IamRPDev/kodi-build)*
