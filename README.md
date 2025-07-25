# Velox OS - Manifest

This is the manifest repository for Velox OS.

## Getting Started

```bash
repo init -u https://github.com/Velox-Os/platform_manifest.git -b velox-15
repo sync -c --force-sync --no-tags --no-clone-bundle -j$(nproc --all)

