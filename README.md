```bash
pnpm add -D github:cooolbros/hello-wasm-test#path:/packages/hello-wasm
```

```bash
pnpm approve-builds
```

error: linking with `link.exe` failed: exit code: 1104

Currently fails if any file path passed to `link.exe` is longer than 256 characters

`hello-wasm/package.json` does not declare entry point (`main`, `types` or `files`)
