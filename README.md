# sha2-wasm

Implmentation of SHA2 hash functions in WebAssembly. Uses the text format of
WASM as used by [WebAssembly/sexpr-wasm-prototype][expr]. To try it, run

    test/run-d8.py --spec sha2.wasm 

from the sexpr-wasm-prototype directory.

[expr]: https://github.com/WebAssembly/sexpr-wasm-prototype
