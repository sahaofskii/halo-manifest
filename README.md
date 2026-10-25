# halo-manifest

The signed control file of the [Halo](https://github.com/sahaofskii/halo-releases) app: update notices, messages and feature switches.

- `manifest.json` is the current file. The app reads it and accepts it only if it carries a valid signature from the Halo release keys built into the app; an unsigned or edited file is ignored.
- `history/` keeps every published file by its sequence number.

Files here are written by the owner's signing tool. Do not edit them by hand: any change breaks the signature.
