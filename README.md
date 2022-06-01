# structurae-test

## Test

For reporting an import error while importing [zandaqo/structurae](https://github.com/zandaqo/structurae)

```sh
pnpm install 
pnpm test

# or
# npm install
# npm
```

The error that occurs is:

```
Error [ERR_PACKAGE_PATH_NOT_EXPORTED]: No "exports" main defined in /tmp/structurae-test/node_modules/structurae/package.json
    at new NodeError (node:internal/errors:371:5)
    at throwExportsNotFound (node:internal/modules/esm/resolve:453:9)
    at packageExportsResolve (node:internal/modules/esm/resolve:669:7)
    at resolveExports (node:internal/modules/cjs/loader:482:36)
    ...
```
