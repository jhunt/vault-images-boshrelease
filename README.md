Vault Docker Images BOSH Release
================================

This BOSH release packages the Vault images (specifically v1.0.2)
as offline exports (via `docker save`) that can be loaded into a
running Docker daemon (via `docker load`) for air-gapped Vaulty
goodness.

For the most part this is a proof-of-concept.  PRs welcome at
this time, but if you are using this for some reason, do let me
know!
