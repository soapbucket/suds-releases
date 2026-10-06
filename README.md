# Suds binary releases

This repository distributes signed Suds binaries and their verification bundles.
Suds source code is maintained privately. No source checkout or build credential
is included in this repository.

Published downloads appear on the [releases page](https://github.com/soapbucket/suds-releases/releases).
There are no published versions yet.

Artifact signing stays in the Suds source repository. Verify each download with
its matching Sigstore bundle, the issuer
`https://token.actions.githubusercontent.com`, and the exact release identity
`https://github.com/soapbucket/suds/.github/workflows/release.yml@refs/tags/v<VERSION>`.
The artifact repository name is different from the signing identity.

Published artifact bytes are immutable. A correction receives a new release
version rather than replacing an existing download.
