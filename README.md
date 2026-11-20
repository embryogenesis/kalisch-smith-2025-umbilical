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

The atlas's maternal layer currently models the cord as a schematic helix with an invented pitch, which is on the list of things this project made up. This is real staged geometry for the structure and the obvious way to replace an invention with a measurement.

## Contents

1 file(s), 17.9 MB total.

| File | Size | SHA-256 |
| --- | --- | --- |
| `data/Human CS stages 02.tif` | 17.9 MB | `540d4e6411136b3e…` |

Full checksums, original filenames and the source article id for every file are in [`MANIFEST.json`](MANIFEST.json).

## Notes for anyone using this

- A single multi-page TIFF covering Carnegie stages, not a mesh. Image stack, so expect to segment it.
- Deposited at Oxford ORA, which runs on Figshare infrastructure, so the same API serves it.

## Verifying the mirror

```sh
# every file, against the manifest
python3 -c "import json,hashlib,pathlib;m=json.load(open('MANIFEST.json'));[print(('ok  ' if hashlib.sha256(pathlib.Path(f['path']).read_bytes()).hexdigest()==f['sha256'] else 'BAD ')+f['path']) for f in m['files'] if pathlib.Path(f['path']).exists()]"
```

## Why this mirror exists

It is part of [embryogenesis](https://github.com/embryogenesis/embryogenesis), an interactive atlas of embryological development and the biodynamic-osteopathic "fluid body".

The atlas exists because the best segmented human embryo geometry in the world is licensed CC BY-NC-ND and therefore cannot be redistributed by anyone. The lesson of that is not that licences are inconvenient but that **availability is not permanence**: a deposit can be superseded, re-licensed or lost with its repository. Where a depositor has chosen CC BY they have explicitly permitted redistribution, and taking them up on it — with a checksum on every byte — is the cheapest insurance there is against that geometry becoming as unavailable as the geometry we already cannot use.

If you are one of the depositors and would like something changed or removed, open an issue; the request will be honoured regardless of what the licence permits.

---

Mirrored 2026-11-20 by `tools/mirror.ts` in the atlas repository, which re-verifies the licence of every article against the live Figshare metadata before downloading anything and aborts on a mismatch.
