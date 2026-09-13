[Arabic](README.md) | [English]

# A2kliDis Scoop Bucket

A Scoop bucket for installing and managing Windows applications. This repository currently provides a manifest for [Mangayomi](https://github.com/kodjodevf/mangayomi).

[![CI](https://github.com/A2kliDis/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/A2kliDis/scoop-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/A2kliDis/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/A2kliDis/scoop-bucket/actions/workflows/excavator.yml)

## Installation

Install [Scoop](https://scoop.sh), then add this bucket and install Mangayomi:

```powershell
scoop bucket add a2klidis https://github.com/A2kliDis/scoop-bucket
scoop install a2klidis/mangayomi
```

## Updating

To update the application manually:

```powershell
scoop update
scoop update mangayomi
```

New Mangayomi releases are checked automatically every four hours by GitHub Actions. You can follow the checks and updates from the [Actions](https://github.com/A2kliDis/scoop-bucket/actions) tab.

## Contributing

Manifests are stored in the `bucket` directory. Each manifest should have a valid download URL and SHA256 hash, with `checkver` and `autoupdate` configured when available.
