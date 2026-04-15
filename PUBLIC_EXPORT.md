# Public example export

This directory is a generated export of the `omnikernel` example.

It is intended to be mirrored into a read-only example repository. Framework
dependencies are rewritten to package-specific public npm versions, while
example-local modules stay as local `file:` dependencies.

Do not edit the mirror repository directly. Change the source example in
`NestDevLab/nestjs-yalc`, regenerate the export, and sync the mirror.

Regenerate it from the framework monorepo with:

```bash
npm run examples:export
```
