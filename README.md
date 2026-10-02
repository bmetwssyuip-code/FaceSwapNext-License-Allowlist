# FaceSwapNext License Allowlist

This public repository is the read-only authorization endpoint for FaceSwapNext commercial clients.

- `allowlist.json` contains only SHA-256 device identifiers, activation status, timestamps, and an RSA signature.
- It contains no application source, private signing key, password, OAuth token, or customer media.
- Clients reject every edit that is not signed by the offline FaceSwapNext release key.
- Public visibility permits unauthenticated HTTPS reads; it does not grant write access.

The private signing key must remain offline in the owner's removable-drive source backup and must never be committed here.
