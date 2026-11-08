# industrial-surface-defect-detection

Dataset zip for Industrial Surface Defect Detection (SurfaceGuard AI), split into parts because GitHub blocks single files over 100 MB and the account's Git LFS budget is full.

Original file: `industrial-surface-defect-detection.zip` (367 MB, 14,395 files: public/train, public/test, public/train.csv, public/sample_submission.csv)

## Rebuild the zip
Download all files in `parts/`, then in that folder run:

```bash
cat industrial-surface-defect-detection.zip.part* > industrial-surface-defect-detection.zip
sha256sum industrial-surface-defect-detection.zip
# should match SHA256.txt in this repo
```

Then unzip as normal.
