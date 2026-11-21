# Kalisch-Smith 2025 — 3D models of the early human umbilical vasculature

A **verbatim mirror** of [`10.25446/oxford.28883651`](https://doi.org/10.25446/oxford.28883651), redistributed under the terms of the licence the depositors chose. No file has been modified.

## Attribution

> Kalisch-Smith, Jacinta I.
>
> Kalisch-Smith JI (2025). 3D models of the early human umbilical vasculature. University of Oxford ORA.
>
> DOI: [10.25446/oxford.28883651](https://doi.org/10.25446/oxford.28883651) — licensed **CC BY 4.0**

Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/); see [`LICENSE`](LICENSE). You may share and adapt this material for any purpose, including commercially, provided you give appropriate credit, link to the licence and indicate if changes were made. **This mirror makes no changes.**

## What this is

A multi-page TIFF image stack of 3D models of the early human umbilical vasculature across Carnegie stages. Image data rather than mesh geometry, so extracting vessel centrelines or a surface requires segmentation.

## Contents

1 file(s), 17.9 MB total.

| File | Size | SHA-256 |
| --- | --- | --- |
| `data/Human CS stages 02.tif` | 17.9 MB | `540d4e6411136b3e…` |

Full checksums, original filenames and the source article id for every file are in [`MANIFEST.json`](MANIFEST.json).

## Notes for anyone using this

- A single multi-page TIFF covering several Carnegie stages. An image stack rather than a mesh.
- Deposited at Oxford ORA, which runs on Figshare infrastructure, so the same API serves it.

## Verifying the mirror

```sh
# every file, against the manifest
python3 -c "import json,hashlib,pathlib;m=json.load(open('MANIFEST.json'));[print(('ok  ' if hashlib.sha256(pathlib.Path(f['path']).read_bytes()).hexdigest()==f['sha256'] else 'BAD ')+f['path']) for f in m['files'] if pathlib.Path(f['path']).exists()]"
```

---

Mirrored 2026-11-21 by `tools/mirror.ts` from [embryogenesis](https://github.com/embryogenesis/embryogenesis). The licence of each source article was checked against the live Figshare metadata before download.
