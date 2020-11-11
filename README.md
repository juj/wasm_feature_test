# wasm_feature_detect

This repository contains small JS code snippets that can be used to feature detect different WebAssembly subfeatures:
 - https://webassembly.org/roadmap/
 - https://github.com/WebAssembly/website/issues/214

This repository is similar to https://github.com/GoogleChromeLabs/wasm-feature-detect, but emphasis based on educating how the tests are performed, and intended to be easily embeddable to external code by easily copy-pasting the code (rather than needing to set up a npm ecosystem).

All the feature tests operate synchronously.

Try online:
 - [sign extend](http://clb.confined.space/wasm_feature_detect/sign_extend.html)
 - Nontrapping fp-to-int: TODO
 - [mutable globals](http://clb.confined.space/wasm_feature_detect/mutable_globals.html)
 - [bulk memory](http://clb.confined.space/wasm_feature_detect/bulk_memory.html)
 - BigInt: TODO
 - Multivalue: TODO
 - Reference types: TODO
 - SharedArrayBuffer + Atomics: TODO
 - Exceptions: TODO
 - SIMD128: TODO
 - Tail calls: TODO
 - [4gb wasm memory](http://clb.confined.space/wasm_feature_detect/4gb_wasm_memory.html)
