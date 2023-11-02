# wasm_feature_test

This repository contains small JS code snippets that can be used to feature detect different WebAssembly subfeatures:
 - https://webassembly.org/roadmap/
 - https://github.com/WebAssembly/website/issues/214

This repository is similar to https://github.com/GoogleChromeLabs/wasm-feature-detect, but emphasis based on educating how the tests are performed, minimal code size, and intended to be easily embeddable to external JS code by easily copy-pasting the code (rather than needing to set up a npm ecosystem).

With the exception of BigInt test, which must operate asynchronously, all other feature tests operate synchronously.

## Run live

 - [sign extend](sign_extend.html)
 - [Nontrapping fp-to-int](nontrapping_fptoint.html)
 - [mutable globals](mutable_globals.html)
 - [bulk memory](bulk_memory.html)
 - [BigInt](bigint.html)
 - Multivalue: TODO
 - Reference types: TODO
 - SharedArrayBuffer + Atomics: TODO
 - [WebAssembly Native Exceptions](wasm_exceptions.html)
 - [simd128](simd.html)
 - Tail calls: TODO
 - [4gb wasm memory](4gb_wasm_memory.html)

## License

Public domain. Do not attribute back. Copy-paste to your project.
