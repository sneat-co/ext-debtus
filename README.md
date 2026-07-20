# ext-debtus

Public contract repository for the Sneat Debtus extension.

`frontend/` owns and publishes `@sneat/extension-debtus-contract`. It contains
only stable models, service interfaces, injection tokens, and pure helpers.
The private `debtus` repository owns all runtime providers, UI, applications,
and deployment configuration.

Debtus bot controller/view code and bot-framework adapters are implemented in
[`sneat-co/sneat-bots`](https://github.com/sneat-co/sneat-bots) under
`extensions/debtus/`. Changes to this contract that affect Debtus backend
workflows or bot-facing models must consider that implementation as well.

## Publish

Pushing to `main` builds and publishes the package through the shared
`sneat-co/cicd` workflow.
