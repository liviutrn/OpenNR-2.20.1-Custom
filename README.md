# OpenNR 2.20.1 Custom

Clean custom-build workspace based exclusively on upstream OpenNR 2.20.1.

## Versioning

- `2.20.1-v00` — clean baseline, no custom OpenNR code modifications.
- `2.20.1-v01` — first custom revision.
- `2.20.1-v02` — second custom revision.
- Versions are never reused or overwritten.

Each version must document:

- exact upstream/base commit;
- previous custom version;
- complete modification summary;
- files changed and why;
- performance/quality implications;
- known issues and test status;
- build commit and package hashes.

## DLSS-NR carrier

`nvngx_dlssnr.dll` is not stored in this public repository or build artifacts. Copy your own carrier into `Shaders/Upscaling/Streamline/` after downloading a build.

## Baseline

Upstream OpenNR 2.20.1 tag commit: `9b6340870f3910d81917f167245885b50216654f`.
