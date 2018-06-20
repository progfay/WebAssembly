# WebAssembly

getting started [WebAssembly](https://webassembly.org/getting-started/developers-guide/) with C

```bash
$ emcc hello.c -s WASM=1 -o hello.html
$ emrun --no_browser --port 8080 .
```
