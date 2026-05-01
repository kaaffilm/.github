# kaaffilm

## MK10-PRO v1.0.3

Deterministic pre-delivery truth infrastructure for audiovisual mastering.

MK10-PRO produces cryptographically verifiable Master Truth Bundles and exposes a bounded public package surface.

| Surface | Public location | Role |
| --- | --- | --- |
| Source truth | https://github.com/kaaffilm/MK10-PRO | maintained repository |
| Release | https://github.com/kaaffilm/MK10-PRO/releases/tag/v1.0.3 | signed v1.0.3 release |
| PyPI | https://pypi.org/project/mk10-pro/ | canonical runtime witness |
| NPM | https://www.npmjs.com/package/@kaaffilm/mk10-pro | public registry discovery surface |
| GitHub Packages | https://github.com/kaaffilm/MK10-PRO/pkgs/npm/mk10-pro | package-surface mirror |

Canonical runtime proof:

```bash
pip install mk10-pro==1.0.3
mk10 proof
mk10 boundary
mk10 witness
````

Version lock:

```text
MK10-PRO public package surfaces are locked at 1.0.3.
Do not raise the public package version to repair an immutable registry artifact.
```

Boundary:

```text
MK10-PRO verifies deterministic pre-delivery truth infrastructure.

It does not verify playback, device compatibility, venue certification,
operator trustworthiness, post-delivery behavior, or business outcome.
```

