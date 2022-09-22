# Homebrew Tap for V8

This homebrew tap provides easy access to current and former V8 versions.

For now, installation needs to be done with `--build-from-source` otherwise it attempts to download bottles from an invalid url (https://ghcr.io/v2/homebrew/core/v8-10.2/... rather than https://ghcr.io/v2/homebrew/core/v8/...)

## Usage

```sh
$ brew install dharesign/homebrew-v8/v8-9.8 --build-from-source
```
