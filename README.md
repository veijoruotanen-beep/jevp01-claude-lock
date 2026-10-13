# JEV-P 01 / Claude – pre-draw forecast lock commitment

- Project: JEV-P 01 / Claude (independent, blinded Eurojackpot predictability study)
- Target draw: Eurojackpot 2026-10-13 (first prospectively evaluated draw)
- Data cutoff: 2026-10-09 (997 draws; source CSV git blob SHA-1 ad9a72561e231c584adc7746a7d17431775f8da0)
- Local lock time: 2026-10-13T09:45:56+03:00

SHA-256 of `LOCK_MANIFEST.sha256` (the manifest lists SHA-256 hashes of the forecast,
model parameters, preregistration, data and the source code needed to run the model):

```
9ed0ed340c5d4932c43083d680195834aeb4941767b0a381c51247522bc73536
```

Verification once the files are released: `shasum -a 256 LOCK_MANIFEST.sha256` must print the
hash above, and `shasum -a 256 -c LOCK_MANIFEST.sha256` must report OK for every listed file.

This commitment publishes no forecast content. It is not a betting recommendation.
