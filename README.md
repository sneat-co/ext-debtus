# ext-debtus

Public contract repository for the Sneat Debtus extension.

`frontend/` owns and publishes `@sneat/extension-debtus-contract`. It contains
only stable models, service interfaces, injection tokens, and pure helpers.
The private `debtus` repository owns all runtime providers, UI, applications,
and deployment configuration.

## Publish

Pushing to `main` builds and publishes the package through the shared
`sneat-co/cicd` workflow.
