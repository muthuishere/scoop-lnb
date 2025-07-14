# LNB Scoop Bucket

This repository contains the Scoop bucket for [LNB](https://github.com/muthuishere/lnb) - a cross-platform utility that makes command-line tools accessible from anywhere.

## Installation

```powershell
# Add the bucket
scoop bucket add lnb https://github.com/muthuishere/scoop-lnb

# Install LNB
scoop install lnb
```

## Usage

After installation, the `lnb` command will be available in your PATH:

```cmd
lnb help
lnb install ./mybinary.exe
lnb list
```

## Manual Installation

If you prefer to install without adding the bucket:

```powershell
scoop install https://raw.githubusercontent.com/muthuishere/scoop-lnb/main/bucket/lnb.json
```

## Updating

To update to the latest version:

```powershell
scoop update lnb
```

## About

This bucket is automatically maintained by the LNB release process. The manifest file (`bucket/lnb.json`) is updated automatically when new versions of LNB are released.

## Links

- **Main Project**: https://github.com/muthuishere/lnb
- **Documentation**: https://github.com/muthuishere/lnb#readme
- **Issues**: https://github.com/muthuishere/lnb/issues
