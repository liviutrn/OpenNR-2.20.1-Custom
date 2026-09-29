# Custom source patches

This folder contains only the source changes introduced by custom OpenNR versions.

Rules:

1. `2.20.1-v00` has no `.patch` files and is the clean baseline.
2. Every later version adds or updates explicitly documented `.patch` files.
3. Patch names use the version first, for example `2.20.1-v01-gaze-stabilization.patch`.
4. Every patch must also be described in that version's file under `versions/`.
5. No version number is reused or silently overwritten.
6. The build workflow verifies each patch with `git apply --check` before applying it.

This keeps the exact differences from upstream OpenNR 2.20.1 directly inspectable.
