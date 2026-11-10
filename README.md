# ripgrep

ripgrep 15.2.0: rg, a very fast recursive text search (64-bit tOS)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install ripgrep
```

| | |
|---|---|
| Version | 15.2.0 |
| Licence | MIT or Unlicense |
| Upstream | https://github.com/BurntSushi/ripgrep |
| Needs | none |
| Needs tOS build | 616 or newer |
| Size | 2223924 bytes (5668690 unpacked) |
| SHA-256 of the `.tpkg` | `299341a9326b265778551471b348ea5f2cad341a37843faa76a079e8b2d5c506` |

## Commands it adds

| Command | Runs |
|---|---|
| `rg` | `bin/rg` |

## Download

The package file (`ripgrep-15.2.0.tpkg`) and the sources it was built from are the assets of the
[v15.2.0 release](https://github.com/Artfical/tpkg-ripgrep/releases/tag/v15.2.0).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `ripgrep-15.2.0-src.tar.gz`

Check a download: `sha256sum ripgrep-15.2.0.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: MIT or Unlicense. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
