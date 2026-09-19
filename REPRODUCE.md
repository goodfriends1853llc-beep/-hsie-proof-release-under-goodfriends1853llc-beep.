# Reproduce the HSIE ANAT Reference Proof

**Reproduction kit:** `HSIE_ANAT_PHASE6_REPRO_KIT_v1.0.0.zip`  
**Expected SHA-256:** `dcf8491595c92c73706b20bbabdc61edc4661f23d24bc91441918f36181ce643`

## Independence boundary

A run is independent only when a genuinely independent person or team performs it in an environment they control.

A second run by the original builder, assistant, or owner is repeatability evidence—not independent reproduction.

## Procedure

1. Obtain `HSIE_ANAT_PHASE6_REPRO_KIT_v1.0.0.zip`.
2. Compute SHA-256 and verify it equals:

   `dcf8491595c92c73706b20bbabdc61edc4661f23d24bc91441918f36181ce643`

3. Unpack the archive into a clean directory.
4. Read the included `REPRO_MANIFEST.json` and `REPRODUCE.md`.
5. Verify the unpacked file hashes before changing anything.
6. Run the unchanged test suite exactly as documented in the kit.
7. Run PT-001 exactly as documented.
8. Preserve stdout, stderr, environment details, failures, reruns, and deviations.
9. Do not overwrite a failed first run after a correction.
10. Report PASS, FAIL, PARTIAL, or INCONCLUSIVE with evidence.

## Expected reference behavior

The originating internal reference run produced:

- 109 / 109 tests PASS
- PT-001 11 / 11 PASS
- accepted PT-001 receipt hash:
  `224ea5793b49576c565ff35c06c077ec9d098a840796e99cef5bd351e48c6962`

A reproducer should report any behavioral disagreement rather than altering the implementation to force agreement.

## What a successful reproduction would mean

A valid independent PASS would establish independent reproduction for this bounded implementation and procedure.

It would not establish production reliability, field effectiveness, real financial settlement, physical-world effect validation, constitutional authority, standards certification, or universal fitness.
