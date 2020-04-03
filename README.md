# Example with WebAssembly source maps

## Preview

Go to https://ksxgithub.github.io/wasm-source-map-emscripten/pi.html, open DevTools, open "Source" tab.

## Development

### Prepare emcc

- Install emsdk and activate incoming version.
- If needed, `source emsdk_env.sh`

### Build

```
make
```

### Testing

Open in Firefox Nightly via local server at http://localhost:8000/pi.html

(At the moment try with `devtools.debugger.new-debugger-frontend=false`)
