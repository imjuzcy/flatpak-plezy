# flatpak-plezy

Flatpak packaging repository for [Plezy](https://github.com/edde746/plezy), a Plex client.

## Contents

- `flatpak.yml`: Flatpak manifest and module definitions.
- `extra/`: Desktop file, icon, and AppStream metadata.
- `patches/`: Packaging patches applied to the upstream Plezy source during build.

## Build and release

This repository builds the Flatpak bundle with GitHub Actions using `.github/workflows/build.yml`.

## License

This repository is licensed under **GPL-3.0-only**. See [LICENSE](./LICENSE).
