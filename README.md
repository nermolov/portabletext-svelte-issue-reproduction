# @portabletext/svelte issue reproduction

```
npm run build

> svelte-latest-check@0.0.1 build
> vite build


vite v4.4.9 building SSR bundle for production...
✓ 33 modules transformed.
✓ built in 267ms
[commonjs--resolver] Failed to resolve entry for package "@portabletext/svelte". The package may have incorrect main/module/exports specified in its package.json.
error during build:
Error: Failed to resolve entry for package "@portabletext/svelte". The package may have incorrect main/module/exports specified in its package.json.
    at packageEntryFailure (file:///home/nik/playground/cdc/svelte-latest-check/node_modules/vite/dist/node/chunks/dep-df561101.js:28691:11)
    at resolvePackageEntry (file:///home/nik/playground/cdc/svelte-latest-check/node_modules/vite/dist/node/chunks/dep-df561101.js:28688:5)
    at tryNodeResolve (file:///home/nik/playground/cdc/svelte-latest-check/node_modules/vite/dist/node/chunks/dep-df561101.js:28419:20)
    at Object.resolveId (file:///home/nik/playground/cdc/svelte-latest-check/node_modules/vite/dist/node/chunks/dep-df561101.js:28180:28)
    at Object.handler (file:///home/nik/playground/cdc/svelte-latest-check/node_modules/vite/dist/node/chunks/dep-df561101.js:48234:19)
    at file:///home/nik/playground/cdc/svelte-latest-check/node_modules/rollup/dist/es/shared/node-entry.js:25461:40
    at async PluginDriver.hookFirstAndGetPlugin (file:///home/nik/playground/cdc/svelte-latest-check/node_modules/rollup/dist/es/shared/node-entry.js:25361:28)
    at async resolveId (file:///home/nik/playground/cdc/svelte-latest-check/node_modules/rollup/dist/es/shared/node-entry.js:24035:26)
    at async ModuleLoader.resolveId (file:///home/nik/playground/cdc/svelte-latest-check/node_modules/rollup/dist/es/shared/node-entry.js:24449:15)
    at async Object.resolveId (file:///home/nik/playground/cdc/svelte-latest-check/node_modules/vite/dist/node/chunks/dep-df561101.js:7910:10)
```
