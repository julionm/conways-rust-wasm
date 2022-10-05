# conways-rust-wasm
Conways Game of Life Tutorial with Rust and WebAssembly

The Tutorial is available through this link: https://rustwasm.github.io/docs/book/introduction.html

`wat` extension is for S-expression based Web Assembly code
`wasm` is the bytecode version of it

The Web Assembly code has access to a linear memory on the browser where everything will be stored,
thus JS have access to it from the `pkg/*_bg` file, enabling Rust to pass pointers to data structures
instead of the structure itself.

### TODO

- [ ] Implement the tests
- [ ] Continue to learn
- [ ] Study hashlife to improve the algorithm
- [ ] Improve UI of the web side
- [ ] (Opt.) Toy a little with these animation frames
