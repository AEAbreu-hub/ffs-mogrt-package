# WKND Product Showcase — sample MOGRT package

Example **Motion Graphics Template** package for **Dynamic Graphics Render** (DGR) on Adobe Firefly Services: the WKND Product Showcase sample used with the Audio/Video API.

## What’s in this repository

**Layout:** Sample assets live at the **repository root** (flat layout), with a `Documentation/` folder for the hand-off PDF.

- **Templates:** `DGR-Demo-MOGRT_WKND-Product-Showcase_Beginner.mogrt` and `DGR-Demo-MOGRT_WKND-Product-Showcase_Advanced.mogrt`
- **Sample payloads:** `DGR-Demo-MOGRT_WKND-Product-Showcase_Beginner.json`, `DGR-Demo-MOGRT_WKND-Product-Showcase_Advanced.json`, and `DGR-Demo-MOGRT_WKND-Product-Showcase_Beginner.csv`
- **Data:** `Data_Beginner_*` and `Data_Advanced_*` CSVs (1-, 4-, and 10-row variants, including localized beginner/advanced where applicable)
- **Media:** `Music_*.wav`, `Video_*.mp4`, `Photo_*`, `Product_*`
- **Fonts:** `SourceSans3-Bold.ttf`, `SourceSerif4-Bold.ttf`
- **Documentation:** `Documentation/DGR-Demo-MOGRT_WKND-Product-Showcase - Documentation.pdf` — full property matrix and hand-off notes (motion design → automation)

## How to get the files

### Clone

```bash
git clone https://github.com/AEAbreu-hub/ffs-mogrt-package.git
cd ffs-mogrt-package
```

Use branch `main` unless your team points you at another branch.

### Download archive (optional)

If a [GitHub Release](https://github.com/AEAbreu-hub/ffs-mogrt-package/releases) publishes a `.zip`, use that release page for a single download instead of cloning. When present, the README for that release will list contents or checksums for verification.

## Access

This repository is **public** on GitHub. No org membership or special approval is required to clone or download public artifacts. If the repo visibility changes, this section should be updated to match consumer docs.

## Beginner vs Advanced

- **Beginner** — `DGR-Demo-MOGRT_WKND-Product-Showcase_Beginner.mogrt` — simpler template and data paths for first integrations.
- **Advanced** — `DGR-Demo-MOGRT_WKND-Product-Showcase_Advanced.mogrt` — extended layout and data for deeper automation scenarios.

Pair each MOGRT with the matching `Data_*` and payload files from the same package.

## Developer documentation

- **Audio/Video API — WKND sample MOGRT:** [WKND sample MOGRT guide](https://developer.adobe.com/audio-video-firefly-services/guides/dgr/dgr-sample-mogrt-wknd/)  
  (Adjust the URL if the published path on developer.adobe.com differs.)

## Large files and Git

This package stays **under GitHub’s 100 MB per-file limit** in normal use. If future assets exceed that, use [Git LFS](https://git-lfs.github.com/) or a [Release ZIP](#download-archive-optional) instead of committing huge blobs to `main`.

## Contributing

Changes are expected to go through pull requests. Default reviewers are configured via `.github/CODEOWNERS` when branch protection requires code owner review.
