# ApkHub Scoop Bucket

[![Tests](https://github.com/huanfeng/apkhub-scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/huanfeng/apkhub-scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/huanfeng/apkhub-scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/huanfeng/apkhub-scoop-bucket/actions/workflows/excavator.yml)

Scoop bucket for [ApkHub CLI](https://github.com/huanfeng/apkhub-cli), a command-line tool for managing distributed APK repositories.

## Installation

To install ApkHub CLI using Scoop:

```pwsh
# Add the bucket
scoop bucket add apkhub-bucket https://github.com/huanfeng/apkhub-scoop-bucket

# Install ApkHub CLI
scoop install apkhub-bucket/apkhub

# Verify installation
apkhub version
```

## Update

To update ApkHub CLI:

```pwsh
scoop update apkhub
```

## Available Apps

- **apkhub** - A command-line tool for managing distributed APK repositories

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
